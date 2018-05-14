### Chia FAQ

+ <b>Q: 什么是Chia?</b>

A: Chia 是一款即将发布的基于区块链的数字货币，它依靠空间证明和时间证明来代替传统的工作证明。 Chia通过由“农民”所拥有的未使用的存储空间来“播种”， “农民”通过回答每个区块的问题作为共识机制而获得Chia。 Chia“农业”使用空间证明，与另一个证明时间共识算法协调，以减少已知的基于空间区块链证明的攻击。我们的目标是防止浪费大量电力的同时来开采并且减少集中开采（例如ASIC驱动的采矿）。 “播种”时，随机生成的认证信息存储在硬盘上的可用空间中。



+ <b>Q: 农业是什么意思?</b>

A: Chia 农业有点像挖矿，下面来说下它是如何安全的创造区块的，“农业”通过在你的硬盘驱动器上执行未使用的存储的快照（播种）来工作。根据农场的存储量作为网络上所有存储的百分比，你将有机会获得Chia奖励。你分配给农场的空间越多，获得奖励的可能性越大。但是通过大量购买硬盘来获得Chia的动机不大，因为Chia预计目前存在大量闲置空间，而不是逐渐增加所有人的成本。 Chia利用这个闲置空间。因为世界上存在这么多的存储空间，获得奖励的机会对于普通用户来说是非常低的，但是考虑到它使用的能量、带宽和空间都是闲置的，上面这些都不重要了。另外Chia会尽量减少矿池，矿工，ASIC等集中，减少能源消耗。



+ <b>Q: Chia和比特币的主要区别是什么？</b>

A: Chia与硬盘驱动器一样拥有存储空间，而不是采用处理能力进行挖掘。 这会允许更多人参与进来，并且极大地降低了在电力消耗或定制硬件消耗中保护网络的成本/浪费。 Chia对集中挖矿有抵抗力。 Chia还将包括一系列对比特币协议的基本改进：所有内容都使用<a href="https://en.wikipedia.org/wiki/Boneh%E2%80%93Lynn%E2%80%93Shacham"> BLS签名 </a>以获得更好的智能交易支持，并且它将包含一些错误修复，如<a href =“https://bitcoin.stackexchange.com/questions/20597/where-exactly-is-the-off-by-one-difficulty-bug“> timewarp </a>，同时将这些修补程序提供给比特币。 我们的目标是使硬分支变得不可能实现，因此共识的达成将来自用户选择和比特币分散式激励。



+ <b>Q: 什么是“空间证明”？</b>

“空间证明”不应与存储协议混淆。 区块链存储协议是进行一些有用的数据存储。 诸如Filecoin，MaidSafe，Sia或Storj等存储协议的证明需要大量的带宽，但是这些概念不会在Chia协议中使用。 空间证明是对任何东西都没用的数据。产生空间证据，作出空间证明或向网络提供证据基本上不需要带宽。 空间证明可以被认为是保持一些存储空间不被使用的预先承诺。 客户端软件将使农民可以轻松管理农业存储，因为他们可以选择逐步缩小农场规模，以便根据需要为有用文件腾出空间。



+ <b>Q: Chia种子是什么意思？</b>

A: 播种是一个过程，需要不止一次地读写所分配的农业空间的每个部门; 但是一旦驱动器被播种，只要证据保留在磁盘上，您就可以进行播种。 初始播种过程用随机输入的证据填充存储空间，然后运行一种排序以快速查找所得到的证明。 播种会使用低级别直接访问API读取驱动器。 客户端将支持播种多个驱动器。 重播存储通常没有优势。 重新设置驱动器的唯一原因是过多的现有证据被覆盖。 播种一盘将花费大量的时间，每个驱动器一次。但目标是，一个普通的农民可以种植他们的养殖空间24至48小时初步建立。


+ <b>Q: Chia 将何时推出？</b>

A: Chia计划在第二季度推出代币出售，并将于2018年底推出，但这并非最终结果，可能会因发展进程而发生变化。



+ <b>Q: 我将如何能够购买Chia？</b>

A: Chia计划向公众进行某种销售，目前我们正在与我们的律师合作。 我们销售的目标是尽可能广泛地让投资者参与进来。  因为项目有很多未完成的工作，所以我们需要一些资金。 我们只是在做我们必须做的事情，我们很感激为项目未来的发展和扩张提供资金。 资金到位该货币的前期预定将被执行，预售的资产将会被分配给未来的发展和开发团队。 筹资机制将在代币开始销售之前向公众开放。



+ <b>Q: 现在Chia发展到什么阶段了？</b>

A: 尚未编写任何代码。 一些数学理论已经制定出来并正在朝着论文发表的方向努力。 我们现在正在招聘程序员，编码工作很快就会开始。 关于空间证明和赫尔曼时间 - 内存权衡的技术性论文可以在<a href="https://eprint.iacr.org/2017/893">这里</a>查阅。



+ <b>Q: 我什么时候可以种植Chia呢？</b>

A: 我们希望在2018年第二季度公开发售，一旦网络启动，我们希望在2018年底之前启动，您就可以开始播种了。所有的时间表可能会根据开发进度而改变。。



+ <b>Q: 时间证明是什么意思？</b>

A: 时间证明是农业的第二步。 时间证明取决于以实时为参数来生成证明的函数，但是证明对于当前块是正确的，并且可以由网络中的任何人快速验证为正确。 Chia预计只有有限数量的时间节点证明，因为这些节点不会因为提出当前块的时间证明而获得奖励。 只有农场拥有最佳空间证明的农民才能在每个区块获得Chia代币奖励。



+ <b>Q: 为什么叫Chia呢？</b>

A: “Chia”是你之前可能听说过的粮食的名称。 它是一种绿色粮食。 它符合“农业”主题。



+ <b>Q: 更多的硬盘空间是否意味着更多的Chia？</b>

A: 您下一个区块种植的机会与您分配给Chia农场的存储空间量成正比。



+ <b>Q: 值得购买硬盘驱动Chia吗？</b>

A: Chia认为，仅仅为了农业目的购买硬盘驱动器是无利可图的，因为每个人都可以从未使用的存储器中获得奖励 - 这是很多的。 农业奖励可能很小，但如果您因其他原因已经拥有存储设备，则不会为农民带来额外的费用。 人们已经支付了大量未使用的存储容量 - 可用剩余资源 - 所以仅仅为了农业而购买存储将是无利可图的。 这直接关系到存储对其他事物有用，尽管它不是“有用的”农业，因为计算本身并不具有生产力，但它正在利用有用的资源。 就Chia意外地推动降低存储成本的发展而言，我们认为这对社会有益 - 特别是与在定制ASIC采矿硬件上浪费电力相比时。



+ <b>Q: Chia与Burst等其他存储代币有什么不同？</b>

A: Burstcoin没有时间方面的证明，因此存在使其不适合作为挖掘算法的攻击。 此外，Chia简化了用于空间证明的数学运算。 Chia还继承了比特币协议的部署经验。


+ <b>Q: Chia将如何获得资助？</b>

A: Chia筹集了一笔种子资金，但我们有足够的开发工作来完成筹集资金的必要。 我们将尽可能以透明和公开的方式尝试这样做。



+ <b>Q: Chia交易的速度有多快？</b>

A: 除了区块链之外，Chia还支持闪电网络，因此支付速度取决于是否有可用的闪电路径。 闪电交易在合理的网络延迟上花费不到几秒钟的时间。 我们的上链交易封锁时间与比特币相似。



+ <b>Q: 作品中的其他Chia动态？</b>

A: 在首次发布后，我们的重点将是支持Lightning，就像今天一样，增加了外链频道，支持MAST，并可能使用<a href="https://blockstream.com/simplicity.pdf">Simplicity</a>语言 以及支持保险库的智能合约。 Chia将支持原子交换出去。 我们从比特币脚本开始使用BLS签名而不是DSA。 该计划将结合比特币部署推出版本，因为它基于相同的代码库。



+ <b>Q:Chia会使用哪种脚本语言？</b>

A: 我们将使用修改后的比特币脚本，为初学者和切换到BLS签名。 <a href="https://www.youtube.com/watch?v=Og52VDU-pjc">这次演讲</a>解释了我们两个变化的原因。 长期来看，一旦可用，我们将添加Simplicity。 我们正在建设比特币代码库，所以核心开发将采用C / C ++。



+ <b>Q: Chia的难度将如何调整？</b>

A: 和比特币一样，难度也会动态调整，以保持封锁时间的规律 农业困难将平衡空间证明的难度和时间证据。 因此，随着农业竞争的加剧，您可以期望来自特定存储量的回报下降。 我们不希望农业具有足够高的预期价值，以便为农场购买驱动器。



+ <b>Q: 硬盘需要多大？</b>

A:可能最小分配大小为100 GB或1 TB。 强制执行最低限度的要求是，在分配完成之前要求最少的挂钟时间才能通过，以便攻击者不能重复生成和尝试新的分配，而不是执行单个查找。



+ <b>Q: 我能在我的个人电脑上种植Chia吗？</b>

A: 对于个人电脑的农民来说，仍然会有一些奖励，对于一些非零奖励，成本仍然会实际为零。 它不像比特币采矿，因为电力消耗导致个人电脑失去与ASIC矿工竞争的问题。 并且带宽需求预计也很低。


+ <b>Q: Chia和比特币有类似的供应机制吗？</b>

A: Chia种植奖励将减少三分之一，最终每块获得奖励给农民的低固定数量的chia。 流通中的硬币继续以固定的年度开采率增长，但每年铸造（生长？）代币（谷物？）的比例永久降低，占现有总硬币的百分比。 为了了解这在实践中意味着什么，在主网上线后，Chia的衰减数量需要大约153年。



+ <b>Q: Chia如何抵抗矿工集中？</b>

A: Chia使用空的存储器（如硬盘驱动器）来种子。 由于存在这么多的空闲存储空间，任何有未使用存储空间的人都可以耕种，这应该导致农业分散化。 比特币的工作采矿系统证明推动了对数量有限的矿工的组建，因为购买专门的ASIC采矿设备并将其定位在便宜的电力附近超出了大多数人的投资能力。 存储制造商可以优化存储硬件以便更快速地或更便宜地进行存储，但是这样做的成本可能不值得奖励，而且这样做可能会降低每个人的存储成本。 Chia应该成为市场上最权威的加密货币。



+ <b>Q: Chia代码会开源吗？</b>

A: Chia将发布有关该协议构建模块的学术论文，所有实施代码均为开放源代码。 我们将使用<a href="https://www.apache.org/licenses/LICENSE-2.0"> Apache许可证</a>。 当testnet出来但mainnet还没有启动时，我们有机会保持我们的源代码更专有一些，但是一旦mainnet通常可用，我们一定会根据Apache许可证开源我们的所有源代码。



+ <b>Q: 你有我可以阅读更多的白皮书吗？</b>

A: 像大多数项目一样，我们不会只有一份白皮书，我们将在期刊上发表学术论文。 到目前为止，我们已有<a href="https://eprint.iacr.org/2017/893">我们的第一篇论文</a>被Asiacrypt和我们的<a href =“https：//eprint.iacr.org / 2018/183“>第二篇论文</a>在Eurocrypt上获得最佳论文。 至少还会有另外一篇论文讨论如何将整个事物连接成区块链。



+ <b>Q: 我在哪里可以找到更多？</b>

A: 您可以注册公告列表以获取信息。 我们也可以在Keybase上讨论公告。 查看我们的主页链接。
