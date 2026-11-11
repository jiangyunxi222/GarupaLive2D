# 白金燐子（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 角色菜单

双击本角色文件夹中的 `打开角色菜单.cmd`。页面、预览和桌面菜单均随角色提供，Windows 无需另装 Python。

- 腿部菜单使用半透明圆角浮层，以角色身体中线居中。字体优先使用华文行楷，按系统字体情况回退到楷体。
- 「打开面板」进入完整页面，动作、表情、衣装、语音和❤收藏通过平面标签切换。
- 动作、语音和换装循环均可选择全部或❤收藏，设置随机或按列表顺序及各自间隔。
- 动作与语音间隔从播放完成后计算。换装间隔为最短停留时间，换装会等待当前动作和语音结束，再恢复循环。
- 「恢复待机」停止全部循环、动作和语音，清除表情、字幕及保持状态。
- 字幕开关与「身体互动仅❤」独立设置，衣装与语音收藏在角色内共享，动作与表情收藏按衣装保存。
- 桌面浮层和循环由角色面板后台统一执行。关闭浏览器后，后台程序继续运行。
- 启动 Live2DViewerEX 后，点击页面「连接桌面」。桌面换装会同步页面，连接中断后自动尝试恢复。

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
| 校服·夏季 | `008_costume.model.json` |
| 校服·冬季 | `009_costume.model.json` |
| 校服·冬季V3 | `010_costume.model.json` |
| 演出服·纯粹的热情（SSR） | `011_costume.model.json` |
| 演出服·不习惯的电话（SSR） | `012_costume.model.json` |
| 演出服·大家挑选的泳衣（SR） | `013_costume.model.json` |
| 演出服·些许的担忧（R） | `014_costume.model.json` |
| 演出服·Blue Rose Maid（R） | `015_costume.model.json` |
| 演出服·可爱的盛装（SR） | `016_costume.model.json` |
| 演出服·孤高的巫师（SSR） | `017_costume.model.json` |
| 演出服·临时社团成员（SSR） | `018_costume.model.json` |
| 演出服·下定决心的呼声（SR） | `019_costume.model.json` |
| 演出服·河滨的人鱼（R） | `020_costume.model.json` |
| 演出服·舞台服装（SSR） | `021_costume.model.json` |
| 演出服·隐秘的斗志（R） | `022_costume.model.json` |
| 演出服·甜蜜的目光（SR） | `023_costume.model.json` |
| 演出服·我与钢琴（SSR） | `024_costume.model.json` |
| 演出服·向着出色的学生会长（SSR） | `025_costume.model.json` |
| 演出服·优雅的调查（SR） | `026_costume.model.json` |
| 演出服·藏在内心深处的热情（R） | `027_costume.model.json` |
| 演出服·终将来临的未来（SSR） | `028_costume.model.json` |
| 演出服·抓住的荣光（SSR） | `029_costume.model.json` |
| 演出服·抵达的目的地（SR） | `030_costume.model.json` |
| 演出服·我来弹奏一曲吧？（R） | `031_costume.model.json` |
| 演出服·咏唱于战场的新娘（SSR） | `032_costume.model.json` |
| 演出服·传达的音色（SSR） | `033_costume.model.json` |
| 演出服·音调印象（SR） | `034_costume.model.json` |
| 演出服·慌张少女（SR） | `035_costume.model.json` |
| 演出服·属于自己的答案（SSR） | `036_costume.model.json` |
| 演出服·置身于新世界（SR） | `037_costume.model.json` |
| 演出服·参加派对的邀请（R） | `038_costume.model.json` |
| 演出服·坚持战斗的学生会长（SSR） | `039_costume.model.json` |
| 演出服·涂抹心意（SSR） | `040_costume.model.json` |
| 演出服·未曾体会的欢喜（SR） | `041_costume.model.json` |
| 演出服·享受旅行（R） | `042_costume.model.json` |
| 演出服·拥抱那音色（SSR） | `043_costume.model.json` |
| 演出服·令人平静的归途（SR） | `044_costume.model.json` |
| 演出服·即使无法重演（SSR） | `045_costume.model.json` |
| 演出服·收下我的声援（SR） | `046_costume.model.json` |
| 演出服·开始『今天』的声音 | `047_costume.model.json` |
| 演出服·毕业（SSR） | `048_costume.model.json` |
| 演出服·身上穿的是……（UR） | `049_costume.model.json` |
| 演出服·流星新娘（R） | `050_costume.model.json` |
| 演出服·海风与太阳（UR） | `051_costume.model.json` |
| 演出服·午夜礼服（R） | `052_costume.model.json` |
| 演出服·两个人制作的友情巧克力（SR） | `053_costume.model.json` |
| 演出服·即使1cm也要前进（UR） | `054_costume.model.json` |
| 演出服·即便只是谈心（SSR） | `055_costume.model.json` |
| 演出服·染上绯红（SR） | `056_costume.model.json` |
| 演出服·原原本本的魅力（UR） | `057_costume.model.json` |
| 演出服·被深红色所渲染（R） | `058_costume.model.json` |
| 演出服·我的世界第一（UR） | `059_costume.model.json` |
| 演出服·暮色中的誓言（SSR） | `060_costume.model.json` |
| 演出服·红宝石熠熠生辉（UR） | `061_costume.model.json` |
| 演出服·一心向前（UR） | `062_costume.model.json` |
| 演出服·Blanc Resonance（R） | `063_costume.model.json` |
| 演出服·纯洁高贵（R） | `064_costume.model.json` |
| 演出服·True brillante（UR） | `065_costume.model.json` |
| 演出服·重叠的蓝色蔷薇 | `066_costume.model.json` |
| 演出服·Noble・Rose | `067_costume.model.json` |
| 演出服·崇高志向 | `068_costume.model.json` |
| 演出服·环伊甸园 | `069_costume.model.json` |
| 演出服·神秘花束 | `070_costume.model.json` |
| 演出服·我该怎么办… | `071_costume.model.json` |
| 活动·第3回总选举（R） | `072_costume.model.json` |
| 活动·梦想祭·愉悦的旋律 | `073_costume.model.json` |
| 活动·梦想祭·旧书店巡礼 | `074_costume.model.json` |
| 活动·梦想祭·星夜中的野餐（UR） | `075_costume.model.json` |
| 活动·梦想祭·浅粉掩映的窗边（UR） | `076_costume.model.json` |
| 活动·奇幻冒险 | `077_costume.model.json` |
| 活动·5周年特别服 | `078_costume.model.json` |
| 剧情·活动38剧情01 | `079_costume.model.json` |
| 剧情·活动38剧情02 | `080_costume.model.json` |
| 剧情·活动38剧情03 | `081_costume.model.json` |
| 剧情·活动52剧情01 | `082_costume.model.json` |
| 剧情·活动70剧情01 | `083_costume.model.json` |
| 剧情·活动89剧情01 | `084_costume.model.json` |
| 剧情·活动105剧情01 | `085_costume.model.json` |
| 剧情·活动116剧情01 | `086_costume.model.json` |
| 剧情·活动119剧情01 | `087_costume.model.json` |
| 剧情·活动216剧情01 | `088_costume.model.json` |
| 剧情·活动304剧情01 | `089_costume.model.json` |
| 剧情·活动342剧情01 | `090_costume.model.json` |
| 剧情·活动342剧情02 | `091_costume.model.json` |
| 剧情·活动342剧情03 | `092_costume.model.json` |
| 季节·2018狗年 | `093_costume.model.json` |
| 季节·2018振袖 | `094_costume.model.json` |
| 季节·2025振袖 | `095_costume.model.json` |
| 季节·夏日水手服 | `096_costume.model.json` |
| 季节·泳装 | `097_costume.model.json` |
| 季节·泳装2023 | `098_costume.model.json` |
| 生日·2021 | `099_costume.model.json` |
| 生日·2022 | `100_costume.model.json` |
| 联动·初音未来·右肩之蝶 | `101_costume.model.json` |
| 其他·Garupa T恤 | `102_costume.model.json` |
| 其他·NFO游戏角色 | `103_costume.model.json` |

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
