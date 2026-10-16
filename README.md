# 超级碗营养计算器 1.0.0

一个用于计算轻食品牌"超级碗FOODBOWL"单餐营养（多餐也行）的小工具，适用于超级碗现行菜单。需求来源于连续吃了两个月轻食碗，终于受不了天天算热量的我。

纯静态网站，无需安装依赖或构建。

我也不知道为什么官方不提供这个功能。

CnH2n_6策划，Codex 辅助开发。

## 文件

- index.html：页面入口
- assets/styles.css：样式（字体路径相对于此文件）
- assets/app.js：食物数据及交互逻辑
- assets/fonts/SourceHanSansCN-Regular.otf：未修改的思源黑体
- assets/fonts/OFL.txt：字体版权声明与许可证
- .nojekyll：关闭 GitHub Pages 的 Jekyll 处理

所有页面运行资源都使用相对路径，可部署到域名根目录或仓库子路径。关于页面中的外部资料链接保留原网址，它们不是运行资源。

## 数据与许可证

菜单数据来源：小红书 @超级碗FOODBOWL，置顶2026.7.6版。三明治热量来自官方2026年8月10日的上新海报，但缺少碳蛋脂数据。注明来源不代表品牌授权。

鸡腿肉估算参考：USDA FoodData Central，FDC 172388，经 https://whatyoueat.io/foods/172388 查阅。USDA 数据采用 CC0 1.0。

字体依 SIL Open Font License 1.1 分发，完整声明见 assets/fonts/OFL.txt，同时保留在页面内。字体许可证不覆盖品牌、菜单数据或工具代码。本包尚未另行指定代码开源许可证；公开仓库不等于自动授予开源许可。

## 本地记录

记录保存在浏览器 localStorage。文件版与 GitHub Pages 的记录不会自动同步；迁移前导出 JSON 备份，再到网站导入。
