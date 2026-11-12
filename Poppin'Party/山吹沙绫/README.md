# 山吹沙绫（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服·咖啡厅 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 常服·睡衣2023 | `010_costume.model.json` |
| 校服·体操服 | `011_costume.model.json` |
| 校服·夏季 | `012_costume.model.json` |
| 校服·夏季2023 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季2023 | `015_costume.model.json` |
| 演出服·加油面包（SR） | `016_costume.model.json` |
| 演出服·一日限定的新娘（SR） | `017_costume.model.json` |
| 演出服·温柔的慰问品（R） | `018_costume.model.json` |
| 演出服·夕阳下的更衣准备（SSR） | `019_costume.model.json` |
| 演出服·Merry・Surprise!（SSR） | `020_costume.model.json` |
| 演出服·带有许多回忆的物品（SR） | `021_costume.model.json` |
| 演出服·沙绫的告白（SR） | `022_costume.model.json` |
| 演出服·人偶秀（SR） | `023_costume.model.json` |
| 演出服·闪亮的笑容（SSR） | `024_costume.model.json` |
| 演出服·将安宁赠予友人（SSR） | `025_costume.model.json` |
| 演出服·点缀（R） | `026_costume.model.json` |
| 演出服·招牌员工（SSR） | `027_costume.model.json` |
| 演出服·充满回忆的道路（SR） | `028_costume.model.json` |
| 演出服·惊喜礼物（SR） | `029_costume.model.json` |
| 演出服·自然状态的我（SR） | `030_costume.model.json` |
| 演出服·姐姐是魔女（SSR） | `031_costume.model.json` |
| 演出服·正在收集玩具！（SR） | `032_costume.model.json` |
| 演出服·记录下无数个瞬间（SSR） | `033_costume.model.json` |
| 演出服·雨天的野餐♪（SSR） | `034_costume.model.json` |
| 演出服·似曾相识的人影（SR） | `035_costume.model.json` |
| 演出服·相连的羁绊（SSR） | `036_costume.model.json` |
| 演出服·白巧克力海螺包（R） | `037_costume.model.json` |
| 演出服·心情激动的时刻（SSR） | `038_costume.model.json` |
| 演出服·Popipa的优点（SR） | `039_costume.model.json` |
| 演出服·清爽的休假（R） | `040_costume.model.json` |
| 演出服·波子汽水瓶里的回忆（SSR） | `041_costume.model.json` |
| 演出服·加油・海螺包（SR） | `042_costume.model.json` |
| 演出服·愉快的聊天（SR） | `043_costume.model.json` |
| 演出服·朝霞中的优美歌声（SSR） | `044_costume.model.json` |
| 演出服·怀旧的棕褐色 | `045_costume.model.json` |
| 演出服·棱镜·流星 | `046_costume.model.json` |
| 演出服·某时的蓝天（SSR） | `047_costume.model.json` |
| 演出服·为声音提供支援的工作（SSR） | `048_costume.model.json` |
| 演出服·装满口袋的Enjoy（SSR） | `049_costume.model.json` |
| 演出服·站在热闹的桥上（UR） | `050_costume.model.json` |
| 演出服·越狱者（R） | `051_costume.model.json` |
| 演出服·无私的陪伴者（SSR） | `052_costume.model.json` |
| 演出服·那些鲜花盛放的未来（R） | `053_costume.model.json` |
| 演出服·感受未来的悸动（UR） | `054_costume.model.json` |
| 演出服·食欲和心灵都得到满足（SR） | `055_costume.model.json` |
| 演出服·复古♡少女感（R） | `056_costume.model.json` |
| 演出服·去寻找新年气息（UR） | `057_costume.model.json` |
| 演出服·春天的山吹面包节（SR） | `058_costume.model.json` |
| 演出服·向我伸来的手（UR） | `059_costume.model.json` |
| 演出服·定格美好瞬间（SR） | `060_costume.model.json` |
| 演出服·通往明天的旅行（R） | `061_costume.model.json` |
| 演出服·作战大成功！（SR） | `062_costume.model.json` |
| 演出服·这就是我的声音！（UR） | `063_costume.model.json` |
| 演出服·那时的温暖（UR） | `064_costume.model.json` |
| 演出服·超大声援！（SSR） | `065_costume.model.json` |
| 演出服·Colorful Poppin！ | `066_costume.model.json` |
| 演出服·Cheerful Star☆ | `067_costume.model.json` |
| 演出服·Peaceful Jump！ | `068_costume.model.json` |
| 演出服·星光闪耀的日常 | `069_costume.model.json` |
| 演出服·Miracle☆Poppin | `070_costume.model.json` |
| 演出服·宝贵的时间 | `071_costume.model.json` |
| 演出服·配对的发圈 | `072_costume.model.json` |
| 活动·第4回总选举（R） | `073_costume.model.json` |
| 活动·梦想祭·CiRCLE面包祭 | `074_costume.model.json` |
| 活动·梦想祭·对太阳公公挥手 | `075_costume.model.json` |
| 活动·梦想祭·这个挺可爱的♪（UR） | `076_costume.model.json` |
| 活动·梦想祭·被温暖的雪包围（UR） | `077_costume.model.json` |
| 活动·活动09 | `078_costume.model.json` |
| 活动·Poppin'Party Fes | `079_costume.model.json` |
| 活动·5周年特别服 | `080_costume.model.json` |
| 剧情·第0章Live | `081_costume.model.json` |
| 剧情·第0章睡衣 | `082_costume.model.json` |
| 剧情·活动92剧情01 | `083_costume.model.json` |
| 剧情·活动108剧情01 | `084_costume.model.json` |
| 剧情·活动119剧情01 | `085_costume.model.json` |
| 剧情·活动160剧情01 | `086_costume.model.json` |
| 剧情·活动216剧情01 | `087_costume.model.json` |
| 剧情·活动236剧情01 | `088_costume.model.json` |
| 季节·2018狗年 | `089_costume.model.json` |
| 季节·2019振袖 | `090_costume.model.json` |
| 季节·2025振袖 | `091_costume.model.json` |
| 季节·圣诞01 | `092_costume.model.json` |
| 季节·夏日水手服 | `093_costume.model.json` |
| 季节·浴衣 | `094_costume.model.json` |
| 生日·2021 | `095_costume.model.json` |
| 生日·2022 | `096_costume.model.json` |
| 联动·时乃空（hololive） | `097_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `098_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `099_costume.model.json` |
| 其他·2021愚人节 | `100_costume.model.json` |
| 其他·CHiSPA | `101_costume.model.json` |
| 其他·Garupa T恤 | `102_costume.model.json` |

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
