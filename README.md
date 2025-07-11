# Academic Portfolio Website Template (本网页只是暂时提供一个模版，网站展示的并非个人真实信息。目前个人网页正在创建中。)

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-brightgreen)](https://brycewang-stanford.github.io)
[![Jekyll](https://img.shields.io/badge/Jekyll-4.3.0-red)](https://jekyllrb.com/)
[![Minimal Mistakes](https://img.shields.io/badge/Theme-Minimal%20Mistakes-blue)](https://mmistakes.github.io/minimal-mistakes/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A modern, responsive, and professional academic portfolio website template built with Jekyll and the Minimal Mistakes theme. Perfect for researchers, PhD students, professors, and academics who want to showcase their work, publications, and research projects.

**🎨 Design Philosophy**: Inspired by OpenAI's clean, minimalist black and white aesthetic, this template focuses on content readability and professional presentation without visual distractions.

**📝 Content-First Approach**: Built with Markdown source files for ultimate simplicity - adding a new publication or project is as easy as editing a text file. No complex CMS or database required.

## 🌟 Features

- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🎨 OpenAI-Inspired Design**: Clean, minimalist black and white aesthetic focusing on content clarity
- **📝 Markdown-Powered**: Easy content management with simple Markdown files - no database required
- **📚 Publications Management**: Dedicated section for papers, conferences, and journals
- **🔬 Research Showcase**: Highlight your research projects and collaborations
- **💻 Project Portfolio**: Display your technical projects with GitHub integration
- **📧 Contact Integration**: Professional contact page with office hours and social links
- **🔍 Search Functionality**: Built-in site search powered by Lunr.js
- **📊 SEO Optimized**: Automatic sitemap generation and meta tags
- **🚀 GitHub Pages Ready**: Deploy automatically with GitHub Pages
- **📝 Blog Support**: Optional blog functionality for research updates
- **🏷️ Content Organization**: Tags and categories for easy content management

## 🏗️ Architecture

### Site Structure
```
├── _config.yml              # Site configuration
├── _data/
│   └── navigation.yml       # Navigation menu structure
├── _pages/                  # Main site pages
│   ├── about.md            # About page
│   ├── research.md         # Research projects
│   ├── projects.md         # Technical projects
│   ├── publications.md     # Academic publications
│   ├── contact.md          # Contact information
│   └── test.md             # Testing/debug page
├── _posts/                 # Blog posts (optional)
├── assets/
│   └── images/             # Site images and media
├── index.md                # Homepage
├── Gemfile                 # Ruby dependencies
└── README.md               # This file
```

### Technology Stack
- **Static Site Generator**: Jekyll 4.3+
- **Theme**: Minimal Mistakes 4.27.1
- **Hosting**: GitHub Pages
- **Styling**: SCSS/CSS3
- **JavaScript**: Minimal, progressive enhancement
- **Search**: Lunr.js
- **Analytics**: Google Analytics ready

## 🚀 Quick Start

### Method 1: Use This Template (Recommended)
1. Click the "Use this template" button at the top of this repository
2. Name your new repository `yourusername.github.io`
3. Clone your new repository locally
4. Follow the customization steps below

### Method 2: Fork This Repository
1. Fork this repository
2. Rename it to `yourusername.github.io`
3. Clone your fork locally
4. Follow the customization steps below

### Method 3: Manual Setup
```bash
# Clone the repository
git clone https://github.com/brycewang-stanford/brycewang-stanford.github.io.git
cd brycewang-stanford.github.io

# Install dependencies (optional, for local development)
bundle install

# Serve locally (optional)
bundle exec jekyll serve
```

## ⚙️ Customization

### 1. Basic Site Configuration
Edit `_config.yml` to customize your site:

```yaml
title: "Your Name"
email: "your.email@university.edu"
description: "Your professional description"
url: "https://yourusername.github.io"

author:
  name: "Your Name"
  avatar: "/assets/images/bio-photo.jpg"
  bio: "Your professional bio"
  links:
    # Add your social media links
```

### 2. Navigation Menu
Update `_data/navigation.yml`:

```yaml
main:
  - title: "Home"
    url: /
  - title: "About"
    url: /about/
  - title: "Research"
    url: /research/
  # Add or remove menu items as needed
```

### 3. Homepage Content
Customize `index.md`:
- Update the header image and overlay
- Modify the feature rows
- Add your own introduction text
- Update action buttons

### 4. Individual Pages
Update each page in `_pages/`:
- **about.md**: Your background, education, skills
- **research.md**: Current and past research projects
- **projects.md**: Technical projects and code repositories
- **publications.md**: Academic papers and presentations
- **contact.md**: Contact information and office hours

### 5. Profile Photo
Replace `assets/images/bio-photo.jpg` with your own professional photo.

### 6. Resume/CV
Replace `resume.pdf` with your own CV.

## 📝 Content Management

### Easy Markdown Editing
All content is stored in simple Markdown files, making updates incredibly straightforward:
- No complex CMS interface to learn
- Edit files directly in GitHub or your favorite text editor
- Version control for all content changes
- Easy collaboration with co-authors

### Adding Publications
In `_pages/publications.md`, add new publications following this format:

```markdown
**Your Name**, Co-author, A. (2024). "Paper Title." *Conference/Journal Name*, pp. 123-145.
[[PDF]](link-to-pdf) [[Code]](link-to-code) [[Slides]](link-to-slides)
```

**Example workflow for adding a new publication:**
1. Open `_pages/publications.md` in any text editor
2. Copy the format above and fill in your details
3. Save the file and push to GitHub
4. Your site automatically updates!

### Adding Projects
In `_pages/projects.md`, add new projects:

```markdown
### Project Name
**Technologies**: Python, TensorFlow, React
**Duration**: 2023 - Present
**Status**: Active Development

Description of your project...

[View on GitHub](https://github.com/yourusername/project-name)
```

### Adding Research
In `_pages/research.md`, describe your research areas and current projects.

### Blog Posts (Optional)
Create new blog posts in `_posts/` following the naming convention:
`YYYY-MM-DD-post-title.md`

## 🎨 Customization Options

### Theme Customization
The site uses the Minimal Mistakes theme. You can:
- Change the skin in `_config.yml`
- Override theme styles by creating custom CSS files
- Modify layouts by copying them from the theme and editing

### Color Schemes
Available Minimal Mistakes skins:
- `default` (default)
- `air`
- `aqua`
- `contrast`
- `dark`
- `dirt`
- `neon`
- `mint`
- `plum`
- `sunrise`

### Advanced Customization
- Add custom CSS in `assets/css/main.scss`
- Override layouts by creating files in `_layouts/`
- Add custom JavaScript in `assets/js/`

## 🚀 Deployment

### GitHub Pages (Automatic)
1. Push your changes to the `main` branch
2. GitHub will automatically build and deploy your site
3. Visit `https://yourusername.github.io`

### Local Development
```bash
# Install Jekyll and dependencies
bundle install

# Serve locally
bundle exec jekyll serve

# View at http://localhost:4000
```

## 📋 Checklist for New Users

- [ ] Update `_config.yml` with your information
- [ ] Replace profile photo in `assets/images/`
- [ ] Update all pages in `_pages/` with your content
- [ ] Add your publications to `publications.md`
- [ ] Add your projects to `projects.md`
- [ ] Update contact information
- [ ] Replace `resume.pdf` with your CV
- [ ] Test all links and navigation
- [ ] Customize colors/theme if desired
- [ ] Enable Google Analytics (optional)

## 🤝 Contributing

Contributions are welcome! If you have ideas for improvements:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions
- Additional page templates
- New theme customizations
- Improved responsive design
- Integration with academic databases
- Enhanced search functionality
- Multi-language support

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) by Michael Rose
- [Jekyll](https://jekyllrb.com/) static site generator
- [GitHub Pages](https://pages.github.com/) for hosting
- Academic community for inspiration and feedback

## 📬 Support

If you have questions or need help:
- Check the [Issues](https://github.com/brycewang-stanford/brycewang-stanford.github.io/issues) page
- Create a new issue for bugs or feature requests
- Star ⭐ this repository if you find it useful!

---

## 中文说明

# 学术作品集网站模板

这是一个现代化、响应式的学术作品集网站模板，基于Jekyll和Minimal Mistakes主题构建。特别适合研究人员、博士生、教授和学者展示他们的工作、发表成果和研究项目。

**🎨 设计理念**: 受OpenAI简洁、极简的黑白美学风格启发，这个模板专注于内容的可读性和专业呈现，避免视觉干扰。

**📝 内容优先**: 使用Markdown源文件构建，简单至极 - 添加新的发表成果或项目就像编辑文本文件一样简单，无需复杂的CMS或数据库。

## 🌟 主要特性

- **📱 响应式设计**: 在桌面、平板和手机设备上完美展示
- **🎨 OpenAI风格设计**: 简洁、极简的黑白美学风格，专注于内容清晰度
- **📝 Markdown驱动**: 使用简单的Markdown文件轻松管理内容 - 无需数据库
- **📚 发表成果管理**: 专门展示论文、会议和期刊文章的版块
- **🔬 研究展示**: 突出显示您的研究项目和合作
- **💻 项目作品集**: 展示技术项目并集成GitHub链接
- **📧 联系集成**: 包含办公时间和社交链接的专业联系页面
- **🔍 搜索功能**: 基于Lunr.js的内置网站搜索
- **📊 SEO优化**: 自动生成站点地图和元标签
- **🚀 GitHub Pages就绪**: 通过GitHub Pages自动部署
- **📝 博客支持**: 可选的博客功能用于研究更新
- **🏷️ 内容组织**: 标签和分类便于内容管理

## 🚀 快速开始

### 方法1: 使用此模板（推荐）
1. 点击本仓库顶部的"Use this template"按钮
2. 将新仓库命名为 `yourusername.github.io`
3. 将新仓库克隆到本地
4. 按照下面的自定义步骤操作

### 方法2: Fork此仓库
1. Fork此仓库
2. 重命名为 `yourusername.github.io`
3. 将Fork的仓库克隆到本地
4. 按照下面的自定义步骤操作

## ⚙️ 自定义配置

### 1. 基本网站配置
编辑 `_config.yml` 自定义您的网站：

```yaml
title: "您的姓名"
email: "your.email@university.edu"
description: "您的专业描述"
url: "https://yourusername.github.io"

author:
  name: "您的姓名"
  avatar: "/assets/images/bio-photo.jpg"
  bio: "您的专业简介"
```

### 2. 导航菜单
更新 `_data/navigation.yml`:

```yaml
main:
  - title: "首页"
    url: /
  - title: "关于"
    url: /about/
  - title: "研究"
    url: /research/
  # 根据需要添加或删除菜单项
```

### 3. 内容更新
- **about.md**: 您的背景、教育和技能
- **research.md**: 当前和过去的研究项目
- **projects.md**: 技术项目和代码仓库
- **publications.md**: 学术论文和演讲
- **contact.md**: 联系信息和办公时间

### 4. 个人照片
用您自己的专业照片替换 `assets/images/bio-photo.jpg`。

### 5. 简历
用您自己的简历替换 `resume.pdf`。

## 📝 内容管理

### 简单的Markdown编辑
所有内容都存储在简单的Markdown文件中，使更新变得非常简单：
- 无需学习复杂的CMS界面
- 直接在GitHub或您喜欢的文本编辑器中编辑文件
- 所有内容更改都有版本控制
- 便于与合作者协作

### 添加发表成果
在 `_pages/publications.md` 中，按以下格式添加新的发表内容：

```markdown
**您的姓名**, 合作者, A. (2024). "论文标题." *会议/期刊名称*, pp. 123-145.
[[PDF]](PDF链接) [[代码]](代码链接) [[幻灯片]](幻灯片链接)
```

**添加新发表成果的示例工作流程：**
1. 在任何文本编辑器中打开 `_pages/publications.md`
2. 复制上面的格式并填入您的详细信息
3. 保存文件并推送到GitHub
4. 您的网站自动更新！

### 添加项目
在 `_pages/projects.md` 中添加新项目：

```markdown
### 项目名称
**技术栈**: Python, TensorFlow, React
**时间**: 2023 - 至今
**状态**: 积极开发中

项目描述...

[在GitHub上查看](https://github.com/yourusername/project-name)
```

## 🚀 部署

### GitHub Pages（自动）
1. 将更改推送到 `main` 分支
2. GitHub会自动构建和部署您的网站
3. 访问 `https://yourusername.github.io`

### 本地开发
```bash
# 安装Jekyll和依赖
bundle install

# 本地运行
bundle exec jekyll serve

# 在 http://localhost:4000 查看
```

## 📋 新用户检查清单

- [ ] 用您的信息更新 `_config.yml`
- [ ] 替换 `assets/images/` 中的个人照片
- [ ] 用您的内容更新 `_pages/` 中的所有页面
- [ ] 在 `publications.md` 中添加您的发表成果
- [ ] 在 `projects.md` 中添加您的项目
- [ ] 更新联系信息
- [ ] 用您的简历替换 `resume.pdf`
- [ ] 测试所有链接和导航
- [ ] 如需要，自定义颜色/主题
- [ ] 启用Google Analytics（可选）

## 🤝 贡献

欢迎贡献！如果您有改进想法：

1. Fork仓库
2. 创建功能分支 (`git checkout -b feature/amazing-feature`)
3. 提交更改 (`git commit -m 'Add amazing feature'`)
4. 推送到分支 (`git push origin feature/amazing-feature`)
5. 开启Pull Request

## 📄 许可证

本项目采用MIT许可证 - 详见 [LICENSE](LICENSE) 文件。

## 🙏 致谢

- [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/) 主题作者 Michael Rose
- [Jekyll](https://jekyllrb.com/) 静态网站生成器
- [GitHub Pages](https://pages.github.com/) 提供托管服务
- 学术社区的启发和反馈

## 📬 支持

如果您有问题或需要帮助：
- 查看 [Issues](https://github.com/brycewang-stanford/brycewang-stanford.github.io/issues) 页面
- 为错误或功能请求创建新issue
- 如果觉得有用，请给这个仓库加星 ⭐！

---

**开始建立您的学术作品集网站吧！** 🚀
