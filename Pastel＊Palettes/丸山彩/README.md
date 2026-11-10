# 丸山彩（Garupa）

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
| 常服·围裙2023 | `002_costume.model.json` |
| 常服·咖啡厅 | `003_costume.model.json` |
| 常服 | `004_costume.model.json` |
| 常服·2023 | `005_costume.model.json` |
| 常服·2023·荧光棒 | `006_costume.model.json` |
| 常服·夏 | `007_costume.model.json` |
| 常服·夏2023 | `008_costume.model.json` |
| 常服·冬 | `009_costume.model.json` |
| 常服·冬2023 | `010_costume.model.json` |
| 常服·快餐店 | `011_costume.model.json` |
| 校服·体操服 | `012_costume.model.json` |
| 校服·夏季 | `013_costume.model.json` |
| 校服·冬季 | `014_costume.model.json` |
| 演出服·憧憬的前方（SSR） | `015_costume.model.json` |
| 演出服·七夕的店员（SR） | `016_costume.model.json` |
| 演出服·全力支持（R） | `017_costume.model.json` |
| 演出服·1日店长（R） | `018_costume.model.json` |
| 演出服·认真・待机……（R） | `019_costume.model.json` |
| 演出服·嘿呦？嘿呦！（SR） | `020_costume.model.json` |
| 演出服·丸山要入场了！（SR） | `021_costume.model.json` |
| 演出服·目标中的理想偶像（SR） | `022_costume.model.json` |
| 演出服·引人注目的照片？（SR） | `023_costume.model.json` |
| 演出服·给予梦想的偶像（SSR） | `024_costume.model.json` |
| 演出服·第一次的拿铁拉花（R） | `025_costume.model.json` |
| 演出服·小彩·南瓜灯（SSR） | `026_costume.model.json` |
| 演出服·舞台副导演（SR） | `027_costume.model.json` |
| 演出服·新年会开始！（SSR） | `028_costume.model.json` |
| 演出服·顽固之人？（R） | `029_costume.model.json` |
| 演出服·小彩的夜间奋斗（SR） | `030_costume.model.json` |
| 演出服·这样就完美了！（SSR） | `031_costume.model.json` |
| 演出服·沉迷社交网站？（R） | `032_costume.model.json` |
| 演出服·恐怖品味（R） | `033_costume.model.json` |
| 演出服·轻抚水面（SSR） | `034_costume.model.json` |
| 演出服·电光火石！（SSR） | `035_costume.model.json` |
| 演出服·自然状态的我（SSR） | `036_costume.model.json` |
| 演出服·情人节的微笑（R） | `037_costume.model.json` |
| 演出服·不会再掉下去了！（SR） | `038_costume.model.json` |
| 演出服·一起欢笑的存在（SSR） | `039_costume.model.json` |
| 演出服·活动前的兴奋（SR） | `040_costume.model.json` |
| 演出服·重叠起来的心意（SR） | `041_costume.model.json` |
| 演出服·被朝霞笼罩（SSR） | `042_costume.model.json` |
| 演出服·为食评苦恼中……（SR） | `043_costume.model.json` |
| 演出服·蓬松粉僵尸（SSR） | `044_costume.model.json` |
| 演出服·完美微笑（SSR） | `045_costume.model.json` |
| 演出服·花样摩登（R） | `046_costume.model.json` |
| 演出服·现在就想传达给你（SR） | `047_costume.model.json` |
| 演出服·修学旅行的乐趣（SR） | `048_costume.model.json` |
| 演出服·Happily ever after（SSR） | `049_costume.model.json` |
| 演出服·蓦然回首，只见青春（SSR） | `050_costume.model.json` |
| 演出服·无数次喊出安可（SR） | `051_costume.model.json` |
| 演出服·毕业（SSR） | `052_costume.model.json` |
| 演出服·享受☆大学生（UR） | `053_costume.model.json` |
| 演出服·饱含梦想（R） | `054_costume.model.json` |
| 演出服·破壁（UR） | `055_costume.model.json` |
| 演出服·因为明白那泪水的含义（SSR） | `056_costume.model.json` |
| 演出服·吃点甜食吧（UR） | `057_costume.model.json` |
| 演出服·纯粹的偶像笨蛋（UR） | `058_costume.model.json` |
| 演出服·一起描绘的故事（UR） | `059_costume.model.json` |
| 演出服·自然风格（R） | `060_costume.model.json` |
| 演出服·心跳加速的自我搜索（SR） | `061_costume.model.json` |
| 演出服·从摩天轮上看到的景色（UR） | `062_costume.model.json` |
| 演出服·婚礼的感动（R） | `063_costume.model.json` |
| 演出服·错答亦是趣味所在？（SSR） | `064_costume.model.json` |
| 演出服·心跳加速☆水上滑梯（UR） | `065_costume.model.json` |
| 演出服·目标只有一个！（SR） | `066_costume.model.json` |
| 演出服·自拍范本♡（UR） | `067_costume.model.json` |
| 演出服·因为知道来时的路（SR） | `068_costume.model.json` |
| 演出服·轻飘飘的爱心♡（UR） | `069_costume.model.json` |
| 演出服·触动心弦之物（SR） | `070_costume.model.json` |
| 演出服·实吃！在地美食（SSR） | `071_costume.model.json` |
| 演出服·在最近的地方（UR） | `072_costume.model.json` |
| 演出服·海边绽放的一朵花（R） | `073_costume.model.json` |
| 演出服·前往辉煌的舞台 | `074_costume.model.json` |
| 演出服·照亮梦想 | `075_costume.model.json` |
| 演出服·盛放的声援 | `076_costume.model.json` |
| 演出服·华丽舞步 | `077_costume.model.json` |
| 演出服·梦色婚礼 | `078_costume.model.json` |
| 演出服·牡丹褶边 | `079_costume.model.json` |
| 演出服·必杀偶像动作☆ | `080_costume.model.json` |
| 活动·第2回总选举（R） | `081_costume.model.json` |
| 活动·梦想祭·我们的海报 | `082_costume.model.json` |
| 活动·梦想祭·瞬间，四目相对 | `083_costume.model.json` |
| 活动·梦想祭·全新偶像姿势！​（UR） | `084_costume.model.json` |
| 活动·梦想祭·镜中无法映照之物（UR） | `085_costume.model.json` |
| 活动·Garupa派对！2019 | `086_costume.model.json` |
| 活动·闪耀祭·秋日之梦 | `087_costume.model.json` |
| 活动·5周年特别服 | `088_costume.model.json` |
| 剧情·活动55剧情01 | `089_costume.model.json` |
| 剧情·活动56剧情01 | `090_costume.model.json` |
| 剧情·活动65剧情01 | `091_costume.model.json` |
| 剧情·活动74剧情01 | `092_costume.model.json` |
| 剧情·活动82剧情01 | `093_costume.model.json` |
| 剧情·活动86剧情01 | `094_costume.model.json` |
| 剧情·活动86剧情02 | `095_costume.model.json` |
| 剧情·活动96剧情01 | `096_costume.model.json` |
| 剧情·活动104剧情01 | `097_costume.model.json` |
| 剧情·活动154剧情01 | `098_costume.model.json` |
| 剧情·徒花School Girl（SSR） | `099_costume.model.json` |
| 剧情·活动154剧情02 | `100_costume.model.json` |
| 剧情·活动195剧情01 | `101_costume.model.json` |
| 剧情·活动216剧情01 | `102_costume.model.json` |
| 剧情·活动278剧情01 | `103_costume.model.json` |
| 剧情·活动304剧情01 | `104_costume.model.json` |
| 剧情·剧情01 | `105_costume.model.json` |
| 剧情·剧情01（2023） | `106_costume.model.json` |
| 季节·2018狗年 | `107_costume.model.json` |
| 季节·2019振袖 | `108_costume.model.json` |
| 季节·2024振袖 | `109_costume.model.json` |
| 季节·夏日水手服 | `110_costume.model.json` |
| 季节·泳装 | `111_costume.model.json` |
| 季节·泳装2023 | `112_costume.model.json` |
| 生日·2021 | `113_costume.model.json` |
| 生日·2022 | `114_costume.model.json` |
| 联动·bilibili联动（SSR） | `115_costume.model.json` |
| 联动·认真对决～！（UR） | `116_costume.model.json` |
| 联动·传说级的偶像（UR） | `117_costume.model.json` |
| 联动·湊阿库娅（hololive） | `118_costume.model.json` |
| 其他·机关小丑 | `119_costume.model.json` |
| 其他·Garupa T恤 | `120_costume.model.json` |

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
