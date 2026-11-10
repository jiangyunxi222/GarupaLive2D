# 奥泽美咲（Garupa）

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
| 默认·米歇尔（舞台） | `002_costume.model.json` |
| 常服·咖啡厅 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 常服·睡衣2023 | `010_costume.model.json` |
| 常服·练习服 | `011_costume.model.json` |
| 校服·体操服 | `012_costume.model.json` |
| 校服·体操服2023 | `013_costume.model.json` |
| 校服·夏季 | `014_costume.model.json` |
| 校服·夏季2023 | `015_costume.model.json` |
| 校服·冬季 | `016_costume.model.json` |
| 校服·冬季2023 | `017_costume.model.json` |
| 校服·冬季V3 | `018_costume.model.json` |
| 演出服·米歇尔·R卡2023 | `019_costume.model.json` |
| 演出服·樱色米歇尔（R） | `020_costume.model.json` |
| 演出服·爱之告白（SR） | `021_costume.model.json` |
| 演出服·我最珍贵的事物（SSR） | `022_costume.model.json` |
| 演出服·魔法师米歇尔（SR） | `023_costume.model.json` |
| 演出服·白组声援团？（R） | `024_costume.model.json` |
| 演出服·企鹅？熊？（R） | `025_costume.model.json` |
| 演出服·冬日装扮（SR） | `026_costume.model.json` |
| 演出服·汗滴也如梦似幻（SSR） | `027_costume.model.json` |
| 演出服·坚定的选手（SR） | `028_costume.model.json` |
| 演出服·米歇尔的口信（SSR） | `029_costume.model.json` |
| 演出服·那边与这边（R） | `030_costume.model.json` |
| 演出服·为何会变成这样（SSR） | `031_costume.model.json` |
| 演出服·在树荫斑驳之地（SR） | `032_costume.model.json` |
| 演出服·这里就是我的归宿（SSR） | `033_costume.model.json` |
| 演出服·练习的恩赐（SR） | `034_costume.model.json` |
| 演出服·深夜谈心（SSR） | `035_costume.model.json` |
| 演出服·不要太操劳（R） | `036_costume.model.json` |
| 演出服·吃惊的内容（SR） | `037_costume.model.json` |
| 演出服·手牵手（SSR） | `038_costume.model.json` |
| 演出服·明亮的光，微弱的光（SR） | `039_costume.model.json` |
| 演出服·大家一起做针线活（SSR） | `040_costume.model.json` |
| 演出服·迷路的圣诞老人（SSR） | `041_costume.model.json` |
| 演出服·舞狮的压力（SR） | `042_costume.model.json` |
| 演出服·专心致志作曲中！（SR） | `043_costume.model.json` |
| 演出服·5号，二垒手（SR） | `044_costume.model.json` |
| 演出服·被夏天的光芒引导（SSR） | `045_costume.model.json` |
| 演出服·语言的桥梁（R） | `046_costume.model.json` |
| 演出服·无奈魔女（SR） | `047_costume.model.json` |
| 演出服·千年一遇的夜晚（SR） | `048_costume.model.json` |
| 演出服·我们是最棒的（SSR） | `049_costume.model.json` |
| 演出服·动如脱兔！（SSR） | `050_costume.model.json` |
| 演出服·服装进度是布料。（SR） | `051_costume.model.json` |
| 演出服·满月下跃动的身影（SSR） | `052_costume.model.json` |
| 演出服·增添一抹笑容（SR） | `053_costume.model.json` |
| 演出服·Q！U！AN！圈！（SSR） | `054_costume.model.json` |
| 演出服·teach about:M（SSR） | `055_costume.model.json` |
| 演出服·直播秀（SR） | `056_costume.model.json` |
| 演出服·Party time！（SSR） | `057_costume.model.json` |
| 演出服·两人一起努力（SSR） | `058_costume.model.json` |
| 演出服·我所不知道的（UR） | `059_costume.model.json` |
| 演出服·秘密回忆（UR） | `060_costume.model.json` |
| 演出服·会议结束后的疲惫（SR） | `061_costume.model.json` |
| 演出服·羞怯的舞台练习（SSR） | `062_costume.model.json` |
| 演出服·与印象重合的笑容（UR） | `063_costume.model.json` |
| 演出服·让世界充满笑容的每一天（UR） | `064_costume.model.json` |
| 演出服·水族馆的后台（SR） | `065_costume.model.json` |
| 演出服·屏幕上映出的笑容（UR） | `066_costume.model.json` |
| 演出服·萌芽的可能性（SR） | `067_costume.model.json` |
| 演出服·从足尖感知到的夏日气息（UR） | `068_costume.model.json` |
| 演出服·被托付的祈愿（SSR） | `069_costume.model.json` |
| 演出服·掌心里的圣诞节（R） | `070_costume.model.json` |
| 演出服·老练的手法（SR） | `071_costume.model.json` |
| 演出服·极致的放松（UR） | `072_costume.model.json` |
| 演出服·两个人的泪颜（UR） | `073_costume.model.json` |
| 演出服·支援型徒步者（SR） | `074_costume.model.json` |
| 演出服·笑容的魔法 | `075_costume.model.json` |
| 演出服·Smile Seeker！ | `076_costume.model.json` |
| 演出服·微笑的行星 | `077_costume.model.json` |
| 演出服·来吧来吧，笑容游行 | `078_costume.model.json` |
| 演出服·笑容∞奇迹！ | `079_costume.model.json` |
| 演出服·米歇尔的秘密 | `080_costume.model.json` |
| 活动·第4回总选举（R） | `081_costume.model.json` |
| 活动·梦想祭·另一个我 | `082_costume.model.json` |
| 活动·梦想祭·放学后继续 | `083_costume.model.json` |
| 活动·梦想祭·三朵绽放的微笑之花（UR） | `084_costume.model.json` |
| 活动·梦想祭·与你共度的放学后（UR） | `085_costume.model.json` |
| 活动·梦想祭·Clutch Play！（UR） | `086_costume.model.json` |
| 活动·5周年特别服 | `087_costume.model.json` |
| 剧情·活动33剧情01 | `088_costume.model.json` |
| 剧情·活动33剧情02 | `089_costume.model.json` |
| 剧情·活动38剧情01 | `090_costume.model.json` |
| 剧情·活动44剧情01 | `091_costume.model.json` |
| 剧情·活动48剧情01 | `092_costume.model.json` |
| 剧情·活动49剧情01 | `093_costume.model.json` |
| 剧情·活动57剧情01 | `094_costume.model.json` |
| 剧情·活动67剧情01 | `095_costume.model.json` |
| 剧情·活动88剧情01 | `096_costume.model.json` |
| 剧情·活动93剧情01 | `097_costume.model.json` |
| 剧情·活动110剧情01 | `098_costume.model.json` |
| 剧情·活动119剧情01 | `099_costume.model.json` |
| 剧情·活动144剧情01 | `100_costume.model.json` |
| 剧情·活动175剧情01 | `101_costume.model.json` |
| 剧情·活动216剧情01 | `102_costume.model.json` |
| 剧情·活动244剧情01 | `103_costume.model.json` |
| 剧情·活动289剧情01 | `104_costume.model.json` |
| 剧情·活动302剧情01 | `105_costume.model.json` |
| 剧情·活动315剧情01 | `106_costume.model.json` |
| 剧情·活动316剧情01 | `107_costume.model.json` |
| 剧情·米歇尔·Hello Happy战队 | `108_costume.model.json` |
| 剧情·Hello Happy战队面具 | `109_costume.model.json` |
| 剧情·剧情01 | `110_costume.model.json` |
| 剧情·剧情03 | `111_costume.model.json` |
| 季节·2018狗年 | `112_costume.model.json` |
| 季节·2019振袖 | `113_costume.model.json` |
| 季节·夏日水手服 | `114_costume.model.json` |
| 季节·泳装2023 | `115_costume.model.json` |
| 生日·2021 | `116_costume.model.json` |
| 生日·2022 | `117_costume.model.json` |
| 联动·白上吹雪（hololive） | `118_costume.model.json` |
| 联动·初音未来·Alien Alien | `119_costume.model.json` |
| 其他·Garupa T恤 | `120_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
