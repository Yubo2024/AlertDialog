代码解析：
MainActivity.kt：
监听按钮点击事件，调用 showAlertDialog() 方法弹出 AlertDialog。
AlertDialog.Builder(this) 创建对话框，并设置 标题、内容、按钮。
setPositiveButton("确定") 监听 确认按钮。
setNegativeButton("取消") 监听 取消按钮。

2.activity_main.xml：
只包含一个 按钮，点击后触发 showAlertDialog()。
