# 二叶筑紫（Garupa）

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
| 常服·打工 | `002_costume.model.json` |
| 常服·打工2023 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季2023 | `011_costume.model.json` |
| 校服·冬季 | `012_costume.model.json` |
| 校服·冬季2023 | `013_costume.model.json` |
| 演出服·模范队长的修养（SR） | `014_costume.model.json` |
| 演出服·早安电话（SSR） | `015_costume.model.json` |
| 演出服·名作词家·二叶筑紫（SR） | `016_costume.model.json` |
| 演出服·蝴蝶结也要绑得很完美！（SR） | `017_costume.model.json` |
| 演出服·做到了！这是实力的证明（SSR） | `018_costume.model.json` |
| 演出服·星月之夜的闪耀（R） | `019_costume.model.json` |
| 演出服·一个一个地来（SSR） | `020_costume.model.json` |
| 演出服·能够肯定自己的证明（SR） | `021_costume.model.json` |
| 演出服·交给班长吧（R） | `022_costume.model.json` |
| 演出服·早早盛开的唇彩（SSR） | `023_costume.model.json` |
| 演出服·泳圈达人（R） | `024_costume.model.json` |
| 演出服·受到称赞之人（SSR） | `025_costume.model.json` |
| 演出服·火候很完美！（SR） | `026_costume.model.json` |
| 演出服·迷茫的庭园（UR） | `027_costume.model.json` |
| 演出服·涩谷冒险，出发！（SSR） | `028_costume.model.json` |
| 演出服·圣诞颂歌（UR） | `029_costume.model.json` |
| 演出服·为了做我自己（SR） | `030_costume.model.json` |
| 演出服·在光辉的校园里（UR） | `031_costume.model.json` |
| 演出服·在清澈的蓝色中摇曳（SSR） | `032_costume.model.json` |
| 演出服·变身少女在夜晚闪耀（UR） | `033_costume.model.json` |
| 演出服·什么都可以问我哦！（SSR） | `034_costume.model.json` |
| 演出服·得意的笑容（SR） | `035_costume.model.json` |
| 演出服·分享幸福的时刻（UR） | `036_costume.model.json` |
| 演出服·正因为是共同度过的时光（SSR） | `037_costume.model.json` |
| 演出服·被朝阳照亮的你（UR） | `038_costume.model.json` |
| 演出服·将心意寄于交叠的手中（UR） | `039_costume.model.json` |
| 演出服·属于我的美好颜色（SR） | `040_costume.model.json` |
| 演出服·Poppin' Flap（R） | `041_costume.model.json` |
| 演出服·清凉而娴静（R） | `042_costume.model.json` |
| 演出服·和月之森的大家一起！（UR） | `043_costume.model.json` |
| 演出服·高贵的微蓝 | `044_costume.model.json` |
| 演出服·北极星 | `045_costume.model.json` |
| 演出服·值得信赖的委员长 | `046_costume.model.json` |
| 演出服·因为是姐姐 | `047_costume.model.json` |
| 活动·梦想祭·急促的气息，染上冬色 | `048_costume.model.json` |
| 活动·梦想祭·与小鸟们嬉戏（UR） | `049_costume.model.json` |
| 活动·梦想祭·猛力扣杀！（UR） | `050_costume.model.json` |
| 活动·5周年特别服 | `051_costume.model.json` |
| 剧情·活动119剧情01 | `052_costume.model.json` |
| 剧情·活动120剧情01 | `053_costume.model.json` |
| 剧情·活动194剧情01 | `054_costume.model.json` |
| 剧情·活动203剧情01 | `055_costume.model.json` |
| 剧情·活动272剧情01 | `056_costume.model.json` |
| 剧情·活动340剧情01 | `057_costume.model.json` |
| 季节·2022振袖 | `058_costume.model.json` |
| 季节·泳装 | `059_costume.model.json` |
| 生日·2021 | `060_costume.model.json` |
| 生日·2022 | `061_costume.model.json` |
| 联动·初音未来·深海少女 | `062_costume.model.json` |
| 其他·2021愚人节 | `063_costume.model.json` |

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
