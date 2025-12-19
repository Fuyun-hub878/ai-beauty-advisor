# 💄 AI美妆顾问应用

一个基于人工智能的个性化美妆护肤顾问应用，提供专业的肤质测试、护肤品推荐和化妆技巧指导。

## ✨ 特色功能

### 🧪 智能肤质测试
- 通过问答形式分析用户肤质类型
- 识别常见皮肤问题（痘痘、敏感、干燥等）
- 生成个性化肤质报告

### 💡 个性化推荐
- 根据肤质推荐适合的护肤品
- 智能匹配护肤成分
- 提供购买建议和使用指南

### 💄 美妆指导
- 日常妆容教程
- 特殊场合化妆技巧
- 产品搭配建议

### 📱 PWA支持
- 可安装到手机桌面
- 离线功能支持
- 响应式设计，适配所有设备

## 🚀 快速开始

### 环境要求
- Python 3.8+
- pip 20.0+
- Git

### 本地部署步骤

1. **克隆仓库**
```bash
git clone https://github.com/Fuyun-hub878/ai-beauty-advisor.git
cd ai-beauty-advisor
安装依赖
bash
pip install -r requirements.txt
运行应用
bash
streamlit run app.py
访问应用
打开浏览器访问：http://localhost:8501
使用说明

在首页选择"开始肤质测试"
回答相关问题（5-10分钟）
查看个性化分析报告
获取产品推荐和美妆建议
🌐 在线体验

https://static.streamlit.io/badges/streamlit_badge_black_white.svg

注：部署Streamlit后替换上面的链接

🛠️ 技术栈

前端框架: Streamlit
后端语言: Python 3.8+
AI引擎: OpenAI API / 本地模型
数据库: SQLite (轻量级存储)
部署平台: Streamlit Cloud
PWA支持: Service Workers, Web App Manifest
📁 项目结构

text
ai-beauty-advisor/
├── app.py                    # 主应用文件
├── requirements.txt          # Python依赖包
├── README.md                # 项目说明
├── .streamlit/              # Streamlit配置
│   └── config.toml
├── static/                  # 静态资源
│   ├── css/                # 样式文件
│   ├── images/             # 图片资源
│   └── js/                 # JavaScript文件
└── data/                   # 数据文件（可后续添加）
🔧 高级配置

环境变量

如需使用AI功能，请设置以下环境变量：

bash
export OPENAI_API_KEY="你的API密钥"
自定义主题

编辑 .streamlit/config.toml 修改应用主题：

toml
[theme]
primaryColor = "#FF69B4"  # 粉色主题
backgroundColor = "#FFFFFF"
secondaryBackgroundColor = "#F0F2F6"
textColor = "#262730"
font = "sans serif"
🤝 贡献指南

欢迎贡献代码！请遵循以下步骤：

Fork本仓库
创建功能分支 (git checkout -b feature/AmazingFeature)
提交更改 (git commit -m 'Add some AmazingFeature')
推送到分支 (git push origin feature/AmazingFeature)
开启Pull Request
📝 许可证

本项目采用 MIT 许可证。

📞 联系方式

项目维护者: 浮云
GitHub: @Fuyun-hub878
问题反馈: GitHub Issues
🙏 致谢

Streamlit团队提供优秀的前端框架
开源社区的各种工具和库
所有贡献者和用户
⭐ 如果这个项目对你有帮助，请给个Star！
