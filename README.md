# GarupaLive2D

整理后的 Live2DViewerEX 资源：47 个角色，3438 套衣装。

完整复制角色目录并导入 `00_integrated` 主入口。

## 新版菜单

主菜单提供「动作」「表情」「换装」「声音与控制」「关闭菜单」。换装及各级列表均可直接返回主菜单。

- 点击身体上的语音区域只播放语音，不展开主菜单或播放控制菜单；再次点击可以切换语音。
- 从菜单中主动选择语音时，仍显示字幕、重播、停止和返回按钮。
- 表情保持至下一次选择，使用「清除表情」恢复。
- 新动作或「停止并回到待机」可解除动作保持，操作菜单无需等待动画结束。
- 「声音与控制 → 恢复默认 / 解除保持」清除动作、表情及参数锁定；「关闭菜单」仅关闭操作框。

更新后请完整重载 `00_integrated` 主入口，确保旧实例中的控制器已卸载；仅切换衣装不会更新父模型。

## 角色索引

| 团体 | 角色 | 衣装数 | 整合入口 |
|---|---|---:|---|
| Afterglow | 上原绯玛丽 | 109 | [导入入口](<Afterglow/上原绯玛丽/00_integrated.model.json>) |
| Afterglow | 宇田川巴 | 113 | [导入入口](<Afterglow/宇田川巴/00_integrated.model.json>) |
| Afterglow | 美竹兰 | 111 | [导入入口](<Afterglow/美竹兰/00_integrated.model.json>) |
| Afterglow | 羽泽鸫 | 108 | [导入入口](<Afterglow/羽泽鸫/00_integrated.model.json>) |
| Afterglow | 青叶摩卡 | 104 | [导入入口](<Afterglow/青叶摩卡/00_integrated.model.json>) |
| Ave Mujica（Garupa） | 三角初华（Garupa） | 6 | [导入入口](<Ave Mujica（Garupa）/三角初华（Garupa）/00_integrated.model.json>) |
| Ave Mujica（Garupa） | 丰川祥子（Garupa） | 5 | [导入入口](<Ave Mujica（Garupa）/丰川祥子（Garupa）/00_integrated.model.json>) |
| Ave Mujica（Garupa） | 八幡海铃（Garupa） | 4 | [导入入口](<Ave Mujica（Garupa）/八幡海铃（Garupa）/00_integrated.model.json>) |
| Ave Mujica（Garupa） | 祐天寺若麦（Garupa） | 2 | [导入入口](<Ave Mujica（Garupa）/祐天寺若麦（Garupa）/00_integrated.model.json>) |
| Ave Mujica（Garupa） | 若叶睦（Garupa） | 4 | [导入入口](<Ave Mujica（Garupa）/若叶睦（Garupa）/00_integrated.model.json>) |
| Hello, Happy World! | 北泽育美 | 106 | [导入入口](<Hello, Happy World!/北泽育美/00_integrated.model.json>) |
| Hello, Happy World! | 奥泽美咲 | 120 | [导入入口](<Hello, Happy World!/奥泽美咲/00_integrated.model.json>) |
| Hello, Happy World! | 弦卷心 | 115 | [导入入口](<Hello, Happy World!/弦卷心/00_integrated.model.json>) |
| Hello, Happy World! | 松原花音 | 105 | [导入入口](<Hello, Happy World!/松原花音/00_integrated.model.json>) |
| Hello, Happy World! | 濑田薰 | 112 | [导入入口](<Hello, Happy World!/濑田薰/00_integrated.model.json>) |
| Morfonica | 二叶筑紫 | 63 | [导入入口](<Morfonica/二叶筑紫/00_integrated.model.json>) |
| Morfonica | 仓田真白 | 73 | [导入入口](<Morfonica/仓田真白/00_integrated.model.json>) |
| Morfonica | 八潮瑠唯 | 60 | [导入入口](<Morfonica/八潮瑠唯/00_integrated.model.json>) |
| Morfonica | 广町七深 | 64 | [导入入口](<Morfonica/广町七深/00_integrated.model.json>) |
| Morfonica | 桐谷透子 | 65 | [导入入口](<Morfonica/桐谷透子/00_integrated.model.json>) |
| MyGO!!!!!（Garupa） | 千早爱音（Garupa） | 17 | [导入入口](<MyGO!!!!!（Garupa）/千早爱音（Garupa）/00_integrated.model.json>) |
| MyGO!!!!!（Garupa） | 椎名立希（Garupa） | 18 | [导入入口](<MyGO!!!!!（Garupa）/椎名立希（Garupa）/00_integrated.model.json>) |
| MyGO!!!!!（Garupa） | 要乐奈（Garupa） | 16 | [导入入口](<MyGO!!!!!（Garupa）/要乐奈（Garupa）/00_integrated.model.json>) |
| MyGO!!!!!（Garupa） | 长崎素世（Garupa） | 15 | [导入入口](<MyGO!!!!!（Garupa）/长崎素世（Garupa）/00_integrated.model.json>) |
| MyGO!!!!!（Garupa） | 高松灯（Garupa） | 18 | [导入入口](<MyGO!!!!!（Garupa）/高松灯（Garupa）/00_integrated.model.json>) |
| Pastel＊Palettes | 丸山彩 | 120 | [导入入口](<Pastel＊Palettes/丸山彩/00_integrated.model.json>) |
| Pastel＊Palettes | 冰川日菜 | 112 | [导入入口](<Pastel＊Palettes/冰川日菜/00_integrated.model.json>) |
| Pastel＊Palettes | 大和麻弥 | 103 | [导入入口](<Pastel＊Palettes/大和麻弥/00_integrated.model.json>) |
| Pastel＊Palettes | 白鹭千圣 | 104 | [导入入口](<Pastel＊Palettes/白鹭千圣/00_integrated.model.json>) |
| Pastel＊Palettes | 若宫伊芙 | 110 | [导入入口](<Pastel＊Palettes/若宫伊芙/00_integrated.model.json>) |
| Poppin'Party | 山吹沙绫 | 102 | [导入入口](<Poppin'Party/山吹沙绫/00_integrated.model.json>) |
| Poppin'Party | 市谷有咲 | 114 | [导入入口](<Poppin'Party/市谷有咲/00_integrated.model.json>) |
| Poppin'Party | 户山香澄 | 121 | [导入入口](<Poppin'Party/户山香澄/00_integrated.model.json>) |
| Poppin'Party | 牛込里美 | 101 | [导入入口](<Poppin'Party/牛込里美/00_integrated.model.json>) |
| Poppin'Party | 花园多惠 | 104 | [导入入口](<Poppin'Party/花园多惠/00_integrated.model.json>) |
| RAISE A SUILEN | 佐藤益木（MASKING） | 53 | [导入入口](<RAISE A SUILEN/佐藤益木（MASKING）/00_integrated.model.json>) |
| RAISE A SUILEN | 和奏瑞依（LAYER） | 54 | [导入入口](<RAISE A SUILEN/和奏瑞依（LAYER）/00_integrated.model.json>) |
| RAISE A SUILEN | 朝日六花（LOCK） | 63 | [导入入口](<RAISE A SUILEN/朝日六花（LOCK）/00_integrated.model.json>) |
| RAISE A SUILEN | 珠手知由（CHU²） | 52 | [导入入口](<RAISE A SUILEN/珠手知由（CHU²）/00_integrated.model.json>) |
| RAISE A SUILEN | 鳰原令王那（PAREO） | 50 | [导入入口](<RAISE A SUILEN/鳰原令王那（PAREO）/00_integrated.model.json>) |
| Roselia | 今井莉莎 | 108 | [导入入口](<Roselia/今井莉莎/00_integrated.model.json>) |
| Roselia | 冰川纱夜 | 105 | [导入入口](<Roselia/冰川纱夜/00_integrated.model.json>) |
| Roselia | 凑友希那 | 105 | [导入入口](<Roselia/凑友希那/00_integrated.model.json>) |
| Roselia | 宇田川亚子 | 108 | [导入入口](<Roselia/宇田川亚子/00_integrated.model.json>) |
| Roselia | 白金燐子 | 103 | [导入入口](<Roselia/白金燐子/00_integrated.model.json>) |
| 其他角色 | 户山明日香 | 12 | [导入入口](<其他角色/户山明日香/00_integrated.model.json>) |
| 其他角色 | 纯田真奈（Garupa） | 1 | [导入入口](<其他角色/纯田真奈（Garupa）/00_integrated.model.json>) |

模型 ID 独立，换装由固定父模型管理。仅提交处理后的模型配置、运行资源、清单和必要说明，不包含原始 LPK、备份及处理工具。

配置与资源引用已校验；样本做过官方接口冒烟检查，完整鼠标点击实测尚未完成。素材权利归原权利人。
