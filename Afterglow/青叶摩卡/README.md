# 青叶摩卡（Garupa）

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
| 常服·睡衣2023 | `008_costume.model.json` |
| 常服·商店 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季2023 | `011_costume.model.json` |
| 校服·夏季S2 | `012_costume.model.json` |
| 校服·夏季V3 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季2023 | `015_costume.model.json` |
| 校服·冬季S2 | `016_costume.model.json` |
| 演出服·想要理解的思念（SSR） | `017_costume.model.json` |
| 演出服·学园七大不思议（SR） | `018_costume.model.json` |
| 演出服·最棒的打工伙伴（SR） | `019_costume.model.json` |
| 演出服·小小的成长？（R） | `020_costume.model.json` |
| 演出服·食欲是无穷无尽的（R） | `021_costume.model.json` |
| 演出服·稍微绕个远路（SR） | `022_costume.model.json` |
| 演出服·神秘美少女（SSR） | `023_costume.model.json` |
| 演出服·Hungry（SR） | `024_costume.model.json` |
| 演出服·陪伴在身旁（SSR） | `025_costume.model.json` |
| 演出服·一起来玩吧（SSR） | `026_costume.model.json` |
| 演出服·秘密的编排（SSR） | `027_costume.model.json` |
| 演出服·绝对我行我素（R） | `028_costume.model.json` |
| 演出服·冥界的引导者（SSR） | `029_costume.model.json` |
| 演出服·齐声一起说（SR） | `030_costume.model.json` |
| 演出服·常伴身旁（SSR） | `031_costume.model.json` |
| 演出服·华丽的异国风情服装（SR） | `032_costume.model.json` |
| 演出服·代号摩卡（SR） | `033_costume.model.json` |
| 演出服·今天是纪念日（SSR） | `034_costume.model.json` |
| 演出服·再次奋进！（R） | `035_costume.model.json` |
| 演出服·度假写真（SSR） | `036_costume.model.json` |
| 演出服·黑猫带路中（SR） | `037_costume.model.json` |
| 演出服·寻找答案（SR） | `038_costume.model.json` |
| 演出服·杰出的采访者（SR） | `039_costume.model.json` |
| 演出服·诱惑的阿拉伯风情（R） | `040_costume.model.json` |
| 演出服·绽放在夏日的笑容（SSR） | `041_costume.model.json` |
| 演出服·羽泽咖啡店的常客（SR） | `042_costume.model.json` |
| 演出服·慢节奏生活的冒险者（R） | `043_costume.model.json` |
| 演出服·回家路上绕个道（R） | `044_costume.model.json` |
| 演出服·如今映入眼瞳的是（SSR） | `045_costume.model.json` |
| 演出服·幻想巧克力（SR） | `046_costume.model.json` |
| 演出服·樱花相框（SSR） | `047_costume.model.json` |
| 演出服·我们的颜色 | `048_costume.model.json` |
| 演出服·Round & Round（SSR） | `049_costume.model.json` |
| 演出服·熠熠生辉的眼眸 | `050_costume.model.json` |
| 演出服·回忆是艳红的色彩（R） | `051_costume.model.json` |
| 演出服·表情阴沉的你（SR） | `052_costume.model.json` |
| 演出服·名侦探小摩卡学姐（R） | `053_costume.model.json` |
| 演出服·夕阳照耀下的侧脸（UR） | `054_costume.model.json` |
| 演出服·把愿望藏在心里（UR） | `055_costume.model.json` |
| 演出服·不要一个人烦恼（SSR） | `056_costume.model.json` |
| 演出服·温暖的时刻（SR） | `057_costume.model.json` |
| 演出服·无论何种颜色的夕阳（UR） | `058_costume.model.json` |
| 演出服·被卷入之后（UR） | `059_costume.model.json` |
| 演出服·每天都要来天台（R） | `060_costume.model.json` |
| 演出服·在梦与现实的交界处（SSR） | `061_costume.model.json` |
| 演出服·本杰明仔（UR） | `062_costume.model.json` |
| 演出服·思念与花朵同在（R） | `063_costume.model.json` |
| 演出服·英雄赠予的面包（SSR） | `064_costume.model.json` |
| 演出服·B5尺寸的无限大（UR） | `065_costume.model.json` |
| 演出服·暖洋洋、软蓬蓬（UR） | `066_costume.model.json` |
| 演出服·请品尝我的精心之作~（UR） | `067_costume.model.json` |
| 演出服·认真的指正？（SSR） | `068_costume.model.json` |
| 演出服·沐浴初次的热情（UR） | `069_costume.model.json` |
| 演出服·考拉与我（R） | `070_costume.model.json` |
| 演出服·Grow Up Rock | `071_costume.model.json` |
| 演出服·疾驰之空 | `072_costume.model.json` |
| 演出服·绯红之魂 | `073_costume.model.json` |
| 演出服·激情四溢的青春 | `074_costume.model.json` |
| 演出服·Get up！ | `075_costume.model.json` |
| 演出服·青梅竹马的意义 | `076_costume.model.json` |
| 活动·第2回总选举（R） | `077_costume.model.json` |
| 活动·梦想祭·为了超越期待 | `078_costume.model.json` |
| 活动·梦想祭·指尖的温暖 | `079_costume.model.json` |
| 活动·梦想祭·樱花飘散的旋律（UR） | `080_costume.model.json` |
| 活动·梦想祭·幸福无比的时光（UR） | `081_costume.model.json` |
| 活动·梦想祭·浅眠的序章（UR） | `082_costume.model.json` |
| 活动·5周年特别服 | `083_costume.model.json` |
| 剧情·活动06 | `084_costume.model.json` |
| 剧情·活动42剧情01 | `085_costume.model.json` |
| 剧情·活动49剧情01 | `086_costume.model.json` |
| 剧情·活动54剧情01 | `087_costume.model.json` |
| 剧情·活动65剧情01 | `088_costume.model.json` |
| 剧情·活动94剧情01 | `089_costume.model.json` |
| 剧情·活动94剧情02 | `090_costume.model.json` |
| 剧情·活动122剧情01 | `091_costume.model.json` |
| 剧情·活动200剧情01 | `092_costume.model.json` |
| 剧情·活动216剧情01 | `093_costume.model.json` |
| 剧情·活动266剧情01 | `094_costume.model.json` |
| 剧情·活动322剧情01 | `095_costume.model.json` |
| 季节·2018狗年 | `096_costume.model.json` |
| 季节·2019振袖 | `097_costume.model.json` |
| 季节·2024振袖 | `098_costume.model.json` |
| 季节·夏日水手服 | `099_costume.model.json` |
| 季节·泳装2023 | `100_costume.model.json` |
| 生日·2021 | `101_costume.model.json` |
| 生日·2022 | `102_costume.model.json` |
| 联动·初音未来·Lost one的号哭 | `103_costume.model.json` |
| 其他·Garupa T恤 | `104_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
