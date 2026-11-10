# 珠手知由（CHU²）（Garupa）

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
| 常服·2023 | `002_costume.model.json` |
| 常服·夏2023 | `003_costume.model.json` |
| 常服·冬2023 | `004_costume.model.json` |
| 校服·冬季 | `005_costume.model.json` |
| 校服·冬季2023 | `006_costume.model.json` |
| 演出服·EXPOSE | `007_costume.model.json` |
| 演出服·改变世界的力量（SSR） | `008_costume.model.json` |
| 演出服·衣橱之泪（SR） | `009_costume.model.json` |
| 演出服·World is ours！（SSR） | `010_costume.model.json` |
| 演出服·大家一起演奏（SR） | `011_costume.model.json` |
| 演出服·I'm so excited！（SR） | `012_costume.model.json` |
| 演出服·闪亮的舞步（R） | `013_costume.model.json` |
| 演出服·因为是RAS，这是当然的（SR） | `014_costume.model.json` |
| 演出服·盛夏的危机！？（SSR） | `015_costume.model.json` |
| 演出服·What's happen！？（SR） | `016_costume.model.json` |
| 演出服·最强女学生（R） | `017_costume.model.json` |
| 演出服·令人落泪的感情（SSR） | `018_costume.model.json` |
| 演出服·检查要足够细致（SR） | `019_costume.model.json` |
| 演出服·丽厨哑睡莲 总长（SSR） | `020_costume.model.json` |
| 演出服·Pop'n future | `021_costume.model.json` |
| 演出服·真不像我 | `022_costume.model.json` |
| 演出服·烦人的电话（SSR） | `023_costume.model.json` |
| 演出服·燃烧的渴望（UR） | `024_costume.model.json` |
| 演出服·热热闹闹过新年（SR） | `025_costume.model.json` |
| 演出服·忽右忽左（SSR） | `026_costume.model.json` |
| 演出服·不会放开你（UR） | `027_costume.model.json` |
| 演出服·Invasion（UR） | `028_costume.model.json` |
| 演出服·因爱而温暖（SSR） | `029_costume.model.json` |
| 演出服·日式风格（R） | `030_costume.model.json` |
| 演出服·一触即发？互相瞪视（SSR） | `031_costume.model.json` |
| 演出服·喜欢与讨厌（UR） | `032_costume.model.json` |
| 演出服·突破重围（SSR） | `033_costume.model.json` |
| 演出服·in the mirror（SSR） | `034_costume.model.json` |
| 演出服·这条道路（UR） | `035_costume.model.json` |
| 演出服·Don't wake up！（SR） | `036_costume.model.json` |
| 演出服·Dog Fight！ | `037_costume.model.json` |
| 演出服·Rampage!!! | `038_costume.model.json` |
| 活动·梦想祭·生疏的手法 | `039_costume.model.json` |
| 活动·梦想祭·雨天的小小邂逅（UR） | `040_costume.model.json` |
| 活动·梦想祭·这样的休假方式（UR） | `041_costume.model.json` |
| 活动·闪耀祭·低声说出的Thanks | `042_costume.model.json` |
| 活动·5周年特别服 | `043_costume.model.json` |
| 剧情·活动158剧情01 | `044_costume.model.json` |
| 剧情·活动187剧情01 | `045_costume.model.json` |
| 剧情·活动308剧情01 | `046_costume.model.json` |
| 季节·2022振袖 | `047_costume.model.json` |
| 季节·2024振袖 | `048_costume.model.json` |
| 生日·2021 | `049_costume.model.json` |
| 生日·2022 | `050_costume.model.json` |
| 联动·初音未来·劣等上等 | `051_costume.model.json` |
| 其他·2021愚人节 | `052_costume.model.json` |

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
