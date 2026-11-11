# 若宫伊芙（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服·打工2023 | `003_costume.model.json` |
| 常服·咖啡厅 | `004_costume.model.json` |
| 常服 | `005_costume.model.json` |
| 常服·2023 | `006_costume.model.json` |
| 常服·2023·荧光棒 | `007_costume.model.json` |
| 常服·夏 | `008_costume.model.json` |
| 常服·夏2023 | `009_costume.model.json` |
| 常服·冬 | `010_costume.model.json` |
| 常服·冬2023 | `011_costume.model.json` |
| 校服·体操服 | `012_costume.model.json` |
| 校服·夏季 | `013_costume.model.json` |
| 校服·夏季2023 | `014_costume.model.json` |
| 校服·冬季 | `015_costume.model.json` |
| 校服·冬季2023 | `016_costume.model.json` |
| 演出服·期待已久的赏樱（R） | `017_costume.model.json` |
| 演出服·武士道的精神（R） | `018_costume.model.json` |
| 演出服·模特模式（SR） | `019_costume.model.json` |
| 演出服·满含心意的花束（SR） | `020_costume.model.json` |
| 演出服·认真・无念无想（R） | `021_costume.model.json` |
| 演出服·Pastel Maid（R） | `022_costume.model.json` |
| 演出服·最周全的招待（SSR） | `023_costume.model.json` |
| 演出服·第一次捣年糕（SSR） | `024_costume.model.json` |
| 演出服·流行的发型（SR） | `025_costume.model.json` |
| 演出服·不屈的剑士（SR） | `026_costume.model.json` |
| 演出服·属于我的武士道！（SSR） | `027_costume.model.json` |
| 演出服·想要一起分担！（SR） | `028_costume.model.json` |
| 演出服·海边的姿态（SSR） | `029_costume.model.json` |
| 演出服·可爱的吸血鬼（R） | `030_costume.model.json` |
| 演出服·偶然发现的珍品（SR） | `031_costume.model.json` |
| 演出服·不够在行的人（SSR） | `032_costume.model.json` |
| 演出服·一刀两断！（SR） | `033_costume.model.json` |
| 演出服·绽放于新娘手中的幸福（SSR） | `034_costume.model.json` |
| 演出服·沙滩天堂（R） | `035_costume.model.json` |
| 演出服·我们的奢侈时间（SSR） | `036_costume.model.json` |
| 演出服·农场风格（R） | `037_costume.model.json` |
| 演出服·描绘的舞台（SSR） | `038_costume.model.json` |
| 演出服·在河边找到的宝物（SR） | `039_costume.model.json` |
| 演出服·装饰完成！（SR） | `040_costume.model.json` |
| 演出服·兴高采烈（SR） | `041_costume.model.json` |
| 演出服·友爱之伞（SSR） | `042_costume.model.json` |
| 演出服·偶像前辈（R） | `043_costume.model.json` |
| 演出服·通过这双手（SR） | `044_costume.model.json` |
| 演出服·天真的期待（SR） | `045_costume.model.json` |
| 演出服·请将我的声音（SSR） | `046_costume.model.json` |
| 演出服·宇宙船员（R） | `047_costume.model.json` |
| 演出服·武士僵尸（SR） | `048_costume.model.json` |
| 演出服·托盘达人（SR） | `049_costume.model.json` |
| 演出服·偶像大追踪（SSR） | `050_costume.model.json` |
| 演出服·哈！小心考试（SR） | `051_costume.model.json` |
| 演出服·想要支持同伴的信念（SSR） | `052_costume.model.json` |
| 演出服·请交给我！（SR） | `053_costume.model.json` |
| 演出服·成束的真挚祝福（R） | `054_costume.model.json` |
| 演出服·刨冰的精华所在（SR） | `055_costume.model.json` |
| 演出服·蝴蝶飞舞的茶会（SSR） | `056_costume.model.json` |
| 演出服·紧紧拥抱（SSR） | `057_costume.model.json` |
| 演出服·祝来访者福如东海（SR） | `058_costume.model.json` |
| 演出服·心跳加速！？兜风（SR） | `059_costume.model.json` |
| 演出服·呐喊吧，青春当下（UR） | `060_costume.model.json` |
| 演出服·忧郁紫色（R） | `061_costume.model.json` |
| 演出服·绝不让步的信念（UR） | `062_costume.model.json` |
| 演出服·转圈圈♪（SR） | `063_costume.model.json` |
| 演出服·小小的海中宝物（UR） | `064_costume.model.json` |
| 演出服·充满感谢和欣喜（SSR） | `065_costume.model.json` |
| 演出服·将特别的一天献给你（UR） | `066_costume.model.json` |
| 演出服·令人兴奋的出行（R） | `067_costume.model.json` |
| 演出服·猜谜小课堂（SR） | `068_costume.model.json` |
| 演出服·兴奋的试穿时间（UR） | `069_costume.model.json` |
| 演出服·幸福满满的年糕小豆汤（SSR） | `070_costume.model.json` |
| 演出服·寻觅话语（SSR） | `071_costume.model.json` |
| 演出服·加上Hashtag（UR） | `072_costume.model.json` |
| 演出服·眺望杜之都（SSR） | `073_costume.model.json` |
| 演出服·前往辉煌的舞台 | `074_costume.model.json` |
| 演出服·照亮梦想 | `075_costume.model.json` |
| 演出服·盛放的声援 | `076_costume.model.json` |
| 演出服·梦色婚礼 | `077_costume.model.json` |
| 演出服·牡丹褶边 | `078_costume.model.json` |
| 演出服·武士要惺惺相惜 | `079_costume.model.json` |
| 活动·梦想祭·憧憬无法隐藏 | `080_costume.model.json` |
| 活动·梦想祭·枝形吊灯路 | `081_costume.model.json` |
| 活动·梦想祭·独枝匿于幽邃间（UR） | `082_costume.model.json` |
| 活动·梦想祭·自然微笑（UR） | `083_costume.model.json` |
| 活动·梦想祭·浮现的七彩，轻飘于空（UR） | `084_costume.model.json` |
| 活动·5周年特别服 | `085_costume.model.json` |
| 剧情·活动024剧情02 | `086_costume.model.json` |
| 剧情·活动38剧情01 | `087_costume.model.json` |
| 剧情·活动50剧情01 | `088_costume.model.json` |
| 剧情·活动65剧情01 | `089_costume.model.json` |
| 剧情·活动80剧情01 | `090_costume.model.json` |
| 剧情·活动104剧情01 | `091_costume.model.json` |
| 剧情·活动143剧情01 | `092_costume.model.json` |
| 剧情·活动154剧情01 | `093_costume.model.json` |
| 剧情·活动154剧情02 | `094_costume.model.json` |
| 剧情·活动195剧情01 | `095_costume.model.json` |
| 剧情·活动216剧情01 | `096_costume.model.json` |
| 剧情·活动278剧情01 | `097_costume.model.json` |
| 剧情·剧情01 | `098_costume.model.json` |
| 剧情·剧情01（2023） | `099_costume.model.json` |
| 季节·2018狗年 | `100_costume.model.json` |
| 季节·2018振袖 | `101_costume.model.json` |
| 季节·夏日水手服 | `102_costume.model.json` |
| 季节·泳装2023 | `103_costume.model.json` |
| 季节·浴衣2023 | `104_costume.model.json` |
| 生日·2021 | `105_costume.model.json` |
| 生日·2022 | `106_costume.model.json` |
| 联动·湊阿库娅（hololive） | `107_costume.model.json` |
| 其他·2021愚人节 | `108_costume.model.json` |
| 其他·机关小丑 | `109_costume.model.json` |
| 其他·Garupa T恤 | `110_costume.model.json` |

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
