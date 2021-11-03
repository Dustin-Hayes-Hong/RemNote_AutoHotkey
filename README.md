# RemNote_AutoHotkey

通过 autohotkey 将中文符号转换为英文符号，以便触发 remnote 的相关指令。

例如输入`￥￥`会转换为`$$`以便插入公式。

## 使用方法
下载本仓库后，双击运行 `RemNote_AutoHotkey.exe` 即可

## 支持转换的符号 / 指令

感谢【AutoHotkey(ahk) | 中文社区】的管理员“混沌+AHK2”和“AHK1-僵尸”。

```
 :*T://:://   ;打开命令菜单（相当于中文输入两个顿号 、、）
 :*T:[[::[[   ;使用双链
 :*T:$$::$$   ;输入公式
 :*T:!!::!!   ;寻找日期
 :*T:##::##   ;输入Tag标签
 :*T:%%::%%   ;输入emoji表情 （remnote pro版本可用）
 :*T:``::``   ;输入引述/引用
 
 :*T:>>::>>   ;前向卡片(forward only)
 :*T:<>::<>   ;双向卡片(backward only)
 :*T:<<::<<   ;后向卡片
 :*T::::::    ;concept 的双向卡片
 :*T::>:::>   ;concept 的前向卡片
 :*T::<:::<   ;concept 的后向卡片
 :*T:;;::;;   ;descriptor 的双向卡片
 :*T:;<>::;<> ;descriptor 的前向卡片
 :*T:;<::;<   ;descriptor 的后向卡片
```

注意: 

由于这里使用两个斜杠`//`的方式来触发命令菜单 Command Menu，所以你
需要在 Remnote 的 [Settings] -> [Keyboard Shortcuts] 打开  [Double Slash to Trigger the Command Menu]
