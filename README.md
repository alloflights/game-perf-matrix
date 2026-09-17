# Game Performance & PC Adaptation Matrix (2026)

> 🎮 **国内畅销手游 Top 50 ✕ Supercell 全家桶：移动端性能门槛与电脑端适配体验全景矩阵**  
> 纯本地离线可交互看板（零外部依赖、双击秒开）与多维数据分析报告。

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Zero-Dependency](https://img.shields.io/badge/Dependencies-Zero-brightgreen.svg)](index.html)
[![Offline Ready](https://img.shields.io/badge/Offline-100%25-orange.svg)](index.html)

---

## 🌟 项目亮点

1. **2026 最新移动端芯片天梯锚点**：基于苹果 **A19 Pro / A18 Pro**、高通 **骁龙 8 Elite / 8 Gen 3**、联发科 **天玑 9400** 量化 5 级真实畅玩门槛。
2. **PC 端五大体验迁移定级**：
   - **Tier 1: 完美上位替代**（次时代原生客户端 / 端游完全体生态）
   - **Tier 2: 比手机端略好**（大屏多开防发热增益）
   - **Tier 3: 相仿 / 互有优缺点**（大屏 vs 多指触控平分秋色）
   - **Tier 4: 比手机端稍差**（双摇杆冲突 / 模拟器转译及匹配隔离）
   - **Tier 5: 完全没有 / 体验极差**（触控专属 / 严打模拟器）
3. **四象限交互归因模型**：深度解构重度算力释放、双摇杆极坐标壁垒与地缘战略大屏协同机制。
4. **100% 纯本地离线单文件 (`index.html`)**：零外部 CDN 请求，断网秒开，完美适配电脑、平板及手机浏览器。

---

## 🚀 快速启动

### 本地直接运行
本项目为纯静态单文件应用，**无需安装任何运行环境或构建工具**：

```bash
# 克隆仓库
git clone git@github.com:allofights/game-perf-matrix.git
cd game-perf-matrix

# macOS 直接双击打开
open index.html
```

* **手机/平板运行**：直接将 `index.html` 传至手机，使用任意浏览器（Safari / Chrome / Via / 夸克）点开即可流畅交互。

---

## 📊 四象限分布速查

```
       PC端相对体验 (Y)
          ▲
  Tier 1  │      【象限 II: 策略大屏增益区】       │     【象限 I: 重度算力上位区】
  (完美上位)│  • 梦幻西游 / 率土之滨 / 崩铁       │  • 原神 / 鸣潮 / 三角洲行动 / 绝区零
          │  • 剑与远征:启程 / 阴阳师 / 三战     │  • 无畏契约 / 和平精英 (端游生态)
  Tier 2  │  (低中门槛，PC多开挂机不发热)       │  • 尘白禁区 / 逆水寒 / 妮姬
──────────┼──────────────────────────────────────┼────────────────────────────────────►
  Tier 3  │                                      │
  (相仿互优)│  • 炉石 / 金铲铲 / 部落冲突(CoC)      │  • 第五人格 (键鼠准但独立排队)
          │  【象限 III: 触控原生折损区】       │  【象限 IV: 高负荷移植受限区】
  Tier 4  │  • 王者荣耀 (双摇杆操作冲突)        │  • DNF手游模拟器 (搓招割裂)
  (稍差/极差)│  • 荒野乱斗 / 开心消消乐 / Monopoly  │  • FC足球世界 / 实况足球 (传控手感)
          │  • 捕鱼大作战 / 斗地主 / 怪物弹珠    │  (高算力消耗，但跨端移植体验受限)
  Tier 5  ▼
          └──────────────────────────────────────┴────────────────────────────────────
            Level 1~2 (轻度~中轻)                 Level 3~5 (中重~次时代极重)
                                                               手机端性能负荷 (X)
```

详细完整的数据分类与技术归因请参阅 [REPORT.md](REPORT.md)。

---

## 📁 目录结构

```text
game-perf-matrix/
├── index.html       # 纯离线交互式散点矩阵看板 (内置全内联 CSS/JS/SVG)
├── REPORT.md        # 55款海内外热门游戏深度分析报告与硬件量化天梯
└── README.md        # 项目说明
```

---

## 📄 开源许可

本项目遵循 [MIT License](LICENSE)。
