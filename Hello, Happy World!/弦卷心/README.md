# 弦卷心（Garupa）

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
| 常服·夏 | `005_costume.model.json` |
| 常服·夏2023 | `006_costume.model.json` |
| 常服·冬 | `007_costume.model.json` |
| 常服·冬2023 | `008_costume.model.json` |
| 常服·睡衣2023 | `009_costume.model.json` |
| 校服·体操服2023 | `010_costume.model.json` |
| 校服·夏季 | `011_costume.model.json` |
| 校服·夏季2023 | `012_costume.model.json` |
| 校服·冬季 | `013_costume.model.json` |
| 校服·冬季2023 | `014_costume.model.json` |
| 演出服·赏花特集！（SR） | `015_costume.model.json` |
| 演出服·船上的名侦探（SSR） | `016_costume.model.json` |
| 演出服·Happy革命！（SR） | `017_costume.model.json` |
| 演出服·见习魔女（SSR） | `018_costume.model.json` |
| 演出服·Poppin & After（R） | `019_costume.model.json` |
| 演出服·我也是企鹅！（R） | `020_costume.model.json` |
| 演出服·新年满是开心事（SSR） | `021_costume.model.json` |
| 演出服·各位，要开始了哦！（SR） | `022_costume.model.json` |
| 演出服·最喜欢软绵角色啦!（R） | `023_costume.model.json` |
| 演出服·雨天亦可心情爽朗（SSR） | `024_costume.model.json` |
| 演出服·愉快的相会（R） | `025_costume.model.json` |
| 演出服·令人兴奋的大发现（SR） | `026_costume.model.json` |
| 演出服·与鱼争锋（R） | `027_costume.model.json` |
| 演出服·耀眼的太阳公公（SSR） | `028_costume.model.json` |
| 演出服·激动的作战会议（SR） | `029_costume.model.json` |
| 演出服·立体图画书（SR） | `030_costume.model.json` |
| 演出服·一枚硬币的笑容（SR） | `031_costume.model.json` |
| 演出服·透过玻璃弹珠看世界（SSR） | `032_costume.model.json` |
| 演出服·好奇心的结果（SR） | `033_costume.model.json` |
| 演出服·笑容的节奏（SSR） | `034_costume.model.json` |
| 演出服·为了特别的夜晚（SR） | `035_costume.model.json` |
| 演出服·舞动的龙！（SSR） | `036_costume.model.json` |
| 演出服·7号，右外场手（R） | `037_costume.model.json` |
| 演出服·前往笑容集结的地方！（SR） | `038_costume.model.json` |
| 演出服·闪闪发光的朋友（SR） | `039_costume.model.json` |
| 演出服·微笑魔女（SSR） | `040_costume.model.json` |
| 演出服·连接世界的笑容（SSR） | `041_costume.model.json` |
| 演出服·如果你被孵化出来（SR） | `042_costume.model.json` |
| 演出服·夕阳色的发现（SSR） | `043_costume.model.json` |
| 演出服·找到你的声音！（SSR） | `044_costume.model.json` |
| 演出服·洞悉真实之眼（SR） | `045_costume.model.json` |
| 演出服·两人的回忆+1（SSR） | `046_costume.model.json` |
| 演出服·魔法的工作（SSR） | `047_costume.model.json` |
| 演出服·向着光的1，2，3（SR） | `048_costume.model.json` |
| 演出服·活力欢呼 | `049_costume.model.json` |
| 演出服·笑容大游行♪（UR） | `050_costume.model.json` |
| 演出服·青梅竹马是留学生（SSR） | `051_costume.model.json` |
| 演出服·来一份青春！（SR） | `052_costume.model.json` |
| 演出服·盛夏的宝物（UR） | `053_costume.model.json` |
| 演出服·微笑☆女演员（R） | `054_costume.model.json` |
| 演出服·充满童心的你（SR） | `055_costume.model.json` |
| 演出服·心心相通（UR） | `056_costume.model.json` |
| 演出服·度假风格（R） | `057_costume.model.json` |
| 演出服·瞬间成为挚友！（UR） | `058_costume.model.json` |
| 演出服·愿祈祷传向天空（SR） | `059_costume.model.json` |
| 演出服·自由体验进行中（R） | `060_costume.model.json` |
| 演出服·倾谈之夜（UR） | `061_costume.model.json` |
| 演出服·享受☆畅玩（UR） | `062_costume.model.json` |
| 演出服·两张灿烂的笑脸（SR） | `063_costume.model.json` |
| 演出服·委托蜂拥而至！（SSR） | `064_costume.model.json` |
| 演出服·悠闲午睡（SR） | `065_costume.model.json` |
| 演出服·朝着比赛前进！（SSR） | `066_costume.model.json` |
| 演出服·这也是『最棒的夏天』（UR） | `067_costume.model.json` |
| 演出服·微笑徒步者（UR） | `068_costume.model.json` |
| 演出服·笑容的魔法 | `069_costume.model.json` |
| 演出服·Smile Seeker！ | `070_costume.model.json` |
| 演出服·微笑的行星 | `071_costume.model.json` |
| 演出服·满脸喜色的哼唱♪ | `072_costume.model.json` |
| 演出服·来吧来吧，笑容游行 | `073_costume.model.json` |
| 演出服·笑容∞奇迹！ | `074_costume.model.json` |
| 演出服·无敌的主人公 | `075_costume.model.json` |
| 活动·梦想祭·全员欢迎！ | `076_costume.model.json` |
| 活动·梦想祭·水中乐园 | `077_costume.model.json` |
| 活动·梦想祭·像做梦一样（UR） | `078_costume.model.json` |
| 活动·梦想祭·浪漫戏剧（UR） | `079_costume.model.json` |
| 活动·活动03 | `080_costume.model.json` |
| 活动·Garupa派对！2019 | `081_costume.model.json` |
| 活动·5周年特别服 | `082_costume.model.json` |
| 剧情·活动44剧情01 | `083_costume.model.json` |
| 剧情·活动44剧情02 | `084_costume.model.json` |
| 剧情·活动48剧情01 | `085_costume.model.json` |
| 剧情·活动50剧情01 | `086_costume.model.json` |
| 剧情·活动67剧情01 | `087_costume.model.json` |
| 剧情·活动82剧情01 | `088_costume.model.json` |
| 剧情·活动82剧情02 | `089_costume.model.json` |
| 剧情·活动88剧情01 | `090_costume.model.json` |
| 剧情·活动110剧情01 | `091_costume.model.json` |
| 剧情·活动119剧情01 | `092_costume.model.json` |
| 剧情·活动131剧情01 | `093_costume.model.json` |
| 剧情·活动141剧情01 | `094_costume.model.json` |
| 剧情·活动216剧情01 | `095_costume.model.json` |
| 剧情·活动244剧情01 | `096_costume.model.json` |
| 剧情·活动266剧情01 | `097_costume.model.json` |
| 剧情·活动316剧情01 | `098_costume.model.json` |
| 剧情·活动335剧情01 | `099_costume.model.json` |
| 剧情·活动341剧情01 | `100_costume.model.json` |
| 剧情·Hello Happy战队面具 | `101_costume.model.json` |
| 季节·2018狗年 | `102_costume.model.json` |
| 季节·2018振袖 | `103_costume.model.json` |
| 季节·2024振袖 | `104_costume.model.json` |
| 季节·万圣节·无灯笼 | `105_costume.model.json` |
| 季节·夏日水手服 | `106_costume.model.json` |
| 季节·泳装2023 | `107_costume.model.json` |
| 生日·2021 | `108_costume.model.json` |
| 生日·2022 | `109_costume.model.json` |
| 联动·bilibili联动（UR） | `110_costume.model.json` |
| 联动·友情之证（UR） | `111_costume.model.json` |
| 联动·白上吹雪（hololive） | `112_costume.model.json` |
| 联动·初音未来·Alien Alien | `113_costume.model.json` |
| 其他·2021愚人节 | `114_costume.model.json` |
| 其他·Garupa T恤 | `115_costume.model.json` |

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
