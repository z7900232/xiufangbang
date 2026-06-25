# 🏠 修房帮 - 装修·维修·建房一站式平台

> 本地装修·维修·建房一站式平台
> 对标「美团」本地生活 + 「滴滴」师傅派单模式
> 专注：县城及周边乡镇 装修、维修、自建房、建材、家政房屋类全部业务

## 部署指南

### Vercel（推荐）
```bash
npm i -g vercel
vercel --prod
```

### GitHub Pages
```bash
git remote add origin <你的仓库地址>
git push -u origin main
# 在仓库 Settings → Pages 选择 main 分支即可
```

### 传统服务器
将本目录所有文件上传到 Web 服务器（Nginx/Apache）即可。

## 技术栈
- 原生 HTML5 + CSS3 + JavaScript（SPA）
- 微信小程序版本正在开发中
- 纯静态，无需后端服务
- localStorage 数据持久化

## 项目结构
```
xiufangbang-website/
├── index.html    # 主应用（SPA，含品牌落地页+完整功能）
└── README.md     # 本文件
```
