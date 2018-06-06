# [←](../README.md) “登出”用例

##1.用例规约
|用例名称|登录|
|-----|-----|
|功能 | 用户登录平台|
|参与者 | 学生，老师|
|前置条件||
|后置条件|登录成功后，跳转到主页 |
|主事件流| 1. 访客输入用户名和密码，选择用户类型<br>2.系统判断用户名，密码，用户类正确，允许登录<br>3.系统在客户端以Cookie形式存储登录用户信息，保持登录的持久性。|
|备选事件流|1.如果用户登录之后，长时间不超作界面，导致Cookie失效 <br>2.系统清除客户端登录信息（Cookie） |

##2.业务流程（顺序图）
无

##3.界面设计
- 界面参照
    - https://giftedhong.github.io/is_analysis/test6/ui/login.html
- API接口调用
    - 接口：[登录接口](../others/login.md)

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