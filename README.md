# Granblue Fantasy Relink Simplified Chinese Community

以简中 [wiki](https://gbf.huijiwiki.com/) 为标准，对部分非约定俗成的译名进行了修改，旨在使角色名和术语更符合 [Granblue Fantasy](https://game.granbluefantasy.jp) 本家玩家 ~~(以及我自己)~~ 的习惯

## 效果预览

![角色](/assets/preview-chara.png)
![因子](/assets/preview-geen.png)

## 变更对照

### 角色名

| 官方版       | wiki 版      |
| ------------ | ------------ |
| 巴恩         | 维恩         |
| 珀西瓦尔     | 帕西瓦尔     |
| 娜露梅       | 娜尔梅亚     |
| 塞达         | 泽塔         |
| 卡莉奥丝特罗 | 卡莉奥斯特萝 |

### 因子

| 官方版 | wiki 版 |
| ------ | ------- |
| 热血   | 浑身    |
| 豪胆   | 根性    |
| 激昂   | 高扬    |

### 状态效果

| 官方版 | wiki 版  |
| ------ | -------- |
| 豪胆   | 即死回避 |

### 特殊行动

| 官方版       | wiki 版      |
| ------------ | ------------ |
| 凌驾法则     | 理之超越     |
| 永恒拒绝之剑 | 永远拒绝之剑 |

### 道具

| 官方版   | wiki 版    |
| -------- | ---------- |
| 终焉暗晶 | 终末之暗晶 |

## 使用方法

### Relink Mod Organizer

1. 请参照我的 [Relink Mod Organizer](https://github.com/RokyZevon/RelinkModOrganizer) 的 [中文说明](https://github.com/RokyZevon/RelinkModOrganizer/blob/master/README_zh.md)

### Reloaded II

1. 请参照 [Relink Modding Site](https://nenkai.github.io/relink-modding/getting_started/mod_manager/)

### 手动 (不推荐, 与其他 mod 不兼容)

0. 从 [Github Releases](https://github.com/RokyZevon/gbfr-sc-community/releases) 或 [Nexus](https://www.nexusmods.com/granbluefantasyrelink/mods/18?tab=files) 下载最新的 zip 文件并解压, 也可直接使用源码里的 mod 文件夹
1. 备份游戏根目录下的 `data.i` 文件 (虽然理论上没关系，但保险起见最好也备份下存档)
2. 将 `mod` 文件夹下的内容拷贝至游戏根目录

## 还原方法

1. 删除游戏根目录下的 `/data/system/` 文件夹
2. 将备份的 `data.i` 文件覆盖至游戏根目录 (若确实丢失, 可以试试 Steam 的验证游戏文件完整性)

## 致谢

- [GBFRDataTools](https://github.com/Nenkai/GBFRDataTools)

## 其它

- msg / json 之间的转换使用的是 [MsgPacker](https://github.com/RokyZevon/MsgPacker)
