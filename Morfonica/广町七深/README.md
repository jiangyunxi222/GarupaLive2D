# 广町七深（Garupa）

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

| 点击区域 | 触发效果 |
|---|---|
| 表情区域 | 随机切换表情，不展开菜单 |
| 语音区域 | 只播放语音，不展开菜单 |
| 正面动作区域 | 播放普通动作，不展开菜单 |
| 左手 / 右手区域 | 优先播放对应方向动作，不展开菜单 |
| 换装区域 | 打开换装菜单 |
| 菜单区域 | 打开主菜单 |

缺少左右方向动作时回退到普通动作；没有动作素材时保持待机，不回退到菜单。没有语音或表情素材时也不弹出菜单。

重叠区域统一按「表情 → 语音 → 手部动作 → 正面动作 → 换装 → 菜单」处理，同一网格只保留一个有效触发。各衣装沿用自身网格，网格编号及形状不作修改。未命中专用区域时，仍可通过默认点击打开主菜单。

更新后请完整重载 `00_integrated` 主入口。
