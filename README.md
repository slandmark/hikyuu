![封面](http://hikyuu.org/images/00000_title.png)

Hikyuu Quant Framework是一款基于C++/Python的开源量化交易研究框架，用于策略分析及回测。其核心思想基于当前成熟的系统化交易方法，将整个系统化交易抽象为由市场环境判断策略、系统有效条件、信号指示器、止损/止盈策略、资金管理策略、盈利目标策略、移滑价差算法七大组件，你可以分别构建这些组件的策略资产库，在实际研究中对它们自由组合来观察系统的有效性、稳定性以及单一种类策略的效果。

Maybe，你已经注意到了，上面没有“选股策略”？！是的，选股策略是股票交易的重要方面，肯定不会少。事实上，之前所述的交易系统都是针对一个交易对象的，也就是经常听到的策略，但很多所谓的“策略”其实仅仅只是买入、卖出的指示信号而已，并非完整的交易策略。为了区别，在这里直接以系统指称，表示一个完整的系统化交易方法或策略。而在系统之上，称为Portfolio资产组合，选股策略则是Portfolio的组件，Portfolio的另一重要组成则是资金分配策略，比如选股策略选定了4个交易对象（股票或基金等），那么如何在它们之间进行合理的资金分配？

所以，Hikyuu Quant Framework其实是在System和Portfolio基础之上、包含了九大策略组件：市场环境判断策略、系统有效条件、信号指示器、止损/止盈策略、资金管理策略、盈利目标策略、移滑价差算法、交易对象选择策略、资金分配策略。可以在此基础上构建自己的策略库，并进行灵活的组合和测试，甚至可以更进一步，在选择交易对象的同时，选取与之匹配的最优系统交易策略（System）。

更多信息请访问：<http://hikyuu.org>

