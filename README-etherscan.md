<h1 style="text-align: center;">etherscan使用介绍：</h1>

Etherscan 是以太坊网络的区块链浏览器。该网站允许您搜索交易、区块、钱包地址、智能合约和其他链上数据。它是最受欢迎的以太坊区块链浏览器之一，并且可以免费使用。
提示：
本次介绍仅在以太坊Testnet进行
本次介绍的输入地址都是测试网中任意地址，仅做参考

下面介绍基本使用：
切换网络节点
1.鼠标悬浮
![image](etherscan-screenshot/图片1.jpg)

2.我们可以切换到Ropsten Testnet，Kovan Testnet，Rinkeby Testnet，Goerli Testnet ...
3.选择Ropsten Testnet切换


查询address
1.在搜索框输入查询：0x81b7E08F65Bdf5648606c89998A9CC8164397647
![image](etherscan-screenshot/图2.jpg)


2.可以查询到address详情
![image](etherscan-screenshot/图20.jpg)

查询交易
1.在搜索框输入查询：
0x14aa05c4021ce95b469a13c1309fb50c5398807a1c546c5829b70ad0b79fd9b0
![image](etherscan-screen/图3.jpg)


2.可以查询到交易详情
![image](etherscan-screenshot/图4.jpg)


查询合约
1.在搜索框输入查询：0xc778417E063141139Fce010982780140Aa0cD5Ab
![image](etherscan-screenshot/图5.jpg)

2.可以查询到合约基本信息
![image](etherscan-screenshot/图6.jpg)

查询所有ERC20\ERC721\ERC1155合约数据
我们以ERC20为例子来操作
1.鼠标悬浮Tokens
![image](etherscan-screenshot/图7.jpg)


2.点击View ERC20 Transfers,可以查询到所有ERC20合约到交易数据
![image](etherscan-screenshot/图8.jpg)



查询合约ABI-json
1.在搜索框输入查询：0xc778417E063141139Fce010982780140Aa0cD5Ab
![image](etherscan-screenshot/图9.jpg)


2.进入合约详情页，点击Contract
![image](etherscan-screenshot/图10.jpg)


3.滚动到Contract ABI，点击复制ABI
![image](etherscan-screenshot/图11.jpg)


4.复制ABI后，我们可以进行导入到编译器中进行使用（这里我们使用Black IDE进行调试 https://ide.black/）
![image](etherscan-screenshot/图12.jpg)
![image](etherscan-screenshot/图13.jpg)
![image](etherscan-screenshot/图14.jpg)
![image](etherscan-screenshot/图15.jpg)
![image](etherscan-screenshot/图16.jpg)
![image](etherscan-screenshot/图17.jpg)






注意：合约地址要是该ABI的合约地址
进入合约调试页面成功
![image](etherscan-screenshot/图18.jpg)


查询合约函数
1.进入合约详情页面，点击Contract->Read Contract
![image](etherscan-screenshot/图19.jpg)


