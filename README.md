<div align="center">

<img src="https://raw.githubusercontent.com/tuolola/tuolola/main/assets/profile-banner.svg" width="100%" alt="tuolola — AI, made practical. 从需求到可以使用的工具。" />

### 把 AI 做成可以使用的工具

AI 辅助软件工程 · AI 编程工具 · 跨端应用

<a href="https://jianglisoftware.com"><img src="https://img.shields.io/badge/SoftJL-在线体验-2563EB?style=for-the-badge" alt="SoftJL 在线体验" /></a>
<a href="https://jianglisoftware.com/tutorial"><img src="https://img.shields.io/badge/使用手册-在线阅读-0F766E?style=for-the-badge" alt="SoftJL 使用手册" /></a>

[主要项目](#主要项目) · [技术栈](#技术栈) · [正在探索](#正在探索) · [English](#english)

</div>

## 关于我

Hi，我是 **tuolola**。我在做 AI 辅助建模与编程工具：让需求、UML、测试和文档衔接起来，也让电脑上的 AI 编程会话能在手机上继续。

我关心的不只是生成结果，还有 **设计的来源、修改的影响，以及工具用起来是否顺手**。

## 主要项目

<table width="100%">
<tr><td>
<sub>01 / WEB · 自托管</sub>
<h3><a href="https://github.com/tuolola/SoftJL">SoftJL Community ↗</a></h3>
<p><strong>把需求、设计、测试与文档放进同一个 AI 工作台。</strong></p>
<p>面向软件类毕设与课程设计，关联需求、UML、测试用例与可编辑 Word 工程文档，支持来源追踪、变更影响检查和自带 OpenAI 兼容模型服务。</p>
<p><code>TypeScript</code> <code>React</code> <code>Next.js</code> <code>Fastify</code> <code>PlantUML</code></p>
<p><a href="https://github.com/tuolola/SoftJL">查看源码</a> · <a href="https://jianglisoftware.com">在线体验</a> · <a href="https://jianglisoftware.com/tutorial">使用手册</a></p>
</td></tr>
</table>

<table width="100%">
<tr><td>
<sub>02 / WINDOWS · 本地工作台</sub>
<h3><a href="https://github.com/tuolola/softJL-desktop">SoftJL Desktop ↗</a></h3>
<p><strong>在自己的电脑上，完成从需求到工程文档的 AI 建模。</strong></p>
<p>打开即用，无需注册登录。支持对话建模、分阶段工程建模与 Word 文档导出；项目和历史保存在本机，AI 调用使用自己配置的模型服务。</p>
<p><code>TypeScript</code> <code>Electron</code> <code>React</code> <code>Fastify</code> <code>PlantUML</code></p>
<p><a href="https://github.com/tuolola/softJL-desktop">查看源码与运行说明</a></p>
</td></tr>
</table>

<table width="100%">
<tr><td>
<sub>03 / ANDROID · AI 编程会话</sub>
<h3><a href="https://github.com/tuolola/cc-android-tunnel">CC Android Tunnel ↗</a></h3>
<p><strong>离开电脑后，用手机接着操作自己的 AI 编程工作台。</strong></p>
<p>使用 Kotlin 与 Jetpack Compose 构建原生 Android 客户端，连接自己的 CC Desk Tunnel 服务，延续 Claude Code 会话，查看流式回复、工具执行与会话历史。</p>
<p><code>Kotlin</code> <code>Jetpack Compose</code> <code>WSS</code></p>
<p><a href="https://github.com/tuolola/cc-android-tunnel">查看源码与使用说明</a> · <a href="https://github.com/tuolola/cc-android-tunnel/releases">下载与发布记录</a></p>
<p><sub>基于 <a href="https://github.com/sun168567/cc-desk-tunnel">sun168567/cc-desk-tunnel</a> 独立维护的非官方 Android 原生移植，需配合上游服务端使用。</sub></p>
</td></tr>
</table>

## 技术栈

<p>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&amp;logo=typescript&amp;logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/React-20232A?style=flat-square&amp;logo=react&amp;logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Next.js-171717?style=flat-square&amp;logo=nextdotjs&amp;logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/Node.js-417E38?style=flat-square&amp;logo=nodedotjs&amp;logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Electron-2B2E3A?style=flat-square&amp;logo=electron&amp;logoColor=9FEAF9" alt="Electron" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&amp;logo=kotlin&amp;logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&amp;logo=jetpackcompose&amp;logoColor=white" alt="Jetpack Compose" />
</p>

## 正在探索

- **可追溯的 AI 软件设计**：连接需求、模型与测试，帮助定位变更后需要复核的内容。
- **可检查的生成过程**：打磨任务状态、失败项重试、模型接入与实际用量展示。
- **顺手的移动端编程体验**：改善长会话阅读、流式输出、工具结果展示与断线恢复。

欢迎围绕 **AI 建模、AI 编程工具与跨端应用** 交流想法，也欢迎到项目仓库反馈问题与建议。

---

<a name="english"></a>

<details>
<summary><strong>English</strong></summary>

### Hi, I'm tuolola 👋

I build practical tools for AI-assisted software design and coding, across web, desktop and Android.

- **[SoftJL Community](https://github.com/tuolola/SoftJL)** — A self-hosted workspace connecting requirements, UML models, tests and editable engineering documents.
- **[SoftJL Desktop](https://github.com/tuolola/softJL-desktop)** — A Windows modeling workspace with local project storage and your own model service.
- **[CC Android Tunnel](https://github.com/tuolola/cc-android-tunnel)** — A native Android client for continuing Claude Code sessions through your own CC Desk Tunnel server. An independently maintained, unofficial port based on [cc-desk-tunnel](https://github.com/sun168567/cc-desk-tunnel).

Both SoftJL editions support OpenAI-compatible model services. I'm interested in traceable designs, inspectable AI workflows and tools that fit everyday use.

</details>
