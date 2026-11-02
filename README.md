# 你健哥的场景生成器

将场景描述或参考照片转成真实场景资产，供后续图片、视频和分镜创作使用。

- 有参考图时，生成前确认同机位或新机位、完整环境或白底独立布景，以及家具陈设的处理方式。
- 先生成一张独立主图，完成后可选生成同场景的多机位九视图。
- 九视图编号 01–09，选择编号后分别提取对应独立图片。
- 多机位先固定空间布局，再移动相机，并核对结构、陈设、材质与光线的一致性。

技能入口：[SKILL.md](SKILL.md)。技能标识：`scene-asset-generator`。

文件结构：

```text
scene-asset-generator/
├── SKILL.md
├── agents/openai.yaml
└── references/
    ├── prompt-blueprints.md
    └── multiview-nine.md
```
