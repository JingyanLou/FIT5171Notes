# FIT5171Notes
- Notes for FIT5171:System validation and testing (Monash University), Semester 1 2024. 
- Feel free to ask me questions related to this unit.
# Course Review
- 选这门课之前就有上一届的学长提醒我千万不要选这门课，当时不懂，后来经历了这一个学期以后感受如下：
- 1.这门课主要代码成分不多，大多数都是用离散数学去抽象测试。如果你喜欢离散数学，测试的理论，一些测试metrics，graph theory的话可以来学。
- 2.如果你是为了学习测试代码的话来学这门课，那么代码部分例如junit test，mockitto，oop programming真的需要你去花5000刀去学吗？这些东西看个tutorial，udemy 30刀报个课学不明白？
- 3.这门课只有2个老师，ed上的问题基本上要3-5天才能恢复，lecture recording有12节，但是只有6节有声音（this is crazy），但是总体来说上课的氛围还不错老师很厉害，可以和你分享一些工作中真实的案例。
- 4.说到作业，50%的in-sem，其中40%是一个大作业，从测试计划，测试用例，到最后的评估测试结果。小组组员很重要，但是根据我的观察，老师其实并没有很细心的看你的作业，差不多就行了基本上，而且打分很宽松，基本上刷脸多一些，和老师互动多的话分数都不低。
- 5.有出勤率，和每周的quiz，总体占10%。
- 6.学习中最苦难的是，没有答案！所以学到最后也不知道自己是对的还是错的，太开放了。
- 7.说一说这个yuanfang大哥，yuanfang大哥听在monash工作的朋友说事it部门元老级别的人物了，讲课很有数学大哥的感觉，但是希望还是讲的具体一些，多给一些例子，因为本身东西理论的部分就很多了，例子少的话就很难去抽象。
- 8.总体来说别选这门课，选5225云计算这种又有用又资源多的课，不香啊？不听劝选这门课你就等着吧，一学一个不吱声。


Before choosing this course, a senior from the previous year warned me not to select it. I didn't understand at the time, but after experiencing this semester, here's how I feel:
- This course doesn't involve much coding. Most of it is about abstracting testing using discrete mathematics. If you enjoy discrete mathematics, testing theory, some testing metrics, and graph theory, you might like this course.
- If you're here to learn about testing code, ask yourself if you really need to spend $5,000 to learn things like JUnit tests, Mockito, and OOP programming. Can't you just learn these from a tutorial or a $30 Udemy course?
- There are only two instructors for this course. Questions on Ed usually take 3-5 days to get a response. There are 12 lecture recordings, but only 6 have sound (this is crazy). However, the overall class atmosphere is good, and the teachers are very knowledgeable, sharing real-world examples from their work.
- Regarding assignments, 50% of the grade is in-semester, with 40% being a major project that includes the test plan, test cases, and final evaluation of test results. Group members are very important, but based on my observation, the instructors don't seem to pay much attention to your assignments. If it's - decent enough, you'll get a good score. Interaction with the instructors can significantly boost your grade.
- There is attendance and a weekly quiz, which together account for 10% of the grade.
- The hardest part of studying is that there are no answers! So, by the end, you don't know if what you learned is right or wrong. It's too open-ended.
- Let's talk about Yuanfang. I've heard from friends working at Monash that he's a veteran in the IT department. He lectures like a math guru, but I wish he could be more specific and give more examples because the theoretical content is already very heavy. Without enough examples, it's hard to abstract.
- Overall, don't choose this course. Choose something useful and resource-rich like 5225 Cloud Computing. Isn't that much better? If you don't listen to the advice and take this course, you'll regret it silently for a whole semester.

# Exam Review
## Exam Details
- Duration:2h10min 
- Closed book 
- 5 Page double sided Cheatsheet allowed
- Answer sheet:6 (Uploaded Answer sheets) 
- 2024 Sem1
- 难度：8.5/10 

## Exam questions: 
### Q1:BVT

- <img width="430" alt="image" src="https://github.com/JingyanLou/FIT5171Notes/assets/92469426/9dc6addb-5cac-4bb8-a5b9-a1fbfe4b590a">

- 现在有一个method他的input是a,b,c,d,分别对应着四边形的四个角
- 例如：a=90，b=90.c=90.d=90 => 正方形
- 四边形的四个角的和加起来是360度
- 如果a=b=c=d,那么说明这是一个正方形
- Q1.1: Write two testcases for normal worst case BVT
- Q1.2: Write four testcases for robust BVT

### Q2: DDT
- 根据shopping website的checkout功能，写一个decesion table.
- checkout的时候user可以选择支付方式（paypal，alipay，store credit）
- user也可以选择shipping methods
- checkout也许有discount
- 购物会有tax，有的商品有，有的商品没有tax
- checkout要计算total

### Q3: Program Graph

- <img width="432" alt="image" src="https://github.com/JingyanLou/FIT5171Notes/assets/92469426/976fb5e1-aff3-447a-b4de-c9c6ceba077b">
- MergeSort
- Merge
- Q3.1:求program excution graph
- Q3.2:求complexity

### Q4 Mutation Testing
- <img width="305" alt="image" src="https://github.com/JingyanLou/FIT5171Notes/assets/92469426/c2a41655-5896-4ff7-842b-98271edfe6fa">
- Q4.1:Write a testcases that can covers 80% at least statement for this program (c0 >= 80%) 
- Q4.2:Write 6 different mutant for BinarySort

### Q5 FSM
- <img width="432" alt="image" src="https://github.com/JingyanLou/FIT5171Notes/assets/92469426/1c1d689b-6ec0-4401-baed-4b073b5dead1">
- Draw the FSM for this traffic light system, It has 4 directions... 
- 根据这个交通信号灯系统，画出finite state machine
- 这道题考试的时候简直就是噩梦级别的存在


## Cheatsheet
[FIT5171CompressedNotes.pdf](https://github.com/user-attachments/files/15813257/FIT5171CompressedNotes.pdf)


