# 北泽育美（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 新版菜单

主菜单提供「动作」「表情」「换装」「声音与控制」「关闭菜单」。换装及各级列表均可直接返回主菜单。

- 点击身体上的语音区域只播放语音，不展开主菜单或播放控制菜单；再次点击可以切换语音。
- 从菜单中主动选择语音时，仍显示字幕、重播、停止和返回按钮。
- 表情保持至下一次选择，使用「清除表情」恢复。
- 新动作或「停止并回到待机」可解除动作保持，操作菜单无需等待动画结束。
- 「声音与控制 → 恢复默认 / 解除保持」清除动作、表情及参数锁定；「关闭菜单」仅关闭操作框。

更新后请完整重载 `00_integrated` 主入口，确保旧实例中的控制器已卸载；仅切换衣装不会更新父模型。

## 衣装入口

| 衣装 | 内部配置 |
|---|---|
| 默认·舞台 | `001_costume.model.json` |
| 常服·咖啡厅 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·冬 | `007_costume.model.json` |
| 常服·冬2023 | `008_costume.model.json` |
| 常服·睡衣2023 | `009_costume.model.json` |
| 校服·体操服 | `010_costume.model.json` |
| 校服·体操服2023 | `011_costume.model.json` |
| 校服·夏季 | `012_costume.model.json` |
| 校服·夏季2023 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季2023 | `015_costume.model.json` |
| 校服·制服 | `016_costume.model.json` |
| 演出服·可爱的侦探（R） | `017_costume.model.json` |
| 演出服·精神的源泉（SR） | `018_costume.model.json` |
| 演出服·熊熊燃烧！（R） | `019_costume.model.json` |
| 演出服·认真决胜的笑容（SSR） | `020_costume.model.json` |
| 演出服·好多可爱的东西！（SR） | `021_costume.model.json` |
| 演出服·我来教你！（SSR） | `022_costume.model.json` |
| 演出服·被王子殿下治愈（SR） | `023_costume.model.json` |
| 演出服·玛丽·安德罗美亚（SSR） | `024_costume.model.json` |
| 演出服·两人的开始（SSR） | `025_costume.model.json` |
| 演出服·大冒险！（R） | `026_costume.model.json` |
| 演出服·盛夏的跳跃（SR） | `027_costume.model.json` |
| 演出服·为了笑容！（SR） | `028_costume.model.json` |
| 演出服·绯玛丽穿搭风格（SSR） | `029_costume.model.json` |
| 演出服·来了——！！（SR） | `030_costume.model.json` |
| 演出服·仅有少数人知道的近路？（SR） | `031_costume.model.json` |
| 演出服·花开般的笑容（SSR） | `032_costume.model.json` |
| 演出服·欢欣雀跃的烟花大会（SR） | `033_costume.model.json` |
| 演出服·蹦跳的兔子（R） | `034_costume.model.json` |
| 演出服·仰望秋日（SSR） | `035_costume.model.json` |
| 演出服·快乐的派对！（SSR） | `036_costume.model.json` |
| 演出服·碰一下，蹦♪（SR） | `037_costume.model.json` |
| 演出服·精神100倍！（SR） | `038_costume.model.json` |
| 演出服·4号，投手（SSR） | `039_costume.model.json` |
| 演出服·要找的东西！（SR） | `040_costume.model.json` |
| 演出服·夏天的快乐（R） | `041_costume.model.json` |
| 演出服·活力魔女（SSR） | `042_costume.model.json` |
| 演出服·新的朋友（SR） | `043_costume.model.json` |
| 演出服·可爱地嗷呜！（R） | `044_costume.model.json` |
| 演出服·里面不断发出声音（SSR） | `045_costume.model.json` |
| 演出服·Spooky Pop（R） | `046_costume.model.json` |
| 演出服·正在学习中！（SSR） | `047_costume.model.json` |
| 演出服·解开谜团之人（SR） | `048_costume.model.json` |
| 演出服·就像是米歇尔！（R） | `049_costume.model.json` |
| 演出服·大家一起来！（SSR） | `050_costume.model.json` |
| 演出服·Hello，乌托邦！ | `051_costume.model.json` |
| 演出服·往复百次，聚集福气（SSR） | `052_costume.model.json` |
| 演出服·笑容灿烂的国际交流（UR） | `053_costume.model.json` |
| 演出服·南国岛屿的大冒险（SSR） | `054_costume.model.json` |
| 演出服·杂技明星（UR） | `055_costume.model.json` |
| 演出服·刚出炉的笑容！（SSR） | `056_costume.model.json` |
| 演出服·快乐无极限（UR） | `057_costume.model.json` |
| 演出服·一碗拉面！（SR） | `058_costume.model.json` |
| 演出服·一起画画吧！（SR） | `059_costume.model.json` |
| 演出服·愉快的清洁！（SSR） | `060_costume.model.json` |
| 演出服·新年就要吃可乐饼！（SR） | `061_costume.model.json` |
| 演出服·星球舞台（R） | `062_costume.model.json` |
| 演出服·大大的爱心！（SR） | `063_costume.model.json` |
| 演出服·头脑风暴◎思考中（SSR） | `064_costume.model.json` |
| 演出服·偶尔也要优雅一下（R） | `065_costume.model.json` |
| 演出服·少女的呐喊划破盛夏（UR） | `066_costume.model.json` |
| 演出服·解开心灵的枷锁（UR） | `067_costume.model.json` |
| 演出服·好多点心！（SSR） | `068_costume.model.json` |
| 演出服·成为万事屋！（UR） | `069_costume.model.json` |
| 演出服·纯真徒步者（R） | `070_costume.model.json` |
| 演出服·心跳★惊喜（UR） | `071_costume.model.json` |
| 演出服·笑容的魔法 | `072_costume.model.json` |
| 演出服·Smile Seeker！ | `073_costume.model.json` |
| 演出服·微笑的行星 | `074_costume.model.json` |
| 演出服·来吧来吧，笑容游行 | `075_costume.model.json` |
| 演出服·笑容∞奇迹！ | `076_costume.model.json` |
| 演出服·大家一起来！ | `077_costume.model.json` |
| 活动·梦想祭·育美是代表！ | `078_costume.model.json` |
| 活动·梦想祭·育美是姐姐！ | `079_costume.model.json` |
| 活动·梦想祭·海岸边的灿烂笑容（UR） | `080_costume.model.json` |
| 活动·梦想祭·笑容满面的一大口！（UR） | `081_costume.model.json` |
| 活动·活动40 | `082_costume.model.json` |
| 活动·闪耀祭·花朵与笑容，轻柔地绽放 | `083_costume.model.json` |
| 活动·5周年特别服 | `084_costume.model.json` |
| 剧情·活动33剧情01 | `085_costume.model.json` |
| 剧情·活动48剧情01 | `086_costume.model.json` |
| 剧情·活动50剧情01 | `087_costume.model.json` |
| 剧情·活动67剧情01 | `088_costume.model.json` |
| 剧情·活动88剧情01 | `089_costume.model.json` |
| 剧情·活动110剧情01 | `090_costume.model.json` |
| 剧情·活动153剧情01 | `091_costume.model.json` |
| 剧情·活动216剧情01 | `092_costume.model.json` |
| 剧情·活动244剧情01 | `093_costume.model.json` |
| 剧情·活动316剧情01 | `094_costume.model.json` |
| 剧情·活动344剧情01 | `095_costume.model.json` |
| 剧情·Hello Happy战队面具 | `096_costume.model.json` |
| 季节·2018狗年 | `097_costume.model.json` |
| 季节·2019振袖 | `098_costume.model.json` |
| 季节·2025振袖 | `099_costume.model.json` |
| 季节·夏日水手服 | `100_costume.model.json` |
| 季节·泳装2023 | `101_costume.model.json` |
| 生日·2021 | `102_costume.model.json` |
| 生日·2022 | `103_costume.model.json` |
| 联动·白上吹雪（hololive） | `104_costume.model.json` |
| 联动·初音未来·Alien Alien | `105_costume.model.json` |
| 其他·Garupa T恤 | `106_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
