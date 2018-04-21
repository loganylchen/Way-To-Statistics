# [Importance of being uncertain](https://www.nature.com/articles/nmeth.2613)

>**统计并不会告诉我们我们是不是对的，而是告诉我们我们错误的可能性有多大。**

是不是很熟悉? _p value_ 啊。

>每当我们做一个重复实验的时候，我们不太可能重复出来**完全一样**的结果。由于生物的变化以及测量精度的限制，重复的实验将会测量目标值的范围。但是如果每次的测量值都不同，我们如何能说明，这个实验符合我们的假设，能够证明我们的假设理论没有问题？

>“科学的最大的悲剧就是，最美丽的假设理论都是被最丑陋的数据所屠戮。”而且这“丑陋”居然还没有办法测量。

科学版的“美女与野兽”。而且当别人问野兽有多丑时，我们只能回答，“有点丑”或者“非常丑”。

>然而统计却能帮助我们回答这个问题。它能帮助我们对实验中观察到的某一现象（数据）进行定量的可能性评估。同时还告诉我们数据并不是准确的测量，还是伴有一定错误的估计。丫还能告诉我们计算过程中的错误是如何从输入数据中传递进来的。这要理论框架，能够描述实验结果的不确定性，同时也能对我们从观察数据中得到的一般规律给出一个置信度的描述。


>尽管统计中的很多基本原理可以被很直观的理解，但在真实情况下，特别是涉及到“可能”及“概率”的时候，我们需要摒弃我们的直觉印象。

`Although many fundamental concepts in statistics can be understood intuitively, as natural pattern-seekers we must recognize the limits of our intuition when thinking about chance and probability.`我觉得这一部分我必须贴上原文，因为感觉上怎么翻译都是怪怪的。

>`Monty Hall`问题就是一个非常经典的例子，我们是如何既快又确信的得出一个错误的答案。

后面就主要是描述这个`Monty Hall`场景的。

>规则规定，一个参赛者需要从三个门中作出选择，选择对的门，可以获得一个奖励。当参赛者选择一扇门后（假设A门），主持人会打开另外两扇门中没有奖励的门（假设B门，如果剩下两扇门都没有奖励，就随便开一扇），然后给予参赛者第二次选择的机会，可以让参赛者重新选择没开又没有被选择的门（门C）。令人恼火的事情就是，作为参赛者，到底是应该换门C还是坚持自己选择门A。

为了方便大家理解，我从网上找了维基百科上对于这个游戏规则的描述：这个游戏的玩法是：参赛者会看见三扇关闭了的门，其中一扇的后面有一辆汽车或者是奖品，选中后面有车的那扇门就可以赢得该汽车或奖品，而另外两扇门后面则各藏有一只山羊或者是后面没有任何东西。当参赛者选定了一扇门，但未去开启它的时候，知道门后情形的节目主持人会开启剩下两扇门的其中一扇，露出其中一只山羊。主持人其后会问参赛者要不要换另一扇仍然关上的门。问题是：换另一扇门会否增加参赛者赢得汽车的机会率？


>答案是，选择换。


 but you would be in good company if you thought otherwise. When a solution was published in Parade magazine, thousands of readers (many with PhDs) wrote in that the answer was wrong2. Comments varied from “You made a mistake, but look at the positive side. If all those PhDs were wrong, the country would be in some very serious trouble” to “I must admit I doubted you until my fifth grade math class proved you right”2.





 It also tells us how error in input values propagates through calculations. The practical application of this theoretical framework is to associate uncertainty to the outcome of experiments and to assign confidence levels to statements that generalize beyond observations.

 Although many fundamental concepts in statistics can be understood intuitively, as natural pattern-seekers we must recognize the limits of our intuition when thinking about chance and probability. 

The Monty Hall problem is a classic example of how the wrong answer can appear far too quickly and too credibly before our eyes. 
A contestant is given a choice of three doors, only one leading to a prize. After selecting a door (e.g., door 1), the host opens one of the other two doors that does not lead to a prize (e.g., door 2) and gives the contestant the option to switch their pick of doors (e.g., door 3). The vexing question is whether it is in the contestant’s best interest to switch. The answer is yes, but you would be in good company if you thought otherwise. When a solution was published in Parade magazine, thousands of readers (many with PhDs) wrote in that the answer was wrong2. Comments varied from “You made a mistake, but look at the positive side. If all those PhDs were wrong, the country would be in some very serious trouble” to “I must admit I doubted you until my fifth grade math class proved you right”2.
The Points of Significance column will help you move beyond an
intuitive understanding of fundamental statistics relevant to your work. Its aim will be to address the observation that “approximate- ly half the articles published in medical journals that use statistical methods use them incorrectly”3. Our presentation will be practical and cogent, with focus on foundational concepts, practical tips and common misconceptions4. A spreadsheet will often accompany each column to demonstrate the calculations (Supplementary Table 1). We will not exhaust you with mathematics. Statistics can be broadly divided into two categories: descriptive and
inferential. The first summarizes the main features of a data set with measures such as the mean and standard deviation (s.d.). The second generalizes from observed data to the world at large. Underpinning both are the concepts of sampling and estimation, which address the process of collecting data and quantifying the uncertainty in these generalizations
