# 宇田川巴（Garupa）

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
| 常服·睡衣 | `008_costume.model.json` |
| 常服·练习服 | `009_costume.model.json` |
| 校服·夏季 | `010_costume.model.json` |
| 校服·夏季2023 | `011_costume.model.json` |
| 校服·夏季S2 | `012_costume.model.json` |
| 校服·夏季V3 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 校服·冬季2023 | `015_costume.model.json` |
| 校服·冬季S2 | `016_costume.model.json` |
| 演出服·多年的发小（R） | `017_costume.model.json` |
| 演出服·擅闯婚礼之人（SR） | `018_costume.model.json` |
| 演出服·穿睡衣的患者（SSR） | `019_costume.model.json` |
| 演出服·阶梯上的怪谈（R） | `020_costume.model.json` |
| 演出服·无以言表之物（SR） | `021_costume.model.json` |
| 演出服·巫女帮手（R） | `022_costume.model.json` |
| 演出服·梦幻开演！（R） | `023_costume.model.json` |
| 演出服·永远的夕阳（SSR） | `024_costume.model.json` |
| 演出服·守护到底！（SR） | `025_costume.model.json` |
| 演出服·和太鼓的魅力（SSR） | `026_costume.model.json` |
| 演出服·Festa（SR） | `027_costume.model.json` |
| 演出服·姐姐的自尊心（SSR） | `028_costume.model.json` |
| 演出服·属于我们的夕阳（SR） | `029_costume.model.json` |
| 演出服·帅气的红色（SR） | `030_costume.model.json` |
| 演出服·一勺入魂（SSR） | `031_costume.model.json` |
| 演出服·有魄力的学姐（SR） | `032_costume.model.json` |
| 演出服·Twilight butler（R） | `033_costume.model.json` |
| 演出服·重温回忆（SSR） | `034_costume.model.json` |
| 演出服·感受北欧之风（R） | `035_costume.model.json` |
| 演出服·帅气的慰问品（SR） | `036_costume.model.json` |
| 演出服·人气宠儿（SSR） | `037_costume.model.json` |
| 演出服·紧急情况（SR） | `038_costume.model.json` |
| 演出服·RIDEtheWAVE（SR） | `039_costume.model.json` |
| 演出服·伙伴由我来守护（SR） | `040_costume.model.json` |
| 演出服·白色圣诞（R） | `041_costume.model.json` |
| 演出服·燃烧・骄傲（SSR） | `042_costume.model.json` |
| 演出服·伴随着热情（SR） | `043_costume.model.json` |
| 演出服·绯红之夜（SSR） | `044_costume.model.json` |
| 演出服·兴奋不已的预感（SSR） | `045_costume.model.json` |
| 演出服·最爱的乐句（R） | `046_costume.model.json` |
| 演出服·商店街的救世主（SSR） | `047_costume.model.json` |
| 演出服·在船上萌发的情谊（SR） | `048_costume.model.json` |
| 演出服·接住花瓣（SR） | `049_costume.model.json` |
| 演出服·绯红色的决心 | `050_costume.model.json` |
| 演出服·#万圣节快乐（SSR） | `051_costume.model.json` |
| 演出服·使出全力之后（SR） | `052_costume.model.json` |
| 演出服·银河级的沥面技艺（UR） | `053_costume.model.json` |
| 演出服·乌云的彼岸（R） | `054_costume.model.json` |
| 演出服·为万圣节帮忙（SR） | `055_costume.model.json` |
| 演出服·来自天台的消息（SSR） | `056_costume.model.json` |
| 演出服·为了寻找晚霞（UR） | `057_costume.model.json` |
| 演出服·还不够，再来一次（R） | `058_costume.model.json` |
| 演出服·面VS汤（UR） | `059_costume.model.json` |
| 演出服·清澈的橙色（SR） | `060_costume.model.json` |
| 演出服·日常30帧（UR） | `061_costume.model.json` |
| 演出服·优雅的装扮（R） | `062_costume.model.json` |
| 演出服·知晓寂寞的人（SSR） | `063_costume.model.json` |
| 演出服·未曾知晓的彼岸（UR） | `064_costume.model.json` |
| 演出服·演奏后的一杯！（SR） | `065_costume.model.json` |
| 演出服·甜蜜礼物（R） | `066_costume.model.json` |
| 演出服·为了热情的演奏！（UR） | `067_costume.model.json` |
| 演出服·利落的手法（SR） | `068_costume.model.json` |
| 演出服·将这片晚霞铭记于心（UR） | `069_costume.model.json` |
| 演出服·尽情享受祭典中！（SSR） | `070_costume.model.json` |
| 演出服·夜晚才刚开始！（UR） | `071_costume.model.json` |
| 演出服·Grow Up Rock | `072_costume.model.json` |
| 演出服·疾驰之空 | `073_costume.model.json` |
| 演出服·绯红之魂 | `074_costume.model.json` |
| 演出服·激情四溢的青春 | `075_costume.model.json` |
| 演出服·Get up！ | `076_costume.model.json` |
| 演出服·不坦率的家伙 | `077_costume.model.json` |
| 活动·梦想祭·全力排练 | `078_costume.model.json` |
| 活动·梦想祭·打盹的窗边 | `079_costume.model.json` |
| 活动·梦想祭·IN THE ZONE（UR） | `080_costume.model.json` |
| 活动·梦想祭·寻找属于我的颜色（UR） | `081_costume.model.json` |
| 活动·活动340·太鼓 | `082_costume.model.json` |
| 活动·闪耀祭·茜色水洼 | `083_costume.model.json` |
| 活动·巫女 | `084_costume.model.json` |
| 活动·5周年特别服 | `085_costume.model.json` |
| 剧情·活动06 | `086_costume.model.json` |
| 剧情·活动42剧情01 | `087_costume.model.json` |
| 剧情·活动42剧情02 | `088_costume.model.json` |
| 剧情·活动42剧情03 | `089_costume.model.json` |
| 剧情·活动44剧情01 | `090_costume.model.json` |
| 剧情·活动49剧情01 | `091_costume.model.json` |
| 剧情·活动54剧情01 | `092_costume.model.json` |
| 剧情·活动85剧情01 | `093_costume.model.json` |
| 剧情·活动107剧情01 | `094_costume.model.json` |
| 剧情·活动119剧情01 | `095_costume.model.json` |
| 剧情·活动122剧情01 | `096_costume.model.json` |
| 剧情·活动128剧情01 | `097_costume.model.json` |
| 剧情·活动200剧情01 | `098_costume.model.json` |
| 剧情·活动216剧情01 | `099_costume.model.json` |
| 剧情·活动236剧情01 | `100_costume.model.json` |
| 剧情·活动294剧情01 | `101_costume.model.json` |
| 剧情·活动340剧情01 | `102_costume.model.json` |
| 剧情·中学纪念 | `103_costume.model.json` |
| 季节·2018狗年 | `104_costume.model.json` |
| 季节·2019振袖 | `105_costume.model.json` |
| 季节·2025振袖 | `106_costume.model.json` |
| 季节·万圣节 | `107_costume.model.json` |
| 季节·夏日水手服 | `108_costume.model.json` |
| 生日·2021 | `109_costume.model.json` |
| 生日·2022 | `110_costume.model.json` |
| 联动·初音未来·Lost one的号哭 | `111_costume.model.json` |
| 其他·2021愚人节 | `112_costume.model.json` |
| 其他·Garupa T恤 | `113_costume.model.json` |

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
