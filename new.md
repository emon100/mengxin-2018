#  试试Git吧

## Part 1: Git Tutorial (必做)
 - 任务描述：
   
   Git 是一个版本控制工具。在加入我们进行多人协作的开发之前，你**必须学会**使用它，不然你将几乎无法为我们的项目做出有效的贡献。

   虽然 Git 有为数众多的图形工具（比如 TortoiseGit、Git GUI（没错，这货是 Git Windows 版自带的）、GitKraken，甚至是各种 IDE 自带的 Git 组件（比如 JetBrains 系列 IDE 中的 Git 功能、微软 Visual Studio Code 中的 Git 功能等等）），但如果要**从根本上掌握 Git 的使用方法**，大家仍然**需要在命令行中使用 Git**，在 Git 命令行提供的各种命令中熟悉 Git 的各种操作。（太过功利可是学不到真东西的哦）
   
   GitHub，最为活跃的开源社区之一，是一个使用 Git 作为版本控制系统的代码托管平台。如无特殊情况，我们部门的项目都会托管于 GitHub，并遵循各种开源协议的规范和要求。所以要加入先锋网络部的大家庭，毫无疑问地**你需要注册一个自己的 GitHub 帐号**。有这样一种说法，一个程序员的 GitHub 帐号相当于这个程序员的门面，一个好的 GitHub 帐号是无声而最有力的简历和推荐信，而事实上你注册的 GitHub 帐号（如不出意外）将会陪伴你整个代码生涯，所以请**慎重地为自己选择一个 GitHub ID**，然后**给自己上传一个合适的头像**（也可以使用 GitHub 自动为你生成的像素风头像）。所以你还在等什么呢，快快为你的开源社区生涯打开第一扇门吧！
   
   完成注册 GitHub 之后，请学习并完成 [try.github.io](https://try.github.io/) 上有关 Git/GitHub 的命令行教程。同时你也可以参考网络上各种优质的 Git/GitHub 学习资料，**自学 Git 版本控制系统**，自学有关**如何在 GitHub 上进行协作**的内容。我们也为大家精选了一些学习资料，列举如下，供大家参考。也欢迎发现高质量学习资源的同学们发起 Pull Request，积极为大家补充！
    - 廖雪峰《[Git 教程](https://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000)》（由 @dongdaxiaodong 分享）
    - 开源图书《Pro Git 第二版》
      * 英文在线版：https://git-scm.com/book/en/v2
      * 中文在线版：https://git-scm.com/book/zh/v2
    - 网络部2018招新宣讲宣讲《Git版本控制与GitHub》[演示文稿](https://docs.google.com/presentation/d/1SSdmcZ3DXoZL836bpmGDI3ISkPWMomg0_ox6qV_mgpE/edit#slide=id.p)（by 舒意恒）
    - 博文《Git入门与基础》（by 舒意恒） on [GitHub](https://github.com/lzw429/Git-Guide/blob/master/Git-%E5%85%A5%E9%97%A8%E4%B8%8E%E5%9F%BA%E7%A1%80.pdf)
    - GitHub Guides：https://guides.github.com/
    - Learn Git Branching：https://learngitbranching.js.org/
    
   另外要说明的一点是，虽然 GitHub 是英文的，还请大家**尽量避免使用全文翻译来浏览 GitHub 上的内容**。英文是每个合格的开发者必须要精通的，建议英文基础不太好的同学们常备词典（或电子辞典），记下自己不会的生词然后想办法掌握他们，而非直接通过全文翻译等工具绕过他们。提升英文阅读能力，将让你在以后阅读（和书写）纯英文文档时如虎添翼，极大的提升开发效率（以及与国际友人的沟通能力）。学英语，不吃亏！
 - 任务提交：
 
   在 GitHub 上 **fork** 这个（`mengxin-2018`）仓库，然后将你的姓名加入文章末尾的列表中，再发起 **pull request**。
 - 注意事项：
   1. 你可能需要稍微了解一点 Markdown 语法知识
   2. 请使用命令行进行 **commit**， i.e. 你的 **commit** 中不能出现 `committed on GitHub` 字样。
   3. 请尽量避免使用会污染原文的工具进行编辑（比如会自动添加 BOM 头的 Windows 记事本、会自动调整 Markdown 空白字符格式的可视化 Markdown 编辑器等），就算使用也请在提交前对更改详情进行审查，避免向版本库提交有毒内容。

## Part 2: Direction Choice (必做)
 - 任务描述：
   了解前端、后端和运维的工作及技能需求，结合自己的兴趣与他人的建议，决定自己的主力方向。
   一些可能的方向需求列举如下：
    * 前端方向：
      - 需要对基础三件套（HTML、CSS、JavaScript）熟练掌握，尽量掌握较新版本（如HTML5、CSS3、ECMAScript6）等的特性；
      - 需要对浏览器渲染时的各种细节做到准确把握，在出现玄学问题时能系统地分析问题原因；
      - 至少掌握基础三件套的一组预处理器组合（如处理到 HTML 的 [Pug](https://pugjs.org/)、[Haml](http://haml.info/)、[Slim](http://slim-lang.com/) 等，处理到 CSS 的 [Sass](https://sass-lang.com/)、[LESS](http://lesscss.org/)、[SCSS](http://sass-lang.com/documentation/file.SCSS_FOR_SASS_USERS.html)、[Stylus](http://stylus-lang.com/) 等，处理到 JavaScript 的 [TypeScript](https://www.typescriptlang.org/)、[CoffeeScript](https://coffeescript.org/) 等，以及通用的预处理器 [Emmet Abbreviation](https://emmet.io/) 等）；
      - 熟悉现代化 Web 处理技法，如 [Babel](https://babeljs.io/)、[Webpack](https://webpack.js.org/)、[响应式设计](https://en.wikipedia.org/wiki/Responsive_web_design)、[PWA](https://developers.google.com/web/fundamentals/codelabs/your-first-pwapp/?hl=zh-cn)、[ServiceWorker](https://developer.mozilla.org/zh-CN/docs/Web/API/Service_Worker_API)、[异步 XMLHTTP 请求](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Synchronous_and_Asynchronous_Requests)、[WebSocket](https://developer.mozilla.org/zh-CN/docs/Web/API/WebSocket) 等；
      - 掌握现代化前端框架（如 [Vue.js](https://vuejs.org/)、[Angular](https://angular.io/)、[React](https://reactjs.org/) 等）中的一个或多个；
      - 掌握前端 UI 框架（如 [Bootstrap](http://getbootstrap.com/)、[jQuery DOM](https://api.jquery.com/category/miscellaneous/dom-element-methods/)、[jQuery EasyUI](https://www.jeasyui.com/)、[Ant Design](https://ant.design/)、[ElementUI](https://github.com/ElemeFE/element)、[iView](https://www.iviewui.com/)、[ECharts](http://echarts.baidu.com/)、[Handlebars](http://handlebarsjs.com/) 等）中的一个或多个，以及其所依赖的前置技术栈；
      - 掌握前端模块化编程现代理念（如 [RequireJS](https://requirejs.org/)、[CommonJS](https://nodejs.org/docs/latest/api/modules.html)、[Browserify](http://browserify.org/)、[AMD](https://requirejs.org/docs/whyamd.html) 等）；
      - 掌握前后端通讯技术与框架（如 Websocket、jQuery XMLHTTP、[Axios](https://github.com/axios/axios)、[HTML5 `fetch`](https://developer.mozilla.org/zh-CN/docs/Web/API/Fetch_API/Using_Fetch) 等），熟悉对应的 HTTP 协议规范，了解基本的通讯归约与语义规范；
      - ...
      
    * 后端方向：
      - 需要对 Java、Python、Ruby、Golang、Kotlin、Groovy、JavaScript 等语言中的一种或几种有较好的掌握；
      - 对 Oracle、MySQL（或 MariaDB）、PostgreSQL 等关系型数据库系统（RDBMS）中的一种或几种的基本使用熟悉；
      - 对 Redis、MongoDB 等常见的非关系型数据库基本熟悉掌握；
      - 对 RabbitMQ、RocketMQ、Kafka 等消息队列系统（MQ）的原理熟悉，掌握使用方法；
      - 对 JSON-RPC、SOAP、RESTful、GraphQL、APIJSON 等调用归约模式中的一个或几个做到熟练掌握；
      - 对常用的后端敏捷开发框架（如 Flask、Sanic、Tornado、aiohttp、Vibora 等 Python Web 框架，Vert.x、Spring Boot、JFinal、Resty、Cloudopt Next 等 JVM Web 框架，Express、Meteor 等 NodeJS Web 框架，以及许多语言的许多 Web 框架）中的一个或几个做到熟练掌握；
      - ...
      
    * 运维方向：
      - 对 Linux 操作系统的指令有全面的了解，熟悉 Bash 脚本（或 Zsh 脚本）编程；
      - 需要对常见服务器 Linux 发行版本（如 Ubuntu LTS、CentOS 等）的安装、重装、安装新软件、配置特定环境等操作熟悉；
      - 对常见的服务器软件（如 nginx、Apache 等 Web 服务器，MySQL、PostgreSQL、MySQL（MariaDB）、Redis、MongoDB 等数据库服务器，RabbitMQ、Kafka 等消息队列服务器，以及其他服务器软件）中大多数的配置与日常维护熟悉，要能与后端开发人员协同对服务器进行停机更新或不停机更新；
      - 对网络安全方面的知识有一定的了解，会及时将服务器上的软件或操作系统更新到较新的版本以修复安全漏洞，会配置服务器防火墙、用户及用户组权限到最小权限要求；
      - （深入 Linux）对 Linux 内核编程有了解和研究，能自己魔改 Linux 内核，给内核提交 Patch 等。
      - ...
      
 - 任务提交：10 月 13 日例会前后将会统计大家的方向志愿，并根据部门的实际情况作出一定的调剂。
 

### Part 1: Git Tutorial
- Your name
- Emon100
- tomtiao
- Monarcaa
- Rain3030
ok
