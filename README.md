# Rubik's Cube Solver

一个基于浏览器的魔方标色、校验、求解和动画演示工具。

## 功能

- 2D / 3D 双视图
- 颜色标记与状态串输入
- 魔方合法性检查
- 固定公式 LBL 求解
- 可选两阶段求解
- 播放、上一步、下一步
- 撤销 / 重做
- 鼠标视角、标色、手工转动

## 颜色标准

- U: 黄
- D: 白
- F: 蓝
- B: 绿
- L: 橙
- R: 红

状态串顺序为 `U R F D L B`。

## 使用

1. 用任意静态服务器打开 `index.html`。
2. 在 2D 或 3D 视图中标色，或者直接输入状态串。
3. 点击“求解”，再用播放或步进查看解法。

示例：

```bash
python3 -m http.server 8000
```

## 控制

- `U / R / F / D / L / B`：手工转动
- `Shift`：反向
- 鼠标转动模式：左键点贴纸正向，右键逆向，拖拽调视角

---

A browser-based Rubik's Cube tool for coloring, validation, solving, and animation.

## Features

- Dual 2D / 3D views
- Color marking and state-string input
- Cube validity checks
- Strict LBL solver
- Optional two-phase solver
- Playback, step-by-step navigation
- Undo / redo
- Mouse orbit, coloring, and manual turns

## Color Standard

- U: yellow
- D: white
- F: blue
- B: green
- L: orange
- R: red

The facelet string order is `U R F D L B`.

## Usage

1. Open `index.html` through any static server.
2. Mark colors or paste a state string.
3. Click Solve, then play or step through the solution.

Example:

```bash
python3 -m http.server 8000
```

## Controls

- `U / R / F / D / L / B`: manual turns
- `Shift`: inverse
- Mouse turn mode: left click for clockwise, right click for inverse, drag to orbit
