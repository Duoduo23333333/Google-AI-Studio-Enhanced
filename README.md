# Google AI Studio Enhanced

## 使用方法(二选一)

1. 使用 **油猴/暴力猴** 加载 js 脚本 
[![GreasyFork](https://img.shields.io/badge/Install%20from-GreasyFork-bf202f?style=for-the-badge&logo=greasyfork&logoColor=white)](https://greasyfork.org/zh-CN/scripts/559114-google-ai-studio-%E5%A2%9E%E5%BC%BA-%E7%BE%8E%E5%8C%96-markdown%E4%BC%98%E5%8C%96-%E5%AF%B9%E8%AF%9D%E7%9B%AE%E5%BD%95-%E4%BE%A7%E8%BE%B9%E6%A0%8F%E9%87%8D%E6%8E%92)

2. 用[Stylus 插件](https://chromewebstore.google.com/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)直接加载 css 样式
[![UserStyles](https://img.shields.io/badge/Install%20from-UserStyles.world-32a8a0?style=for-the-badge&logo=stylus&logoColor=white)](https://userstyles.world/style/25632/google-ai-studio-markdown)

## 功能说明

### 1. 对话区分
*   **背景区分**：为 User 部分加上醒目但不刺眼的背景色（适配 Dark/Light 模式，推荐 Dark 模式），以明确区分对话角色。

### 2. 侧边栏重构
*   **布局**：隐藏无关信息，减少视觉干扰。
*   **排序**：将常用设置项单独提取出，并置顶。
*   **样式**：常用功能项改为卡片式布局。

![Cover](https://ddwanan.oss-cn-hongkong.aliyuncs.com/%E5%A4%A7%E5%9B%BE.jpg)

### 3. 导航增强
*   **对话目录**：在右侧利用滚动条区域生成可视化目录。
*   **快速跳转**：点击目录项可直接跳转至对应的 User 提问处。
*   **当前位置**：目录会自动高亮显示当前视口所在的对话段落。

![Demo](https://ddwanan.oss-cn-hongkong.aliyuncs.com/%E5%8A%A8%E7%94%BB1.gif)

### 4. Markdown 渲染优化
针对原版样式进行以下调整：
*   **排版**：调整段落间距与行高，解决排版不合理问题，提高易读性。
*   **字重**：减少正文字体颜色对比度，增加粗体颜色对比度与字重，提高辨识度。
*   **编程字体**：代码块应用编程字体（Fira Code, JetBrains Mono 等），优化代码阅读体验。
*   **其他**：优化突兀/不合理的分割线样式、缩进等杂项。

![Comparison](https://ddwanan.oss-cn-hongkong.aliyuncs.com/%E5%AF%B9%E6%AF%94%E5%9B%BE.jpg)

## 兼容性

*   已测试环境：Chrome / Edge + Stylus
*   适配模式：支持 Google AI Studio 的深色（Dark）和浅色（Light）模式。

## License

MIT