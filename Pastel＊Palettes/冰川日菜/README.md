# 冰川日菜（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 角色菜单

双击本角色文件夹中的 `打开角色菜单.cmd`。页面、预览和全部操作均随角色提供，Windows 无需另装 Python。

- 动作、表情、衣装、语音和❤收藏使用平面标签切换，点击条目即可使用，点击爱心只收藏。
- 动作与语音提供循环开关，可选择全部或❤收藏。身体点击继续随机播放单个条目。
- 字幕开关与「身体互动仅❤」独立设置，同一角色换装后保留。
- 桌面菜单提供页面入口、动作循环、语音循环、随机换装、恢复待机和关闭菜单。循环开启后再次点击即可停止。
- 页面可独立预览。启动 Live2DViewerEX 后，点击「连接桌面」即可同步控制当前角色。
- 衣装缩略图首次逐一生成并缓存在本角色目录中。桌面换装会同步页面，连接中断后会自动尝试恢复。

更新后请完整重载 `00_integrated` 主入口。角色文件夹整体移动时，需一同保留 `控制台` 与 `assets`。

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

| 实际点击位置 | 效果 |
|---|---|
| 头顶、刘海上部 | 切换表情 |
| 脸部下半部 | 随机语音，按开关显示字幕 |
| 上身中央 | 播放普通动作 |
| 画面右侧手臂 | 角色左臂动作 |
| 画面左侧手臂 | 角色右臂动作 |
| 腰部、衣服中段 | 直接随机换装 |
| 腿部、衣服下段 | 打开主菜单 |

每套衣装均包含七个独立矩形点击区，按该衣装默认站姿的头部和身体比例定位，跟随模型整体移动和缩放。点击层保持透明，衣服网格合并或隐藏不会取消入口。动作造成的局部身体变形不会改变矩形分区。

仅头像形态也保留相同布局，上身、腰部、腿部入口位于头像下方的透明区域，左右手入口位于对应两侧。

表情、语音和身体动作不会展开菜单。缺少方向动作时播放普通动作，缺少素材时保持待机。点击分区之间的空白可打开主菜单。

请完整重载 `00_integrated` 主入口，保留 `assets/hitareas` 中的点击层文件。

页面提供「语音字幕」开关，默认开启，同一角色换装后保留。点击语音区只播放随机语音及可选字幕。腰部点击随机切换其他衣装，全部衣装可在页面中选择。

语音字幕默认开启，同一角色换装后保留设置。原始资源没有语音文件时，点击语音区显示「当前角色未提供语音素材」，此提示不受字幕开关影响。
