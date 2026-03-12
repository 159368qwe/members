# 个人网站

这是一个单页应用（SPA）的个人网站，所有内容都在 `index.html` 中。

## 功能特性

- **首页**：个人信息区（头像、名字、身份、Slogan）
- **关于页面**：个人介绍、统计数据
- **技能区**：图标 + 文字展示
- **页脚**：社交链接
- **导航栏**：首页、关于、技能
- **深色/浅色模式切换**
- **平滑滚动**
- **移动端友好**

## 如何部署到 GitHub Pages

### 1. 创建 GitHub 仓库

1. 登录 GitHub，点击 **New repository**。
2. 填写仓库名称（例如 `your-username.github.io`，这是用户主页的推荐命名）。
3. 选择 **Public**。
4. 勾选 **Add a README file**（可选，但推荐）。
5. 点击 **Create repository**。

### 2. 上传代码

#### 方法 A：使用命令行（推荐）

```bash
# 1. 克隆仓库到本地
git clone https://github.com/your-username/your-username.github.io.git
cd your-username.github.io

# 2. 复制 index.html 到仓库目录
# （将 index.html 文件复制到当前目录）

# 3. 添加文件并提交
git add .
git commit -m "Initial commit: Add personal website"
git push origin main
```

#### 方法 B：使用 GitHub 网页界面

1. 在仓库页面，点击 **Uploading an existing file**。
2. 拖拽 `index.html` 文件到上传区域。
3. 填写提交信息，例如 "Add personal website"。
4. 点击 **Commit changes**。

### 3. 启用 GitHub Pages

1. 在仓库页面，点击 **Settings**（设置）。
2. 在左侧菜单中找到 **Pages**。
3. 在 **Source** 部分，选择 **Deploy from a branch**。
4. 选择分支（通常是 `main` 或 `master`）。
5. 点击 **Save**。

### 4. 访问网站

等待几分钟后，GitHub 会自动部署。访问地址通常是：
- 用户主页：`https://your-username.github.io`
- 项目页：`https://your-username.github.io/your-repo-name`

## 自定义

你可以编辑 `index.html` 中的内容来个性化你的网站：

- **个人信息**：修改 `#name`、`#title`、`#slogan` 的文本。
- **头像**：替换 `#avatar` 的 `src` 属性为你的图片 URL。
- **技能**：修改 `.skill-card` 中的图标和描述。
- **关于**：修改 `.about-text` 中的段落。
- **统计数据**：修改 `.stat-number` 和 `.stat-label`。
- **社交链接**：更新 `.social-link` 的 `href` 属性。

## 技术栈

- HTML5
- CSS3（使用 CSS 变量实现主题切换）
- JavaScript（原生）

## 浏览器兼容性

- Chrome
- Firefox
- Safari
- Edge

## 许可证

MIT License