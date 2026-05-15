Codex 桌面端 Provider 切换工具 - OpenAI 登录账户版

文件说明：
- run-switch-codex-provider.bat：菜单版，可选 DeepSeek / OpenAI 登录账户 / 查看配置
- switch-to-deepseek.bat：直接切到 CCS DeepSeek
- switch-to-openai-login.bat：直接切到 OpenAI 官方登录账户
- switch-codex-provider.ps1：实际执行脚本

使用方法：
1. 解压。
2. 双击 run-switch-codex-provider.bat。
3. 选择：
   1 = 切换到 CCS DeepSeek
   2 = 切换到 OpenAI 官方登录账户
4. 切换完成后，完全退出 Codex 桌面端，再重新打开。

OpenAI 官方通道说明：
- 本版本不会要求输入 OPENAI_API_KEY。
- 切换 OpenAI 时会删除明显错误的 OPENAI_API_KEY=123456。
- OpenAI 官方通道依赖 Codex 桌面端中已登录的 OpenAI 账号。

DeepSeek 通道说明：
- 如果 CCS 报 401 Invalid proxy access key，请切换到 DeepSeek 时输入 CCS 的 Proxy Access Key。
