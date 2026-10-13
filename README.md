# BooMO Privacy Policy

Last updated: October 13, 2026

BooMO is a Chrome extension for organizing, finding, and decluttering bookmarks. This policy explains how BooMO handles data. An English version and a Simplified Chinese version are provided below.

## English

### Data used by BooMO

BooMO accesses bookmark titles, URLs, IDs, folder structure, and related bookmark metadata through Chrome's bookmarks API. It uses this information to display bookmark cards and folders, search bookmarks, and carry out actions you choose, including creating, moving, sorting, renaming, deleting, and restoring bookmarks.

BooMO stores preferences, folder colors and stickers, daily review progress, recent review records, sticker collection and redemption status, and update notifications in browser storage. Review records may include bookmark identifiers, titles, URLs, and parent folder identifiers. These records support the daily review workflow and help avoid repeatedly showing recently reviewed bookmarks; they are not advertising or general browsing-activity logs.

BooMO uses website favicons to identify bookmarks. When a bookmark preview or suspected domain-for-sale check is needed, it requests the bookmarked page's public HTML and reads preview-image metadata or domain-sale indicators. It may load the referenced preview image from its website or image host. Fetched HTML is treated as data; BooMO does not execute scripts from that HTML.

BooMO does not read Chrome's browsing-history database, monitor visits to unrelated webpages, record keystrokes or pointer movements as analytics, or collect account passwords, payment details, health information, or precise location for its features.

### Storage and sharing

BooMO does not operate a developer-hosted server that receives your bookmarks, review records, preferences, or usage analytics. It does not sell user data or use it for advertising, creditworthiness, or lending decisions.

Bookmarks remain managed by Chrome. Extension settings and supported state are stored using Chrome's local and sync storage APIs. If Chrome sync is enabled, Chrome may synchronize bookmarks and supported extension data across your devices under your Chrome account and sync settings. Google handles that service under its own privacy policies.

Requests for public page HTML omit site credentials. Websites and image hosts contacted for previews can receive the requested URL, your IP address, and ordinary request information. Redirects and image requests follow the browser's network rules. These sites' own privacy policies apply; BooMO cannot control their server logs. Network requests are limited to providing the bookmark-related features described above, not sending a complete bookmark collection to the developer.

### Retention and your choices

Preferences and collection state are retained in browser storage while needed for the extension's features. Review records and bounded temporary preview/check caches are used for the relevant workflows, rather than kept as a developer-side history of your activity.

You can edit or delete bookmarks in BooMO or Chrome, change supported preferences in BooMO, manage Chrome sync, or remove the extension. Removing BooMO does not delete your Chrome bookmarks. Local extension storage and any synchronized copies are subject to Chrome's extension-removal and sync-storage behavior; removing the extension is not a guarantee that all Chrome-synchronized data has been deleted from every device. Use Chrome's data and sync controls when managing those copies.

### Permissions

- **bookmarks:** Read and modify bookmarks and folders as part of the bookmark-management interface.
- **favicon:** Display bookmark website icons.
- **storage:** Save preferences, appearance, review and sticker state, and update information using browser storage.
- **HTTP/HTTPS host access:** Read public bookmark-page information for previews and suspected domain-for-sale checks. Arbitrary bookmark domains require access beyond a fixed list of websites.

All extension executable code is included in the extension package. BooMO does not download and execute remote JavaScript or WebAssembly as extension logic.

### Limited Use

BooMO's use and transfer of information received from Google APIs adheres to the Chrome Web Store User Data Policy, including its Limited Use requirements. User data is used only to provide BooMO's bookmark-related features. It is not sold, used for personalized advertising, or transferred for unrelated purposes. The developer does not receive bookmark content through an application backend or review it as part of operating the extension.

### Changes and contact

This policy will be updated if BooMO's data practices change. The revision date appears at the top of this document.

For privacy questions, use the [BooMO privacy repository's issue tracker](https://github.com/charonzen/boomo-privacy/issues). Issues are public: do not include private bookmarks, credentials, or other sensitive information.

---

## 简体中文

### BooMO 使用哪些数据

BooMO 是用于整理、查找和精简 Chrome 书签的扩展程序。它通过 Chrome 书签接口读取书签标题、网址、标识、文件夹结构及相关元数据，用于展示书签卡片和文件夹、搜索书签，以及执行你选择的新建、移动、排序、重命名、删除和恢复操作。

BooMO 在浏览器存储中保存偏好设置、文件夹颜色和贴纸、每日精简进度、近期整理记录、贴纸收藏和兑换状态，以及更新提示。整理记录可能包含书签标识、标题、网址和父文件夹标识，用于支持每日精简流程并避免反复展示近期已整理的书签，而非广告分析或一般网页浏览行为记录。

BooMO 使用网站图标帮助识别书签。当需要网页预览或“疑似域名出售”检测时，会请求书签网页公开的 HTML，读取预览图元数据或域名出售特征，并可能从相应网站或图片托管服务加载预览图。获取的 HTML 仅用于数据解析，不执行其中的脚本。

BooMO 不读取 Chrome 浏览历史数据库，不监控与上述功能无关的网页访问，不将击键或鼠标移动记录为分析数据，也不为其功能收集账户密码、付款信息、健康信息或精确位置。

### 存储与共享

BooMO 没有接收你的书签、整理记录、偏好设置或使用分析数据的开发者自建服务器，不出售用户数据，不将其用于广告、信用评估或贷款决策。

书签由 Chrome 管理。扩展设置和受支持的状态通过 Chrome 本地存储和同步存储接口保存。如果开启 Chrome 同步，Chrome 可能根据你的账户和同步设置，在设备间同步书签及受支持的扩展数据。该服务由 Google 提供，并适用其隐私政策。

公开网页 HTML 请求不携带网站登录凭证。提供网页或预览图的网站、图片托管服务可能收到请求网址、IP 地址及常规请求信息；重定向和图片请求遵循浏览器的网络规则。这些服务适用其自身隐私政策，BooMO 无法控制它们的服务器日志。上述网络请求仅用于书签相关功能，不会把完整书签集合发送给开发者。

### 保留时间与用户控制

偏好设置和收藏状态在扩展功能需要期间保存在浏览器存储中。整理记录以及容量受限的临时预览和检测缓存用于相应功能，并非开发者侧长期保存的用户活动记录。

你可以在 BooMO 或 Chrome 中修改、删除书签，在 BooMO 中调整受支持的偏好设置，管理 Chrome 同步，或卸载扩展。卸载 BooMO 不会删除 Chrome 书签。本地扩展存储及同步副本的处理取决于 Chrome 的卸载和同步存储机制；卸载不代表所有设备上的 Chrome 同步数据都已删除。需要管理这些副本时，请使用 Chrome 的数据与同步设置。

### 权限用途

- **bookmarks：** 为书签管理界面读取和修改书签及文件夹。
- **favicon：** 显示书签网站图标。
- **storage：** 在浏览器中保存偏好设置、外观、精简和贴纸状态及更新信息。
- **HTTP/HTTPS 网页访问：** 为预览和“疑似域名出售”检测读取公开的书签网页信息。由于书签可以指向任意网站，不能仅限于固定网站列表。

扩展的可执行代码均包含在安装包中，不会下载并执行远程 JavaScript 或 WebAssembly 作为扩展逻辑。

### 有限使用声明

BooMO 对从 Google API 获取的信息的使用和转移遵守 Chrome Web Store 用户数据政策，包括有限使用要求。用户数据仅用于 BooMO 的书签相关功能，不出售、不用于个性化广告，也不为无关目的转移。开发者不会通过应用后端接收或在运营扩展时查看书签内容。

### 政策更新与联系

如果 BooMO 的数据处理方式发生变化，本政策会相应更新，修订日期见文档顶部。

隐私问题可通过 [BooMO 隐私政策仓库的 Issues](https://github.com/charonzen/boomo-privacy/issues) 联系。Issues 是公开的，请勿提交私人书签、登录凭证或其他敏感信息。
