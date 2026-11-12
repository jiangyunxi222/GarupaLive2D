# 鳰原令王那（PAREO）（Garupa）

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
| 常服·夏2023 | `004_costume.model.json` |
| 常服·冬2023 | `005_costume.model.json` |
| 校服·冬季 | `006_costume.model.json` |
| 校服·冬季2023 | `007_costume.model.json` |
| 演出服·EXPOSE | `008_costume.model.json` |
| 演出服·招募吉他手！（SR） | `009_costume.model.json` |
| 演出服·因为有你在（SSR） | `010_costume.model.json` |
| 演出服·慈爱的目光（SR） | `011_costume.model.json` |
| 演出服·相同的午饭（SR） | `012_costume.model.json` |
| 演出服·永远都喜欢（SSR） | `013_costume.model.json` |
| 演出服·贴心的照料（R） | `014_costume.model.json` |
| 演出服·充满回忆的夏天（SSR） | `015_costume.model.json` |
| 演出服·主人的母亲！？（SR） | `016_costume.model.json` |
| 演出服·快乐的合影♡（SR） | `017_costume.model.json` |
| 演出服·旋律队 嬉铸牡音（SR） | `018_costume.model.json` |
| 演出服·∞Surprise！（SSR） | `019_costume.model.json` |
| 演出服·作为粉丝的礼仪 | `020_costume.model.json` |
| 演出服·超越一切（SSR） | `021_costume.model.json` |
| 演出服·远方的声音（R） | `022_costume.model.json` |
| 演出服·繁星婚礼（UR） | `023_costume.model.json` |
| 演出服·开始失控的指南针（SSR） | `024_costume.model.json` |
| 演出服·渐渐远去的你（UR） | `025_costume.model.json` |
| 演出服·不要离开我（UR） | `026_costume.model.json` |
| 演出服·high-Stakes（R） | `027_costume.model.json` |
| 演出服·蓝花鼠尾草的少女（R） | `028_costume.model.json` |
| 演出服·无法触及的声音（SR） | `029_costume.model.json` |
| 演出服·世界焕然一新的清晨（UR） | `030_costume.model.json` |
| 演出服·握住勇者大人的手（UR） | `031_costume.model.json` |
| 演出服·向往的舞台（SR） | `032_costume.model.json` |
| 演出服·也让我们加入吧～！（SSR） | `033_costume.model.json` |
| 演出服·最近又最远的人（UR） | `034_costume.model.json` |
| 演出服·Dog Fight！ | `035_costume.model.json` |
| 演出服·Rampage!!! | `036_costume.model.json` |
| 活动·梦想祭·令王那也辛苦了♪ | `037_costume.model.json` |
| 活动·梦想祭·欣赏偶像的时刻（UR） | `038_costume.model.json` |
| 活动·梦想祭·献给一直努力的你（UR） | `039_costume.model.json` |
| 活动·闪耀祭·Today's | `040_costume.model.json` |
| 活动·5周年特别服 | `041_costume.model.json` |
| 剧情·活动143剧情02 | `042_costume.model.json` |
| 剧情·活动158剧情01 | `043_costume.model.json` |
| 剧情·活动308剧情01 | `044_costume.model.json` |
| 季节·2022振袖 | `045_costume.model.json` |
| 生日·2021 | `046_costume.model.json` |
| 生日·2022 | `047_costume.model.json` |
| 联动·开心迎接挑战吧！（UR） | `048_costume.model.json` |
| 联动·初音未来·劣等上等 | `049_costume.model.json` |
| 其他·2021愚人节 | `050_costume.model.json` |

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
