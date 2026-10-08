# GitHub 主页配套完善建议

README 已根据 2026-10-08 可访问的公开仓库整理。个人履历、具体职责和项目效果仍需要本人补充。

## 个人资料

在 GitHub 的 Edit profile 中，可把目前的 Bio 改成：

> Java · AI applications · Full-stack engineering | Spring AI, RAG & MCP | Shenzhen

Location 可保留 Shenzhen。Website 和公开邮箱填写你愿意公开的真实地址。

## 推荐置顶

建议先置顶以下四个仓库，让访客快速找到与你主页定位相关的代码：

1. [OpenClaw4j](https://github.com/Dexter-Huang/OpenClaw4j)：AI 应用与工作流实践。
2. [geo-frontend-vue](https://github.com/Dexter-Huang/geo-frontend-vue)：Vue 与 Electron 桌面端交付实践；保留构建镜像的说明。
3. [redis-mq](https://github.com/Dexter-Huang/redis-mq)：Java 后端与 Redis 消息队列实践。
4. [test-graalvm](https://github.com/Dexter-Huang/test-graalvm)：运行时与原生库调用实验。

这四个仓库各自的 README 也需要补充，才能承接主页展示。OpenClaw4j 尤其需要根目录项目入口。

## 仓库 Description 与 Topics 草稿

| 仓库 | 建议 Description | 建议 Topics |
| --- | --- | --- |
| OpenClaw4j | AI application and workflow experiments with Spring AI, RAG, pgvector and MCP. | java, spring-boot, spring-ai, rag, pgvector, mcp |
| geo-frontend-vue | Public build mirror for a Vue 3 web frontend and Electron desktop packaging. | vue, typescript, electron, vite, github-actions |
| redis-mq | Redis-backed messaging experiments with listener annotations and Spring Boot auto-configuration. | java, spring-boot, redis, message-queue |
| test-graalvm | Spring Boot and GraalVM Native Image experiments with Java FFM and native library integration. | java, graalvm, native-image, spring-boot, panama |

## 对求职展示最有帮助的补充

每个重点项目补充：

- 解决什么问题，适合什么使用场景。
- 一张实际界面截图或简短演示。
- 你具体负责的模块，以及使用了哪些上游项目。
- 一个值得说明的设计决策，例如向量检索、消息消费或桌面打包方案。
- 可复现的启动步骤，以及已验证的功能范围。
- 有证据的结果：测试环境、测量方法与数据；没有数据时先描述功能。

个人介绍后续可加入：当前职业方向、工作或教育经历、公开博客、邮箱及合作偏好。Fork 与基于上游代码的实践仓库应继续注明来源；如有实际合并的 PR，再增加贡献记录。

## 维护

- 横幅在 `assets/profile-header.svg`，可以直接编辑文字与配色。
- 修改展示项目时，同步调整项目介绍与技术栈。
- GitHub 统计卡片放在折叠区，依赖第三方服务；主页主体使用本仓库的静态内容。
- 个人资料、置顶、仓库 Description / Topics 需要在对应的 GitHub 设置中单独更新。
