# [←](../README.md) “查看评语”用例

##1.用例规约
|用例名称|查看评语|
|-----|-----|
|功能 | 学生查看自己的每个实验的实验成绩及实验评价|
|参与者 | 学生|
|前置条件|学生需要登录|
|后置条件||
|主事件流||
|备选事件流||

##2.业务流程（顺序图）
无

##3.界面设计
- 界面参照
    - 老师身份：https://giftedhong.github.io/is_analysis/test6/ui/teachercomment.html
    - 学生身份：https://giftedhong.github.io/is_analysis/test6/ui/studentcomment.html
- API接口调用
    - 接口：[查看/评定评语接口](../others/getOneStudentResults.md)

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