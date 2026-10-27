# 自媒体剪辑 Skill

这是一个用于 AI 商业口播、电商复刻和工具教程视频的 Codex skill。它指导助手先盘点素材、对齐口播并提交素材插入方案，经用户核对后再按目标画幅剪辑、检查和交付。

## 包含内容

- [`SKILL.md`](./SKILL.md)：完整的工作流程、横竖屏布局要求、演示素材与人物圆形画中画规则、封面 Prompt 和交付检查项。

## 安装

在尚未安装此 skill 的机器上运行：

```bash
git clone https://github.com/Hisensen/zimeiti-jianji-skill.git ~/.agents/skills/自媒体剪辑
```

然后在 Codex 中提出剪辑需求，或明确提及“自媒体剪辑” skill。

## 使用前准备

提供口播原片、文案和相关图片、录屏等素材，并说明目标画幅。Skill 会先生成“素材—口播”对应表，待你核对后再制作正式成片。

`SKILL.md` 中的 V27Cinema 和 V22Biz 指向作者本机的 Remotion 参考工程。该工程和视频素材不包含在本仓库中；在其他机器使用时，需要提供相应模板，或按 skill 中的说明采用近似方案。
