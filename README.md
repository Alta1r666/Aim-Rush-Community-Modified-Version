# Aim Rush - Community Modified Version

> A community-modified version of the classic CS2 warm-up and aim training map **Aim Rush**, originally created by **JoeyyBiden**.

---

<a id="table-of-contents"></a>

## Table of Contents / 目录

### English

- [Project Overview](#en-overview)
- [How to Use](#en-usage)
- [Version Information](#en-version)
- [Basic Controls](#en-controls)
- [Weapon Selection](#en-weapons)
- [Knives & Utilities](#en-knives)
- [Preset Configurations](#en-presets)
- [Bot Logic](#en-bots)
- [Enhanced Bot Utility Reactions](#en-utility-reactions)
- [Credits](#en-credits)
- [Related Links](#en-links)

### 中文

- [项目概览](#zh-overview)
- [使用方法](#zh-usage)
- [版本提示](#zh-version)
- [基本使用说明](#zh-controls)
- [枪械选择](#zh-weapons)
- [匕首与道具](#zh-knives)
- [预设配置](#zh-presets)
- [Bot 逻辑说明](#zh-bots)
- [Enhanced Bot 对道具的反应](#zh-utility-reactions)
- [致谢](#zh-credits)
- [相关链接](#zh-links)

---

# English

<a id="en-overview"></a>

## Project Overview

This project is a CS2 Workshop map based on the classic **Aim Rush** map created by **JoeyyBiden**.

It builds upon the original map with additional weapons, knives, utilities, preset configurations, Bot behavior options, and various bug fixes and gameplay improvements.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-usage"></a>

## How to Use

Search for the following map in the CS2 Steam Workshop:

**Aim Rush - Community Modified Version**

Subscribe to the map and launch the international version of CS2. The map will then be available in your Workshop maps.

- **Steam Workshop:**  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3779660631

- **Workshop ID:**  
  `3779660631`

[Back to Table of Contents](#table-of-contents)

---

<a id="en-version"></a>

## Version Information

When the map is loaded, the current version number will be displayed in the in-game text panel.

> [!IMPORTANT]
> If the displayed version is lower than **v2.2.0**, or no version number is shown, please update the map to ensure the best experience.

### How to Force a Workshop Update

Steam Workshop may not always update the map automatically.

If your map is not updating:

1. Unsubscribe from the map.
2. Subscribe to it again.
3. If CS2 starts downloading Workshop files, the map update has been triggered.
4. Enter the map again and check the displayed version number.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-controls"></a>

## Basic Controls

- All interactive objects can be activated using the **Use / Interact key**.
- Most interactive objects can also be triggered by **dealing damage to them**.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-weapons"></a>

## Weapon Selection

<!-- Insert the weapon selection image here.

Example:

![Available Weapons](images/weapons.jpg)

-->

> The image above shows all currently available weapons.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-knives"></a>

## Knives & Utilities

<!-- Insert the knives and utilities image here.

Example:

![Knives and Utilities](images/knives-utilities.jpg)

-->

> The image above shows all currently available knife and utility replacements.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-presets"></a>

## Preset Configurations

Preset configurations **do not include map/room selection or knife selection**.

The map includes four default presets:

| Preset | Weapon / Mode | Reload | Bots | Spawn Peek |
| --- | --- | --- | ---: | --- |
| Config 1 | Deagle Pistol Mode | Required | 3 | Off |
| Config 2 | AK-47 | Required | 4 | Off |
| Config 3 | AK-47 | Required | 3 | On |
| Config 4 | AWP | Not Required | 4 | On |

### Saving Custom Presets

After adjusting your current settings, use one of the following console commands to overwrite the corresponding preset:

```text
aimrush_save_config 1
aimrush_save_config 2
aimrush_save_config 3
aimrush_save_config 4
```

For example:

```text
aimrush_save_config 2
```

This saves your current configuration to **Config 2**.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-bots"></a>

## Bot Logic

The map currently provides **Bot Original** and **three Enhanced Bot modes**.

### Bot Original

**Bot Original** uses the original Aim Rush Bot logic and relies directly on the highest-difficulty Bots available in CS2.

Because some navigation issues appeared during the map decompilation process, Original Bots may occasionally show unusual movement behavior.

Possible issues include:

- Unusual movement paths
- Strange movement behavior
- Navigation problems in certain areas

---

### Enhanced Bot

The map includes **three Enhanced Bot modes**.

All three Enhanced Bot modes use external scripts.

Current shared settings:

- **Reaction time:** `0.35s`
- **Target awareness:** Full-map awareness by default
- **Core behavior logic:** The same across all three modes
- **Main differences:** Attack-related parameters

The three Enhanced Bot modes therefore use the same basic behavior logic, while different attack parameters are used to create different difficulty levels.

[Back to Table of Contents](#table-of-contents)

---

<a id="en-utility-reactions"></a>

## Enhanced Bot Utility Reactions

| Utility | Bot Behavior |
| --- | --- |
| **Flashbang** | Bots lose their current attack target. After the flash effect ends and the target is reacquired, they may continue firing short bursts in the direction they are currently facing. |
| **Molotov / Incendiary Grenade** | Bots detect nearby fire and perform limited avoidance behavior. However, shooting and other attack actions have higher priority than avoiding fire. |
| **Smoke Grenade** | Bots treat smoke as cover / visual obstruction. |
| **HE Grenade** | No special reaction is currently implemented. |

[Back to Table of Contents](#table-of-contents)

---

<a id="en-credits"></a>

## Credits

Special thanks to **JoeyyBiden** for creating **Aim Rush**, an excellent warm-up and aim training map.

The Bot logic modifications in this project were heavily inspired by the open-source project **CS2-Bot-Improver**.

Special thanks to its developer and contributors.

- **CS2-Bot-Improver:**  
  https://github.com/ed0ard/CS2-Bot-Improver

[Back to Table of Contents](#table-of-contents)

---

<a id="en-links"></a>

## Related Links

- **Aim Rush - Community Modified Version**  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3779660631

- **CS2-Bot-Improver**  
  https://github.com/ed0ard/CS2-Bot-Improver

[Back to Table of Contents](#table-of-contents)

---

# 中文

<a id="zh-overview"></a>

## 项目概览

本项目是基于 **JoeyyBiden** 制作的经典地图 **Aim Rush** 修改而来的 CS2 创意工坊地图。

修改版在原地图基础上增加了更多枪械、匕首、道具、预设配置、Bot 行为选项，同时修复并优化了部分影响游戏体验的问题。

[返回目录](#table-of-contents)

---

<a id="zh-usage"></a>

## 使用方法

在 CS2 创意工坊搜索：

**Aim Rush - Community Modified Version**

订阅地图并启动国际服 CS2，即可在创意工坊地图中使用。

- **Steam 创意工坊页面：**  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3779660631

- **创意工坊 ID：**  
  `3779660631`

[返回目录](#table-of-contents)

---

<a id="zh-version"></a>

## 版本提示

打开地图时，游戏内的文本提示区域会显示当前版本号。

> [!IMPORTANT]
> 如果显示的版本低于 **v2.2.0**，或没有出现版本提示，请更新地图以获得最佳体验。

### 强制更新地图的方法

Steam 创意工坊有时不会自动更新地图。

如果地图没有更新：

1. 取消订阅本地图。
2. 重新订阅。
3. 如果此时 CS2 触发创意工坊文件下载，则说明地图更新已经触发。
4. 再次进入地图并检查版本号。

[返回目录](#table-of-contents)

---

<a id="zh-controls"></a>

## 基本使用说明

- 所有可互动物品均可以通过 **交互键** 使用。
- 大部分可互动物品也可以通过 **造成伤害** 来触发。

[返回目录](#table-of-contents)

---

<a id="zh-weapons"></a>

## 枪械选择

<!-- 在这里插入枪械区域截图。

例如：

![全部可用枪械](images/weapons.jpg)

-->

> 上图为当前版本全部可用枪械。

[返回目录](#table-of-contents)

---

<a id="zh-knives"></a>

## 匕首与道具

<!-- 在这里插入匕首与道具区域截图。

例如：

![全部匕首与道具](images/knives-utilities.jpg)

-->

> 上图为当前版本全部可替换的匕首和道具。

[返回目录](#table-of-contents)

---

<a id="zh-presets"></a>

## 预设配置

预设配置**不包括地图区域和匕首的选择**。

地图默认自带 4 种预设：

| 预设 | 武器 / 模式 | 换弹 | Bot 数量 | Spawn Peek |
| --- | --- | --- | ---: | --- |
| 配置 1 | Deagle 手枪模式 | 需换弹 | 3 | 关 |
| 配置 2 | AK-47 | 需换弹 | 4 | 关 |
| 配置 3 | AK-47 | 需换弹 | 3 | 开 |
| 配置 4 | AWP | 无需换弹 | 4 | 开 |

### 保存自定义预设

调整好当前配置后，可以使用以下控制台命令，将当前配置保存到对应预设槽位：

```text
aimrush_save_config 1
aimrush_save_config 2
aimrush_save_config 3
aimrush_save_config 4
```

例如：

```text
aimrush_save_config 2
```

会将当前配置保存为 **配置 2**。

[返回目录](#table-of-contents)

---

<a id="zh-bots"></a>

## Bot 逻辑说明

目前地图提供 **Bot Original** 和 **3 种 Enhanced Bot**。

### Bot Original

**Bot Original** 使用原版 Aim Rush 的 Bot 逻辑，直接使用游戏内部最高难度 Bot。

由于地图反编译过程中出现了一些导航问题，目前 Original Bot 在部分区域可能存在一些异常运动行为。

例如：

- 移动路线异常
- 运动行为不自然
- 个别区域出现导航问题

---

### Enhanced Bot

地图目前提供 **3 种 Enhanced Bot 模式**。

3 种 Enhanced Bot 均使用外部脚本。

当前统一设定：

- **反应时间：** `0.35s`
- **目标感知：** 默认全图透视
- **主要行为逻辑：** 三种模式相同
- **主要区别：** 攻击相关参数不同

因此，三种 Enhanced Bot 本质上使用相同的行为逻辑，仅通过调整不同的攻击参数来形成不同难度。

[返回目录](#table-of-contents)

---

<a id="zh-utility-reactions"></a>

## Enhanced Bot 对道具的反应

| 道具 | Bot 行为 |
| --- | --- |
| **闪光弹** | Bot 会丢失当前攻击目标。闪光效果结束并重新找到目标后，可能会继续向当前正对方向进行点射。 |
| **燃烧瓶 / 燃烧弹** | Bot 会检测附近火焰，并执行一定程度的躲避行为。但开枪等攻击行为的优先级高于躲避。 |
| **烟雾弹** | Bot 会将烟雾视为掩体 / 视野遮挡。 |
| **HE 手雷** | 目前没有特殊反应。 |

[返回目录](#table-of-contents)

---

<a id="zh-credits"></a>

## 致谢

感谢 **JoeyyBiden** 创作了 **Aim Rush**，这是一张非常优秀的热身与练枪地图。

本修改版的 Bot 逻辑修改大量参考了开源项目 **CS2-Bot-Improver**，在此特别感谢该项目的开发者与贡献者。

- **CS2-Bot-Improver：**  
  https://github.com/ed0ard/CS2-Bot-Improver

[返回目录](#table-of-contents)

---

<a id="zh-links"></a>

## 相关链接

- **Aim Rush - Community Modified Version**  
  https://steamcommunity.com/sharedfiles/filedetails/?id=3779660631

- **CS2-Bot-Improver**  
  https://github.com/ed0ard/CS2-Bot-Improver

[返回目录](#table-of-contents)
