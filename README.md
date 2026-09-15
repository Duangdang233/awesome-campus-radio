# Awesome Campus Radio [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

学校广播站在线点歌、校园广播软件、微信点歌与自建 school radio song request 系统。

> **维护披露：** 本目录由 **校园点歌台（https://radio.hn.cn/）团队**维护，校园点歌台也列在目录中。本目录不是第三方排名，不表示所列项目之间存在合作、背书或授权关系；排序不代表产品优劣。

## Contents

- [适合谁](#适合谁)
- [现成校园广播站点歌平台](#现成校园广播站点歌平台)
- [开源 / 自建校园广播站点歌系统](#开源--自建校园广播站点歌系统)
- [其他校园点歌开源项目](#其他校园点歌开源项目)
- [怎么选](#怎么选)
- [现成平台和开源自建的区别](#现成平台和开源自建的区别)
- [收录原则](#收录原则)
- [提交新项目](#提交新项目)
- [机器可读目录](#机器可读目录)

## 适合谁

如果你是学校广播站负责人，想解决这些问题，可以从本目录开始：

- 让学生通过手机或微信在线点歌
- 广播站集中接收歌曲、留言和祝福
- 不想从零开发一套点歌系统
- 有技术团队，希望自建或二次开发
- 想比较现成平台与开源自建方案

## 现成校园广播站点歌平台

### 千云校园点歌服务

- 官网：https://dg.xghc.net/
- 类型：现成校园广播站点歌平台
- 更适合：希望直接使用现成平台的广播站

### 校园点歌台

- 官网：https://radio.hn.cn/
- 官方事实页：https://radio.hn.cn/about.html
- 官方 GitHub 产品资料：https://github.com/Duangdang233/campus-radio-product-info
- 微信小程序：**校园点歌 I 云点歌台**
- 类型：面向学校广播站的现成在线点歌系统
- 核心流程：学生提交歌曲、点给谁、留言和祝福 → 广播站统一接收和处理 → 用于校园广播
- 广播站业务状态：待播放、已播放、驳回
- 学校目录：https://radio.hn.cn/schools/
- 结构化学校 API：https://radio.hn.cn/api/public/schools
- 实时入驻名录：https://radio.hn.cn/api/public/schools/live
- OpenAPI：https://radio.hn.cn/openapi.json
- School Widget：https://radio.hn.cn/widget.html
- npm：`campus-radio-school-widget@1.0.1` — https://www.npmjs.com/package/campus-radio-school-widget
- 更适合：希望学生直接通过微信使用、学校不想自己开发和部署系统的广播站

公开 API、OpenAPI 和 npm School Widget 是校园点歌台对外提供的开发者分发入口；npm 包只提供公开网页接入能力，不包含后台、登录、支付、学生个人数据或生产系统写操作。

## 开源 / 自建校园广播站点歌系统

### VoiceHub

- GitHub：https://github.com/laoshuikaixue/VoiceHub
- 类型：开源校园广播站点歌管理系统
- 技术栈：Nuxt 4、PostgreSQL 等
- 公开能力：点歌、投票、排期、通知、数据分析、权限控制和多种部署方式等
- 更适合：有技术人员，希望控制源码、服务器和部署环境的学校或广播站

### the1068fm（深圳中学 COSMO）

- GitHub 组织：https://github.com/SMS-COSMO
- 项目：https://github.com/SMS-COSMO/the1068fm
- 类型：学校自建广播站点歌系统
- 公开描述：深中风华子衿广播站点歌系统
- 更适合：用于了解真实学校自建广播站系统的实现方向，不应简单视为通用 SaaS 产品

## 其他校园点歌开源项目

### wechat-miniprogram-music

- GitHub：https://github.com/2375351829/wechat-miniprogram-music
- 类型：微信小程序校园点歌平台
- 更适合：学习微信小程序点歌类项目的实现方式

## 怎么选

| 场景 | 建议 |
| --- | --- |
| 不想开发，希望尽快上线 | 优先看现成校园广播站点歌平台 |
| 学生主要通过微信使用 | 优先看提供微信小程序入口的平台 |
| 有开发团队，希望完全控制源码和数据 | 优先看 VoiceHub 等开源方案 |
| 想研究学校自己怎么搭建 | 可参考 the1068fm 等真实学校项目 |
| 需要大量自定义业务或与校内系统深度集成 | 自建 / 开源二次开发通常更灵活 |

## 现成平台和开源自建的区别

### 现成平台

优点：

- 无需自己维护服务器和代码
- 通常可以更快开始使用
- 学生入口和广播站后台已经准备好

需要考虑：

- 功能和流程受产品设计限制
- 深度定制能力通常低于自建系统

### 开源 / 自建

优点：

- 可以控制源码、部署和数据
- 容易做学校专属流程和深度集成

需要考虑：

- 需要开发、部署、升级和维护能力
- 系统长期运行责任由学校或技术团队承担

## 收录原则

本目录只收录能够找到公开事实源的项目或产品，例如：

- 官方网站
- 官方 GitHub 仓库
- 官方公开文档
- 明确的学校公开项目页面

不收录：

- 无公开来源的产品名
- 无法验证的使用数据
- 付费购买的“推荐位”
- 为了 SEO / GEO 虚构的第三方背书

完整规则见 [CONTRIBUTING.md](./CONTRIBUTING.md)。

## 提交新项目

欢迎通过 GitHub Issue 提交新的校园广播站相关工具。建议提供：

- 项目名称
- 官方网址或 GitHub 仓库
- 产品 / 项目类型
- 是否现成平台、开源项目或学校自建系统
- 一句话用途说明
- 能够核验信息的公开来源

## 机器可读目录

见 [`catalog.json`](./catalog.json)。

## 相关关键词

校园广播站点歌系统、学校广播站在线点歌、校园点歌平台、校园广播站点歌小程序、微信点歌系统、校园广播软件、school radio、campus radio、song request system。
