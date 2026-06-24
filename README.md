# 赵仲煊

前端工程师｜AI 平台 / 微前端架构｜6 年 React + TypeScript 开发

- 电话：18635517712
- 邮箱：zzxzzx8888@gmail.com
- 简历主页：[https://resume.zzxzzx8888.dpdns.org](https://resume.zzxzzx8888.dpdns.org)
- GitHub：[https://github.com/sidey-zzy](https://github.com/sidey-zzy)

## 个人总结

6 年前端开发，深耕 React+TS 技术栈，具备 AI 商业化产品自研、淘天十万 PV 微前端、国际化 SEO 站点完整落地经验。可独立完成需求评审、架构设计、编码、性能优化、上线迭代全流程；自主沉淀全局埋点 Hook、多语言路由、统一 MTOP 请求层、Schema 动态表单等通用工程工具。独立从零搭建 3 套 AI 产品官网 / 控制台 / 文档站，擅长大型 B 端权限、数据可视化、多语言路由、Module Federation 微前端架构。掌握 Python，LeetCode 刷题 1000+，熟练掌握各类常用数据结构与算法。

## 工作经历

### 阿里淘天商家项目组（杭州博彦科技 / 北京汉克驻场）

前端工程师 | 2021.06 - 至今

- 负责淘宝服务市场、千牛工作台和商家服务管理平台等核心模块建设，覆盖高流量服务导购、服务商入驻、资质认证、订单履约、结算财务等业务链路。
- 落地 Module Federation 微前端、24+ 路由动态分包、MTOP 请求封装、曝光埋点 Hook 和动态表单能力，支撑日均 10w+ PV 的服务市场访问与多团队协作迭代。

### 中国药科大学

药物化学 / 本科 | 2011.09 - 2015.07

## 项目经历

### 淘天商家服务生态平台

- 项目地址：[服务市场](https://fuwu.taobao.com/) / [服务商后台](https://work.open.taobao.com/) / [千牛工作台](https://myseller.taobao.com/home.htm/qianniu-service-market/)
- 角色：全权负责前端开发
- 核心技术：React、TypeScript、Ice.js、Module Federation、MTOP、配置化页面、曝光埋点

1. C 端导购服务市场：独立搭建首页、服务商详情、工具推荐等流量页面，承接平台日均 10w + 商家访问流量；封装复用型 useExposure 埋点钩子，统一管控全站 75 + 曝光点位，支撑运营活动数据统计复盘。
2. B 端服务商后台：负责资质入驻、订单履约、结算报税等 15 个核心业务模块，基于 Module Federation 实现微前端拆分，对 24 + 业务路由做动态分包懒加载，支持各模块独立开发、独立发版，适配多团队并行协作。
3. 千牛工作台内嵌页面：采用 MT2 配置化渲染方案，运营内容无需前端发版即可实时更新；通过 RemoteModule 远程加载工具模块，整合 20 余项商家服务 API，实现工具订阅、续费、评价完整业务闭环。
4. 沉淀标准化 MTOP 请求层、环境切换、全局异常捕获、动态表单、拖拽交互等通用能力，统一全平台基础交互逻辑，减少重复开发工作。
5. 项目规范治理 & AI研发赋能：主导项目前端Spec全流程规范制定，统一接口交互、组件定义、目录结构、代码格式、Git提交规范，统一微前端多应用研发标准，解决多子应用代码风格割裂、维护难度大的痛点；同时主导落地AI辅助开发流程，沉淀业务专属Prompt，利用AI完成通用页面脚手架、基础组件、TS类型、重复业务代码自动生成，并且人工把控架构设计、业务逻辑与代码审核，规范AI代码产出质量，大幅减少低效重复开发，提升项目整体研发效率。

### OneRoute 官网与用户控制台

- 项目地址：[https://1route.ai](https://1route.ai)
- 角色：独立从零搭建，全链路负责前端方案设计与开发
- 核心技术：React Router v7、React 19、RSC、AI SDK、G2、国际化 SEO

1. 独立搭建一体化 AI 产品官网 + 用户控制台，覆盖品牌宣传、模型咨询、充值支付、API 密钥、用量统计全链路，面向海内外 AI 开发者提供自助服务。
2. 自研 URL 驱动多语言路由体系，统一处理语言切换、国际站点重定向，标准化 canonical 标签输出，解决多语言站点收录混乱问题，完善海外 SEO 基础能力。
3. 分层封装通用请求与状态管理模块，解耦页面与接口逻辑；基于 G2 搭建可视化用量看板，直观呈现模型消耗数据，支撑运营数据分析。
4. 完整配置 sitemap、robots、结构化数据、OG 标签等 SEO 基础设施，提升站点搜索引擎曝光与外部分享展示效果。

### 1route-console-ui 管理控制台

- 项目地址：[https://console-global.1route.ai/zh-CN/](https://console-global.1route.ai/zh-CN/)
- 角色：独立从零搭建，全链路负责前端方案设计与开发
- 核心技术：React Router v7、React 19、SSR、Ant Design、Zustand、G2、CodeMirror

1. 从零搭建 AI 后台管理系统，覆盖登录鉴权、用量审计、用户管理、账单告警、模型路由、插件配置等复杂 B 端场景。
2. 基于 React Router 搭建多级权限路由，搭配 Zustand 全局状态管理统一数据流，大幅降低多模块协同维护成本。
3. 整合代码编辑器、多维数据表格、可视化图表组件，支持模型配置、日志排查、策略调试等技术运营场景。
4. 实现账单批量导出、价格策略、异常告警体系，支持多维度数据筛选聚合，快速定位 API 调用、计费相关线上问题。

## 近两月业余技术实验项目

- Web CAD：https://smartcad.app/ 基于 React Router + Canvas 验证浏览器 CAD 编辑器能力，实现高清画布、平移缩放、网格标尺、选择变换、撤销重做、JSON CAD / DXF 解析导出等基础能力。
- 洛克王国世界助手平台：https://lkhub.cn/ 基于 pnpm Monorepo 搭建玩家 H5、管理后台、小程序、Fastify、 prisma、 postgres API 和资讯机器人，验证游戏资料站、数据导入和 AI 辅助内容生产链路。
- My Company Sim：https://company-sim.zzxzzx8888.dpdns.org/ 基于 React + Zustand + Pixi.js 构建外包公司模拟经营游戏原型，验证招聘、合同、财务、邮件、仲裁、存档和时间流逝等复杂规则系统。
