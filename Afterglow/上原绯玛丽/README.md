# 上原绯玛丽（Garupa）

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
