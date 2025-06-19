# 奥古斯都战队官方网站

这是一个为公司内部LOL电竞队伍"奥古斯都"打造的现代化静态网站。

## 功能特色

- 🎮 现代化电竞风格设计
- 📱 完全响应式，支持手机和平板访问
- ⚡ 快速加载，优秀的用户体验
- 🎯 队伍介绍和队员展示
- 🎬 精彩视频展示区域
- 📝 招募信息和联系方式
- ✨ 丰富的动画效果和交互

## 文件结构

```
AugustusHtml/
├── index.html      # 主页面
├── styles.css      # 样式文件
├── script.js       # JavaScript交互
└── README.md       # 说明文档
```

## 如何自定义内容

### 1. 替换队员信息
在 `index.html` 文件中找到队员卡片部分，修改：
- 队员姓名（替换"队员A"、"队员B"等）
- 队员介绍文字
- 擅长英雄列表

### 2. 添加真实图片
- 队伍合影：替换带有 `placeholder-image` 类的div
- 队员头像：替换带有 `placeholder-avatar` 类的div
- 示例：`<img src="team-photo.jpg" alt="奥古斯都战队合影">`

### 3. 添加视频
- 将视频文件放在网站目录中
- 替换带有 `placeholder-video` 类的div
- 示例：
```html
<video controls poster="thumbnail.jpg">
    <source src="highlight-video.mp4" type="video/mp4">
</video>
```

### 4. 修改联系信息
在联系我们部分更新：
- 队长微信和邮箱
- QQ群号
- 训练时间

### 5. 自定义颜色主题
在 `styles.css` 文件的 `:root` 部分修改颜色变量：
```css
:root {
    --primary-color: #00d9ff;    /* 主色调 */
    --secondary-color: #ff6b35;  /* 次要色 */
    --accent-color: #ffd700;     /* 强调色 */
}
```

## 浏览器支持

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 部署方式

### 本地预览
1. 直接双击 `index.html` 文件即可在浏览器中预览
2. 或使用本地服务器：`python -m http.server 8000`

### 线上部署
可以部署到任何静态网站托管平台：
- GitHub Pages
- Netlify
- Vercel
- 阿里云OSS
- 腾讯云COS

## 技术栈

- **HTML5** - 页面结构
- **CSS3** - 样式和动画
- **JavaScript** - 交互功能
- **Font Awesome** - 图标库
- **Google Fonts** - 字体资源

## 更新日志

### v1.0.0 (2024-01-01)
- 初始版本发布
- 包含所有基础功能
- 响应式设计完成
- 动画效果实现

## 许可证

此项目仅供奥古斯都战队内部使用。

## 联系支持

如需技术支持或功能定制，请联系开发团队。 