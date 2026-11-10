# 桐谷透子（Garupa）

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
| 演出服·大家一起摆姿势☆（SSR） | `012_costume.model.json` |
| 演出服·悔恨之后（SR） | `013_costume.model.json` |
| 演出服·不拘小节的旋律（SR） | `014_costume.model.json` |
| 演出服·最强的气氛制造者（R） | `015_costume.model.json` |
| 演出服·雄辩的热情（SSR） | `016_costume.model.json` |
| 演出服·不擅长看书（R） | `017_costume.model.json` |
| 演出服·我真是天才！（SSR） | `018_costume.model.json` |
| 演出服·不服输的心情（SR） | `019_costume.model.json` |
| 演出服·我的假期（SSR） | `020_costume.model.json` |
| 演出服·我会向上走（SR） | `021_costume.model.json` |
| 演出服·超绚丽的水花（SR） | `022_costume.model.json` |
| 演出服·秒速和魔物交上朋友（SR） | `023_costume.model.json` |
| 演出服·一辈子的请求D.C.（SSR） | `024_costume.model.json` |
| 演出服·Sulky Girl（SR） | `025_costume.model.json` |
| 演出服·天才恶魔猎人？透子（UR） | `026_costume.model.json` |
| 演出服·玻璃蝴蝶（R） | `027_costume.model.json` |
| 演出服·前往TOCO秀！（SR） | `028_costume.model.json` |
| 演出服·华丽而轻盈（SSR） | `029_costume.model.json` |
| 演出服·无法传达的心情（UR） | `030_costume.model.json` |
| 演出服·收集花瓣（SR） | `031_costume.model.json` |
| 演出服·我们是最棒的！（SR） | `032_costume.model.json` |
| 演出服·泳装射手（SSR） | `033_costume.model.json` |
| 演出服·BEST★ANGLE！（UR） | `034_costume.model.json` |
| 演出服·将思念寄托于风中（R） | `035_costume.model.json` |
| 演出服·梦幻可爱小兔子（R） | `036_costume.model.json` |
| 演出服·审视美的目光（SSR） | `037_costume.model.json` |
| 演出服·能将未来拉近的是……（UR） | `038_costume.model.json` |
| 演出服·透过玻璃的闪耀光芒（UR） | `039_costume.model.json` |
| 演出服·Breaking Blue（R） | `040_costume.model.json` |
| 演出服·将勇气赠予你（UR） | `041_costume.model.json` |
| 演出服·我正在超绝进化中！（SSR） | `042_costume.model.json` |
| 演出服·追思逝去的时光（UR） | `043_costume.model.json` |
| 演出服·高贵的微蓝 | `044_costume.model.json` |
| 演出服·北极星 | `045_costume.model.json` |
| 演出服·杰作完成！ | `046_costume.model.json` |
| 演出服·空前流行浪潮的到来 | `047_costume.model.json` |
| 活动·梦想祭·犯困时的餐桌 | `048_costume.model.json` |
| 活动·梦想祭·最强最上镜的一张！（UR） | `049_costume.model.json` |
| 活动·梦想祭·魅力四射的存在（UR） | `050_costume.model.json` |
| 活动·梦想祭·入迷的天才（UR） | `051_costume.model.json` |
| 活动·5周年特别服 | `052_costume.model.json` |
| 剧情·活动132剧情01 | `053_costume.model.json` |
| 剧情·活动194剧情01 | `054_costume.model.json` |
| 剧情·活动203剧情01 | `055_costume.model.json` |
| 剧情·活动227剧情01 | `056_costume.model.json` |
| 剧情·活动266剧情01 | `057_costume.model.json` |
| 剧情·活动272剧情01 | `058_costume.model.json` |
| 季节·2022振袖 | `059_costume.model.json` |
| 季节·2024振袖 | `060_costume.model.json` |
| 季节·泳装 | `061_costume.model.json` |
| 生日·2021 | `062_costume.model.json` |
| 生日·2022 | `063_costume.model.json` |
| 联动·初音未来·深海少女 | `064_costume.model.json` |
| 其他·2021愚人节 | `065_costume.model.json` |

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
