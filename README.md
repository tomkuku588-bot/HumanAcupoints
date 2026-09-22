# 人体位图解协议页面

本仓库用于公开展示人体位图解（HarmonyOS，包名 `com.xmgod.rentixuewei`）的隐私政策和用户协议，供应用市场审核和用户查看。

## 页面

- `index.html`：协议入口页
- `privacy-policy.html`：隐私政策，支持中文和英文
- `user-agreement.html`：用户协议，支持中文和英文
- `legal-manifest.json`：协议页面元数据

公开访问地址预计为：

- `https://tomkuku588-bot.github.io/HumanAcupoints/privacy-policy.html`
- `https://tomkuku588-bot.github.io/HumanAcupoints/user-agreement.html`

## 部署

仓库包含 GitHub Pages Actions 工作流。推送到 `main` 后，GitHub Actions 会发布当前静态文件。若仓库尚未启用 Pages，请在 GitHub 仓库 `Settings -> Pages` 中选择 `GitHub Actions` 作为部署来源。

## 内容依据

隐私政策和用户协议依据人体位图解 HarmonyOS 版（1.0.0，compatibleSdkVersion 5.0.0(12)）的实际行为编写：

- 不申请任何系统权限（module.json5 无 requestPermissions）。
- 不联网，无网络权限；全部图解数据内置在应用中。
- 不接入任何第三方 SDK、广告、统计、账号、支付或云同步服务（oh-package.json5 无依赖）。
- 收藏与设置仅保存在设备本地应用沙箱。
- 用户协议含医疗免责声明：穴位内容仅供学习参考，不构成医疗建议。

应用版本或集成的服务变更时，需同步更新两份协议中的对应章节和版本号、日期。注意：`D:\Harmony_Code\Apps\HumanAcupoints` 下的 `人体位图解_3.2.1s` 是安卓版参考 APK（集成 AdMob，包名不同），协议内容以鸿蒙工程实际配置为准。
