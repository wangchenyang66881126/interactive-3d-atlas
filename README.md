# 3D Boom图与交互地图

可复用的 Codex skill，用于汽车、飞机和产品三维交互展示，以及建筑、机场设施地图。

## 使用

将本仓库内容放到个人 skills 目录下的 `interactive-3d-atlas` 文件夹中。默认路径为 `~/.codex/skills/interactive-3d-atlas`；如已配置 `CODEX_HOME`，使用该目录下的 `skills/interactive-3d-atlas`。

调用示例：

> 用 $interactive-3d-atlas 做一辆银色保时捷 911，可旋转、拆解、点选部件。

## 规则内容

- [入口与工作流](SKILL.md)
- [结构与拆解](references/geometry-and-explosion.md)
- [材质、灯光和投影](references/materials-and-lighting.md)
- [有依据的空间地图](references/evidence-led-maps.md)
- [交互、验证和交付](references/interaction-and-delivery.md)
- [历史案例与修正规则](references/case-lessons.md)

本仓库保存制作规则及调用配置，不包含汽车或飞机模型、原厂 CAD 数据、网站凭据或在线服务。使用具体模型和资料时，应另行核对版本、来源及许可；网页制作与发布使用当前环境可用的工具。
