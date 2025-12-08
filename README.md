cd C:\Users\Administrator\zhongzhengjie-blog

# 创建文件
@"
# 钟正杰的个人博客

## 📍 博客信息
- **作者**: 钟正杰
- **学号**: 202215003354
- **博客地址**: https://zzj-hsl.github.io
- **创建时间**: $(Get-Date -Format 'yyyy-MM-dd HH:mm')

## 🚀 本地运行
1. 安装 Node.js 和 Git
2. 克隆项目：\`git clone https://github.com/zzj-hsl/zhongzhengjie-blog.git\`
3. 安装依赖：\`npm install\`
4. 启动服务：\`hexo server\`

## 📦 部署步骤
\`\`\`bash
hexo clean
hexo generate
hexo deploy
\`\`\`

## 📁 项目结构
\`\`\`
zhongzhengjie-blog/
├── source/          # 文章和页面
├── themes/          # 主题文件  
├── _config.yml      # 博客配置
├── package.json     # 依赖配置
└── README.md        # 项目说明
\`\`\`

## 🔗 相关链接
- GitHub 仓库: https://github.com/zzj-hsl/zhongzhengjie-blog
- 博客主页: https://zzj-hsl.github.io
- 课程: 云计算原理与应用
"@ | Out-File -Encoding UTF8 README.md

# 查看创建的文件
cat README.md
