# [←](../README.md) “选择课程”用例

##1.用例规约
|用例名称|选择课程|
|-----|-----|
|功能 | 用于老师和学生的选课|
|参与者 | 老师，学生|
|前置条件|学生，老师需要登录|
|后置条件||
|主事件流||
|备选事件流||

##2.业务流程（顺序图）
###顺序图源码：[PUML文件](../puml/puml选择课程顺序图.puml)
![](../images/png选择课程顺序图.png)

##3.界面设计
- 界面参照
    - 老师身份：https://giftedhong.github.io/is_analysis/test6/ui/teachercourse.html
    - 学生身份：https://giftedhong.github.io/is_analysis/test6/ui/studentchoose.html
- API接口调用
    - 接口：[选择课程接口](../others/getcourse.md)

## 4. 算法描述
无

## 5. 参照表
- [USER](数据库设计.md/#USER)
- [STUDENT](数据库设计.md/#STUDENT)
- [TEACHER](数据库设计.md/#TEACHER)
- [TERM](数据库设计.md/#TERM)
- [TEST](数据库设计.md/#TESTS)
- [TESTGRADE](数据库设计.md/#TESTGRADE)
- [COURSE](数据库设计.md/#COURSE)
- [COURSEGRADE](数据库设计.md/#COURSEGRADE)