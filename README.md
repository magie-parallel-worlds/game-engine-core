# 🎮 Game Engine Core / 游戏引擎核心

A pure-logic game engine implementing Lizzie Magie's original economic rules in both "Prosperity" and "Monopoly" modes.  
纯逻辑游戏引擎，支持马吉原版“繁荣模式”与“垄断模式”双规则。

## 🧩 功能边界 / Scope
- Game state management (state machine)  
  游戏状态机管理
- Rule enforcement for both modes  
  双模式规则执行
- Event system (trade, tax, rent, etc.)  
  事件系统（交易、征税、租金等）
- No UI / rendering — logic only  
  无 UI，仅逻辑层

## ⚙️ 技术栈 / Tech Stack
- TypeScript
- Jest (unit tests)
- JSON-based rule configuration

## 🚀 本地开发 / Development
```bash
git clone https://github.com/magie-parallel-worlds/game-engine-core.git
cd game-engine-core
npm install
npm test
