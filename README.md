# hrm-666.github.io

个人主页仓库，同时用于维护保研展示页面和后续的 LaTeX 简历材料。

## 当前结构

```text
.
|-- index.html                 # GitHub Pages 首页
|-- assets/
|   |-- docs/                  # PDF 简历、证书 PDF
|   |-- images/
|   |   |-- certificates/      # 奖项证书图片
|   |   |-- personal/          # 证件照、个人照片
|   |   |-- projects/
|   |   |   |-- robocon/       # ROBOCON 项目图片
|   |   |   `-- underwater/    # 水下机器人项目图片
|   |   `-- misc/              # 拼图、备用视觉素材
|   `-- videos/                # 页面展示视频与录屏
|-- backups/                   # 旧页面备份
`-- latex-resume/              # LaTeX 简历工作区
```

## 使用说明

- 主页入口：`index.html`
- 主页引用的图片、视频、PDF 都统一从 `assets/` 读取
- LaTeX 简历建议在 `latex-resume/` 中维护，避免和主页素材混在一起
