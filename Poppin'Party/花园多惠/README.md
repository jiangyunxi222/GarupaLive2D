# 花园多惠（Garupa）

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
| 常服·打工（活动287） | `002_costume.model.json` |
| 常服·咖啡厅 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 校服·体操服 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·夏季2023 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季2023 | `014_costume.model.json` |
| 演出服·穿着睡衣来叨扰（SSR） | `015_costume.model.json` |
| 演出服·兔子大作战（SR） | `016_costume.model.json` |
| 演出服·只要牵起双手（SR） | `017_costume.model.json` |
| 演出服·叼面包赛跑！（SR） | `018_costume.model.json` |
| 演出服·长胡子的圣诞老人（R） | `019_costume.model.json` |
| 演出服·一心向前（SSR） | `020_costume.model.json` |
| 演出服·过晌的汉堡肉饼（SR） | `021_costume.model.json` |
| 演出服·作为奖励的西瓜（SR） | `022_costume.model.json` |
| 演出服·看起来像兔子（SSR） | `023_costume.model.json` |
| 演出服·送上声援（R） | `024_costume.model.json` |
| 演出服·引以为傲的才艺展示（SR） | `025_costume.model.json` |
| 演出服·映照于玻璃前的你（SSR） | `026_costume.model.json` |
| 演出服·新舞台（R） | `027_costume.model.json` |
| 演出服·期待的新星主持人（SR） | `028_costume.model.json` |
| 演出服·重要的回忆录（SSR） | `029_costume.model.json` |
| 演出服·万圣节兔子（R） | `030_costume.model.json` |
| 演出服·杰作的预感（SR） | `031_costume.model.json` |
| 演出服·重归于好的证明（SSR） | `032_costume.model.json` |
| 演出服·马口铁兔子（SR） | `033_costume.model.json` |
| 演出服·其乐融融Level Up♪（SR） | `034_costume.model.json` |
| 演出服·奔放的声音（R） | `035_costume.model.json` |
| 演出服·在人鱼之家晒太阳☆（SSR） | `036_costume.model.json` |
| 演出服·兔子小屋介绍（R） | `037_costume.model.json` |
| 演出服·魅惑的香味（SSR） | `038_costume.model.json` |
| 演出服·特别拍摄（SR） | `039_costume.model.json` |
| 演出服·震撼心灵的声音（SR） | `040_costume.model.json` |
| 演出服·出航！水手（R） | `041_costume.model.json` |
| 演出服·第一次合奏（SSR） | `042_costume.model.json` |
| 演出服·与粉丝邂逅（SR） | `043_costume.model.json` |
| 演出服·花园流电吉他讲座（SSR） | `044_costume.model.json` |
| 演出服·阁楼日记 | `045_costume.model.json` |
| 演出服·文化节的味道是？（SSR） | `046_costume.model.json` |
| 演出服·能量充电中！（SSR） | `047_costume.model.json` |
| 演出服·朝气蓬勃的光明 | `048_costume.model.json` |
| 演出服·寻找更好的声音（UR） | `049_costume.model.json` |
| 演出服·我能做好吗？（SSR） | `050_costume.model.json` |
| 演出服·蛀牙患者的忧郁（UR） | `051_costume.model.json` |
| 演出服·奔跑在春天里（UR） | `052_costume.model.json` |
| 演出服·台阶的尽头（SR） | `053_costume.model.json` |
| 演出服·如果你的梦想在闪耀（UR） | `054_costume.model.json` |
| 演出服·贴着滚烫的脸颊（R） | `055_costume.model.json` |
| 演出服·我们闪耀的地方（R） | `056_costume.model.json` |
| 演出服·不可思议的向导（UR） | `057_costume.model.json` |
| 演出服·果然很奇怪啊（SR） | `058_costume.model.json` |
| 演出服·不期而遇的小确幸（UR） | `059_costume.model.json` |
| 演出服·纪念之蓝（R） | `060_costume.model.json` |
| 演出服·你终将跑过的天空（UR） | `061_costume.model.json` |
| 演出服·绽放的笑容与花朵（R） | `062_costume.model.json` |
| 演出服·秘密作战会议（SSR） | `063_costume.model.json` |
| 演出服·热血彩排（UR） | `064_costume.model.json` |
| 演出服·街角兔子发现录（SR） | `065_costume.model.json` |
| 演出服·Colorful Poppin！ | `066_costume.model.json` |
| 演出服·Cheerful Star☆ | `067_costume.model.json` |
| 演出服·Peaceful Jump！ | `068_costume.model.json` |
| 演出服·星光闪耀的日常 | `069_costume.model.json` |
| 演出服·Miracle☆Poppin | `070_costume.model.json` |
| 演出服·大家的歌 | `071_costume.model.json` |
| 演出服·幸福的共享 | `072_costume.model.json` |
| 活动·梦想祭·强制带走 | `073_costume.model.json` |
| 活动·梦想祭·宁静的海，轻拂的风 | `074_costume.model.json` |
| 活动·梦想祭·这里只有我一人（UR） | `075_costume.model.json` |
| 活动·梦想祭·在新绿中驰骋。（UR） | `076_costume.model.json` |
| 活动·闪耀祭·夏日，跨越道口 | `077_costume.model.json` |
| 活动·Poppin'Party Fes | `078_costume.model.json` |
| 活动·5周年特别服 | `079_costume.model.json` |
| 剧情·第0章Live | `080_costume.model.json` |
| 剧情·第0章睡衣 | `081_costume.model.json` |
| 剧情·活动50剧情01 | `082_costume.model.json` |
| 剧情·活动99剧情01 | `083_costume.model.json` |
| 剧情·活动99剧情02 | `084_costume.model.json` |
| 剧情·活动102剧情01 | `085_costume.model.json` |
| 剧情·活动119剧情01 | `086_costume.model.json` |
| 剧情·活动140剧情01 | `087_costume.model.json` |
| 剧情·活动160剧情01 | `088_costume.model.json` |
| 剧情·活动166剧情01 | `089_costume.model.json` |
| 剧情·活动216剧情01 | `090_costume.model.json` |
| 剧情·活动233剧情01 | `091_costume.model.json` |
| 季节·2018狗年 | `092_costume.model.json` |
| 季节·2019振袖 | `093_costume.model.json` |
| 季节·圣诞01 | `094_costume.model.json` |
| 季节·夏日水手服 | `095_costume.model.json` |
| 季节·泳装2023 | `096_costume.model.json` |
| 季节·浴衣 | `097_costume.model.json` |
| 生日·2021 | `098_costume.model.json` |
| 生日·2022 | `099_costume.model.json` |
| 联动·时乃空（hololive） | `100_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `101_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `102_costume.model.json` |
| 其他·2021愚人节 | `103_costume.model.json` |
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
