# 右键菜单

右键单击用户界面的各种元素时，将显示上下文菜单。这些选项将根据所单击的UI元素的类型而有所不同。

使用单键鼠标的Mac用户可以通过按住++ctrl++键进行“右键单击”操作，某些用户可能需要在系统设置中启用此功能。

此页面上的标题首先按 UI 部分进行排列，然后按右键单击的 UI 元素进行排列。

## 编曲栏

有关 UI 元素的概述，请参阅[编曲栏](../workspace/arrangement.md)。

### 现有轨道

删除或复制轨道（请参阅[管理音轨](../quickstart/managing-tracks.md)）。

### 轨道下方的空白区域

创建新的人声或伴奏轨道（请参阅[管理音轨](../quickstart/managing-tracks.md)）。

### 时间轴（小节号或空白部分）

创建曲速、拍号或循环标记（请参阅[设置拍号和曲速](../quickstart/setting-up-the-score.md)和[播放控件 → 循环标记](../quickstart/playback.md#1-loop-marker)）。

### 时间轴（现有标记）

删除曲速或拍号标记（请参阅[设置拍号和曲速](../quickstart/setting-up-the-score.md)）。

可以通过单击循环模式按钮隐藏循环标记（请参阅[播放控件 → 循环模式](../quickstart/playback.md#3-loop-mode)）。

### 音符预览区域（音符组）

有多个选项会影响音符组的选定实例（请参阅[音符组](groups.md)）：

* 复制、剪切或删除它
* 解散实例
* 将其与父组取消关联
* 更改所选歌手

右键单击伴奏预览时将出现相同的选项，但只有“删除所选内容”选项会产生影响。

### 音符预览区域（其他位置）

将复制的音符组粘贴到编曲栏中的此点（请参阅[音符组](groups.md)）。

## 钢琴卷帘

有关 UI 元素的概述，请参阅[钢琴卷帘](../workspace/piano-roll.md)。

### 时间轴

与在编曲面板中右键单击时间轴时的选项相同（见上文）。

### 音符

将显示多个选项，以各种方式与所选音符进行交互：

* 在当前鼠标位置拆分音符
* 合并所选音符
* 打开所选内容的“[插入歌词](batch-lyrics.md)”对话框
* 重置音符的各个方面
* 生成或裁剪[AI重录](../ai-functions/ai-retakes.md)
* 重新计算所选音符的音高（使用[歌唱](../ai-functions/pitch-mode-sing.md)或[说唱](../ai-functions/pitch-mode-rap.md)音高模式时强制重新渲染）
* 复制、剪切或删除音符
* 选择音符的所有参数（请参见[编辑参数 → 附加参数](../parameters/editing-parameters.md#select-parameters-for-notes)）
* 合并到音符组中（如果音符已在[音符组](groups.md)中则不起作用）
* 解散或分离音符组（如果选择整个[音符组](groups.md)）

### 空白位置

* 粘贴当前复制的音符或音符组
* 更改当前正在编辑的音符组

## 参数面板

有关 UI 元素的概述，请参阅[参数面板](../parameters/parameters-panel.md)。

右键单击参数面板主区域（而不是工具栏）内的任意位置将显示以下选项：

* 复制、剪切或删除选定的参数点（请参见[编辑参数 → 编辑参数曲线](../parameters/editing-parameters.md#editing-parameter-curves)）。
* 粘贴复制的参数点。

如果当前编辑的是“说唱音高”参数，则不会显示任何选项。

## 侧面板和其他菜单

### 文本框

右键单击文本框将提供用于复制、剪切、删除或选择文本的选项，以及在确认更改之前撤消/重做更改的选项。

### 音符组库面板（音符组）

删除音符组及其所有实例（请参阅[音符组](groups.md)）。

### 音符组库面板（音符组实例）

解散、分离或删除音符组的实例（请参阅[音符组](groups.md)）。

---

[报告问题](https://github.com/claire-west/svstudio-manual-zh/issues/new?template=report-a-problem.md&title=[Page: Context Menus in Detail])