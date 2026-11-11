# 桐谷透子（Garupa）

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
| 常服 | `002_costume.model.json` |
| 常服·2023 | `003_costume.model.json` |
| 常服·夏 | `004_costume.model.json` |
| 常服·夏2023 | `005_costume.model.json` |
| 常服·冬 | `006_costume.model.json` |
| 常服·冬2023 | `007_costume.model.json` |
| 校服·夏季 | `008_costume.model.json` |
| 校服·夏季2023 | `009_costume.model.json` |
| 校服·冬季 | `010_costume.model.json` |
| 校服·冬季2023 | `011_costume.model.json` |
| 演出服·大家一起摆姿势☆（SSR） | `012_costume.model.json` |
| 演出服·悔恨之后（SR） | `013_costume.model.json` |
| 演出服·不拘小节的旋律（SR） | `014_costume.model.json` |
| 演出服·最强的气氛制造者（R） | `015_costume.model.json` |
| 演出服·雄辩的热情（SSR） | `016_costume.model.json` |
| 演出服·不擅长看书（R） | `017_costume.model.json` |
| 演出服·我真是天才！（SSR） | `018_costume.model.json` |
| 演出服·不服输的心情（SR） | `019_costume.model.json` |
| 演出服·我的假期（SSR） | `020_costume.model.json` |
| 演出服·我会向上走（SR） | `021_costume.model.json` |
| 演出服·超绚丽的水花（SR） | `022_costume.model.json` |
| 演出服·秒速和魔物交上朋友（SR） | `023_costume.model.json` |
| 演出服·一辈子的请求D.C.（SSR） | `024_costume.model.json` |
| 演出服·Sulky Girl（SR） | `025_costume.model.json` |
| 演出服·天才恶魔猎人？透子（UR） | `026_costume.model.json` |
| 演出服·玻璃蝴蝶（R） | `027_costume.model.json` |
| 演出服·前往TOCO秀！（SR） | `028_costume.model.json` |
| 演出服·华丽而轻盈（SSR） | `029_costume.model.json` |
| 演出服·无法传达的心情（UR） | `030_costume.model.json` |
| 演出服·收集花瓣（SR） | `031_costume.model.json` |
| 演出服·我们是最棒的！（SR） | `032_costume.model.json` |
| 演出服·泳装射手（SSR） | `033_costume.model.json` |
| 演出服·BEST★ANGLE！（UR） | `034_costume.model.json` |
| 演出服·将思念寄托于风中（R） | `035_costume.model.json` |
| 演出服·梦幻可爱小兔子（R） | `036_costume.model.json` |
| 演出服·审视美的目光（SSR） | `037_costume.model.json` |
| 演出服·能将未来拉近的是……（UR） | `038_costume.model.json` |
| 演出服·透过玻璃的闪耀光芒（UR） | `039_costume.model.json` |
| 演出服·Breaking Blue（R） | `040_costume.model.json` |
| 演出服·将勇气赠予你（UR） | `041_costume.model.json` |
| 演出服·我正在超绝进化中！（SSR） | `042_costume.model.json` |
| 演出服·追思逝去的时光（UR） | `043_costume.model.json` |
| 演出服·高贵的微蓝 | `044_costume.model.json` |
| 演出服·北极星 | `045_costume.model.json` |
| 演出服·杰作完成！ | `046_costume.model.json` |
| 演出服·空前流行浪潮的到来 | `047_costume.model.json` |
| 活动·梦想祭·犯困时的餐桌 | `048_costume.model.json` |
| 活动·梦想祭·最强最上镜的一张！（UR） | `049_costume.model.json` |
| 活动·梦想祭·魅力四射的存在（UR） | `050_costume.model.json` |
| 活动·梦想祭·入迷的天才（UR） | `051_costume.model.json` |
| 活动·5周年特别服 | `052_costume.model.json` |
| 剧情·活动132剧情01 | `053_costume.model.json` |
| 剧情·活动194剧情01 | `054_costume.model.json` |
| 剧情·活动203剧情01 | `055_costume.model.json` |
| 剧情·活动227剧情01 | `056_costume.model.json` |
| 剧情·活动266剧情01 | `057_costume.model.json` |
| 剧情·活动272剧情01 | `058_costume.model.json` |
| 季节·2022振袖 | `059_costume.model.json` |
| 季节·2024振袖 | `060_costume.model.json` |
| 季节·泳装 | `061_costume.model.json` |
| 生日·2021 | `062_costume.model.json` |
| 生日·2022 | `063_costume.model.json` |
| 联动·初音未来·深海少女 | `064_costume.model.json` |
| 其他·2021愚人节 | `065_costume.model.json` |

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
