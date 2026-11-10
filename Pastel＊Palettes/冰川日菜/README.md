# 冰川日菜（Garupa）

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
| 常服·2023·荧光棒 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季S2 | `011_costume.model.json` |
| 校服·夏季V3 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季S2 | `014_costume.model.json` |
| 演出服·数光年的光芒（SR） | `015_costume.model.json` |
| 演出服·重要的契机（R） | `016_costume.model.json` |
| 演出服·重要的诗笺（SSR） | `017_costume.model.json` |
| 演出服·舞台的背后（R） | `018_costume.model.json` |
| 演出服·认真・摇摇晃晃！（SR） | `019_costume.model.json` |
| 演出服·大概分量就好（SR） | `020_costume.model.json` |
| 演出服·滑雪场最棒了！（SR） | `021_costume.model.json` |
| 演出服·独一无二的我（SSR） | `022_costume.model.json` |
| 演出服·周边介绍（SR） | `023_costume.model.json` |
| 演出服·繁星璀璨的邂逅（SSR） | `024_costume.model.json` |
| 演出服·日菜的愿望（SR） | `025_costume.model.json` |
| 演出服·爱捣蛋的小恶魔（SSR） | `026_costume.model.json` |
| 演出服·欢迎来到天文社！（SSR） | `027_costume.model.json` |
| 演出服·万事大吉（SR） | `028_costume.model.json` |
| 演出服·这就是偶像（SR） | `029_costume.model.json` |
| 演出服·惜别之时（SSR） | `030_costume.model.json` |
| 演出服·已经等不及了！（SR） | `031_costume.model.json` |
| 演出服·什么什么？小鸫鸫（SSR） | `032_costume.model.json` |
| 演出服·灵动跳跃（R） | `033_costume.model.json` |
| 演出服·心情愉悦的学生会会长（SR） | `034_costume.model.json` |
| 演出服·完美的东方服装（R） | `035_costume.model.json` |
| 演出服·噜噜噜噜噜♪（SSR） | `036_costume.model.json` |
| 演出服·交给我吧！（R） | `037_costume.model.json` |
| 演出服·日菜抽中的大奖（SSR） | `038_costume.model.json` |
| 演出服·发现大海邮箱☆（SSR） | `039_costume.model.json` |
| 演出服·活跃气氛的前辈（R） | `040_costume.model.json` |
| 演出服·小双子星（SSR） | `041_costume.model.json` |
| 演出服·哔哔地请多关照！（SR） | `042_costume.model.json` |
| 演出服·噜♪地扩散！（SR） | `043_costume.model.json` |
| 演出服·自己开辟的道路（SSR） | `044_costume.model.json` |
| 演出服·噜♪僵尸（SR） | `045_costume.model.json` |
| 演出服·鲜花飘舞♪（R） | `046_costume.model.json` |
| 演出服·不愧是小伊芙！（SR） | `047_costume.model.json` |
| 演出服·知道这题的答案吗？（SSR） | `048_costume.model.json` |
| 演出服·感觉被点燃了♪（R） | `049_costume.model.json` |
| 演出服·喜欢模仿的小日菜（SR） | `050_costume.model.json` |
| 演出服·波子汽水颜色的夏天 | `051_costume.model.json` |
| 演出服·致即将展翅高飞的我们（SSR） | `052_costume.model.json` |
| 演出服·今后会更有趣（SSR） | `053_costume.model.json` |
| 演出服·毕业（SSR） | `054_costume.model.json` |
| 演出服·Enjoy中华街♪（SSR） | `055_costume.model.json` |
| 演出服·银河偶像（UR） | `056_costume.model.json` |
| 演出服·悬崖边上的我们（UR） | `057_costume.model.json` |
| 演出服·在意的事情是（SR） | `058_costume.model.json` |
| 演出服·天文社的情谊？（UR） | `059_costume.model.json` |
| 演出服·蓦然回首、望见未来（SSR） | `060_costume.model.json` |
| 演出服·想做就去做！（R） | `061_costume.model.json` |
| 演出服·Hyvää joulua！（UR） | `062_costume.model.json` |
| 演出服·户外拓展大师（UR） | `063_costume.model.json` |
| 演出服·活力全开模式（R） | `064_costume.model.json` |
| 演出服·夏日祭典，雀跃的心（SSR） | `065_costume.model.json` |
| 演出服·恶作剧大成功！（SR） | `066_costume.model.json` |
| 演出服·说出口，听进心（UR） | `067_costume.model.json` |
| 演出服·让人感到噜♪的歌词（UR） | `068_costume.model.json` |
| 演出服·Traveling Way（R） | `069_costume.model.json` |
| 演出服·雨中紫（R） | `070_costume.model.json` |
| 演出服·连接我们的事物（UR） | `071_costume.model.json` |
| 演出服·装饰交给我（SR） | `072_costume.model.json` |
| 演出服·前往辉煌的舞台 | `073_costume.model.json` |
| 演出服·照亮梦想 | `074_costume.model.json` |
| 演出服·盛放的声援 | `075_costume.model.json` |
| 演出服·梦色婚礼 | `076_costume.model.json` |
| 演出服·牡丹褶边 | `077_costume.model.json` |
| 演出服·未知数 | `078_costume.model.json` |
| 活动·梦想祭·一样的T恤 | `079_costume.model.json` |
| 活动·梦想祭·run-A-way | `080_costume.model.json` |
| 活动·梦想祭·双胞胎穿搭很噜♪（UR） | `081_costume.model.json` |
| 活动·梦想祭·变幻自如的光芒（UR） | `082_costume.model.json` |
| 活动·闪耀祭·双眸闪闪发亮 | `083_costume.model.json` |
| 活动·5周年特别服 | `084_costume.model.json` |
| 剧情·活动33剧情01 | `085_costume.model.json` |
| 剧情·活动36剧情01 | `086_costume.model.json` |
| 剧情·活动56剧情01 | `087_costume.model.json` |
| 剧情·活动86剧情01 | `088_costume.model.json` |
| 剧情·活动86剧情02 | `089_costume.model.json` |
| 剧情·活动86剧情03 | `090_costume.model.json` |
| 剧情·活动104剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动134剧情01 | `093_costume.model.json` |
| 剧情·活动154剧情01 | `094_costume.model.json` |
| 剧情·活动154剧情02 | `095_costume.model.json` |
| 剧情·活动195剧情01 | `096_costume.model.json` |
| 剧情·活动216剧情01 | `097_costume.model.json` |
| 剧情·活动278剧情01 | `098_costume.model.json` |
| 剧情·活动304剧情01 | `099_costume.model.json` |
| 剧情·活动344剧情01 | `100_costume.model.json` |
| 剧情·剧情01 | `101_costume.model.json` |
| 剧情·剧情01（2023） | `102_costume.model.json` |
| 季节·2018狗年 | `103_costume.model.json` |
| 季节·2019振袖 | `104_costume.model.json` |
| 季节·夏日水手服 | `105_costume.model.json` |
| 季节·泳装2023 | `106_costume.model.json` |
| 生日·2021 | `107_costume.model.json` |
| 生日·2022 | `108_costume.model.json` |
| 联动·湊阿库娅（hololive） | `109_costume.model.json` |
| 其他·2021愚人节 | `110_costume.model.json` |
| 其他·Garupa T恤 | `111_costume.model.json` |
| 其他·机关小丑 | `112_costume.model.json` |

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
