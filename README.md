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

## 📚 阅读语言 / Language / 言語

| 🇨🇳 中文 | 🇺🇸 English | 🇯🇵 日本語 |
|---------|-------------|-----------|
| [中文版](#简介) | [English](#english) | [日本語](#日本語) |

---

## 🇨🇳 中文版

### 简介

AI Manga Studio 是为 OpenClaw Agent 设计的漫画创作技能，提供完整的 AI 漫画创作流程指南。从受众分析到最终成稿，涵盖创作全流程，支持中/英/日三种语言。

基于 **Gemini** 文本模型和 **Nano Banana 2** 图像模型，打造具有网感、强反差萌、适合社交媒体传播的连载漫画。

### 特性

- 🎯 **零基础友好**：完整的六阶段创作流程
- 🌍 **多语言支持**：中文、英文、日文版本
- 🤖 **AI 驱动**：Gemini + Nano Banana 2 完美配合
- 🎨 **视觉一致**：角色与场景固定 Prompt 模板
- 💡 **去 AI 味**：人感注入技巧与排版建议

### 安装

#### OpenClaw Agent

将此技能复制到 OpenClaw skills 目录：

```bash
cd ~/.openclaw/skills
git clone https://github.com/Aixxww/AI-Manga-Studio.git
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

#### 独立使用

直接查看各语言版本的 SKILL 文件：
- `SKILL.md` - 中文版
- `SKILL_EN.md` - 英文版
- `SKILL_JP.md` - 日文版

### 快速开始

1. **激活 AI 编辑引擎** - 发送激活指令给 AI
2. **分析受众痛点** - 使用受众分析模块
3. **构建世界观** - 设定3条不可违背的铁律
4. **建立角色 DNA** - 创建角色档案和视觉锚点
5. **生成分镜脚本** - 将大纲转化为可执行的分镜
6. **Nano Banana 2 生图** - 使用万能公式生成图像

### 项目结构

```
ai-manga-studio/
├── SKILL.md              # 中文技能定义
├── SKILL_EN.md           # 英文技能定义
├── SKILL_JP.md           # 日文技能定义
├── README.md             # 本文件
├── package.json          # OpenClaw 元数据
├── locales/              # 多语言模板
├── prompts/              # 完整提示词库
└── templates/            # 项目模板
```

### 六阶段流程

1. **Phase 1**: 破局与定位 - 受众分析、反差选题
2. **Phase 2**: 骨架构建 - 世界观铁律、卷首大纲
3. **Phase 3**: 灵魂注入 - 角色DNA、视觉锚点
4. **Phase 4**: 视觉资产 - 场景、道具、氛围
5. **Phase 5**: 连载执行 - 分镜脚本转化
6. **Phase 6**: 炼金术 - 去AI味、破格排版

### Nano Banana 2 生图公式

```
[画风基调] + [角色视觉锚点] + [动作表情] + [场景特效]
```

### 环境变量

```bash
AI_MANGO_STUDIO_LANG=zh  # 语言：zh/en/jp
```

---

## 🇺🇸 English

### Introduction

AI Manga Studio is an OpenClaw Agent skill for manga creation, providing a complete AI-assisted manga production workflow. From audience analysis to final rendering, covering the entire creative process with support for Chinese/English/Japanese.

Powered by **Gemini** text model and **Nano Banana 2** image model, creating internet-viral serialized manga with strong contrast appeal.

### Features

- 🎯 **Beginner Friendly**: Complete six-stage workflow
- 🌍 **Multi-language**: Chinese, English, Japanese versions
- 🤖 **AI Driven**: Gemini + Nano Banana 2 integration
- 🎨 **Visual Consistency**: Character & scene fixed prompt templates
- 💡 **De-AI-fication**: Human touch injection & layout tips

### Installation

#### OpenClaw Agent

Clone to OpenClaw skills directory:

```bash
cd ~/.openclaw/skills
git clone https://github.com/Aixxww/AI-Manga-Studio.git
```

Enable in `openclaw.json`:

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

#### Standalone Usage

Read language-specific SKILL files:
- `SKILL.md` - Chinese
- `SKILL_EN.md` - English
- `SKILL_JP.md` - Japanese

### Quick Start

1. **Activate AI Editor Engine** - Send activation command to AI
2. **Analyze Audience Pain Points** - Use audience analysis module
3. **Build World-view** - Set 3 unbreakable iron rules
4. **Create Character DNA** - Build character profile & visual anchors
5. **Generate Storyboard Script** - Convert outline to executable panels
6. **Nano Banana 2 Image Generation** - Use universal formula

### Project Structure

```
ai-manga-studio/
├── SKILL.md              # Chinese skill definition
├── SKILL_EN.md           # English skill definition
├── SKILL_JP.md           # Japanese skill definition
├── README.md             # This file
├── package.json          # OpenClaw metadata
├── locales/              # Multi-language templates
├── prompts/              # Complete prompt library
└── templates/            # Project templates
```

### Six-Stage Workflow

1. **Phase 1**: Market & Concept - Audience analysis, reverse-topic
2. **Phase 2**: World-building - Iron rules, volume outline
3. **Phase 3**: Characters - Character DNA, visual anchors
4. **Phase 4**: Visual Assets - Scenes, props, atmosphere
5. **Phase 5**: Scripting - Storyboard conversion
6. **Phase 6**: De-AI-fication - Human touch, break-frame layout

### Nano Banana 2 Generation Formula

```
[Art Style Base] + [Character Visual Anchor] + [Action/Expression] + [Scene/Effects]
```

### Environment Variables

```bash
AI_MANGO_STUDIO_LANG=en  # Language: zh/en/jp
```

---

## 🇯🇵 日本語

### 紹介

AIマンガスタジオはOpenClaw Agentのためのマンガ作成スキルで、完全なAI支援マンガ制作ワークフローを提供します。読者分析から最終レンダリングまで、制作全プロセスをカバーし、中国語/英語/日本語をサポートします。

**Gemini**テキストモデルと**Nano Banana 2**画像モデルで、強いコントラスト魅力を持つインターネットバイラル連載マンガを作成します。

### 特徴

- 🎯 **初心者に優しい**：完全な6段階ワークフロー
- 🌍 **多言語対応**：中国語、英語、日本語版
- 🤖 **AI駆動**：Gemini + Nano Banana 2統合
- 🎨 **ビジュアル一貫性**：キャラクターとシーン固定プロンプトテンプレート
- 💡 **脱AI感**：人間感注入とレイアウトティップ

### インストール

#### OpenClaw Agent

OpenClaw skillsディレクトリにクローン：

```bash
cd ~/.openclaw/skills
git clone https://github.com/Aixxww/AI-Manga-Studio.git
```

`openclaw.json`で有効化：

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

#### スタンドアロン使用

言語別SKILLファイルを読む：
- `SKILL.md` - 中国語
- `SKILL_EN.md` - 英語
- `SKILL_JP.md` - 日本語

### クイックスタート

1. **AI編集エンジン有効化** - AIにアクティベーションコマンドを送る
2. **読者痛みポイント分析** - 読者分析モジュールを使用
3. **世界観構築** - 破ってはいけない3つの鉄則を設定
4. **キャラクターDNA作成** - キャラクタープロファイルとビジュアルアンカー作成
5. **コマ割りスクリプト生成** - アウトラインを実行可能なコマに変換
6. **Nano Banana 2画像生成** - 万能公式を使用

### プロジェクト構造

```
ai-manga-studio/
├── SKILL.md              # 中国語スキル定義
├── SKILL_EN.md           # 英語スキル定義
├── SKILL_JP.md           # 日本語スキル定義
├── README.md             # 本ファイル
├── package.json          # OpenClawメタデータ
├── locales/              # 多言語テンプレート
├── prompts/              # 完全プロンプトライブラリ
└── templates/            # プロジェクトテンプレート
```

### 6段階ワークフロー

1. **Phase 1**: 市場とコンセプト - 読者分析、逆説企画
2. **Phase 2**: 世界観構築 - 鉄則、巻頭アウトライン
3. **Phase 3**: キャラクター - キャラクターDNA、ビジュアルアンカー
4. **Phase 4**: ビジュアル資産 - シーン、小道具、雰囲気
5. **Phase 5**: 連載実行 - コマ割りスクリプト変換
6. **Phase 6**: 脱AI感 - 人間の味、破枠レイアウト

### Nano Banana 2生成公式

```
[画風ベース] + [キャラクタービジュアルアンカー] + [アクション/表情] + [シーン/エフェクト]
```

### 環境変数

```bash
AI_MANGO_STUDIO_LANG=jp  # 言語: zh/en/jp
```

---

## License

MIT License

## 作者

AIxxww

## 贡献 / Contribute / 貢献

欢迎提交 Issue 和 Pull Request！/ Welcome to submit Issues and Pull Requests! / IssueとPull Requestをお待ちしています！

---

<p align="center">
  Made with ❤️ by AIxxww + Claude Code
</p>
