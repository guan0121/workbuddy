# WorkBuddy Skills by 管哥

> 管哥自研的 WorkBuddy Skill 集合仓库 —— 拍完视频一键出发布物料

## 仓库说明

这是管哥（野新派）的 **WorkBuddy Skill 集合仓库**，目前包含：

- `video-publisher-assistant/` —— 短视频发布运营助手（通用版，v1）
- `video-publisher-assistant-alpha/` —— 短视频发布运营助手（安发集团经销商定制版 · 视频号默认）

后续所有管哥自研的 WorkBuddy Skill 都会托管在这个仓库。

---

## Skill 1：video-publisher-assistant（通用版）

**适合**：短视频博主、IP 操盘手、需要每天稳定产出的内容团队

**默认输出**：发布标题 × 3 选 1 + 发布文案 + tag + 评论区置顶 × 2 版 + 朋友圈转发文案 × 2 版

### 一键安装（Mac / Linux）

```bash
mkdir -p ~/.workbuddy/skills/video-publisher-assistant && \
curl -sL https://raw.githubusercontent.com/guan0121/workbuddy/main/video-publisher-assistant/SKILL.md \
  -o ~/.workbuddy/skills/video-publisher-assistant/SKILL.md \
  && echo "✅ video-publisher-assistant 安装完成，重启 WorkBuddy 即可使用"
```

### 一键安装（Windows PowerShell）

```powershell
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/guan0121/workbuddy/main/video-publisher-assistant/SKILL.md" -OutFile "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant\SKILL.md"
```

---

## Skill 2：video-publisher-assistant-alpha（安发经销商版）

**适合**：安发集团旗下经销商、品牌方、合伙人
**默认平台**：视频号
**核心约束**：
- tag ≤ 5 个，必带 `#安发`
- 标题 = 疑问式 + 数字化收获感
- 发布文案 ≤ 100 字、不带互动引导
- 评论区置顶：只输出 1 版（提问引导型）
- 朋友圈：不写跳转路径，用「欢迎大家具体看视频」收尾
- 全程「大白话」风格，10 岁小孩和 60 岁阿姨能听懂

### 一键安装（Mac / Linux）

```bash
mkdir -p ~/.workbuddy/skills/video-publisher-assistant-alpha && \
curl -sL https://raw.githubusercontent.com/guan0121/workbuddy/main/video-publisher-assistant-alpha/SKILL.md \
  -o ~/.workbuddy/skills/video-publisher-assistant-alpha/SKILL.md \
  && echo "✅ video-publisher-assistant-alpha 安装完成，重启 WorkBuddy 即可使用"
```

### 一键安装（Windows PowerShell）

```powershell
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant-alpha"
Invoke-WebRequest -Uri "https://raw.githubusercontent.com/guan0121/workbuddy/main/video-publisher-assistant-alpha/SKILL.md" -OutFile "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant-alpha\SKILL.md"
```

---

## 卸载

```bash
rm -rf ~/.workbuddy/skills/video-publisher-assistant
rm -rf ~/.workbuddy/skills/video-publisher-assistant-alpha
```

## 反馈 / 定制

直接联系作者定制。

---

**作者**：管哥（野新派）
**License**: MIT
