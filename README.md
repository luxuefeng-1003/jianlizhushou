# 简历智能助手 ✨

基于 DeepSeek API + STAR法则的简历优化工具，输入岗位和经历，AI帮你生成专业简历内容。

## 快速开始
```

> 获取地址: https://platform.deepseek.com/api_keys

### 2. 安装依赖

```bash
cd backend
npm install
```

### 3. 启动服务

```bash
cd backend
DEEPSEEK_API_KEY=sk-your-key npm start
```

服务将在 http://localhost:8000 启动，浏览器打开即可使用。

## 项目结构

```
resume-assistant/
├── backend/
│   ├── server.js        # Node.js后端（DeepSeek API + 流式输出）
│   ├── package.json     # Node依赖
│   └── .env             # API Key配置（可选，优先用环境变量）
└── frontend/
    └── index.html       # 单页前端页面
```

## 功能

- 🎯 输入目标岗位名称
- 💼 输入原始工作经历描述（随意写即可）
- ✨ AI用STAR法则自动优化
- 📡 流式实时输出，无需等待
- 📋 一键复制优化结果

## 技术栈

- **后端**: Node.js + Express
- **前端**: 单页HTML + CSS + JavaScript
- **AI**: DeepSeek Chat API + 流式输出
- **部署**: 阿里云ECS

## 快捷键

- `Ctrl/Cmd + Enter`: 快速提交
