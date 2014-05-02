## 1.0.2 / 2014-05-02
* 增加CSRF防御系统
* 增加"go to top"功能
* 修复admin不能发Discuss的bug
* 改善Discuss的交互
* 为Discuss增加实时提醒

## 1.0.1 / 2014-05-01
* 每250ms拿一次待判提交记录的结果改为每1000ms拿一次
* 增加rating系统
* 修复上传文件后文件名会变的问题
* 首页修复比赛没按时间排序的bug
* 改善登录交互，增加"remember me for a month"功能
* 公告独立出来，方便维护

## 1.0.0 / 2014-04-10
* 重要功能介绍:
* 题目标签管理完全采用Codeforces的模式
* 除了Special Judge模式外，还有TC模式(按照题目要求编写接口-不写main函数)
* VIPContest: public(通过注册参加，类似CF), private(不能注册，只能通过admin添加参赛者)
* admin可以去某个用户的页面(如: user/kidx)赋予/回收加题权限，也可重置该用户的密码
* admin可以在自己的页面(user/admin)重新统计用户AC数和提交数
* admin可以在自己的页面(user/admin)最下方看到hidden的题目
* admin可以在contest页面对题目进行"显示到题库/隐藏"
* admin可以对指定题目进行rejudge(problem页面/contest页面)
* rating系统，还没定怎么做
* admin以及contest的创建者可以在contest的rank页进行打星、广播消息(实时socket通讯)
* admin可以在VIPContest的rank页添加参赛者
