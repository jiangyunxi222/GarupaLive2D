# 今井莉莎（Garupa）

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
| 常服 | `002_costume.model.json` |
| 常服·2023 | `003_costume.model.json` |
| 常服·夏 | `004_costume.model.json` |
| 常服·夏2023 | `005_costume.model.json` |
| 常服·冬 | `006_costume.model.json` |
| 常服·冬2023 | `007_costume.model.json` |
| 常服·商店 | `008_costume.model.json` |
| 常服·商店2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季S2 | `011_costume.model.json` |
| 校服·夏季V3 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季S2 | `014_costume.model.json` |
| 演出服·守望思念（R） | `015_costume.model.json` |
| 演出服·不可或缺的存在（SR） | `016_costume.model.json` |
| 演出服·情牵两人（R） | `017_costume.model.json` |
| 演出服·耀眼的艳阳（SSR） | `018_costume.model.json` |
| 演出服·罗曼蒂克（R） | `019_costume.model.json` |
| 演出服·不可缺少的存在（R） | `020_costume.model.json` |
| 演出服·认真地挑战（SSR） | `021_costume.model.json` |
| 演出服·新手治疗术士（SR） | `022_costume.model.json` |
| 演出服·甜点制作交给我吧（SSR） | `023_costume.model.json` |
| 演出服·再度制作饼干（SSR） | `024_costume.model.json` |
| 演出服·幽灵什么的绝对不行！（SR） | `025_costume.model.json` |
| 演出服·盛夏的日光（SR） | `026_costume.model.json` |
| 演出服·交流能力MAX（SSR） | `027_costume.model.json` |
| 演出服·挑战书（SR） | `028_costume.model.json` |
| 演出服·星光闪烁（R） | `029_costume.model.json` |
| 演出服·担心过头？（R） | `030_costume.model.json` |
| 演出服·勉强赶上的赏花（SR） | `031_costume.model.json` |
| 演出服·起始的演奏会（SSR） | `032_costume.model.json` |
| 演出服·看不见，但是没关系（SR） | `033_costume.model.json` |
| 演出服·缩短的距离（SSR） | `034_costume.model.json` |
| 演出服·幻想万岁！（SR） | `035_costume.model.json` |
| 演出服·笑容绽放（SSR） | `036_costume.model.json` |
| 演出服·必然的联系（SR） | `037_costume.model.json` |
| 演出服·沐浴在欢呼声中（SSR） | `038_costume.model.json` |
| 演出服·有线索了？（SR） | `039_costume.model.json` |
| 演出服·感受异世界风情（SSR） | `040_costume.model.json` |
| 演出服·乐于照顾人的公主（R） | `041_costume.model.json` |
| 演出服·STOP！（SR） | `042_costume.model.json` |
| 演出服·试探的目光（SR） | `043_costume.model.json` |
| 演出服·蔓延的恐惧之环（SSR） | `044_costume.model.json` |
| 演出服·这就是命运！（SSR） | `045_costume.model.json` |
| 演出服·我可以相信吗？（SR） | `046_costume.model.json` |
| 演出服·被充满期待的眼眸注视（SSR） | `047_costume.model.json` |
| 演出服·触碰动摇的心情（SR） | `048_costume.model.json` |
| 演出服·温柔的坏心眼（SR） | `049_costume.model.json` |
| 演出服·璀璨的前奏（SSR） | `050_costume.model.json` |
| 演出服·海风中描绘的心意（SR） | `051_costume.model.json` |
| 演出服·优雅的玫红 | `052_costume.model.json` |
| 演出服·Say cheese！（SSR） | `053_costume.model.json` |
| 演出服·观众的声音和表情 | `054_costume.model.json` |
| 演出服·这首曲子结束之后（SR） | `055_costume.model.json` |
| 演出服·毕业（SSR） | `056_costume.model.json` |
| 演出服·彻底地调查？（SSR） | `057_costume.model.json` |
| 演出服·夏日飞溅！（UR） | `058_costume.model.json` |
| 演出服·找不到的答案（SR） | `059_costume.model.json` |
| 演出服·阳春时节的闪亮盛装（UR） | `060_costume.model.json` |
| 演出服·远去的背影（UR） | `061_costume.model.json` |
| 演出服·在你身旁编织花朵（UR） | `062_costume.model.json` |
| 演出服·编织秋意（R） | `063_costume.model.json` |
| 演出服·水流声中洒落的笑容（UR） | `064_costume.model.json` |
| 演出服·『别担心』之类的话（SR） | `065_costume.model.json` |
| 演出服·欣喜的评价（SR） | `066_costume.model.json` |
| 演出服·花与星闪耀之地（SSR） | `067_costume.model.json` |
| 演出服·豪华阵容（SR） | `068_costume.model.json` |
| 演出服·一起来装饰吧！（UR） | `069_costume.model.json` |
| 演出服·DEAR MY LIKE（UR） | `070_costume.model.json` |
| 演出服·约定之地（SSR） | `071_costume.model.json` |
| 演出服·她所选择的未来（UR） | `072_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `073_costume.model.json` |
| 演出服·Noble・Rose | `074_costume.model.json` |
| 演出服·崇高志向 | `075_costume.model.json` |
| 演出服·环伊甸园 | `076_costume.model.json` |
| 演出服·神秘花束 | `077_costume.model.json` |
| 演出服·努力的痕迹 | `078_costume.model.json` |
| 活动·第2回总选举（R） | `079_costume.model.json` |
| 活动·第3回总选举（R） | `080_costume.model.json` |
| 活动·梦想祭·团结一心 | `081_costume.model.json` |
| 活动·梦想祭·今后也要一起 | `082_costume.model.json` |
| 活动·梦想祭·不再穿制服的早晨（UR） | `083_costume.model.json` |
| 活动·梦想祭·樱影中摇曳的光（UR） | `084_costume.model.json` |
| 活动·奇幻冒险 | `085_costume.model.json` |
| 活动·5周年特别服 | `086_costume.model.json` |
| 剧情·活动52剧情01 | `087_costume.model.json` |
| 剧情·活动81剧情01 | `088_costume.model.json` |
| 剧情·活动89剧情01 | `089_costume.model.json` |
| 剧情·活动93剧情01 | `090_costume.model.json` |
| 剧情·活动105剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动128剧情01 | `093_costume.model.json` |
| 剧情·活动156剧情01 | `094_costume.model.json` |
| 剧情·活动216剧情01 | `095_costume.model.json` |
| 剧情·活动216剧情02 | `096_costume.model.json` |
| 季节·2018狗年 | `097_costume.model.json` |
| 季节·2019振袖 | `098_costume.model.json` |
| 季节·2024振袖 | `099_costume.model.json` |
| 季节·夏日水手服 | `100_costume.model.json` |
| 季节·泳装 | `101_costume.model.json` |
| 季节·泳装2023 | `102_costume.model.json` |
| 生日·2021 | `103_costume.model.json` |
| 生日·2022 | `104_costume.model.json` |
| 联动·炒作热度的专家（UR） | `105_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `106_costume.model.json` |
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
