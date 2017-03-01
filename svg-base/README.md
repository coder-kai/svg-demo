# 1.SVG-demo
## 1.svg中的viewBox属性，和width及height之间的影响
* 1.viewBox的值大于width和height的值，内容区域在width和height之内
* 2.viewBox的值大于width和height的值，内容区域在viewBox之内

## 2.svg正方形属性
* 1.标签rect \<rect x="0" y="0" width="100" height="100" fill="#2d87f9" stroke="#ccc" stroke-width="5" rx="5" ry="5"/>
* 2.svg是网格系统，左上角为圆心坐标（0,0）其中x,y相对于左上角的位置坐标，width和height是高度。
* 3.fill是填充的背景色，stroke是边线颜色，cx，cy分别是圆角

## 3.svg圆形属性
* 1.\<circle cx="25" cy="75" r="20" stroke="red" fill="transparent" stroke-width="5"/>
* 2.cx和cy是圆心坐标的位置，r是半径
* 3.fill是填充的背景色，stroke是边线颜色。

## 4.svg椭圆属性
* 1.\<ellipse cx="75" cy="75" rx="20" ry="5" fill="transparent" stroke-width="5"/>
* 2.cx和cy是椭圆的圆心坐标的位置，rx，ry分别是长轴或短轴的长度
* 3.fill是填充的背景色，stroke是边线颜色。

## 5.线段
* 1.\<line x1="10" x2="50" y1="110" y2="150" stroke="orange" stroke-width="5"/>
* 2.x1和y1是起点坐标，x2和y2是终点坐标。只能有2组值
* 3.fill是填充的背景色，stroke是边线颜色。

## 6.折线Polyline
* 1.\<polyline points="00 00,100 100,200 00, 200 200" stroke="orange" stroke-width="5"/>
* 2.存在多组值
* 3.fill是填充的背景色，stroke是边线颜色。

## 7.多边形Polygon
* 1.\<polygon points="00 00,100 100,200 00, 200 200" stroke="orange" stroke-width="5"/> 
* 2.存在多组值，自动回折回起点
* 3.fill是填充的背景色，stroke是边线颜色。

## 8.路径(Path)曲线
* 1.\<path d="M10 10 H 90 V 90 H 10 L 10 10"/>
* 2.存在多组值，自动回折回起点
* 3.fill是填充的背景色，stroke是边线颜色。

# 2.SVG的元素参考（好多有没有）[参考地址](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Element)

![](http://upload-images.jianshu.io/upload_images/2604175-a9e4fb3e68f7c658.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 3.SVG的属性参考（好多有没有）[参考地址](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Attribute)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/2604175-ea42d52690969538.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 4.svg文档对象模型  [参考地址](https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model#SVG_interfaces)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/2604175-db8fa6dc688aa8c5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 5.svg文档对象模型  [参考地址](https://developer.mozilla.org/zh-CN/docs/Web/API/Document_Object_Model#SVG_interfaces)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/2604175-db8fa6dc688aa8c5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

# 6.svg在html中的使用效果 [参考地址](https://developer.mozilla.org/zh-CN/docs/Web/SVG/Applying_SVG_effects_to_HTML_content)

![Paste_Image.png](http://upload-images.jianshu.io/upload_images/2604175-2d65c9a9d5f98614.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)




