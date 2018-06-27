# logback-chinese-manual
logback 中文手册
> 翻译自 [The logback manual](https://logback.qos.ch/manual/index.html)
## 简介

Logback 继承自 log4j。

Logback 的架构非常的通用，适用不同的使用场景。Logback 被分成三个不同的模块：logback-core，logback-classic，logback-access。

logback-core 是其它两个模块的基础。logback-classic 模块可以看作是 log4j 的一个优化版本，它天然的支持 SLF4J，所以你可以随意的从其它日志框架（例如：log4j 或者 java.util.logging）切回到 logack。

logback-access 可以与 Servlet 容器进行整合，例如：Tomcat、Jetty。它提供了 http 访问日志的功能。

## The logback manual

手册包括了最新版本的 logback，总共有 150 多页，以及许多具体的例子，主要包含以下基本的和高级的特性：

- logback 的整体架构
- 讨论 logback 最好的实践以及反模式
- logback 的 xml 配置方式
- appender
- encoder
- layout
- filter
- 上下文诊断
- Joran - logback 的配置系统

logback 手册尽可能详细的描述了 logback API，包括它的特性以及设计原理。logback 手册适用于那些使用 java 但是是 logback 新手的人，也适合那些对 logback 有一定经验的人。在手册的帮助下，新手可以快速上手。
