# 短视频发布运营助手 (video-publisher-assistant)

> 管哥自用的 WorkBuddy Skill —— **拍完视频后一站式出发布四件套**：
> 发布标题 × 3 选 1 + 发布文案（含热门 tag）+ 评论区置顶 × 2 版 + 朋友圈转发文案 × 2 版

## 仓库说明

这是管哥（野新派）的 **WorkBuddy Skill 集合仓库**，目前包含：

- `video-publisher-assistant/` —— 短视频发布运营助手（首发）

后续所有管哥自研的 WorkBuddy Skill 都会托管在这个仓库。

## 一键安装（Mac / Linux）

打开终端，复制下面这条命令粘贴回车：

```bash
git clone https://github.com/guan0121/guan-ge-skills.git \
  && mkdir -p ~/.workbuddy/skills/video-publisher-assistant \
  && cp guan-ge-skills/video-publisher-assistant/SKILL.md \
        ~/.workbuddy/skills/video-publisher-assistant/SKILL.md \
  && echo "✅ video-publisher-assistant 安装完成，重启 WorkBuddy 即可使用"
```

## 一键安装（Windows PowerShell）

```powershell
git clone https://github.com/guan0121/guan-ge-skills.git
New-Item -ItemType Directory -Force -Path "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant"
Copy-Item "guan-ge-skills\video-publisher-assistant\SKILL.md" "$env:USERPROFILE\.workbuddy\skills\video-publisher-assistant\SKILL.md" -Force
Write-Host "✅ video-publisher-assistant 安装完成，重启 WorkBuddy 即可使用" -ForegroundColor Green
```

## 使用方法

重启 WorkBuddy 后，跟它说：

```
帮我写个视频发布四件套
```

或者直接扔一条视频内容给它：

```
这条视频讲的是怎么用 AI 帮小餐饮店做获客，3 个真实案例，帮我写发布四件套
```

AI 会自动输出：

```
1. 发布标题（3 选 1）
2. 发布文案 + 热门 tag
3. 评论区置顶（2 选 1）
4. 朋友圈转发文案（2 选 1）
```

## 覆盖平台

抖音 / 视频号 / 小红书 / 快手 / B 站 —— 各平台调性自动适配。

## 卸载

```bash
rm -rf ~/.workbuddy/skills/video-publisher-assistant
```

## 适用对象

- 短视频博主、IP 操盘手
- 需要每天稳定产出的内容团队
- 想把"发布环节"标准化的工作室

## 反馈 / 定制

如果想要：
- 加新平台（比如知乎视频、即刻动态）
- 改四件套的字段（比如加挂车引导）
- 适配你的具体人设和行业

直接联系作者定制。

---

**作者**：管哥（野新派）
**License**: MIT
