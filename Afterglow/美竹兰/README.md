# 美竹兰（Garupa）

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
| 常服·睡衣2023 | `008_costume.model.json` |
| 校服·夏季 | `009_costume.model.json` |
| 校服·夏季2023 | `010_costume.model.json` |
| 校服·夏季S2 | `011_costume.model.json` |
| 校服·夏季V3 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季2023 | `014_costume.model.json` |
| 校服·冬季S2 | `015_costume.model.json` |
| 演出服·存在于此的证明（SSR） | `016_costume.model.json` |
| 演出服·暮色的回忆（SR） | `017_costume.model.json` |
| 演出服·恐惧分去一半（SR） | `018_costume.model.json` |
| 演出服·Poppin & Happy（R） | `019_costume.model.json` |
| 演出服·等身大的夜空（SSR） | `020_costume.model.json` |
| 演出服·不变的友情（SSR） | `021_costume.model.json` |
| 演出服·章鱼毛巾（SR） | `022_costume.model.json` |
| 演出服·或许还挺有趣的？（R） | `023_costume.model.json` |
| 演出服·兰的眼神交流（R） | `024_costume.model.json` |
| 演出服·Scarlet（SSR） | `025_costume.model.json` |
| 演出服·太热了……（SR） | `026_costume.model.json` |
| 演出服·逐渐改变的天空（SSR） | `027_costume.model.json` |
| 演出服·强硬派不良少女？（R） | `028_costume.model.json` |
| 演出服·大冒险（SR） | `029_costume.model.json` |
| 演出服·优哉游哉地赏花（SR） | `030_costume.model.json` |
| 演出服·戴眼镜的我（SSR） | `031_costume.model.json` |
| 演出服·受邀参加盛宴之人（SR） | `032_costume.model.json` |
| 演出服·伴娘（R） | `033_costume.model.json` |
| 演出服·大家一起找吧（SR） | `034_costume.model.json` |
| 演出服·真挚的心意（SSR） | `035_costume.model.json` |
| 演出服·别拿相机对着我！（SR） | `036_costume.model.json` |
| 演出服·和兰小兔一起散步（R） | `037_costume.model.json` |
| 演出服·轻柔的风（SSR） | `038_costume.model.json` |
| 演出服·回礼作战准备就绪（SR） | `039_costume.model.json` |
| 演出服·保持自我（SR） | `040_costume.model.json` |
| 演出服·迈向明天的步伐（SR） | `041_costume.model.json` |
| 演出服·害羞的少女（SR） | `042_costume.model.json` |
| 演出服·反抗精神（SSR） | `043_costume.model.json` |
| 演出服·对朋友的信任（R） | `044_costume.model.json` |
| 演出服·柔和的热情（SSR） | `045_costume.model.json` |
| 演出服·Al-Bukhur在咏唱（SSR） | `046_costume.model.json` |
| 演出服·只要闭上双眼（SR） | `047_costume.model.json` |
| 演出服·资料背后的旋律（SSR） | `048_costume.model.json` |
| 演出服·父亲的舞台（SR） | `049_costume.model.json` |
| 演出服·樱花色的放学后时光（R） | `050_costume.model.json` |
| 演出服·云间缝隙与透出的光芒（SR） | `051_costume.model.json` |
| 演出服·黄昏的约定（SSR） | `052_costume.model.json` |
| 演出服·Scream！！！（SR） | `053_costume.model.json` |
| 演出服·最后的誓言（SSR） | `054_costume.model.json` |
| 演出服·映在镜子里的全新早晨（SSR） | `055_costume.model.json` |
| 演出服·过去的憧憬（UR） | `056_costume.model.json` |
| 演出服·孤高的恶魔猎人·兰（UR） | `057_costume.model.json` |
| 演出服·雨，冰冷地落下（SSR） | `058_costume.model.json` |
| 演出服·坦率传达的话语（UR） | `059_costume.model.json` |
| 演出服·接纳软弱的自己（R） | `060_costume.model.json` |
| 演出服·脚尖的方向（SR） | `061_costume.model.json` |
| 演出服·灿烂，然而……（UR） | `062_costume.model.json` |
| 演出服·粉红兔女郎（R） | `063_costume.model.json` |
| 演出服·一流抓娃娃玩家（SSR） | `064_costume.model.json` |
| 演出服·怀着感激之情（UR） | `065_costume.model.json` |
| 演出服·蒸汽少女（R） | `066_costume.model.json` |
| 演出服·水面上跃动的阳光（UR） | `067_costume.model.json` |
| 演出服·你的世界的颜色（UR） | `068_costume.model.json` |
| 演出服·装饰时要满怀心意（SSR） | `069_costume.model.json` |
| 演出服·勾起小指（UR） | `070_costume.model.json` |
| 演出服·今天，谢谢你（SR） | `071_costume.model.json` |
| 演出服·甜蜜的洗礼（SSR） | `072_costume.model.json` |
| 演出服·Grow Up Rock | `073_costume.model.json` |
| 演出服·疾驰之空 | `074_costume.model.json` |
| 演出服·绯红之魂 | `075_costume.model.json` |
| 演出服·Going on | `076_costume.model.json` |
| 演出服·激情四溢的青春 | `077_costume.model.json` |
| 演出服·Get up！ | `078_costume.model.json` |
| 演出服·斩断迷茫 | `079_costume.model.json` |
| 活动·梦想祭·觉醒的对抗心 | `080_costume.model.json` |
| 活动·梦想祭·被夕阳染红的教室 | `081_costume.model.json` |
| 活动·梦想祭·特等席的景色（UR） | `082_costume.model.json` |
| 活动·梦想祭·凝视之处（UR） | `083_costume.model.json` |
| 活动·Garupa派对！2019 | `084_costume.model.json` |
| 活动·5周年特别服 | `085_costume.model.json` |
| 剧情·活动06 | `086_costume.model.json` |
| 剧情·活动49剧情01 | `087_costume.model.json` |
| 剧情·活动54剧情01 | `088_costume.model.json` |
| 剧情·活动75剧情01 | `089_costume.model.json` |
| 剧情·活动80剧情01 | `090_costume.model.json` |
| 剧情·活动101剧情01 | `091_costume.model.json` |
| 剧情·活动122剧情01 | `092_costume.model.json` |
| 剧情·活动128剧情01 | `093_costume.model.json` |
| 剧情·活动138剧情01 | `094_costume.model.json` |
| 剧情·活动216剧情01 | `095_costume.model.json` |
| 剧情·活动227剧情01 | `096_costume.model.json` |
| 剧情·活动227剧情02 | `097_costume.model.json` |
| 剧情·活动227剧情03 | `098_costume.model.json` |
| 剧情·活动227剧情04 | `099_costume.model.json` |
| 剧情·中学纪念 | `100_costume.model.json` |
| 季节·2018狗年 | `101_costume.model.json` |
| 季节·2019振袖 | `102_costume.model.json` |
| 季节·2024振袖 | `103_costume.model.json` |
| 季节·夏日水手服 | `104_costume.model.json` |
| 季节·泳装2023 | `105_costume.model.json` |
| 生日·2021 | `106_costume.model.json` |
| 生日·2022 | `107_costume.model.json` |
| 联动·bilibili联动（UR） | `108_costume.model.json` |
| 联动·前往恐惧之海，启航吧（UR） | `109_costume.model.json` |
| 联动·初音未来·Lost one的号哭 | `110_costume.model.json` |
| 其他·Garupa T恤 | `111_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
