# AI × Food Lab

全自动食品营养分析实验室 · 中国农业科学院农产品加工研究所

中英文实验室介绍、四个重点研究项目、近期代表性论文及配图、导师和实验空间。

## 网站发布

- `site.zip`：完整静态网页，包含首页、脚本、样式、图片和 PDF。
- `.github/workflows/pages.yml`：自动解包网站并发布到 GitHub Pages。
- `website-source.zip`：可编辑的完整源码与构建配置。

在仓库 Settings → Pages 中选择 GitHub Actions，之后推送到 main 即可自动发布。
最终访问地址以 Settings → Pages 显示的链接为准。

## 修改内容

解压 `website-source.zip`，使用 Node.js 22.13 或更新版本，运行 `pnpm install --frozen-lockfile`、`pnpm build`。
构建结果位于 `dist/` 和 `docs/`。把 `dist/` 内的全部内容（包括 `.nojekyll`，不要再套一层 dist 目录）打包替换 `site.zip`，提交即可更新。

内容和配图来源见 `content-sources.md` 与 `publication-image-sources.json`。
原始 PPT、完整 Word 文稿和账号凭据未包含在本仓库中。
第三方论文图片等素材的权利归原作者或出版方所有。
