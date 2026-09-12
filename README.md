# A-Home

All-in-one 个人工作台，在一个主页中集中管理看板、计划、任务、笔记、倒数日、进度与生活记录。

## 主要功能

- 可自定义 Banner、主题、模块排序与主页布局。
- 月历、天气、倒数日、番茄钟、座右铭和最近文件六个生活模块。
- 今日日程、进度管理、目录、画板、计划和六级任务管理。
- 支持任务创建、编辑、分组、筛选、循环、完成历史及跨分区联动。
- 支持亮色、深色和小岛主题，并适配桌面端与移动端布局。
- 使用 Vault 内 Markdown/JSON 数据，便于随仓库备份与多设备同步。

## 付费与激活

A-Home 是需要购买许可证并激活后使用完整功能的付费插件。未激活时可以打开只读主页预览，并进入插件设置完成激活。

激活码请通过作者的正式销售或联系渠道获取：

- [购买 A-Home 激活码](https://wzyp.cn/shop/NIAR958A)
- QQ群：603045364
- 微信：VinVinVin444
- [Bilibili](https://space.bilibili.com/3493128231193555)
- [小红书](https://xhslink.cn/m/8ZWjZpJc6sK)
- [抖音](https://v.douyin.com/bqTGipbnW_8/)

## 网络访问

A-Home 只在下列场景访问网络：

1. 激活许可证，以及在离线许可进入续签窗口、过期恢复、可信时间异常或用户主动验证时连接授权服务器。
2. 用户自行填写天气与地点接口后，天气模块访问用户指定的服务。
3. 用户主动打开作者链接、任务网站链接或自行配置的外部 Banner 图片。

授权服务可能接收激活或验证所必需的数据类别：激活码（仅激活时）、产品代码、匿名设备 ID、设备名称与平台信息，以及续签时的离线许可证。插件不会把激活码写入设置或日志。

## 隐私

- 无客户端遥测。
- 无使用行为分析。
- 无广告跟踪。
- 不出售用户数据。

完整说明见 [PRIVACY.md](./PRIVACY.md)。

## 数据与备份

业务数据主要保存在当前 Vault 的 `A_Shared_Data` 与 `A_Dashboard_Data` 目录。插件设置和离线许可证保存在当前 Vault 的插件配置数据中；匿名设备 ID 保存在当前 Vault 配置目录下的 `a-license/device.json`。

备份整个 Vault 时，上述数据会一并备份。跨设备同步插件配置目录时，请注意每个授权设备仍受许可证设备数量限制。

## 安装与更新

正式上架后，请通过 Obsidian Community Plugin Directory 安装和更新。不要从非官方来源下载修改过的构建文件。

## Source and review

A-Home is a paid, license-activated plugin. Its complete TypeScript source code is maintained in a private repository. Release builds are submitted to the Obsidian Community Directory review and scanning process.

The plugin connects to its licensing service only for activation and periodic license validation. It sends the minimum license-related data described above. Weather and geocoding requests are made only after the user provides compatible endpoint URLs. A-Home contains no client telemetry, usage analytics, or advertising trackers.

## Third-party software

Third-party notices are available in [THIRD_PARTY_NOTICES.md](./THIRD_PARTY_NOTICES.md).

## Support

作者：全平台-岛民Vin。问题反馈与购买咨询可通过上述作者渠道联系。

## License

A-Home is proprietary commercial software distributed under the terms in [LICENSE](./LICENSE). Third-party components remain governed by their respective licenses.
