# 快速开始指南 (Quick Start)

---

## 三步激活

### 1. 复制到 OpenClaw Skills

```bash
cd ~/.openclaw/skills
git clone https://github.com/aixxww/ai-manga-studio.git
```

### 2. 启用技能

编辑 `~/.openclaw/openclaw.json`：

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

### 3. 发送激活指令

在对话中输入：

```
你现在是拥有千万级销量打造经验的日本顶尖漫画编辑...
（详见 SKILL.md 激活部分或 templates/01-persona.txt）
```

---

## 创作流程速查

### Day 1: 确定方向
1. **受众分析** → 使用 prompts/phase1-audience.md
2. **选题决策** → 选择一个 Logline
3. **激活编辑引擎** → 输入 templates/01-persona.txt

### Day 2-3: 世界观与角色
1. **世界观设定** → 使用 prompts/phase2-world.md
2. **创建 IP Bible** → 填写 templates/02-ip-bible.txt
3. **角色 DNA** → 使用 prompts/phase3-character.md

### Day 4: 剧情规划
1. **第一卷大纲** → 使用 templates/03-story.md 模块A
2. **世界观细化** → 补充铁律、阵营、现象

### Day 5+: 分镜与生图
1. **单话脚本** → 使用 prompts/phase5-script.md
2. **Nano Banana 2 生图** → 使用 templates/04-render.md
3. **去 AI 味** → 使用 prompts/phase6-deai.md

---

## 关键记忆点

### 角色一致性 🎯
角色 A 视觉锚点必带：
```
1boy, messy black hair, dead fish eyes, heavy eyebags, tired expression, loose unbuttoned office suit
```

### 固定画风 🎨
```
Vertical black and white Japanese manga page, screentone shading, high contrast line art, single manga panel, monochrome,
```

### 万能生图公式 ⚡
```
[画风基调] + [角色锚点] + [动作表情] + [场景特效]
```

---

## 提示词速用

| 阶段 | 文件 | 复制即可 |
|------|------|---------|
| 受众分析 | prompts/phase1-audience.md | ✅ |
| 世界观 | prompts/phase2-world.md | ✅ |
| 角色 DNA | prompts/phase3-character.md | ✅ |
| 视觉资产 | prompts/phase4-visual.md | ✅ |
| 分镜脚本 | prompts/phase5-script.md | ✅ |
| 去AI味 | prompts/phase6-deai.md | ✅ |

---

## 常见问题

**Q: AI 画风不一致怎么办？**
A: 固定视觉锚点！角色、场景每次都用相同英文 tag。

**Q: 台词太 AI 味？**
A: 用 phase6-deai.md 的"对白人味化处理"模块。

**Q: 不知道画什么？**
A: 从 phase1 受众分析开始，痛点即看点。

**Q: 钩子写不好？**
A: 用"熟悉的配方 + 意想不到的味道"公式。

---

## 下一步

开始第一阶段：`cat prompts/phase1-audience.md | pbcopy`

然后发给 AI，开始你的漫画创作之旅！ 🚀

---

*Happy Creating! 🦞*