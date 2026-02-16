# 除夕赛博烟花

一个具有东方美学与赛博感的除夕烟花网页。

## 特点

- 🎆 Canvas粒子烟花系统，汉字词库（马、万事如意、发财、平安）
- 💌 弹幕祝福系统，可扫码发送祝福
- 🌙 克制、温暖、略带赛博感的视觉气质
- 🎵 预留音频接口

## 本地运行

```bash
cd /Users/imac/cyber-new-year-blooms
python3 -m http.server 8080
```

然后在浏览器打开：`http://localhost:8080`

## 部署到Vercel（推荐）

### 方法1: 通过Vercel网站

1. 访问 [vercel.com](https://vercel.com)
2. 用GitHub账号登录
3. 点击 "Add new..." → "Project"
4. 选择 "Upload" 或直接拖拽本文件夹
5. 部署完成即可获得分享链接

### 方法2: 使用Vercel CLI（需安装）

```bash
npm i -g vercel
vc --prod
```

### 方法3: 通过GitHub

1. 在GitHub创建新仓库
2. 上传本文件夹内容
3. 在Vercel导入GitHub仓库即可自动部署

## 分享链接

部署后你会获得类似：`your-project-name.vercel.app` 的链接，直接分享给朋友即可。
