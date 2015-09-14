# hexagon
css3 hexagon with rounded corners and borders.    
css3六边形，可设置border与border-radius

## result

view [demo here](http://tarobjtu.github.io/hexagon/index.html)

### capture
![demo capture](https://raw.githubusercontent.com/tarobjtu/hexagon/master/demo_capture.png)

### size and border-width

You can change the size and border-width of hexagon by scale.

#### To change here at css file.

```css
 -webkit-transform: rotate(-30deg) skewX(30deg) scale(0.5);
  -moz-transform: rotate(-30deg) skewX(30deg) scale(0.5);
  -ms-transform: rotate(-30deg) skewX(30deg) scale(0.5);
  -o-transform: rotate(-30deg) skewX(30deg) scale(0.5);
  transform: rotate(-30deg) skewX(30deg) scale(0.5);
```

```css
  -webkit-transform: rotate(-30deg) skewX(30deg) scale(0.46);
  -moz-transform: rotate(-30deg) skewX(30deg) scale(0.46);
  -ms-transform: rotate(-30deg) skewX(30deg) scale(0.46);
  -o-transform: rotate(-30deg) skewX(30deg) scale(0.46);
  transform: rotate(-30deg) skewX(30deg) scale(0.46);
```

#### To change here at less file.

```less
@inner-scale : 0.46;
@outter-scale : 0.5;
```