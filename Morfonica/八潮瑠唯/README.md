# 八潮瑠唯（Garupa）

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
| 常服·夏 | `004_costume.model.json` |
| 常服·夏2023 | `005_costume.model.json` |
| 常服·冬 | `006_costume.model.json` |
| 常服·冬2023 | `007_costume.model.json` |
| 校服·夏季 | `008_costume.model.json` |
| 校服·夏季2023 | `009_costume.model.json` |
| 校服·冬季 | `010_costume.model.json` |
| 校服·冬季2023 | `011_costume.model.json` |
| 演出服·与未知不期而遇（SR） | `012_costume.model.json` |
| 演出服·反复练习的乐谱（SSR） | `013_costume.model.json` |
| 演出服·与我无关（SR） | `014_costume.model.json` |
| 演出服·和以往不同的景色（SSR） | `015_costume.model.json` |
| 演出服·在喧嚣中保持平静（R） | `016_costume.model.json` |
| 演出服·发现才能的视线（SR） | `017_costume.model.json` |
| 演出服·那天的回答（SSR） | `018_costume.model.json` |
| 演出服·时尚领结（R） | `019_costume.model.json` |
| 演出服·在海上盛开的繁花（SSR） | `020_costume.model.json` |
| 演出服·互相提升的时光（SR） | `021_costume.model.json` |
| 演出服·沉醉于那音色（SSR） | `022_costume.model.json` |
| 演出服·黑发美人鱼（SR） | `023_costume.model.json` |
| 演出服·正论恶魔（SR） | `024_costume.model.json` |
| 演出服·不断增加的记录，以及……（SSR） | `025_costume.model.json` |
| 演出服·无人所知的战斗（UR） | `026_costume.model.json` |
| 演出服·恶魔猎人的调停者·瑠唯（SSR） | `027_costume.model.json` |
| 演出服·被声浪催促着（SR） | `028_costume.model.json` |
| 演出服·白色蝴蝶的旋律（R） | `029_costume.model.json` |
| 演出服·这个光彩四溢的世界（UR） | `030_costume.model.json` |
| 演出服·共赏前方的景色（SSR） | `031_costume.model.json` |
| 演出服·离心力，不为所动（SR） | `032_costume.model.json` |
| 演出服·致未来尚未见面的我们（UR） | `033_costume.model.json` |
| 演出服·下不为例（SR） | `034_costume.model.json` |
| 演出服·自那以后，我们……（UR） | `035_costume.model.json` |
| 演出服·决心寄于乐声（SSR） | `036_costume.model.json` |
| 演出服·被看穿的内心（SSR） | `037_costume.model.json` |
| 演出服·照亮我的光（UR） | `038_costume.model.json` |
| 演出服·文档大师（SSR） | `039_costume.model.json` |
| 演出服·高贵的微蓝 | `040_costume.model.json` |
| 演出服·北极星 | `041_costume.model.json` |
| 演出服·才能与断念 | `042_costume.model.json` |
| 演出服·前往知识的海洋 | `043_costume.model.json` |
| 活动·第4回总选举（R） | `044_costume.model.json` |
| 活动·梦想祭·黄昏，身穿浴衣 | `045_costume.model.json` |
| 活动·梦想祭·阳光下的寂静树影（UR） | `046_costume.model.json` |
| 活动·梦想祭·静静飘落堆积的雪（UR） | `047_costume.model.json` |
| 活动·闪耀祭·进入甜美的梦乡 | `048_costume.model.json` |
| 活动·5周年特别服 | `049_costume.model.json` |
| 剧情·活动132剧情01 | `050_costume.model.json` |
| 剧情·活动190剧情01 | `051_costume.model.json` |
| 剧情·活动194剧情01 | `052_costume.model.json` |
| 剧情·活动203剧情01 | `053_costume.model.json` |
| 剧情·活动227剧情01 | `054_costume.model.json` |
| 剧情·活动272剧情01 | `055_costume.model.json` |
| 季节·2022振袖 | `056_costume.model.json` |
| 季节·泳装 | `057_costume.model.json` |
| 生日·2021 | `058_costume.model.json` |
| 生日·2022 | `059_costume.model.json` |
| 联动·初音未来·深海少女 | `060_costume.model.json` |

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
