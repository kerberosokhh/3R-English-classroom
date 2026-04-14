

# Tips：

#### 从第一节开始的练习

###### 1 不要刻意学习他们的口音，会引起未知的冒犯

###### 2 练习RS的tips(每天 简单、中等 各15个)：

(a). 先听，尽量听懂句子含义或者前半段含义

(b). 复述的时候，尽量清晰，不图快

(初期可专项练印度口音，后可以改为随机)

![image-20260414161717230](C:\Users\40839\AppData\Roaming\Typora\typora-user-images\image-20260414161717230.png)

##### 3 如何写简历和求职：

对于国外：

1 流程：自我介绍，能力，介绍工作经历

2 简历内容：不超过1页半，直接写技术栈，技术总结**，男女不写不放照片**，时长：3 mins，总结几个点  

3 

# lesson 01：

### 笔记：

#### 句子组成：

| 零件            | 回答什么问题               | 编程类比        |
| --------------- | -------------------------- | --------------- |
| 主语 Subject    | 谁？什么？                 | 调用者 / 执行者 |
| 谓语 Verb       | 做了什么？                 | 函数 / 方法     |
| 宾语 Object     | 对什么做的？               | 参数            |
| 补语 Complement | 是什么？什么状态？         | 赋值 / 属性描述 |
| 定语 Attribute  | 什么样的？                 | 注释 / 修饰符   |
| 状语 Adverbial  | 什么时候？在哪？怎么做的？ | 配置项 / 上下文 |

#### 句型速查：

| 句型 | 结构            | 编程类比         | 例句                             |
| ---- | --------------- | ---------------- | -------------------------------- |
| 1    | S + V           | 无参函数         | The server crashed.              |
| 2    | S + V + O       | 单参函数         | I fixed the bug.                 |
| 3    | S + V + C       | 赋值操作         | The API is stable.               |
| 4    | S + V + IO + DO | 双参函数         | I sent him the report.           |
| 5    | S + V + O + OC  | 函数改变对象属性 | We found the solution effective. |







### 作业：

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

# lesson 02：

### 笔记：

#### 1 时态=动词的执行状态

| 执行状态         | 含义                  | 对应时态   |
| ---------------- | --------------------- | ---------- |
| CONSTANT         | 本职工作 / 不变的事实 | 一般现在时 |
| RUNNING          | 正在执行中            | 现在进行时 |
| RESOLVED (log)   | 执行完了，记录结果    | 一般过去时 |
| RESOLVED (state) | 执行完了，状态已变更  | 现在完成时 |
| SCHEDULED        | 已排期，等待执行      | 一般将来时 |
| WAS_RUNNING      | 当时正在跑的后台线程  | 过去进行时 |

##### 1、一般现在时

​	声明常量：主语 + 动词原形（第三人称加 -s ）

##### 2、现在进行时：

正在运行的进程：主语 + am / is / are + doing

▸ I'm working on the API integration. 我正在做 API 对

##### 3、一般过去时(yesterday过去时态标志词)：

主语 + 动词过去式(一般)

##### 4、现在完成时：

执行完了，记录结果— 持久化的状态变更：主语 + have / has + done （过去分词）

##### 5、一般将来时：已排期的任务

主语 + will + 动词原形 / 主语 + be going to + 动词原形

will 更像临时决定 / 承诺， be going to 更像已经计划好的事。职场沟通中两者混用没问题。

##### 6、过去进行时：后台运行的线程

主语 + was / were + doing

几乎总是和 when 连用：「我正在 A ，这时 B 发生了」

#### 2 IT 高频不规则动词

![image-20260414160205594](C:\Users\40839\AppData\Roaming\Typora\typora-user-images\image-20260414160205594.png)

ps：好消息： deploy, merge, push, test, review, fix, release, update 都是规则的（加 -ed 就行）

#### 3 职场高频动词

| 职场高频动词       |               |                  |                 |
| ------------------ | ------------- | ---------------- | --------------- |
| 英文               | 中文          | 英文             | 中文            |
| maintain           | 维护          | deploy           | 部署            |
| release            | 发布          | merge            | 合并分支        |
| push               | 推送代码      | fix              | 修复            |
| refactor           | 重构          | migrate          | 迁移            |
| debug              | 调试          | review           | 审查 / 评审     |
| test               | 测试          | approve          | 批准            |
| handle             | 处理          | identify         | 定位 / 识别     |
| expire             | 过期          | renew            | 续期 / 更新     |
| Standup / 会议常用 |               |                  |                 |
| standup            | 每日站会      | blocker          | 阻碍 / 卡点     |
| in progress        | 进行中        | done / completed | 已完成          |
| backlog            | 待办 / 需求池 | ETA              | 预计完成时间    |
| hotfix             | 紧急修复      | staging          | 预发布环境      |
| production / prod  | 生产环境      | sprint           | 迭代周期        |
| PR (Pull Request)  | 代码合并请求  | CI pipeline      | 持续集成流水线  |
| root cause         | 根本原因      | EOD (end of day) | 今天下班前      |
| so far             | 到目前为止    | already / yet    | 已经 / 还（没） |

#### 4 课堂练习：模拟 Standup

![image-20260414160930765](C:\Users\40839\AppData\Roaming\Typora\typora-user-images\image-20260414160930765.png)

模板： Yesterday I ___. Today I'm ___. I'll ___. One blocker: ___.

### 作业：

##### 作业一：每日虚拟 Standup （持续一周）

**After the requirements meeting one week ago, we finally launched the system with a new feature yesterday.**

**Today,The system is under heavy traffic .**

**I have called my PM to request more servers.**

**Tomorrow we will monitor logs to check if the issue is fixed.**

###### Day 1：

1、 Yesterday I climbed a mountain with my climbing partner, and we ate lunch at the middle of the mountain.
2、 Today I'm practicing code for reinforcement learning.
3、I have finished the second lesson of the English class.
4、I will summarize what I’ve learned this week. But for now, I haven’t finished it yet.

###### Day 2：

**After the requirements meeting one week ago, we finally launched the system with a new feature yesterday.**

**Today,The system is under heavy traffic .**

**I have called my PM to request more servers.**

**Tomorrow we will monitor logs to check if the issue is fixed.**

Day 2：

Day 2：

Day 2：

##### 作业二：纠错挑战

1. I have completed the feature last sprint and now I work on the next one. 
2. The team didn't deployed the fix yet because QA is still testing it yesterday. 
3. When the client is calling us, we have discussed the architecture changes.

answer：

1. I completed the feature last sprint and now I'm working on the next one. 
2. The team hasn't deployed the fix yet because QA  was still testing it yesterday. 
3. When the client called us, we discussed the architecture changes.







