# calendfi-docs
### product requirements document

front-end source code:Typescript or javascript

smartcontract source code:Cardano Haskell


Source code introduction: The system has no management backend, and the data is completely decentralized. All data is stored in the contract on the chain. Only the front end interacts with the contract. The contract can be deployed in any network environment and is compatible with all networks. All executable operations such as setting the lock-up period and output rate can be executed in the contract. The contract comes with Chinese documents and comments, source code compilation and all maintenance documents and developer documents are provided. The front-end supports wallet connection network judgment and prompts to connect to the appropriate network. It can adapt to multiple network environments and can also be set independently to support only a single network.
源码介绍:系统无管理后台，完全属于去中心化数据都存在链上合约里，只有前端与合约的交互，合约可在任意网络环境上部署，兼容全部网络，可在合约设定锁仓期限以及产出速率等一切可执行操作可在合约执行，合约附带中文文档和注释，源码编译以及全部维护文档以及开发者文档，前端支持钱包连接网络判断以及提示连接合适网络，可适应多网络环境情况下也可以单独设定仅支持独一网络。

### pledge step:

1，Supports pledge of any token reward. A certain token can open the time limit for withdrawal of pledge or the time limit for withdrawal of income (single currency reward single currency)

2，Support for staking any LP reward A certain token can open the time limit for withdrawal of pledge or time limit for withdrawal of income (liquidity reward single currency)

3，Supports pledge of any token to reward a certain token + a certain token can open the time limit for withdrawal of pledge or the time limit for withdrawal of income (single currency reward dual currency)

支持质押任意LP奖励:某代币可开启提取质押时间限制 或 提取收益时间限制（流动性奖励单币）

支持质押任意代币奖励:某代币可开启提取质押时间限制 或 提取收益时间限制（单币奖励单币）

支持质押任意代币奖励:某代币+某代币可开启提取质押时间限制 或 提取收益时间限制（单币奖励双币）

### Single currency mining business logic

单币挖矿是什么意思？
单币挖矿⼜被成为单币⽆损挖矿。单币质押简单理解就是质押一种代币，可以锁仓质押，也可随，时提取，不通的方式年化收益不等。特点就是拿着单个加密资产，质押后产⽣收益。这种质押⻛险极低(⼤多数时候没有⻛险)，操作简单，如果只是质押加密资产也就是借⼊资产⽽不借出资产，就相当于单币挖矿。最⼤的弊病是收益率不够⾼。

What does single coin mining mean?
Single-coin mining is called single-coin lossless mining. A simple understanding of single-currency pledge is to pledge a token, which can be locked and pledged, or withdrawn at any time. The annualized income varies in different ways.The characteristic is to hold a single encrypted asset and generate income after pledge. This kind of pledge is very low risk (most of the time there is no risk), and the operation is simple. If you only pledge encrypted assets, that is, borrow assets without lending assets, it is equivalent to single-coin mining. The biggest drawback is that the rate of return is not high enough.


