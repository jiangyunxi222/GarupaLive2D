# 上原绯玛丽（Garupa）

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
| 常服·运动服 | `009_costume.model.json` |
| 常服·练习服 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·夏季2023 | `012_costume.model.json` |
| 校服·夏季S2 | `013_costume.model.json` |
| 校服·夏季V3 | `014_costume.model.json` |
| 校服·冬季 | `015_costume.model.json` |
| 校服·冬季2023 | `016_costume.model.json` |
| 校服·冬季S2 | `017_costume.model.json` |
| 演出服·令人怀念的音源（R） | `018_costume.model.json` |
| 演出服·3人一起戏水（SR） | `019_costume.model.json` |
| 演出服·爱丢东西的幽灵（SSR） | `020_costume.model.json` |
| 演出服·性感吸血鬼（SR） | `021_costume.model.json` |
| 演出服·自我风格的优点（R） | `022_costume.model.json` |
| 演出服·珍藏的地点（SR） | `023_costume.model.json` |
| 演出服·舞蹈训练（SR） | `024_costume.model.json` |
| 演出服·我们来了！（SSR） | `025_costume.model.json` |
| 演出服·无法停下的幻想（R） | `026_costume.model.json` |
| 演出服·Cutie（SSR） | `027_costume.model.json` |
| 演出服·两人和睦相处（SR） | `028_costume.model.json` |
| 演出服·停滞的时间（SR） | `029_costume.model.json` |
| 演出服·情绪高涨！（SR） | `030_costume.model.json` |
| 演出服·令人怀念的圣诞节（R） | `031_costume.model.json` |
| 演出服·目标是大成功（SSR） | `032_costume.model.json` |
| 演出服·开心的眼泪和巧克力（SSR） | `033_costume.model.json` |
| 演出服·好累啊~~（SR） | `034_costume.model.json` |
| 演出服·憧憬的自己（SSR） | `035_costume.model.json` |
| 演出服·学生食堂的甜点！（SR） | `036_costume.model.json` |
| 演出服·接触艺术（SR） | `037_costume.model.json` |
| 演出服·年糕小豆汤派对♪（SSR） | `038_costume.model.json` |
| 演出服·少女的憧憬（SR） | `039_costume.model.json` |
| 演出服·纯白的下午茶时光（R） | `040_costume.model.json` |
| 演出服·快闪跃动（SR） | `041_costume.model.json` |
| 演出服·大家一起迈出新的一步（SSR） | `042_costume.model.json` |
| 演出服·阳光般的微笑（R） | `043_costume.model.json` |
| 演出服·可爱夏日女孩（R） | `044_costume.model.json` |
| 演出服·一如既往的「那个」（SSR） | `045_costume.model.json` |
| 演出服·绯玛丽剪刀手☆（R） | `046_costume.model.json` |
| 演出服·『非玛丽』，出动！（SSR） | `047_costume.model.json` |
| 演出服·环游世界之门！（SR） | `048_costume.model.json` |
| 演出服·崭新的景色（SSR） | `049_costume.model.json` |
| 演出服·幸福涂鸦（SR） | `050_costume.model.json` |
| 演出服·今年也和平时一样♪（SSR） | `051_costume.model.json` |
| 演出服·出乎意料的『一口』（SR） | `052_costume.model.json` |
| 演出服·呐喊（SSR） | `053_costume.model.json` |
| 演出服·夏日回忆（SR） | `054_costume.model.json` |
| 演出服·Meow♡Maid（R） | `055_costume.model.json` |
| 演出服·永恒的心意（SR） | `056_costume.model.json` |
| 演出服·蓝色火焰 | `057_costume.model.json` |
| 演出服·夕阳与上一段活用动词（SR） | `058_costume.model.json` |
| 演出服·如果并非没问题（UR） | `059_costume.model.json` |
| 演出服·一起跳舞吧♪（UR） | `060_costume.model.json` |
| 演出服·摇曳着不安的眼眸（R） | `061_costume.model.json` |
| 演出服·幸福的一刻（UR） | `062_costume.model.json` |
| 演出服·因为是队长（SSR） | `063_costume.model.json` |
| 演出服·云外茜天（UR） | `064_costume.model.json` |
| 演出服·围着篝火（UR） | `065_costume.model.json` |
| 演出服·俏皮☆粉红（R） | `066_costume.model.json` |
| 演出服·再次诉说一生的请求（SR） | `067_costume.model.json` |
| 演出服·因为你从不落泪（SR） | `068_costume.model.json` |
| 演出服·儿时的憧憬与当下（UR） | `069_costume.model.json` |
| 演出服·绽放的笑容与水花（SSR） | `070_costume.model.json` |
| 演出服·中意的日常？（SSR） | `071_costume.model.json` |
| 演出服·最棒的口感！（SR） | `072_costume.model.json` |
| 演出服·革命前夜的光芒（R） | `073_costume.model.json` |
| 演出服·黄昏时分的约定（UR） | `074_costume.model.json` |
| 演出服·难忘的晚霞（R） | `075_costume.model.json` |
| 演出服·永远的羁绊（UR） | `076_costume.model.json` |
| 演出服·Grow Up Rock | `077_costume.model.json` |
| 演出服·疾驰之空 | `078_costume.model.json` |
| 演出服·绯红之魂 | `079_costume.model.json` |
| 演出服·激情四溢的青春 | `080_costume.model.json` |
| 演出服·Get up！ | `081_costume.model.json` |
| 演出服·神奇的护身符 | `082_costume.model.json` |
| 活动·梦想祭·特别的设计 | `083_costume.model.json` |
| 活动·梦想祭·乞求的眼神 | `084_costume.model.json` |
| 活动·梦想祭·绯玛丽的游乐园计划（UR） | `085_costume.model.json` |
| 活动·梦想祭·阳光下的你（UR） | `086_costume.model.json` |
| 活动·5周年特别服 | `087_costume.model.json` |
| 剧情·活动06 | `088_costume.model.json` |
| 剧情·活动42剧情01 | `089_costume.model.json` |
| 剧情·活动42剧情02 | `090_costume.model.json` |
| 剧情·活动42剧情03 | `091_costume.model.json` |
| 剧情·活动49剧情01 | `092_costume.model.json` |
| 剧情·活动54剧情01 | `093_costume.model.json` |
| 剧情·活动90剧情01 | `094_costume.model.json` |
| 剧情·活动122剧情01 | `095_costume.model.json` |
| 剧情·活动128剧情01 | `096_costume.model.json` |
| 剧情·活动144剧情01 | `097_costume.model.json` |
| 剧情·活动216剧情01 | `098_costume.model.json` |
| 剧情·活动236剧情01 | `099_costume.model.json` |
| 剧情·活动296剧情01 | `100_costume.model.json` |
| 季节·2018狗年 | `101_costume.model.json` |
| 季节·2019振袖 | `102_costume.model.json` |
| 季节·夏日水手服 | `103_costume.model.json` |
| 季节·泳装 | `104_costume.model.json` |
| 季节·泳装2023 | `105_costume.model.json` |
| 生日·2021 | `106_costume.model.json` |
| 生日·2022 | `107_costume.model.json` |
| 联动·初音未来·Lost one的号哭 | `108_costume.model.json` |
| 其他·Garupa T恤 | `109_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
