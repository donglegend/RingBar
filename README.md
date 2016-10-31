# RingBar(圆环进度条，canvas实现)
依赖jQuery，简单改写即可不依赖，如有必要，请自行修改


## demo效果预览

## 使用说明
引入RingBar.js之后，即可使用
```
var Bar = new RingBar($("#box"), {
	radius: 50, // 半径，默认50
	barWidth: 10, // 圆环宽度，默认10
	barBgColor: '#cccccc', // 圆环背景色，默认'#cccccc'
	barColor: '#4691e2', // 圆环颜色，默认'#4691e2'
	fontColor: "#4691e2", // 内部文本颜色，默认'#4691e2'
	fontFamily: "微软雅黑", // 内部文本字体，默认"微软雅黑"
	fontWeight: 'bold', // 字体加粗，默认bold
	fontSize: 14, // 字体大小，默认14
	percent: 80, // 进度百分比，默认 80
	animate: true // 是否需要动画，默认 true
});
```
