# Swift-get-answer
Swift问答程序
import Foundation
导入Foundation框架是为了使用一些Swift语言的基础功能和标准库，例如字符串操作、输入输出等。Foundation框架提供了许多常用的功能和类型，使得开发者能够更方便地进行应用程序开发。
readLine()函数来读取用户的输入，这个函数是Foundation框架提供的一个用于从标准输入流读取一行数据的函数。
func getAnswer(for question: String) -> String：定义了一个名为getAnswer的函数，它接受一个名为question的字符串参数，并返回一个字符串作为回答。
4-15. 使用switch语句根据问题的内容进行匹配和回答。
19-27. 在一个无限循环中，提示用户输入问题，并根据问题调用getAnswer函数获取回答。
if let userQuestion = readLine()：使用readLine()函数获取用户的输入，并将其赋值给userQuestion常量。
if userQuestion == "退出"：如果用户输入的问题是"退出"，则跳出循环，结束程序的执行。
let response = getAnswer(for: userQuestion)：调用getAnswer函数，传递用户输入的问题作为参数，并将返回的回答存储在response常量中。
print(response)：将回答输出到控制台。
