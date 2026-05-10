# 湾水告示栏

一个简洁美观的静态告示栏网页，用于展示湾水集团的公告信息。

## 预览

在线访问：[https://fennmoo.github.io/wanbriefing/](https://fennmoo.github.io/wanbriefing/)

## 功能特点

- **图片轮播** - 顶部 Banner 支持自动轮播和手动切换
- **响应式设计** - 适配桌面端和移动端设备
- **毛玻璃效果** - 现代化的视觉设计风格
- **平滑滚动** - 导航锚点平滑跳转

## 页面结构

| 模块 | 说明 |
|------|------|
| 顶部导航 | Logo + 快速导航链接 |
| 轮播 Banner | 展示背景图片 |
| 欢迎标题 | 中英文欢迎语 |
| 地铁告示栏 | 地铁相关公告信息 |
| 公交告示栏 | 公交相关公告信息 |

## 项目结构

```
wanbriefing/
├── index.html              # 主页面
├── background.png          # 背景图片
├── background1.png         # 轮播图片 1
├── background2.png         # 轮播图片 2
├── background3.png         # 轮播图片 3
└── wanshuigaoshilan.png    # Logo 图片
```

## 使用方法

### 在线访问

直接访问 GitHub Pages 链接即可查看。

### 本地运行

1. 克隆仓库
   ```bash
   git clone https://github.com/Fennmoo/wanbriefing.git
   ```

2. 打开 `index.html` 文件即可在浏览器中查看

## 自定义内容

- **修改公告内容**：编辑 `index.html` 中对应模块的 `<p class="notice-text">` 内容
- **更换轮播图片**：替换 `background1.png`、`background2.png`、`background3.png` 文件
- **更新日期**：修改各模块中的 `<h3>` 标签内的日期

## 技术栈

- HTML5
- CSS3（Flexbox、毛玻璃效果、响应式媒体查询）
- 原生 JavaScript（无外部依赖）

## 许可证

MIT License
