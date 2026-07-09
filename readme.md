# 梦塔防封严腱鞘炎辅助工具

一个帮助梦塔防玩家减少重复操作、保护手腕健康的自动化辅助工具。通过图像识别技术，自动检测技能冷却状态并释放技能。

## 功能特性

- **窗口绑定**：自动识别梦塔防游戏窗口
- **技能检测**：实时检测技能冷却状态（Ready/Cooldown）
- **自动释放**：技能就绪时自动释放
- **坐标采集**：可视化拖动框选技能区域，无需重复训练
- **快捷开关**：F12键在游戏内快速开启/关闭辅助功能
- **独立控制**：每个功能可单独开启或关闭

## 支持的功能

| 功能 | 快捷键 | 说明 |
|------|--------|------|
| 技能F1 | F1 | 主要技能释放 |
| 锤子 | T | 眩晕怪物 |
| 包大伯 | W | 召唤包大伯 |
| 科技 | E | 升级包大伯 |

## 工具截图

![主界面](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/用法.png)

## 使用说明

### 快速开始

1. 下载并解压 `v1.3.7.zip`
2. 运行 `DreamTowerHelper.exe`
3. 点击「绑定窗口」（绑定时游戏不要最小化）
4. 如果是首次使用，需要进行训练；如果已有坐标配置，直接拖动框选即可

### 训练模式

1. 在训练模式下，分别对技能(F1)、锤子、包大伯(W)、科技(E) 4个功能进行框选
2. 框选后点击采集（技能能释放的状态 Ready）
3. 按 F2 释放技能，再按 F2 采集 Cooldown 状态
4. 完成对4个功能的框选和采集

**训练参考截图：**

技能框选示例：

![F1 Ready](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/F1/Ready.png)
![F1 Cooldown](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/F1/Cooldown.png)

锤子框选示例：

![Hammer Ready](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/Hammer/Ready.png)
![Hammer Cooldown](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/Hammer/Cooldown.png)

包大伯框选示例：

![W Ready](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/W/Ready.png)
![W Cooldown](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/W/Cooldown.png)

科技框选示例：

![E Ready](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/E/Ready.png)
![E Cooldown](https://raw.githubusercontent.com/nomoneynolife/mtf-fy-auto/master/bin/Debug/net451/Templates/E/Cooldown.png)

### 坐标采集

- 更新坐标采集功能，避免重复训练采集图片
- 直接拖动框选到对应位置即可
- 如果没有4个框框，点击重置坐标

## 注意事项

1. **绑定窗口时游戏不要最小化**，否则程序会卡死，可通过任务管理器终止 `DreamTowerHelper.exe` 进程
2. 工具基于坐标识别，**更改分辨率会导致功能失效**（不改分辨率可以移动窗口）
3. F12 键在游戏内可以开启/关闭程序功能
4. 主界面取消勾选后会立即生效（如科技7/1后即可取消勾选）
5. 首次在新电脑使用必须训练，后续更换坐标即可（屏幕色彩差异）

## 运行环境

- Windows 7/8/10/11
- .NET Framework 4.5.1 或更高版本

## 下载地址

当前版本：**v1.3.7**

下载：`v1.3.7.zip`

## 开源说明

开发中，暂不开源。欢迎提 issues。

## 开源协议

本项目采用 **MIT 开源协议**进行开源，遵循 MIT 协议的核心条款，允许任何人免费使用、修改、分发本工具代码（包括商业用途），仅需在软件及副本中保留原作者的版权声明和许可声明即可。
