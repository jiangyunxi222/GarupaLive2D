# 市谷有咲（Garupa）

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
| 常服·打工（活动287） | `002_costume.model.json` |
| 常服·咖啡厅 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 常服·睡衣2023 | `010_costume.model.json` |
| 校服·体操服 | `011_costume.model.json` |
| 校服·夏季 | `012_costume.model.json` |
| 校服·夏季2023 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季2023 | `015_costume.model.json` |
| 校服·冬季V3 | `016_costume.model.json` |
| 演出服·在盛开的樱花树下（SSR） | `017_costume.model.json` |
| 演出服·5人一起过夜（R） | `018_costume.model.json` |
| 演出服·有咲梦游仙境（SR） | `019_costume.model.json` |
| 演出服·秘密的场所（SR） | `020_costume.model.json` |
| 演出服·运动员精神（R） | `021_costume.model.json` |
| 演出服·代理监护人（R） | `022_costume.model.json` |
| 演出服·大家一起过圣诞（SR） | `023_costume.model.json` |
| 演出服·享受演奏（R） | `024_costume.model.json` |
| 演出服·心动不已的瞬间（SSR） | `025_costume.model.json` |
| 演出服·满含心意的笔记（SR） | `026_costume.model.json` |
| 演出服·充满回忆的诗笺（SR） | `027_costume.model.json` |
| 演出服·有咲的武士道！？（SSR） | `028_costume.model.json` |
| 演出服·有咲的演奏（R） | `029_costume.model.json` |
| 演出服·展现真实自我（SSR） | `030_costume.model.json` |
| 演出服·送上慰问品（SR） | `031_costume.model.json` |
| 演出服·微笑的场所（SR） | `032_costume.model.json` |
| 演出服·向着可靠的书记（SSR） | `033_costume.model.json` |
| 演出服·用花色来打扮（SR） | `034_costume.model.json` |
| 演出服·因为有大家在（SSR） | `035_costume.model.json` |
| 演出服·最前排的小红帽（SSR） | `036_costume.model.json` |
| 演出服·纸屑飞舞（SR） | `037_costume.model.json` |
| 演出服·提线陶瓷玩偶（R） | `038_costume.model.json` |
| 演出服·让人腼腆的慰劳☆（SSR） | `039_costume.model.json` |
| 演出服·美好旅途（R） | `040_costume.model.json` |
| 演出服·后夜祭也要尽情享受☆（SSR） | `041_costume.model.json` |
| 演出服·制作小册子（SR） | `042_costume.model.json` |
| 演出服·心意相通的感觉（SSR） | `043_costume.model.json` |
| 演出服·甜蜜又苦涩的时间（SR） | `044_costume.model.json` |
| 演出服·如今在这里的我们（SSR） | `045_costume.model.json` |
| 演出服·日晒是大忌！（SR） | `046_costume.model.json` |
| 演出服·星星贴纸优等生（SR） | `047_costume.model.json` |
| 演出服·棒棒糖☆洋娃娃（R） | `048_costume.model.json` |
| 演出服·融入夕阳的疑惑（SR） | `049_costume.model.json` |
| 演出服·和兔兔海螺包一起（SSR） | `050_costume.model.json` |
| 演出服·向着休息室GO！（SR） | `051_costume.model.json` |
| 演出服·天真无邪追忆录（SSR） | `052_costume.model.json` |
| 演出服·未曾体验的光辉 | `053_costume.model.json` |
| 演出服·送上抚慰的话语（SR） | `054_costume.model.json` |
| 演出服·舞台侧的誓言（SSR） | `055_costume.model.json` |
| 演出服·staring（UR） | `056_costume.model.json` |
| 演出服·线索的结果（SSR） | `057_costume.model.json` |
| 演出服·学校☆EXPO（R） | `058_costume.model.json` |
| 演出服·关西演出，出发！（SR） | `059_costume.model.json` |
| 演出服·失控无法停止！（SSR） | `060_costume.model.json` |
| 演出服·搜索开始（SR） | `061_costume.model.json` |
| 演出服·甜美♡洛丽塔（R） | `062_costume.model.json` |
| 演出服·纸片中的未来（UR） | `063_costume.model.json` |
| 演出服·一个人承受的痛楚（SSR） | `064_costume.model.json` |
| 演出服·我爱拉面（R） | `065_costume.model.json` |
| 演出服·不想忘记的时刻（UR） | `066_costume.model.json` |
| 演出服·名导演助理有咲（SSR） | `067_costume.model.json` |
| 演出服·初次见到的一面（UR） | `068_costume.model.json` |
| 演出服·自那时起始终（SSR） | `069_costume.model.json` |
| 演出服·向着大海展翅的天马（UR） | `070_costume.model.json` |
| 演出服·担忧与信赖（SR） | `071_costume.model.json` |
| 演出服·被卷入一场野餐（SSR） | `072_costume.model.json` |
| 演出服·双重♡风味（UR） | `073_costume.model.json` |
| 演出服·以100%为目标（SSR） | `074_costume.model.json` |
| 演出服·荷叶边旋律（R） | `075_costume.model.json` |
| 演出服·Colorful Poppin！ | `076_costume.model.json` |
| 演出服·Cheerful Star☆ | `077_costume.model.json` |
| 演出服·Peaceful Jump！ | `078_costume.model.json` |
| 演出服·星光闪耀的日常 | `079_costume.model.json` |
| 演出服·Miracle☆Poppin | `080_costume.model.json` |
| 演出服·可靠的合作者 | `081_costume.model.json` |
| 演出服·可爱的朋友们 | `082_costume.model.json` |
| 活动·梦想祭·紧急强化合宿！ | `083_costume.model.json` |
| 活动·梦想祭·真是个让人费心的家伙 | `084_costume.model.json` |
| 活动·梦想祭·蒸汽缭绕的旅程（UR） | `085_costume.model.json` |
| 活动·梦想祭·金色地毯（UR） | `086_costume.model.json` |
| 活动·梦想祭·夏日，直到冰块融化（UR） | `087_costume.model.json` |
| 活动·闪耀祭·在黄昏中盛放☆ | `088_costume.model.json` |
| 活动·Poppin'Party Fes | `089_costume.model.json` |
| 活动·5周年特别服 | `090_costume.model.json` |
| 剧情·第0章Live | `091_costume.model.json` |
| 剧情·第0章睡衣 | `092_costume.model.json` |
| 剧情·活动50剧情01 | `093_costume.model.json` |
| 剧情·活动80剧情01 | `094_costume.model.json` |
| 剧情·活动92剧情01 | `095_costume.model.json` |
| 剧情·活动101剧情01 | `096_costume.model.json` |
| 剧情·活动119剧情01 | `097_costume.model.json` |
| 剧情·活动137剧情01 | `098_costume.model.json` |
| 剧情·活动160剧情01 | `099_costume.model.json` |
| 剧情·活动166剧情01 | `100_costume.model.json` |
| 剧情·活动216剧情01 | `101_costume.model.json` |
| 季节·2018狗年 | `102_costume.model.json` |
| 季节·2019振袖 | `103_costume.model.json` |
| 季节·圣诞01 | `104_costume.model.json` |
| 季节·夏日水手服 | `105_costume.model.json` |
| 季节·泳装2023 | `106_costume.model.json` |
| 季节·浴衣 | `107_costume.model.json` |
| 生日·2021 | `108_costume.model.json` |
| 生日·2022 | `109_costume.model.json` |
| 联动·时乃空（hololive） | `110_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `111_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `112_costume.model.json` |
| 其他·2021愚人节 | `113_costume.model.json` |
| 其他·Garupa T恤 | `114_costume.model.json` |

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
