## Sprint Planning 冲刺计划会议简介

Sprint Planning （冲刺计划会议），又叫规划会议。此会议通过 Scrum 团队的集体沟通讨论，确定接下来的 Sprint 中要完成的待开发项，把它们组成一个 Sprint Backlog。这些待开发项都是从 Product Backlog 中挑选的。

![image](https://github.com/user-attachments/assets/2468ef20-3297-4292-9e27-55a071700816)

- Product Backlog：产品功能特性列表
- Sprint Backlog：迭代任务列表，可以细化为更小的开发任务 Task

>  可以规划一个 Sprint Backlog，也可以规划多个，根据产品规划路线图、产品开发进度、团队任务量等等多种因素来确定。

## Sprint计划会议目的

![image](https://github.com/user-attachments/assets/06b741a1-2c26-4e0e-8ffb-bb65620f6eff)

- **设定目标**：设定 Sprint 迭代的计划、目标和期望的成果。
- **理解需求**：对于待开发的需求，需要团队成员的理解是一致的。
- **估算工作量**：对 Sprint Backlog 中待开发项进行估算，有的待开发项需进一步细化然后估算。最后估算整个 Sprint 的工作量。
- **承诺**：团队对完成 Sprint（冲刺）目标做出承诺，并达成一致。

## Sprint计划会议内容

1、**Sprint 目标**，确定 Sprint Goal

> 产品负责人提议如何在这次的 Sprint 中增加产品的价值。然后，与 Scrum 团队共同讨论并制定本次冲刺的目标 - **Sprint Goal**，最后确定下目标。
> “我们为什么要做这次的 Sprint，而不是去度假？”

2、**待办项选择，这次 Sprint 迭代要完成哪些待开发项**

>Scrum 开发团队和产品负责人一起讨论，按优先级顺序从 Product Backlog 中选取待开发项，放入到当前 Sprint 中，组成 Sprint Backlog。
>
>在此过程中，可以对 Sprint Backlog 中的待开发项进一步细化、拆解，分解为更小的开发 Task，这样容易估算工作量，也容易完成开发任务。


![image](https://github.com/user-attachments/assets/1047d115-8537-4d76-832d-89dabbc75b3a)

3、**任务拆分，估算工作量，制定开发计划，分配开发任务，领取任务**

>- 可以将一些待开发项拆分为更小的开发项。比如把大的 Epic 拆分为 Feature（特性），在把 Feature 拆分为更具体更小的 User Story（用户故事）。比如把用户故事拆分为程序员的开发任务 Task，便于开发人员开发和估算。
>
>- 待开发项或 更小的开发 Task，对它们的工作量进行估算，通常以天或小时为单位。
>
>- 确定每个待开发任务的执行顺序、所需资源和依赖关系。
>
>- 澄清待开发项，确保团队成员对它的理解是一致的。
> 
>- 团队成员根据自己的技能和兴趣领取工作 Task。
>
>- 制定开发计划，可以用甘特图、燃起图来跟踪项目完成情况。

一般一个 Sprint 的迭代开发周期是 1 - 4 周。

![image](https://github.com/user-attachments/assets/d38dae69-e028-4118-af03-e8f8147f2eac)

4、**定义验收标准**

> 定义验收标准，确保团队成员对 “完成” 有共同的理解。
> 
> - DoD - Definition of Done ，完成的定义
> - Acceptance Criteria，验收标准

## Sprint计划会议注意事项

- **明确会议议程**：在开始会议前，明确会议的议程和目标，并通知所有参与者分享。
- **时间控制**：对一个为期 2 周的 Sprint，会议时间通常持续 2 - 4 个小时，以此类推。
- **利益相关者参与**：产品负责人、Scrum Master、开发团队，以及邀请必要的与此次会议有关的人员，也要注意限制参与人数。因为人数越多，一是浪费无关人员时间，二是讨论事情复杂增大。
- **透明沟通**：要确保所有的沟通都是开发和透明的。
- **避免过度承诺**：团队应该避免选择过多的开发任务，而无法完成冲刺目标。
- **冲刺计划灵活性**：冲刺计划灵活性，以适应 Sprint 中需求的变更。

## 开发项与用户故事的拆分

### 大开发项的拆分
对 Sprint 中需求开发项的拆分和细化。

比如从 Product Backlog 中挑选的大的 Epic（史诗），拆分为多个具体的 Feature（特性），特性进一步拆分为更小、更具体的 User Story（用户故事）。每个用户故事都是站在用户角度的最小可交付的工作项。
在把用户故拆分为开发任务（Task）。

> - Epic：史诗，更大更高层次的用户故事。可以是多个功能集合，对业务产生显著价值。
> - Feature：特性，可以看着是关联用户故事的集合，组合提供某种业务价值。
> - User Story：用户故事，站在用户角度对功能的描述，给用户带来什么价值。

![image](https://github.com/user-attachments/assets/b2409676-1ad0-4f7a-907c-e3a7b7e70a84)

### 用户故事拆分

用户故事拆分方法有哪些呢，下面来看有哪些方法。

![image](https://github.com/user-attachments/assets/e6dd1bc3-c168-48e1-ac3b-eb4aeeb1dd37)

**1、基于流程步骤拆分**

按照用户完成一个业务流程步骤来拆分用户故事。梳理出清晰的用户操作路径。

比如：常见的 "用户下单购买商品" 的用户故事，可以拆分为
- 用户浏览商品列表
- 用户查看商品详情
- 将商品加入购物车
- 购物车商品结算
- 选择支付方式完成支付

等更小的用户故事。这里每一个子故事代表了“下单购买商品”流程中的一个一个关键步骤，开发人员就可以根据这些子故事来进行系统功能的开发。

**2、基于用户角色拆分**

当一个系统涉及多个角色和系统交互时，可以根据不同的角色来拆分用户故事。这样可以明确角色在系统中的功能需求和角色权限。

比如：比如 ERP 系统的开发，在这个系统中有管理员、销售人员和仓库管理人员等不同的角色。对于“库存管理”这个用户故事，可以拆分为
- 管理员设置库存预警阙值
- 销售人员查询库存数量以确定销售策略
- 仓库管理人员，根据收货单更新库存数量

等这些子用户故事，开发人员可以根据每个角色的需求进行功能开发。

**3、基于功能特性拆分**

按照开发的系统提供的功能特性来进行拆分。这种方法有助于聚焦系统具体功能模块。

比如：在社交媒体软件上“用户发布内容”的用户故事，可以拆分为
- 用户发布文字内容
- 用户发布图片内容
- 用户发布视频内容
- 编辑已发布的内容

等子用户故事，开发人员可以根据每个功能特性来进行开发。

比如“发布图片内容”的子故事，支持哪些图片格式？这就是业务规则。

**4、其它一些拆分方法**

其它一些方法有哪些：

- 基于规则和约束拆分
- 基于数据边界
- 基于功能依赖顺序
  
### 开发任务的拆分

细化研发工程师开发的任务（Task），比如一个需求开发，把它所有的开发任务都列出来：

- 用户文档、页面设计、前端、功能的编码、测试、Bug修复、测试验收、部署等。

比如需求功能的编码，可以细化为哪些子开发任务？
>- 有多少个功能需要开发？
>- 对应程序中的功能模块有哪些？
>- 程序编码设计？功能模块里的类有哪些？
>- 类的功能有哪些？
>
>- 需要提前设计吗？等等

程序开发人员都可以进一步细化开发任务（Task）。

如果你使用 CICD Pipeline 集成开发测试交付流水线，那么需要写的测试脚本就有很多。
总之，统统列出来，便于估算开发时长。

> **说明**：不仅有对用户故事的拆分，拆分为更小功能，还有对开发任务的拆分。

## Sprint Backlog 任务清单模板

Dev Team 负责人负责维护 Sprint 开发任务清单，由开发需求或用户故事的功能拆分而来。

一般我们会用在线敏捷软件来管理开发任务。

任务清单模板如下：

![image](https://github.com/user-attachments/assets/f3c41121-bf8f-463e-9eca-a824befc4d10)


> 这只是一个示例模板，里面的每一格标题都可以根据自家情况进行增加、删除和调整。

## Scrum 整体流程图(计划面板、任务面板、发布面板)

看到一个 Scrum 框架开发流程图，里面有各种步骤，而且图把各个步骤流程很好展示出来：

![image](https://github.com/user-attachments/assets/8c70a4ac-683d-4bc6-9a5a-8b097b07d31e)
（来自网络侵删）
