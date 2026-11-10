# 凑友希那 (Garupa)

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
| 008 | 常服·眼镜2023 | `008_costume.model.json` |
| 009 | 校服·夏季 | `009_costume.model.json` |
| 010 | 校服·夏季S2 | `010_costume.model.json` |
| 011 | 校服·冬季 | `011_costume.model.json` |
| 012 | 校服·冬季S2 | `012_costume.model.json` |
| 013 | 演出服·鸟笼歌姬（SSR） | `013_costume.model.json` |
| 014 | 演出服·4个人在咖啡厅（SR） | `014_costume.model.json` |
| 015 | 演出服·第一次戴猫耳（R） | `015_costume.model.json` |
| 016 | 演出服·秋雨天晴后（SSR） | `016_costume.model.json` |
| 017 | 演出服·莉莎风格的歌词（SR） | `017_costume.model.json` |
| 018 | 演出服·秘密时间（SR） | `018_costume.model.json` |
| 019 | 演出服·更上一层楼（SSR） | `019_costume.model.json` |
| 020 | 演出服·潸然泪下（SSR） | `020_costume.model.json` |
| 021 | 演出服·水光潋滟之中（SSR） | `021_costume.model.json` |
| 022 | 演出服·舞台服装（R） | `022_costume.model.json` |
| 023 | 演出服·VERSUS（SSR） | `023_costume.model.json` |
| 024 | 演出服·赠予友人的花束（SSR） | `024_costume.model.json` |
| 025 | 演出服·一起见证的未来（SR） | `025_costume.model.json` |
| 026 | 演出服·连接心意的桥梁（SSR） | `026_costume.model.json` |
| 027 | 演出服·前往光明之处（R） | `027_costume.model.json` |
| 028 | 演出服·描绘回忆（SR） | `028_costume.model.json` |
| 029 | 演出服·手忙脚乱（SSR） | `029_costume.model.json` |
| 030 | 演出服·精彩的凯旋（SSR） | `030_costume.model.json` |
| 031 | 演出服·窗边的微笑（SR） | `031_costume.model.json` |
| 032 | 演出服·终将到达的地方（SSR） | `032_costume.model.json` |
| 033 | 演出服·无敌之歌（SR） | `033_costume.model.json` |
| 034 | 演出服·怀念的景色（SSR） | `034_costume.model.json` |
| 035 | 演出服·巫女的大混乱（SSR） | `035_costume.model.json` |
| 036 | 演出服·坚定的灵魂（R） | `036_costume.model.json` |
| 037 | 演出服·凝聚心灵（SR） | `037_costume.model.json` |
| 038 | 演出服·蓝玫瑰的道路（SSR） | `038_costume.model.json` |
| 039 | 演出服·圣夜的礼物（SSR） | `039_costume.model.json` |
| 040 | 演出服·响彻，创世的歌声（SR） | `040_costume.model.json` |
| 041 | 演出服·波光粼粼中的笑靥之花（SSR） | `041_costume.model.json` |
| 042 | 演出服·等待黎明 | `042_costume.model.json` |
| 043 | 演出服·全新的心动（R） | `043_costume.model.json` |
| 044 | 演出服·直击而来的『今天』（SR） | `044_costume.model.json` |
| 045 | 演出服·花的名字（SSR） | `045_costume.model.json` |
| 046 | 演出服·毕业（SSR） | `046_costume.model.json` |
| 047 | 演出服·穿过招新宣传的浪潮（SR） | `047_costume.model.json` |
| 048 | 演出服·应该选择的是……（UR） | `048_costume.model.json` |
| 049 | 演出服·盛夏的门扉（R） | `049_costume.model.json` |
| 050 | 演出服·压抑的心情（SSR） | `050_costume.model.json` |
| 051 | 演出服·排山倒海一般（SSR） | `051_costume.model.json` |
| 052 | 演出服·顶级拉面（SSR） | `052_costume.model.json` |
| 053 | 演出服·献给身旁微笑的阳光（UR） | `053_costume.model.json` |
| 054 | 演出服·在迷途的尽头（UR） | `054_costume.model.json` |
| 055 | 演出服·专注于指尖（SR） | `055_costume.model.json` |
| 056 | 演出服·世界第一的你们（R） | `056_costume.model.json` |
| 057 | 演出服·坚不可摧的信任（UR） | `057_costume.model.json` |
| 058 | 演出服·双星的轨迹（R） | `058_costume.model.json` |
| 059 | 演出服·感受交融的热度（UR） | `059_costume.model.json` |
| 060 | 演出服·起始之弦（SSR） | `060_costume.model.json` |
| 061 | 演出服·此刻我们的音乐（UR） | `061_costume.model.json` |
| 062 | 演出服·激斗！盛夏的决战！（UR） | `062_costume.model.json` |
| 063 | 演出服·直奔猫咪而去！（SR） | `063_costume.model.json` |
| 064 | 演出服·重叠的蓝色蔷薇 | `064_costume.model.json` |
| 065 | 演出服·Noble・Rose | `065_costume.model.json` |
| 066 | 演出服·崇高志向 | `066_costume.model.json` |
| 067 | 演出服·我的・理想世界 | `067_costume.model.json` |
| 068 | 演出服·环伊甸园 | `068_costume.model.json` |
| 069 | 演出服·神秘花束 | `069_costume.model.json` |
| 070 | 演出服·歌姬的觉悟 | `070_costume.model.json` |
| 071 | 活动·第3回总选举（R） | `071_costume.model.json` |
| 072 | 活动·梦想祭·编织言语 | `072_costume.model.json` |
| 073 | 活动·梦想祭·将身置于皑皑白雪 | `073_costume.model.json` |
| 074 | 活动·梦想祭·校园里的猫（UR） | `074_costume.model.json` |
| 075 | 活动·梦想祭·月光之下（UR） | `075_costume.model.json` |
| 076 | 活动·梦想祭·无人知晓的我（UR） | `076_costume.model.json` |
| 077 | 活动·新手吟游诗人 | `077_costume.model.json` |
| 078 | 活动·Garupa派对！2019 | `078_costume.model.json` |
| 079 | 活动·闪耀祭·不变的温暖 | `079_costume.model.json` |
| 080 | 活动·闪耀祭·不变的温暖（大衣） | `080_costume.model.json` |
| 081 | 活动·5周年特别服 | `081_costume.model.json` |
| 082 | 剧情·活动42剧情01 | `082_costume.model.json` |
| 083 | 剧情·活动52剧情01 | `083_costume.model.json` |
| 084 | 剧情·活动59剧情01 | `084_costume.model.json` |
| 085 | 剧情·活动78剧情01 | `085_costume.model.json` |
| 086 | 剧情·活动89剧情01 | `086_costume.model.json` |
| 087 | 剧情·活动105剧情01 | `087_costume.model.json` |
| 088 | 剧情·活动105剧情02 | `088_costume.model.json` |
| 089 | 剧情·活动119剧情01 | `089_costume.model.json` |
| 090 | 剧情·活动137剧情01 | `090_costume.model.json` |
| 091 | 剧情·活动216剧情01 | `091_costume.model.json` |
| 092 | 剧情·活动216剧情02 | `092_costume.model.json` |
| 093 | 季节·2018狗年 | `093_costume.model.json` |
| 094 | 季节·2019振袖 | `094_costume.model.json` |
| 095 | 季节·2024振袖 | `095_costume.model.json` |
| 096 | 季节·万圣节 | `096_costume.model.json` |
| 097 | 季节·夏日水手服 | `097_costume.model.json` |
| 098 | 季节·泳装2023 | `098_costume.model.json` |
| 099 | 生日·2021 | `099_costume.model.json` |
| 100 | 生日·2022 | `100_costume.model.json` |
| 101 | 联动·bilibili联动（UR） | `101_costume.model.json` |
| 102 | 联动·共度甜蜜时刻（UR） | `102_costume.model.json` |
| 103 | 联动·初音未来·右肩之蝶 | `103_costume.model.json` |
| 104 | 其他·2021愚人节 | `104_costume.model.json` |
| 105 | 其他·Garupa T恤 | `105_costume.model.json` |

素材权利归原权利人，不含播放器及编辑器源工程。

## ????

???????????????????????????????????????????????????????????????

- ?????????????????????????????
- ????????????????????????????????????
- ??????????????????????????????????
- ?????? ? ???? / ?????????????????????????????

???????? `00_integrated` ????????????????????????????????????
