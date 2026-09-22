## 更新

- 添加：OCR 流程集成二维码识别，可在识别结果中直接查看并选择二维码内容
- 添加：新增土耳其语、波斯语和俄语界面及内置插件本地化
- 添加：翻译语种新增维吾尔语，并适配内置 OCR、翻译服务及 RTL 文本方向
- 添加：OpenAI 翻译支持 Responses API 和自定义请求参数
- 添加：Google 翻译新增多种请求模式，可按需切换接口策略
- 添加：音频播放支持 WAV 和裸 PCM 格式，并保留 MP3 自动识别能力
- 添加：鼠标划词支持双击取词触发，并提供跟随鼠标的状态图标
- 添加：服务右键菜单新增重命名操作
- 添加：OCR、图片翻译与静默 OCR 可分别配置识别语种
- 优化：鼠标划词底层实现、状态图标动画与对比度，提升触发稳定性和可见性
- 优化：OCR 与图片翻译窗口工具栏支持响应式溢出布局
- 优化：设置界面布局、服务选择定位及翻译结果操作动画
- 优化：智能分段可正确拆分编号列表
- 优化：WebDAV 备份反馈更清晰，并补充 HTTP 请求与响应跟踪日志
- 优化：窗口激活与退出链路，提升 Ctrl+C+C 唤起前台及应用关闭的可靠性
- 修复：全屏应用占用快捷键时自动释放全局热键，并在瞬时注册冲突后重试
- 修复：翻译请求状态相互干扰、取消边界异常及 OpenAI 流式空结果处理
- 修复：内置 Google 翻译请求失败
- 修复：输入框、输出框及相关界面的 RTL 文本方向显示异常
- 修复：OCR 服务面板命令绑定及 OCR、图片翻译窗口保存图片内容不一致
- 修复：空词典结果错误显示耗时
- 修复：设置窗口关闭时密码字段被意外清空，以及主窗口失焦后未隐藏
- 修复：多处未本地化文本、无结果提示及波斯语和土耳其语翻译资源问题

## 插件开发

- `STranslate.Plugin` 更新至 `1.0.15`
- `IAudioPlayer` 新增 `PlayAsync(AudioData, CancellationToken)`，支持显式指定 MP3、WAV 和裸 PCM 音频格式
- 新增 `AudioData`、`AudioFormat`、`PcmAudioFormat` 和 `PcmSampleEncoding` 公共契约
- `LangEnum` 新增维吾尔语（`Uyghur`）

## 其他

- [插件市场](https://stranslate.zggsong.com/plugins.html)
- [使用说明](https://stranslate.zggsong.com/docs/)
- [集成调用](https://stranslate.zggsong.com/docs/invoke.html)
- [安装卸载](https://stranslate.zggsong.com/docs/(un)install.html)
- [FAQ](https://stranslate.zggsong.com/docs/faq.html)

**完整更新日志:** [v2.0.9...v2.0.10](https://github.com/STranslate/STranslate/compare/v2.0.9...v2.0.10)
