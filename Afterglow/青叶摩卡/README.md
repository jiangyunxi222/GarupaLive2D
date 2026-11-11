# 青叶摩卡（Garupa）

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
