# 户山香澄（Garupa）

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
| 校服·冬季V3 | `016_costume.model.json` |
| 演出服·大家一起赏樱花（SR） | `017_costume.model.json` |
| 演出服·第一位客人（R） | `018_costume.model.json` |
| 演出服·最初的声音（SSR） | `019_costume.model.json` |
| 演出服·宣誓！烟花大会！（R） | `020_costume.model.json` |
| 演出服·大家一起折纸（SR） | `021_costume.model.json` |
| 演出服·圣诞老人突击（R） | `022_costume.model.json` |
| 演出服·举办最棒的演出！（SSR） | `023_costume.model.json` |
| 演出服·和大家一起开演唱会（SR） | `024_costume.model.json` |
| 演出服·仰望星空（SSR） | `025_costume.model.json` |
| 演出服·干劲十足（SR） | `026_costume.model.json` |
| 演出服·走访回忆（SSR） | `027_costume.model.json` |
| 演出服·来·唱歌♪（SR） | `028_costume.model.json` |
| 演出服·商店街的欢呼声（SR） | `029_costume.model.json` |
| 演出服·大成功！？（SSR） | `030_costume.model.json` |
| 演出服·再次来临、樱花飘舞的季节（SSR） | `031_costume.model.json` |
| 演出服·爱之花飞舞的瞬间（SSR） | `032_costume.model.json` |
| 演出服·Living Dead（SR） | `033_costume.model.json` |
| 演出服·来开派对吧！（R） | `034_costume.model.json` |
| 演出服·希望的旋律（SR） | `035_costume.model.json` |
| 演出服·扑过来的僵尸（SR） | `036_costume.model.json` |
| 演出服·那个时候的回忆（SSR） | `037_costume.model.json` |
| 演出服·终于来了呢！（SSR） | `038_costume.model.json` |
| 演出服·将重要之物送到！（SSR） | `039_costume.model.json` |
| 演出服·色彩缤纷的岩石地（SR） | `040_costume.model.json` |
| 演出服·甜蜜时间（SSR） | `041_costume.model.json` |
| 演出服·全力采访！（R） | `042_costume.model.json` |
| 演出服·丝滑巧克力乐园（SR） | `043_costume.model.json` |
| 演出服·STAR☆（SSR） | `044_costume.model.json` |
| 演出服·畅享☆暑假（SSR） | `045_costume.model.json` |
| 演出服·两人一起学习（SSR） | `046_costume.model.json` |
| 演出服·耀眼的新年（R） | `047_costume.model.json` |
| 演出服·请享用点心♪（R） | `048_costume.model.json` |
| 演出服·手工制的许愿星（SR） | `049_costume.model.json` |
| 演出服·找到了吗！？（SR） | `050_costume.model.json` |
| 演出服·向着全新的一片天（SSR） | `051_costume.model.json` |
| 演出服·属于你自己的光明 | `052_costume.model.json` |
| 演出服·闪亮之歌 | `053_costume.model.json` |
| 演出服·开始打工了！（UR） | `054_costume.model.json` |
| 演出服·为新声音干杯（SR） | `055_costume.model.json` |
| 演出服·执行委员长的工作（UR） | `056_costume.model.json` |
| 演出服·给你一个♪（R） | `057_costume.model.json` |
| 演出服·户山院长（UR） | `058_costume.model.json` |
| 演出服·Good Morning☆（SSR） | `059_costume.model.json` |
| 演出服·拉钩钩（SR） | `060_costume.model.json` |
| 演出服·迈向我们的崭新未来（UR） | `061_costume.model.json` |
| 演出服·商店街的☆（SR） | `062_costume.model.json` |
| 演出服·发自内心的尖叫（UR） | `063_costume.model.json` |
| 演出服·今年也要开开心心（SSR） | `064_costume.model.json` |
| 演出服·迫不及待的起点（R） | `065_costume.model.json` |
| 演出服·我们的CiRCLE（UR） | `066_costume.model.json` |
| 演出服·不能输的战斗（SR） | `067_costume.model.json` |
| 演出服·绝佳礼物！（SSR） | `068_costume.model.json` |
| 演出服·来打开那扇门吧！（UR） | `069_costume.model.json` |
| 演出服·有咲和香澄（UR） | `070_costume.model.json` |
| 演出服·纯白婚礼（R） | `071_costume.model.json` |
| 演出服·相信伙伴！（UR） | `072_costume.model.json` |
| 演出服·来自天空的礼物（UR） | `073_costume.model.json` |
| 演出服·Colorful Poppin！ | `074_costume.model.json` |
| 演出服·Cheerful Star☆ | `075_costume.model.json` |
| 演出服·Peaceful Jump！ | `076_costume.model.json` |
| 演出服·Joy time！ | `077_costume.model.json` |
| 演出服·星光闪耀的日常 | `078_costume.model.json` |
| 演出服·Miracle☆Poppin | `079_costume.model.json` |
| 演出服·约定的糖果 | `080_costume.model.json` |
| 演出服·大家在游乐园！ | `081_costume.model.json` |
| 活动·梦想祭·开心的庆功会 | `082_costume.model.json` |
| 活动·梦想祭·向着光辉伸出手 | `083_costume.model.json` |
| 活动·梦想祭·雨水带来的光芒（UR） | `084_costume.model.json` |
| 活动·梦想祭·酣然入梦（UR） | `085_costume.model.json` |
| 活动·Garupa派对！2019 | `086_costume.model.json` |
| 活动·闪耀祭·情谊的礼物 | `087_costume.model.json` |
| 活动·Poppin'Party Fes | `088_costume.model.json` |
| 活动·5周年特别服 | `089_costume.model.json` |
| 剧情·第0章Live | `090_costume.model.json` |
| 剧情·第0章睡衣 | `091_costume.model.json` |
| 剧情·活动44剧情01 | `092_costume.model.json` |
| 剧情·活动65剧情01 | `093_costume.model.json` |
| 剧情·活动80剧情01 | `094_costume.model.json` |
| 剧情·活动102剧情01 | `095_costume.model.json` |
| 剧情·活动119剧情01 | `096_costume.model.json` |
| 剧情·活动119剧情02 | `097_costume.model.json` |
| 剧情·活动124剧情01 | `098_costume.model.json` |
| 剧情·活动128剧情01 | `099_costume.model.json` |
| 剧情·活动147剧情01 | `100_costume.model.json` |
| 剧情·活动160剧情01 | `101_costume.model.json` |
| 剧情·活动216剧情01 | `102_costume.model.json` |
| 剧情·活动312剧情02 | `103_costume.model.json` |
| 剧情·活动335剧情01 | `104_costume.model.json` |
| 季节·2018狗年 | `105_costume.model.json` |
| 季节·2019振袖 | `106_costume.model.json` |
| 季节·2024振袖 | `107_costume.model.json` |
| 季节·圣诞01 | `108_costume.model.json` |
| 季节·夏日水手服 | `109_costume.model.json` |
| 季节·泳装2023 | `110_costume.model.json` |
| 季节·浴衣 | `111_costume.model.json` |
| 生日·2021 | `112_costume.model.json` |
| 生日·2022 | `113_costume.model.json` |
| 联动·bilibili联动（R） | `114_costume.model.json` |
| 联动·bilibili联动（UR） | `115_costume.model.json` |
| 联动·心动合奏♪（UR） | `116_costume.model.json` |
| 联动·时乃空（hololive） | `117_costume.model.json` |
| 联动·初音未来·夜行性ハイズ | `118_costume.model.json` |
| 联动·初音未来·罗密欧与辛德瑞拉 | `119_costume.model.json` |
| 其他·2021愚人节 | `120_costume.model.json` |
| 其他·Garupa T恤 | `121_costume.model.json` |

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
