# WebHomeTV 下载：基于 FongMi 二开的高级影视TV，支持 WebHome 自定义首页

如果你正在找「WebHomeTV 下载」「WebHTV 下载」「WebHomeTV APK」「WebHomeTV GitHub」或者「支持自定义首页的影视TV」，这篇文章会把 WebHomeTV 是什么、GitHub 下载地址、夸克网盘和光鸭网盘下载地址，以及安装包应该怎么选整理在一起。

WebHomeTV 是基于 FongMi / CatVod 生态二次开发的 Android 影音应用。它保留了 FongMi 原有的点播、直播、Spider、解析、投屏、本地 HTTP 服务等能力，同时重点增强了 WebHome 自定义首页、App Native SDK、网盘链接检测、站点健康排序、观影记录同步、远程管理和 Nostr/TMDB 推荐首页等功能。

<!--more-->

## WebHomeTV 下载地址

夸克网盘下载：

```text
【这里填写你的夸克网盘下载地址】
```

**光鸭网盘（免会员不限速）**：

```text
【这里填写你的光鸭网盘下载地址】
```

GitHub 开源项目地址：

```text
https://github.com/fish2018/webhtv
```

GitHub 下载地址：

```text
https://github.com/fish2018/webhtv/releases
```

说明：如果你只是普通用户，优先使用夸克网盘或**光鸭网盘下载**更方便；如果你懂 GitHub，可以到 Releases 页面里下载最新版安装包。

## WebHomeTV 是什么

WebHomeTV 可以理解为 FongMi 生态里的高级增强版。它不是简单换皮，而是把「首页」做成了可以开发、可以扩展的 WebHome。

普通 TVBox / 影视仓 / FongMi 通常是通过配置接口加载首页、分类、搜索和播放规则；WebHomeTV 在这个基础上，进一步允许开发者用 HTML、CSS、JavaScript 定制首页，再通过 App 暴露的 Native 能力完成搜索、播放、跨域请求、资源代理、最近观看、网盘检测和状态同步。

简单理解：

- FongMi / CatVod：提供影视壳、点播、直播、Spider、解析等基础能力。
- WebHomeTV：在这些基础能力上，增强 WebHome 自定义首页和高级管理能力。
- WebHome：可以把首页做成更像网页应用，而不是传统固定列表。

如果你只是普通追剧用户，WebHomeTV 可以当作一个功能更强的影视TV来用；如果你会折腾配置、站点、脚本和自定义首页，它的可玩性会更高。

## WebHomeTV 适合哪些人

WebHomeTV 更适合下面几类用户：

- 想找 FongMi 增强版的人。
- 想使用 WebHome 自定义首页的人。
- 想体验 Nostr / TMDB 推荐首页的人。
- 想要网盘链接检测功能的人。
- 想在局域网里管理配置、文件、接口和登录态的人。
- 想做多设备同步、观影记录同步的人。
- 熟悉 TVBox / FongMi / CatVod 配置，想进一步折腾高级能力的人。

如果你只是想装一个简单播放器，影视仓、OK影视或 FongMi 蜂蜜版可能更容易上手。WebHomeTV 的优势在于增强功能多，适合愿意折腾的人。

## WebHomeTV 的功能亮点

### 1. WebHome 自定义首页

WebHomeTV 的核心亮点是 WebHome 自定义首页。开发者可以用 HTML、CSS、JavaScript 定制首页，让 CSP 站点首页变成真正可开发的网页应用。

这和传统影视壳应用不太一样。传统应用更多是固定界面 + 配置接口；WebHomeTV 则给了首页更高的自由度。

### 2. App Native SDK

WebHomeTV 提供 App Native 能力，让 WebHome 页面可以调用应用内部能力，例如搜索、播放、跨域请求、资源代理、最近观看、网盘检测和状态同步。

对普通用户来说，这意味着某些自定义首页可以做得更好用；对开发者来说，这意味着可以写出更贴合自己需求的首页和扩展。

### 3. 网盘链接检测

WebHomeTV 内置网盘分享链接有效性检测，WebHome 和本地 HTTP API 都可以调用。

如果你经常使用网盘资源，这个功能会比较实用：可以提前判断链接是否可用，减少点进去才发现失效的情况。

### 4. 站点健康排序

WebHomeTV 支持自动学习站点搜索、详情和播放成功率。搜索和换源时，可以优先使用更可用的站点。

简单说，它会尽量把更稳定、更容易成功的站点排到前面，降低来回试错的成本。

### 5. 管理页面和局域网管理

WebHomeTV 可以在 App 内启动局域网浏览器管理页，用于管理本机或远端设备的文件、登录态、同步目录、站点注入、接口、搜索和推送等内容。

这类功能对电视端尤其有价值，因为电视上用遥控器输入很麻烦；如果能在局域网里用手机或电脑管理，效率会高很多。

### 6. 一键同步和观影记录同步

WebHomeTV 支持在同一局域网设备间同步配置、站源数据、登录态、WebHome 数据、搜索记录、观看历史、收藏和应用设置。

如果你有多台设备，比如客厅电视、卧室盒子和 Android 手机，这类同步能力会很实用。

### 7. Nostr / TMDB 推荐首页

WebHomeTV README 中提到 Nostr / TMDB 推荐首页相关能力。对用户来说，这类首页可以让内容推荐、首页展示和发现体验更灵活。

如果你不想只看传统分类列表，可以尝试 WebHomeTV 的自定义首页玩法。

## 安装包怎么选

WebHomeTV 的 GitHub Releases 页面可能会出现多个 APK 文件。新手看到 `mobile`、`leanback`、`arm64_v8a`、`armeabi_v7a`、`debug`、`release` 这类文件名，容易不知道下载哪个。

下面做一个简单扫盲。

### 设备类型

- `leanback` = 电视版，适合 TV、电视盒子、机顶盒。
- `mobile` = 手机版，适合手机、平板。

### 架构版本

- `arm64_v8a` = 64 位版本，适合新款设备。
- `armeabi_v7a` = 32 位版本，适合老款设备，兼容范围更广。

### 构建类型

- `release` = 正式构建，普通用户优先选择。
- `debug` = 测试构建，适合调试或临时测试。

### 新手选择指南

| 你的设备 | 推荐选择 |
|---|---|
| 电视 / 电视盒子 / 机顶盒 | `leanback + armeabi_v7a + release` |
| 新款电视盒子 | `leanback + arm64_v8a + release` |
| 手机 / 平板 | `mobile + arm64_v8a + release` |

如果你不确定设备架构，电视盒子优先试 `leanback + armeabi_v7a`，手机和平板优先试 `mobile + arm64_v8a`。如果安装失败，再换另一个架构版本。

## WebHomeTV 和 FongMi、OK影视、影视仓有什么区别

### 和 FongMi 蜂蜜版相比

FongMi 蜂蜜版更像基础开源影视TV应用，整体更偏简洁稳定。WebHomeTV 基于 FongMi 生态继续增强，重点是 WebHome 首页、网盘检测、管理页面、远程托管、一键同步等高级能力。

如果你只想简单看剧，FongMi 蜂蜜版更轻；如果你想折腾自定义首页和高级扩展，WebHomeTV 更适合。

### 和 OK影视相比

OK影视更偏向在蜂蜜版基础上增加用户常用功能，比如字幕、弹幕、播放器能力等。WebHomeTV 更偏向首页开发、Native SDK、管理能力和多设备协同。

简单说，OK影视偏功能丰富，WebHomeTV偏高级扩展。

### 和影视仓相比

影视仓在 TVBox 魔改应用中知名度很高，上手门槛低，适合普通用户。WebHomeTV 功能更复杂，更适合有折腾需求的人。

## WebHomeTV 怎么配置接口

安装好 WebHomeTV 后，如果首页没有内容，需要先配置接口。流程和 TVBox、影视仓、FongMi 类似。

如果你想看带截图的详细步骤，可以看这篇图文教程：

[**TVBox / 影视仓接口配置教程（图文版）**](https://b.zhuiju.me/archives/5/)

常见步骤如下：

1. 打开 WebHomeTV。
2. 进入「设置」或「配置」页面。
3. 找到「配置地址」。
4. 粘贴接口地址。
5. 点击「确定」或「保存」。
6. 返回首页，等待数据加载。

示例配置地址：

```text
http://www.饭太硬.net/tv
```

注意：配置地址只是示例，不能保证长期可用。接口失效时，换一个配置源即可。

如果你需要更多可复制的接口地址，可以看这篇持续更新的配置地址列表：

[**TVBox影视仓接口/配置地址，持续更新ing**](https://b.zhuiju.me/archives/3/)

## 常见问题

### WebHomeTV 是不是 FongMi？

WebHomeTV 是基于 FongMi / CatVod 生态二次开发的 Android 影音应用。它保留 FongMi 的很多基础能力，同时增加了 WebHome 自定义首页、管理页、网盘检测、同步等增强功能。

### WebHomeTV 适合新手吗？

如果只是安装、配置接口、看剧，新手也可以使用。但 WebHomeTV 的高级功能比较多，想完全发挥它的价值，需要一定折腾能力。

### WebHomeTV 下载哪个版本？

电视盒子选 `leanback`，手机和平板选 `mobile`。新设备优先 `arm64_v8a`，老设备优先 `armeabi_v7a`。普通用户优先下载 `release` 版本。

### 安装后首页空白怎么办？

大概率是没有配置接口，或者当前接口失效。先检查配置地址是否填写正确，再换一个接口测试。

### WebHomeTV 的网盘检测有什么用？

网盘检测可以帮助判断分享链接是否还有效，减少点进去才发现失效的情况。具体效果取决于配置、网盘类型和当前版本能力。

## 使用提醒

WebHomeTV 本身是播放器和聚合工具，配置接口里的内容来自第三方源。不同接口的稳定性、内容来源和可用性都不同，需要自行判断。

本文只做软件介绍、下载入口整理和使用说明，不存储、不上传影视内容，也不保证任何第三方接口长期可用。观看影视内容请遵守当地法律法规，支持正版。

## 总结

WebHomeTV 适合想要更强扩展能力的影视TV用户。它不是单纯的 FongMi 换皮，而是在 FongMi / CatVod 生态基础上增加了 WebHome 自定义首页、网盘检测、站点健康排序、管理页面、远程托管、一键同步和观影记录同步等高级能力。

下载时记住一个简单规则：电视盒子选 `leanback`，手机平板选 `mobile`；新设备优先 `arm64_v8a`，老设备优先 `armeabi_v7a`；普通用户优先选 `release`。

---

更多追剧资源，关注**Awesome Zhuiju Free**

GitHub地址：https://github.com/laoma528/awesome-zhuiju-free
