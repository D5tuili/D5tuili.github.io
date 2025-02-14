# 推理之径计算器 -v1.0
## 项目介绍
 这是一个简单的计算器，用来计算根据目前的步数，每周需要打多少推理积分，才能顺利的得到推理之径的皮肤
## 使用说明
### 自动计算
 输入当前步数，同时在“每周预计打推理积分”中不输入任何内容，直接点击绿色的计算按钮，就可以自动计算出每周需要打的推理积分数目，以及各项的贡献。
### 手动计算
  可以通过输入当前步数，以及输入自己每周打的推理积分，来计算最终能走到的步数。同时可以在“设置选项”中，针对性的输入月卡、20面骰天数等，来实现个性化的方案设计。
### 设置选项
 正常来说可以不用动他。但考虑到在计算中，使用的是较为理想的情况，即每天登录三把首胜都拉满，月卡20面也按照拉满来算。但实际上，有些学生党可能没法保证每天登录打首胜，有的人为了省钱，可能只想扔几天20面，只买一张月卡等，因此，这边设计了个性化的设置按钮，可以根据自己的需要进行调整，以下是具体的介绍:<br>
#### 1.平均骰子步数。
 第五人格四面骰的平均步数为3，但有些人可能觉得自己比较非，因此可以将其改成2.8甚至2.5，来得到一个更加保守的结果（我个人觉得没什么必要）。当然步数必须要在1-4之间
 #### 2.每周登录天数。
 默认是7，你每周登几天就写几。
 #### 3.每周首胜天数。
 默认是7，你每周能打几天首胜就填几。
 #### 4.月卡天数。 
 填你准备开月卡的天数，比如你月卡还剩14天，用完不继续开了，就填14。如果你月卡准备一直续到赛季末。这边就不用改。注意不要超过赛季剩余天数！
 #### 5.20面骰天数。
 同上，填准备买20面骰的个数。这边要注意的是，赛季冲刺的时候20面骰的点数会变多，因此假设你要买10个20面，最好是3个现在扔，然后7个赛季末扔。我也是默认这样算的。
### 结果判断
#### 自动计算模式
 在自动计算模式，对于得到的推理积分，需要自行判断是否超过42000，如果超过了，那么说明需要额外的月卡/20面/推演才可以顺利拿到皮肤<br>
 例如，我是学生党，只有周末能登录和打首胜，那么在设置选项中，将每周登录天数和首胜天数都设置成2，其他不动。点击计算,假设结果为：<br>
 不买月卡20面，每周需要打 48637 个推理积分，买月卡，每周需要打 28086 个推理积分，买月卡和20面，除首胜外，无需额外获取推理积分。<br>
 说明不买月卡是不可能拿到的，而买了月卡，每周要打2.8w左右。而如果月卡和20面拉满，则打完首胜后，一把不打，就可以轻松拿到。（当然，此时可以将首胜天数置为0，再次计算。若结果仍然如此，则说明只要买月卡扔20面，就可以拿到，一把都不用打。）
 #### 手动计算模式
 在手动计算模式，只需要关注最终的步数有没有超过1528即可，例子我就懒得再举了
 ## 注意事项
 1.本计算器仅供学习使用，可以转载但最好说明出处。结果仅供参考，是较为乐观的估计，因此能多打尽量多打，本人不承担拿不到皮肤的任何责任。<br>
 2.本计算器在赛季冲刺阶段无效，不过到时候会更新赛季冲刺期间的专版计算器。<br>
 3.由于赛季冲刺阶段有20%的积分加成，因此那个时候也要相应多打20%。<br>
 4.作者为了省事，懒得加那么多错误判断了。所以步数小于0，超过1528，带小数点，1周超过7天等情况都是可以正常使用计算器的，但是得出的结果也没什么意义。这点大家不要学。。。
