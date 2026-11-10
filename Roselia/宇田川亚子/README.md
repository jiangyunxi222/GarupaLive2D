# 宇田川亚子（Garupa）

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
| 校服·夏季2023 | `009_costume.model.json` |
| 校服·夏季S2 | `010_costume.model.json` |
| 校服·冬季 | `011_costume.model.json` |
| 校服·冬季2023 | `012_costume.model.json` |
| 校服·冬季S2 | `013_costume.model.json` |
| 演出服·专一的上进心（SR） | `014_costume.model.json` |
| 演出服·列席婚礼！（R） | `015_costume.model.json` |
| 演出服·大家打起精神来（R） | `016_costume.model.json` |
| 演出服·巴的专属护士（SSR） | `017_costume.model.json` |
| 演出服·游泳圈与大海（R） | `018_costume.model.json` |
| 演出服·永远的憧憬！（SR） | `019_costume.model.json` |
| 演出服·深渊的死灵法师（SSR） | `020_costume.model.json` |
| 演出服·擅长滑雪（R） | `021_costume.model.json` |
| 演出服·大家一起喝下午茶（SR） | `022_costume.model.json` |
| 演出服·想要追赶（SSR） | `023_costume.model.json` |
| 演出服·来转圈圈！（SR） | `024_costume.model.json` |
| 演出服·信念（SSR） | `025_costume.model.json` |
| 演出服·今年也要干劲十足！（R） | `026_costume.model.json` |
| 演出服·首次打工？（R） | `027_costume.model.json` |
| 演出服·白费功夫的关怀（SR） | `028_costume.model.json` |
| 演出服·连战连胜（SR） | `029_costume.model.json` |
| 演出服·觉醒吧大魔姬（SSR） | `030_costume.model.json` |
| 演出服·为了莉莎姐！（SR） | `031_costume.model.json` |
| 演出服·暗黑漫步者（SSR） | `032_costume.model.json` |
| 演出服·被解放的力量？（SR） | `033_costume.model.json` |
| 演出服·为了姐姐（SSR） | `034_costume.model.json` |
| 演出服·握住对方的手（SR） | `035_costume.model.json` |
| 演出服·祝福的皇冠（SR） | `036_costume.model.json` |
| 演出服·发现，帅气（SR） | `037_costume.model.json` |
| 演出服·黑暗力量那个的变装（R） | `038_costume.model.json` |
| 演出服·恶灵退散！（SSR） | `039_costume.model.json` |
| 演出服·蓝玫瑰的保养（SR） | `040_costume.model.json` |
| 演出服·因为很重要！（SR） | `041_costume.model.json` |
| 演出服·遵循吾之指引吧（SSR） | `042_costume.model.json` |
| 演出服·宽广的舞台（SR） | `043_costume.model.json` |
| 演出服·快乐玫瑰（R） | `044_costume.model.json` |
| 演出服·期盼已久的特别日子（SSR） | `045_costume.model.json` |
| 演出服·天真无邪的导火索（R） | `046_costume.model.json` |
| 演出服·向着新世界飞翔（SSR） | `047_costume.model.json` |
| 演出服·向着夏季DIVE！（R） | `048_costume.model.json` |
| 演出服·追赶、超越（SSR） | `049_costume.model.json` |
| 演出服·名垂青史吧！ | `050_costume.model.json` |
| 演出服·全身心感受新年日出（R） | `051_costume.model.json` |
| 演出服·直到生命值降为0！（SSR） | `052_costume.model.json` |
| 演出服·上吧，Trish（R） | `053_costume.model.json` |
| 演出服·前往积雨云的彼岸（SSR） | `054_costume.model.json` |
| 演出服·一、二、三、四！（UR） | `055_costume.model.json` |
| 演出服·应当守护的事物（UR） | `056_costume.model.json` |
| 演出服·为了不迷失方向（R） | `057_costume.model.json` |
| 演出服·欢迎回来，莉莎姐（SR） | `058_costume.model.json` |
| 演出服·下定决心的奔跑（UR） | `059_costume.model.json` |
| 演出服·自豪的手工巧克力！（SSR） | `060_costume.model.json` |
| 演出服·攀向至高的巅峰（UR） | `061_costume.model.json` |
| 演出服·荣耀骑士（R） | `062_costume.model.json` |
| 演出服·来吧，踏浪前行（SR） | `063_costume.model.json` |
| 演出服·帮助我的是（SSR） | `064_costume.model.json` |
| 演出服·将誓言化为力量（SSR） | `065_costume.model.json` |
| 演出服·占卜一年的瞬间（SR） | `066_costume.model.json` |
| 演出服·Re:VENGER（UR） | `067_costume.model.json` |
| 演出服·沉浸于深渊般的旋律中……（SSR） | `068_costume.model.json` |
| 演出服·最棒的曲目单！（SR） | `069_costume.model.json` |
| 演出服·绽放的向日葵（R） | `070_costume.model.json` |
| 演出服·魔弹射手（SR） | `071_costume.model.json` |
| 演出服·晕染于纯白的色彩（SSR） | `072_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `073_costume.model.json` |
| 演出服·Noble・Rose | `074_costume.model.json` |
| 演出服·崇高志向 | `075_costume.model.json` |
| 演出服·环伊甸园 | `076_costume.model.json` |
| 演出服·神秘花束 | `077_costume.model.json` |
| 演出服·小魔王 | `078_costume.model.json` |
| 活动·第3回总选举（R） | `079_costume.model.json` |
| 活动·梦想祭·头号粉丝 | `080_costume.model.json` |
| 活动·梦想祭·鲜花盛开的夏月之夜 | `081_costume.model.json` |
| 活动·梦想祭·By my side（UR） | `082_costume.model.json` |
| 活动·梦想祭·NEAR FUTURE（UR） | `083_costume.model.json` |
| 活动·奇幻冒险 | `084_costume.model.json` |
| 活动·闪耀祭·像魔法一样绽放！ | `085_costume.model.json` |
| 活动·5周年特别服 | `086_costume.model.json` |
| 剧情·活动33剧情01 | `087_costume.model.json` |
| 剧情·活动52剧情01 | `088_costume.model.json` |
| 剧情·活动89剧情01 | `089_costume.model.json` |
| 剧情·活动97剧情01 | `090_costume.model.json` |
| 剧情·活动105剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动156剧情01 | `093_costume.model.json` |
| 剧情·活动216剧情01 | `094_costume.model.json` |
| 剧情·活动236剧情01 | `095_costume.model.json` |
| 剧情·活动335剧情01 | `096_costume.model.json` |
| 剧情·活动340剧情01 | `097_costume.model.json` |
| 季节·2018狗年 | `098_costume.model.json` |
| 季节·2018振袖 | `099_costume.model.json` |
| 季节·万圣节 | `100_costume.model.json` |
| 季节·夏日水手服 | `101_costume.model.json` |
| 季节·泳装 | `102_costume.model.json` |
| 季节·泳装2023 | `103_costume.model.json` |
| 生日·2021 | `104_costume.model.json` |
| 生日·2022 | `105_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `106_costume.model.json` |
| 其他·Garupa T恤 | `107_costume.model.json` |
| 其他·NFO游戏角色 | `108_costume.model.json` |

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
