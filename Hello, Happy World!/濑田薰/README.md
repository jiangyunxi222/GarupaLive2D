# 濑田薰（Garupa）

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
| 常服·练习服 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季S2 | `011_costume.model.json` |
| 校服·夏季V3 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季S2 | `014_costume.model.json` |
| 演出服·怪盗Hello Happy（SR） | `015_costume.model.json` |
| 演出服·曾经的称呼（SSR） | `016_costume.model.json` |
| 演出服·这也是梦幻（R） | `017_costume.model.json` |
| 演出服·极其梦幻的生物（SR） | `018_costume.model.json` |
| 演出服·主角登场！（SSR） | `019_costume.model.json` |
| 演出服·应援之舞（R） | `020_costume.model.json` |
| 演出服·梦幻般的名演技（SSR） | `021_costume.model.json` |
| 演出服·有我在（SR） | `022_costume.model.json` |
| 演出服·咖啡拿铁的香气（R） | `023_costume.model.json` |
| 演出服·我就是我（SR） | `024_costume.model.json` |
| 演出服·主演（SR） | `025_costume.model.json` |
| 演出服·梦幻的抽鬼牌（SSR） | `026_costume.model.json` |
| 演出服·出色的表演时间（SR） | `027_costume.model.json` |
| 演出服·Elegant Patrol（R） | `028_costume.model.json` |
| 演出服·华丽登场！（SSR） | `029_costume.model.json` |
| 演出服·梦幻的一句（R） | `030_costume.model.json` |
| 演出服·为你献上梦幻的午后（R） | `031_costume.model.json` |
| 演出服·梦幻永存（SR） | `032_costume.model.json` |
| 演出服·给听话的孩子们（SR） | `033_costume.model.json` |
| 演出服·和小千在一起（SSR） | `034_costume.model.json` |
| 演出服·1号，中外场手（SSR） | `035_costume.model.json` |
| 演出服·梦幻眼泪的来由（SR） | `036_costume.model.json` |
| 演出服·优雅的课程（SSR） | `037_costume.model.json` |
| 演出服·梦幻魔女（SR） | `038_costume.model.json` |
| 演出服·光荣的大吉（SR） | `039_costume.model.json` |
| 演出服·随心所欲（SR） | `040_costume.model.json` |
| 演出服·有古代的感觉了吗？（R） | `041_costume.model.json` |
| 演出服·『戏剧性』的日常主角（SSR） | `042_costume.model.json` |
| 演出服·那是掩人耳目的变装（SR） | `043_costume.model.json` |
| 演出服·华丽的逃生剧（SSR） | `044_costume.model.json` |
| 演出服·就连女神也会展露笑容（R） | `045_costume.model.json` |
| 演出服·优雅的广播体操（SR） | `046_costume.model.json` |
| 演出服·华丽的魔术师（SR） | `047_costume.model.json` |
| 演出服·田园复古风 | `048_costume.model.json` |
| 演出服·向往的歌剧院（SR） | `049_costume.model.json` |
| 演出服·『学校里的王子殿下』（SSR） | `050_costume.model.json` |
| 演出服·Fly to infinite sky | `051_costume.model.json` |
| 演出服·毕业（SSR） | `052_costume.model.json` |
| 演出服·饭团游行（SR） | `053_costume.model.json` |
| 演出服·走向光明（UR） | `054_costume.model.json` |
| 演出服·与你共度的夏天（R） | `055_costume.model.json` |
| 演出服·梦幻般的谢幕（UR） | `056_costume.model.json` |
| 演出服·晴天心情似风轻（R） | `057_costume.model.json` |
| 演出服·梦幻的演讲说给你听（SR） | `058_costume.model.json` |
| 演出服·把诚意融入玫瑰中（SSR） | `059_costume.model.json` |
| 演出服·苍海的演奏者（R） | `060_costume.model.json` |
| 演出服·大自然的幕布（UR） | `061_costume.model.json` |
| 演出服·T台魔法（UR） | `062_costume.model.json` |
| 演出服·每球298日元（SR） | `063_costume.model.json` |
| 演出服·梦幻的祭典之花（R） | `064_costume.model.json` |
| 演出服·梦幻盛宴的序幕（UR） | `065_costume.model.json` |
| 演出服·梦幻独角兽（R） | `066_costume.model.json` |
| 演出服·仅此一次的革命（UR） | `067_costume.model.json` |
| 演出服·交给濑田薰吧！（SR） | `068_costume.model.json` |
| 演出服·虚幻兜风之邀（SSR） | `069_costume.model.json` |
| 演出服·优雅徒步者（UR） | `070_costume.model.json` |
| 演出服·笑容的魔法 | `071_costume.model.json` |
| 演出服·Smile Seeker！ | `072_costume.model.json` |
| 演出服·微笑的行星 | `073_costume.model.json` |
| 演出服·来吧来吧，笑容游行 | `074_costume.model.json` |
| 演出服·笑容∞奇迹！ | `075_costume.model.json` |
| 演出服·装点世界的演员 | `076_costume.model.json` |
| 活动·梦想祭·希望你收下 | `077_costume.model.json` |
| 活动·梦想祭·谜团重重的人 | `078_costume.model.json` |
| 活动·梦想祭·拉开舞台帷幕的时刻（UR） | `079_costume.model.json` |
| 活动·梦想祭·通往新世界之门（UR） | `080_costume.model.json` |
| 活动·活动09 | `081_costume.model.json` |
| 活动·闪耀祭·梦幻，倾倒 | `082_costume.model.json` |
| 活动·5周年特别服 | `083_costume.model.json` |
| 剧情·活动45剧情01 | `084_costume.model.json` |
| 剧情·活动48剧情01 | `085_costume.model.json` |
| 剧情·活动67剧情01 | `086_costume.model.json` |
| 剧情·活动88剧情01 | `087_costume.model.json` |
| 剧情·活动100剧情01 | `088_costume.model.json` |
| 剧情·活动110剧情01 | `089_costume.model.json` |
| 剧情·活动119剧情01 | `090_costume.model.json` |
| 剧情·活动206剧情01 | `091_costume.model.json` |
| 剧情·活动216剧情01 | `092_costume.model.json` |
| 剧情·活动226剧情01 | `093_costume.model.json` |
| 剧情·活动244剧情01 | `094_costume.model.json` |
| 剧情·活动260剧情01 | `095_costume.model.json` |
| 剧情·活动304剧情01 | `096_costume.model.json` |
| 剧情·活动316剧情01 | `097_costume.model.json` |
| 剧情·活动342剧情01 | `098_costume.model.json` |
| 剧情·Hello Happy战队面具 | `099_costume.model.json` |
| 剧情·罗密欧 | `100_costume.model.json` |
| 剧情·剧情01（2023） | `101_costume.model.json` |
| 季节·2018狗年 | `102_costume.model.json` |
| 季节·2019振袖 | `103_costume.model.json` |
| 季节·夏日水手服 | `104_costume.model.json` |
| 季节·泳装2023 | `105_costume.model.json` |
| 生日·2021 | `106_costume.model.json` |
| 生日·2022 | `107_costume.model.json` |
| 联动·碰撞出火花吧（UR） | `108_costume.model.json` |
| 联动·白上吹雪（hololive） | `109_costume.model.json` |
| 联动·初音未来·Alien Alien | `110_costume.model.json` |
| 其他·2021愚人节 | `111_costume.model.json` |
| 其他·Garupa T恤 | `112_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。

## 统一点击规则

| 实际点击位置 | 效果 |
|---|---|
| 头顶、刘海上部 | 切换表情 |
| 脸部下半部 | 播放语音 |
| 上身中央 | 播放普通动作 |
| 画面右侧手臂 | 角色左臂动作 |
| 画面左侧手臂 | 角色右臂动作 |
| 腰部、衣服中段 | 打开换装菜单 |
| 腿部、衣服下段 | 打开主菜单 |

每套衣装均包含七个独立矩形点击区，按该衣装默认站姿的头部和身体比例定位，跟随模型整体移动和缩放。点击层保持透明，衣服网格合并或隐藏不会取消入口。动作造成的局部身体变形不会改变矩形分区。

仅头像形态也保留相同布局，上身、腰部、腿部入口位于头像下方的透明区域，左右手入口位于对应两侧。

表情、语音和身体动作不会展开菜单。缺少方向动作时播放普通动作，缺少素材时保持待机。点击分区之间的空白可打开主菜单。

请完整重载 `00_integrated` 主入口，保留 `assets/hitareas` 中的点击层文件。
