# 仓田真白（Garupa）

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
| 常服·睡衣2023 | `008_costume.model.json` |
| 校服·夏季 | `009_costume.model.json` |
| 校服·夏季2023 | `010_costume.model.json` |
| 校服·冬季 | `011_costume.model.json` |
| 校服·冬季2023 | `012_costume.model.json` |
| 演出服·欢迎来到派对！（SSR） | `013_costume.model.json` |
| 演出服·热情与传达的心意（R） | `014_costume.model.json` |
| 演出服·沐浴着憧憬的光芒（SSR） | `015_costume.model.json` |
| 演出服·害羞的招牌动作（R） | `016_costume.model.json` |
| 演出服·外语的翻译方法（SR） | `017_costume.model.json` |
| 演出服·必须要说出来……！（SR） | `018_costume.model.json` |
| 演出服·让人心情激动的事（SR） | `019_costume.model.json` |
| 演出服·通过语言来表现（SSR） | `020_costume.model.json` |
| 演出服·正月赞歌（SR） | `021_costume.model.json` |
| 演出服·变成不寻常的我（SR） | `022_costume.model.json` |
| 演出服·对阵河之主（SSR） | `023_costume.model.json` |
| 演出服·欢迎来到异世界！（SSR） | `024_costume.model.json` |
| 演出服·讲究的配料（SR） | `025_costume.model.json` |
| 演出服·我的光芒照亮的道路（UR） | `026_costume.model.json` |
| 演出服·彷徨于灰色世界的蝴蝶（R） | `027_costume.model.json` |
| 演出服·夕阳的泪滴（UR） | `028_costume.model.json` |
| 演出服·挺直腰背（UR） | `029_costume.model.json` |
| 演出服·在那片天空下休憩（R） | `030_costume.model.json` |
| 演出服·勇气展翅高飞之时（UR） | `031_costume.model.json` |
| 演出服·快乐手工艺（R） | `032_costume.model.json` |
| 演出服·海上的梦幻故事（SR） | `033_costume.model.json` |
| 演出服·落入→仙境（UR） | `034_costume.model.json` |
| 演出服·变装之日（R） | `035_costume.model.json` |
| 演出服·思念朋友的夜晚（UR） | `036_costume.model.json` |
| 演出服·未来蓝图绘制中！（SSR） | `037_costume.model.json` |
| 演出服·夏天，投入「最爱」的怀抱（SSR） | `038_costume.model.json` |
| 演出服·动人心弦的旋律（SR） | `039_costume.model.json` |
| 演出服·勇敢的一步（UR） | `040_costume.model.json` |
| 演出服·一直以来支持我的人（UR） | `041_costume.model.json` |
| 演出服·心灵的色彩（R） | `042_costume.model.json` |
| 演出服·宛如星空一般（UR） | `043_costume.model.json` |
| 演出服·挑战钓水球！（UR） | `044_costume.model.json` |
| 演出服·将光辉释放向天空（SR） | `045_costume.model.json` |
| 演出服·相信・我 | `046_costume.model.json` |
| 演出服·高贵的微蓝 | `047_costume.model.json` |
| 演出服·北极星 | `048_costume.model.json` |
| 演出服·再次闪耀 | `049_costume.model.json` |
| 演出服·心跳加速的大小姐学校 | `050_costume.model.json` |
| 演出服·如今，在憧憬的地方（SSR） | `051_costume.model.json` |
| 活动·梦想祭·在萤火中见到的未来 | `052_costume.model.json` |
| 活动·梦想祭·拥抱光芒（UR） | `053_costume.model.json` |
| 活动·梦想祭·镜头前的羞涩（UR） | `054_costume.model.json` |
| 活动·闪耀祭·天蓝色的海洋 | `055_costume.model.json` |
| 活动·5周年特别服 | `056_costume.model.json` |
| 剧情·活动119剧情01 | `057_costume.model.json` |
| 剧情·活动132剧情01 | `058_costume.model.json` |
| 剧情·活动194剧情01 | `059_costume.model.json` |
| 剧情·活动203剧情01 | `060_costume.model.json` |
| 剧情·活动203剧情02 | `061_costume.model.json` |
| 剧情·活动266剧情01 | `062_costume.model.json` |
| 剧情·活动272剧情01 | `063_costume.model.json` |
| 剧情·活动340剧情01 | `064_costume.model.json` |
| 季节·2022振袖 | `065_costume.model.json` |
| 季节·2024振袖 | `066_costume.model.json` |
| 季节·泳装 | `067_costume.model.json` |
| 生日·2021 | `068_costume.model.json` |
| 生日·2022 | `069_costume.model.json` |
| 联动·bilibili联动（UR） | `070_costume.model.json` |
| 联动·甜蜜的耳语（UR） | `071_costume.model.json` |
| 联动·初音未来·深海少女 | `072_costume.model.json` |
| 其他·2021愚人节 | `073_costume.model.json` |

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
