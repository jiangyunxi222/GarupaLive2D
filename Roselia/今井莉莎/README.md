# 今井莉莎（Garupa）

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
| 常服·商店 | `008_costume.model.json` |
| 常服·商店2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季S2 | `011_costume.model.json` |
| 校服·夏季V3 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季S2 | `014_costume.model.json` |
| 演出服·守望思念（R） | `015_costume.model.json` |
| 演出服·不可或缺的存在（SR） | `016_costume.model.json` |
| 演出服·情牵两人（R） | `017_costume.model.json` |
| 演出服·耀眼的艳阳（SSR） | `018_costume.model.json` |
| 演出服·罗曼蒂克（R） | `019_costume.model.json` |
| 演出服·不可缺少的存在（R） | `020_costume.model.json` |
| 演出服·认真地挑战（SSR） | `021_costume.model.json` |
| 演出服·新手治疗术士（SR） | `022_costume.model.json` |
| 演出服·甜点制作交给我吧（SSR） | `023_costume.model.json` |
| 演出服·再度制作饼干（SSR） | `024_costume.model.json` |
| 演出服·幽灵什么的绝对不行！（SR） | `025_costume.model.json` |
| 演出服·盛夏的日光（SR） | `026_costume.model.json` |
| 演出服·交流能力MAX（SSR） | `027_costume.model.json` |
| 演出服·挑战书（SR） | `028_costume.model.json` |
| 演出服·星光闪烁（R） | `029_costume.model.json` |
| 演出服·担心过头？（R） | `030_costume.model.json` |
| 演出服·勉强赶上的赏花（SR） | `031_costume.model.json` |
| 演出服·起始的演奏会（SSR） | `032_costume.model.json` |
| 演出服·看不见，但是没关系（SR） | `033_costume.model.json` |
| 演出服·缩短的距离（SSR） | `034_costume.model.json` |
| 演出服·幻想万岁！（SR） | `035_costume.model.json` |
| 演出服·笑容绽放（SSR） | `036_costume.model.json` |
| 演出服·必然的联系（SR） | `037_costume.model.json` |
| 演出服·沐浴在欢呼声中（SSR） | `038_costume.model.json` |
| 演出服·有线索了？（SR） | `039_costume.model.json` |
| 演出服·感受异世界风情（SSR） | `040_costume.model.json` |
| 演出服·乐于照顾人的公主（R） | `041_costume.model.json` |
| 演出服·STOP！（SR） | `042_costume.model.json` |
| 演出服·试探的目光（SR） | `043_costume.model.json` |
| 演出服·蔓延的恐惧之环（SSR） | `044_costume.model.json` |
| 演出服·这就是命运！（SSR） | `045_costume.model.json` |
| 演出服·我可以相信吗？（SR） | `046_costume.model.json` |
| 演出服·被充满期待的眼眸注视（SSR） | `047_costume.model.json` |
| 演出服·触碰动摇的心情（SR） | `048_costume.model.json` |
| 演出服·温柔的坏心眼（SR） | `049_costume.model.json` |
| 演出服·璀璨的前奏（SSR） | `050_costume.model.json` |
| 演出服·海风中描绘的心意（SR） | `051_costume.model.json` |
| 演出服·优雅的玫红 | `052_costume.model.json` |
| 演出服·Say cheese！（SSR） | `053_costume.model.json` |
| 演出服·观众的声音和表情 | `054_costume.model.json` |
| 演出服·这首曲子结束之后（SR） | `055_costume.model.json` |
| 演出服·毕业（SSR） | `056_costume.model.json` |
| 演出服·彻底地调查？（SSR） | `057_costume.model.json` |
| 演出服·夏日飞溅！（UR） | `058_costume.model.json` |
| 演出服·找不到的答案（SR） | `059_costume.model.json` |
| 演出服·阳春时节的闪亮盛装（UR） | `060_costume.model.json` |
| 演出服·远去的背影（UR） | `061_costume.model.json` |
| 演出服·在你身旁编织花朵（UR） | `062_costume.model.json` |
| 演出服·编织秋意（R） | `063_costume.model.json` |
| 演出服·水流声中洒落的笑容（UR） | `064_costume.model.json` |
| 演出服·『别担心』之类的话（SR） | `065_costume.model.json` |
| 演出服·欣喜的评价（SR） | `066_costume.model.json` |
| 演出服·花与星闪耀之地（SSR） | `067_costume.model.json` |
| 演出服·豪华阵容（SR） | `068_costume.model.json` |
| 演出服·一起来装饰吧！（UR） | `069_costume.model.json` |
| 演出服·DEAR MY LIKE（UR） | `070_costume.model.json` |
| 演出服·约定之地（SSR） | `071_costume.model.json` |
| 演出服·她所选择的未来（UR） | `072_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `073_costume.model.json` |
| 演出服·Noble・Rose | `074_costume.model.json` |
| 演出服·崇高志向 | `075_costume.model.json` |
| 演出服·环伊甸园 | `076_costume.model.json` |
| 演出服·神秘花束 | `077_costume.model.json` |
| 演出服·努力的痕迹 | `078_costume.model.json` |
| 活动·第2回总选举（R） | `079_costume.model.json` |
| 活动·第3回总选举（R） | `080_costume.model.json` |
| 活动·梦想祭·团结一心 | `081_costume.model.json` |
| 活动·梦想祭·今后也要一起 | `082_costume.model.json` |
| 活动·梦想祭·不再穿制服的早晨（UR） | `083_costume.model.json` |
| 活动·梦想祭·樱影中摇曳的光（UR） | `084_costume.model.json` |
| 活动·奇幻冒险 | `085_costume.model.json` |
| 活动·5周年特别服 | `086_costume.model.json` |
| 剧情·活动52剧情01 | `087_costume.model.json` |
| 剧情·活动81剧情01 | `088_costume.model.json` |
| 剧情·活动89剧情01 | `089_costume.model.json` |
| 剧情·活动93剧情01 | `090_costume.model.json` |
| 剧情·活动105剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动128剧情01 | `093_costume.model.json` |
| 剧情·活动156剧情01 | `094_costume.model.json` |
| 剧情·活动216剧情01 | `095_costume.model.json` |
| 剧情·活动216剧情02 | `096_costume.model.json` |
| 季节·2018狗年 | `097_costume.model.json` |
| 季节·2019振袖 | `098_costume.model.json` |
| 季节·2024振袖 | `099_costume.model.json` |
| 季节·夏日水手服 | `100_costume.model.json` |
| 季节·泳装 | `101_costume.model.json` |
| 季节·泳装2023 | `102_costume.model.json` |
| 生日·2021 | `103_costume.model.json` |
| 生日·2022 | `104_costume.model.json` |
| 联动·炒作热度的专家（UR） | `105_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `106_costume.model.json` |
| 其他·2021愚人节 | `107_costume.model.json` |
| 其他·Garupa T恤 | `108_costume.model.json` |

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
