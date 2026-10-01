# 神人大乱斗杀 · 下载兼容页

**最新内容更新：第 4 版**

包含第 3 版的手机子页面、军八、2v2、全屏背景与遮罩修复，并补上开局换牌期间的菜单限制，避免窗口叠加。已安装 0.1.4 的玩家下载内容更新后完全退出、重新打开即可生效。下方手机修正版 APK 内置第 3 版，进入菜单后可下载第 4 版；更新原生启动器的后台检查行为仍需覆盖安装修正版一次。


**0.1.4 手机修正版与内容更新第 3 版（2026-10-01）**

推荐下载 [Android 全屏修正版 APK（约 239.9 MiB）](https://github.com/3206789615/shenren-game-download/releases/download/v0.1.4/ShenrenDaluandou-0.1.4-Android-Fullscreen.apk)。版本仍为 0.1.4，Android 版本代码为 6，包名与签名保持一致，可直接覆盖安装并保留存档。

修复原标题和 UI 资源缺失、普通页面切换空白，以及手机子页面、军八和 2v2 排版。控件保留统一设计坐标并等比适配安全区域，背景及弹窗遮罩独立铺满屏幕；不再拉宽控件容器或按位置分段移动武将。较慢的对局加载显示独立背景与进度条。保留原有卡牌和武将美术，日势力图标保持原样，初始招募令为 100 张。

修正版先进入游戏菜单，再后台检查内容更新；没有更新或网络不可用时不会遮住菜单等待。下载新内容后关闭并重新打开游戏生效。已装旧 0.1.4 的玩家需要覆盖安装这个修正版一次，才能更新最早运行的启动器；后续兼容的资源、武将、技能及 AI 代码更新仍通过热更新完成。已装 0.1.4 的 Android 和 Windows 玩家均可直接热更新第 3 版布局修复；覆盖安装修正版另用于更新原生启动器。

手机布局已做长屏、普通宽屏、平板比例和刘海安全区域模拟验证；Android 签名、双架构、离线资源及热更新 DLL 已验证，尚未完成 Android 真机运行验证。


当前版本：**0.1.4（2026-10-01）**。

请前往[主下载仓库](https://github.com/3206789615/shenren-game-download)，或直接下载：

- [Android APK](https://github.com/3206789615/shenren-game-download/releases/download/v0.1.4/ShenrenDaluandou-0.1.4-Android-Fullscreen.apk)
- [Windows 完整 ZIP](https://github.com/3206789615/shenren-game-download/releases/download/v0.1.4/ShenrenDaluandou-0.1.4-Windows.zip)
- [最新版与更新说明](https://github.com/3206789615/shenren-game-download/releases/latest)

0.1.4 支持资源与 C# 游戏代码热更新；旧版本先覆盖安装一次 0.1.4，后续兼容的武将、技能、AI 和资源更新可在启动时下载，无需重新安装。新档初始招募令为 100 张，原有美术保持原样。

Android 安装后显示“神人大乱斗杀”和原游戏图标，保留旧包名及签名。Windows 请完整解压后运行 `ShenrenDaluandou.exe`。Android 尚未完成真机运行验证。

本仓库保留旧客户端需要的更新清单和实际安装包，供历史版本自动更新使用，不包含 Unity 工程源码。
