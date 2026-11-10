# 朝日六花（LOCK）（Garupa）

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
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·夏2023 | `005_costume.model.json` |
| 常服·冬2023 | `006_costume.model.json` |
| 校服·夏季 | `007_costume.model.json` |
| 校服·夏季2023 | `008_costume.model.json` |
| 校服·冬季 | `009_costume.model.json` |
| 校服·冬季2023 | `010_costume.model.json` |
| 校服·冬季2 | `011_costume.model.json` |
| 演出服·EXPOSE | `012_costume.model.json` |
| 演出服·六花的全力以赴（SSR） | `013_costume.model.json` |
| 演出服·果然乐队最棒了（SR） | `014_costume.model.json` |
| 演出服·一起万圣节！（SSR） | `015_costume.model.json` |
| 演出服·被鼓动的心跳（R） | `016_costume.model.json` |
| 演出服·Lock on！（SSR） | `017_costume.model.json` |
| 演出服·LOCK SOS！！（SSR） | `018_costume.model.json` |
| 演出服·传达的心意，跃动的心（SR） | `019_costume.model.json` |
| 演出服·分享友情（SR） | `020_costume.model.json` |
| 演出服·相信『我』的勇气（SR） | `021_costume.model.json` |
| 演出服·被铭刻的时光（SR） | `022_costume.model.json` |
| 演出服·前往光芒照耀之处（SSR） | `023_costume.model.json` |
| 演出服·旋律队 义侘哑（SR） | `024_costume.model.json` |
| 演出服·即使分离（SSR） | `025_costume.model.json` |
| 演出服·坐立不安Stay | `026_costume.model.json` |
| 演出服·驯鸽师莅临新年（SR） | `027_costume.model.json` |
| 演出服·我面对事物的方法（UR） | `028_costume.model.json` |
| 演出服·孤高的无敌者（R） | `029_costume.model.json` |
| 演出服·发现了现行犯！？（UR） | `030_costume.model.json` |
| 演出服·For my dear（SSR） | `031_costume.model.json` |
| 演出服·是全垒打！（SR） | `032_costume.model.json` |
| 演出服·笑容的圆环（SSR） | `033_costume.model.json` |
| 演出服·连结奇迹（R） | `034_costume.model.json` |
| 演出服·All-in（SSR） | `035_costume.model.json` |
| 演出服·可爱的贪吃鬼（UR） | `036_costume.model.json` |
| 演出服·打开心门（SSR） | `037_costume.model.json` |
| 演出服·衷心祝福（UR） | `038_costume.model.json` |
| 演出服·在清凉的溪畔（SR） | `039_costume.model.json` |
| 演出服·淡淡的夏日回忆（R） | `040_costume.model.json` |
| 演出服·予黑暗以光明（UR） | `041_costume.model.json` |
| 演出服·活力全开即兴演奏！（SSR） | `042_costume.model.json` |
| 演出服·Stellar Frontline（R） | `043_costume.model.json` |
| 演出服·率直的『喜欢』（UR） | `044_costume.model.json` |
| 演出服·魅惑的异国风情（SSR） | `045_costume.model.json` |
| 演出服·Dog Fight！ | `046_costume.model.json` |
| 演出服·Rampage!!! | `047_costume.model.json` |
| 活动·梦想祭·温泉中的LOCK | `048_costume.model.json` |
| 活动·梦想祭·开心的事要一起做！（UR） | `049_costume.model.json` |
| 活动·梦想祭·只属于我们的泳池（UR） | `050_costume.model.json` |
| 活动·5周年特别服 | `051_costume.model.json` |
| 剧情·活动119剧情01 | `052_costume.model.json` |
| 剧情·活动128剧情01 | `053_costume.model.json` |
| 剧情·活动158剧情01 | `054_costume.model.json` |
| 剧情·活动187剧情01 | `055_costume.model.json` |
| 剧情·活动216剧情01 | `056_costume.model.json` |
| 剧情·活动308剧情01 | `057_costume.model.json` |
| 剧情·剧情01 | `058_costume.model.json` |
| 季节·2022振袖 | `059_costume.model.json` |
| 季节·泳装2023 | `060_costume.model.json` |
| 生日·2021 | `061_costume.model.json` |
| 生日·2022 | `062_costume.model.json` |
| 联动·初音未来·劣等上等 | `063_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
