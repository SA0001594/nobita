
# 更新日志
---

- 如果发现新的问题无法解决， 欢迎提交 [Nobita issue](https://github.com/nobitajs/nobita/issues)
- 定期更新

## v0.8.8
  - 去冗余，删除不必要的加载。
  - 增加 ready.js 可启动完成前执行。

## v0.8.5
  - 修复 helper.js 不存在产生的bug。
  - 增加启东时判断 router 是否存在。
  - 增加 定时任务 启动异常抛出错误。

## v0.8.3
  - 修复 mongo 密码登陆bug。

## v0.8.2
  - 修复 中间件 与 定时任务冲突bug。[#3](https://github.com/nobitajs/nobita/issues/3)

## v0.8.1
  - 更新 nobita 内部执行方式。

## v0.7.9
  - 修复 prod 环境打不出 logger 日志。
  - 增加 允许查看日志文件 [查看](/logger?id=允许查看日志文件)

## v0.7.7
  - nobita-curl 修复 headers 为空的错误。
  - 增加 定时任务 [查看](/schedule)

## v0.7.4
  - 修改 mysql 使用方式，引入 sequelize 插件。[查看](/mysql)
  - config.{env}.js 增加函数式调用。[查看](/config?id=函数式引入)

## v0.7.2
  - 修改文件路径 app/middleware 改为 app/middlewares，但也兼容 app/middleware。
  - app.middlewares 可读取所有中间件函数。
  - 增加路由引入对应的中间件。[查看](/middleware?id=路由引入)

## v0.6.9
  - 修改中间件加载方式，match、ignore增加传入方式。

## v0.6.7
  - 修复 error 错误输出捕抓逻辑。
  - 修复 logger 本地开发时报错。

## v0.6.6
  - 增加 catch 错误 UI。
  - 增加 favicon 网页小图标。

## v0.6.1
  - nobita-catch 返回 json 改改成返回 stack。
  - 增加 request 和 response 事件。

## v0.6.0
  - 增加插件 nobita-catch 异常处理，捕获 50x 错误。
  - 增加线上链接 _debug=1 即可输出错误信息。
