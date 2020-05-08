# Awesome-Deno 中文

> 一份精心编辑的 [Deno](https://github.com/olivewind/awesome-deno-cn) 相关清单。

- [文档](#docs)
    - [官方文档](#官方文档)
    - [社区文档](#社区文档)
- [模块](#模块)
- [工具](#工具)
- [文章](#文章)
- [演讲](#演讲)
- [新闻](#新闻)
- [其它语言的资源](#其它语言的资源)
  - [中文](#中文)
  - [希伯来语](#希伯来语)
  - [日语](#日语)
  - [韩语](#韩语)
  - [俄语](#俄语)

# 文档

### 官方文档

- [官方网站 (deno.land)](https://deno.land)
- [Deno API 类型文档](https://deno.land/typedoc/)
- [Deno 手册](https://deno.land/manual.html)
- [Deno 仓库](https://deno.land/x/)

### 社区文档

- [Deno 的设计核心指南 (设计 & 给贡献者)](https://denolib.gitbook.io/guide/) (⚠ 过期)
- [Deno 的 V8 文档](https://denolib.github.io/v8-docs/)

### 在线玩具

- deno-play.app (⚠ 证书问题)
- [deno.town](https://deno.town)

# 模块

__注意__: Deno有一些官方模块可以在[deno_std](https://deno.land/std/)中找到，
如果你有合适的模块可以考虑提交到[deno.land/x](https://github.com/denoland/deno_website2/blob/master/src/database.json)仓库。

- [abc](https://github.com/zhmushan/abc) - 一个更好的用于创建Web应用程序的Deno框架。
- [alosaur](https://github.com/alosaur/alosaur) - Alosaur-具有许多装饰器的Deno Web框架。
- [bytes_formater](https://github.com/manyuanrong/bytes_formater) - 格式化字节（Uint8Array，ArrayBufferView ...）输出，在调试IO功能时很有用。
- [cac](https://github.com/cacjs/cac) - 用于构建命令行应用程序的简单但功能强大的框架。
- [camelcase](https://github.com/denolib/camelcase) - 将破折号/点号/下划线/空格分隔的字符串转换为camelCase：foo-bar→fooBar。
- [colors](https://deno.land/std/fmt/colors.ts) - 用于Deno控制台的颜色基础库。
- [cli-spinner](https://github.com/ameerthehacker/cli-spinners) - 在执行长任务时在终端中显示加载中。
- [csv](https://github.com/hashrock/deno-fnparse/blob/master/parsers/csv.ts) - 一个简单的CSV解析器。
- [dcc](https://github.com/BoltDoggy/deno#dcc) - Deno Cache Clean，在下次运行时重新加载dep。
- [dejs](https://github.com/syumai/dejs) - Deno的ejs模板引擎。
- [denon](https://github.com/eliassjogreen/denon/blob/master/watcher.ts) - 具有for-await generator的文件监视程序
- [deno_case_style](https://github.com/zekth/deno_case_style) - 不同大小写样式的字符串验证器和格式化程序。 例如：camelCase等。
- [deno-checksum](https://github.com/manyuanrong/deno-checksum) - SHA1/MD5算法。
- [deno-deamon](https://github.com/manyuanrong/deno-deamon) - 使Deno程序在后台运行。
- deno-dotenv
    - [pietvanzoen/deno-dotenv](https://github.com/pietvanzoen/deno-dotenv) - .env
    - [cardosomarcos/deno-dotenv](https://github.com/cardosomarcos/deno-dotenv) - 从.env文件中加载 Deno 项目的环境变量。
- [deno-express](https://github.com/NMathar/deno-express) - Node Express移植到Deno。
- [deno-fnparse](https://github.com/hashrock/deno-fnparse) - 一个非常简单的JavaScript解析器组合器。
- [deno-globrex](https://github.com/hayd/deno-globrex) -  globex移植到Deno。
- [deno-mysql](https://github.com/manyuanrong/deno_mysql) - MySQL数据库驱动.
- [deno_mongo](https://github.com/manyuanrong/deno_mongo) - MongoDB数据库驱动.
- [deno-opn](https://github.com/hashrock/deno-opn) - 打开网站，文件，可执行文件之类的东西。 跨平台。
- [deno-plugin-prepare](https://github.com/manyuanrong/deno-plugin-prepare) - 一个用于管理Deno Native插件依赖关系的库
- [deno-pretty-assert](https://github.com/bokuweb/deno-pretty-assert) - 具有颜色输出的断言库。
- [deno-prettystring](https://github.com/OnikurYH/deno-prettystring) - 格式化，修剪和删除字符串中字符之间的多余空白。
- [deno_random_interval](https://github.com/zekth/deno_random_interval) - 生成随机间隔的工具。
- [deno-redis](https://github.com/keroxp/deno-redis) - Redis Client的实验实现。
- [deno-slugify](https://github.com/jcardama/deno_slugify) - Deno的字符串节流器。
- [deno-smtp](https://github.com/manyuanrong/deno-smtp) - 基于SMTP的邮件发送工具。
- [deno_tiny_templates](https://github.com/zekth/deno_tiny_templates) - Deno的模板渲染器。
- [deno_tokenizer](https://github.com/eliassjogreen/deno_tokenizer) - 简单的Deno标记器。
- [deno-using](https://github.com/hayd/deno-using) - Python样式语法。
- [deno-uuid](https://github.com/lucascaro/deno-uuid) - UUID模块。
- [deno-ws](https://github.com/keroxp/deno-ws) - Websocket Server的实验实现。
- [deno-xml-parser](https://github.com/nekobato/deno-xml-parser) - 从segmentio/xml-parser移植的 XML 解析器。
- [dinatra](https://github.com/syumai/dinatra) - Sinatra语法的Deno的轻量级Web应用程序框架。
- [djwt](https://github.com/timonson/djwt) -根据JWT和JWS规范在Deno上创建JSON Web令牌（JWT）。
- [dso](https://github.com/manyuanrong/dso) - 一个基于MySQL的简单ORM库。
- [evt](https://github.com/garronej/evt) - EventEmitter的类型安全替代品。
- [expect](https://github.com/allain/expect) - 类似Jest语法断言测试工具.
- [flags](https://github.com/denoland/deno_std/tree/master/flags) - 基于minimist的命令行参数解析器。
- [gardens](https://github.com/partheseas/gardens) - 一个无处不在的JavaScript日志工具。
- [gentleRpc](https://github.com/timonson/gentleRpc) - 用于Deno和浏览器的JSON-RPC 2.0 TypeScript库。
- [http](https://github.com/denoland/deno_std/tree/master/http) - HTTP模块，包括文件服务器。
- [http-libs](https://github.com/denoserverless/http-libs) - HTTP模块和类型。
- [jwt](https://github.com/denoserverless/jwt) - auth0/jsonwebtoken。
- [lazy](https://github.com/luvies/lazy) - 类似linq的惰性执行迭代模块。
- [log](https://github.com/denoland/deno_std/tree/master/log) - 日志模块。
- [marked](https://github.com/denolib/marked/) - Markdown-to-HTML转换器.
- [ms](https://github.com/denolib/ms) - 轻松地将各种时间格式转换为毫秒。
- [normalize_diacritics](https://github.com/motss/deno_mod/tree/master/normalize_diacritics) - 删除字符串中的重音符号/变音符号。
- [oak](https://github.com/oakserver/oak) - 用于Deno网络服务器的中间件框架。
- [path](https://github.com/denoland/deno_std/tree/master/fs/path) - Deno path操作库。
- [pogo](https://github.com/sholladay/pogo) - Deno的服务器框架。
- [postgres](https://github.com/buildondata/deno-postgres) - PostgreSQL数据库驱动。
- [qs](https://github.com/denolib/qs) - 支持嵌套的querystring解析器。
- [sax-ts](https://github.com/Maxim-Mazurok/sax-ts) - 类似于SAX的XML解析器，来自[sax-js](https://github.com/isaacs/sax-js)
- [servest](https://github.com/keroxp/servest) - 渐进式HTTP服务器/路由器。
- [sql-builder](https://github.com/manyuanrong/sql-builder) - SQL查询语句生成器。
- [textproto](https://github.com/denoland/deno_std/tree/master/textproto)
- [type-fest](https://github.com/denoserverless/type-fest) - 一些必要的TypeScript类型集合(sindresorhus/type-fest)。
- [watch](https://github.com/jinjor/deno-watch) - 文件监听器。
- [webview](https://github.com/eliassjogreen/deno_webview) - Webview的Deno绑定，这是一个用于创建基于Web的桌面GUI的小型库。
- [wu-diff-js](https://github.com/bokuweb/wu-diff-js) - 使用wu(O(NP))算法的Diff库.

# 工具

- [clone](https://github.com/ekaragodin/clone) - 一个方便克隆的简单实用程序。
- [denoget](https://github.com/syumai/denoget) - denoget安装可执行的Deno脚本。
- [denoify](https://github.com/garronej/denoify) - 对于希望支持Deno但不想编写和维护的 npm 模块作者。
- [denoinit](https://github.com/syumai/deno-libs/tree/master/denoinit) - denoinit 为 Deno项目生成有用的文件。
- [denomander](https://github.com/siokas/denomander) -Deno命令行界面的灵感来自 commander.js。
- [denon](https://github.com/eliassjogreen/denon) - 类似 Nodemon
- [denopkg](https://github.com/denopkg/denopkg.com) - 在您的Deno项目中使用来自 GitHub 的代码的更简单方法。
- [denoversion](https://github.com/lucascaro/denoversion) -Deno的 SemVer + Git 版本管理。
- [deno.mk](https://github.com/MarkTiedemann/deno.mk) - 用于安装和运行Deno的跨平台 Makefile。
- maxmcd's [deno-docker](https://github.com/maxmcd/deno-docker) 一个Docker镜像。
- hayd's [deno-docker](https://github.com/hayd/deno-docker) 一些Docker镜像。
- [deno-vscode](https://github.com/ameerthehacker/deno-vscode) - 利用此扩展利用vscode中内置的typedef 和intellisense
- [deno_ls_plugin](https://www.npmjs.com/package/deno_ls_plugin) - 一个TypeScript插件，它将允许Deno之外的TypeScript以类似于在Deno内部进行解析的方式来解析模块。
- [dev_server](https://github.com/zhmushan/dev_server) - 让TypeScript文件直接在script标签中使用。
- [dpm](https://github.com/BoltDoggy/deno#dpm) -Deno软件包管理器，为Deno安装全局命令。 类似 denoget。
- dvm
    - [justjavac/dvm](https://github.com/justjavac/dvm) -Deno版本管理器：管理多个Deno版本。
    - [axetroy/dvm](https://github.com/axetroy/dvm) - 没有运行时相关的Deno版本管理器。
- [elm-live-reload](https://github.com/jinjor/deno-playground/tree/master/elm-live-reload) - 用Deno编写的Elm Live Reloader。
- [nessie](https://github.com/halvardssm/deno-nessie) - 为PostgreSQL，MySQL 和 SQLite创建，迁移和回滚迁移。
- [task-runner](https://github.com/jinjor/deno-task-runner) - 像npm脚本一样编写任务。
- [typescript-deno-plugin](https://github.com/justjavac/typescript-deno-plugin) - Deno语言服务插件，在编辑器中的TypeScript文件中提供智能提示。
- [udd](https://github.com/hayd/deno-udd) - 更新Deno依赖：将导入语句更新为最新发布的版本。
- [vscode-deno](https://github.com/justjavac/vscode-deno) - VS Code扩展，使用typescript-deno-plugin提供Deno支持。
- [packer-provisioner-deno](https://github.com/dontlaugh/packer-provisioner-deno) - 一个Packer插件，可轻松使用Deno脚本构建虚拟机映像。
- [pika deno plugin](https://github.com/pikapkg/builders/tree/master/packages/plugin-build-deno/)

# 文章

- [使用Deno和Visual Studio Code进行开发](https://medium.com/@kitsonk/develop-with-deno-and-visual-studio-code-225ce7c5b1ba)
- [关于Deno（JavaScript / TypeScript 运行时）的初步思考](https://43081j.com/2019/01/first-look-at-deno)
- [Deno入门教程](https://dev.to/wuz/getting-started-with-deno-e1m)
- [什么是Deno，它与Node.js有什么不同？](https://dev.to/bnevilleoneill/what-s-deno-and-how-is-it-different-from-node-js-366g)
- [使用Deno编写一个小型API](https://dev.to/kryz/write-a-small-api-using-deno-1cl0)
- [使用Architect或SAM的AWS Lambda上的Deno](https://blog.begin.com/deno-runtime-support-for-architect-805fcbaa82c3)
- [Deno简介 - NodeJS杀手](https://adarshron.com/introducing-deno)

# 演讲

- [Ryan Dahl - 我为Node.js感到遗憾的10件事 | JSConf EU 2018](https://www.youtube.com/watch?v=M3BM9TB-8yA)
    - [演讲稿](https://tinyclouds.org/jsconf2018.pdf)
- [Ryan Dahl - Deno, 新的服务器端运行时 | JSDC 2018#A01](https://www.youtube.com/watch?v=FlTG0UXRAkE)
    - [演讲稿](https://tinyclouds.org/deno_jsdc.pptx)
- [Ryan Dahl - Deno, 一种新的JavaScript方法 | JS Fest 2019 Spring](https://www.youtube.com/watch?v=z6JRlx5NC9E)
    - [演讲稿](https://www.slideshare.net/JSFestUA/js-fest-2019-ryan-dahl-deno-a-new-way-to-javascript)
- [Rafał Pocztarski — 从Node.js到Deno-使用V8和Rust构建的JavaScript / TypeScript运行时[EN]](https://www.youtube.com/watch?v=Aib1OZLy0_c)
    - [演讲稿](https://gitpitch.com/rsp/ntd/ntd?utm_campaign=Deno%20Newsletter#/)
- [Ryan Dahl: JavaScript和TypeScript的安全运行时 | js.la April 2019](https://www.youtube.com/watch?v=RAmqgbv247s)
    - [演讲稿](https://docs.google.com/presentation/d/1CSQVTeH5tFzE4AZVXIpx9Xwew5YS-gxJZ03eRFtNeIc/edit)
- [Ryan Dahl: Deno, 一种新的JavaScript方法 | HolyJS 2019 Piter](https://www.youtube.com/watch?v=HjdJzNoT_qg)
    - [演讲稿](https://docs.google.com/presentation/d/1BjvZx5S8noVfFINptH4jfKfqh9jB9nXlFC0I3oIDtg4/edit)
- [Rafał Pocztarski - 什么是Deno？ 2020年代用于现代JavaScript和TypeScript后端的新运行时 | Deno Warsaw](https://www.youtube.com/watch?v=aI5A9zvYSjk)
    - [演讲稿](https://gitpitch.com/rsp/wid/wid)
- [Michał Sabiniarz - 如何为Deno做贡献 | Deno Warsaw](https://www.youtube.com/watch?v=LAtjnKLbPpw)
    - [演讲稿](https://docs.google.com/presentation/d/1rETgslJS1ks4EihzLpUI3sS_zI46YxAOuQ5B1Z_k1mY/edit?usp=sharing)
- [Bartek Iwańczuk - Deno内部是如何构建现代运行时 | Deno Warsaw](https://www.youtube.com/watch?v=qt7fbmypAFk)
    - [演讲稿](https://docs.google.com/presentation/d/1LYNGpyjx9PemL-P__7hVC8mSqkX-jL8VQLMhCRehy00/edit?usp=sharing)
- [Ryan Dahl & Kitson Kelly:  Deno是一种新的JavaScript方法 | TSConf 2019](https://www.youtube.com/watch?v=1gIiZfSbEAE)

# 新闻

- [Deno 新闻推送](https://deno.news)

# 其它语言的资源

## 中文

- [Deno 并不是下一代 Node.js](https://juejin.im/post/5b14a390e51d4506c1300bbc)
- [玩 Deno 遇到问题的解决方案](https://juejin.im/post/5b1245b3f265da6e4c6cf249)
- [让我们一起来学习别人学不动的 Deno](https://segmentfault.com/a/1190000015151287)
- [Design Mistakes in Node zh-CN](https://zhuanlan.zhihu.com/p/37637923)
- [Node之父ry：Node中的设计错误](https://mp.weixin.qq.com/s/7XAiYw18c8YZc-fXk0-wrw)
- [《Deno进阶开发笔记》](https://github.com/chenshenhai/deno_note/)
- [Deno 手册](https://nugine.github.io/deno-manual-cn/manual-cn.html)
- [Deno 风格指南](https://nugine.github.io/deno-manual-cn/style-guide-cn.html)
- [Deno中文社区](https://denocn.org)

## 希伯来语

- [Deno intro in Hebrew (slides in English)](https://www.youtube.com/watch?v=9tJ_LkI6_qw)

## 日语

- [Node.js における設計ミス By Ryan Dahl](https://yosuke-furukawa.hatenablog.com/entry/2018/06/07/080335)
- [mizchi/deno_code_reading.md](https://gist.github.com/mizchi/31e5628751330b624a0e8ada9e739b1e)
- [Design Mistakes in Node & Deno #kng5 / deno](https://speakerdeck.com/masashi/deno)
- [Dive into Deno：プロセス起動からTypeScriptが実行されるまで](https://blog.leko.jp/post/code-reading-of-deno-boot-process/)

## 韩语

- [denoland.kr/](https://denoland.kr/)

## 俄语

- [Telegram channel](https://t.me/denoland_ru)
- [Telegram chat](https://t.me/denoland)
