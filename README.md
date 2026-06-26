# 高考志愿填报智能规划

为高考考生提供数据驱动的志愿填报方案，核心优势是**挖掘信息差机会**，帮助考生用同等分数读更好的学校/专业。

## 功能

- 分数定位与位次分析
- 院校专业匹配（冲/稳/保三档）
- 信息差机会挖掘：
  - 专项计划（高校专项/地方专项/国家专项）
  - 中外合作办学（用学费换分数）
  - 外省院校降维录取
  - 征求志愿捡漏
  - 转专业通道
  - 提前批特殊通道（军校/公安/免费师范等）

## 项目结构

```
├── SKILL.md                      # 技能定义（工作流程、输入参数、输出格式）
├── references/
│   ├── matching-strategy.md      # 院校专业匹配策略参考
│   └── special-programs.md       # 特殊招生通道参考
├── zanshang.png                   # 赞赏二维码
├── shangwu.png                    # 商务联系二维码
└── README.md                     # 本文件
```

## 安装

### 方式一：口令安装（推荐）

对 AI 助手说：请先检查是否已安装 SkillHub 商店，若未安装，请根据 https://skillhub.cn/install/skillhub.md 安装SkillHub商店，但是只安装CLI，然后安装toutiao-article-publish技能。若已安装，则直接安装toutiao-article-publish技能。

AI 会自动执行以下流程：

1. 检查 SkillHub CLI 是否已安装
2. 若未安装 → 先安装 SkillHub CLI（仅 CLI）
3. 安装 collegeplanner 技能

### 方式二：手动安装

```bash
# 1. 安装 SkillHub CLI（仅 CLI）
curl -fsSL https://skillhub-1388575217.cos.ap-guangzhou.myqcloud.com/install/install.sh | bash -s -- --cli-only

# 2. 安装技能
skillhub install collegeplanner --dir ~/.codex/skills/
```

### 方式三：GitHub 安装

```bash
python ~/.codex/skills/.system/skill-installer/scripts/install-skill-from-github.py \
  --repo yibeixiaobai/college-admission-planner
```

## 使用方式

当用户提及"高考志愿""志愿填报""志愿规划""选专业"等关键词时，技能自动触发。

支持全国各省份，自动识别新高考/老高考模式。

## 赞赏与联系

<table>
  <tr>
    <td align="center">
      <b>赞赏</b><br>
      <img src="zanshang.png" width="120"><br>
      <sub>赞助一杯咖啡 ☕</sub>
    </td>
    <td align="center">
      <b>商务联系</b><br>
      <img src="shangwu.png" width="120">
    </td>
  </tr>
</table>

