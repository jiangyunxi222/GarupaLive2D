# 松原花音（Garupa）

完整复制本角色目录，在 Live2DViewerEX 中导入 `00_integrated.model.json`。

## 新版菜单

主菜单提供「动作」「表情」「换装」「声音与控制」「关闭菜单」。换装及各级列表均可直接返回主菜单。

- 点击身体上的语音区域只播放语音，不展开主菜单或播放控制菜单；再次点击可以切换语音。
- 从菜单中主动选择语音时，仍显示字幕、重播、停止和返回按钮。
- 表情保持至下一次选择，使用「清除表情」恢复。
- 新动作或「停止并回到待机」可解除动作保持，操作菜单无需等待动画结束。
- 「声音与控制 → 恢复默认 / 解除保持」清除动作、表情及参数锁定；「关闭菜单」仅关闭操作框。

更新后请完整重载 `00_integrated` 主入口，确保旧实例中的控制器已卸载；仅切换衣装不会更新父模型。

## 衣装入口

| 衣装 | 内部配置 |
|---|---|
| 默认·舞台 | `001_costume.model.json` |
| 常服·咖啡厅 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·冬 | `007_costume.model.json` |
| 常服·冬2023 | `008_costume.model.json` |
| 常服·快餐店 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·冬季 | `011_costume.model.json` |
| 校服·冬季V3 | `012_costume.model.json` |
| 演出服·兔子猎手（SSR） | `013_costume.model.json` |
| 演出服·星之织女（R） | `014_costume.model.json` |
| 演出服·想要帮忙（SR） | `015_costume.model.json` |
| 演出服·变身之术？（SR） | `016_costume.model.json` |
| 演出服·决意的一步（SSR） | `017_costume.model.json` |
| 演出服·精彩的点茶（R） | `018_costume.model.json` |
| 演出服·被卷入舞会（SR） | `019_costume.model.json` |
| 演出服·鼓起勇气来（SSR） | `020_costume.model.json` |
| 演出服·在秋日天空下野餐（SSR） | `021_costume.model.json` |
| 演出服·大家齐心协力（SR） | `022_costume.model.json` |
| 演出服·小旅行？（R） | `023_costume.model.json` |
| 演出服·面带笑容吃一口（SSR） | `024_costume.model.json` |
| 演出服·心花怒放（SSR） | `025_costume.model.json` |
| 演出服·一点点帮忙（SR） | `026_costume.model.json` |
| 演出服·颜色各异的光辉（SR） | `027_costume.model.json` |
| 演出服·绚烂的花束（SSR） | `028_costume.model.json` |
| 演出服·和煦的阳光（SR） | `029_costume.model.json` |
| 演出服·穿上圣诞服装（R） | `030_costume.model.json` |
| 演出服·梦之果实（SR） | `031_costume.model.json` |
| 演出服·那一天的景色在眼前蔓延（SSR） | `032_costume.model.json` |
| 演出服·8号，接手（SR） | `033_costume.model.json` |
| 演出服·微笑的绣球花（R） | `034_costume.model.json` |
| 演出服·星空下的闲谈（SSR） | `035_costume.model.json` |
| 演出服·悠闲魔女（SR） | `036_costume.model.json` |
| 演出服·我的勇气（SSR） | `037_costume.model.json` |
| 演出服·演出前的准备是拿手好戏（SR） | `038_costume.model.json` |
| 演出服·恐龙蛋新成员（SR） | `039_costume.model.json` |
| 演出服·明亮且正确的道路（SSR） | `040_costume.model.json` |
| 演出服·Secret Eyes（R） | `041_costume.model.json` |
| 演出服·累积起来的刹那（SR） | `042_costume.model.json` |
| 演出服·与捣蛋猫咪的攻防战（SR） | `043_costume.model.json` |
| 演出服·笑容的追踪者（SSR） | `044_costume.model.json` |
| 演出服·森林里的欢乐朋友 | `045_costume.model.json` |
| 演出服·数道交叠的声音（SSR） | `046_costume.model.json` |
| 演出服·毕业（SSR） | `047_costume.model.json` |
| 演出服·Bonjour！（R） | `048_costume.model.json` |
| 演出服·大学生们的对话（SSR） | `049_costume.model.json` |
| 演出服·海滩上的宝石（SR） | `050_costume.model.json` |
| 演出服·令人心跳加速的试装（SR） | `051_costume.model.json` |
| 演出服·可爱的包装（UR） | `052_costume.model.json` |
| 演出服·理由和目的（UR） | `053_costume.model.json` |
| 演出服·阳光灿烂的浅蓝夏日（UR） | `054_costume.model.json` |
| 演出服·梦幻气球（R） | `055_costume.model.json` |
| 演出服·骑着海豚的公主（UR） | `056_costume.model.json` |
| 演出服·公主练习曲（SSR） | `057_costume.model.json` |
| 演出服·耀眼之人（UR） | `058_costume.model.json` |
| 演出服·箱庭世界的冒险者（R） | `059_costume.model.json` |
| 演出服·相处融洽的两位鼓手（SSR） | `060_costume.model.json` |
| 演出服·纯白的大小姐（R） | `061_costume.model.json` |
| 演出服·梅花，在寒空中绽放（UR） | `062_costume.model.json` |
| 演出服·惬意的空间（UR） | `063_costume.model.json` |
| 演出服·共度宁静时光（SR） | `064_costume.model.json` |
| 演出服·微笑的温度（SSR） | `065_costume.model.json` |
| 演出服·未来护士（R） | `066_costume.model.json` |
| 演出服·晕头转向大混乱（SR） | `067_costume.model.json` |
| 演出服·暖心徒步者（SSR） | `068_costume.model.json` |
| 演出服·无与伦比的瞬间（SSR） | `069_costume.model.json` |
| 演出服·笑容的魔法 | `070_costume.model.json` |
| 演出服·Smile Seeker！ | `071_costume.model.json` |
| 演出服·微笑的行星 | `072_costume.model.json` |
| 演出服·来吧来吧，笑容游行 | `073_costume.model.json` |
| 演出服·笑容∞奇迹！ | `074_costume.model.json` |
| 演出服·走出的第一步 | `075_costume.model.json` |
| 活动·第2回总选举（R） | `076_costume.model.json` |
| 活动·梦想祭·购物也要拼尽全力 | `077_costume.model.json` |
| 活动·梦想祭·飘浮的月亮 | `078_costume.model.json` |
| 活动·梦想祭·晴空之下（UR） | `079_costume.model.json` |
| 活动·梦想祭·街角时尚达人（UR） | `080_costume.model.json` |
| 活动·活动03 | `081_costume.model.json` |
| 活动·闪耀祭·青色散步 | `082_costume.model.json` |
| 活动·5周年特别服 | `083_costume.model.json` |
| 剧情·活动48剧情01 | `084_costume.model.json` |
| 剧情·活动55剧情01 | `085_costume.model.json` |
| 剧情·活动67剧情01 | `086_costume.model.json` |
| 剧情·活动74剧情01 | `087_costume.model.json` |
| 剧情·活动88剧情01 | `088_costume.model.json` |
| 剧情·活动110剧情01 | `089_costume.model.json` |
| 剧情·活动119剧情01 | `090_costume.model.json` |
| 剧情·活动216剧情01 | `091_costume.model.json` |
| 剧情·活动244剧情01 | `092_costume.model.json` |
| 剧情·活动316剧情01 | `093_costume.model.json` |
| 剧情·活动344剧情01 | `094_costume.model.json` |
| 剧情·米歇尔 | `095_costume.model.json` |
| 剧情·Hello Happy战队面具 | `096_costume.model.json` |
| 季节·2018狗年 | `097_costume.model.json` |
| 季节·2019振袖 | `098_costume.model.json` |
| 季节·夏日水手服 | `099_costume.model.json` |
| 季节·泳装2023 | `100_costume.model.json` |
| 生日·2021 | `101_costume.model.json` |
| 生日·2022 | `102_costume.model.json` |
| 联动·白上吹雪（hololive） | `103_costume.model.json` |
| 联动·初音未来·Alien Alien | `104_costume.model.json` |
| 其他·Garupa T恤 | `105_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。

## 统一点击规则

| 实际点击位置 | 效果 |
|---|---|
| 头顶、刘海上部 | 切换表情 |
| 脸部下半部 | 播放语音 |
| 上身中央 | 播放普通动作 |
| 画面右侧手臂 | 角色左臂动作 |
| 画面左侧手臂 | 角色右臂动作 |
| 腰部、衣服中段 | 打开换装菜单 |
| 腿部、衣服下段 | 打开主菜单 |

每套衣装均包含七个独立矩形点击区，按该衣装默认站姿的头部和身体比例定位，跟随模型整体移动和缩放。点击层保持透明，衣服网格合并或隐藏不会取消入口。动作造成的局部身体变形不会改变矩形分区。

仅头像形态也保留相同布局，上身、腰部、腿部入口位于头像下方的透明区域，左右手入口位于对应两侧。

表情、语音和身体动作不会展开菜单。缺少方向动作时播放普通动作，缺少素材时保持待机。点击分区之间的空白可打开主菜单。

请完整重载 `00_integrated` 主入口，保留 `assets/hitareas` 中的点击层文件。
