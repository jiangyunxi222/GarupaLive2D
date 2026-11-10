# 冰川纱夜（Garupa）

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
| 常服·围裙 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·冬 | `007_costume.model.json` |
| 常服·冬2023 | `008_costume.model.json` |
| 校服·夏季 | `009_costume.model.json` |
| 校服·冬季 | `010_costume.model.json` |
| 校服·冬季V3 | `011_costume.model.json` |
| 演出服·愿能交融的音色（R） | `012_costume.model.json` |
| 演出服·夏天的圆筒冰激凌（R） | `013_costume.model.json` |
| 演出服·两人度过的七夕（SSR） | `014_costume.model.json` |
| 演出服·雨声与泪滴（SR） | `015_costume.model.json` |
| 演出服·烘焙饼干（SR） | `016_costume.model.json` |
| 演出服·新手防御者（SR） | `017_costume.model.json` |
| 演出服·百发百中（SSR） | `018_costume.model.json` |
| 演出服·这次由我来（SR） | `019_costume.model.json` |
| 演出服·与雨相伴（SR） | `020_costume.model.json` |
| 演出服·我所能说的（R） | `021_costume.model.json` |
| 演出服·闪耀的水之魔法（SSR） | `022_costume.model.json` |
| 演出服·静静燃烧的气焰（SR） | `023_costume.model.json` |
| 演出服·两人一起看过的星空（SSR） | `024_costume.model.json` |
| 演出服·新作的挑战（SR） | `025_costume.model.json` |
| 演出服·同一个前进目标（SSR） | `026_costume.model.json` |
| 演出服·一本正经的风纪委员（SR） | `027_costume.model.json` |
| 演出服·两人的约定（SSR） | `028_costume.model.json` |
| 演出服·庆祝的芭菲（SR） | `029_costume.model.json` |
| 演出服·凛然的朗诵者（SSR） | `030_costume.model.json` |
| 演出服·秋色狐狸（R） | `031_costume.model.json` |
| 演出服·同伴的危机（SR） | `032_costume.model.json` |
| 演出服·梦幻舞者（R） | `033_costume.model.json` |
| 演出服·最棒的应援者（SSR） | `034_costume.model.json` |
| 演出服·皇家骑士（R） | `035_costume.model.json` |
| 演出服·动人心弦的演奏（SSR） | `036_costume.model.json` |
| 演出服·古典的希望（R） | `037_costume.model.json` |
| 演出服·双子星的二重奏（SSR） | `038_costume.model.json` |
| 演出服·颤栗的演奏者（SR） | `039_costume.model.json` |
| 演出服·你的话一定能做到（R） | `040_costume.model.json` |
| 演出服·瞬间的乡愁（SR） | `041_costume.model.json` |
| 演出服·前往理想之地（SSR） | `042_costume.model.json` |
| 演出服·预习得很充分（SR） | `043_costume.model.json` |
| 演出服·你是为了谁？（SR） | `044_costume.model.json` |
| 演出服·初春漫步（SSR） | `045_costume.model.json` |
| 演出服·对香格里拉的向往（R） | `046_costume.model.json` |
| 演出服·造访古都（SSR） | `047_costume.model.json` |
| 演出服·踏上荆棘之路的觉悟（SSR） | `048_costume.model.json` |
| 演出服·唯有皎洁明月知晓（SSR） | `049_costume.model.json` |
| 演出服·回首旅途 | `050_costume.model.json` |
| 演出服·毕业（SSR） | `051_costume.model.json` |
| 演出服·积累每一个音符（SSR） | `052_costume.model.json` |
| 演出服·激活未来（R） | `053_costume.model.json` |
| 演出服·恶魔猎人的领导者·纱夜（UR） | `054_costume.model.json` |
| 演出服·蓝天下的高速公路（SR） | `055_costume.model.json` |
| 演出服·摇摆不定的天平（UR） | `056_costume.model.json` |
| 演出服·登上重大舞台的邀请（SR） | `057_costume.model.json` |
| 演出服·沐浴在阳光中（UR） | `058_costume.model.json` |
| 演出服·纯白的野花花束（R） | `059_costume.model.json` |
| 演出服·困惑的假期（UR） | `060_costume.model.json` |
| 演出服·操不完的心（SSR） | `061_costume.model.json` |
| 演出服·从我到你（UR） | `062_costume.model.json` |
| 演出服·一位姐姐的话（SSR） | `063_costume.model.json` |
| 演出服·迂回的尽头（UR） | `064_costume.model.json` |
| 演出服·两块拼图（UR） | `065_costume.model.json` |
| 演出服·冰冻的结晶（R） | `066_costume.model.json` |
| 演出服·迈向约定之地的一步（SR） | `067_costume.model.json` |
| 演出服·此刻我们的距离（UR） | `068_costume.model.json` |
| 演出服·在绚烂的夜空下（UR） | `069_costume.model.json` |
| 演出服·书之沙龙（R） | `070_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `071_costume.model.json` |
| 演出服·Noble・Rose | `072_costume.model.json` |
| 演出服·崇高志向 | `073_costume.model.json` |
| 演出服·环伊甸园 | `074_costume.model.json` |
| 演出服·神秘花束 | `075_costume.model.json` |
| 演出服·双子的苦恼 | `076_costume.model.json` |
| 活动·第3回总选举（R） | `077_costume.model.json` |
| 活动·第4回总选举（R） | `078_costume.model.json` |
| 活动·梦想祭·魅惑之手 | `079_costume.model.json` |
| 活动·梦想祭·下着雨的窗边 | `080_costume.model.json` |
| 活动·梦想祭·雨滴与太阳（UR） | `081_costume.model.json` |
| 活动·梦想祭·乘着温暖的风（UR） | `082_costume.model.json` |
| 活动·奇幻冒险 | `083_costume.model.json` |
| 活动·奇幻冒险（二） | `084_costume.model.json` |
| 活动·5周年特别服 | `085_costume.model.json` |
| 剧情·活动38剧情01 | `086_costume.model.json` |
| 剧情·活动38剧情02 | `087_costume.model.json` |
| 剧情·活动38剧情03 | `088_costume.model.json` |
| 剧情·活动42剧情01 | `089_costume.model.json` |
| 剧情·活动52剧情01 | `090_costume.model.json` |
| 剧情·活动105剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动216剧情01 | `093_costume.model.json` |
| 剧情·活动227剧情01 | `094_costume.model.json` |
| 剧情·活动266剧情01 | `095_costume.model.json` |
| 剧情·活动340剧情01 | `096_costume.model.json` |
| 季节·2018狗年 | `097_costume.model.json` |
| 季节·2019振袖 | `098_costume.model.json` |
| 季节·夏日水手服 | `099_costume.model.json` |
| 季节·泳装2023 | `100_costume.model.json` |
| 生日·2021 | `101_costume.model.json` |
| 生日·2022 | `102_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `103_costume.model.json` |
| 其他·2021愚人节 | `104_costume.model.json` |
| 其他·Garupa T恤 | `105_costume.model.json` |

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
