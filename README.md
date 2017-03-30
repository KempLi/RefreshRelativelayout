# RefreshRelativelayout
适用于Android平台的拖动刷新控件，支持API 14以上版本的android系统。通过配置orientation属性设置水平方向拖动刷新还是竖直方向下拉刷新或者加载更多等，
另外可以通过实现IRefresher接口实现自定义的刷新header，以适用于实际场景中，并设置了刷新回调接口等。另外还解决了可能存在的滑动冲突的问题，保证嵌套滑动的时候互不影响。
先看实际效果图（效果图较大，工程实际只有300k）。
## Demo
###### 竖直方向嵌套
![vertical](demoGif/vertical.gif)
###### 水平方向嵌套
![horizontal](demoGif/horizontal.gif)
###### 混合嵌套
![mixed](demoGif/mixed.gif)