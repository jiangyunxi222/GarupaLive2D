# 鳰原令王那（PAREO）（Garupa）

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
