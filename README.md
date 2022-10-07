# xstate-viz 状态机可视化本地部署

- 可直接静态部署，建议用 vscode 的 liveserver 或 utool 的 liveserver，或者 nginx 部署

- 网页直接调用可以直接编辑测试状态机

- 若需要项目接入测试，项目内设置 inspect:

```javascript
inspect({
  iframe: document.getElementById("xstate-inspect"), //展示的位置，默认是新打开页
  url: "http://127.0.0.1:6600/index.html?inspect&panel=false",
});
```
