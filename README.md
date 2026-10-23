# Project Recorder support / 项目录音支持

Project Recorder groups multiple recordings in one project. You can record or import audio, transcribe it on your device, review each recording, ask questions about one recording or the complete project, and export transcripts and conversations as Markdown.

项目录音可将多段录音放在同一个录音项目中。你可以录制或导入音频、在设备上转写、查看单段录音、基于单段或整个项目提问，并以 Markdown 导出转写和对话。

For help, bug reports, or privacy questions, [open a support issue](https://github.com/yanhuicsdn/project-recorder-support/issues/new). Please do not include API keys, private audio, or transcripts in a public issue. You can read the [privacy policy](PRIVACY.md) here.

如需帮助、反馈问题或咨询隐私事项，请[提交支持问题](https://github.com/yanhuicsdn/project-recorder-support/issues/new)。公开问题中请勿粘贴 API Key、私人音频或转写内容。请阅读[隐私政策](PRIVACY.md)。

## Common questions / 常见问题

**Where are my recordings? / 录音在哪里？** Recordings and transcripts are stored on your device. Export important content before deleting the app or a project. / 录音和转写保存在本机。删除应用或录音项目前，请先导出重要内容。

**Why is AI unavailable? / 为什么无法使用 AI？** Open AI Service settings, select TaoToken or your own OpenAI Chat Completions compatible HTTPS service, enter a valid model and API key, then try again. The selected provider may charge for API use. / 打开“AI 服务”设置，选择 TaoToken 或自定义兼容 OpenAI Chat Completions 的 HTTPS 服务，填写模型和 API Key 后重试。所选服务可能单独收费。

**Does AI receive audio? / AI 会收到音频吗？** No. When you request an AI summary or answer, the app sends relevant transcript text to the provider you selected. Project questions include the full available transcripts of that project. / 不会。请求 AI 摘要或回答时，应用向你选择的服务发送相关转写文字。项目问答包含该项目所有可用的转写全文。
