# Assets / 图片素材

Images used by the documentation in this repository. Keep this folder small — it is cloned by everyone.
本仓库文档所使用的图片。请保持本目录精简——每个人克隆仓库时都会下载它。

## What to put here / 需要放什么

| File / 文件 | Purpose / 用途 | Spec / 规格 |
| --- | --- | --- |
| `icon.png` | App icon shown at the top of the README / 展示在说明文档顶部的应用图标 | 512 x 512, PNG, transparent or solid background |
| `screenshots/01-home.png` | Home screen / 主页 | Portrait, 1080 x 2400 or the same aspect ratio |
| `screenshots/02-assistant.png` | AI assistant / AI 助手 | same / 同上 |
| `screenshots/03-office.png` | Office tools / 办公工具 | same / 同上 |
| `screenshots/04-image-editor.png` | Image editor / 图片编辑器 | same / 同上 |
| `screenshots/05-files.png` | Files and projects / 文件与项目 | same / 同上 |
| `screenshots/06-plugins.png` | Plugin manager / 插件管理 | same / 同上 |

## Rules / 规范

- Lower-case file names, hyphens instead of spaces, numbered prefix for ordering.
  文件名小写，用连字符代替空格，用数字前缀控制顺序。
- PNG for interface captures, JPEG only for photographic content.
  界面截图用 PNG，照片类内容才用 JPEG。
- Keep each file under 500 KB where possible; compress before committing.
  尽量将每个文件控制在 500 KB 以内，提交前先压缩。
- No personal information in screenshots: no real conversations, contacts, file names, locations,
  phone numbers or account identifiers. Use neutral demo content.
  截图中不得含个人信息：真实对话、联系人、文件名、位置、手机号、账号标识一律不要出现，请用中性演示内容。
- Do not include third-party logos or copyrighted artwork you do not have the right to use.
  不要放入你无权使用的第三方标识或受版权保护的图形。
- Same screenshots serve both language versions; captions live in the documents, not baked into images.
  中英两个版本共用同一批截图；说明文字写在文档里，不要压进图片。

## How to reference / 如何引用

Relative paths, from the file that uses them / 从引用文件出发使用相对路径:

```
![Home](assets/screenshots/01-home.png)
```

In a table, three or four screenshots side by side read better than a long vertical stack.
排版时用表格并排放三到四张，比纵向长条更好读。
