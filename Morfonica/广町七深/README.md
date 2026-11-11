# 广町七深（Garupa）

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
| 常服·打工2023 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·V3 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季2023 | `011_costume.model.json` |
| 校服·冬季 | `012_costume.model.json` |
| 校服·冬季2023 | `013_costume.model.json` |
| 演出服·樱花模式（R） | `014_costume.model.json` |
| 演出服·第一次来粗点心店！（SSR） | `015_costume.model.json` |
| 演出服·无法隐藏的秘密（SR） | `016_costume.model.json` |
| 演出服·第一次的圆阵（SSR） | `017_costume.model.json` |
| 演出服·HOT的初次体验（SR） | `018_costume.model.json` |
| 演出服·只属于我们的秘密（SSR） | `019_costume.model.json` |
| 演出服·现在，感受青春（SR） | `020_costume.model.json` |
| 演出服·向往许久的分享（SR） | `021_costume.model.json` |
| 演出服·额头上闪烁的青春之证（SSR） | `022_costume.model.json` |
| 演出服·调解专家？（SR） | `023_costume.model.json` |
| 演出服·现在可以做到任何事情（SSR） | `024_costume.model.json` |
| 演出服·这就是我的最辣料理（SR） | `025_costume.model.json` |
| 演出服·♡For you（R） | `026_costume.model.json` |
| 演出服·被禁止的日常（SSR） | `027_costume.model.json` |
| 演出服·PARE町小队（SR） | `028_costume.model.json` |
| 演出服·想要传达的话语（UR） | `029_costume.model.json` |
| 演出服·圣夜的青春（SSR） | `030_costume.model.json` |
| 演出服·因为是朋友（SSR） | `031_costume.model.json` |
| 演出服·不放弃的心情（R） | `032_costume.model.json` |
| 演出服·奥义·毅力能量！（UR） | `033_costume.model.json` |
| 演出服·the wicked road（SSR） | `034_costume.model.json` |
| 演出服·从乐谱中传达的期待（SSR） | `035_costume.model.json` |
| 演出服·一直在一起讴歌青春（UR） | `036_costume.model.json` |
| 演出服·现身吧！隐藏款！（UR） | `037_costume.model.json` |
| 演出服·Don't miss it！（R） | `038_costume.model.json` |
| 演出服·携手同行（UR） | `039_costume.model.json` |
| 演出服·广町感应器启动！（SR） | `040_costume.model.json` |
| 演出服·指引我的色彩（UR） | `041_costume.model.json` |
| 演出服·慰劳的片刻（SR） | `042_costume.model.json` |
| 演出服·氛围满分（SSR） | `043_costume.model.json` |
| 演出服·空中飞舞的灯火（R） | `044_costume.model.json` |
| 演出服·高贵的微蓝 | `045_costume.model.json` |
| 演出服·北极星 | `046_costume.model.json` |
| 演出服·延展开的景色 | `047_costume.model.json` |
| 演出服·赠品收藏 | `048_costume.model.json` |
| 活动·梦想祭·再次牵起手来 | `049_costume.model.json` |
| 活动·梦想祭·冬天的海，很冷（UR） | `050_costume.model.json` |
| 活动·梦想祭·泡沫之梦（UR） | `051_costume.model.json` |
| 活动·闪耀祭·春天就在这里 | `052_costume.model.json` |
| 活动·5周年特别服 | `053_costume.model.json` |
| 剧情·活动132剧情01 | `054_costume.model.json` |
| 剧情·活动157剧情01 | `055_costume.model.json` |
| 剧情·活动194剧情01 | `056_costume.model.json` |
| 剧情·活动203剧情01 | `057_costume.model.json` |
| 剧情·活动272剧情01 | `058_costume.model.json` |
| 剧情·活动335剧情01 | `059_costume.model.json` |
| 季节·2022振袖 | `060_costume.model.json` |
| 季节·泳装 | `061_costume.model.json` |
| 生日·2021 | `062_costume.model.json` |
| 生日·2022 | `063_costume.model.json` |
| 联动·初音未来·深海少女 | `064_costume.model.json` |

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
