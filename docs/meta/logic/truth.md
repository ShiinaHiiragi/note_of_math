# 2 真理与悖论

## 2.1 逻辑真理
### 2.1.1 真值与语义
1. 形式化语言中的真概念：对于一个给定的语言，建立一种实质上充分和形式上正确的关于「真语句」这个词项的定义
    1. $\text{T}$ 等式：$X$ 是真语句当且仅当 $p$，例如「『雪是白的』当且仅当雪是白的」
        1. $X$ 可由此语句的名称代替，其名称可以是引号名称或结构摹状名称
        2. $p$ 可用「真的」这个词适用于它的任何语句代替
    2. 将 $\text{T}$ 等式应用于日常语言时，会导致悖论。为避免悖论，一个可接受的真定义必须满足两个限制条件
        1. 实质的充分性和内容的适当性
        2. 形式的正确性
2. $\text{Tarski}$ 真概念的非形式定义
    1. 定义真概念的程序
        1. 规定对象语言 $\mathscr O$ 的语法结构，真谓词是相对于 $\mathscr O$ 而被定义的
        2. 规定元语言 $\mathscr M$ 的语法结构，其中「在 $\mathscr O$ 中为真」将得到定义
        3. 在 $\mathscr M$ 中定义「在 $\mathscr O$ 中满足」
        4. 在 $\mathscr M$ 中根据「在 $\mathscr O$ 中满足」定义「在 $\mathscr O$ 中为真」
    2. 通过「满足」定义「真」：符合的闭语句并非直接由原子闭语句构造而成，而是由语句函项（即开语句）构造而成，开语句并不是真的或假的，而只是为对象所满足或不满足
        1. 满足是开语句与对象的 $n$ 元有序组之间的关系，复合开语句由原子开语句的满足来定义
        2. 闭语句是零元开语句，闭语句的真被定义为「被所有序列满足」，闭语句为假被定义为「不被任何序列满足」
3. 经典逻辑的逻辑真
    1. $\text{Leibniz}$ 区分逻辑真理与事实真理
        1. 推理的真理：必然的，其否定是不可能的。必然真理的依据是矛盾律，在所有可能世界真
        2. 事实的真理：偶然的，其否定是可能的。偶然真理遵守充足理由律，只在有的可能世界中为真
    2. $\text{Quine}$ 提出五个等价的逻辑真定义
        1. 根据结构为真：对于一个语句，如果具有它的逻辑构造的所有语句皆为真的话，则称这个语句逻辑上为真
        2. 根据替换为真：对于一个语句，如果对于它的谓词的所有改变，它都保持为真，则称这个语句逻辑上为真
        3. 根据模型为真：将语句的一切替换转化为集合的一切指派，只要对象语言包含初等数论，则两个定义等价
        4. 根据证明程序为真：选择一些明显地逻辑真的语句，并运用从公式变换到公式且保持逻辑真的形式规则，（依据 $\text{G}\ddot{\mathrm o}\text{del}$ 一阶逻辑完全性定理）所能得到的就都是逻辑真命题
        5. 根据句法为真：一逻辑真语句就是在对其词汇做替换时不可能变为假的语句，当用任何属于同一语法范畴的别的符号串来替换其词汇成分时，所得到的那个语句为真

### 2.1.2 逻辑真的性质
1. 分析性：语言哲学的区分
    1. $\text{Kant}$ 阐述分析命题和综合命题的区别
        1. 分析命题：通过谓词不给主词的概念增加任何东西，仅将在主词中所已经始终思考着的内容分析为构成分析命题的概念
        2. 综合命题：给主词概念增加一个在任何方式下都没有思考过的谓词，且这个为此不能用分析的方法从主词中抽引出来
    2. 逻辑实证主义使用证实原则说明逻辑数学命题的真理性和普遍必然性
        1. $\text{Carnap}$ 将分析命题定义为「没有任何经验内容的重言式」
        2. $\text{Ayer}$ 将分析命题定义为「其效准仅依据于它所包括的那些符号的定义的命题」，将综合命题定义为「其效准决定于经验事实的命题」
        3. 排斥先验综合命题的存在，将任何必然命题一并归于分析命题
    3. $\text{Quine}$ 反对经验论的两个教条
        1. 哲学上的陈述分为两类，一类是逻辑真的陈述，另一类是能通过同义词替换而变成一个逻辑真的陈述
        2. 依赖同义性说明分析性时，同义性标准必须首先提供，人们利用同义词定义、保全真值地可替换性、人工语言内的语义规则来说明和刻画同义性都直接或间接地包含逻辑循环
        3. 分析陈述和综合陈述地分界线不可能被划分出来，认为有这样的一条可划是经验论者的一个非经验的教条

        !!! note "整体主义知识观"
            $\text{Quine}$ 用如下的整体主义知识观批判还原论

            1. 人们的信念或知识是作为一个整体来面对感觉经验法庭的，具有经验意义的是整个科学
            2. 由于整体内的各个陈述在逻辑上是相互联系的，所以对整体内部的某些陈述的再评价必将引起整体内部的重新调整及对其真值的重新分配
            3. 在经验面前，整体内部的任何陈述都可以被修正或免予修正，甚至逻辑—数学规律也不例外，这是因为经验证据对于理论整体的决定是不充分的
            4. 所以在理论的评价和选择上，更不存在唯一确定的真理标准，而是受是否方便和有用这样一些实用主义的考虑所支配

            驳倒还原论和意义的证实论，分析命题和综合命题的区分就再无成立的可能

2. 必然性：形而上学的区分
    1. 必然性的定义
        1. 诉诸事物的本质：必然性是指现实中由本质因素决定的确定不移的联系和唯一可能的趋势；偶然性是指现实中由非本质的、互相交错的因素决定的并以多种不同形式来呈现的联系
        2. 诉诸矛盾律：$\text{Leibniz}$ 认为，一个真理是必然的当且仅当其否定包含逻辑矛盾
        3. 诉诸可能世界：$\text{Leibniz}$ 将「$A$ 是必然的」定义为「$A$ 再所有可能世界中为真」
        4. 诉诸事件：$\text{Aristotle}$ 认为必然发生就是总是发生，事物的存在是必然的当且仅当其是永恒的
    2. 绝对必然性和相对必然性
        1. $\text{Aristotle}$ 认为，如果主项 $a$ 和属性 $b$ 之间有本质的联系，或 $b$ 是 $a$ 的本质，则称 $a$ 具有 $b$ 是绝对必然的；主项 $a$ 和谓项 $b$ 有本质联系是指 $b$ 是 $a$ 的本质中的一个因素或 $a$ 是 $b$ 本质中的一个因素
        2. $A$ 是绝对必然的，即 $A$ 是普遍地并且是无条件地真的；$A$ 是相对必然的，是指 $A$ 的真是有前提的、有条件的，这种必然性是 $A$ 与其他命题的一种关系
3. 先验性：认识论的区分
    1. 传统观点认为逻辑真理具有 $\text{Kant}$ 意义的先验性
    2. 经验论观点：$\text{Mill}$ 归纳主义
        1. 逻辑和数学同自然科学都属于科学知识体系
        2. 逻辑命题和数学命题与事实或实在有关，根本上以经验为基础，所依靠的经验是「重复多次的经验」
        3. 由于逻辑和数学命题被认为只是一种经验真理或归纳真理，因而关于逻辑和数学命题的必然真理性信念只是一种错觉

## 2.2 逻辑悖论
### 2.2.1 悖论与解悖
1. 悖论的宽定义包括三种情况
    1. 与公认的看法或观点相矛盾的命题或原则，似是而非，但潜藏着深刻的思想。例如 $\text{Zeno}$ 悖论以及 $\text{Kant}$ 的四个二律背反
    2. 从一组看似合理的前提出发，通过有效的逻辑推导得出一对自相矛盾的命题，它们与当时普遍接受的常识、直观、理论相冲突，但又不容易弄清楚问题在哪里，例如 $\text{Cantor}$ 悖论
    3. 狭定义：从看似合理的前提出发，通过看似有效的逻辑推到，得出互相矛盾的命题构成的等价式 $\alpha \leftrightarrow \neg \alpha$，例如 $\text{Russell}$ 悖论
2. 悖论的解决方案
    1. $\text{Russell}$ 认为悖论的解决方案至少满足三个条件：① 让悖论消失；② 尽可能让数学保持原样；③ 非特设性
    2. $\text{Haack}$ 在概括 $\text{Russell}$ 论述的基础上，对悖论的解决方案提出更明确的要求
        1. 从形式或技术上来说，这种方案应提供一套相容的或一致的语义学或集合论理论，用以表明导致悖论的那些看似无懈可击的前提或推理原则必须被拒斥
        2. 从哲学上说，这种方案应说明为什么导致悖论的那些前提或推论看上去是无懈可击，而实际上却必须被拒斥
3. $\text{Ramsey}$ 将已知悖论分为逻辑—数学悖论与语义悖论
    1. 句法悖论：即逻辑—数学悖论，只与元素、类或集合、基数和序数等数学概念相关，它们能用符号逻辑体系的语言表述，并且只出现在数学中
    2. 语义悖论：不是纯逻辑和纯数学的，而与一些心理的或语义的概念如意义、命名、指称、定义、断定、真假等相关
    3. 语用悖论：与语境和认知主体及其背景知识有关，即与知道、相信、怀疑、允诺或希望这一类知道行动的话语或态度有关的概念相干的悖论。例如考试悖论

### 2.2.2 句法悖论
1. 句法悖论例举
    1. $\text{Burali}-\text{Forti}$ 悖论：假设 $\mathbf{On}$ 是集合，且 $\forall \alpha \in \mathbf{On}$ 皆是序数，所以 $\mathbf{On}$ 是良序集。因此 $\mathbf{On}$ 是可递集，$\mathbf{On}$ 是序数，这与序数的反自反性矛盾
    2. $\text{Cantor}$ 悖论：假如 $\mathbf{Cn}$ 为集合，那么 $\cup \mathbf{Cn}$ 也是基数，而且比所有基数都大，但是最大的基数不存在。因此，$\mathbf{Cn}$ 不是集合，否则利用替换公理，$\mathbf{On}$ 也可以是集合
    3. $\text{Russell}$ 悖论：定义集合 $S = \{x \mid x \notin x\}$，则可得出结论 $S \in S \leftrightarrow S \notin S$
2. 句法悖论的解决方案
    1. $\text{Russell}$ 的类型论：禁止任何形式的恶性循环
        1. 简单类型论排除已知的集合论悖论：$\text{Burali}-\text{Forti}$ 悖论、$\text{Cantor}$ 悖论与 $\text{Russell}$ 悖论
        2. 分支类型论排除如 $\text{Richard}$ 之类的语义悖论
    2. 公理集合论：对于 $\text{Russell}$ 悖论
        1. $\mathbf{ZFC}$ 公理集合论否定任一性质 $R$ 决定一个集合 $S$，从而对集合的生成做出更严格的限制
        2. $\mathbf{BGC}$ 公理集合论否定对任一集合 $S$，$S \in S$ 是一有意义的命题，从而对集合元素的身份做出更严格的限制
    3. $\mathrm{NF}$ 系统与 $\mathrm{ML}$ 系统：$\text{Quine}$ 构造的类型论替代
        1. $\mathrm{NF}$ 系统：逻辑加集合论，用分层公式的方法避免悖论，包括三个部分 ① 真值函项理论；② 量化理论；③ 类理论
        2. $\mathrm{ML}$ 系统：将类区分为两种
            1. 可以充当某个类的元素的类，称为元素或集合
            2. 不能作为某个类的元素的类，称为非元素或真类

### 2.2.3 语义悖论
1. 语义悖论例举
    1. 说谎者悖论：起源于公元前六世纪，希腊克里特岛人 $\text{Epimennides}$ 说的「所有的克里特岛人都说谎」。一般表述为

        $$
        \boxed{\textsf{本方框内的这个语句是假的}}
        $$

        !!! note "说谎者悖论的变体"

            1. 明信片悖论：一张明信片的正面写有「此明信片背面的那句话是假的」，背面写有「此明信片正面的那句话是假的」
            2. 经验悖论：一组命题的真假取决于其中一个支命题的真假，后者通过迂回的途径声称自己为假，例如「$2 \times 2 = 4$ 并且这个合取命题是假的」
            3. 加强的说谎者悖论：对经典逻辑进行改造以规避说谎者悖论无法摆脱加强的说谎者悖论，例如「本语句不是真的」

    2. $\text{Richard}$ 悖论：已知任一语句都是用可能重复的某种语言的字母加上若干其他符号或空位构成的有穷长的符号序列
        1. 有能用有穷长语句加以定义的一切十进制小数组成一个集合 $E$，令 $E$ 中的元素按字典序排列为 $e_1, e_2, \cdots, e_n, \cdots$，令 $e_n = 0.x_{n1}x_{n2}\cdots x_{nm} \cdots, n, m \in Z_+$，其中 $x_{nm}$ 表示 $e_n$ 的小数点后第 $m$ 位数
        2. 构造无限十进制小数 $f = 0.y_1 y_2 \cdots y_n \cdots$，其中 $y_n = \left\{\begin{aligned} & 0, & x_{nn} = 1 \\ & 1, & x_{nn} \neq 1 \end{aligned}\right.$
        3. $f$ 是能用有穷长的语句加以定义的无限十进制小数，因此 $f\in E$；但由 $f$ 的定义可知 $f$ 与 $E$ 中任意元素都有一个有穷差值，因此 $f \notin E$
    3. $\text{Berry}$ 悖论：摹状词「无法用十六个汉字命名的最小正整数」指称的整数
    4. $\text{Grelling}$ 悖论：也称非自谓悖论。将所有形容西分为两类
        1. 对自身适用的（例如「四个字的」或「中文的」），称之为自谓的
        2. 对自身不适用的（例如「单音节的」或「红色的」），称之为非自谓的

        则形容词「非自谓的」是自谓的当且仅当它是非自谓的

2. $\text{Tarski}$ 语义学：对象语言即语言系统中被作为研究对象的语言；元语言即用来指称对象语言的语言
    1. $\text{T}$ 等式应用于日常语言时会导致悖论：令符号 $C$ 表示「$C$ 不是一个真语句」，则「$C$ 不是一个真语句」是一个真语句当且仅当 $C$ 不是一个真语句
        1. $\text{Tarski}$ 认为悖论的产生有两个原因：① 语义封闭性，即这种语言不仅包含它的语句及其他表达式，而且包含了这些语句和表达式的名称，以及包含这些名称的语句；② 通行的逻辑推理规则在其中成立
        2. 日常语言的普遍性是造成一切语义悖论的根源，在一个丰富、普遍的语言系统内，无矛盾地定义真概念是不可能的
        3. 一个可接受的真定义应该满足两个限制条件：① 实质的充分性或内容的适当性；② 形式的正确性
    2. 真定义的形式正确性包括以下要求
        1. 必须区分语言层级，即区分对象语言和元语言
        2. 这两种语言都必须具有「明确规定的结构」，即都必须用公理化、形式化的方法来表述：首先给出不加定义的初始词项，给出造词、造句的形成规则，通过定义引入其他此项、其次给出与初始词项相关的公理和推理规则，并经过证明程序得到定理或可证语句
        3. 元语言必须比形式语言在实质上更丰富，即元语言必须把对象语言作为一个真部分包括在自身之内
    3. $\text{Tarski}$ 区分了两种形式的语言
        1. 较贫乏的：元语言比对象语言更丰富、具有比对象语言更高的逻辑类型。对于这类语言，无矛盾地给出实质上充分、形式上正确地真定义是可能的
        2. 较丰富的：对象语言和元语言中的变元具有相同的逻辑类型，以致元语言中的所有词项和语法形式都能在对象语言中得到翻译。对于这类语言，要给出这样的定义而不导致矛盾是不可能的（$\text{Tarski}$ 真不可定义性定理）
    4. $\text{Tarski}$ 语义学的质疑
        1. 强烈的特设性：语言分层与日常语言习惯和知觉相冲突，因为日常所使用的知识同一个语言，而非多个语言
        2. 语言层次的终结性：分层体系是否终结于同一的元语言；若有这样的元语言，是否会像其他语义封闭的语言一样产生悖论
        3. 在这种分层的语言中，也可以构造出一个悖论性语句：「这个语句在分层语言的任何层次上都不是真的」
3. $\text{Kripke}$ 真理论
    1. 利用 $\text{Kleene}$ 强三值逻辑模型，以严格的形式手段发展 $\text{Martin}$ 与 $\text{Woodruff}$ 的观点：只存在一个真谓词，它可以用于含有这个谓词的语言本身，但这种语言不会导致悖论，其办法是允许真值间隙并使悖论性语句处于这种间隙之中
    2. 有根性
        1. 一个语句是有根的当且仅当可以通过一定的程序将其真值归结为某个先前语句的真值，或者通过某个先前的语句是否为真来确定其是否为真
        2. 一个含有多个叠置的真谓词的语句是有根的当且仅当最终可以通过这种程序将其真值归结于某个不含真谓词的语句真值
        3. 悖论性语句是无根的，它们处于真值间隙中，但并非所有无根的语句都是悖论
        4. 如果一个合式公式在最小的固定点上有一个真值，则这个公式就是有根的，否则就是无根的；北仑语句是一个不能再任何一个固定点上一致地指派真值的语句
    3. $\text{Kripke}$ 真理论的质疑
        1. 对极小点的归纳定义是在一个集合论语句中而不是在该对象语言本身中给出的
        2. 一些关于对象语言的断定不能在该对象语言中给出，例如「『本语句是假的』不是真的」
        3. 由于有根性都不属于该对象语言，因此无法解决例如「本语句是假的或无根的」的加强说谎者悖论
4. 其他观点
    1. 悖论是思维甚至外部世界中固有的、无法摆脱的。$\text{Herzberger}$ 的朴素语义学、$\text{Priest}$ 的次协调逻辑主张修改传统真理论，从矛盾中可以推出任意命题的经典逻辑
    2. $\text{Kripke}$ 固定点理论开始了向自然语言的回归，语词的含义和指称以及语句的真值都是与语境因素相关的，例如情景语义学就是一种语境敏感方案

### 2.2.4 悖论的性质
1. 悖论的产生原因
    1. 自我指称：一个总体的元素、分子或部分直接或间接地又指称这个总体本身，或者要通过这个总体来加以定义或说明
        1. 分类：直接循环（例如说谎者悖论）与间接循环（例如明信片悖论）
        2. 通常只有自我否定的命题可以构成悖论，如果没有否定（例如「这句话是真的」），则不一定构成悖论
    2. 无穷概念：潜无穷与实无穷
        1. 潜无穷将无穷看成一个永无止境的过程，强调其过程性；实无穷将无穷看作是完成了的整体，强调其完成性
        2. 大部分句法悖论源自对潜无穷对象做实无穷把握，例如「所有不以自身尾元素的集合的集合」是一个潜无穷对象，但并非一个实无穷对象
2. $\text{Thomson}$ 证明句法悖论与语义悖论具有统一结构
    1. 对角线定理：设 $S$ 是任一集合，$R$ 是至少在 $S$ 上有定义的任意关系，则 $S$ 中不存在这样的元素，它与且仅与所有那些与其自身没有 $R$ 关系的元素具有 $R$ 关系
        1. 用集合论语言表述为 $\neg \exists y\ (y \in S \wedge \forall x \ (x \in S \to (Ryx \leftrightarrow \neg Rxx)))$
        2. 将集合论语言 $y \in S$ 还原为一阶语言 $S(y)$，该定理转写为 $\neg \exists y\ (S(y) \wedge \forall x \ (S(x) \to (Ryx \leftrightarrow \neg Rxx)))$
    2. 对角线悖论：句法悖论例如 $\text{Russell}$ 悖论、语义悖论例如理发师悖论、$\text{Richard}$ 悖论、$\text{Grelling}$ 悖论
