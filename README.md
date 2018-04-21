# Sepicat 公告

## Sepicat 组件化方案

* SepiKit - 【尚未开源】总架构方案，Sepicat MVVM-C 简易非绑定架构协议方案。
* [Straycat](https://github.com/Sepicat/Straycat) - 用于 GitHub 额外数据的爬取，支持 **Kanna**、**SwiftSoup**、**正则表达式**三种爬取策略。
* Icecat（Ice）- 【尚未开源】LRU 缓存策略，思想来源于 **YYCache**。

## Sepicat 更新日志

### v1.2.2（正在施工）

#### App 变化

* 对于 Email 增加 App 内邮件发送功能
* 静态更新 follower 数据，并作出校准
* cell 点击后动画时机优化
* 修复 *Straycat* 爬虫策略，修正数据错误

#### GitHub 线上社区构建

* 开始搭建 Pages 主页
* 指定自定义皮肤社区规则

### v1.2.1

* Setting 定制化设定
  * 消息通知栏更换（很多小伙伴建议换掉 Octocat 小猫通知，因为遮挡内容）
  * 震动回馈开关
  * Trending 爬虫策略自选
    * Kanna - 基于 libxml.o，速度是 SwiftSoup 的 3 倍以上，但是在某些情况下会有数据爬取错误
    * SwiftSoup - Swift 原生 xml 爬虫，API 友好准确略较高
* Organisation Repos 和 Members 列表分页修复
* User Profile 页面支持对用户的 follow 功能

### v1.2.0

* 新增换肤功能（后期将增加皮肤分享社区）
* 将 Trending 爬虫策略修改为 Kanna
