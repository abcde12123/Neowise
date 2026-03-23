# NEOWISE - UE5 高节奏双人合作生存游戏

NEOWISE 是一款基于UE5开发的、创新结合了**俄罗斯方块 (Tetris)** 与 **平台跳跃 (Platformer)** 的非对称双人合作生存游戏。

---

## 核心玩法：非对称合作 (Asymmetrical Co-op)
在 NEOWISE 中，生存不再是一个人的事。两位玩家需要高度默契的配合来应对不断坠落的威胁：

- **玩家 A (方块管理)：** 负责方块搭建任务。通过搭建方块来创建场地，或是搭建庇护空间。
- **玩家 B (角色生存)：** 实时操控角色在掉落的方块间跳跃、躲避，必须在方块落地之前寻找生存空间防止被坠落的方块砸中，以及躲避boss弹幕。

**核心冲突：** 放置方块速度过慢能清空场地，但也可能让角色失去立足点；而保留过多方块虽能提供跳跃平台，却会极大压缩生存空间。

---

## 核心技术点

### 1. 碰撞优化
- **网格与物理双重判定：** 实现了方块网格逻辑与角色物理碰撞的实时同步。确保方块在从“逻辑下落”转变为“静态平台”时，角色的站立与碰撞反馈无缝衔接。

### 2. 游戏机制与增益系统
- **增益效果：** 实现护盾、加速、二段跳等 Buff 系统，为角色在极端环境下生存提供策略选择。

### 3. 初始方块随机程序化生成
为了确保每一局游戏的开局体验具有多样性与公平性，项目实现了一套自定义的初始化生成算法：
- **随机生成：** 算法在每个方块生成时随机指定一个俄罗斯方块的样式进行生成。
---

## 开发环境
- **引擎版本：** Unreal Engine 5.4
- **版本控制：** SVN

---

## 项目展示
<img width="2226" height="1391" alt="image" src="https://github.com/user-attachments/assets/d286e511-e002-4ace-8ccb-b02ebf732c24" />
<img width="1806" height="1391" alt="image" src="https://github.com/user-attachments/assets/87bebcf3-7adc-4180-88ba-7936ab5ae3cd" />
<img width="1806" height="1391" alt="image" src="https://github.com/user-attachments/assets/e6816c6a-047c-4b9c-b5f7-b3f0e2b7db3d" />
<img width="1812" height="1391" alt="image" src="https://github.com/user-attachments/assets/6e4404db-80a1-49f9-b659-aab61fea330f" />
<img width="2226" height="1391" alt="image" src="https://github.com/user-attachments/assets/8b7bfdd7-e7e5-44a3-8026-2a62dabd607d" />
