# 不妨来学学英语

说到英语, 或许会让一部分人感到头疼. 确实是这样, 英语本身是人类的一种自然语言, 当我们已经熟悉了自己的母语之后, 再学习其他语言是有一定门槛的.

当然, 我并没有打击你的意思. 要知道, **我们身边随处可以看到一些程序开发人员, 或者机房运维人员一句英语都看不懂的情况**. 英语对于程序开发本身来说并不是非常的重要. 追究其原因, 要知道程序开发主要是**思路和思想**, 而不是**用什么语言去说明**.

所以, 你也大可不必害怕英语把你难倒了. 但是这可不是说英语对于程序开发是毫无用途的. 相反, 英语在程序开发中起到了一个分水岭的作用 - 它**决定**你是否可以成为**高级程序员**.



# 拼音不能代替英语

有人说, *我们写代码的时候如果不会英语, 可不可以用拼音来写代码呢*?

是的, 严格上说, 你确实可以使用拼音写代码. 而且这样写出的代码一样能运行, 也不见得会有什么问题. 但是重要的是, 这样做的话, **是严重影响开发效率的**.

为什么会这样? 设想一下, 我们以 *编程的方式* 这个标识符名称为例. 如果用英语写, 我们可以写作 *TheProgrammingWays* , 而用拼音写的话, 需要 *BianChengDeFangShi* .

直接看上去的话, 两种代码似乎都很美观且漂亮. 但仔细读起来就会发现一个致命的问题 - 拼音拼起来费时费力, 因为一个拼音对应了太多的中文汉字.

用你的输入法输入 *BianChengDeFangShi* , 然后观察屏幕上的候选词, 体会一下, 在代码阅读中将拼音拼出来是多么的困难.

而英文单词/英文短语却不会出现这么一个问题.



# 英语可加快代码阅读速度

要知道, 这种需求往往出现在和他人合作开发的时候; 或者是某代码先前是他人编写的, 由你来进行后续的接手维护.

这个时候你需要阅读他人的代码, 但他人的代码往往出于一种编程规范, 统一使用了英文标识符名称. 这时候英语的重要性就凸显出来了 - 如果你会英语, 你甚至可以只看名字就知道某个函数/某个变量是干什么用的. 否则, 你可能需要将大量的时间消耗在弄清楚函数的功能上.

说到标识符名称, 这里还有一个非常有趣的应用, 那就是 *代码混淆* . 代码混淆作为一项代码保护手段, 通过将所有的标识符名称重命名成乱码或随机生成的字符, 进而让逆向分析人员难以阅读, 加大软件逆向所需要的成本和技术门槛.

所以说, 我可不希望看到我的代码, 在你的世界里都是像是被"混淆"过一般.



# 英语也是为了阅读技术文档

或许我们学习编程的时候, 跟着教程一步步的走, 就能够将任务完美的完成. 但是在实际开发当中, 我们还能找到这样完美的教程么?

如果你还认为什么东西都可以搜到中文资料, 那么你就真的是太天真了. 现在, 假设你需要制作一个Windows内核驱动程序, 用于实现一个最简单的硬件虚拟化. 那么, 请你去搜索引擎搜索一下, 你真的能搜到VT层的相关中文资料么?

对不对, 当然是资料少的可怜. 我们在实际开发当中, 难免会遇到一些陌生的领域. 这可能是我们从来没用过的一些库类, 也可能是非常小众的一些知识点, 更可能是前无古人后无来者的全新领域. 而这时候, **官方英文资料就显得相当重要**.

再回到这个硬件虚拟化驱动的话题上. 假若我们英语好的可以, 那么我们可以直接去看Intel或AMD提供的技术手册, 阅读VT-x或SVM的相关资料, 自己编写控制代码实现.

当然, 如果你问, *为什么官方资料都是英文写的呢?* 我只能说, 英语作为一门国际化语言, 有着国际化的天然优势. 或许比起英语来说, 我们更不想阅读一份超小众的小众语言编写的文档吧!

**注: 此处谈到的VMM驱动已有较为完善的开源实现, 如您很有兴趣, 可前往github项目HyperPlatform自行研究. 研究此项目需要相当多的计算机底层知识储备, 难度评估: 9/10*



# 英语用于阅读调试信息

还记得, 之前说过的程序报错信息么?

实际上, 一些常见软件的报错是完全符合人类语法的, 不管是中文还是英文, 还是其他语言. 因为你要明白一点, **报错信息就是给人看的**. 假设人都看不懂报错信息, 那么这个报错信息可谓是毫无意义.

举个例子, 假如我们的服务器某天出现了 *No space left on device* 的提示, 我们就可以直接根据提示来知道 "这是因为硬盘满了" . 反之, 我们是不是要花费很多的时间去排查问题的原因, 浪费一大堆人力物力之后, 才知道是硬盘被占满了呢?

其他软件也一样是这样.



# 英语也用于圈内交际

不管你的对面是其他国籍的程序员, 还是自己国内的程序员, 在圈内交际中, 往往都会离不开英语的使用.

比如, 我们在日常的交流当中, 会直接使用 "VLAN" 代替 "虚拟局域网" 这几个字, 也会使用 "Windows" 来代替 "微软视窗操作系统" 这几个字. 虽然仅仅是几个单词, 但这却来的方便有效, 而且更清晰准确的表达了自己心中的意思.

而对于和其他国际的程序员交流的情况, 英语当然就显得更重要了. 因为你们之间, 可能唯一相通的语言, 除了一门英语, 也就只剩下阿拉伯数字啦~~~



# 学英语不一定要全学

当然, 如果你的时间或记忆力不允许你将英语本身学好, 那么有一个简单有效的办法学英语 - 那就是学 *专业英语* .

所谓专业英语, 那就是学习你所在领域内的术语单词和常用单词, 以便你能以最快的速度将学习到的英语知识用到实际使用当中.

我们举几个例子. "文件" => "File". "保存" => "Save". "另存为" => "Save as". "复制" => "Copy" ...

就是这么一种感觉. 这些单词或许你也不需要主动学习, 只要在日常生活中混个脸熟, 哪怕是不会读, 也能大概知道这几个单词是什么意思. 但这却对你的工作效率起着很大的帮助.

当然, 这只是一个比较另类的办法. 我本人当然还是推荐多学习一些基础英语知识. **多学一门知识, 有备无患嘛.**



# 别把单词拼错

要知道, 在社交圈子内, 将单词拼错是一个非常丢人的事情.

对于我们自己认不准的单词, 我们可以先搜索, 或者查询词典后, 确认单词准确无误之后再使用. 千万不要将单词用错呢.

否则, 拼错的单词虽然不影响阅读, 但是却能显示出你十分的不专业. 这是一件很丢人的事情.



# 日常积累就好了

接下来我们再来聊聊学英语本身吧.

学英语实际上没有什么好办法, 至少我是没有办法提供太好的学习方法. 个人认为, 学英语根本上还是单词和句式的积累.

但是有一个良好的英语环境会让你进步的很快. 设想你如果天天和一些英语单词打交道的话, 你肯定很快就会弄懂一部分单词是做什么的. 随着知识量的增长, 词汇也能逐渐形成一张网络.

这么说的话, 使用英文软件要比汉化软件要更有优势. 当然前提是你要会用哦.



# 放轻松, 别害怕

最后要说的是, 放轻松.

不要被刚才说的吓到了. 实际上哪怕你一个单词都不会, 你依然是可以学习计算机领域知识的. 别急嘛, 我们一步步, 慢慢来填补这些空缺.

要知道在很多年前, 我本人的英语基础是差的可怕的. 而现在的英语积累虽然也并不是非常的好, 但至少将一本英文资料拿过来直接读是毫无问题的.

这个能力是如何锻炼的? 就是不断地去尝试, 去使用. 

一项语言也好, 一项技能也好, 你越去想办法深究它, 你知道的东西也就会越多. 但越多并不代表你越快乐, 也并不代表你学的越深. 相反, 有些时候只需要慢慢进步, 反而能收获到一些意想不到的成就.

不管是计算机领域, 还是英语, 还是其他领域, 都是如此.