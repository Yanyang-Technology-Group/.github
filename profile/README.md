<div align="center">

<img src="https://capsule-render.vercel.app/api?type=venom&height=200&text=We%20are%20Y.T.G.&fontSize=70&color=0:BFE1FF,100:B678C4&stroke=B678C4" alt="We are Y.T.G." width="100%">

# 晏阳技术组

**Yanyang Technology Group**

**创新为骨，代码为韵。**

从社区网站到桌面工具，从 Minecraft 创作到服务器诊断，
用代码连接想法，让工具走进日常。

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group)
[![Gitee](https://img.shields.io/badge/Gitee-C71D23?style=for-the-badge&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group)
[![Gitea](https://img.shields.io/badge/Gitea-609926?style=for-the-badge&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group)

[官方网站](https://tech.yanyn.cn) · [项目一览](#projects) · [核心成员](#team) · [参与贡献](#contribute)

</div>

---

## 关于我们

我们是晏阳技术组，一个围绕 **社区服务、桌面应用与 Minecraft 生态** 开展创作的技术团队。我们关注实际使用中的问题，也享受把想法逐步做成作品的过程。

这里既有持续迭代的社区平台、直播工具和插件，也保留了早期邮箱客户端的开发历程。欢迎浏览源码、提出建议，或和我们一起完善下一个版本。

| 创作方向 | 我们在做什么 |
| :--- | :--- |
| 🌐 社区与网站 | 自托管社区、跨平台客户端、城市建设官网与技术组展示网站 |
| 🧰 桌面与媒体 | 邮箱客户端、Minecraft 启动器、直播推流与字幕转码工具 |
| 🚆 Minecraft 生态 | 轨道交通模组优化、文字格式插件与服务器性能分析 |

<a id="projects"></a>

## 项目一览

**按用途找到你感兴趣的项目。** 每个项目均提供 GitHub 源码入口；已确认存在的平台镜像紧随其后。

[社区与网站](#web) · [桌面与媒体](#desktop) · [Minecraft 与开发工具](#minecraft) · [历史项目](#archive)

<!-- 仓库与镜像核对日期：2026-11-09。范围：14 个公开非 Fork 仓库，另纳入 MTR-YanYang 作为 Fork 特例。镜像存在不代表与 GitHub 实时同步。 -->

<a id="web"></a>

### 🌐 社区与网站

#### YComm_WebSite · 晏阳社区服务端

面向自托管的社区平台，将 **账号系统、论坛与资源下载区** 集成在一起。提供角色与访问权限管理、内容审核及通知能力，支持通过 Docker 部署。

`TypeScript` `Next.js` `Hono` `PostgreSQL` · **AGPL-3.0-or-later**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YComm_WebSite)
[![Gitee Mirror](https://img.shields.io/badge/Gitee-Mirror-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group/YComm_WebSite)
[![Gitea Mirror](https://img.shields.io/badge/Gitea-Mirror-609926?style=flat-square&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group/YComm_WebSite)

#### YComm_Flutter · 晏阳社区客户端

以 Flutter 构建的社区客户端，围绕 **社区、资源、消息与个人中心** 提供统一入口。支持讨论与回复、资源浏览与下载、GitHub 登录、主题切换和 WebSocket 通知，兼顾手机与宽屏布局。

`Dart` `Flutter` `Material 3` `WebSocket` · **AGPL-3.0-or-later**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YComm_Flutter)
[![Gitee Mirror](https://img.shields.io/badge/Gitee-Mirror-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group/YComm_Flutter)
[![Gitea Mirror](https://img.shields.io/badge/Gitea-Mirror-609926?style=flat-square&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group/YComm_Flutter)

#### Yanyang_WebSite · 晏阳城市建设官网

晏阳城市建设的官方形象网站，展示 **社区活动、城市规划与轨道交通创作**。采用响应式布局，提供双语内容、线路图与下载等页面。

`TypeScript` `React` `Vite` `Tailwind CSS` · **GPLv3**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/Yanyang_WebSite)
[![Gitee Mirror](https://img.shields.io/badge/Gitee-Mirror-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group/Yanyang_WebSite)
[![Gitea Mirror](https://img.shields.io/badge/Gitea-Mirror-609926?style=flat-square&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group/Yanyang_WebSite)

#### YTG_Website · 晏阳技术组展示网站

集中介绍技术组、开源项目与多平台入口的响应式静态网站。提供 **项目分类筛选、项目详情与深浅色主题**，方便访客了解团队并找到对应仓库。

`JavaScript` `React` `Vite` `Tailwind CSS` `DaisyUI` · **GPL-3.0-only**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YTG_Website)

<a id="desktop"></a>

### 🧰 桌面与媒体

#### YanynEmail · 晏阳邮箱

基于 C++ 与 Qt 6 构建的桌面邮箱客户端，通过 Mailio 实现邮件收发。面向 **QQ 邮箱、163 邮箱、Outlook 与 Gmail** 等邮箱服务，延续晏阳邮箱从 Python 到 C++ 的开发探索。

`C++` `Qt 6` `Mailio` `Boost` `OpenSSL` · **GPLv3**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YanynEmail)

#### Yanyang_Craft_Launcher · 晏阳 Minecraft 启动器

面向晏阳城市建设社区的 Minecraft 启动器项目，使用 **C++ 与 Qt** 开发。具体功能与可用版本以仓库说明及发布内容为准。

`C++` `Qt` · **GPLv3**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/Yanyang_Craft_Launcher)

#### YLive-cpp · 直播推流与转码工具

面向 Windows 与 Linux 的 Qt 6 桌面工具，集中管理 **RTMP 服务、字幕烧录与 HLS 转码**。集成 FFmpeg、HTTP-FLV、HLS 播放和 FRP 配置入口，让推流与运行日志更易管理。

`C++` `Qt 6` `FFmpeg` `CMake` · **GPLv3**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YLive-cpp)

<a id="minecraft"></a>

### 🚆 Minecraft 与开发工具

#### MTR-YanYang · MTR 晏阳优化版

基于 Minecraft Transit Railway 4.0.5 的 **社区优化分支**，重点改善密集车站、轨道与列车场景中的渲染、内存分配及服务端重复计算。性能优化基线为 Minecraft 1.20.1 Fabric，并包含可选的 C++ 原生 OBJ 模型处理实现。

`Java` `C++` `Fabric` `Gradle` · **MIT** · **Fork 特例收录**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/MTR-YanYang)
[![Gitee Mirror](https://img.shields.io/badge/Gitee-Mirror-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group/MTR-YanYang)
[![Gitea Mirror](https://img.shields.io/badge/Gitea-Mirror-609926?style=flat-square&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group/MTR-YanYang)

> 感谢 [上游 Minecraft Transit Railway](https://github.com/Minecraft-Transit-Railway/Minecraft-Transit-Railway) 的开发者。本项目为社区分支，兼容范围与下载版本请查看仓库 README 和 Releases。

#### ColorfulSign · 彩色告示牌

为 Minecraft Java 版服务器带来基岩版风格的 **文字颜色与格式化** 体验。通过 `&` 格式码、十六进制颜色和彩虹效果，让聊天、告示牌、物品名称与书籍等内容更有表现力。

`Kotlin` `Paper API` `Gradle` · **GPLv3**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/ColorfulSign)
[![Gitee Mirror](https://img.shields.io/badge/Gitee-Mirror-C71D23?style=flat-square&logo=gitee&logoColor=white)](https://gitee.com/Yanyang-Technology-Group/ColorfulSign)
[![Gitea Mirror](https://img.shields.io/badge/Gitea-Mirror-609926?style=flat-square&logo=gitea&logoColor=white)](https://gitea.com/Yanyang-Technology-Group/ColorfulSign)

#### parse_sparkprofile · spark 性能报告解析器

使用 C 语言读取 Minecraft spark 的 `.sparkprofile` 原生 protobuf 数据，生成 **中文 Markdown 性能诊断报告**。覆盖运行环境、TPS / MSPT、热点方法、线程与调用树等信息，零第三方依赖，方便人工排查与后续自动化分析。

`C11` `Protobuf 解析` `Make` · **MIT**

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/parse_sparkprofile)

<a id="archive"></a>

### 📦 历史项目

以下仓库已归档，保留源码与版本演进记录，供学习和参考。

<details>
<summary><strong>展开查看：YLive 与三代 Python 晏阳邮箱</strong></summary>

#### YLive · Java 版直播工具

早期的 Java 直播处理项目，用于 RTMP 信号转 HLS / FLV 及字幕叠加。后续可关注桌面工具 **YLive-cpp**。

`Java` `FFmpeg` · **GPLv3** · 已归档

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/YLive)

#### Yanyn_Email.PyTheFirst · 初代 Python 晏阳邮箱

晏阳邮箱最早的 Python 实现，记录了邮件收发、后台线程与 HTML / 纯文本邮件处理等功能的早期探索。

`Python` · **GPLv3** · 已归档

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/Yanyn_Email.PyTheFirst)

#### Yanyn_Email.PyTheNewCode · 第二代 Python 晏阳邮箱

晏阳邮箱的第二版 Python 实现，延续早期客户端功能，并对界面与托盘退出行为进行调整和修复。

`Python` · **GPLv3** · 已归档

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/Yanyn_Email.PyTheNewCode)

#### Yanyn_Email.PyReNewCode · 第三代 Python 晏阳邮箱

晏阳邮箱的第三版 Python 实现，继续完善 SSL 端口、自定义 SMTP 服务器、线程处理与邮箱信息展示，保留向后续版本演进的开发记录。

`Python` · **GPLv3** · 已归档

[![GitHub Repo](https://img.shields.io/badge/GitHub-Repo-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Yanyang-Technology-Group/Yanyn_Email.PyReNewCode)

</details>

<div align="right">

[返回项目导航 ↑](#projects)

</div>

---

## 技术生态

围绕项目需求选择工具，让技术服务于实际体验。

| 领域 | 常用技术 |
| :--- | :--- |
| Web 与社区 | TypeScript · JavaScript · React · Next.js · Hono · Vite · Tailwind CSS · PostgreSQL |
| 跨平台应用 | C++ · Qt · Dart · Flutter · Python |
| 游戏与工具 | Java · Kotlin · C · Fabric · Paper API · FFmpeg |
| 构建与协作 | Git · CMake · Gradle · Docker · GitHub Actions |

<a id="team"></a>

## 核心成员

| 成员 | 角色 | 主要方向 | 一句话介绍 |
| :--- | :--- | :--- | :--- |
| <a href="https://github.com/shenui6"><img src="https://github.com/shenui6.png?size=80" width="40" alt="深水6 的头像"></a><br>**[深水6](https://github.com/shenui6)** | 创始人 / 组长 / 全栈开发 / 子服运维 | 桌面软件、网站与服务器运维 | 定方向、写核心、挖新坑。 |
| <a href="https://github.com/VasilyZa"><img src="https://github.com/VasilyZa.png?size=80" width="40" alt="小白的头像"></a><br>**[小白](https://github.com/VasilyZa)** | 副组长 / 全栈开发 / 主服运维 | Minecraft 插件、模组与服务器运维 | 管理组员、维护服务器。 |
| <a href="https://github.com/Leonmmcoset"><img src="https://github.com/Leonmmcoset.png?size=80" width="40" alt="LeonMMcoset 的头像"></a><br>**[LeonMMcoset](https://github.com/Leonmmcoset)** | 前端 / 后端工程师 | 网站开发与技术支持 | 让晏阳网站功能更多。 |
| <a href="https://github.com/SDFGTT"><img src="https://github.com/SDFGTT.png?size=80" width="40" alt="RAO_DIE 的头像"></a><br>**[RAO_DIE](https://github.com/SDFGTT)** | 建模师 | 模型制作 | 用最简单的软件做最细腻的模型。 |
| <a href="https://github.com/star201-linux"><img src="https://github.com/star201-linux.png?size=80" width="40" alt="star 的头像"></a><br>**[star](https://github.com/star201-linux)** | 前端工程师 | 网站开发与技术支持 | 让晏阳网站细节更多。 |

成员列表持续更新，也期待未来的你。

## 持续推进

- **社区体验**：持续完善晏阳社区网页与客户端，让讨论、资源分享和消息触达更加顺畅。
- **网站建设**：推进城市建设、轨道交通与技术组网站的内容和体验完善。
- **桌面工具**：继续打磨晏阳邮箱、Minecraft 启动器与直播工具。
- **开源协作**：完善文档、问题反馈与构建流程，让项目更容易使用和参与。

<a id="contribute"></a>

## 参与贡献

欢迎开发者、设计师、建模师，以及每一位愿意分享想法的使用者。

1. **发现问题**：在对应项目的 Issues 中描述复现步骤、使用环境与预期行为。
2. **提交改进**：阅读仓库中的贡献说明，提交代码、文档、翻译或设计建议。
3. **支持项目**：为喜欢的仓库点亮 Star，或向有需要的人分享。

**官方网站**：[tech.yanyn.cn](https://tech.yanyn.cn)  
**联系邮箱**：[techgroup@yanyn.cn](mailto:techgroup@yanyn.cn)

## 开源与许可

各项目采用独立的许可证：社区服务端与客户端采用 **AGPL-3.0-or-later**，MTR-YanYang 与 parse_sparkprofile 采用 **MIT**，其余已标明许可的软件项目主要采用 **GPLv3**。使用、修改与分发时，请以各仓库的许可证文件及相关声明为准。

项目功能、版本兼容范围及发布状态以对应仓库的最新说明为准。镜像可能存在同步延迟，最新源码与发布信息请优先查看 GitHub。

---

<div align="center">

**晏阳初升，代码不息。**

让我们一起构建更好的数字世界。

[探索 GitHub 组织 →](https://github.com/Yanyang-Technology-Group)

</div>
