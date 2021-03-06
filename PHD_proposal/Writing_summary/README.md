科学写作与哲学 [科学写作与哲学 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/433168083)

CVPR 9999 Best Paper——《一种加辣椒的番茄炒蛋》 [CVPR 9999 Best Paper——《一种加辣椒的番茄炒蛋》 - 知乎 (zhihu.com)](https://zhuanlan.zhihu.com/p/433237905)

[你提出的idea为什么会被别人抢先做出来？怎么写Introduction和Abstract？ (qq.com)](https://mp.weixin.qq.com/s/wg52Fi3guibVvUUzYVTqKg)

**introduction写作和abstract**
[你还在为idea纠结么？这里告诉你两种提idea的思路 (qq.com)](https://mp.weixin.qq.com/s/HzeD2-lIs3HMHVgTt5vJkA)

方法的设计写作
[论文的实验部分应该怎么写？读者需要我们给他们展示什么试验结果？ (qq.com)](https://mp.weixin.qq.com/s/1YLTFOUxY0-ANPbW-oekUA)

实验设计

# 学术写作

此文用于分享一下一个老博士的科学写作经验。本博士写作水平只能说是将将及格，因此不敢舔着脸好为人师，此文仅当做一种信息交流，以供后来者扬弃。场面话言尽于此，下面我将正式从头到尾讲讲我的心得。

## 哲学原则

最初尝试科学写作的人，也大致了解文章分为abstract, introduction, related works, approaches, experiments, (optional) applications, conclusion 这几章。但是具体写起来，科研小白们，包括我自己一开始，都是一样无从下手的。经过这么多年混下来，终于初悟此道。

一个科研小白，最常用的思维是线性而非[层次化](https://www.zhihu.com/search?q=层次化&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})的。因此，他对于项目的理解往往是我干了A所以有a，然后干了B所以有b，然后我又干了CDE，最后我的系统是ABCDE，发现厉害了。然后谈[related work](https://www.zhihu.com/search?q=related+work&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})，ABCDE是related work，了事了。对，你是厉害了和了事了，但听者什么也没学到。一个好的论文，原则是用最少的文字最精准的传达关于项目的知识。

小白可能不服气——我都说了ABCDE了，该说的都说了，不然你让我怎么描述知识呀？！这时，我极其想给他推荐几篇[柏拉图](https://www.zhihu.com/search?q=柏拉图&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})和亚里士多德的作品，不过我就简单搬运一下：

1. [Theaetetus](https://zhuanlan.zhihu.com/p/401946696), 知识是正确的见解加与其他易混淆事物差异的解释。
2. [Philebus](https://zhuanlan.zhihu.com/p/408373372)/[Timaeus](https://zhuanlan.zhihu.com/p/409572819)，无限的多是一种混沌，有限的一是美的。
3. [Statesman](https://zhuanlan.zhihu.com/p/406811959)，本质的划分导致精确的概念的讨论。
4. [Categories](https://zhuanlan.zhihu.com/p/419743663)，普遍的还是个例的，必然的还是偶然的？
5. [Prior Analytics](https://zhuanlan.zhihu.com/p/423141967), [三段论](https://www.zhihu.com/search?q=三段论&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})。
6. Posterior Analytics（尚在写作中），证明是从在先的必然的结论出发的三段论。定义是本源实体的最先描述。

由此，ABCDE模式的几个显著缺陷就明了了。一方面，这虽然详述了你的方案，但读者并不知道它与他所知道事物的联系，他有可能认为这就是某些已知的知识，或者认为这就是[天方夜谭](https://www.zhihu.com/search?q=天方夜谭&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})，不知所以，总之没有建立与他人知识体系的联系。二方面，东西太多，虽然还未达到无限，但已经非常繁琐，非常没有美感，别人记不住，也不欣赏。三方面，人类常说“知识树”，因为知识是一种[树状层次化结构](https://www.zhihu.com/search?q=树状层次化结构&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})，ABCDE像是粗暴的在树旁边竖了根电线杆，让人反胃。另外，ABCDE可能人家觉得不本质或不必然，感觉你没逻辑。

概括一下写作几大原则：

1. 差异联系原则
2. 有限性原则
3. 层次化原则
4. 普遍性原则
5. 必然性原则
6. 前提明晰原则

## 几大写作谬误

既然有了哲学指导，违反哲学原则的几大谬误应运而生。

1. 只关注自己的工作或别人的工作——在非related work里只说自己干了啥，在related work里只说别人干了啥。（违反[差异联系原则](https://www.zhihu.com/search?q=差异联系原则&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})，让人觉得你在自说自话）
2. 详尽列举自己的做法，列举了一长串；或不列自己做法，直接上一个雷人的大描述。（违反有限性原则，让人听着头昏。就一句话而无细节，又让人感到空泛茫然。）
3. 该说大事的时候沉浸在细节的描述。（违反层次化原则，让人不知道你在讲什么）
4. 过度把自己的个例说成普适性的，把自己闪光的普适性方法说成了一个小例子。（违反普遍性原则，要么错误包装，要么没有正确体现价值）
5. 说我怎么做，但没说为啥我要这么做。（违反必然性原则，人家为啥要按你说的做，傲慢）
6. 非必然三段论逻辑（违反前提明晰原则，总觉得你这么做不solid）

该吐槽的都吐槽完了，下面便是每个原则在各段中的体现，我们一一分析。

## 知识的差异与联系

Related Works模块的设计非常好的体现了这个宗旨——你不说别人做了啥，我咋知道你做了啥？因此，最明显的体现便是Related Works。而其正确的写作思路应当是别人做了啥，有啥问题，我们和他这方面不一样，正好解决了这样的问题。相当一部分写作者，只写别人干了啥，没写我和他哪里不一样，这种作者就是没有理解Related work章节设计的初衷——Related works是从别人的工作中对比着来介绍自己的工作。

除了显性的Related works，知识的差异和联系原则可以在各个地方被使用。比如Introduction，不能直接说我们通过做什么把事情做牛了，而应当说这个事情就这么多做法，挂在了哪里，我们在挂掉的地方做了什么事，从而把事情做牛了。我们甚至不能只说我们要做什么事情，我们还得说这事情和其他事情有啥差别。比如Approach介绍创新方法，也不是ABCDE的平铺直叙。应该说在设计A时，直觉上容易想到A1, A2, A3几种方法但都因为什么而不work，我们的A和这些方法的区别是XXX（真实的创新），从而能work。比如在实验中人们长考虑使用而我们不使用的数据或方法，我们也要说这实验看上去可以做，但由于XXX的点和人们预想的不同，这实验我们不做。

**我的原则是，凡是哪个地方存在某种似是而非的替代方法或解释或实验，我们都必须论述他们并强调他们的某一个差异点，从而得出我们的创新方法、数学模型、或实验方案。**

## 有限性、分类和层次化

我们时刻要记住有限性原则，有限性即时在任何一个尺度上我们都不能给读者暴露出过多平行的概念。然而做一个项目，其要点确实可能多如牛毛，所以层次化的写作对于有限性的展示知识至关重要。科学论文实质上无处不体现其有限性和层次化：

整体框架是有限的几个段落，abstract/introduction/relatedwork/approach/experiment。

Introduction就干有限的四件事：先说问题重要，二说现有方法垃圾，三说我们方法牛逼，四说我们实验牛逼。related works干若干件事，简单点说就是把related works按照几类不同联系方式进行分组，每组分别讨论。Approach需要把自己的创新方法分模块介绍。Experiments需要把自己试验按照不同的目的或结论类型分类。

然而层次化远没有就此结束——比如introduction说问题重要，并不是只说我们做的三维重建重要。应该说三维重建可以分为是否带range sensor，不带range sensor的是否是多目的，多目里面是物体还是场景的，直到层次化并向下划分到那个你所需要去做的问题的最大集合为止。说现有方法垃圾也是这样，得先说现有方法从哪几个方向来解决哪些挑战，每个挑战又有哪些方法从哪个角度解决，最后才能说他们都是垃圾。

Approach也是如此，大模块里分小模块，小模块里分更小的模块，最后要保证每个模块底下的小模块或者最终的技术点不能太多太杂。一个人的方法如果一招毙命，那就写一句话了事。如果方法稍多，就要分模块在subsection描述，如果某模块太多就要分paragraph描述，如果还不够用就将approach拆分成多个section，再写一个section叫overview。

## 层次化的应用

既然一个优秀的文章应当是层次化的，那么我们写作如何做到层次化呢？**我有两招——自顶向下的划分法，和自底向上的[归纳法](https://www.zhihu.com/search?q=归纳法&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})。**

当我想描述某件事，结果显而易见的找到了简短的一句话就描述它时，我就要非常警惕，因为我所描述的可能是一个过于普遍而不精确的事情。比如我做了个牛逼的方法，跟别人说我是搞三维[建模](https://www.zhihu.com/search?q=建模&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})的（introduction第一段）。这就是自顶向下划分法的重要时刻。我要思考三维建模分哪几类，我是哪一类，如果还不够充实，就需要再次划分。学术论文里无需严格按照《Statesman》里所说的一定是本性的穷尽的二元划分；他的原则是在所预期的长度内进行最优的本性划分。

相反，当我想描述我的工作，事情多如牛毛，我就要把事情列一下，找共性，进行归纳。共性具体可以指相似的目的、方法、流程模块。若共性归纳了一波，发现不同的共性还是太多，那就需要进一步归纳不同共性之间的相似性，直到满足每个模块3-5个子模块的原则。

## 普遍性原则

描述一件事，就应当描述的恰当好处。比如有人问你，什么玩意儿爱吃肉，不应当回答回答老虎也不应当回答动物，应当回答食肉动物。

例如有个人做了个牛逼方法，明明适用于大场景的室内环境，他说自己适用于小屋子，那就把自己的价值说小了。如果他说适用于各种环境，读者就会吐槽他，这样的假设根本不适用于室外环境。除了适用范围，方法也是如此。例如某个模块，我们明明可以适配一类方法，那就不能说我们就用了XX方法。别人会觉得XX方法有很多局限性，你这个方法有问题啊！事实上我们只要是满足性质A的方法都可以用，XX方法是性质B有问题，所以本质上我们的方法没问题。但正因为我们描述时错误的失去了普遍性，导致自己把自己写出了问题。

**我的原则是，在论文的每一句话里，都应当严格的保证主语和宾语所应当具有的[普遍性](https://www.zhihu.com/search?q=普遍性&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})的度拿捏的恰到好处，不过分吹牛，也不贬低自己，不卑不亢。**

## **前提清晰和必然性原则**

我读了一些学生写的论文，发现逻辑总是不让人满意，断断续续，最后发现主要是没有用必然三段论去证明自己所写的东西的实在性。

v0：我们在系统里用了个牛逼的A模型。听上去很好，其实毫无信息量和逻辑。
v1: 因为数学模型A可以导致良好的位姿预测，所以我们在系统的某个模块用了它。听上去没毛病吧？但是谁说了系统需要良好的位姿预测呢？
v2: 我们系统需要准确的位姿，正巧数学模型A可以满足我们的需要，所以我们用上了它（实然三段论）。没毛病了吧？但是谁说一定要用数学模型A呢？
v3: 我们系统需要准确、快速、大场景可泛化的位姿，行业一类准确模型不快速，一类快速问题只适用于小场景，只有最近某个方法A正好都适用，所以我们在系统里使用了A（必然三段论）。

v0没有逻辑，v1逻辑缺失，v2逻辑不必然，v3才是完备的证明逻辑。

当然，我们的科学写作并不是通篇严谨的必然三段论证明，因为那样就太长了，同时也违反了有限性原则，因为形成逻辑的命题数量本身也应当遵循[有限性](https://www.zhihu.com/search?q=有限性&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})原则。因此，重要的命题一定要使用v3，无关证明的可以直接使用v0这种陈述方式，而大多数情况不会过于无关紧要，可以采取v1的[省略三段论](https://www.zhihu.com/search?q=省略三段论&search_source=Entity&hybrid_search_source=Entity&hybrid_search_extra={"sourceType"%3A"article"%2C"sourceId"%3A433168083})或者v2的实然三段论模式。

总结一下，过量的v0和v1会导致文章不流畅，过量的v2, v3会导致文章冗余。但是对于重要的证明，一定要采取v2甚至v3的论述方式，才能把最重要的论点用最强的证明逻辑扎在读者心里。

## 语言

最后讲讲语言。其实英语不需要太好，事实上我的英语可以说是属于非常不好的那一类。但这顶多会影响写作的优美度，却不会影响到写作的合格度。

我认为语言无非就是三个原则——长度最小化，信息最大化，描述真实化。用最少的长度，描述最大的信息量，并保证一定处于正确的范畴中。只要满足三个原则，这篇写作就是合格的。

## 样例

做人不能太严肃，我写了一篇样例，仅供大家玩笑，为论文实操，九阴真经下卷。
