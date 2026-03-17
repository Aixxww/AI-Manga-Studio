# AI Manga Studio — AI漫画创作工作台

<p align="center">
  <strong>一站式 AI 漫画创作指南 | Gemini & Nano Banana 2 驱动</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-1.0.0-blue.svg" alt="Version">
  <img src="https://img.shields.io/badge/license-MIT-green.svg" alt="License">
  <img src="https://img.shields.io/badge/languages-zh%20%7C%20en%20%7C%20jp-orange.svg" alt="Languages">
</p>

---

## 简介

AI Manga Studio 是为 OpenClaw Agent 设计的漫画创作技能，提供完整的 AI 漫画创作流程指南。从受众分析到最终成稿，涵盖创作全流程，支持中/英/日三种语言。

基于 **Gemini** 文本模型和 **Nano Banana 2** 图像模型，打造具有网感、强反差萌、适合社交媒体传播的连载漫画。

## 特性

- 🎯 **零基础友好**：完整的六阶段创作流程
- 🌍 **多语言支持**：中文、英文、日文版本
- 🤖 **AI 驱动**：Gemini + Nano Banana 2 完美配合
- 🎨 **视觉一致**：角色与场景固定 Prompt 模板
- 💡 **去 AI 味**：人感注入技巧与排版建议

## 安装

### OpenClaw Agent

将此技能复制到 OpenClaw skills 目录：

```bash
cd ~/.openclaw/skills
git clone https://github.com/aixxww/ai-manga-studio.git
```

在 `openclaw.json` 中启用：

```json
{
  "skills": {
    "entries": {
      "ai-manga-studio": {
        "enabled": true
      }
    }
  }
}
```

### 独立使用

直接查看各语言版本的 SKILL 文件：

- `SKILL.md` - 中文版
- `SKILL_EN.md` - 英文版
- `SKILL_JP.md` - 日文版

## 快速开始

### 1. 激活 AI 编辑引擎

发送激活指令给 AI：

> 你现在是拥有千万级销量打造经验的日本顶尖漫画编辑...
> （详见 SKILL.md 激活部分）

### 2. 分析受众痛点

使用受众分析模块：

> 我准备创作一部针对[目标群体]的漫画，请分析他们的核心痛点...

### 3. 构建世界观

使用世界观设定模块：

> 结合我的选题，请设定3条不可违背的铁律...

### 4. 建立角色 DNA

创建角色档案和视觉锚点：

> 我需要为主角建立角色DNA档案...

### 5. 生成分镜脚本

将大纲转化为可执行的分镜：

> 请将第[X]话转化为漫画分镜脚本...

### 6. Nano Banana 2 生图

使用万能公式生成图像：

```
Vertical black and white Japanese manga page, screentone shading + 角色anchor + 动作 + 场景
```

## 项目结构

```
ai-manga-studio/
├── SKILL.md              # 中文技能定义
├── SKILL_EN.md           # 英文技能定义
├── SKILL_JP.md           # 日文技能定义
├── README.md             # 本文件
├── package.json          # OpenClaw 元数据
├── locales/              # 多语言模板
│   ├── zh/               # 中文提示词模板
│   ├── en/               # 英文提示词模板
│   └── jp/               # 日文提示词模板
├── prompts/              # 完整提示词库
│   ├── phase1-audience.md
│   ├── phase2-world.md
│   ├── phase3-character.md
│   ├── phase4-visual.md
│   ├── phase5-script.md
│   └── phase6-deai.md
└── templates/            # 项目模板
    ├── 01-persona.txt
    ├── 02-ip-bible.txt
    ├── 03-story.md
    └── 04-render.txt
```

## 六阶段流程

### Phase 1: 破局与定位 (Market & Core Concept)
- 受众目标群体画像分析
- 选题与题材（反套路法则）
- 故事内核定义

### Phase 2: 骨架构建 (World-building & Plot)
- 世界观铁律设定
- 卷首大纲规划
- 悬念设计

### Phase 3: 灵魂注入 (Characters & Progression)
- 角色DNA建档
- 视觉锚点Prompt
- 角色弧光设计

### Phase 4: 视觉资产的建档 (Visual Consistency)
- 主场景固定Prompt
- 核心道具定义
- 氛围网点SOP

### Phase 5: 连载执行与分镜 (Scripting & Storyboarding)
- 章节设计脚本化
- 分镜脚本转化
- 翻页感设计

### Phase 6: 炼金术——去AI味 (De-AI-fication)
- 拒绝完美，拥抱瑕疵
- 打破格子，制造破框
- 对白与潜台词
- 制造"神回"记忆点

## Nano Banana 2 生图公式

```
[画风基调] + [角色视觉锚点] + [动作表情] + [场景特效]
```

**固定画风基调**：
```
Vertical black and white Japanese manga page, screentone shading, high contrast line art, single manga panel, monochrome,
```

**完整示例**：
```
Vertical black and white Japanese manga page, screentone shading, high contrast line art, single manga panel, monochrome,
1boy, messy black hair, dead fish eyes, heavy eyebags, tired expression, loose unbuttoned office suit,
is slamming his hands on a desk in frustration, screaming with a comic jagged speech bubble outline next to him,
messy office background, dramatic dark lighting, vertical speed lines showing intense emotion.
```

## 技巧与最佳实践

### 去AI味核心法则

1. **拒绝完美，拥抱瑕疵**
   - Prompt 加入：exhausted, messy hair, dead eyes, asymmetrical

2. **打破格子，制造破框**
   - 武器、魔法阵、对话气泡冲出格子

3. **对白与潜台词**
   - 删减冗长对话，画面能表现的不写

4. **制造"神回"记忆点**
   - 人味脑洞，幽默感

### 角色一致性

- 建立角色 DNA 档案
- 固定 5-8 个英文 tag 作为视觉锚点
- 每次生图必带相同标签

## 环境变量

```bash
AI_MANGO_STUDIO_LANG=zh  # 语言：zh/en/jp
```

## 相关资源

- Nano Banana 2: https://banana.openclaw.ai/
- Gemini Flash Image: https://aistudio.google.com/
- OpenClaw: https://github.com/6551Team/openclaw

## License

MIT License

## 作者

AIxxww

## 贡献

欢迎提交 Issue 和 Pull Request！

---

<p align="center">
  Made with ❤️ by AIxxww + Claude Code
</p>
