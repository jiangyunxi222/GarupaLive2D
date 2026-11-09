# 宇田川亚子 (Garupa)

在 Live2DViewerEX 中导入 `00_integrated.model.json`。完整复制此角色目录。

整合入口使用固定透明父模型，原有衣装菜单、动作、表情、语音及点击区域保留。
模型 ID 按游戏区分；换装沿用父模型的位置、缩放、旋转和镜像，重复选择当前衣装不重载。
衣装加载时隐藏 150 毫秒后恢复贴图，可能短暂空白；播放器画面效果尚待实测。

| 编号 | 衣装 | 入口 |
|---:|---|---|
| 001 | 默认·舞台 | `001_costume.model.json` |
| 002 | 常服 | `002_costume.model.json` |
| 003 | 常服·2023 | `003_costume.model.json` |
| 004 | 常服·夏 | `004_costume.model.json` |
| 005 | 常服·夏2023 | `005_costume.model.json` |
| 006 | 常服·冬 | `006_costume.model.json` |
| 007 | 常服·冬2023 | `007_costume.model.json` |
| 008 | 校服·夏季 | `008_costume.model.json` |
| 009 | 校服·夏季2023 | `009_costume.model.json` |
| 010 | 校服·夏季S2 | `010_costume.model.json` |
| 011 | 校服·冬季 | `011_costume.model.json` |
| 012 | 校服·冬季2023 | `012_costume.model.json` |
| 013 | 校服·冬季S2 | `013_costume.model.json` |
| 014 | 演出服·专一的上进心（SR） | `014_costume.model.json` |
| 015 | 演出服·列席婚礼！（R） | `015_costume.model.json` |
| 016 | 演出服·大家打起精神来（R） | `016_costume.model.json` |
| 017 | 演出服·巴的专属护士（SSR） | `017_costume.model.json` |
| 018 | 演出服·游泳圈与大海（R） | `018_costume.model.json` |
| 019 | 演出服·永远的憧憬！（SR） | `019_costume.model.json` |
| 020 | 演出服·深渊的死灵法师（SSR） | `020_costume.model.json` |
| 021 | 演出服·擅长滑雪（R） | `021_costume.model.json` |
| 022 | 演出服·大家一起喝下午茶（SR） | `022_costume.model.json` |
| 023 | 演出服·想要追赶（SSR） | `023_costume.model.json` |
| 024 | 演出服·来转圈圈！（SR） | `024_costume.model.json` |
| 025 | 演出服·信念（SSR） | `025_costume.model.json` |
| 026 | 演出服·今年也要干劲十足！（R） | `026_costume.model.json` |
| 027 | 演出服·首次打工？（R） | `027_costume.model.json` |
| 028 | 演出服·白费功夫的关怀（SR） | `028_costume.model.json` |
| 029 | 演出服·连战连胜（SR） | `029_costume.model.json` |
| 030 | 演出服·觉醒吧大魔姬（SSR） | `030_costume.model.json` |
| 031 | 演出服·为了莉莎姐！（SR） | `031_costume.model.json` |
| 032 | 演出服·暗黑漫步者（SSR） | `032_costume.model.json` |
| 033 | 演出服·被解放的力量？（SR） | `033_costume.model.json` |
| 034 | 演出服·为了姐姐（SSR） | `034_costume.model.json` |
| 035 | 演出服·握住对方的手（SR） | `035_costume.model.json` |
| 036 | 演出服·祝福的皇冠（SR） | `036_costume.model.json` |
| 037 | 演出服·发现，帅气（SR） | `037_costume.model.json` |
| 038 | 演出服·黑暗力量那个的变装（R） | `038_costume.model.json` |
| 039 | 演出服·恶灵退散！（SSR） | `039_costume.model.json` |
| 040 | 演出服·蓝玫瑰的保养（SR） | `040_costume.model.json` |
| 041 | 演出服·因为很重要！（SR） | `041_costume.model.json` |
| 042 | 演出服·遵循吾之指引吧（SSR） | `042_costume.model.json` |
| 043 | 演出服·宽广的舞台（SR） | `043_costume.model.json` |
| 044 | 演出服·快乐玫瑰（R） | `044_costume.model.json` |
| 045 | 演出服·期盼已久的特别日子（SSR） | `045_costume.model.json` |
| 046 | 演出服·天真无邪的导火索（R） | `046_costume.model.json` |
| 047 | 演出服·向着新世界飞翔（SSR） | `047_costume.model.json` |
| 048 | 演出服·向着夏季DIVE！（R） | `048_costume.model.json` |
| 049 | 演出服·追赶、超越（SSR） | `049_costume.model.json` |
| 050 | 演出服·名垂青史吧！ | `050_costume.model.json` |
| 051 | 演出服·全身心感受新年日出（R） | `051_costume.model.json` |
| 052 | 演出服·直到生命值降为0！（SSR） | `052_costume.model.json` |
| 053 | 演出服·上吧，Trish（R） | `053_costume.model.json` |
| 054 | 演出服·前往积雨云的彼岸（SSR） | `054_costume.model.json` |
| 055 | 演出服·一、二、三、四！（UR） | `055_costume.model.json` |
| 056 | 演出服·应当守护的事物（UR） | `056_costume.model.json` |
| 057 | 演出服·为了不迷失方向（R） | `057_costume.model.json` |
| 058 | 演出服·欢迎回来，莉莎姐（SR） | `058_costume.model.json` |
| 059 | 演出服·下定决心的奔跑（UR） | `059_costume.model.json` |
| 060 | 演出服·自豪的手工巧克力！（SSR） | `060_costume.model.json` |
| 061 | 演出服·攀向至高的巅峰（UR） | `061_costume.model.json` |
| 062 | 演出服·荣耀骑士（R） | `062_costume.model.json` |
| 063 | 演出服·来吧，踏浪前行（SR） | `063_costume.model.json` |
| 064 | 演出服·帮助我的是（SSR） | `064_costume.model.json` |
| 065 | 演出服·将誓言化为力量（SSR） | `065_costume.model.json` |
| 066 | 演出服·占卜一年的瞬间（SR） | `066_costume.model.json` |
| 067 | 演出服·Re:VENGER（UR） | `067_costume.model.json` |
| 068 | 演出服·沉浸于深渊般的旋律中……（SSR） | `068_costume.model.json` |
| 069 | 演出服·最棒的曲目单！（SR） | `069_costume.model.json` |
| 070 | 演出服·绽放的向日葵（R） | `070_costume.model.json` |
| 071 | 演出服·魔弹射手（SR） | `071_costume.model.json` |
| 072 | 演出服·晕染于纯白的色彩（SSR） | `072_costume.model.json` |
| 073 | 演出服·重叠的蓝色蔷薇 | `073_costume.model.json` |
| 074 | 演出服·Noble・Rose | `074_costume.model.json` |
| 075 | 演出服·崇高志向 | `075_costume.model.json` |
| 076 | 演出服·环伊甸园 | `076_costume.model.json` |
| 077 | 演出服·神秘花束 | `077_costume.model.json` |
| 078 | 演出服·小魔王 | `078_costume.model.json` |
| 079 | 活动·第3回总选举（R） | `079_costume.model.json` |
| 080 | 活动·梦想祭·头号粉丝 | `080_costume.model.json` |
| 081 | 活动·梦想祭·鲜花盛开的夏月之夜 | `081_costume.model.json` |
| 082 | 活动·梦想祭·By my side（UR） | `082_costume.model.json` |
| 083 | 活动·梦想祭·NEAR FUTURE（UR） | `083_costume.model.json` |
| 084 | 活动·奇幻冒险 | `084_costume.model.json` |
| 085 | 活动·闪耀祭·像魔法一样绽放！ | `085_costume.model.json` |
| 086 | 活动·5周年特别服 | `086_costume.model.json` |
| 087 | 剧情·活动33剧情01 | `087_costume.model.json` |
| 088 | 剧情·活动52剧情01 | `088_costume.model.json` |
| 089 | 剧情·活动89剧情01 | `089_costume.model.json` |
| 090 | 剧情·活动97剧情01 | `090_costume.model.json` |
| 091 | 剧情·活动105剧情01 | `091_costume.model.json` |
| 092 | 剧情·活动119剧情01 | `092_costume.model.json` |
| 093 | 剧情·活动156剧情01 | `093_costume.model.json` |
| 094 | 剧情·活动216剧情01 | `094_costume.model.json` |
| 095 | 剧情·活动236剧情01 | `095_costume.model.json` |
| 096 | 剧情·活动335剧情01 | `096_costume.model.json` |
| 097 | 剧情·活动340剧情01 | `097_costume.model.json` |
| 098 | 季节·2018狗年 | `098_costume.model.json` |
| 099 | 季节·2018振袖 | `099_costume.model.json` |
| 100 | 季节·万圣节 | `100_costume.model.json` |
| 101 | 季节·夏日水手服 | `101_costume.model.json` |
| 102 | 季节·泳装 | `102_costume.model.json` |
| 103 | 季节·泳装2023 | `103_costume.model.json` |
| 104 | 生日·2021 | `104_costume.model.json` |
| 105 | 生日·2022 | `105_costume.model.json` |
| 106 | 联动·初音未来·右肩之蝶 | `106_costume.model.json` |
| 107 | 其他·Garupa T恤 | `107_costume.model.json` |
| 108 | 其他·NFO游戏角色 | `108_costume.model.json` |

素材权利归原权利人，不含播放器及编辑器源工程。
