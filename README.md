# mui

### 下拉刷新结束

```javascript
function pullfresh-function() {
     //业务逻辑代码，比如通过ajax从服务器获取新数据；
     ......
     //注意，加载完新数据后，必须执行如下代码，注意：若为ajax请求，则需将如下代码放置在处理完ajax响应数据之后
     //没有更多内容了，endPulldown 传入true， 不再执行下拉刷新
     mui('#refreshContainer').pullRefresh().endPulldownToRefresh();
}
```
