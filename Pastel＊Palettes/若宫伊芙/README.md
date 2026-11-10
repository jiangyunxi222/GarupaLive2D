# 若宫伊芙（Garupa）

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
| 常服·打工2023 | `003_costume.model.json` |
| 常服·咖啡厅 | `004_costume.model.json` |
| 常服 | `005_costume.model.json` |
| 常服·2023 | `006_costume.model.json` |
| 常服·2023·荧光棒 | `007_costume.model.json` |
| 常服·夏 | `008_costume.model.json` |
| 常服·夏2023 | `009_costume.model.json` |
| 常服·冬 | `010_costume.model.json` |
| 常服·冬2023 | `011_costume.model.json` |
| 校服·体操服 | `012_costume.model.json` |
| 校服·夏季 | `013_costume.model.json` |
| 校服·夏季2023 | `014_costume.model.json` |
| 校服·冬季 | `015_costume.model.json` |
| 校服·冬季2023 | `016_costume.model.json` |
| 演出服·期待已久的赏樱（R） | `017_costume.model.json` |
| 演出服·武士道的精神（R） | `018_costume.model.json` |
| 演出服·模特模式（SR） | `019_costume.model.json` |
| 演出服·满含心意的花束（SR） | `020_costume.model.json` |
| 演出服·认真・无念无想（R） | `021_costume.model.json` |
| 演出服·Pastel Maid（R） | `022_costume.model.json` |
| 演出服·最周全的招待（SSR） | `023_costume.model.json` |
| 演出服·第一次捣年糕（SSR） | `024_costume.model.json` |
| 演出服·流行的发型（SR） | `025_costume.model.json` |
| 演出服·不屈的剑士（SR） | `026_costume.model.json` |
| 演出服·属于我的武士道！（SSR） | `027_costume.model.json` |
| 演出服·想要一起分担！（SR） | `028_costume.model.json` |
| 演出服·海边的姿态（SSR） | `029_costume.model.json` |
| 演出服·可爱的吸血鬼（R） | `030_costume.model.json` |
| 演出服·偶然发现的珍品（SR） | `031_costume.model.json` |
| 演出服·不够在行的人（SSR） | `032_costume.model.json` |
| 演出服·一刀两断！（SR） | `033_costume.model.json` |
| 演出服·绽放于新娘手中的幸福（SSR） | `034_costume.model.json` |
| 演出服·沙滩天堂（R） | `035_costume.model.json` |
| 演出服·我们的奢侈时间（SSR） | `036_costume.model.json` |
| 演出服·农场风格（R） | `037_costume.model.json` |
| 演出服·描绘的舞台（SSR） | `038_costume.model.json` |
| 演出服·在河边找到的宝物（SR） | `039_costume.model.json` |
| 演出服·装饰完成！（SR） | `040_costume.model.json` |
| 演出服·兴高采烈（SR） | `041_costume.model.json` |
| 演出服·友爱之伞（SSR） | `042_costume.model.json` |
| 演出服·偶像前辈（R） | `043_costume.model.json` |
| 演出服·通过这双手（SR） | `044_costume.model.json` |
| 演出服·天真的期待（SR） | `045_costume.model.json` |
| 演出服·请将我的声音（SSR） | `046_costume.model.json` |
| 演出服·宇宙船员（R） | `047_costume.model.json` |
| 演出服·武士僵尸（SR） | `048_costume.model.json` |
| 演出服·托盘达人（SR） | `049_costume.model.json` |
| 演出服·偶像大追踪（SSR） | `050_costume.model.json` |
| 演出服·哈！小心考试（SR） | `051_costume.model.json` |
| 演出服·想要支持同伴的信念（SSR） | `052_costume.model.json` |
| 演出服·请交给我！（SR） | `053_costume.model.json` |
| 演出服·成束的真挚祝福（R） | `054_costume.model.json` |
| 演出服·刨冰的精华所在（SR） | `055_costume.model.json` |
| 演出服·蝴蝶飞舞的茶会（SSR） | `056_costume.model.json` |
| 演出服·紧紧拥抱（SSR） | `057_costume.model.json` |
| 演出服·祝来访者福如东海（SR） | `058_costume.model.json` |
| 演出服·心跳加速！？兜风（SR） | `059_costume.model.json` |
| 演出服·呐喊吧，青春当下（UR） | `060_costume.model.json` |
| 演出服·忧郁紫色（R） | `061_costume.model.json` |
| 演出服·绝不让步的信念（UR） | `062_costume.model.json` |
| 演出服·转圈圈♪（SR） | `063_costume.model.json` |
| 演出服·小小的海中宝物（UR） | `064_costume.model.json` |
| 演出服·充满感谢和欣喜（SSR） | `065_costume.model.json` |
| 演出服·将特别的一天献给你（UR） | `066_costume.model.json` |
| 演出服·令人兴奋的出行（R） | `067_costume.model.json` |
| 演出服·猜谜小课堂（SR） | `068_costume.model.json` |
| 演出服·兴奋的试穿时间（UR） | `069_costume.model.json` |
| 演出服·幸福满满的年糕小豆汤（SSR） | `070_costume.model.json` |
| 演出服·寻觅话语（SSR） | `071_costume.model.json` |
| 演出服·加上Hashtag（UR） | `072_costume.model.json` |
| 演出服·眺望杜之都（SSR） | `073_costume.model.json` |
| 演出服·前往辉煌的舞台 | `074_costume.model.json` |
| 演出服·照亮梦想 | `075_costume.model.json` |
| 演出服·盛放的声援 | `076_costume.model.json` |
| 演出服·梦色婚礼 | `077_costume.model.json` |
| 演出服·牡丹褶边 | `078_costume.model.json` |
| 演出服·武士要惺惺相惜 | `079_costume.model.json` |
| 活动·梦想祭·憧憬无法隐藏 | `080_costume.model.json` |
| 活动·梦想祭·枝形吊灯路 | `081_costume.model.json` |
| 活动·梦想祭·独枝匿于幽邃间（UR） | `082_costume.model.json` |
| 活动·梦想祭·自然微笑（UR） | `083_costume.model.json` |
| 活动·梦想祭·浮现的七彩，轻飘于空（UR） | `084_costume.model.json` |
| 活动·5周年特别服 | `085_costume.model.json` |
| 剧情·活动024剧情02 | `086_costume.model.json` |
| 剧情·活动38剧情01 | `087_costume.model.json` |
| 剧情·活动50剧情01 | `088_costume.model.json` |
| 剧情·活动65剧情01 | `089_costume.model.json` |
| 剧情·活动80剧情01 | `090_costume.model.json` |
| 剧情·活动104剧情01 | `091_costume.model.json` |
| 剧情·活动143剧情01 | `092_costume.model.json` |
| 剧情·活动154剧情01 | `093_costume.model.json` |
| 剧情·活动154剧情02 | `094_costume.model.json` |
| 剧情·活动195剧情01 | `095_costume.model.json` |
| 剧情·活动216剧情01 | `096_costume.model.json` |
| 剧情·活动278剧情01 | `097_costume.model.json` |
| 剧情·剧情01 | `098_costume.model.json` |
| 剧情·剧情01（2023） | `099_costume.model.json` |
| 季节·2018狗年 | `100_costume.model.json` |
| 季节·2018振袖 | `101_costume.model.json` |
| 季节·夏日水手服 | `102_costume.model.json` |
| 季节·泳装2023 | `103_costume.model.json` |
| 季节·浴衣2023 | `104_costume.model.json` |
| 生日·2021 | `105_costume.model.json` |
| 生日·2022 | `106_costume.model.json` |
| 联动·湊阿库娅（hololive） | `107_costume.model.json` |
| 其他·2021愚人节 | `108_costume.model.json` |
| 其他·机关小丑 | `109_costume.model.json` |
| 其他·Garupa T恤 | `110_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
