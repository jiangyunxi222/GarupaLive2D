# 仓田真白（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 角色菜单

双击本角色文件夹中的 `ControlPanel/OpenMenu.cmd`。页面、预览和桌面菜单均随角色提供，Windows 无需另装 Python。

- 腿部菜单使用半透明圆角浮层，以角色身体中线居中。字体使用随角色提供的圆体。
- 「打开面板」进入完整页面，动作、表情、衣装、语音和❤收藏通过平面标签切换。
- 动作、语音和换装循环均可选择全部或❤收藏，设置随机或按列表顺序及各自间隔。
- 动作与语音间隔从播放完成后计算。换装间隔为最短停留时间，换装会等待当前动作和语音结束，再恢复循环。
- 「恢复待机」停止全部循环、动作和语音，清除表情、字幕及保持状态，保留当前衣装。
- 字幕开关与「互动仅❤」独立设置，衣装与语音收藏在角色内共享，动作与表情收藏按衣装保存。
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
| 校服·夏季 | `009_costume.model.json` |
| 校服·夏季2023 | `010_costume.model.json` |
| 校服·冬季 | `011_costume.model.json` |
| 校服·冬季2023 | `012_costume.model.json` |
| 演出服·欢迎来到派对！（SSR） | `013_costume.model.json` |
| 演出服·热情与传达的心意（R） | `014_costume.model.json` |
| 演出服·沐浴着憧憬的光芒（SSR） | `015_costume.model.json` |
| 演出服·害羞的招牌动作（R） | `016_costume.model.json` |
| 演出服·外语的翻译方法（SR） | `017_costume.model.json` |
| 演出服·必须要说出来……！（SR） | `018_costume.model.json` |
| 演出服·让人心情激动的事（SR） | `019_costume.model.json` |
| 演出服·通过语言来表现（SSR） | `020_costume.model.json` |
| 演出服·正月赞歌（SR） | `021_costume.model.json` |
| 演出服·变成不寻常的我（SR） | `022_costume.model.json` |
| 演出服·对阵河之主（SSR） | `023_costume.model.json` |
| 演出服·欢迎来到异世界！（SSR） | `024_costume.model.json` |
| 演出服·讲究的配料（SR） | `025_costume.model.json` |
| 演出服·我的光芒照亮的道路（UR） | `026_costume.model.json` |
| 演出服·彷徨于灰色世界的蝴蝶（R） | `027_costume.model.json` |
| 演出服·夕阳的泪滴（UR） | `028_costume.model.json` |
| 演出服·挺直腰背（UR） | `029_costume.model.json` |
| 演出服·在那片天空下休憩（R） | `030_costume.model.json` |
| 演出服·勇气展翅高飞之时（UR） | `031_costume.model.json` |
| 演出服·快乐手工艺（R） | `032_costume.model.json` |
| 演出服·海上的梦幻故事（SR） | `033_costume.model.json` |
| 演出服·落入→仙境（UR） | `034_costume.model.json` |
| 演出服·变装之日（R） | `035_costume.model.json` |
| 演出服·思念朋友的夜晚（UR） | `036_costume.model.json` |
| 演出服·未来蓝图绘制中！（SSR） | `037_costume.model.json` |
| 演出服·夏天，投入「最爱」的怀抱（SSR） | `038_costume.model.json` |
| 演出服·动人心弦的旋律（SR） | `039_costume.model.json` |
| 演出服·勇敢的一步（UR） | `040_costume.model.json` |
| 演出服·一直以来支持我的人（UR） | `041_costume.model.json` |
| 演出服·心灵的色彩（R） | `042_costume.model.json` |
| 演出服·宛如星空一般（UR） | `043_costume.model.json` |
| 演出服·挑战钓水球！（UR） | `044_costume.model.json` |
| 演出服·将光辉释放向天空（SR） | `045_costume.model.json` |
| 演出服·相信・我 | `046_costume.model.json` |
| 演出服·高贵的微蓝 | `047_costume.model.json` |
| 演出服·北极星 | `048_costume.model.json` |
| 演出服·再次闪耀 | `049_costume.model.json` |
| 演出服·心跳加速的大小姐学校 | `050_costume.model.json` |
| 演出服·如今，在憧憬的地方（SSR） | `051_costume.model.json` |
| 活动·梦想祭·在萤火中见到的未来 | `052_costume.model.json` |
| 活动·梦想祭·拥抱光芒（UR） | `053_costume.model.json` |
| 活动·梦想祭·镜头前的羞涩（UR） | `054_costume.model.json` |
| 活动·闪耀祭·天蓝色的海洋 | `055_costume.model.json` |
| 活动·5周年特别服 | `056_costume.model.json` |
| 剧情·活动119剧情01 | `057_costume.model.json` |
| 剧情·活动132剧情01 | `058_costume.model.json` |
| 剧情·活动194剧情01 | `059_costume.model.json` |
| 剧情·活动203剧情01 | `060_costume.model.json` |
| 剧情·活动203剧情02 | `061_costume.model.json` |
| 剧情·活动266剧情01 | `062_costume.model.json` |
| 剧情·活动272剧情01 | `063_costume.model.json` |
| 剧情·活动340剧情01 | `064_costume.model.json` |
| 季节·2022振袖 | `065_costume.model.json` |
| 季节·2024振袖 | `066_costume.model.json` |
| 季节·泳装 | `067_costume.model.json` |
| 生日·2021 | `068_costume.model.json` |
| 生日·2022 | `069_costume.model.json` |
| 联动·bilibili联动（UR） | `070_costume.model.json` |
| 联动·甜蜜的耳语（UR） | `071_costume.model.json` |
| 联动·初音未来·深海少女 | `072_costume.model.json` |
| 其他·2021愚人节 | `073_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。

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
