---
title: PreFlight Insight Privacy Policy
layout: default
---

# PreFlight Insight 隐私政策

**生效日期：2026 年 5 月 21 日**
**最后更新：2026 年 5 月 21 日**

---

## 一、关于本政策

PreFlight Insight（下称"本 App"）是一款由独立开发者制作的 iPad 与 macOS 桌面端工具，
帮助用户在本机解析与查看其个人持有的飞行计划包文件（.efbFPP）以及内嵌的 PDF 附件。

本 App **不收集、不存储、不上传任何用户的个人信息或文件内容到任何属于开发者的服务器**。
本政策旨在如实告知用户本 App 处理数据的方式。

---

## 二、本 App **不** 收集的信息

我们不收集以下任何信息：

- 你的姓名、邮箱、手机号、身份证号等个人身份信息
- 你的设备 ID、广告标识符（IDFA / IDFV）
- 你的位置信息、通讯录、相机、相册、麦克风
- 你的使用习惯、点击行为、崩溃日志（本 App 未集成任何统计或埋点 SDK）
- 你的飞行计划文件内容
- 任何形式的账户信息（本 App 不需要也不提供注册/登录）

---

## 三、本 App 在本机处理的数据

本 App 仅在你的设备本地处理以下数据，**所有处理过程不会离开你的设备**：

1. **你导入的 .efbFPP 文件**：解析后的航路点、气象、NOTAM、PDF 附件等信息，存储在 App 沙盒内，可随时通过 App 内"档案列表"或卸载本 App 清除。
2. **你的偏好设置**：例如界面语言、字号档位、风切变阈值等，存储在 iOS 标准的 UserDefaults，仅本机使用。
3. **AI 服务的 API Key（若你选择启用 AI 问答功能）**：存储在 iOS Keychain，仅本机使用，开发者无法读取。

卸载本 App 时，上述所有本地数据会被 iOS 系统一并删除。

---

## 四、关于 AI 问答功能（可选）

本 App **不提供生成式人工智能服务**，也不内置任何 AI 模型或 AI 服务 API Key。

如果你在"设置"中自行配置了第三方 AI 服务提供商的 API Key（例如阿里云 DashScope、智谱 GLM 等），并使用 AI 问答功能：

- 本 App 仅作为客户端壳，将你输入的文本和当前飞行计划的**摘要**（航路点、颠簸结果、NOTAM 列表等结构化数据）通过 HTTPS 直接发送到**你所配置的 AI 服务商**。
- 该 AI 服务商的隐私政策与数据处理规则适用，开发者无法替你做出任何关于该服务商的承诺。
- 开发者不参与、不中转、不缓存任何 AI 请求与响应。
- 你随时可以在"设置"中清除 API Key，停用 AI 功能。

常见 AI 服务商隐私政策参考链接（按你的配置实际为准）：
- 阿里云 DashScope: https://help.aliyun.com/document_detail/2587712.html
- 智谱 AI: https://open.bigmodel.cn/usercenter/privacy

---

## 五、第三方 SDK 与统计

本 App **未集成**以下任何第三方组件：

- ❌ Firebase / Google Analytics
- ❌ Crashlytics / Sentry
- ❌ 友盟 / Bugly / TalkingData
- ❌ 任何广告 SDK
- ❌ 任何统计、埋点、用户行为分析工具

本 App 唯一的网络出站是你在 AI 设置中显式配置的服务商域名，且仅当你主动发起 AI 问答时才会触发。

---

## 六、儿童隐私

本 App 面向成年专业人士使用，App Store 分级为 4+。本 App 不收集任何用户信息，因此不存在针对儿童的特殊隐私问题。

---

## 七、数据安全

由于本 App 不上传任何数据，所有数据保存在你的本机沙盒内，受 iOS 系统级安全机制保护：

- API Key 通过 iOS Keychain 加密保存
- App 沙盒文件受 iOS 应用隔离机制保护，其他 App 无法访问
- AI 请求通过 HTTPS（TLS）加密传输

---

## 八、你的权利

你对本 App 持有的本地数据拥有完全控制权：

- **查看**：在 App 内"档案列表"查看已导入的飞行计划包
- **删除单项**：长按列表项删除
- **清除全部**：卸载本 App，所有本地数据自动清除
- **撤回 AI 同意**：在"设置"中清除 API Key，AI 功能立即停用

---

## 九、政策变更

本政策如有变更，将更新本页面并修改顶部"最后更新"日期。重大变更将在 App 内通过弹窗或更新说明告知。

---

## 十、责任声明

本 App 是一款**信息呈现工具**，**不提供任何运行决策建议**，**不替代任何官方电子飞行包（EFB）系统、不替代航空公司签派放行流程**。本 App 输出的内容仅供参考，使用者需自行依据公司手册、官方 EFB 与签派指令进行飞行运行决策。

---

## 十一、联系方式

如对本政策有任何疑问，请通过以下方式联系开发者：

**邮箱：** preflight.insight@qq.com

---

<br>
<br>

# PreFlight Insight Privacy Policy (English)

**Effective Date: May 21, 2026**
**Last Updated: May 21, 2026**

---

## 1. About This Policy

PreFlight Insight (the "App") is an iPad and macOS desktop tool developed by an independent developer.
It helps users parse and view their personally-held flight plan package files (.efbFPP) and embedded PDF
documents locally on their own device.

The App **does not collect, store, or transmit any user personal information or file content to any
server owned by the developer**. This Policy explains how the App handles data, truthfully.

---

## 2. Information the App Does **NOT** Collect

We do not collect:

- Your name, email, phone, ID number, or any other personal identifiers
- Your device ID, advertising identifiers (IDFA / IDFV)
- Your location, contacts, camera, photo library, or microphone data
- Your usage patterns, click behavior, or crash logs (no analytics SDK is embedded)
- The contents of your flight plan files
- Any account information (no registration or login is required or provided)

---

## 3. Data Processed Locally

The App processes the following data **only on your device** — none of it leaves the device:

1. **Imported .efbFPP files**: Parsed waypoints, weather, NOTAMs, and PDF attachments are stored in
   the App's sandbox, removable any time via the in-App archive list or by uninstalling the App.
2. **Your preferences**: UI language, font size, wind shear thresholds etc., stored in iOS UserDefaults,
   used only on this device.
3. **AI service API Key (if you enable AI Q&A)**: Stored in the iOS Keychain, only on this device,
   inaccessible to the developer.

When you uninstall the App, iOS removes all of the above local data.

---

## 4. About the AI Q&A Feature (Optional)

The App **does not provide any generative AI service** and does not embed any AI model or AI API key.

If you configure a third-party AI provider's API Key in Settings (e.g. Alibaba Cloud DashScope, Zhipu GLM)
and use the AI Q&A feature:

- The App acts solely as a client shell, sending your typed text and the **structured summary** of the
  current flight plan (waypoints, turbulence results, NOTAM list, etc.) directly to **the AI provider
  you have configured**, over HTTPS.
- That provider's privacy policy and data handling rules apply. The developer cannot make any
  commitments on behalf of that provider.
- The developer does not participate in, relay, or cache any AI request or response.
- You may clear the API Key in Settings at any time, disabling the AI feature.

---

## 5. Third-Party SDKs & Analytics

The App contains **none** of:

- ❌ Firebase / Google Analytics
- ❌ Crashlytics / Sentry
- ❌ UMeng / Bugly / TalkingData
- ❌ Any advertising SDK
- ❌ Any analytics, telemetry, or behavioral tracking tool

The App's only outbound network connection is to the AI provider domain you explicitly configured,
and only when you actively send an AI Q&A request.

---

## 6. Children's Privacy

The App targets adult professionals (App Store rated 4+). Since the App collects no information,
no children-specific privacy concerns arise.

---

## 7. Data Security

Because no data is uploaded, all data resides in your local device sandbox, protected by iOS system
security:

- API keys are encrypted in the iOS Keychain
- App sandbox files are protected by iOS app isolation; other apps cannot access them
- AI requests are transmitted over HTTPS (TLS)

---

## 8. Your Rights

You have full control over local data held by the App:

- **View**: See imported flight plans in the in-App archive list
- **Delete one**: Long-press a list item to delete
- **Clear all**: Uninstall the App — iOS removes all local data
- **Withdraw AI consent**: Clear the API Key in Settings; the AI feature disables immediately

---

## 9. Policy Changes

If this Policy changes, we will update this page and revise the "Last Updated" date at the top.
Material changes will be announced in-App via an alert or release note.

---

## 10. Disclaimer

The App is an **information display tool**. It provides **no operational decision recommendations** and
**does not replace any official Electronic Flight Bag (EFB) system, nor any airline dispatch release
process**. The App's outputs are for reference only. Users must make flight operations decisions based
on their company manuals, official EFB, and dispatch instructions.

---

## 11. Contact

For any questions about this Policy, contact the developer at:

**Email:** preflight.insight@qq.com
