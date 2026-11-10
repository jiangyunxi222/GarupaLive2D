# 白金燐子（Garupa）

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
| 校服·夏季 | `008_costume.model.json` |
| 校服·冬季 | `009_costume.model.json` |
| 校服·冬季V3 | `010_costume.model.json` |
| 演出服·纯粹的热情（SSR） | `011_costume.model.json` |
| 演出服·不习惯的电话（SSR） | `012_costume.model.json` |
| 演出服·大家挑选的泳衣（SR） | `013_costume.model.json` |
| 演出服·些许的担忧（R） | `014_costume.model.json` |
| 演出服·Blue Rose Maid（R） | `015_costume.model.json` |
| 演出服·可爱的盛装（SR） | `016_costume.model.json` |
| 演出服·孤高的巫师（SSR） | `017_costume.model.json` |
| 演出服·临时社团成员（SSR） | `018_costume.model.json` |
| 演出服·下定决心的呼声（SR） | `019_costume.model.json` |
| 演出服·河滨的人鱼（R） | `020_costume.model.json` |
| 演出服·舞台服装（SSR） | `021_costume.model.json` |
| 演出服·隐秘的斗志（R） | `022_costume.model.json` |
| 演出服·甜蜜的目光（SR） | `023_costume.model.json` |
| 演出服·我与钢琴（SSR） | `024_costume.model.json` |
| 演出服·向着出色的学生会长（SSR） | `025_costume.model.json` |
| 演出服·优雅的调查（SR） | `026_costume.model.json` |
| 演出服·藏在内心深处的热情（R） | `027_costume.model.json` |
| 演出服·终将来临的未来（SSR） | `028_costume.model.json` |
| 演出服·抓住的荣光（SSR） | `029_costume.model.json` |
| 演出服·抵达的目的地（SR） | `030_costume.model.json` |
| 演出服·我来弹奏一曲吧？（R） | `031_costume.model.json` |
| 演出服·咏唱于战场的新娘（SSR） | `032_costume.model.json` |
| 演出服·传达的音色（SSR） | `033_costume.model.json` |
| 演出服·音调印象（SR） | `034_costume.model.json` |
| 演出服·慌张少女（SR） | `035_costume.model.json` |
| 演出服·属于自己的答案（SSR） | `036_costume.model.json` |
| 演出服·置身于新世界（SR） | `037_costume.model.json` |
| 演出服·参加派对的邀请（R） | `038_costume.model.json` |
| 演出服·坚持战斗的学生会长（SSR） | `039_costume.model.json` |
| 演出服·涂抹心意（SSR） | `040_costume.model.json` |
| 演出服·未曾体会的欢喜（SR） | `041_costume.model.json` |
| 演出服·享受旅行（R） | `042_costume.model.json` |
| 演出服·拥抱那音色（SSR） | `043_costume.model.json` |
| 演出服·令人平静的归途（SR） | `044_costume.model.json` |
| 演出服·即使无法重演（SSR） | `045_costume.model.json` |
| 演出服·收下我的声援（SR） | `046_costume.model.json` |
| 演出服·开始『今天』的声音 | `047_costume.model.json` |
| 演出服·毕业（SSR） | `048_costume.model.json` |
| 演出服·身上穿的是……（UR） | `049_costume.model.json` |
| 演出服·流星新娘（R） | `050_costume.model.json` |
| 演出服·海风与太阳（UR） | `051_costume.model.json` |
| 演出服·午夜礼服（R） | `052_costume.model.json` |
| 演出服·两个人制作的友情巧克力（SR） | `053_costume.model.json` |
| 演出服·即使1cm也要前进（UR） | `054_costume.model.json` |
| 演出服·即便只是谈心（SSR） | `055_costume.model.json` |
| 演出服·染上绯红（SR） | `056_costume.model.json` |
| 演出服·原原本本的魅力（UR） | `057_costume.model.json` |
| 演出服·被深红色所渲染（R） | `058_costume.model.json` |
| 演出服·我的世界第一（UR） | `059_costume.model.json` |
| 演出服·暮色中的誓言（SSR） | `060_costume.model.json` |
| 演出服·红宝石熠熠生辉（UR） | `061_costume.model.json` |
| 演出服·一心向前（UR） | `062_costume.model.json` |
| 演出服·Blanc Resonance（R） | `063_costume.model.json` |
| 演出服·纯洁高贵（R） | `064_costume.model.json` |
| 演出服·True brillante（UR） | `065_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `066_costume.model.json` |
| 演出服·Noble・Rose | `067_costume.model.json` |
| 演出服·崇高志向 | `068_costume.model.json` |
| 演出服·环伊甸园 | `069_costume.model.json` |
| 演出服·神秘花束 | `070_costume.model.json` |
| 演出服·我该怎么办… | `071_costume.model.json` |
| 活动·第3回总选举（R） | `072_costume.model.json` |
| 活动·梦想祭·愉悦的旋律 | `073_costume.model.json` |
| 活动·梦想祭·旧书店巡礼 | `074_costume.model.json` |
| 活动·梦想祭·星夜中的野餐（UR） | `075_costume.model.json` |
| 活动·梦想祭·浅粉掩映的窗边（UR） | `076_costume.model.json` |
| 活动·奇幻冒险 | `077_costume.model.json` |
| 活动·5周年特别服 | `078_costume.model.json` |
| 剧情·活动38剧情01 | `079_costume.model.json` |
| 剧情·活动38剧情02 | `080_costume.model.json` |
| 剧情·活动38剧情03 | `081_costume.model.json` |
| 剧情·活动52剧情01 | `082_costume.model.json` |
| 剧情·活动70剧情01 | `083_costume.model.json` |
| 剧情·活动89剧情01 | `084_costume.model.json` |
| 剧情·活动105剧情01 | `085_costume.model.json` |
| 剧情·活动116剧情01 | `086_costume.model.json` |
| 剧情·活动119剧情01 | `087_costume.model.json` |
| 剧情·活动216剧情01 | `088_costume.model.json` |
| 剧情·活动304剧情01 | `089_costume.model.json` |
| 剧情·活动342剧情01 | `090_costume.model.json` |
| 剧情·活动342剧情02 | `091_costume.model.json` |
| 剧情·活动342剧情03 | `092_costume.model.json` |
| 季节·2018狗年 | `093_costume.model.json` |
| 季节·2018振袖 | `094_costume.model.json` |
| 季节·2025振袖 | `095_costume.model.json` |
| 季节·夏日水手服 | `096_costume.model.json` |
| 季节·泳装 | `097_costume.model.json` |
| 季节·泳装2023 | `098_costume.model.json` |
| 生日·2021 | `099_costume.model.json` |
| 生日·2022 | `100_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `101_costume.model.json` |
| 其他·Garupa T恤 | `102_costume.model.json` |
| 其他·NFO游戏角色 | `103_costume.model.json` |

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
