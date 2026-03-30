# Skills 参赛打包指南

## 核心Skills（已打包）

| # | Skill | 目录 | 核心文件 |
|---|--------|------|----------|
| 1 | PRD生成器 | `skills/prd-generator/` | skill.json, README.md |
| 2 | 毒舌产品经理 | `skills/toxic-pm/` | skill.json, README.md |
| 3 | UI提示词设计师 | `skills/ui-prompt-designer/` | skill.json, README.md |

## 参赛提交结构

```
Skills/
├── prd-generator/
│   ├── skill.json
│   ├── README.md
│   └── (其他资源)
│
├── toxic-pm/
│   ├── skill.json
│   ├── README.md
│   └── (其他资源)
│
└── ui-prompt-designer/
    ├── skill.json
    ├── README.md
    └── (其他资源)
```

## 使用方法

### 1. PRD生成器
```json
{
  "name": "prd-generator",
  "version": "1.0.0",
  "description": "专业的PRD生成器，支持完整需求和小需求两种模式"
}
```

### 2. 毒舌产品经理
```json
{
  "name": "toxic-pm",
  "version": "1.0.0", 
  "description": "极度苛刻、毫不留情的资深产品经理"
}
```

### 3. UI提示词设计师
```json
{
  "name": "ui-prompt-designer",
  "version": "1.0.0",
  "description": "专业的UI提示词设计师，生成高质量HTML/CSS代码"
}
```

## 打包命令

```bash
# 打包Skills目录
cd ~/Desktop/work/AI/.sisyphus/skills/
tar -czvf skills-submission.tar.gz prd-generator toxic-pm ui-prompt-designer
```

## 验证完整性

```bash
# 检查文件
ls -la prd-generator/
ls -la toxic-pm/
ls -la ui-prompt-designer/
```

每个Skill应包含:
- ✅ skill.json (配置文件)
- ✅ README.md (使用说明)

---

*Skills打包 v1.0*
*创建时间: 2026-02-06*
