# 项目维护说明

## 目录约定

- 技术类 Skill 放在 `technical/` 下。
- 工具类 Skill 放在 `tools/` 下。
- 每个 Skill 必须使用独立目录，并在目录中提供 `SKILL.md`。
- 如果新增 Skill 不适合当前已有分类，则根据其用途新增一个分类目录；分类应清晰、通用，并保持目录层级简单。

## README 路由约定

新增、删除、移动或重命名 Skill 时，必须同步更新根目录 `README.md` 的“Skills 索引”：

1. 为项目中每个 Skill 添加可点击的相对路径链接。
2. 将该 Skill 的 `SKILL.md` frontmatter 中的 `description` 原样复制为简单说明。
3. 确保索引覆盖当前项目中的全部 Skills，不保留失效链接。

## AGENTS.md 维护路由

- 新增、修改、拆分或审查 `AGENTS.md` / `AGENTS.override.md` 时，先读取并遵循 `tools/agents-md-author/references/authoring-guide.md`。

## Git 提交与推送

- 每次完成 Skill 的新建或修改后，都必须询问用户是否需要创建中文提交并推送到远端仓库。
- 只有在用户明确表示需要后，才创建中文 Git 提交并推送到远端。
- 提交信息必须使用中文，并准确概括本次 Skill 变更。
- 未经用户确认，不得自行提交或推送。
