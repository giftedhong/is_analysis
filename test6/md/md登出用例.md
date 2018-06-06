# [←](../README.md) “登出”用例

##1.用例规约
|用例名称|登出|
|-----|-----|
|功能 | 用户登出平台|
|参与者 | 学生，老师|
|前置条件|必须先登录|
|后置条件|登出后，跳转到登录页面 |
|主事件流| 系统清除客户端登录信息（Cookie）|
|备选事件流|1.如果用户登录之后，长时间不超作界面，导致Cookie失效 <br>2.系统清除客户端登录信息（Cookie |

##2.业务流程（顺序图）
无

##3.界面设计
- 界面参照
    - https://giftedhong.github.io/is_analysis/test6/ui/logout.html
- API接口调用
    - 接口：[登出接口](../others/logout.md)

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