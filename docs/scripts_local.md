# 本地开发
> Nobita 框架热更新的是 nobita-scripts，当然也能换其他的守护模块。

## nobita-scripts 配置
- package.json
```
{
  ...
  "scripts": {
    "local": "ns local ./app.js",
  },
  ...
}
```

- local \[app.js\](启动本地开发)
  - --ignored [value] 忽略文件, 多个文件逗号隔开。


> Ctrl + C 关闭进程