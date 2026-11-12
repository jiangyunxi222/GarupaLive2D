# 二叶筑紫（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服·打工2023 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季2023 | `011_costume.model.json` |
| 校服·冬季 | `012_costume.model.json` |
| 校服·冬季2023 | `013_costume.model.json` |
| 演出服·模范队长的修养（SR） | `014_costume.model.json` |
| 演出服·早安电话（SSR） | `015_costume.model.json` |
| 演出服·名作词家·二叶筑紫（SR） | `016_costume.model.json` |
| 演出服·蝴蝶结也要绑得很完美！（SR） | `017_costume.model.json` |
| 演出服·做到了！这是实力的证明（SSR） | `018_costume.model.json` |
| 演出服·星月之夜的闪耀（R） | `019_costume.model.json` |
| 演出服·一个一个地来（SSR） | `020_costume.model.json` |
| 演出服·能够肯定自己的证明（SR） | `021_costume.model.json` |
| 演出服·交给班长吧（R） | `022_costume.model.json` |
| 演出服·早早盛开的唇彩（SSR） | `023_costume.model.json` |
| 演出服·泳圈达人（R） | `024_costume.model.json` |
| 演出服·受到称赞之人（SSR） | `025_costume.model.json` |
| 演出服·火候很完美！（SR） | `026_costume.model.json` |
| 演出服·迷茫的庭园（UR） | `027_costume.model.json` |
| 演出服·涩谷冒险，出发！（SSR） | `028_costume.model.json` |
| 演出服·圣诞颂歌（UR） | `029_costume.model.json` |
| 演出服·为了做我自己（SR） | `030_costume.model.json` |
| 演出服·在光辉的校园里（UR） | `031_costume.model.json` |
| 演出服·在清澈的蓝色中摇曳（SSR） | `032_costume.model.json` |
| 演出服·变身少女在夜晚闪耀（UR） | `033_costume.model.json` |
| 演出服·什么都可以问我哦！（SSR） | `034_costume.model.json` |
| 演出服·得意的笑容（SR） | `035_costume.model.json` |
| 演出服·分享幸福的时刻（UR） | `036_costume.model.json` |
| 演出服·正因为是共同度过的时光（SSR） | `037_costume.model.json` |
| 演出服·被朝阳照亮的你（UR） | `038_costume.model.json` |
| 演出服·将心意寄于交叠的手中（UR） | `039_costume.model.json` |
| 演出服·属于我的美好颜色（SR） | `040_costume.model.json` |
| 演出服·Poppin' Flap（R） | `041_costume.model.json` |
| 演出服·清凉而娴静（R） | `042_costume.model.json` |
| 演出服·和月之森的大家一起！（UR） | `043_costume.model.json` |
| 演出服·高贵的微蓝 | `044_costume.model.json` |
| 演出服·北极星 | `045_costume.model.json` |
| 演出服·值得信赖的委员长 | `046_costume.model.json` |
| 演出服·因为是姐姐 | `047_costume.model.json` |
| 活动·梦想祭·急促的气息，染上冬色 | `048_costume.model.json` |
| 活动·梦想祭·与小鸟们嬉戏（UR） | `049_costume.model.json` |
| 活动·梦想祭·猛力扣杀！（UR） | `050_costume.model.json` |
| 活动·5周年特别服 | `051_costume.model.json` |
| 剧情·活动119剧情01 | `052_costume.model.json` |
| 剧情·活动120剧情01 | `053_costume.model.json` |
| 剧情·活动194剧情01 | `054_costume.model.json` |
| 剧情·活动203剧情01 | `055_costume.model.json` |
| 剧情·活动272剧情01 | `056_costume.model.json` |
| 剧情·活动340剧情01 | `057_costume.model.json` |
| 季节·2022振袖 | `058_costume.model.json` |
| 季节·泳装 | `059_costume.model.json` |
| 生日·2021 | `060_costume.model.json` |
| 生日·2022 | `061_costume.model.json` |
| 联动·初音未来·深海少女 | `062_costume.model.json` |
| 其他·2021愚人节 | `063_costume.model.json` |

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
