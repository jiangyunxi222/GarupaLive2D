# 佐藤益木（MASKING）（Garupa）

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
| 演出服·大小姐的膳食（SR） | `009_costume.model.json` |
| 演出服·撕裂黑夜的风（SSR） | `010_costume.model.json` |
| 演出服·兴致勃勃之王（SR） | `011_costume.model.json` |
| 演出服·去吃拉面吧！（SR） | `012_costume.model.json` |
| 演出服·在彼此相连的时间里（SSR） | `013_costume.model.json` |
| 演出服·无论何时都要拼尽全力！（SR） | `014_costume.model.json` |
| 演出服·兴奋视线的前方（SSR） | `015_costume.model.json` |
| 演出服·好了，出发！（R） | `016_costume.model.json` |
| 演出服·难以言喻的焦躁（SR） | `017_costume.model.json` |
| 演出服·Ephemeral（SSR） | `018_costume.model.json` |
| 演出服·律动队 怒罗梦（SR） | `019_costume.model.json` |
| 演出服·180度、12分（SR） | `020_costume.model.json` |
| 演出服·仔细听我的声音！（SSR） | `021_costume.model.json` |
| 演出服·就是那一点（SSR） | `022_costume.model.json` |
| 演出服·附带终极赠品！（SR） | `023_costume.model.json` |
| 演出服·和孩子们一起（SSR） | `024_costume.model.json` |
| 演出服·即使那是地狱（UR） | `025_costume.model.json` |
| 演出服·在黑白的世界里（R） | `026_costume.model.json` |
| 演出服·若你迈出一步（SSR） | `027_costume.model.json` |
| 演出服·最强&究极（UR） | `028_costume.model.json` |
| 演出服·Risky Bet（SR） | `029_costume.model.json` |
| 演出服·充满挑战精神的背影（SSR） | `030_costume.model.json` |
| 演出服·井之岛Strollin’（UR） | `031_costume.model.json` |
| 演出服·总有一天（UR） | `032_costume.model.json` |
| 演出服·无畏的小恶魔（R） | `033_costume.model.json` |
| 演出服·万圣节机遇（SR） | `034_costume.model.json` |
| 演出服·NO STAR HERE（UR） | `035_costume.model.json` |
| 演出服·狂犬的迷惘（SSR） | `036_costume.model.json` |
| 演出服·高雅管弦乐（R） | `037_costume.model.json` |
| 演出服·行家如是说（SR） | `038_costume.model.json` |
| 演出服·放手去干吧（UR） | `039_costume.model.json` |
| 演出服·Dog Fight！ | `040_costume.model.json` |
| 演出服·Rampage!!! | `041_costume.model.json` |
| 活动·梦想祭·与燃烧的红色一起驰骋 | `042_costume.model.json` |
| 活动·梦想祭·火花四溅的生活方式（UR） | `043_costume.model.json` |
| 活动·梦想祭·晴空的雨滴（UR） | `044_costume.model.json` |
| 活动·5周年特别服 | `045_costume.model.json` |
| 剧情·活动158剧情01 | `046_costume.model.json` |
| 剧情·活动236剧情01 | `047_costume.model.json` |
| 剧情·活动308剧情01 | `048_costume.model.json` |
| 剧情·活动335剧情01 | `049_costume.model.json` |
| 季节·2022振袖 | `050_costume.model.json` |
| 生日·2021 | `051_costume.model.json` |
| 生日·2022 | `052_costume.model.json` |
| 联动·初音未来·劣等上等 | `053_costume.model.json` |

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

语音菜单提供「开启字幕 / 关闭字幕」开关，默认开启，同一角色换装后保留。点击语音区只播放随机语音及可选字幕。腰部点击随机切换其他衣装，衣装列表仍可从主菜单进入。

语音字幕默认开启，同一角色换装后保留设置。原始资源没有语音文件时，点击语音区显示「当前角色未提供语音素材」，此提示不受字幕开关影响。
