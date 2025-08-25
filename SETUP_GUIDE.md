# GitHub 个人主页 README 设置指南

## 📋 快速开始

1. **创建特殊仓库**：在 GitHub 上创建一个与你的用户名完全相同的仓库（例如：如果你的用户名是 `json0755`，就创建名为 `json0755` 的仓库）
2. **设置为公开**：确保仓库是公开的（Public）
3. **上传 README**：将本目录中的 `README.md` 文件上传到该仓库
4. **个性化定制**：根据下面的指南修改内容

## 🎨 个性化定制指南

### 基本信息替换

在 `README.md` 文件中，需要替换以下占位符：

- `[Your Name]` → 你的真实姓名
- `[Your Current Project]` → 你当前正在进行的项目
- `[Technologies you're learning]` → 你正在学习的技术
- `[Your expertise areas]` → 你的专业领域
- `[your-email@example.com]` → 你的邮箱地址
- `[Something interesting about you]` → 关于你的有趣事实

### 组织信息设置

在 "🏢 Organizations" 部分：

1. 替换 `[organization1]`、`[organization2]` 为实际的组织名称
2. 替换 `[org-id]` 为组织的 GitHub ID（可以在组织页面 URL 中找到）
3. 替换 `[Organization Name 1]` 为组织的显示名称
4. 替换 `[Your Role]` 为你在该组织中的角色

### GitHub 统计信息

所有包含 `json0755` 的 URL 都需要替换为你的实际 GitHub 用户名：

```markdown
# 将所有的 json0755 替换为你的用户名
https://github-readme-stats.vercel.app/api?username=你的用户名
https://github-readme-streak-stats.herokuapp.com/?user=你的用户名
```

### 技能标签定制

在 "💻 Tech Stack" 部分，你可以：

1. **添加新技能**：访问 [shields.io](https://shields.io/) 生成新的徽章
2. **删除不相关的技能**：移除你不使用的技术标签
3. **调整顺序**：按照你的熟练程度重新排列

### 项目展示

在 "🌟 Featured Projects" 部分：

1. 替换 `project1`、`project2` 为你的实际项目仓库名
2. 确保这些仓库是公开的，否则统计卡片无法显示

### 社交链接

在 "🤝 Connect with Me" 部分：

- `[your-linkedin]` → 你的 LinkedIn 用户名
- `[your-twitter]` → 你的 Twitter 用户名
- `[your-email@example.com]` → 你的邮箱
- `[your-website].com` → 你的个人网站

## 🔧 高级功能

### 1. 动态打字效果

修改这行代码来自定义打字动画：
```markdown
https://readme-typing-svg.herokuapp.com?font=Fira+Code&pause=1000&color=2196F3&center=true&vCenter=true&width=435&lines=Welcome+to+my+GitHub+Profile!;Full+Stack+Developer;Open+Source+Enthusiast;Always+learning+new+things
```

在 `lines=` 后面添加你想要显示的文本，用分号分隔。

### 2. 代码时间统计（WakaTime）

要启用 "📊 Weekly Development Breakdown" 功能：

1. 注册 [WakaTime](https://wakatime.com/)
2. 在你的编辑器中安装 WakaTime 插件
3. 按照 [waka-readme-stats](https://github.com/anmol098/waka-readme-stats) 的说明设置 GitHub Action

### 3. 主题定制

你可以更改统计卡片的主题，可选主题包括：
- `radical`（当前使用）
- `dark`
- `merko`
- `gruvbox`
- `tokyonight`
- `onedark`
- `cobalt`
- `synthwave`
- `highcontrast`
- `dracula`

只需在 URL 中修改 `theme=radical` 为其他主题名称。

### 4. 添加更多组织

如果你属于更多组织，可以复制组织表格的行：

```html
<td align="center">
  <a href="https://github.com/[organization3]">
    <img src="https://avatars.githubusercontent.com/u/[org-id]?s=100&v=4" width="100px;" alt="Organization 3"/>
    <br />
    <sub><b>[Organization Name 3]</b></sub>
  </a>
  <br />
  <sub>Role: [Your Role]</sub>
</td>
```

## 🎯 最佳实践

1. **保持更新**：定期更新你的技能和项目信息
2. **简洁明了**：不要添加过多信息，保持页面整洁
3. **真实准确**：确保所有信息都是准确和最新的
4. **个性化**：添加能体现你个性的元素
5. **测试链接**：确保所有链接都能正常工作

## 🚀 部署步骤

1. 在 GitHub 上创建与用户名同名的仓库
2. 将修改后的 `README.md` 上传到仓库根目录
3. 确保仓库是公开的
4. 访问你的 GitHub 个人主页查看效果

## 📚 参考资源

- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats) - 生成 GitHub 统计卡片
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy) - 显示 GitHub 成就
- [Shields.io](https://shields.io/) - 生成各种徽章
- [Simple Icons](https://simpleicons.org/) - 获取品牌图标
- [Readme Typing SVG](https://github.com/DenverCoder1/readme-typing-svg) - 动态打字效果

## ❓ 常见问题

**Q: 为什么我的统计卡片不显示？**
A: 确保你的仓库是公开的，并且用户名拼写正确。

**Q: 如何获取组织的 ID？**
A: 访问组织的 GitHub 页面，查看 URL 或使用 GitHub API。

**Q: 可以添加自定义的 CSS 样式吗？**
A: GitHub README 不支持自定义 CSS，但可以使用 HTML 标签和内联样式。

**Q: 如何让代码时间统计自动更新？**
A: 需要设置 GitHub Actions 和 WakaTime 集成，具体步骤请参考相关文档。

---

🎉 **祝你打造出一个令人印象深刻的 GitHub 个人主页！**