# WeexEros
基于 WeexSDK 实现的 iOS工程，可结合 BMFE_scaffold 脚手架快速开始开发 App，完整的文档请看这里 [weex-eros]( https://karynsong.gitbooks.io/weex-eros/content/ )

## WeexEros 是什么
WeexEros 是由本木前端团队基于 [Weex](https://github.com/apache/incubator-weex) 创建的 iOS 工程，基于此工程我们已经开发并上架了两款 App。如果你恰巧也在学习weex，或者在使用 weex 中遇到了一些问题，那么可以参考一下本工程，你可以将其作为 iOS 工程模板快速开发基于 Weex 的 App。（ps:如您发现哪里写的有问题，或需要优化，欢迎提issues，谢谢!）

## WeexEros 能实现哪些功能
使用 WeexEros 可以将所有业务相关代码都放到 js 端来实现，native端工程只提供基础功能不侵入业务，我们在 Weex 的基础上扩展了一套适合在项目中使用的 [Module](https://weex.incubator.apache.org/cn/references/advanced/extend-to-ios.html)、[Component](https://weex.incubator.apache.org/cn/references/advanced/extend-to-ios.html)供 js 端调用，并且已经集成在工程中。还实现了一些大多数 App 都需要用到的功能；

- 从本地（App沙盒）加载 js 资源文件，白屏时间控制在百毫秒内；
- js 资源文件热更新机制，支持 diff 差分包；
- 消息推送；
- 第三方支付（目前只实现了微信支付）；
- 社区化分享;
- 获取当前位置坐标；
- 高德地图；
- 设置全局字体大小；
- 第三方登录（目前只实现了微信登录）；
- 发送网络请求，支持GET、POST,自定义 RequestHeaders;
- 扫一扫；
- 拍照、相册选择图片，支持多选；
- 图片上传，支持多种；
- 图片浏览器；
- 消息中心机制；
- alert、confirm、toast、loading 提示框；
- 原生导航栏，支持自定义按钮，显隐设置；
- 封装了Router，页面跳转支持push、present，支持页面间传值；
- 打开WebView页面；
- 数据本地存储；
- 富文本（目前只支持不同样式的文字）；

## 运行项目
项目中内置了简易 demo，只需简单几步即可查看效果，首先假设你已经完成了安装 iOS 开发环境 和 CocoaPods

- clone项目：`git clone https://github.com/xiaohuapunk/WeexEros.git`

- cd到工程目录执行文件：`./install.sh`

执行完成之后会自动打开 Xcode，运行项目即可；

## 感谢
感谢所有项目中用到的第三方SDK作者，感谢你们。