# Graduate_Project_Bitcon
## 比特币深层监控系统及其实现    
### 一、挖矿原理  
1.挖矿的过程就是重复计算区块头的hash，不断修改随机数Nonce，直到小于难度目标计算出来的hash。  
2.挖矿是比特币共识机制中的工作量证明机制算法。  
3.分布式系统一致性的核心就是节点达成共识，而共识算法的核心就是解决拜占庭将军问题，BitCoin巧妙地利用了POW解决了拜占庭问题。  
4.经济学上认为，理性的人都是逐利的，POW一直了节点的恶意动机。    
全节点，轻节点，记账节点。  
钱包的含义：  
钱包是存储和管理用户密钥的数据结构。其中只含有密钥，并没有余额。  
非确定型钱包：随机生成的私钥集合。  
确定型钱包：钱包中所有的密钥是由一个主密钥派生出来，该类型中钱包的所有密钥都相互关联，如果有原始种子，则可以再次生成全部密钥。（用树状结构生成的称为HD钱包）。

### 二、BitcoinCore安装    
安装，然后下载Block.dat文件。