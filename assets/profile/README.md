# 夜航工作室 · Profile assets

为 `alanbulan/alanbulan` 个人主页制作的日系极简视觉：暖纸白、月夜蓝、樱花粉与低饱和薰衣草色，配合原创矢量耳机猫插画。

## 文件

| 区块 | 桌面版本 | 窄屏版本 |
| --- | --- | --- |
| 个人首屏 | `hero.svg` | `hero-mobile.svg` |
| TuneFree | `tunefree.svg` | `tunefree-mobile.svg` |
| AI anime | `aianime.svg` | `aianime-mobile.svg` |
| Prism | `prism.svg` | `prism-mobile.svg` |
| 技术面板 | `workbench.svg` | `workbench-mobile.svg` |

根 README 使用 `picture` 在视口不超过 600px 时选择窄屏版本。宽屏与窄屏采用不同排版，不把整张桌面图机械缩小。

## 维护方式

配色变量位于每个 SVG 的 `<style>` 中；深色配色由 `prefers-color-scheme: dark` 切换。首屏的花瓣采用缓慢动画，并为 `prefers-reduced-motion: reduce` 提供静止状态。所有图片都保存在仓库中，没有依赖第三方统计图片服务，也不请求外部字体。

修改项目名称、技术栈或定位时，同时更新根 README 的可读文字、图片 `alt` 和对应两个尺寸的 SVG。图片内文字用于视觉排版，核心项目介绍与真实链接仍保留在 Markdown 中。

插画和卡片图标是装饰，不是产品截图或实时状态。面板不展示虚构的贡献次数、技能百分比、在线状态或社区背书。原有根目录 SVG 保留未改，历史版本可通过 Git 追溯。

## 验证范围

2026-09-08：在本地 Chromium 离线预览中检查桌面 1120px 与手机 390px、浅色与深色四种组合；检查图片加载、内部锚点、横向溢出及页面错误。已检查 SVG XML 结构。

上述预览不是 GitHub 实际页面截图；最终字体、图像缓存和主题表现由 GitHub 页面与访问者浏览器共同决定。本次仅更新文档与视觉资产，不代表相关软件重新完成构建或运行验收。
