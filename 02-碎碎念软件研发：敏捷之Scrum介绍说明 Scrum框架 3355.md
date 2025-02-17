## 一、什么是 Scrum

### 1.1 Scrum 定义

Scrum 是敏捷开发方法之一，它使用比较广泛。

敏捷的其它开发方法还有 XP(极限编程)、FDD(特性驱动开发)、Crystal(水晶方法)、TDD(测试驱动开发)、DSDM(动态系统开发)等等敏捷方法。



[Scrum-Guide](https://scrumguides.org/scrum-guide.html) 中定义的 Scrum：

> Scrum 是一个开发和维护产品的框架，它通过提供针对复杂问题的自适应解决方案来帮助人们、团队和组织创造价值。
>
> Scrum 需要 Scrum Mater 营造一个环境：
>
> 1. 一名 Product Owner 将解决复杂问题所需要的工作整理成一份 Product Backlog。
>
> 2. Scrum Team 在一个 Sprint 周期里将选择的工作转化为有价值的 Increment。
>
> 3. Scrum Team 和利益相关者检视结果并为下一个 Sprint 进行调整
>
> 4. 重复

Scrum-Guide 里还说：

Scrum 框架故意不完整，仅仅定义了实施 Scrum 理论所需的部分。在 Scrum 中，可以使用各种不同的过程、技术和方法。

## 二、Scrum 迭代开发过程

### 2.1 迭代开发过程

Scrum 采纳了一种迭代和增量的开发方法。[前文](https://www.cnblogs.com/jiujuan/p/16294276.html)中有介绍这 2 种开发模型。用这种方式来应对未来需求变化。

在 Scrum 框架中，整个开发过程由若干个短的迭代周期组成，一个短的迭代周期称为一个 Sprint，每个 Sprint 的长度建议是 2 到 4 周。这个时间周期可以根据具体情况调整。



从[瀑布开发模型](https://www.cnblogs.com/jiujuan/p/16294276.html#3548643803)中可以了解到，产品开发前还有产品需求，在 Scrum 中，产品需求在哪里？

> 在 Scrum 中，用 Product Backlog 来管理需求，它是产品的需求池。

需求多了，怎么知道先开发哪个后开发哪个需求？

> 需要开会对 Product Backlog 里的需求进行讨论，然后排定优先级。
>
> 优先开发对客户价值较高的需求。

后面的迭代周期 Sprint 又怎么划分，多大的 Sprint？

> 会在 Sprint 计划会议上讨论、分析和估算挑选的需求，然后得到一个任务列表。这个任务列表称为 Sprint Backlog。下面就针对这个 Sprint Backlog 来开发。

Sprint 周期一般 2 到 4 周，这期间的进度怎么同步和管控？

> 这里有一个 Daily Scrum Meeting，每日站会。一般有 3 个部分：
>
> 1. 昨天完成了什么
> 2. 今天计划做什么
> 3. 遇到了什么困难

最后就是回顾整个 sprint backlog 开发过程的会议，复盘这期间的得与失，在下一次 Sprint 周期中进行改进。

### 2.2 迭代开发过程图解

![image-20220526205356045](https://img2022.cnblogs.com/blog/650581/202205/650581-20220528023155520-1742400124.png)

(https://www.wrike.com/scrum-guide/scrum-sprints/)

### 2.3 总结

细化分解：

Scrum 开发过程就是一个逐步分解细化的过程，把大的产品需求分解为更小的开发需求，再把开发需求按优先级组合，然后划分为一个一个开发周期，在 Scrum 中叫 Spring 迭代周期。在 Sprint 迭代周期中，再划分为一个一个的任务。这样就可以细化到每天需要完成的任务。



PDCA 循环：

Scrum 里有 PDCA 循环思想。Sprint 是一个迭代周期。里面的任务(task)也可以看作是一个更小的开发周期。

## 三、Scrum 框架3-3-5-5

Scrum 是一个自组织、跨职能的完整团队。自组织团队自己决定如何完成他们的工作，而不是由团队外的人来决定。

### 3.1 3个角色

1. 产品负责人 Product Owner  
2. Scrum Master 
3. Scrum Team 开发团队

![image](https://img2024.cnblogs.com/blog/650581/202411/650581-20241119154208069-1738697098.png)

1.产品负责人 Product Owner：

> 产品负责人是对产品价值最大化的责任人。他负责最大化产品价值和开发团队工作的价值。他负责产品待办事项列表 product backlog，并对待办事项优先级进行排序。他要负责 Scrum 团队的下一步工作。



2.Scrum Master：

> Scrum Master 负责 Scrum 被理解并实施。他负责团队成员遵循 Scrum 理论、实践和规则。
>
> 他帮助团队成员理解 Scrum 并和团队一起实施 Scrum 中的各种活动。他教导开发团队创建清晰的待办事项列表。



3.Scrum Team 开发团队：

> 为 Sprint 创建计划，即 Sprint Backlog。负责每个 Sprint 周期里的任务开发完成并交付产品。开发团队是跨职能的，拥有创造产品增量所需的全部技能，并会随着工作领域变化而变化。开发人员作为专业人士对彼此负责。

### 3.2 3个工件

1. Product Backlog 
2. Sprint Backlog 
3. Increment

![image](https://img2024.cnblogs.com/blog/650581/202411/650581-20241119161830823-1992524026.png)


1.Product Backlog：

> 产品需求清单，而且是一份有序的需求清单。它是开发团队工作的来源。Product Backlog 里有一个一个的条目（item），这就是开发每天需要完成的工作。



2.Sprint Backlog：

> Sprint Backlog 由 Sprint Goal（为什么做）、从 Product Backlog 选择的需求（做什么）组成 Sprint Backlog，以及交付 Increment（开发结果）的可执行计划。
>
> Sprint Goal 是 Sprint 的单个目标。Sprint Goal 是在 Sprint 计划会议中决定的。

Sprint 的进度：可以用 Sprint Brun-down Chart 来统计剩余的工作量。



3.Increment：

> 一个 Increment 就是一个可交付的开发结果。在一个 Sprint 中可以创建多个 Increment。增量是迈向目标的一步。

### 3.3 5个事件

1.Sprint

2.Sprint 计划会议

3.每日 Scrum 站会

4.Sprint 评审会议

5.Sprint 回顾会议

![image](https://img2024.cnblogs.com/blog/650581/202411/650581-20241119163339049-1551753349.png)


**1.Sprint**

> Sprint 是 Scrum 的核心，在这里将创意(idea)转化为价值。它的一个迭代周期可以是 2 到 4 周，视具体情况而定。在这段时间内，要构建一个完整的、可发布的产品增量(Increment)。前一个Sprint 结束后，新的下一个 Sprint 紧接着开始。
>
> Sprint 由 Sprint 计划会议(Sprint Planning)、每日 Scrum 站会(Daily Scrum)、开发工作(Develop)、Sprint 评审会议(Sprint Review) 和 Sprint 回顾会议(Sprint Retrospective)组成。

每一个 Sprint 相当于一个小的项目。

如果 Sprint 的目标已经过时，那么可以取消该 Sprint。但是只有产品负责人(Product Owner)才有权利取消。



**2.Sprint Planning**

Sprint 计划会议(Sprint Planning) ，通过安排在 Sprint 中要做的条目(item)，来启动一个 Sprint。需要 Scrum Team 协助创建。

Product Owner 确保讨论最重要的 Product Backlog 条目。



**3.Daily Scrum**

每日会议检查开发的进展，并根据需要实时调整 Sprint Backlog。每日会议一般为 15 分钟，不要太长。



**4.Sprint Review，Sprint评审会议**

Sprint评审会议是检视 Sprint 的成果。Scrum Team 向利益相关者来展现他们的工作成果，在这次 Spirnt 中完成了什么，以及环境发生了什么变化。以及接下来要做什么。



**5.Sprint Retrospective，Sprint 回顾会议**

Sprint 回顾会议的目的是规划提高质量和效能的方法。它发生在 Sprint Review 会议之后，下一个 Sprint 开始之前。

Sprint 回顾会议的目的：

- 检视前一个 Sprint 中关系、过程和工具的情况如何
- 做得好的地方继续发扬，不好的地方提出改进方法
- 指定改进 Scrum Team 团队工作方式

### 3.4 5个价值观

1.承诺：愿意对目标做出承诺

2.专注：把心思和能力用到你承诺的工作上去

3.开放：Scrum 把项目中的一切开放给每个人看

4.尊重：每个人都有他独特的背景和经验

5.勇气：有勇气做出承诺，履行承诺，接受别人的尊重

### 3.5 图解 Scrum 整个过程

![image-20220528015822331](https://img2022.cnblogs.com/blog/650581/202205/650581-20220528023155604-2008578296.png)

（https://www.neonrain.com/agile-scrum-web-development/）

- 1、产品负责人（Product Owner）把产品开发相关人员召集在一起，共同制定产品愿景、产品目标，规划产品路线图等，收集产品的功能特性和非功能特性（比如小的用户故事、Epic（大的用户故事）、基础技术任务、功能优化等等）。

- 2、Product Backlog，把上面收集到的功能特性和非功能特性放到 Product Backlog（产品待办列表）中，并进行优先级排序。定期召开会议梳理 Product Backlog 中的开发项。

- 3、Sprint Planning Meeting（冲刺计划会议），从上面的 Product Backlog 中挑选出开发项，形成一个开发目标（Sprint Goal），把开发项组成一个 Sprint Backlog。然后对这个 Sprint Backlog 进行细化拆分，形成更小的开发 task，并估算开发时间，通常以小时或天为单位来计算开发时间。开发团队开始进行小任务的开发。

- 4、每一个 Sprint Backlog 迭代周期是 1 到 4 个星期。

- 5、在一个 Sprint Backlog 的迭代周期中，每天要进行 Daily Scrum Meeting（每日站会），每次会议时间控制在 15 分钟。

- 6、开发任务的完成进度可以用 Burn down/up Charts（燃尽图）来表示。

- 7、当一个 Sprint Backlog 完成，也就是一次冲刺任务完成时，进行 Sprint Review（评审会议），向利益相关人员演示此次完成的工作成果，并验收成果。

- 8、最后 Sprint Retrospective ，总结回顾会议，每个成员进行发言，总结经验和教训，哪些地方完成的比较好，哪些地方还需要改进，并在下一轮 Sprint 迭代中进行改进。

**再来个简洁的整体流程图**

![image](https://github.com/user-attachments/assets/c1c40f18-304c-40c6-810b-106728d91005)


## 四、实施 Scrum 会遇到的问题

1. Product Backlog 里的需求怎么来？价值大小按照什么排序？
2. 每一个 Sprint 里的 Sprint Goal 怎么确定？Sprint 实施时间怎么确定？
3. Sprint Backlog 里的每个条目，怎么估算时间？每个开发人员能力不同，开发时间怎么估算？
4. 每日站会怎么开？会不会大家对 Scrum 认识不足而流于形式的开会？
5. Sprint 评审会怎么开？会不会变成吐槽会，甩锅大会？
6. 看到敏捷 2 字，好多主管或工程师就误以为它是快速开发方法？这是对敏捷快速交付的片面理解。
7. 还有一个最大的挑战，应该是大家开发习惯的转变。我们知道，要改变一个人脑袋里固有模式和习惯，接受新的理念和方法，总是很难的。
世界上最难的2件事情，一是：把新思想装进别人脑袋里，二是：把别人口袋里的钱装进自己口袋里。

等等各种问题。

但是 Scrum 强调自管理，遇到了问题不要紧，去寻找解决方法，不段的改进。

在实施 Scrum 中，团队的成员初期需要熟悉彼此，开始磨合时，矛盾可能增多。

但是随着不断进行 Sprint，彼此越来越熟悉，改进越来越多，摩擦慢慢会减少，Scrum Team 彼此之间协作也会慢慢进入到最佳状态，

从而不断增加有效产出。

## 五、适用场景

对于需求很明确的产品，比如一些传统产品或成熟的产品，需求非常明确，不会轻易改动需求，那么更适合瀑布开发模式。

而对于那些易变的需求，不能明确客户需求，不晓得用户心里到底想要什么，需要通过不断测试，实践来明确需求的，这种更适合 Scrum 开发。

敏捷开发中的概念非常多，是不是全部都要照着做呢？
答案是不一定。可以根据公司情况适当的裁剪一些步骤，或者灵活的修改一些做法。
上面写到的敏捷开发概念、步骤，是一种标准的做法。
比如在一些小公司做开发，步骤太多，就会显得繁琐，不够灵活做事。所以可以根据公司情况适当的调整。

## 六、参考

- https://scrumguides.org

- https://scrumguides.org/docs/scrumguide/v2020/2020-Scrum-Guide-US.pdf#zoom=100

- https://www.wrike.com/scrum-guide


- https://www.neonrain.com/agile-scrum-web-development/

  
