# 2 三大主义

## 2.1 逻辑主义
### 2.1.1 Frege 与概念文字
1. $\text{Frege}$ 是本体论实在论者与真值实在论者
2. 分析与综合，先验与后验的界定：只有可知的或者可证明的命题可能是分析的或先验的
    1. 如果一个命题是一个不可证明的普遍法则，或者有一个仅依赖于这样的不可证的普遍法则的辩护，则这个命题是先验的；如果一个真无法构造其一个不包含事实依据（即不能被证明，也不是普遍的真）的证明，则这个真是后验的
    2. 如果一个命题是普遍逻辑法则或定义，或者有一个仅依赖于这样的普遍逻辑法则或定义的证明，则这个命题是分析的，否则如果不用到并非普遍逻辑法则而是属于某个普遍学科的真，则这个命题是综合的
3. 算术与实分析是分析的：证明从普遍逻辑法则和定义推导出基础原理，将运用算数解释为对概念和对象的集合的计数
    1. $\text{Hume}$ 原理：对任意概念 $F, G$，$F$ 的数等于 $G$ 的数当且仅当 $F$ 和 $G$ 是等数的
        1. $F$ 的数是指称一个对象的语法形式即是一个「专名」或「单独词项」
        2. 令 $Z$ 为概念「不等于自身」。由于每个对象都等于自身，所以没有对象适合概念 $Z$，定义自然数零为概念 $Z$ 的数
    2. 数的后继关系和归纳原理（$\text{Frege}$ 定理）：存在概念 $F$ 和此概念下对象 $x$，使得概念 $F$ 的数是 $n$ 而概念 $F$ 之下但不等于 $x$ 的数是 $m$。此时 $n$ 是 $m$ 的后继
        1. 定义概念 $T$ 为「等于零」，那么对任意对象 $b$，$T(b)$ 成立当且仅当 $b=0$。定义 $1$ 为概念 $T$ 的数，这个数不预设任何观察到的事实作为其客观的合法性依据，即这个基础的命题是先验且客观的
        2. $n$ 是一个自然数当且仅当「对任意概念 $F$，若 $F$ 对零成立且对每个对象 $d$，从命题 $d$ 在 $F$ 之下可得到 $d$ 的每个后继在  $F$ 之下，那么 $n$ 在 $F$ 之下」
    3. $\text{Caesar}$ 问题：为自然数确定实体。只有能决定任意给定的自然数如何且为何与无论什么对象相同或不同，才能成功将自然数作为对象刻画出来
        1. 自然数：概念 $F$ 的数是「与概念 $F$ 等数」这个概念的外延，即自然数 $n$ 是所有恰好含有 $n$ 个对象的概念的外延
        2. 对 $\text{Frege}$ 来说，外延紧密联结于概念，因此逻辑学有本体论。逻辑对象包括一些必然存在的概念的外延，因此逻辑对象必然存在，逻辑的必然性得以保持
4. $\text{Euclid}$ 几何是先验综合的，几何学有一个特殊的非普遍研究的对象，即空间
5. $\text{Russell}$ 悖论：基本法则是不一致的
    1. 基本法则五：对任意概念 $F, G$，$F$ 的外延等于 $G$ 的外延当且仅当对任意对象 $a$，$F(a)$ 当且仅当 $F(b)$
    2. 不一致性：令 $R$ 为「存在概念 $F$，使 $x$ 使 $F$ 的外延且 $F(x)$ 为假」下对 $x$ 成立的概念，令 $r$ 为 $R$ 的外延，则 $R(r)$ 为真当且仅当 $R(r)$ 为假

### 2.1.2 Russell 与类型论
1. 非直谓（定义设计包含被定义实体的集合）的定义是非法的，例如「最小上界」
    1. 在任何情况下设想一个类是或不是自己的一个成员是无意义的，因此不可能有包含宇宙中所有类的全类
    2. 类型论：将宇宙划分为不同部分，将个体定义为不是类的对象。个体属于类型 $0$，个体组成的类属于类型 $1$，个体类的类属于类型 $2$，以此类推
2. 利用类简化 $\text{Frege}$ 的定义
    1. 自然数：对任意类 $C$，定义 $C$ 的数为由所有与 $C$ 等数的类组成的类
    2. 后继：一个类 $a$ 的数的后继是包含 $a$ 以及任何一个不属于 $a$ 的个体 $x$ 的类的数
3. 利用无穷公理与可化归公理可建立 $\text{Peano}$ 算术公理
    1. 无穷公理：存在无穷多的个体，否则必须假设足够多个体存在
    2. 可划归公理：在每个类型中，对每个类 $C$，存在一直谓类 $C'$ 与 $C$ 有相同成员。其允许逻辑学家忽略分层谱系而继续工作
4. 类型论把握了除集合论外纯粹数学的几乎每一个分支
    1. 整数：$+m$ 为自然数上对任意 $n$，$n+m$ 到 $n$ 为二元关系。因此 $+m$ 无法与 $m$ 等同
    2. 有理数：定义分数 $\dfrac{m}{n}$ 为当 $xn=ym$ 时，$x, y$ 两数所具有的关系
    3. 实数：遵循 $\text{Dedekind}$ 分割，即一个联结的，有界的，无最大元有理数的类。定义一个分割为一个非空的有理数类 $C$ 并满足
        1. 对所有有理数 $x, y$，如果 $x$ 属于 $C$ 且 $y<x$，则 $y$ 属于 $C$
        2. 存在有理数 $z$ 满足对每个有理数 $x$，如果 $x$ 属于 $C$，则 $x<z$
        3. 对每个有理数 $x$，如果 $x$ 属于 $C$，则存在有理数 $y$ 属于 $C$，且 $x<y$

            !!! note "选择公理"

                实分析需要选择公理：对任意由非空且两两不相交的类组成的集合 $c$，至少存在一个类正好含有 $c$ 中每个成员中的各一个成员

    4. 复数：一个实数的有序对

5. $\text{Russell}$ 指出如何和将任意一个关于类的陈述改为一个关于概念和性质的复杂陈述，最终达到「无类」的理论
    1. $\text{Russell}$ 的数都是类，是逻辑虚构，因此不是世界最终构成物的部分
    2. $\text{Russell}$ 背离了 $\text{Frege}$ 在本体论上的实在论立场

### 2.1.3 逻辑实证主义
1. 语义学传统：即语言学转向
    1. 将必然性和先验只是的来源定位于语言的使用中
    2. 必然的真是由定义而真，先验只是是语言使用的知识

        !!! note "$\text{Frege}$ 与语言转向"

            $\text{Frege}$ 不认为所有必然的真都是由定义的真。对 $\text{Frege}$ 而言，几何的真是综合的，先验的，因此并非由定义而真。分析的真是从普遍的逻辑法则和一些定义推导出的，分析真的地位取决于普遍逻辑法则的本质

2. 语言框架：形式地描绘一段话语的尝试，其应该包含一套精确的句法，以指示哪些表达式在该框架中是合法的语句
    1. 内部问题：关于框架中某个特定的新种类的实体之存在的问题
        1. 内部问题及其可能的回答利用新的表达式形式而被公式化，这些回答可以通过纯逻辑方法或经验的方法找到，取决于框架是逻辑的抑或是事实的
        2. 在数框架下，数的存在是那些规则和定义的全然平凡的推论
    2. 外部问题：将这些实体的系统作为整体来考虑其存在或实在性的问题
        1. 实在性的外部问题是无意义的，外部问题在需要仔细检查上是一个有问题的特征
        2. 最接近合法的问题是采纳一个给定的框架的可行性，这是实用主义的选择
    3. 宽容原则：容忍不同的语言形式，允许在特定研究领域的人自由使用任何看起来对其有用的表达形式
3. 数学的真是先验的，每个事实性的问题必定最终由经验决定，所以数学的真没有事实性的内容
    1. 逻辑实证主义排除先验可知的综合命题的可能性
    2. 分析命题没有任何关于经验的情况的信息，但是通过说明运用特定符号的方式启发了人们
    3. 逻辑实证主义本身陈述破坏了观点基础，即命题「每个有意义的陈述或者是分析的，或者是通过经验可证实的」不是分析的

### 2.1.4 新逻辑主义
1. 新逻辑主义
    1. 数学真的重要核心是先验可知的，通过那些分析的或意义构成的规则推导而来
    2. 这样的数学是一个关于对象的理想王国，客观且在某种意义上独立于心灵
2. 方案：绕过 $\text{Frege}$ 对外延的处理，直接在 $\text{Hume}$ 原理上工作
    1. 二阶逻辑的公理和规则在必要的意义上是否是分析的或意义构成的，抑或是没有实质上的认识论预设的
    2. 仅应用自然数和基本算数，需要扩展这种处理方式以覆盖其他数学领域，寻找足够丰富的抽象原理来刻画更有力的数学理论

## 2.2 形式主义

1. 词项形式主义：将数学看作是关于字符和符号的形式系统，即数学在语言学对象上是关于「类型」的
    1. 个例与类型：个例是由墨水，碳粉等构成的物理对象。类型是个例的抽象形式，个例是类型的实例
    2. 类型不同于数，它们有直接的实例，人们通过个例认识类型
    3. 词项形式主义无法将所有实数与名字等同，也无法理解数学命题
2. 游戏形式主义：数学的内容是其语言的操作规则。数学符号是无意义的，或者有与数学实践无关的意义；数学公式和语句不表示关于任何研究对象的真假命题
    1. 数学对象不妨是不存在的，数学知识是关于游戏规则的知识，或者是关于按照这些规则做了某个动作的知识
    2. 数学表达式的意义对于数学自身是外在的，对于数学工作有关系的只是那些被遵守的规则，意义仅仅是启发式的。类似于工具注意科学哲学，它被设计为用来减轻关于为被观察到的理论实体的担忧
    3. $\text{Frege}$ 的的形式系统促成了游戏形式主义的精致版本

### 2.2.1 演绎主义
1. 数学理论的公理是任意约定的，推理的规则必须保真为真，数学实践由未经解释的公理的逻辑推论构成
    1. 区分逻辑词项（如「并且」「存在」「如果……那么……」）和非逻辑词项（如「数」「集合」「线」）。逻辑词项按照其一般意义理解，非逻辑词项不予解释

        !!! note "隐定义"
            $\text{Hilbert}$ 为「点」「线」等出现在公理中未解释的词项提供隐定义或功能定义，这些是通过几个项之间彼此的关系同时特征化它们

            $\text{Frege}$ 并不采纳这种观念，因为如果在所提议的公理中的词项事先没有意义，那么这些陈述没有真值，因而它们不能是公理；如果它们事先已具有意义，那么这些公理就不能是定义

    3. $\Phi$ 是算术的一条定理，其内容是 $\Phi$ 从算术公理推得
    4. 直观和观察的角色被明确限定为动机并且是启发式的

2. 演绎主义者的哲学立场
    1. 数学是关于什么的：什么都不是或者可以被当作是什么都不关于
    2. 什么是数学知识：从什么推出什么的知识，数学的知识就是逻辑的知识
    3. 怎么应用一个数学分支：通过发现使它的公理为真的解释
3. 元数学：形式语言和演绎系统被公式化得足够清楚和严格，以至于它们子集可以被作为数学对象来研究
    1. 元数学的对象是数学系统，目标是阐明形式语言和公理化的研究对象，是演绎主义的例外
    2. 一个公理集的一致性足以使其构成数学的一个合法分支，一致性是数学家所需要的全部「真」和「存在」

### 2.2.2 有穷主义
1. 有穷元算术：有意义，有研究对象（包括逻辑演绎在内所有思维的前提）的判断，一般被认为对应「原始递归算术」
    1. 将只包含有穷量词的语句看作有穷元的：量词的变元被限制在有穷多的自然数，例如 $\exists P \ (P<101! \wedge P$ 是质数$)$
    2. 对于每一个例证都是真的语句，可以引入字母概括，这样的概括也是有穷元的，例如 $1+a=a+1$。这样的语句是「不能否定的」，因为概括陈述的否定会断言存在一个例证使得其是假的，这个断言含有一个无界量词，因而不是有穷元的
2. 算术的内容：关于自然数，具体的符号本身，其结构是清晰可识别的
    1. 理想数学：无界量词关于自然数或字符的陈述
    2. 令 $\Phi$ 为任意有穷元陈述，除非 $\Phi$ 可以被判定为真，否则不能在 $T$ 中导出 $\Phi$ 的对应公式
    3. 如果形式系统 $T$ 是一致的，这一陈述本身是有穷元的，即「$a$ 不是 $T$ 中的一个推理，其最后一行是 $0\neq 0$」
3. $\text{Hilbert}$ 计划：前三项是各数学分支的形式化，已经完成
    1. 枚举所有数学和逻辑中用到的符号
    2. 明确特征化这些符号的所有表示经典数学中被归为「有意义」的陈述的组合，这些组合被称为「公式」
    3. 提供一种构造算法，使得能够成功构造所有对应于经典数学中「可证」陈述的公式，这种程序相应地被称为证明
    4. 以有穷元的方式证明那些对应于经典数学陈述的公式可以由前述算法证明，当且仅当对其所对应陈述的检查显示它是真的
4. 不完全性：令 $T$ 为一个包含一定量算术的形式演绎系统，假设 $T$ 的句法是能行的
    1. 能行性：存在一种算法判定一组给定的字符序列是否是一个 $T$ 中的合法解释，且存在一种算法判定一组给定的公式序列是否是一个 $T$ 中合法的演绎
    2. $\text{G}\ddot{\mathrm o}\text{del}$ 不完备定理
        1. 第一不完全性对所有需要单个形式系统以导出所有算术真的数学哲学提出质疑
        2. 形式系统的一致性不能通过弱于该系统自身得到证明，因此要证明经典数论的一致性，则必须超越 $\text{Hilbert}$ 意义上的有穷元数学框架，不能只是使用记号组合的组合性质
        3. 为 $\text{Hilbert}$ 计划的辩护方式：第二不完全性中对一致性的公式化还存在其他方法表示一致性性质；证明或声明有穷元算术的方法不能在 $\mathrm{PA}$ 或其他任何形式理论被完全把握，即有穷元算术是天生非形式的

### 2.2.3 Curry
1. 形式主义没有额外的形而上学假设
    1. 随着一门数学分支的发展，其方法论会变得越来越严格，这种形式化的进程是数学的本质
    2. 其他的数学哲学是含糊的，一个成熟的数学理论论断不应该被解释为某一特定的演绎系统，而应该是关于一个形式系统的论断；数学的中心概念是关于形式系统的
2. 原数学不应被限于有穷元算术
    1. 不将自己限于初等命题的推理，而是将系统作为材料，用任何掌握的方法来研究它。虽然某种直观被牵涉这种原数学中，但是这种直观的形而上学本性是无关紧要的
    2. 元数学本身是数学的分支，也应被形式化。将问题的解释为关于那个形式系统的定义，假设这样不会形成一个恶性无穷倒退
3. 不存在真正关于一个给定形式系统的真问题，只存在关于「引导人们对某个形式系统感兴趣而非另一个的考虑」的问题
    1. 可接受性的标准：前提的直观自明性；一致性；理论整体的实用性
    2. $\text{Curry}$ 不要求一个一致性的证明：一个一致性证明带给人们关于系统的知识，但是不改变其实用性。即使不一致性被发现，这不意味着理论被完全抛弃，而意味着其修改和提炼

## 2.3 直觉主义
### 2.3.1 Brouwer
1. $\text{Brouwer}$ 是本体论反实在论者与真值反实在论者，认为数学是依据心灵的，是关于人类思维的的一个特殊方面

    !!! note "直觉主义与其他学派"
        $\text{Brouwer}$ 认为，逻辑主义和形式主义都专注于数学交流这一外部的附属物（语言和逻辑），而完全忽视了数学的本质。 
        同时他明确反对关于一致性证明的考虑，因为这不会导致人类关系之间的误解的、实践的确定性这样的担保而感到该数学理论的确实性是有保证的

2. $\text{Noneuclidean}$ 几何的出现与被接受是对 $\text{Kant}$ 观点（几何学是关于知觉的先验综合形式）的打击
    1. 无法再坚持认为经验的空间具有 $\text{Euclid}$ 的性质，甚至寻求一种对于经验空间为真的几何也没有意义
    2. $\text{Brouwer}$ 抛弃 $\text{Kant}$ 的空间观，主张将所有的数学建立在 $\text{Kant}$ 式的时间观上
        1. 二一性：将世界领会为一系列截然区分的时刻，每个时刻引起另一个时刻
        2. 将自然数建立在时间知觉的形式上，这种原始的直觉使得连续的和离散的东西统一起来，并立即引起了线性的，连续统的直觉，从而引出有理数和实数，产生算术和实分析
        3. 通过将点定义为数对，而将几何建立在实数之上，这使得普通平面，多维几何和 $\text{Noneuclidean}$ 几何成为先验综合的，最终几何学也基于时间的直觉
    3. 数学的本质是理想化的精神构造
3. 没有相信排中律普遍成立的先验理由，经典实分析可能是适于科学的，但是比直觉主义分析具有更少的数学真，经典数学相信不可知真的存在性
    1. 双重否定消去是无效的：$\neg\neg p \to p$
    2. 存在即被构造：$\exists x \ (x\in \mathbf N \wedge P(x))$ 只有当证明了如何构造一个具有性质 $P$ 的自然数 $x$，命题才能被确立
    3. 否定实无穷的存在
        1. 反对将数学实体的集合当作似乎已经完成的全体，只有完成对集合中任意一个的所有元素的构造，才能使用此集合
        2. 实数等同于由一个规则给出的小数扩张（潜无穷）或一个创造主体的自由选择序列。因此，任何一个关于一个给定实数的定理必须归自于该实数的有穷多的信息
        3. 选择公理在直觉主义分析中为假
4. 直觉主义数学与经典数学不相容：存在不能被嵌入任何经典逻辑框架的直觉主义的结构，也存在不能对应于任何经典逻辑框架的直觉主义的结构

    !!! note "构造主义"
        构造主义是既不接受排中律，也不接受直觉主义分析的非经典部分的学派

### 2.3.2 Heyting
1. $\text{Heyting}$ 谓词演算：$\text{Heyting}$ 发展的一套严格的直觉主义逻辑的形式化系统
    1. 从经典逻辑背后的形而上学假设（真值实在论）来看，经典数学的语言应被理解为客观的真之条件
    2. $\text{Heyting}$ 同意 $\text{Brouwer}$ 关于宣扬精神构造而贬低语言和逻辑的观点：形式系统自身是一个合法的数学构造，但是人们永远不能保证形式系统完整地表达了任何数学思想的领域
2. 数学是依赖心灵的
    1. 经典数学依赖于「数学对象独立于人们而存在，并且数学真是客观的和永恒的」的形而上学原理
    2. 数学事件不应该依赖于形而上学：如果「存在」的意思不是被构造，那么其必须有其他的形而上学意义。在对精神的数学构造的学习中，存在必须与「被构造」同义

        !!! note "形而上学"
            $\text{Curry}$ 的形式主义同样主张无需形而上学假设，避免形而上学似乎是数学哲学的共同前提。 
            但是在数学哲学中，形而上学是无法回避的（例如 $\text{Brouwer}$ 的 $\text{Kant}$ 式立场并非形而上中立），尽管形而上学和数学实践的关系可以被质疑

### 2.3.3 Dummett
1. $\text{Dummett}$ 研究数学的主要路径从一开始就是语言学的
    1. 任何关于哪种逻辑正确的考虑必须最终取决于意义的问题
    2. 逻辑词项：从一系列前提做出推论的规则源于前提中一些词项的意义，即逻辑推理是分析的或意义构成的
    3. 任何人要理解一个表达式的意义，必须能通过人的行为（此人对该表达式的使用）来证明其理解，理解不应该是不可说的
        1. 数学陈述的意义决定了其使用且完全被其使用决定
        2. 数学陈述的意义不可能是或不可能作为对其使用中显示出来的而是只存在于领会于那个意义的个人的心中的任何东西
2. 意义就是被使用：对「使用」的阐述使通过考虑意义来修正逻辑和数学实践的意图变得荒谬
    1. 形式主义的反修正主义：正确的数学事件可以被编入形式演绎系统
    2. 语义学整体论的反修正主义：追问任何单个陈述的内容都是不合法的，每个陈述的意义都由其与语言中其他区域的其他陈述之间的多种连接形成的整体所修饰，因而不知道整个语言就没有足够理解那些陈述的方法
3. 可证实性或可断言性应该取代真作为成分语义学的主要元素，即提供每个公式证明的条件，而不是给出真的条件
    1. 典型的语义学（$\text{Tarski}$ 语义）是组合的，即一个符合陈述的语义内容通过分析它的各部分的语义内容而得到
    2. 分子语义学：单个语句所承载的属于它的内容对应于它被从它本身的各组成元素符合起来的方式，独立于语言中其他不涉及这些组成元素的语句
    3. 已经确立了的实践是可以批判的，分别引入否定和析取算子并没有证明当这些连接符复合起来时排中律的合法性
    4. 全局语义反实在论：至少在理论上，所有真都是可知的。而经典数学的主要预设是存在或可能存在不能被认识的真
4. 无限可扩展：不能描绘出该概念可应用其上的对象的范围
    1. 不完备定理证明来的算术真的概念的无限可扩展的，进一步，任何实质的数学领域都是无限可扩展的
    2. 令 $d$ 为一个领域，量词 $\forall d$ 是融贯的，无论 $d$ 是否可无限可扩展
