# 千早爱音（Garupa）（Garupa）

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
| 常服·2023 | `002_costume.model.json` |
| 校服·夏季2023 | `003_costume.model.json` |
| 校服·冬季2023 | `004_costume.model.json` |
| 演出服·伴随着迷茫（UR） | `005_costume.model.json` |
| 演出服·队长推荐（SR） | `006_costume.model.json` |
| 演出服·和楚楚动人的花一起（R） | `007_costume.model.json` |
| 演出服·赏花会的纪念！（UR） | `008_costume.model.json` |
| 演出服·点单，还是老样子（SR） | `009_costume.model.json` |
| 演出服·要去找吗？（SR） | `010_costume.model.json` |
| 演出服·连接之锚（SR） | `011_costume.model.json` |
| 演出服·黄昏时分的密会（UR） | `012_costume.model.json` |
| 演出服·干劲十足的酷洛！（UR） | `013_costume.model.json` |
| 演出服·要搞好关系的是…… | `014_costume.model.json` |
| 活动·梦想祭·醒来时的哈欠时光（UR） | `015_costume.model.json` |
| 生日·Hopeful birthday！（SSR） | `016_costume.model.json` |
| 联动·前方闪耀的光芒（UR） | `017_costume.model.json` |

固定父模型管理位置、缩放和换装；重复选择当前衣装不会重载。加载期间使用约 150 毫秒的透明遮蔽。

配置与资源引用已校验；完整鼠标点击实测尚未完成。素材权利归原权利人。
