



# lesson 01：

##### 笔记：

###### 句子组成：

| 零件            | 回答什么问题               | 编程类比        |
| --------------- | -------------------------- | --------------- |
| 主语 Subject    | 谁？什么？                 | 调用者 / 执行者 |
| 谓语 Verb       | 做了什么？                 | 函数 / 方法     |
| 宾语 Object     | 对什么做的？               | 参数            |
| 补语 Complement | 是什么？什么状态？         | 赋值 / 属性描述 |
| 定语 Attribute  | 什么样的？                 | 注释 / 修饰符   |
| 状语 Adverbial  | 什么时候？在哪？怎么做的？ | 配置项 / 上下文 |

###### 句型速查：

| 句型 | 结构            | 编程类比         | 例句                             |
| ---- | --------------- | ---------------- | -------------------------------- |
| 1    | S + V           | 无参函数         | The server crashed.              |
| 2    | S + V + O       | 单参函数         | I fixed the bug.                 |
| 3    | S + V + C       | 赋值操作         | The API is stable.               |
| 4    | S + V + IO + DO | 双参函数         | I sent him the report.           |
| 5    | S + V + O + OC  | 函数改变对象属性 | We found the solution effective. |







##### 作业：

###### 练习一：句型识别

| 句子                                     | 句型                                    | 典型动词 / 结构              |
| ---------------------------------------- | --------------------------------------- | ---------------------------- |
| The deployment succeeded.                | S+V                                     | succeed, agree, happen       |
| We use Docker for containerization.      | S+V+DO+Adv(目的状语)         ❌已改      | be, become, seem, look       |
| The new feature is impressive.           | S+V+C (表语 / 主语补语，说明主语的状态) |                              |
| She showed me the dashboard.             | S+V+IO+DO(主谓双宾)           ❌已改     |                              |
| The team considers the project complete. | S+V+DO+C(说明DO的状态)   ❌已改          |                              |
| I agree.                                 | S+V                                     |                              |
| He became the tech lead.                 | S+V+C                                   |                              |
| They assigned us two new tasks.          | S+V+IO+DO                               | use sth for..., do sth in... |

TIPS: 区分句型4、5 ：句4两个宾语是两个不同的东西(人和物)，句5宾语、宾补共同表示的是同一个对象

###### 练习二：中文→英文编译

| 句子含义                     | 句式                   | 结构分析              | 回答                                             |
| ---------------------------- | ---------------------- | --------------------- | ------------------------------------------------ |
| 1.我们的服务器昨天宕机了。   | 谁/什么+怎么了         | 主谓宾S+V             | Our server crashed yesterday.                    |
| 2.我正在优化数据库查询       | 谁+做什么+对什么       | 主谓宾S+V+O           | I am optimizing the database query.              |
| 3.这个API接口很稳定          | 什么+是什么状态        | 主系补S+V+C           | This API is highly stable.                       |
| 4.我发了测试报告给产品经理。 | 谁+做什么+给谁+什么    | 主谓直宾间宾S+V+DO+IO | I sent the test report to the PM.                |
| 5.这次重构让代码更清晰了。   | 什么+让什么+变成什么样 | 主谓宾宾补S+V+O+OC    | This refactoring has made the code much clearer. |

###### 练习三：自由造句

We had a meeting to discuss a new requirement on Monday last month.

20 days past, we completed 90% of the system.

Yesterday, 3 bugs appeared and we fixed them immediately.

Finally, the system went live , and the front page looks very nice. 











