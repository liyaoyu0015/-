# 表哥 ChatGPT 宠物

大头、黑发、黑西装的「表哥」动画伙伴，带有伸手指向前方的招呼动作。这里提供已完成的宠物精灵图，下载后可在支持自定义宠物的客户端中导入。

![九种动作预览](previews/all-states.gif)

## 下载

- [完整宠物精灵图 spritesheet.png](spritesheet.png)：v2，1536 × 2288，九种动作和十六个看向方向，与本次创建并选用的宠物文件完全一致。
- [兼容版 spritesheet-v1-compat.png](spritesheet-v1-compat.png)：v1，1536 × 1872，保留相同的九种动作，适用于只接受九行精灵图的导入界面；不含十六个看向方向。

点击文件后使用 GitHub 的 Download raw file（下载原始文件）。也可以通过仓库的 Code → Download ZIP 下载全部文件。

## 使用

### 支持精灵图上传的 ChatGPT 界面

在设置中找到宠物（Pets / Pet）和上传宠物（Upload pet），选择下载的 PNG，再选择「表哥」。如果界面提示尺寸必须为 1536 × 1872，请改用兼容版。不同客户端、账户及工作区支持的导入方式可能不同。

### 使用 Pets 插件

将完整版本 `spritesheet.png` 作为附件，在已启用 Pets 插件的聊天中发送：

> 请导入这张现成的宠物精灵图，命名为「表哥」并选用。保留现有图片和全部动作，不要重新生成形象。先验证精灵图，再创建宠物。

### 桌面端显示

如果宠物已经导入并选中但未显示，打开设置 → Pets，刷新并重新选择宠物，再使用 Show pet（显示宠物）。Windows 默认快捷键为 **Windows + Alt + P**。网页宠物与桌面悬浮宠物的显示方式不同。

官方使用说明：[ChatGPT Pets](https://learn.chatgpt.com/docs/pets)。

## 动作

待机、向右跑、向左跑、招手、跳跃、失败反应、等待输入、专注工作、检查成果。完整版本另含顺时针排列的十六个看向方向。

![看向方向预览](previews/look-loop.gif)

![待机到跳跃再回到待机](previews/idle-jump-idle.gif)

## 文件校验

完整版本 `spritesheet.png` 的 SHA-256：

```text
87db2c39fab3bd47fa1232b9ee9f06fbe839ff880e795138b3bc3154dddb515b
```

图片背景透明，完整版本包含 73 个有效动画帧；已通过精灵图结构检查与 Pets 服务校验。`pet.json` 是文件说明元数据，不是某个客户端的安装清单。
