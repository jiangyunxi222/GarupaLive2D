# 山吹沙绫（Garupa）

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
| 演出服·加油面包（SR） | `016_costume.model.json` |
| 演出服·一日限定的新娘（SR） | `017_costume.model.json` |
| 演出服·温柔的慰问品（R） | `018_costume.model.json` |
| 演出服·夕阳下的更衣准备（SSR） | `019_costume.model.json` |
| 演出服·Merry・Surprise!（SSR） | `020_costume.model.json` |
| 演出服·带有许多回忆的物品（SR） | `021_costume.model.json` |
| 演出服·沙绫的告白（SR） | `022_costume.model.json` |
| 演出服·人偶秀（SR） | `023_costume.model.json` |
| 演出服·闪亮的笑容（SSR） | `024_costume.model.json` |
| 演出服·将安宁赠予友人（SSR） | `025_costume.model.json` |
| 演出服·点缀（R） | `026_costume.model.json` |
| 演出服·招牌员工（SSR） | `027_costume.model.json` |
| 演出服·充满回忆的道路（SR） | `028_costume.model.json` |
| 演出服·惊喜礼物（SR） | `029_costume.model.json` |
| 演出服·自然状态的我（SR） | `030_costume.model.json` |
| 演出服·姐姐是魔女（SSR） | `031_costume.model.json` |
| 演出服·正在收集玩具！（SR） | `032_costume.model.json` |
| 演出服·记录下无数个瞬间（SSR） | `033_costume.model.json` |
| 演出服·雨天的野餐♪（SSR） | `034_costume.model.json` |
| 演出服·似曾相识的人影（SR） | `035_costume.model.json` |
| 演出服·相连的羁绊（SSR） | `036_costume.model.json` |
| 演出服·白巧克力海螺包（R） | `037_costume.model.json` |
| 演出服·心情激动的时刻（SSR） | `038_costume.model.json` |
| 演出服·Popipa的优点（SR） | `039_costume.model.json` |
| 演出服·清爽的休假（R） | `040_costume.model.json` |
| 演出服·波子汽水瓶里的回忆（SSR） | `041_costume.model.json` |
| 演出服·加油・海螺包（SR） | `042_costume.model.json` |
| 演出服·愉快的聊天（SR） | `043_costume.model.json` |
| 演出服·朝霞中的优美歌声（SSR） | `044_costume.model.json` |
| 演出服·怀旧的棕褐色 | `045_costume.model.json` |
| 演出服·棱镜·流星 | `046_costume.model.json` |
| 演出服·某时的蓝天（SSR） | `047_costume.model.json` |
| 演出服·为声音提供支援的工作（SSR） | `048_costume.model.json` |
| 演出服·装满口袋的Enjoy（SSR） | `049_costume.model.json` |
| 演出服·站在热闹的桥上（UR） | `050_costume.model.json` |
| 演出服·越狱者（R） | `051_costume.model.json` |
| 演出服·无私的陪伴者（SSR） | `052_costume.model.json` |
| 演出服·那些鲜花盛放的未来（R） | `053_costume.model.json` |
| 演出服·感受未来的悸动（UR） | `054_costume.model.json` |
| 演出服·食欲和心灵都得到满足（SR） | `055_costume.model.json` |
| 演出服·复古♡少女感（R） | `056_costume.model.json` |
| 演出服·去寻找新年气息（UR） | `057_costume.model.json` |
| 演出服·春天的山吹面包节（SR） | `058_costume.model.json` |
| 演出服·向我伸来的手（UR） | `059_costume.model.json` |
| 演出服·定格美好瞬间（SR） | `060_costume.model.json` |
| 演出服·通往明天的旅行（R） | `061_costume.model.json` |
| 演出服·作战大成功！（SR） | `062_costume.model.json` |
| 演出服·这就是我的声音！（UR） | `063_costume.model.json` |
| 演出服·那时的温暖（UR） | `064_costume.model.json` |
| 演出服·超大声援！（SSR） | `065_costume.model.json` |
| 演出服·Colorful Poppin！ | `066_costume.model.json` |
| 演出服·Cheerful Star☆ | `067_costume.model.json` |
| 演出服·Peaceful Jump！ | `068_costume.model.json` |
| 演出服·星光闪耀的日常 | `069_costume.model.json` |
| 演出服·Miracle☆Poppin | `070_costume.model.json` |
| 演出服·宝贵的时间 | `071_costume.model.json` |
| 演出服·配对的发圈 | `072_costume.model.json` |
| 活动·第4回总选举（R） | `073_costume.model.json` |
| 活动·梦想祭·CiRCLE面包祭 | `074_costume.model.json` |
| 活动·梦想祭·对太阳公公挥手 | `075_costume.model.json` |
| 活动·梦想祭·这个挺可爱的♪（UR） | `076_costume.model.json` |
| 活动·梦想祭·被温暖的雪包围（UR） | `077_costume.model.json` |
| 活动·活动09 | `078_costume.model.json` |
| 活动·Poppin'Party Fes | `079_costume.model.json` |
| 活动·5周年特别服 | `080_costume.model.json` |
| 剧情·第0章Live | `081_costume.model.json` |
| 剧情·第0章睡衣 | `082_costume.model.json` |
| 剧情·活动92剧情01 | `083_costume.model.json` |
| 剧情·活动108剧情01 | `084_costume.model.json` |
| 剧情·活动119剧情01 | `085_costume.model.json` |
| 剧情·活动160剧情01 | `086_costume.model.json` |
| 剧情·活动216剧情01 | `087_costume.model.json` |
| 剧情·活动236剧情01 | `088_costume.model.json` |
| 季节·2018狗年 | `089_costume.model.json` |
| 季节·2019振袖 | `090_costume.model.json` |
| 季节·2025振袖 | `091_costume.model.json` |
| 季节·圣诞01 | `092_costume.model.json` |
| 季节·夏日水手服 | `093_costume.model.json` |
| 季节·浴衣 | `094_costume.model.json` |
| 生日·2021 | `095_costume.model.json` |
| 生日·2022 | `096_costume.model.json` |
| 联动·时乃空（hololive） | `097_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `098_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `099_costume.model.json` |
| 其他·2021愚人节 | `100_costume.model.json` |
| 其他·CHiSPA | `101_costume.model.json` |
| 其他·Garupa T恤 | `102_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
