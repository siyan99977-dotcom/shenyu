# 神羽

> 神羽系列项目索引

神羽是一个长期维护的个人项目系列，包含 Android 客户端、Root 系统模块与实验性工具。  
本仓库只做索引与共享文档，各子项目在独立仓库中开发、发版、维护 Issue。

---

## 项目列表

| 项目 | 说明 | 状态 | 仓库 |
|---|---|---|---|
| **神羽·瑶光** | 开源、免登录、可独立运行的 DeepSeek 第三方 Android 客户端（Kotlin + WebView） | 活跃 | [siyan99977-dotcom/yaoguang](https://github.com/siyan99977-dotcom/yaoguang) |
| **神羽·天权（灵动岛）** | Root 原生 ELF 灵动岛，Vulkan + Dear ImGui，源码公开、非商业许可 | 活跃 | [siyan99977-dotcom/tianquan](https://github.com/siyan99977-dotcom/tianquan) |

### 神羽·瑶光

- 自带 API Key 直连 DeepSeek，无账号、无后端、无云同步
- 对话、深度思考、联网搜索、消息分支、引用、后台生成
- 星月命途（记忆星图）、本地知识库、角色卡、多 Provider
- 应用锁 + 生物识别、伪装图标、后台保活、桌面小组件
- 使用说明：[yaoguang/docs/使用说明.md](https://github.com/siyan99977-dotcom/yaoguang/blob/main/docs/使用说明.md)
- 下载：[Releases](https://github.com/siyan99977-dotcom/yaoguang/releases)

### 神羽·天权

- Root 原生 ELF 程序，向 SurfaceFlinger 申请图层，可覆盖状态栏
- Vulkan + Dear ImGui 绘制，胶囊 304 × 89
- 常驻显示时间、延迟、网速、帧率，通知展开，控制面板（音乐、手电筒、亮度、截图、天气、歌词）
- 安装：刷入模块 Zip 后重启；需要 Magisk / KernelSU / APatch
- 下载：[Releases](https://github.com/siyan99977-dotcom/tianquan/releases)

---

## 系列约定

- 每个子项目独立仓库、独立版本号、独立 Release
- 共享文档放在本仓库 `docs/`（后续补充）
- 版本规则：功能中位 +1，修复末位 +0.1，单位满 10 进一
- 代码默认 MIT；各项目可在自己仓库声明额外资源许可（天权为非商业源码许可）
- 不包含任何官方 DeepSeek / 第三方商标素材

## 联系

**QQ：3782073674**

## 许可

本索引仓库文档采用 MIT；各子项目以其仓库内 LICENSE 为准。
