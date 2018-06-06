# [←](../README.md) “修改信息”用例

## 1.用例规约
|用例名称|修改信息|
|-----|-----|
|功能 | 修改用户的GitHub用户名称|
|参与者 | 学生，老师|
|前置条件|必须先登录，并且查看用户现有的GitHub用户名|
|后置条件||
|主事件流|1.用户填写GitHub用户名称 <br>2.用户提交修改信息 <br>3.系统存储修改后的GitHub用户名称|
|备选事件流|1. 如果用户输入的GitHub用户名称为空 <br>2.系统清空用户的GitHub用户名称|

## 2.业务流程（顺序图）
无

## 3.界面设计
- 界面参照
    - https://giftedhong.github.io/is_analysis/test6/ui/modifyuser.html
- API接口调用
    - 接口：[获取用户信息](../others/getUserInfo.md)
    - 接口：[设置用户信息](../others/setUserInfo.md)

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
