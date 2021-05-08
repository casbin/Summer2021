## 开源软件供应链点亮计划-暑期2021 

### 开源软件供应链点亮计划-暑期2021”是什么？

“开源软件供应链点亮计划-暑期2021”（以下简称 暑期2021）是由中科院软件所与 openEuler 社区共同举办的一项面向高校学生的暑期活动，旨在鼓励在校学生积极参与开源软件的开发维护，促进国内优秀开源软件社区的蓬勃发展。

该计划将联合各大开源社区，针对重要开源软件的开发与维护提供项目，并向全球高校学生开放报名。学生可自主选择感兴趣的项目进行申请，并在中选后获得该软件资深维护者（社区导师）亲自指导的机会。根据项目的难易程度和完成情况，参与者还将获取“开源软件供应链点亮计划-暑期2021”活动奖杯和奖金。

暑期 2020 活动信息请查阅去年官网：https://isrc.iscas.ac.cn/summer2020/#/started

**“暑期2021”项目在今年（2021）第二次举办，与Google Summer of Code类似，可以看做中国版的GSoC。**

1. 官网：https://summer.iscas.ac.cn/
2. 官方新闻：http://www.iscas.ac.cn/xshd2016/xshy2016/202104/t20210426_5563484.html

### 活动的组织方有哪些

本次活动由中国科学院软件研究所、openEuler 社区主办，当前是第二届。

### 活动的参与方以及角色有哪些

活动参与方主要角色为学生、社区和导师。

1. 学生：学生自由选择项目，与社区导师沟通实现方案并撰写项目计划书。被选中的学生将在社区导师指导下，按计划完成开发工作，并将成果贡献给社区。社区评估学生的完成度，主办方根据评估结果发放资助金额给学生。
2. 社区：社区提供项目列表和描述，并安排项目对应的导师，导师与申请者沟通方案、并从申请者中选中一位承接项目。在为期三个月的开发周期中，导师指导学生进行对应项目的开发工作。
3. 导师：社区针对每一个项目指定一个社区导师，与学生一起制定合适的开发计划和方案，指导学生按计划完成开发。

### 项目的奖金是多少

每个项目难度分为高、中、低三档，对应税前奖金分别为高（12000 元）、中（9000 元）、低（6000 元）。（注：奖金数额为税前人民币金额）。
难度分级由社区根据项目任务决定。

## Casbin开源项目介绍

Casbin是一个强大的、高效的开源访问控制框架。涉及到Go, Java, Node.js, Javascript (React), Python, PHP, .NET, Delphi, Rust等多种语言。Casbin由北京大学罗杨博士创立于2017年，核心维护团队有数十人。Casbin在业界具有广泛影响力。目前已经被Intel、VMware、Orange、RedHat、T-Mobile等公司开源使用，被腾讯云、Cisco、Verizon等公司闭源使用。具体详见Casbin主页。Casbin Go主项目目前GitHub 8800+ stars，加上所有语言的实现、插件等可达到15000+ stars。Casbin曾经在国际上多次宣讲：

1. 新加坡政府技术部门Open Government Products：https://www.youtube.com/watch?v=OTT84oplR9o
2. 俄罗斯最大在线旅游平台tutu.ru：https://www.youtube.com/watch?v=Z5dUxH4PqYM

具体请了解Casbin官网：https://casbin.org/

## 可选项目列表

下列所有项目都与Casbin一致，采用开源协议：[Apache 2.0 license](LICENSE)

- [1. Casbin核心引擎（Golang）](#1-casbin核心引擎golang)
- [2. Casbin文档中文翻译 + 官网优化](#2-casbin文档中文翻译--官网优化)
- [3. Casbin.js核心前端库研发（前端Javascript + React + vue）](#3-casbinjs核心前端库研发前端javascript--react--vue)
- [4. Casdoor身份认证系统（前端React + Javascript，后端Golang）](#4-casdoor身份认证系统前端react--javascript后端golang)
- [5. Casbin官方核心论坛（前端React + Javascript，后端Golang）](#5-casbin官方核心论坛前端react--javascript后端golang)
- [6. Casbin官方会议投稿系统（前端React + Javascript，后端Golang）](#6-casbin官方会议投稿系统前端react--javascript后端golang)
- [8. jCasbin 生态完善（Java）](#8-jcasbin-生态完善java)
- [10. Casbin-RS 生态完善（Rust）](#10-casbin-rs-生态完善rust)
- [11. PyCasbin 生态完善（Python）](#11-pycasbin-生态完善python)
- [12. PHP-Casbin 生态完善（PHP）](#12-php-casbin-生态完善php)
- [15. Casbin Mesh (Golang) ](#15-casbin-mesh-golang)

### 1. Casbin核心引擎（Golang）

1. 项目标题：Casbin核心引擎（Golang）
2. 项目描述：Casbin采用独特的PERM模型语法（model）来实现强大、灵活的访问控制。Casbin Golang版本作为Casbin的第一个语言实现，拥有最多的用户以及最先进的feature。我们希望在Casbin Golang上：1）增强Casbin语法的表达能力，满足用户多样化的策略制定需求；2）优化Casbin在大规模规则集上（百万以上）的策略评估性能。这两个目标是Casbin的核心竞争力，对于其他Casbin语言的实现也会起到非常重要的借鉴意义。
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 增强Casbin语法的表达能力，满足用户多样化的策略制定需求
   - 优化Casbin在大规模规则集上（百万以上）的策略评估性能
   - 解决Casbin Golang主仓库&相关仓库中的issues：https://github.com/casbin/casbin/issues
8. 项目技术要求：
   - 熟悉Golang语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin
   - https://github.com/casbin

### 2. Casbin文档中文翻译 + 官网优化

1. 项目标题：Casbin文档中文翻译 + 官网优化
2. 项目描述：Casbin官网（https://casbin.org/ ）基于开源文档工具[Docusaurus](https://docusaurus.io/ )构建（基于React），采用Docusaurus所集成的[CrowdIn](https://crowdin.com/project/casbin )在线翻译平台进行众包翻译。Casbin官网原始文档均为英文，由CrowdIn上的贡献者自愿将英文翻译为其他各语言（如中文，韩文等）。但是目前各语言的翻译率较低，中文翻译率目前仅有15%，不利于开源项目在国内推广。因此希望能够将中文翻译率提高到100%。并且该项目也会承担一部分Casbin社区推广（如Casbin官方微信公众号）文章的撰写编辑、公众号管理等临时任务。该项目首先进入Talent 2021，若社区今年有[Google Season of Docs 2021](https://github.com/casbin/SeasonOfDocs2021 )名额则优先入选，若无名额则进入[中科院软件所暑期2021项目](https://github.com/casbin/Summer2020 )。
3. 项目难度：中
4. 项目社区导师：[刘子轩(nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 在CrowdIn翻译平台将Casbin官网英文内容翻译为中文，进度翻译至100%（目前为15%）
   - （可选）改进官网功能、优化内容排版，增加新的文档内容
   - （有时）撰写、编辑Casbin社区推广（如Casbin官方微信公众号）文章
   - 解决Casbin-website主仓库&相关仓库中的issues：https://github.com/casbin/casbin-website/issues
8. 项目技术要求：
   - 热爱并有能力撰写技术博客、文章
   - 了解React框架和NPM包管理
   - 了解Git、GitHub相关操作
   - 了解Casbin的工作原理
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-website
   - https://github.com/casbin/casbin.github.io

### 3. Casbin.js核心前端库研发（前端Javascript + React + vue）

1. 项目标题：Casbin.js核心前端库研发（前端Javascript + React + vue）
2. 项目描述：Casbin本身专注于服务器端（后端）的访问控制、权限管理，然而Web App（前端）也有权限管理的需求：如列出当前登录用户有权访问的所有列表项，或当前用户无权进行删除帖子的操作，则把删除按钮变灰或隐藏等等。因此Casbin推出专门用于前端权限展示的开源库：[Casbin.js](https://github.com/casbin/casbin.js) 。该库主要实现2个功能：1）调用后端Casbin（可能是Go，也可能是Java等）提供的接口（RESTful或cookie等方式），获取当前登录用户的权限；2）将获取到的权限转换为列表、按钮的显示状态。Casbin.js在GSoC 2020期间已经研发了3个月，但是目前从功能、适配性、可用性等方面离最终完成还仍有很大距离。之前的研发文档、记录可从此处获得：https://github.com/casbin/casbin.js/issues 。
3. 项目难度：高
4. 项目社区导师：[刘梓晖 (kingiw)](https://github.com/kingiw)
5. 导师联系方式：kingiw (AT) hotmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 大规模重构、改造、完善[Casbin.js](https://github.com/casbin/casbin.js) ，从功能、适配性、可用性上达到类似CASL项目：https://github.com/stalniy/casl
   - 完成核心主库Casbin.js的开发，推送到NPM。同时类似CASL项目，包装出React、Vue等框架的适配器，方便React、Vue用户使用
   - 开发至少一种后端语言（如Go Casbin）的对接Casbin.js的API接口，从而使后端把权限传给前端的Casbin.js
   - 解决Casbin.js主仓库&相关仓库中的issues：https://github.com/casbin/casbin.js/issues
8. 项目技术要求：
   - 熟悉HTML、Javascript、CSS等前端技术
   - 熟悉React或Vue框架，两种都熟悉更好
   - 熟悉NPM包管理，熟悉Git、GitHub相关操作
   - 至少了解一种后端语言，如Go、Java、Python、Node.js、Rust等，有全栈工程师相关经验；
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin.js
   - https://github.com/casbin-js

### 4. Casdoor身份认证系统（前端React + Javascript，后端Golang）

1. 项目标题：Casdoor身份认证系统（前端React + Javascript，后端Golang）
2. 项目描述：Casdoor是一套基于基于OAuth 2.0 / OIDC协议的统一身份认证（单点登录）系统。其支持多种第三方登录方式，如QQ、微信、Google, GitHub等。Casdoor具有Web管理界面，可以用来管理用户、角色、权限（基于Casbin）
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 扩展架构，添加更多的第三方登录支持
   - 优化、美化Web界面
   - 支持Casbin权限管理
   - 解决Casdoor主仓库&相关仓库中的issues：https://github.com/casbin/casdoor/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casdoor
   - https://github.com/casdoor

### 5. Casbin官方核心论坛（前端React + Javascript，后端Golang）

1. 项目标题：Casbin官方核心论坛（前端React + Javascript，后端Golang）
2. 项目描述：Casbin社区目前采用QQ群（中文），Gitter（英文）进行社区交流，交流渠道比较有限。我们打算开发一个同时面向Casbin开发者和用户的官方论坛：casnode（https://github.com/casbin/casnode ），风格与[V2EX](https://v2ex.com/)类似。该论坛开源，因此也欢迎其他开源社区使用。
3. 项目难度：高
4. 项目社区导师：[张军洁 (kocoler)](https://github.com/kocoler)
5. 导师联系方式：tsglsdrs (AT) 163.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完成一个界面风格类似[V2EX](https://v2ex.com/)的论坛，作为Casbin开源社区的官方论坛
   - 继续维护该项目，添加features，解决bugs，完善其邮件列表功能
   - 解决Casnode&相关仓库中的issues：https://github.com/casbin/casnode/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casnode
   - https://github.com/casbin/casbin

### 6. Casbin官方会议投稿系统（前端React + Javascript，后端Golang）

1. 项目标题：Casbin官方会议投稿系统（前端React + Javascript，后端Golang）
2. 项目描述：Casbin社区目前采用Docusaurus静态页面作为官网（https://github.com/casbin/casbin-website），通过git commit更新文档内容，文档、稿件处理渠道比较有限。我们打算开发一个同时面向Casbin技术写作者（technical writer）的官方稿件处理、评审、展示系统：Casbin-OA（https://github.com/casbin/casbin-oa ）。该投稿系统的另一个功能是全方位展示Casbin访问控制的功能，后台利用[Casbin](https://github.com/casbin/casbin)进行权限管理，前台利用[casbin.js](https://github.com/casbin/casbin.js)控制UI元素，如按钮的显示。该论坛会成为Casbin技术最强有力的展示。该项目开源，因此也欢迎其他开源社区使用。
3. 项目难度：高
4. 项目社区导师：[罗杨 (hsluoyz)](https://github.com/hsluoyz)
5. 导师联系方式：hsluoyz (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完成一个会议投稿系统，作为Casbin开源社区的官方稿件处理系统
   - 后台利用[Casbin](https://github.com/casbin/casbin)进行权限管理
   - 前台利用[casbin.js](https://github.com/casbin/casbin.js)控制UI元素，如按钮的显示（[casbin.js](https://github.com/casbin/casbin.js)目前还在开发中，如果casbin.js未开发完毕则此要求作废，可自行实现前端页面访问控制）
   - 解决Casbin OA&相关仓库中的issues：https://github.com/casbin/casbin-oa/issues
8. 项目技术要求：
   - 熟悉React、Javascript语言（前端）
   - 熟悉Golang语言（后端）
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-oa
   - https://github.com/casbin/casbin

### 8. jCasbin 生态完善（Java）

1. 项目标题：jCasbin 生态完善（Java）
2. 项目描述：jCasbin 在 Java 平台上取得了不错的进展，但是我们仍然需要努力工作，以帮助 Casbin 成为世界上最受欢迎的身份授权库。目前Java语言上最流行的授权库是Apache Shiro和Spring Security，最流行的Web框架是Spring。我们需要实现Casbin针对Spring等框架的插件，使Spring用户可以无缝接入Casbin。同时要兼容Apache Shiro和Spring Security的接口，让目前正在使用Apache Shiro和Spring Security的项目可以无缝迁移到Casbin。同时jCasbin也需要及时跟踪Golang Casbin主库的最新feature并移植到Java版本中来。
3. 项目难度：中
4. 项目社区导师：[房政金 (Distance)](https://github.com/fangzhengjin)
5. 导师联系方式：fangzhengjin (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 实现针对Spring，包括Spring Cloud，SpringBoot等的权限认证中间件
   - 实现兼容Apache Shiro和Spring Security的接口
   - 根据用户需求，实现缺失的数据库adapter
   - 解决 jCasbin 主仓库&相关仓库中的 issues：https://github.com/casbin/jcasbin/issues
8. 项目技术要求：
   - 熟悉 Java 语言
   - 熟悉 SQL
   - 熟悉 Git、GitHub 相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/jcasbin
   - https://github.com/jcasbin

### 10. Casbin-RS 生态完善（Rust）

1. 项目标题：Casbin-RS 生态完善（Rust）
2. 项目描述：Casbin Rust 目前尚缺乏各个主流 Rust Web 框架的集成，以及对于 `gRPC` 的集成支持。此议题希望学生独立完成对于 [Warp](https://github.com/seanmonstar/warp) 、[Tide](https://github.com/http-rs/tide) 框架的中间件集成；独立完成 [casbin-grpc](https://github.com/casbin-rs/casbin-grpc)的基本实现和文档工作。
3. 项目难度：高
4. 项目社区导师：[Eason Chai(Hackerchai)](https://github.com/hackerchai)
5. 导师联系方式：i (AT) hackerchai.com
6. 合作导师联系方式（选填）：psiace (AT) outlook.com
7. 项目产出要求：
   - 针对 [Warp](https://github.com/seanmonstar/warp) 框架实现 casbin 中间件实现，包含正确，充足的单元/集成测试以及完备的文档说明，并且实现一个完备的实际应用样例
   - 针对 [Tide](https://github.com/http-rs/tide) 框架实现 casbin 中间件实现，包含正确，充足的单元/集成测试以及完备的文档说明，并且实现一个完备的实际应用样例
   - 完善 [Casbin-Raft](https://github.com/casbin-rs/casbin-raft) 实现   Rust 版本 [Casbin-Raft (Go)](https://github.com/casbin/casbin-raft) ,使用 [Raft-rs](https://github.com/tikv/raft-rs) 框架实现完备的  `Raft` 协议支持；参考 [hraft-dispatcher（Go）](https://github.com/casbin/hraft-dispatcher) 对 [Casbin-Raft（Go）](https://github.com/casbin-rs/casbin-raft) 进行重构，设计正确，充足的单元/集成测试以确保可用性，完成相应的文档工作。架构可以参考  [toshi（Rust）](https://github.com/toshi-search/Toshi) 或者 [MeiliSearch-Raft](https://github.com/meilisearch/MeiliSearch/tree/raft)；要求可以投入实际生产环境
   - 解决 Casbin Rust 主仓库和相关仓库中的 issues ：https://github.com/casbin/casbin-rs/issues
8. 项目技术要求：
   - 熟悉Rust语言
   - 熟悉Git、GitHub相关操作
   - 熟练掌握一种后端框架，对于中间件，数据库操作有一定了解
   - 熟悉 `RPC` 工作原理，了解一定的云原生开发
   - 熟悉 `Raft` 协议工作原理
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin-rs
   - https://github.com/casbin-rs

### 11. PyCasbin 生态完善（Python）

1. 项目标题：PyCasbin 生态完善（Python）
2. 项目描述：PyCasbin 是Casbin的Python版实现，功能和 Casbin（Golang）基本一致。目前，PyCasbin实现了Casbin的主要功能，但还有少许功能尚未实现，另外代码质量还有调优的可能，PyCasbin对周边框架的支持不够完善，所以我们希望对PyCasibn进行完善和优化，同时需要对PyCasin的生态予以完善。
3. 项目难度：中
4. 项目社区导师：[techoner](https://github.com/techoner)
5. 导师联系方式：techqiang (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完善PyCasbin，和Casbin（Golang）保持一致
   - 在保证功能、结构不变的情况下，调优代码质量
   - 解决PyCasbin仓库中的issues：https://github.com/casbin/pycasbin/issues
8. 项目技术要求：
   - 熟悉Python语言
   - 熟悉Casbin其他任意一种语言的实现
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/casbin/pycasbin
   - https://github.com/pycasbin

### 12. PHP-Casbin 生态完善（PHP）

1. 项目标题：PHP-Casbin 生态完善（PHP）
2. 项目描述：[PHP-Casbin](https://github.com/php-casbin/php-casbin) 是Casbin的PHP版实现，功能和 Casbin（Golang）基本一致。目前，PHP-Casbin已经支持对`Laravel` `ThinkPHP` `Yii` `Codeigniter` `CakePHP` 等主流框架的适配。目前还需要开发对`Symfony`的扩展，C级别的框架进行支持，例如：`Phalcon Framework`，基于Swoole的框架支持，例如： `Hyperf` `easyswoole`等。除此之外，我们也希望Casbin有个PHP的C/C++扩展，以提升性能。
3. 项目难度：中
4. 项目社区导师：[techoner](https://github.com/techoner)
5. 导师联系方式：techqiang (AT) gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 完成 [Symfony-Permission](https://github.com/php-casbin/symfony-permission)
   - 对C级别的框架进行支持，例如：`Phalcon Framework`
   - 对基于Swoole的框架支持，例如： `Hyperf` `easyswoole`等
   - PHP的C/C++扩展，可以基于[Casin-cpp](https://github.com/casbin/casbin-cpp)，也可以考虑通过`zephir`实现
   - 解决PHP-Casbin仓库中的issues：https://github.com/php-casbin/php-casbin/issues
8. 项目技术要求：
   - 熟悉PHP语言
   - 熟悉Git、GitHub相关操作
9. 相关的开源软件仓库列表：
   - https://github.com/php-casbin/php-casbin
   - https://github.com/php-casbin

### 15. Casbin Mesh (Golang)

1. 项目标题：Casbin Mesh (Golang)
2. 项目描述：Casbin Mesh 是一个管理多个访问控制应用的系统，我们将会使用 Casbin + Raft 协议构建开箱即用、可伸缩的访问管理服务，用户可以在任意服务上更新、查找规则集以及检查规则。
3. 项目难度：高
4. 项目社区导师：[刘子轩 (nodece)](https://github.com/nodece)
5. 导师联系方式：nodeces@gmail.com
6. 合作导师联系方式（选填）：无
7. 项目产出要求：
   - 基于 Raft + TCP(with TLS) 提供可伸缩性服务
   - 正确，充足的单元/集成测试，确保程序运行的正确性
   - 支持在 Leader 或者 Follower 节点更新、查找规则集以及检查规则
   - 提供身份认证系统保护系统的安全，例如第三方客户端的接入
   - 提供 Go SDK 访问该系统
   - 提供 WEB/CLI 管理用户的访问控制应用
   - 提供安全审计

8. 项目技术要求：
   - 熟悉 Golang
   - 熟悉 Raft

9. 相关的开源软件仓库列表：
   - https://github.com/casbin/casbin
   - https://github.com/casbin/hraft-dispatcher

所有可选项目详见：https://github.com/casbin/Summer2021#可选项目列表

## 候选人要求

### 工作职责：

- 每周与项目导师进行线上讨论，完成项目规定的开发任务。项目导师由开源项目创始人或其他核心成员担任；
- 积极参与开源社区的建设，参与代码提交、解决Issue、审核PR等日常工作；
- 配合完成官方要求的材料提交等事项，包括项目申请书撰写、社区反馈任务完成度追踪等。

### 职位要求：

- 本科、硕士或博士在读（已毕业、工作的无法参加）；
- 对开源软件、开源社区感兴趣；
- 熟悉一种或多种编程语言，有较强的工程能力，代码格式清晰规范，善于团队协作；
- 有一定英文读写能力，能够熟练运用英语在GitHub进行开发、协作；
- 较强的沟通能力和逻辑表达能力。

### 具有以下条件者优先：

- 熟悉计算机网络、网络安全，有相关项目经验；
- 熟悉Go, Rust等语言、分布式系统、微服务架构，有相关项目经验；
- 在GitHub较为活跃，有自己的开源项目，或参与过知名开源项目；
- 可以在项目结束后继续长期参与开源社区的开发、建设或维护。


## 投递要求

申请学生需要同时完成以下“联系社区”和“官网投递”两个环节：

### 1. 联系社区（即日起至2021年6月13日）

1. 发送【中文简历PDF】至Casbin社区官方邮箱：admin (AT) casbin.org 
2. 加入《Casbin访问控制社区群》（QQ大群）：[546057381](https://shang.qq.com/wpa/qunwpa?idkey=8ac8b91fc97ace3d383d0035f7aa06f7d670fd8e8d4837347354a31c18fac885)
3. 加入《Casbin软件所点亮计划-暑期2021-官方群》（QQ小群）：[637616705](https://qm.qq.com/cgi-bin/qm/qr?k=WsNgmQs-7wRGR_vB0IQ-57Tovs8EuQbw&jump_from=webapi) ，联系导师，与导师沟通项目细节和方案，完善项目申请书

### 2. 官网投递（2021年5月24日至2021年6月13日）

详见：https://summer.iscas.ac.cn/help/student/
