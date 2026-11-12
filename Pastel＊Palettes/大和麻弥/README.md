# 大和麻弥（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 角色菜单

双击本角色文件夹中的 `ControlPanel/OpenMenu.cmd`。页面、预览和桌面菜单均随角色提供，Windows 无需另装 Python。

- 腿部菜单使用半透明圆角浮层，以角色身体中线居中。字体优先使用华文行楷，按系统字体情况回退到楷体。
- 「打开面板」进入完整页面，动作、表情、衣装、语音和❤收藏通过平面标签切换。
- 动作、语音和换装循环均可选择全部或❤收藏，设置随机或按列表顺序及各自间隔。
- 动作与语音间隔从播放完成后计算。换装间隔为最短停留时间，换装会等待当前动作和语音结束，再恢复循环。
- 「恢复待机」停止全部循环、动作和语音，清除表情、字幕及保持状态。
- 字幕开关与「身体互动仅❤」独立设置，衣装与语音收藏在角色内共享，动作与表情收藏按衣装保存。
- 桌面浮层和循环由角色面板后台统一执行。关闭浏览器后，后台程序继续运行。
- 启动 Live2DViewerEX 后，点击页面「连接桌面」。桌面换装会同步页面，连接中断后自动尝试恢复。

更新后请完整重载 `00_integrated` 主入口。角色文件夹整体移动时，需一同保留 `ControlPanel` 与 `assets`。

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
| 常服·练习服 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·夏季S2 | `012_costume.model.json` |
| 校服·夏季V3 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季S2 | `015_costume.model.json` |
| 演出服·与爵士鼓的邂逅（R） | `016_costume.model.json` |
| 演出服·感动的泪水（SR） | `017_costume.model.json` |
| 演出服·两人的协助者（R） | `018_costume.model.json` |
| 演出服·认真・幸存者（SSR） | `019_costume.model.json` |
| 演出服·记者的工作（SR） | `020_costume.model.json` |
| 演出服·果断挑战（SSR） | `021_costume.model.json` |
| 演出服·谦虚系偶像（R） | `022_costume.model.json` |
| 演出服·发现宝藏！（SSR） | `023_costume.model.json` |
| 演出服·心动节拍（R） | `024_costume.model.json` |
| 演出服·所谓偶像（SR） | `025_costume.model.json` |
| 演出服·甜蜜猫咪（SR） | `026_costume.model.json` |
| 演出服·舞台导演（SSR） | `027_costume.model.json` |
| 演出服·理想与现实（SSR） | `028_costume.model.json` |
| 演出服·令人感动的赏花（R） | `029_costume.model.json` |
| 演出服·高端技术（SR） | `030_costume.model.json` |
| 演出服·共同编织的声音（SSR） | `031_costume.model.json` |
| 演出服·海里的水族馆（SR） | `032_costume.model.json` |
| 演出服·为了新的尝试（SR） | `033_costume.model.json` |
| 演出服·女孩快照（SR） | `034_costume.model.json` |
| 演出服·高贵的鼓手（R） | `035_costume.model.json` |
| 演出服·来回火吧☆（SSR） | `036_costume.model.json` |
| 演出服·我来提供支援！（R） | `037_costume.model.json` |
| 演出服·爽快的突然袭击（SR） | `038_costume.model.json` |
| 演出服·按照自己的风格去享受（SSR） | `039_costume.model.json` |
| 演出服·致所有人（SSR） | `040_costume.model.json` |
| 演出服·智将×偶像（R） | `041_costume.model.json` |
| 演出服·准备已万无一失！（SSR） | `042_costume.model.json` |
| 演出服·宇宙领航员（R） | `043_costume.model.json` |
| 演出服·呼嘿嘿僵尸（SR） | `044_costume.model.json` |
| 演出服·幕后的温柔光辉（SSR） | `045_costume.model.json` |
| 演出服·想要介绍的事物（SR） | `046_costume.model.json` |
| 演出服·意外的强敌（SR） | `047_costume.model.json` |
| 演出服·像你一样（SSR） | `048_costume.model.json` |
| 演出服·Best wishes！（SSR） | `049_costume.model.json` |
| 演出服·被祭典氛围所吸引 | `050_costume.model.json` |
| 演出服·所以，音乐就是（SSR） | `051_costume.model.json` |
| 演出服·紧张的选择（SR） | `052_costume.model.json` |
| 演出服·即使没有言语（SR） | `053_costume.model.json` |
| 演出服·温暖宜出行 | `054_costume.model.json` |
| 演出服·毕业（SSR） | `055_costume.model.json` |
| 演出服·将要开始的故事（UR） | `056_costume.model.json` |
| 演出服·可能性为∞（UR） | `057_costume.model.json` |
| 演出服·奔向的终点是（SSR） | `058_costume.model.json` |
| 演出服·高傲的骑士（R） | `059_costume.model.json` |
| 演出服·属于你的地方（UR） | `060_costume.model.json` |
| 演出服·心满意足的信息（SR） | `061_costume.model.json` |
| 演出服·朝阳照耀的时刻（UR） | `062_costume.model.json` |
| 演出服·圣诞PasPale（R） | `063_costume.model.json` |
| 演出服·可靠的司机（SSR） | `064_costume.model.json` |
| 演出服·透彻的解读（UR） | `065_costume.model.json` |
| 演出服·干劲满满的发表会（SSR） | `066_costume.model.json` |
| 演出服·魅惑的团子（R） | `067_costume.model.json` |
| 演出服·心意相通的瞬间（UR） | `068_costume.model.json` |
| 演出服·注视着的温度（SR） | `069_costume.model.json` |
| 演出服·一句句令人欣喜的话语（UR） | `070_costume.model.json` |
| 演出服·不断延展的梦想（SR） | `071_costume.model.json` |
| 演出服·前往辉煌的舞台 | `072_costume.model.json` |
| 演出服·照亮梦想 | `073_costume.model.json` |
| 演出服·盛放的声援 | `074_costume.model.json` |
| 演出服·梦色婚礼 | `075_costume.model.json` |
| 演出服·牡丹褶边 | `076_costume.model.json` |
| 演出服·平时的姿态 | `077_costume.model.json` |
| 活动·梦想祭·开始练习！ | `078_costume.model.json` |
| 活动·梦想祭·淘气地玩水 | `079_costume.model.json` |
| 活动·梦想祭·车辆休整时间（UR） | `080_costume.model.json` |
| 活动·梦想祭·沐浴朝霞（UR） | `081_costume.model.json` |
| 活动·5周年特别服 | `082_costume.model.json` |
| 剧情·活动33剧情01 | `083_costume.model.json` |
| 剧情·活动45剧情01 | `084_costume.model.json` |
| 剧情·活动86剧情01 | `085_costume.model.json` |
| 剧情·活动104剧情01 | `086_costume.model.json` |
| 剧情·活动119剧情01 | `087_costume.model.json` |
| 剧情·活动154剧情01 | `088_costume.model.json` |
| 剧情·活动154剧情02 | `089_costume.model.json` |
| 剧情·活动195剧情01 | `090_costume.model.json` |
| 剧情·活动216剧情01 | `091_costume.model.json` |
| 剧情·活动226剧情01 | `092_costume.model.json` |
| 剧情·活动278剧情01 | `093_costume.model.json` |
| 剧情·剧情01 | `094_costume.model.json` |
| 剧情·剧情01（2023） | `095_costume.model.json` |
| 季节·2018狗年 | `096_costume.model.json` |
| 季节·2018振袖 | `097_costume.model.json` |
| 季节·夏日水手服 | `098_costume.model.json` |
| 生日·2021 | `099_costume.model.json` |
| 生日·2022 | `100_costume.model.json` |
| 联动·湊阿库娅（hololive） | `101_costume.model.json` |
| 其他·Garupa T恤 | `102_costume.model.json` |
| 其他·机关小丑 | `103_costume.model.json` |

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
