# 牛込里美（Garupa）

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
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·冬 | `007_costume.model.json` |
| 常服·冬2023 | `008_costume.model.json` |
| 常服·冬·墨镜 | `009_costume.model.json` |
| 校服·体操服 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·夏季2023 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季2023 | `014_costume.model.json` |
| 演出服·憧憬的姐姐（SR） | `015_costume.model.json` |
| 演出服·惹人怜爱的小猫（SSR） | `016_costume.model.json` |
| 演出服·冰淇淋螺旋♪（R） | `017_costume.model.json` |
| 演出服·害羞的天使（R） | `018_costume.model.json` |
| 演出服·派对的准备（SR） | `019_costume.model.json` |
| 演出服·不由得紧张了（SR） | `020_costume.model.json` |
| 演出服·是干劲的问题？（SSR） | `021_costume.model.json` |
| 演出服·假日的巧克力（SR） | `022_costume.model.json` |
| 演出服·想太多？（R） | `023_costume.model.json` |
| 演出服·创作时间（SSR） | `024_costume.model.json` |
| 演出服·传递的心意（R） | `025_costume.model.json` |
| 演出服·即使分开也心意相通（SSR） | `026_costume.model.json` |
| 演出服·为了守护某人（SSR） | `027_costume.model.json` |
| 演出服·羁绊的腕套（SR） | `028_costume.model.json` |
| 演出服·用我们的音乐（R） | `029_costume.model.json` |
| 演出服·在星空之下（SR） | `030_costume.model.json` |
| 演出服·我不害怕哦？（SR） | `031_costume.model.json` |
| 演出服·抓住秋天（SSR） | `032_costume.model.json` |
| 演出服·玩具朋友（SSR） | `033_costume.model.json` |
| 演出服·急切的心情（SSR） | `034_costume.model.json` |
| 演出服·胜利的花冠（SR） | `035_costume.model.json` |
| 演出服·互相理解的关系（SSR） | `036_costume.model.json` |
| 演出服·平静的声援（SR） | `037_costume.model.json` |
| 演出服·天使与恶魔的私语（SSR） | `038_costume.model.json` |
| 演出服·TRY！（SR） | `039_costume.model.json` |
| 演出服·发现心动不已♪（R） | `040_costume.model.json` |
| 演出服·碧蓝大海的另一端（SR） | `041_costume.model.json` |
| 演出服·饱含情感（SSR） | `042_costume.model.json` |
| 演出服·早上好，全新的我（R） | `043_costume.model.json` |
| 演出服·终将成为回忆的某日（SSR） | `044_costume.model.json` |
| 演出服·和平时不同的教室中（SR） | `045_costume.model.json` |
| 演出服·Apotheose！（R） | `046_costume.model.json` |
| 演出服·追随星光（SSR） | `047_costume.model.json` |
| 演出服·没有注意看路？（R） | `048_costume.model.json` |
| 演出服·胆怯的恶魔猎人·里美（SSR） | `049_costume.model.json` |
| 演出服·倒映于水面上的心（UR） | `050_costume.model.json` |
| 演出服·牙科镜（R） | `051_costume.model.json` |
| 演出服·华丽的少女（R） | `052_costume.model.json` |
| 演出服·里美的决心（UR） | `053_costume.model.json` |
| 演出服·前往梦见的海彼岸（R） | `054_costume.model.json` |
| 演出服·按捺不住的心情（SSR） | `055_costume.model.json` |
| 演出服·温暖人心的菜肴（SR） | `056_costume.model.json` |
| 演出服·牛込导演，拍摄开始！（UR） | `057_costume.model.json` |
| 演出服·守望着的应援（SSR） | `058_costume.model.json` |
| 演出服·在玫瑰花瓣雨中（SR） | `059_costume.model.json` |
| 演出服·满载回忆（SR） | `060_costume.model.json` |
| 演出服·晚霞映照着的脸庞（UR） | `061_costume.model.json` |
| 演出服·紧张的朗读时间（SSR） | `062_costume.model.json` |
| 演出服·街角拍照点（R） | `063_costume.model.json` |
| 演出服·触碰前行的步伐（SR） | `064_costume.model.json` |
| 演出服·温暖的手掌（UR） | `065_costume.model.json` |
| 演出服·Colorful Poppin！ | `066_costume.model.json` |
| 演出服·Cheerful Star☆ | `067_costume.model.json` |
| 演出服·Peaceful Jump！ | `068_costume.model.json` |
| 演出服·星光闪耀的日常 | `069_costume.model.json` |
| 演出服·Miracle☆Poppin | `070_costume.model.json` |
| 演出服·竭尽全力的勇气 | `071_costume.model.json` |
| 演出服·宛若巧克力海螺包的时间 | `072_costume.model.json` |
| 活动·梦想祭·重视基础 | `073_costume.model.json` |
| 活动·梦想祭·照片上那张面容 | `074_costume.model.json` |
| 活动·梦想祭·发现小小秋意（UR） | `075_costume.model.json` |
| 活动·梦想祭·放学后，雨天和好友（UR） | `076_costume.model.json` |
| 活动·Poppin'Party Fes | `077_costume.model.json` |
| 活动·5周年特别服 | `078_costume.model.json` |
| 剧情·第0章Live | `079_costume.model.json` |
| 剧情·第0章睡衣 | `080_costume.model.json` |
| 剧情·活动119剧情01 | `081_costume.model.json` |
| 剧情·活动140剧情01 | `082_costume.model.json` |
| 剧情·活动160剧情01 | `083_costume.model.json` |
| 剧情·活动216剧情01 | `084_costume.model.json` |
| 剧情·活动227剧情01 | `085_costume.model.json` |
| 剧情·活动227剧情02 | `086_costume.model.json` |
| 剧情·活动233剧情01 | `087_costume.model.json` |
| 季节·2018狗年 | `088_costume.model.json` |
| 季节·2019振袖 | `089_costume.model.json` |
| 季节·2024振袖 | `090_costume.model.json` |
| 季节·圣诞01 | `091_costume.model.json` |
| 季节·万圣节 | `092_costume.model.json` |
| 季节·夏日水手服 | `093_costume.model.json` |
| 季节·浴衣 | `094_costume.model.json` |
| 生日·2021 | `095_costume.model.json` |
| 生日·2022 | `096_costume.model.json` |
| 联动·时乃空（hololive） | `097_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `098_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `099_costume.model.json` |
| 其他·2021愚人节 | `100_costume.model.json` |
| 其他·Garupa T恤 | `101_costume.model.json` |

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
