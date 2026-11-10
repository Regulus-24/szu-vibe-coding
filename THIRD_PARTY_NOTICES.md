# 第三方依赖与字体

- React / React DOM：MIT，https://github.com/facebook/react
- Vite：MIT，https://github.com/vitejs/vite
- TypeScript：Apache-2.0，https://github.com/microsoft/TypeScript
- Noto Serif SC：SIL Open Font License 1.1，通过 `@fontsource-variable/noto-serif-sc` 本地打包。正式交付包内 `site/font-license.txt` 保留该字体许可文本。https://github.com/notofonts/noto-cjk

字体在构建时拆分为 unicode-range 子集，浏览器按页面文字需要加载本地 WOFF2 文件。完整字体资产随包提供，以支持新增中文投稿。

视觉设计基于本项目中创建的 MagicPath 组件继续开发。植物背景与资源封面是项目内 SVG/CSS 图形，不依赖外站图片。两份用户提供的网站用于设计参考，未复制其源码或媒体资产。
