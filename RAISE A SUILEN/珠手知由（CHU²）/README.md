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
