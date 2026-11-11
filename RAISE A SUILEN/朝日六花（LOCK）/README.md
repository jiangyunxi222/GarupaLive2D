# 朝日六花（LOCK）（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏2023 | `005_costume.model.json` |
| 常服·冬2023 | `006_costume.model.json` |
| 校服·夏季 | `007_costume.model.json` |
| 校服·夏季2023 | `008_costume.model.json` |
| 校服·冬季 | `009_costume.model.json` |
| 校服·冬季2023 | `010_costume.model.json` |
| 校服·冬季2 | `011_costume.model.json` |
| 演出服·EXPOSE | `012_costume.model.json` |
| 演出服·六花的全力以赴（SSR） | `013_costume.model.json` |
| 演出服·果然乐队最棒了（SR） | `014_costume.model.json` |
| 演出服·一起万圣节！（SSR） | `015_costume.model.json` |
| 演出服·被鼓动的心跳（R） | `016_costume.model.json` |
| 演出服·Lock on！（SSR） | `017_costume.model.json` |
| 演出服·LOCK SOS！！（SSR） | `018_costume.model.json` |
| 演出服·传达的心意，跃动的心（SR） | `019_costume.model.json` |
| 演出服·分享友情（SR） | `020_costume.model.json` |
| 演出服·相信『我』的勇气（SR） | `021_costume.model.json` |
| 演出服·被铭刻的时光（SR） | `022_costume.model.json` |
| 演出服·前往光芒照耀之处（SSR） | `023_costume.model.json` |
| 演出服·旋律队 义侘哑（SR） | `024_costume.model.json` |
| 演出服·即使分离（SSR） | `025_costume.model.json` |
| 演出服·坐立不安Stay | `026_costume.model.json` |
| 演出服·驯鸽师莅临新年（SR） | `027_costume.model.json` |
| 演出服·我面对事物的方法（UR） | `028_costume.model.json` |
| 演出服·孤高的无敌者（R） | `029_costume.model.json` |
| 演出服·发现了现行犯！？（UR） | `030_costume.model.json` |
| 演出服·For my dear（SSR） | `031_costume.model.json` |
| 演出服·是全垒打！（SR） | `032_costume.model.json` |
| 演出服·笑容的圆环（SSR） | `033_costume.model.json` |
| 演出服·连结奇迹（R） | `034_costume.model.json` |
| 演出服·All-in（SSR） | `035_costume.model.json` |
| 演出服·可爱的贪吃鬼（UR） | `036_costume.model.json` |
| 演出服·打开心门（SSR） | `037_costume.model.json` |
| 演出服·衷心祝福（UR） | `038_costume.model.json` |
| 演出服·在清凉的溪畔（SR） | `039_costume.model.json` |
| 演出服·淡淡的夏日回忆（R） | `040_costume.model.json` |
| 演出服·予黑暗以光明（UR） | `041_costume.model.json` |
| 演出服·活力全开即兴演奏！（SSR） | `042_costume.model.json` |
| 演出服·Stellar Frontline（R） | `043_costume.model.json` |
| 演出服·率直的『喜欢』（UR） | `044_costume.model.json` |
| 演出服·魅惑的异国风情（SSR） | `045_costume.model.json` |
| 演出服·Dog Fight！ | `046_costume.model.json` |
| 演出服·Rampage!!! | `047_costume.model.json` |
| 活动·梦想祭·温泉中的LOCK | `048_costume.model.json` |
| 活动·梦想祭·开心的事要一起做！（UR） | `049_costume.model.json` |
| 活动·梦想祭·只属于我们的泳池（UR） | `050_costume.model.json` |
| 活动·5周年特别服 | `051_costume.model.json` |
| 剧情·活动119剧情01 | `052_costume.model.json` |
| 剧情·活动128剧情01 | `053_costume.model.json` |
| 剧情·活动158剧情01 | `054_costume.model.json` |
| 剧情·活动187剧情01 | `055_costume.model.json` |
| 剧情·活动216剧情01 | `056_costume.model.json` |
| 剧情·活动308剧情01 | `057_costume.model.json` |
| 剧情·剧情01 | `058_costume.model.json` |
| 季节·2022振袖 | `059_costume.model.json` |
| 季节·泳装2023 | `060_costume.model.json` |
| 生日·2021 | `061_costume.model.json` |
| 生日·2022 | `062_costume.model.json` |
| 联动·初音未来·劣等上等 | `063_costume.model.json` |

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
