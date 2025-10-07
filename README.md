# Todo-calendar-html
A lightweight HTML wallpaper page for todo lists and calendars.
这是一个轻量的日程待办壁纸html页面。

Preview: https://htmlpreview.github.io/?https://github.com/6SD9/Todo-calendar-html/blob/main/Todo_calendar_wallpaper.html
预览：https://htmlpreview.github.io/?https://github.com/6SD9/Todo-calendar-html/blob/main/Todo_calendar_wallpaper.html
(The preview page does not include the embedded Pinyin input method.)
（预览页面无内嵌拼音输入法）

## Features/特征
- Quickly add / check off / delete todos
- Support for recurring todos
- Changeable background
- Adjustable UI color / transparency / font size
- Import / export schedules in XLSX format
- Built-in Chinese Pinyin input method  
<br></br>
- 快速添加/标记/删除待办
- 支持周期性重复待办添加
- 可更换背景
- ui颜色/透明度/文字大小可调
- 支持日程导入/导出xlsx格式
- 内嵌中文拼音输入法

## Use/使用
Recommended to use together with Wallpaper Engine.<br></br>
建议和wallpaper Engine搭配使用

### Quick test/快速测试
Open a command prompt and:
```
cd <directory-containing-the-file>
```
If you change the port number, also update the port number inside the HTML file/如果要改变端口号请同时更改html文中相应端口号
```
python -m http.server 25095
```
In Wallpaper Engine main window → Open Wallpaper → Open from URL → enter:
wallpaper Engine主界面 → 打开壁纸 → open from url → 输入：
```
http://localhost:25095/Todo_calendar_wallpaper.html
```
Note: When used with Wallpaper Engine you must hide desktop icons in order to type; the system Chinese input method will not work. Please use the page’s built-in Pinyin input method.<br></br>
注意：搭配wallpaper Engine使用时，必须隐藏桌面图标才能输入文字且系统中文输入法失效，请使用页面内嵌的拼音输入法。

### 开机启动
You can use WinSW — see https://github.com/winsw/winsw <br></br>
可以使用winsw，请参阅https://github.com/winsw/winsw


![Screenshot 2025-10-07 143324 ](https://github.com/user-attachments/assets/ebc55342-bb6b-473c-b701-712f9f2e98bb)


### 其他
The Pinyin dictionary was derived from Google Pinyin IME (Apache License) and has been processed.<br></br>
拼音库由Google PinyinIME(Apache License)经过处理得到
