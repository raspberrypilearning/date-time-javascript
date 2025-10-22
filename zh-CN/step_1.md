JavaScript 有一个 `Date()` 函数，它使用浏览器的时区返回当前日期和时间。

例如：

`2024 年 2 月 19 日 星期一 16:15:20 GMT+0000（格林威治标准时间）`

调用 `Date()` 返回一个字符串。

这是此页面加载时调用 `Date()` 的结果：

<iframe src="https://editor.raspberrypi.org/zh-CN/embed/viewer/comic-character-date" width="100%" height="100" frameborder="0" marginwidth="0" marginheight="0" allowfullscreen> </iframe>

### 创建 Date 对象

此示例创建一个新的 Date 对象，表示当前日期和时间。 它保存在常量 `currentDate` 中。

--- code ---
---
language: js
filename: 
line_numbers: false
---
     
    // 更新版权年份函数  
    const currentDate = new Date();
    
--- /code ---

### 获取日期组件

这些函数检索日期和时间的特定部分：

--- code ---
---
language: js
filename: 
line_numbers: 
line_number_start: 
line_highlights: 
---

    const year = currentDate.getFullYear();
    const month = currentDate.getMonth(); // 从0开始 (0 = 一月, 11 = 十二月)
    const day = currentDate.getDate();
    const hours = currentDate.getHours();
    const minutes = currentDate.getMinutes();
    const seconds = currentDate.getSeconds();
    const milliseconds = currentDate.getMilliseconds();

--- /code ---
