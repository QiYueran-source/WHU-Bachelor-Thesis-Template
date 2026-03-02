::: cnabstract
关键词1；关键词2；关键词3

请使用中文分号"；"分割关键词！

摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容摘要内容
:::

::: enabstract
Key1; Key2; Key3

Please use English semicolon and space to separate key words.

This is abstract. This is abstract. This is abstract. This is abstract.
This is abstract. This is abstract. This is abstract. This is abstract.
This is abstract. This is abstract. This is abstract. This is abstract.
This is abstract. This is abstract. This is abstract. This is abstract.
This is abstract. This is abstract. This is abstract.
:::

# 引言

金融市场是一个具有动态演化特征的复杂协调系统。
其中，金融产品价格形成于个体在不确定性情境下做出的决策[@henning2025llm]。
长期以来，中国的股票市场以散户投资者为主，贡献了超80%的市场交易量[@jones2025retail]。
散户投资者对于证券的基本信息理解有限，导致形成预期偏差，对市场波动产生显著的影响[@yang2020anchor]。
具体来说，散户投资者获取和分析信息的能力有限，也无法完全准确地理解信息的含义；
此外，行为金融的研究表明，散户投资者易受情绪影响，形成行为偏差，例如羊群效应、过度自信等。
然而，降低投资者的预期偏差，提高预期协同度，
能否使金融产品的定价过程趋于理性，从而降低市场波动，这一课题仍然存在争议[@shiller1981stock][@xue2020information]。
无论在现有的大量研究中[@wu2015why]，还是党的会议上，都强调了引导市场预期、维护资本市场预期稳定的重要性。
因此，探究投资者的预期协同度对于资产定价的影响，对于维护资本市场预期稳定具有重要的理论价值与现实意义。

近年来，机器学习方法在经济、金融、管理等领域受到的重视程度日益提高[@hong2021how]。
在资产定价领域，因子分析法[@sharpe1964capital][@fama1992cross]自诞生以来，被广泛应用于资产定价研究。
而机器学习方式，以其数据驱动的特性和强大的非线性拟合能力，逐渐成为资产定价研究的热点。
Gu, Kelly,
Xiu等学者[@gu2020machine]通过对比包括随机森林、梯度提升树、感知机在内的14种机器学习方法，
发现机器学习在挖掘高维公司特征的非线性关系方面具有显著优势，解释力远强于传统因子模型。
在国内，李斌等学者[@li2019machine]基于A股因子，对比了神经网络、支持向量机等模型在A股收益预测中的表现，
发现机器学习能够有效捕捉A股"壳价值""政策敏感性特征"等特殊定价因素。
马甜等学者[@ma2022deep]将生成式对抗网络引入A股因子构建，缓解了因子的稀疏性问题，
构建的深度学习复合因子A股市场的表现由于传统因子。
因子是对公司信息的提取和抽象，而机器学习通过对于因子的非线性拟合，
可以模拟投资者对于公司信息的非线性处理过程，从而更准确地预测资产价格。

人工智能技术的发展为金融研究提供了新的视角和工具。
Minsky在1961年首次提出了"Agent"的概念[@minsky1961steps]，
将Agent定义为能够通过协商协作解决问题的智能个体"，强调其社会交互性、自主性两大核心特性。
相比于传统机器学习用于预测、分类等任务，Agent可以直接模拟投资者"端到端"的决策过程，
即收集信息、解读信息、决策、执行、反馈的完整过程[@turgut2023framework]。
自2015年来，Agent-Based金融研究数量迅速增加，覆盖了股票价格预测、投资组合管理、风险管理等多个领域[@ahmed2022artificial]。
使用AI-Agent模拟投资者决策过程，可以更准确地模拟投资者的决策过程，对于投资者预期协同度的研究具有重要的理论价值与现实意义。

# 文献综述

## 公式的使用

在文中引用公式可以这么写：$a^2+b^2=c^2$这是勾股定理，他还可以表示为$c=\sqrt{a^2+b^2}$，还可以让公式单独一段并且加上编号。注意，公式前请不要空行。
$$\begin{equation}
\sin^2{\theta}+\cos^2{\theta}=1 \label{eq:pingfanghe}
\end{equation}$$

还可以通过添加标签在正文中引用公式，如式[\[eq:pingfanghe\]](#eq:pingfanghe){reference-type="eqref"
reference="eq:pingfanghe"}。

我们还可以轻松打出一个漂亮的矩阵： $$\begin{equation}
  \mathbf{A}=
  \left[\begin{matrix}
    1&2&3&4\\
    11&22&33&44\\
  \end{matrix}\right] \times
  \left[\begin{matrix}
    22&24\\
    32&34\\
    42&44\\
    52&54\\
  \end{matrix}\right]
\end{equation}$$

或者多行对齐的公式： $$\begin{equation}
  \begin{aligned}
    f_1(x)&=(x+y)^2\\
          &=x^2+2xy+y^2
  \end{aligned}
\end{equation}$$

## 插图的使用

LaTeX环境下可以使用常见的图片格式：JPEG、PNG、PDF、EPS等。当然也可以使用LaTeX直接绘制矢量图形，可以参考pgf/tikz等包中的相关内容。需要注意的是，无论采用什么方式绘制图形，首先考虑的是图片的清晰程度以及图片的可理解性，过于不清晰的图片将可能会浪费很多时间。

图示例如下：

<figure id="fig:whu" data-latex-placement="!htb">
<p><embed src="figures/whulogo.pdf" style="width:30.0%" /><br />
</p>
<figcaption>插图示例</figcaption>
</figure>

`[htbp]`选项分别是此处、页顶、页底、独立一页。`[width=\textwidth]`让图片占满整行，或`[width=2cm]`直接设置宽度。可以随时在文中进行引用，如图 [2.1](#fig:whu){reference-type="ref"
reference="fig:whu"}，建议缩放时保持图像的宽高比不变。

## 表格的使用

表格的输入可能会比较麻烦，可以使用在线的工具，如 [Tables
Generator](https://www.tablesgenerator.com/) 能便捷的创建表格，也可以使用离线的工具，如 [Excel2LaTeX](https://ctan.org/pkg/excel2latex) 支持从Excel表格转换成LaTeX表格。[LaTeX/Tables](https://en.wikibooks.org/wiki/LaTeX/Tables) 上及 [Tables
in
LaTeX](https://www.tug.org/pracjourn/2007-1/mori/mori.pdf) 也有更多的示例能够参考。

### 普通表格

下面是一些普通表格的示例：

::: {#tab:1}
  我是    一只    普通
  ------ ------ ------
  的      表格      呀

  : 简单表格
:::

::: {#tab:2}
   姓名   学号   性别
  ------ ------ ------
   张三   001     男
   李四   002     女

  : 一般三线表
:::

### 跨页表格

跨页表格常用于附录（把正文懒得放下的实验数据统统放在附录的表中），以下是一个跨页表格的示例：

+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+:========:+:========:+:========:+:========:+:========:+:========:+:========:+:========:+:========:+
| 接上一页 |          |          |          |          |          |          |          |          |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
|          |          |          |          |          |          |          |          |          |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 转下一页                                                                                         |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+
| 1        | 0        | 5        | 1        | 2        | 3        | 4        | 5        | 6        |
+----------+----------+----------+----------+----------+----------+----------+----------+----------+

: 跨页表格示例

### 统计表格

要创建占满整个文字宽度的表格需要使用到tabularx，如不需要，使用tabular就行。引用表格与其它引用一样，只需要：表 [\[tab:3\]](#tab:3){reference-type="ref"
reference="tab:3"}，统计表格一般是三线表形式。

::: tabularx
CCCC 序号&年龄&身高&体重\
&14&156&42\
2&16&158&45\
3&14&162&48\
4&15&163&50\
平均&15&159.75&46.25\
:::

## 列表的使用

下面演示了创建有序及无序列表，如需其它样式，[LaTeX
Lists](https://www.latex-tutorial.com/tutorials/lists/) 上有更多的示例。

### 有序列表

这是一个计数的列表

1.  第一项

    1.  第一项中的第一项

    2.  第一项中的第二项

2.  第二项

    1.  第一项中的第一项

    2.  第一项中的第二项

3.  第三项

### 不计数列表

这是一个不计数的列表

- 第一项

  - 第一项中的第一项

  - 第一项中的第二项

- 第二项

- 第三项

## 定理的使用

::: theorem
设向量$\boldsymbol a\neq\boldsymbol 0$，那么向量$\boldsymbol b//\boldsymbol a$的充分必要条件是：存在唯一的实数$\lambda$，使$\boldsymbol b=\lambda \boldsymbol a$。
:::

::: definition
这是一条定义。
:::

::: lemma
这是一条引理。
:::

::: corollary
对数轴上任意一点$P$，轴上有向线段$\vec {OP}$都可唯一地表示为点$P$的坐标与轴上单位向量$\boldsymbol e_u$的乘积：$\vec {OP}=u \boldsymbol e_u$。
:::

::: proposition
这是一条性质。
:::

::: example
这是一条例。
:::

::: remark
这是一条注。
:::

# 研究设计

## 模型设计

对于一个Agent投资者，其决策和学习的过程可以分为以下几个步骤：

::: algorithm
特征数据 $\xrightarrow{\text{神经网络}}$ 投资决策 [^1]
投资决策、收益数据 $\to$ 组合收益 组合收益序列 $\to$
组合表现指标（如波动率、夏普比率、最大回撤等） 组合表现指标 $\to$ 奖励
奖励 $\to$ 更新后的神经网络
重复上述步骤，直到达到预设的训练次数或达到预设的训练时间。
:::

根据上述步骤，可以设计一个Agent投资者的决策和学习过程。

### Agent构建与训练

#### 数据输入

使用因子数据作为Agent投资者的输入，用于模拟投资者对于因子的解读和决策。
因子数据是以年月-证券为主键的月度面板数据。记原始的因子数据为$raw\_factors_{a,s,t,i}$，
表示$Agent_{a}$在$t$月份对于证券$s$的因子$i$的原始值。

由于不同特征的量纲、数量级、分布等方面存在明显差异，因此需要对特征进行标准化处理，
使得所有特征的均值为0，标准差为1。
具体来说，记$N$为参与该月标准化的证券数量（如股票池大小）。对于每一个因子$factor_{a,s,t,i}$，求相同月份所有证券的因子值的均值和标准差：

$$raw\_\mu_{t,i} = \frac{1}{N} \sum_{s=1}^{N} raw\_factors_{a,s,t,i}$$

$$raw\_\sigma_{t,i} = \sqrt{\frac{1}{N} \sum_{s=1}^{N} (raw\_factors_{a,s,t,i} - raw\_\mu_{t,i})^2}$$

然后对每一个因子进行标准化处理，得到标准化后的因子值：

$$factor_{a,s,t,i} = \frac{raw\_factors_{a,s,t,i} - raw\_\mu_{t,i}}{raw\_\sigma_{t,i}}$$

参考FinRL[@liu2021finrl]的设计， 设定一个因子向量为：

$$\vec{factors}_{a,s,t} = (factor_{a,s,t,1}, factor_{a,s,t,2}, \ldots, factor_{a,s,t,i}, \ldots)^T$$

考虑到不同的Agent投资者的数据获取能力不同，对数据的关注程度也不同，
因此，参考机器学习中的特征选择方法[@breiman2001random]，
设定Agent$a$只能随机获取88个因子中的$l$个因子，用于分析决策。
筛选后的因子向量为：

$$\vec{selected\_factors}_{a,s,t} = (factor_{a,s,t,random_1}, factor_{a,s,t,random_2}, \ldots, factor_{a,s,t,random_i}, \ldots)$$

其中$random_i$为随机选择的因子索引，不同的Agent投资者选择的因子索引不同。

设定Agent拥有一定的数据回顾能力，可以回顾过去$m$个月的因子向量。
在月份$t$，Agent可以回顾过去$m$个月的因子向量，形成一个$(m, l)$的矩阵，记作：

$$\mathbf{factors\_matrix}_{a,s,t} = (\vec{factors}_{a,s,t}, \vec{factors}_{a,s,t-1}, \ldots, \vec{factors}_{a,s,t-m+1})$$

$Agent_{a}$需要选择$n$只证券，构建一个投资组合，记作：

$$\vec{portfolio} = (s_1, s_2, \ldots, s_n)$$

将多个证券的因子矩阵拼接，可以得到一个三维张量，记作：

$$\mathbf{factors\_tensor}_{a,\vec{portfolio},t} = \begin{pmatrix} 
\mathbf{factors\_matrix}_{a,s_1,t} \\ 
\mathbf{factors\_matrix}_{a,s_2,t} \\ 
\vdots \\ 
\mathbf{factors\_matrix}_{a,s_n,t} 
\end{pmatrix}$$

其维度为$(n, m, l)$。

最后，Agent可以回顾自己之前投资组合的收益情况，对于投资组合$\vec{portfolio}$，
获取其$t,t-1,t-2,\ldots,t-m+1$月的收益，组成收益序列，记作：

$$\vec{returns}_{a,portfolio,t} = (return_{a,portfolio,t-m+1}, return_{a,portfolio,t-m+2}, \ldots, return_{a,portfolio,t})$$

其中，$return_{a,portfolio,t}$为使用$t-1$月的决策构建投资组合$\vec{portfolio}$在$t$月份的收益。
其计算方式为各个证券在$t-1$月的决策水平其在$t$月份的收益水平的加权平均。
该收益序列与具体证券无关，为组合整体收益。为与按证券组织的输入一致，将该收益序列复制$n$份，
得到形状为$(n,m)$的矩阵（每行均为同一$m$维收益序列），记作：

$$\mathbf{returns\_matrix}_{a,\vec{portfolio},t} = \begin{pmatrix} 
  return_{a,portfolio,t-m+1} & return_{a,portfolio,t-m+2} & \ldots & return_{a,portfolio,t} \\
  return_{a,portfolio,t-m+1} & return_{a,portfolio,t-m+2} & \ldots & return_{a,portfolio,t} \\
  \vdots & \vdots & \vdots & \vdots \\
  return_{a,portfolio,t-m+1} & return_{a,portfolio,t-m+2} & \ldots & return_{a,portfolio,t} 
\end{pmatrix}$$

再将该矩阵在特征维上扩展为形状为$(n,m,1)$的三维张量，并与原有$(n, m, l)$张量在特征维上拼接，得到最终输入张量，其维度为$(n, m, l+1)$，记作：

$$\mathbf{X}_{a,\vec{portfolio},t} = \begin{pmatrix} 
  \mathbf{factors\_matrix}_{a,s_1,t} \\ 
  \mathbf{factors\_matrix}_{a,s_2,t} \\ 
  \vdots \\ 
  \mathbf{factors\_matrix}_{a,s_n,t} \\ 
  \mathbf{returns\_matrix}_{a,\vec{portfolio},t} 
\end{pmatrix}$$

#### 神经网络设计

与预测模型不同，Agent的神经网络采用端到端设计，
无需预测组合未来的收益，而是直接进行决策，决定将多少比例的资金分配给每只证券（现金）。

**（1）数据输入层。**
参考FinRL[@liu2021finrl]，采用多层感知机（MLP）作为Agent由观测到投资权重的映射模型。
输入为前述的观测张量$\mathbf{X}_{a,\vec{portfolio},t}$，形状为$(n, m, l+1)$。

**（2）展平与线性层。** 将输入张量展平为一维向量，记作：

$$\mathbf{x} = \mathrm{Flatten}(\mathbf{X}_{a,\vec{portfolio},t}) \quad x \in \mathbb{R}^{n m (l+1)}$$

经过Dropout层后，得到：

$$\mathbf{x}' = \mathrm{Dropout}(\mathbf{x}) \quad x' \in \mathbb{R}^{n m (l+1)}$$

然后通过一层全连接层映射为$n+1$维向量，记作：

$$\mathbf{z} = \mathbf{W} \,\mathbf{x}' + \mathbf{b} \quad \mathbf{W} \in \mathbb{R}^{(n+1) \times nm(l+1)},\ \mathbf{b} \in \mathbb{R}^{n+1},$$

得到$\mathbf{z} \in \mathbb{R}^{n+1}$，对应$n$只证券的权重及一个现金（无风险资产）维度。

**（3）激活函数。**
使用Tanh函数作为激活函数，将输出映射到$(-1, 1)$之间。

$$\tanh(x) = \frac{e^x - e^{-x}}{e^x + e^{-x}}$$

经过Tanh函数激活后，得到模型输出，记作：

$$\mathbf{o}_{a,\vec{portfolio},t} = \tanh(\mathbf{z}) \quad \mathbf{o}_{a,\vec{portfolio},t} \in \mathbb{R}^{n+1}$$

使用Tanh作为激活函数，可以保留负权重，用于后续研究中放松对于杠杆和做空的限制。

**（4）输出归一化。**
按照决策的语义，Agent的决策（行动）可以表示为一个和为1的向量，记作：

$$\vec{action}_{a,\vec{portfolio},t} = (w_1, w_2, \ldots, w_{n+1}) \in \mathbb{R}^{n+1}$$

其中，$w_i$表示分配给证券（现金）$i$的比例。
设定最后一个权重$w_{n+1}$为现金权重，表示分配给无风险资产（现金）的比例。

在基线回归中，设定不允许使用杠杆或者做空。
因此，将$\mathbf{o}_{a,\vec{portfolio},t}$转换为决策向量$\vec{action}_{a,\vec{portfolio},t}$，需要满足以下约束：

**1)**
权重之和为1，即$\sum_{i=1}^{n+1} w_i = 1$，表示需要将全部资金用完，无用的资金需要分配给无风险资产（现金）；

**2)**
非负，即$w_i \geqslant 0$，表示不允许做空证券，或者使用杠杆（即现金权重为负，表示借入资金购买证券）；

将$\mathbf{o}_{a,\vec{portfolio},t}$记作：
$$\mathbf{o}_{a,\vec{portfolio},t} = (o_1, o_2, \ldots, o_{n+1})$$

为了满足非负性约束，将$\mathbf{o}_{a,\vec{portfolio},t}$中的负权重部分截断为0，得到：

$$o^+_{i} = \max(o_i, 0)$$

$$\mathbf{o^+_{a,\vec{portfolio},t}} = (o^+_{1}, o^+_{2}, \ldots, o^+_{n+1})$$

然后进行简单归一化，得到归一化后的决策向量，记作：

$$\vec{action}_{a,\vec{portfolio},t} = \left( \frac{o^+_{1}}{\sum_{i=1}^{n+1} o^+_{i}}, \ldots, \frac{o^+_{n+1}}{\sum_{i=1}^{n+1} o^+_{i}} \right)$$

#### 奖励设计

在强化学习中，奖励函数是Agent用于评估其决策好坏，改进决策方向，实现模型优化的关键。
参考Moody等[@moody1998performance]和jiang等[@jiang2017deep]的研究，
使用二次效用函数[@markowitz1956optimization]作为奖励函数。

具体来说，对于一个投资组合$\vec{portfolio}$，其在$t$月份的收益率为$return_{portfolio,t}$，
其计算方式为各个证券在$t-1$月的决策水平其在$t$月份的收益水平的加权平均。

$$return_{portfolio,t} = \vec{action}_{a,\vec{portfolio},t} \cdot \vec{returns}_{portfolio,t}$$

获取其前$m$个月的收益序列

$$\vec{returns}_{portfolio,t} = (return_{portfolio,t-m+1}, return_{portfolio,t-m+2}, \ldots, return_{portfolio,t})$$

计算其方差

$$\sigma_{portfolio,t}^2 = \frac{1}{m} \sum_{i=1}^{m} (r_{portfolio,t-i} - \bar{r_{portfolio,t}})^2$$

其中，$\bar{r_{portfolio,t}}$为前$m$个月的收益率均值。

使用二次效用函数作为奖励函数

$$reward_{a,portfolio,t} = \mu_{portfolio,t} - \frac{A}{2} \sigma_{portfolio,t}^2$$

其中，参数$A$是风险厌恶系数。
$A$越大，表明Agent越厌恶风险，越倾向于选择低风险的组合。
根据尹海员等[@yin2011speciality]、张玥[@zhang2019china]、jiang[@jiang2023dynamic]等学者的研究，
在A股市场中，投资者的风险系数的取值范围在$[2,8]$之间，具有厚尾、右偏的分布特征。因此，使用对数正态分布采样Agent的风险厌恶系数。

$$\ln(A) \sim N(\mu, \sigma^2)$$

#### 强化学习模型设计

## AED因子设计

## 因子检验

# 其它格式

## 代码

### 原始代码

朴实的代码块：

使用verbatim可以得到原样的输出，如下：

        print("Hello world!")

使用[listings](https://en.wikibooks.org/wiki/LaTeX/Source_Code_Listings)环境可以对代码进行进一步的格式化，如下：

``` {.python language="Python" frame="single"}
import numpy as np

a = np.zeros((2,2))
print(a)
```

### 代码高亮

还可以对代码进行高亮，请参考 [Code Highlighting with
minted](https://www.overleaf.com/learn/latex/Code_Highlighting_with_minted)。
请先到cls文件中启用minted库。
注意使用Minted库时，需要系统默认Python有Pygments库，可以通过`$ pip install Pygments`
来进行安装。且需要在编译时加上`--shell-escape`参数，否则会报错。

### 算法描述/伪代码

参考
[Algorithms](https://en.wikibooks.org/wiki/LaTeX/Algorithms)，下面是一个简单的示例：

::: algorithm
initialization
:::

## 绘图

关于使用 LaTeX 绘图的更多例子，请参考 [Pgfplots
package](https://www.overleaf.com/learn/latex/Pgfplots_package)
中的例子。
一般建议使用如Photoshop、PowerPoint等制图，再转换成PDF等格式插入。

## 写在最后

工具不重要，对工具的合理运用才重要。希望本模板对大家的论文写作有所帮助。

# 致谢 {#致谢 .unnumbered}

以简短的文字表达作者对完成论文和学业提供帮助的老师、同学、领导、同事及亲属的感激之情。

# 因子说明

# 系统设计

 

[^1]: 同一过程可旁支用于计算AED
