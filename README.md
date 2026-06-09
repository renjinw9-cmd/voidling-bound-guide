# Voidling Bound Guide — 部署指南

## 📁 项目文件结构

```
voidling-bound-guide/
├── index.html          ← 首页
├── guide.html          ← 新手入门指南
├── voidlings.html      ← Voidlings 生物图鉴
├── evolution.html      ← 进化系统指南
├── combat.html         ← 战斗系统 & Build 指南
├── breeding.html       ← 繁育 & 基因拼接指南
├── css/
│   └── style.css       ← 全局样式（暗色科幻主题）
└── README.md           ← 本文件
```

## 🚀 免费部署步骤（30 分钟内上线）

### 第 1 步：注册 GitHub（5 分钟）
1. 打开 https://github.com
2. 注册账号（用邮箱即可）
3. 创建一个新仓库（Repository），命名如 `voidling-bound-guide`
4. 选择 **Public**（公开，免费）
5. 不要勾选任何初始化选项
6. 创建后记下仓库地址，如 `https://github.com/你的用户名/voidling-bound-guide`

### 第 2 步：上传代码到 GitHub（5 分钟）
**方法 A — 网页端直接上传（最简单）：**
1. 在仓库页面点击 **Add file → Upload files**
2. 把 `voidling-bound-guide` 文件夹里的所有文件直接拖进去
3. 点击 **Commit changes**

**方法 B — 用 GitHub Desktop（推荐，后期更新方便）：**
1. 下载 GitHub Desktop：https://desktop.github.com
2. Clone 你的仓库到本地
3. 把项目文件全部复制进去
4. 点 Commit → Push

### 第 3 步：Vercel 一键部署（2 分钟）
1. 打开 https://vercel.com
2. 点击 **Sign Up** → 选择 **Continue with GitHub** 登录
3. 授权后，点击 **New Project**
4. 选择你刚上传的仓库 `voidling-bound-guide`
5. 直接点 **Deploy**（Vercel 会自动识别这是静态 HTML 站）
6. 等待 30 秒，部署完成！你会得到一个免费域名：
   - 格式：`voidling-bound-guide.netlify.app`

### 第 4 步：验证网站（1 分钟）
1. 在浏览器打开 Vercel 给你的 `.vercel.app` 地址
2. 检查所有页面是否能正常打开
3. 手机打开看看移动端效果

## 🌐 绑定自定义域名（有收益后再买）

### 买域名
- **推荐平台：** Cloudflare Registrar（成本价，无加价）
- 域名格式建议：`voidlingboundguide.com`
- 价格：.com 约 $9/年，.pro 约 $2/年（首年）

### 绑定到 Vercel
1. Vercel 项目 → Settings → Domains
2. 输入你的域名 → Add
3. 按提示去 Cloudflare 添加 DNS 记录
4. 等待 DNS 生效（通常 5-10 分钟）

## 🔧 网站上线后要做的

### 1. 提交到 Google Search Console
- 打开 https://search.google.com/search-console
- 添加你的域名
- 提交 sitemap
- 这样 Google 才会收录你的网站

### 2. 内容更新节奏
- 游戏上线当天：补充 Voidlings 具体数据
- 第 1 周：每天新增 2-3 篇攻略文章
- 之后：每周更新 3-5 篇，追新内容

### 3. 申请 Google AdSense
- 网站内容达到 **30 篇以上原创文章** 后申请
- 通过后把广告代码替换掉页面里的占位符

### 4. 推广引流
- Steam 社区发完整攻略，末尾带网站链接
- Reddit r/VoidlingBound 回答问题引流
- YouTube 攻略视频简介里放链接

## ❓ 常见问题

**Q: Vercel 免费额度够用吗？**
A: 每月 100GB 带宽，攻略站初期完全够用。日访问量到几万都不会超额。

**Q: 代码怎么修改？**
A: 在 GitHub 上直接编辑文件 → Vercel 自动重新部署。或者本地改完重新上传。

**Q: 网站打不开怎么办？**
A: 把页面截图 + 错误信息发给 AI，让 AI 帮你排查。
