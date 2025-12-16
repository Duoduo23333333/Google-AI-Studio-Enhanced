# Google AI Studio Enhanced


## 安装方法

1. [安装 Stylus 插件](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)。
2. [安装该脚本](https://raw.githubusercontent.com/Duoduo23333333/Google-AI-Studio-Enhanced/main/style.user.css)。




## 功能演示

### 核心交互：悬浮目录 (GIF)
![Demo](https://i.111666.best/image/l0A6BxAZuEFIqX9ZPN8yOs.gif)

![Cover](https://i.111666.best/image/Fjm7jEXh9I27VlididL1eJ.jpg)


## 效果对比

![Comparison](https://i.111666.best/image/0IZPOJj5qwV09pnoKXMVWV.jpg)



## 功能说明

### 1. 对话区分
*   **背景区分**：为 User 和 Model 的对话气泡应用不同的背景色（适配 Dark/Light 模式，推荐 Dark 模式），以明确区分对话角色。

### 2. 导航增强
*   **对话目录**：在右侧利用滚动条区域生成可视化目录。
*   **快速跳转**：点击目录项可直接跳转至对应的 User 提问处。
*   **当前位置**：目录会自动高亮显示当前视口所在的对话段落。

### 3. Markdown 渲染优化
针对原版样式进行以下调整：
*   **排版**：调整段落间距与行高，解决排版不合理问题，提高易读性。
*   **字重**：减少正文字体颜色对比度，增加粗体颜色对比度与字重，提高辨识度。
*   **编程字体**：代码块应用编程字体（Fira Code, JetBrains Mono 等），优化代码阅读体验。
*   **其他**：优化突兀/不合理的分割线样式、缩进等杂项。

### 4. 侧边栏重构
*   **布局**：隐藏无关信息，减少视觉干扰。
*   **排序**：将常用设置项单独提取出，并置顶。
*   **样式**：常用功能项改为卡片式布局。

## 兼容性

*   已测试环境：Chrome / Edge + Stylus
*   适配模式：支持 Google AI Studio 的深色（Dark）和浅色（Light）模式。

## License

MIT