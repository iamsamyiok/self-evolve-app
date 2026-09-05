# Self Evolve App（Android）

Self Evolve 智能体的 Android 客户端：WebView 壳加载已部署的对话界面。

## 使用

1. 从 GitHub Releases 下载 `app-debug.apk` 安装（debug 签名，需允许安装未知来源应用）
2. 打开即连到 Self Evolve 服务端

## 更换服务器地址

编辑 `app/build.gradle` 中 `SERVER_URL` 后提交，Actions 会自动重新构建并发布新 Release。

## 构建

推送到 main 分支自动触发 GitHub Actions 构建，产物上传到 Actions artifacts 与 Releases。
