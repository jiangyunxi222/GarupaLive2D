# 羽泽鸫（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服·打工2023 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 常服·睡衣2023 | `010_costume.model.json` |
| 校服·臂章 | `011_costume.model.json` |
| 校服·夏季 | `012_costume.model.json` |
| 校服·夏季2023 | `013_costume.model.json` |
| 校服·夏季S2 | `014_costume.model.json` |
| 校服·夏季V3 | `015_costume.model.json` |
| 校服·冬季 | `016_costume.model.json` |
| 校服·冬季2023 | `017_costume.model.json` |
| 校服·冬季S2 | `018_costume.model.json` |
| 演出服·流星雨（R） | `019_costume.model.json` |
| 演出服·来组个乐队吧！（SR） | `020_costume.model.json` |
| 演出服·温暖的心情（R） | `021_costume.model.json` |
| 演出服·勇者鸫鸫（R） | `022_costume.model.json` |
| 演出服·学生会的工作（SR） | `023_costume.model.json` |
| 演出服·甜点老师（SSR） | `024_costume.model.json` |
| 演出服·仰望夜空（R） | `025_costume.model.json` |
| 演出服·开心的试吃会（SR） | `026_costume.model.json` |
| 演出服·重要的遗失物品（R） | `027_costume.model.json` |
| 演出服·心跳加速的发展！？（SSR） | `028_costume.model.json` |
| 演出服·Barista（SR） | `029_costume.model.json` |
| 演出服·察觉到的『变化』（SR） | `030_costume.model.json` |
| 演出服·大家一起开派对（SSR） | `031_costume.model.json` |
| 演出服·12月的天文观测（SR） | `032_costume.model.json` |
| 演出服·因缘的……猫咪？（SR） | `033_costume.model.json` |
| 演出服·将心意隐藏在糖果中（R） | `034_costume.model.json` |
| 演出服·副会长非常忙碌！（SSR） | `035_costume.model.json` |
| 演出服·腼腆的捧花女孩（SR） | `036_costume.model.json` |
| 演出服·进步（SR） | `037_costume.model.json` |
| 演出服·幸福的下午茶时间（R） | `038_costume.model.json` |
| 演出服·听我说，日菜学姐（SSR） | `039_costume.model.json` |
| 演出服·传达的心意（R） | `040_costume.model.json` |
| 演出服·帮忙回礼（SSR） | `041_costume.model.json` |
| 演出服·朝着同一片天空迈进（SSR） | `042_costume.model.json` |
| 演出服·水花飞溅（SSR） | `043_costume.model.json` |
| 演出服·不想放弃（SR） | `044_costume.model.json` |
| 演出服·忍不住炫耀青梅竹马（SSR） | `045_costume.model.json` |
| 演出服·坦率的真心话！（R） | `046_costume.model.json` |
| 演出服·苍穹的大鹏鸟（SR） | `047_costume.model.json` |
| 演出服·微小的『能做到』的事（SSR） | `048_costume.model.json` |
| 演出服·手忙脚乱的旅行（SR） | `049_costume.model.json` |
| 演出服·朝着最棒迈进！（SR） | `050_costume.model.json` |
| 演出服·予你洁白之花（SSR） | `051_costume.model.json` |
| 演出服·全心全意地营业中（SR） | `052_costume.model.json` |
| 演出服·花，在心中点亮（SSR） | `053_costume.model.json` |
| 演出服·即便雨不停歇（SSR） | `054_costume.model.json` |
| 演出服·旋转咖啡时光（SR） | `055_costume.model.json` |
| 演出服·激励的夕阳（SSR） | `056_costume.model.json` |
| 演出服·想要帮忙（SSR） | `057_costume.model.json` |
| 演出服·将『没问题』当作护身符（UR） | `058_costume.model.json` |
| 演出服·闪耀的羽丘学生会会长（UR） | `059_costume.model.json` |
| 演出服·二人的想法（SR） | `060_costume.model.json` |
| 演出服·再次朝着顶点进发（SR） | `061_costume.model.json` |
| 演出服·追上来的背影（UR） | `062_costume.model.json` |
| 演出服·休憩的大海（SR） | `063_costume.model.json` |
| 演出服·能对你昂首挺胸的我（SSR） | `064_costume.model.json` |
| 演出服·Queen of ♡（R） | `065_costume.model.json` |
| 演出服·身为帅气的前辈（UR） | `066_costume.model.json` |
| 演出服·快乐的糖葫芦（SR） | `067_costume.model.json` |
| 演出服·用我的话语（UR） | `068_costume.model.json` |
| 演出服·为你全速前进（UR） | `069_costume.model.json` |
| 演出服·青春街头少女（R） | `070_costume.model.json` |
| 演出服·晚霞染红脸颊（UR） | `071_costume.model.json` |
| 演出服·清爽海洋风（R） | `072_costume.model.json` |
| 演出服·最初的一步是（SSR） | `073_costume.model.json` |
| 演出服·暮色糖果派对（R） | `074_costume.model.json` |
| 演出服·全世界的鸫式努力（SR） | `075_costume.model.json` |
| 演出服·Grow Up Rock | `076_costume.model.json` |
| 演出服·疾驰之空 | `077_costume.model.json` |
| 演出服·绯红之魂 | `078_costume.model.json` |
| 演出服·激情四溢的青春 | `079_costume.model.json` |
| 演出服·Get up！ | `080_costume.model.json` |
| 演出服·万事开头难 | `081_costume.model.json` |
| 活动·第2回总选举（R） | `082_costume.model.json` |
| 活动·梦想祭·安心之处 | `083_costume.model.json` |
| 活动·梦想祭·晚霞渐淡 | `084_costume.model.json` |
| 活动·梦想祭·干练的羽丘学生会（UR） | `085_costume.model.json` |
| 活动·梦想祭·两人，彼此分享（UR） | `086_costume.model.json` |
| 活动·闪耀祭·午后咖啡 | `087_costume.model.json` |
| 活动·5周年特别服 | `088_costume.model.json` |
| 剧情·活动06剧情 | `089_costume.model.json` |
| 剧情·活动49剧情01 | `090_costume.model.json` |
| 剧情·活动54剧情01 | `091_costume.model.json` |
| 剧情·活动80剧情01 | `092_costume.model.json` |
| 剧情·活动119剧情01 | `093_costume.model.json` |
| 剧情·活动122剧情01 | `094_costume.model.json` |
| 剧情·活动128剧情01 | `095_costume.model.json` |
| 剧情·活动216剧情01 | `096_costume.model.json` |
| 剧情·活动344剧情01 | `097_costume.model.json` |
| 剧情·中学纪念 | `098_costume.model.json` |
| 剧情·剧情01 | `099_costume.model.json` |
| 季节·2018狗年 | `100_costume.model.json` |
| 季节·2019振袖 | `101_costume.model.json` |
| 季节·夏日水手服 | `102_costume.model.json` |
| 季节·泳装2023 | `103_costume.model.json` |
| 生日·2021 | `104_costume.model.json` |
| 生日·2022 | `105_costume.model.json` |
| 联动·初音未来·Lost one的号哭 | `106_costume.model.json` |
| 其他·2021愚人节 | `107_costume.model.json` |
| 其他·Garupa T恤 | `108_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。

## 统一点击规则

| 点击区域 | 触发效果 |
|---|---|
| 表情区域 | 随机切换表情，不展开菜单 |
| 语音区域 | 只播放语音，不展开菜单 |
| 正面动作区域 | 播放普通动作，不展开菜单 |
| 左手 / 右手区域 | 优先播放对应方向动作，不展开菜单 |
| 换装区域 | 打开换装菜单 |
| 菜单区域 | 打开主菜单 |

缺少左右方向动作时回退到普通动作；没有动作素材时保持待机，不回退到菜单。没有语音或表情素材时也不弹出菜单。

重叠区域统一按「表情 → 语音 → 手部动作 → 正面动作 → 换装 → 菜单」处理，同一网格只保留一个有效触发。各衣装沿用自身网格，网格编号及形状不作修改。未命中专用区域时，仍可通过默认点击打开主菜单。

更新后请完整重载 `00_integrated` 主入口。
