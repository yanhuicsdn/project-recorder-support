# Project Recorder Privacy Policy / 项目录音隐私政策

Effective date: October 23, 2026 / 生效日期：2026 年 10 月 23 日

Project Recorder is an iOS recording and transcription app. This policy explains what happens to your information when you use it.

项目录音是一款 iOS 录音及转写应用。本政策说明使用应用时信息的处理方式。

## Information stored on your device / 保存在设备上的信息

Your projects, audio recordings, imported audio, transcripts, summaries, conversation history, and service settings are stored on your device. API keys are stored in the iOS Keychain. The app does not require an account. It does not include advertising or analytics SDKs. Speech transcription uses Apple's on-device speech facilities where supported. The app does not upload the original audio to its AI provider.

录音项目、录制及导入的音频、转写、摘要、问答历史和服务设置保存在你的设备上。API Key 保存在 iOS 钥匙串中。应用无需注册账号，不包含广告或分析 SDK。支持时使用 Apple 设备端语音转写功能。应用不会向 AI 服务上传原始音频。

## AI requests and third parties / AI 请求与第三方

AI features are optional. When you request a summary or answer, the app sends transcript text and your question to the AI service you selected: the TaoToken preset or a custom HTTPS endpoint compatible with OpenAI Chat Completions. A project-wide question sends the full available transcripts of every recording in that project in one request. A recording-specific question sends that recording's full transcript. Your API key is sent to the selected service to authenticate the request. That provider may process and retain the request under its own privacy terms; review them before entering a key or using AI. We do not control a custom provider's data practices.

AI 功能为可选功能。请求摘要或回答时，应用会把转写文字和问题发送到你选择的 AI 服务：TaoToken 预设服务或自定义的兼容 OpenAI Chat Completions 的 HTTPS 地址。项目问答会在一次请求中发送该项目每段录音的全部可用转写；单段问答发送该段转写全文。API Key 会发送到所选服务用于认证。该服务可能按其自身隐私条款处理和保留请求，请在输入密钥或使用 AI 前查看其条款。我们无法控制自定义服务的数据处理方式。

## Your choices, retention, and deletion / 你的选择、保留与删除

You can use recording, playback, transcription, and Markdown export without configuring AI. You can switch AI providers or remove a saved API key in Settings. You can delete a recording or project in the app; this removes its local app data. You can also remove the app and its local data using iOS. Copies you exported or shared must be deleted separately. For AI requests already sent, consult the selected provider's privacy policy and deletion process.

无需配置 AI 也可以录音、回听、转写和导出 Markdown。你可以在设置中切换 AI 服务或移除已保存的 API Key。你可以在应用内删除录音或录音项目，移除对应的本地应用数据；也可以通过 iOS 删除应用及其本地数据。已导出或分享的副本需要单独删除。已发送的 AI 请求请按所选服务的隐私政策和删除流程处理。

## Contact / 联系方式

For privacy questions, [open a support issue](https://github.com/yanhuicsdn/project-recorder-support/issues/new). Do not post private content or API keys in a public issue. / 如有隐私问题，请[提交支持问题](https://github.com/yanhuicsdn/project-recorder-support/issues/new)。请勿在公开问题中发布私人内容或 API Key。
