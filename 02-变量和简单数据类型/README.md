### 2.1 运行hello_world.py时发生的情况

* .py，编辑器将使用Python解释器运行它
* 读取整个程序，确定每个单词的含义
* 比如print就会打印出来内容

### 2.2 变量

添加变量导致Python解释器需要做更多工作。处理第一行代码时，它将变量`message`与文本`"Hello Python world!"`关联起来；处理第二行代码时，它将与变量`message`关联的值打印到屏幕。

```python
message = "Hello Python world!"
print(message)

message = "Hello Python Crash Course world!"
print(message)
```

### 2.2.1 变量的命名和使用

在Python中使用变量时，需要遵守一些规则和指南。违反这些规则将引发错误，而指南旨在让你编写的代码更容易阅读和理解。请务必牢记下述有关变量的规则。

* 变量名只能包含字母、数字和下划线。变量名能以字母或下划线打头，但不能以数字打头。例如，可将变量命名为message_1,但不能将其命名为1_message
* 变量名不能包含空格，但能使用下划线来分割其中的单词。例如，变量名greeting_message可行，但变量名为greeting message会引发错误。
* 慎用小写字母l和大写字母O