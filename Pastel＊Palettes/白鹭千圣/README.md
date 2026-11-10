# 白鹭千圣（Garupa）

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
| 常服·咖啡厅 | `002_costume.model.json` |
| 常服 | `003_costume.model.json` |
| 常服·2023 | `004_costume.model.json` |
| 常服·2023·荧光棒 | `005_costume.model.json` |
| 常服·夏 | `006_costume.model.json` |
| 常服·夏2023 | `007_costume.model.json` |
| 常服·冬 | `008_costume.model.json` |
| 常服·冬2023 | `009_costume.model.json` |
| 常服·练习服 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·冬季 | `012_costume.model.json` |
| 演出服·红心女王（R） | `013_costume.model.json` |
| 演出服·纯白的居所（SR） | `014_costume.model.json` |
| 演出服·推心置腹的伙伴（SSR） | `015_costume.model.json` |
| 演出服·朱丽叶之名（SR） | `016_costume.model.json` |
| 演出服·认真・恐慌（SR） | `017_costume.model.json` |
| 演出服·留宿会（SSR） | `018_costume.model.json` |
| 演出服·偶像的规则（R） | `019_costume.model.json` |
| 演出服·延续梦想之路（SSR） | `020_costume.model.json` |
| 演出服·向阳处的片刻时光（SSR） | `021_costume.model.json` |
| 演出服·偶像·女巫（SR） | `022_costume.model.json` |
| 演出服·美好的同款（SR） | `023_costume.model.json` |
| 演出服·模范偶像（SR） | `024_costume.model.json` |
| 演出服·光芒四溢（SSR） | `025_costume.model.json` |
| 演出服·容量超载（SSR） | `026_costume.model.json` |
| 演出服·心旷神怡（SSR） | `027_costume.model.json` |
| 演出服·若是眺望远方（SR） | `028_costume.model.json` |
| 演出服·铭记这个特别瞬间（SR） | `029_costume.model.json` |
| 演出服·因为有小薰在（SSR） | `030_costume.model.json` |
| 演出服·要注意混合方法！（SR） | `031_costume.model.json` |
| 演出服·能够走多远？（R） | `032_costume.model.json` |
| 演出服·Country Flower（R） | `033_costume.model.json` |
| 演出服·期待高涨的安可（SR） | `034_costume.model.json` |
| 演出服·互相支援的存在（SSR） | `035_costume.model.json` |
| 演出服·绽放在水面的花朵（SR） | `036_costume.model.json` |
| 演出服·迈向舞台灯光（SSR） | `037_costume.model.json` |
| 演出服·无法抑制的感情（SR） | `038_costume.model.json` |
| 演出服·无声的支持（R） | `039_costume.model.json` |
| 演出服·与飘舞的樱花花瓣一起（SSR） | `040_costume.model.json` |
| 演出服·职业意识僵尸（SSR） | `041_costume.model.json` |
| 演出服·跑腿女服务生（R） | `042_costume.model.json` |
| 演出服·保持坦率的你（SSR） | `043_costume.model.json` |
| 演出服·庆祝新的一年（SSR） | `044_costume.model.json` |
| 演出服·传播的热意（R） | `045_costume.model.json` |
| 演出服·耀眼夺目的历史（SSR） | `046_costume.model.json` |
| 演出服·狗狗要通过（SR） | `047_costume.model.json` |
| 演出服·眸中倒映之花（SSR） | `048_costume.model.json` |
| 演出服·艳羡与微笑（SR） | `049_costume.model.json` |
| 演出服·致王子殿下（SSR） | `050_costume.model.json` |
| 演出服·先一步到来的春天 | `051_costume.model.json` |
| 演出服·毕业（SSR） | `052_costume.model.json` |
| 演出服·一起迈出一步（UR） | `053_costume.model.json` |
| 演出服·新的校园（SSR） | `054_costume.model.json` |
| 演出服·为了见到开心的表情（SR） | `055_costume.model.json` |
| 演出服·正因为想要守护（UR） | `056_costume.model.json` |
| 演出服·深厚信赖（R） | `057_costume.model.json` |
| 演出服·你给我的勇气（UR） | `058_costume.model.json` |
| 演出服·只给一条建议（SSR） | `059_costume.model.json` |
| 演出服·光舞的旋律（UR） | `060_costume.model.json` |
| 演出服·勾起拍摄冲动的侧脸（SR） | `061_costume.model.json` |
| 演出服·看一眼就懂啦！（UR） | `062_costume.model.json` |
| 演出服·LOVELY CAT（R） | `063_costume.model.json` |
| 演出服·我的心意（UR） | `064_costume.model.json` |
| 演出服·遗落之物（UR） | `065_costume.model.json` |
| 演出服·悬崖边的告白（SR） | `066_costume.model.json` |
| 演出服·欢喜之环（UR） | `067_costume.model.json` |
| 演出服·For One Night Only（UR） | `068_costume.model.json` |
| 演出服·前往辉煌的舞台 | `069_costume.model.json` |
| 演出服·照亮梦想 | `070_costume.model.json` |
| 演出服·盛放的声援 | `071_costume.model.json` |
| 演出服·梦色婚礼 | `072_costume.model.json` |
| 演出服·牡丹褶边 | `073_costume.model.json` |
| 演出服·目标的距离 | `074_costume.model.json` |
| 演出服·舞台服 | `075_costume.model.json` |
| 活动·梦想祭·东奔西走 | `076_costume.model.json` |
| 活动·梦想祭·不甘之情融于蒸汽 | `077_costume.model.json` |
| 活动·梦想祭·偶尔放缓步调（UR） | `078_costume.model.json` |
| 活动·梦想祭·My dear dog（UR） | `079_costume.model.json` |
| 活动·闪耀祭·与那天一样的风和你 | `080_costume.model.json` |
| 活动·5周年特别服 | `081_costume.model.json` |
| 剧情·活动55剧情01 | `082_costume.model.json` |
| 剧情·活动86剧情01 | `083_costume.model.json` |
| 剧情·活动86剧情02 | `084_costume.model.json` |
| 剧情·活动86剧情03 | `085_costume.model.json` |
| 剧情·活动104剧情01 | `086_costume.model.json` |
| 剧情·活动154剧情01 | `087_costume.model.json` |
| 剧情·活动154剧情02 | `088_costume.model.json` |
| 剧情·活动195剧情01 | `089_costume.model.json` |
| 剧情·活动216剧情01 | `090_costume.model.json` |
| 剧情·活动278剧情01 | `091_costume.model.json` |
| 剧情·活动344剧情01 | `092_costume.model.json` |
| 剧情·朱丽叶 | `093_costume.model.json` |
| 剧情·剧情01 | `094_costume.model.json` |
| 剧情·剧情01（2023） | `095_costume.model.json` |
| 季节·2018狗年 | `096_costume.model.json` |
| 季节·2019振袖 | `097_costume.model.json` |
| 季节·夏日水手服 | `098_costume.model.json` |
| 生日·2021 | `099_costume.model.json` |
| 生日·2022 | `100_costume.model.json` |
| 联动·更加注视我吧（UR） | `101_costume.model.json` |
| 联动·湊阿库娅（hololive） | `102_costume.model.json` |
| 其他·机关小丑 | `103_costume.model.json` |
| 其他·Garupa T恤 | `104_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。

## 统一点击规则

| 实际点击位置 | 效果 |
|---|---|
| 头顶、刘海上部 | 切换表情 |
| 脸部下半部 | 随机语音，按开关显示字幕 |
| 上身中央 | 播放普通动作 |
| 画面右侧手臂 | 角色左臂动作 |
| 画面左侧手臂 | 角色右臂动作 |
| 腰部、衣服中段 | 直接随机换装 |
| 腿部、衣服下段 | 打开主菜单 |

每套衣装均包含七个独立矩形点击区，按该衣装默认站姿的头部和身体比例定位，跟随模型整体移动和缩放。点击层保持透明，衣服网格合并或隐藏不会取消入口。动作造成的局部身体变形不会改变矩形分区。

仅头像形态也保留相同布局，上身、腰部、腿部入口位于头像下方的透明区域，左右手入口位于对应两侧。

表情、语音和身体动作不会展开菜单。缺少方向动作时播放普通动作，缺少素材时保持待机。点击分区之间的空白可打开主菜单。

请完整重载 `00_integrated` 主入口，保留 `assets/hitareas` 中的点击层文件。

语音菜单提供「开启字幕 / 关闭字幕」开关，默认开启，同一角色换装后保留。点击语音区只播放随机语音及可选字幕。腰部点击随机切换其他衣装，衣装列表仍可从主菜单进入。

语音字幕默认开启，同一角色换装后保留设置。原始资源没有语音文件时，点击语音区显示「当前角色未提供语音素材」，此提示不受字幕开关影响。
