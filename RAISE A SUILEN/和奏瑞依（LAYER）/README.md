# 和奏瑞依（LAYER）（Garupa）

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
| 常服·夏2023 | `004_costume.model.json` |
| 常服·冬2023 | `005_costume.model.json` |
| 演出服·EXPOSE | `006_costume.model.json` |
| 演出服·美味的时间（SR） | `007_costume.model.json` |
| 演出服·开始闪耀的星星（SSR） | `008_costume.model.json` |
| 演出服·呼啸在录音室的暴风雨（SSR） | `009_costume.model.json` |
| 演出服·初次纪念（SR） | `010_costume.model.json` |
| 演出服·狂野的流行乐（R） | `011_costume.model.json` |
| 演出服·果然还是要黑咖啡（SSR） | `012_costume.model.json` |
| 演出服·一夏的闪耀（SR） | `013_costume.model.json` |
| 演出服·我不会 哭我 不会哭（SSR） | `014_costume.model.json` |
| 演出服·抓住这双手（SSR） | `015_costume.model.json` |
| 演出服·壮丽的幕间（SR） | `016_costume.model.json` |
| 演出服·丽厨哑睡莲 谱乱兔（SSR） | `017_costume.model.json` |
| 演出服·可爱文化 | `018_costume.model.json` |
| 演出服·挑战的主唱 | `019_costume.model.json` |
| 演出服·擅长默默守候（SR） | `020_costume.model.json` |
| 演出服·前往集结新声音的地方（SR） | `021_costume.model.json` |
| 演出服·领会到的心意（UR） | `022_costume.model.json` |
| 演出服·温暖的声音（SR） | `023_costume.model.json` |
| 演出服·Happy weekend（UR） | `024_costume.model.json` |
| 演出服·握紧的手，在震颤（SR） | `025_costume.model.json` |
| 演出服·一次又一次竭尽全力（SSR） | `026_costume.model.json` |
| 演出服·Emersion（UR） | `027_costume.model.json` |
| 演出服·玩累之后所做的梦（SR） | `028_costume.model.json` |
| 演出服·你从很久以前就（UR） | `029_costume.model.json` |
| 演出服·倾注爱意（SSR） | `030_costume.model.json` |
| 演出服·回忆闪闪发光（UR） | `031_costume.model.json` |
| 演出服·惊悚恐怖秀（R） | `032_costume.model.json` |
| 演出服·RUNAWAY STAR（UR） | `033_costume.model.json` |
| 演出服·有你在身边（SR） | `034_costume.model.json` |
| 演出服·少女的秘密房间（R） | `035_costume.model.json` |
| 演出服·shoooooting！ | `036_costume.model.json` |
| 演出服·Dog Fight！ | `037_costume.model.json` |
| 演出服·Rampage!!! | `038_costume.model.json` |
| 演出服·和『最强』的伙伴一起（SR） | `039_costume.model.json` |
| 活动·第4回总选举（R） | `040_costume.model.json` |
| 活动·梦想祭·填满夜空的群星 | `041_costume.model.json` |
| 活动·梦想祭·巷子里的歌后（UR） | `042_costume.model.json` |
| 活动·梦想祭·填满视野的樱粉色（UR） | `043_costume.model.json` |
| 活动·5周年特别服 | `044_costume.model.json` |
| 剧情·活动158剧情01 | `045_costume.model.json` |
| 剧情·活动304剧情01 | `046_costume.model.json` |
| 剧情·活动308剧情01 | `047_costume.model.json` |
| 季节·2022振袖 | `048_costume.model.json` |
| 季节·2024振袖 | `049_costume.model.json` |
| 生日·2021 | `050_costume.model.json` |
| 生日·2022 | `051_costume.model.json` |
| 联动·bilibili联动（UR） | `052_costume.model.json` |
| 联动·来，歌唱吧（UR） | `053_costume.model.json` |
| 联动·初音未来·劣等上等 | `054_costume.model.json` |

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
