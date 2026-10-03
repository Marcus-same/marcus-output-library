# Marcus Output Library Pages · 发布约定

## 目标

这是 `Marcus-same/marcus-output-library` 的公开 GitHub Pages 发布目录，仅承载 Marcus 产出库网页与脱敏下载包。

## 目录

- `docs/`：GitHub Pages 发布根目录，由 `D:\projects\marcus-output-library\dist` 同步而来。
- `README.md`：公开仓库说明。

## 安全规则

- 只允许发布网页静态文件、`manifest.json` 和已经过白名单打包的下载 ZIP。
- 禁止放入候选人数据、简历、截图、招聘台账、内部 JD、实际 `CONTEXT.md`、个人配置、密钥或 token。
- 历史下载包只增不覆盖；删除任何版本须先征得用户确认。
- 每次 Git push 前必须征得用户确认。

## 同步流程

1. 在 `D:\projects\marcus-output-library` 生成新的脱敏版本。
2. 将其 `dist/` 内容同步到本目录 `docs/`。
3. 检查下载链接与敏感信息。
4. 经用户确认后提交并推送到同一公开仓库。
