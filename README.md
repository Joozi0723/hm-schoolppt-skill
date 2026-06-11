# HM 学校 PPT Skill (hm-school-ppt)

> HM 学校品牌 PPT 生成系统 — 基于 ppt-master v2.6 引擎，输出原生可编辑 PPTX

## 简介

这是一个 **WorkBuddy Skill**，专用于生成 HM 学校（广州华美英语实验学校）品牌风格的 PowerPoint 演示文稿。

## 适用场景

- 校长办公会汇报
- 学部周报
- 品牌办材料
- 招生宣讲
- 活动总结
- 战略演示

## 品牌配色

| 颜色名称 | 色值 | 用途 |
|---------|------|------|
| 深紫 | `#48004E` | 封面底、顶部标题栏 |
| 金色 | `#9A6E3F` | 分隔线、强调、图表主色 |
| 中紫 | `#600769` | 辅助强调、文字点缀 |
| 浅灰底 | `#F2F2F2` | 内容页背景 |

## 使用方法

1. 下载 `huamei-school-ppt-full.zip`
2. 解压到 WorkBuddy skills 目录：`~/.workbuddy/skills/`
3. 在对话中输入触发关键词：
   - **HM学校PPT**
   - **HM汇报**
   - **HM学校风格**
   - **品牌办周报**

## 核心能力

- 📄 支持从 PDF / DOCX / Excel / 网页等源材料自动提取内容
- 🎨 锁定 HM 学校 VI 标准，自动应用品牌规范
- 🖼️ AI 图片生成 + 多风格渲染支持
- ✅ 输出**原生可编辑 PPTX**（文字/形状/图表均可点击修改）
- 🔍 浏览器实时预览，所见即所得

## 文件说明

本仓库包含完整的 skill 包（zip 格式），解压后结构如下：

```
hm-school-ppt/
├── SKILL.md              # Skill 定义文件
├── scripts/              # 核心脚本工具集
├── templates/            # 模板资源（布局/品牌/图标）
├── references/           # 参考文档与规范
├── workflows/            # 工作流定义
├── assets/               # Logo 与品牌素材
└── docs/                 # 详细文档与 FAQ
```

## 技术依赖

- Python 3.8+
- ppt-master v2.6 引擎

## 许可

内部使用。
