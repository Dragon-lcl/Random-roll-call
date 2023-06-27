# Random-roll-call
这段代码是一个简单的网页应用，它允许用户选择一个文本文件（.txt 格式），然后在界面上显示文件中的内容，并以随机方式在指定的文本框中显示文件中的字符。
代码的主要功能如下：

1.用户可以点击 "开始选择小可爱" 按钮选择一个文本文件。
2.用户可以点击 "就是你了" 按钮停止显示随机字符。
3.选择文件后，文件内容会被读取并保存在 str 数组中。
4.当点击 "开始选择小可爱" 按钮后，通过调用 startTimer() 函数，代码会定时执行 print() 函数，该函数会随机选择 str 数组中的一个字符，并在界面上显示在指定的文本框中。
5.当点击 "就是你了" 按钮后，通过调用 stopTimer() 函数，定时器停止执行，随机字符的显示停止。
此外，代码还进行了一些修正和美化，包括文件选择错误的修复和界面样式的简单调整。
