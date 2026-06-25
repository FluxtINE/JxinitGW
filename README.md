# 杰欣智能 RFID 会议签到系统 - 官网

> 泉州市杰欣智能科技有限公司 · RFID 无障碍会议签到系统官方网站

## 项目说明

这是一个**纯静态**企业官网，基于 HTML5 + CSS3 + 原生 JavaScript，无构建步骤、无依赖，可直接托管到 GitHub Pages / Vercel / Netlify / 任何静态服务器。

## 文件结构

```
jiexin-github-test/
├── index.html            # 入口（跳转至 promo-red.html）
├── promo-red.html        # 首页（红版 · 政务/党建大会风格）
├── about.html            # 走进杰欣
├── products.html         # 应用产品
├── tutorials.html        # 说明教程
├── purchase.html         # 购买产品（含客服/老板微信二维码）
├── images/               # 35 张图片资源（logo/产品/场景/二维码）
└── manuals/              # 2 个产品手册 PPT（可访问下载）
```

## 核心特性

- **5 个 HTML 页面 + 1 个入口**：`index.html → promo-red.html`
- **无障碍通道设计**：13.56MHz RFID 远距离感应，识别距离 80-120cm，支持轮椅无障碍通行
- **多模态交互**：弹窗、缩略图灯箱、轮播图、移动端导航
- **内容安全防护**：禁右键/拖拽/复制/调试快捷键 + 动态水印（含时间戳+浏览器指纹）
- **手机端长按识别二维码**：开放 iOS `touch-callout: default` + 微信内置识别能力
- **响应式设计**：桌面/平板/手机三端适配

## 本地预览

直接双击 `index.html` 即可在浏览器打开，或用本地服务器：

```bash
# Python 3
python -m http.server 8000

# Node.js
npx serve .
```

访问 `http://localhost:8000` 即可。

## 部署到 GitHub Pages

1. 在 GitHub 创建新仓库（如 `jiexin-intelligent-web`）
2. 把本目录所有文件 push 到 `main` 分支
3. 仓库 → Settings → Pages → Source 选 `main` 分支 / `/` 根目录
4. 等待 1-2 分钟，访问 `https://<用户名>.github.io/<仓库名>/`

## 联系方式

- **公司**：泉州市杰欣智能科技有限公司
- **地址**：泉州市丰泽区法学路1号引航文创园3楼303
- **电话**：13305958002
- **营业时间**：周一至周六 8:30-18:30

---

© 2014-2026 泉州市杰欣智能科技有限公司
