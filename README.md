# 智能合约安全入门

关键词：smart contract, block chain, security, 智能合约, 区块链

作者：余泽平

![book-1](https://user-images.githubusercontent.com/39737245/155871583-db735bab-ace6-4464-8cee-556ffd63f3b5.png)



## 目录

### 第一章 环境准备  ......................................21

1.1  npm 安装 Remix IDE  .............................................................21

1.2  docker 拉取 Remix IDE .............................................................22

1.3 docker 拉取 geth  .............................................................23

1.4 本章总结  .............................................................23

### 第二章 Remix IDE 介绍和使用 .....................................24

2.1 学习 Remix 环境使用一  .............................................................24

2.1.1 部署学习  .............................................................26

2.2 学习 Remix 环境使用二  .............................................................28

2.2.1 部署学习  .............................................................28

2.2.2 构造函数  .............................................................30

2.2.3 初始化合约余额  .............................................................31

2.3 学习 Remix 环境使用三  .............................................................33

2.3.1 Remix + Metamask  .............................................................33

2.4 附录表-Remix 命令列表  .............................................................35

2.5 本章总结  .............................................................36

### 第三章 Metamask 介绍和使用 .......................................37

3.1 安装 Metamask  .............................................................37

3.2 获取测试币  .............................................................38

3.2 Metamask Api 使用  .............................................................40

3.3 本章总结  .............................................................40

### 第四章 geth 基础和使用  ...................................41

4.1 geth 基础命令  .............................................................41

4.1.1 一些命令使用例子  .............................................................41

4.2 geth console 下的基础命令 .............................................................42

4.2.1 console 下web3对象中常用的命令 ............................................42

4.2.2 console 下挖矿  .............................................................43

4.3 geth 启动私有节点  .............................................................43

4.3.1 启动节点  .............................................................43

4.3.2 测试节点  .............................................................43

4.3.3 启动参数说明  .............................................................44

4.3.4 关于 RPC  .............................................................44

4.3.5 节点 console  .............................................................44

4.3.6 新建用户  .............................................................44

4.3.7 开始挖矿  .............................................................45

4.3.8 测试转账  .............................................................45

4.4 部署智能合约一  .............................................................47

4.4.1 使用容器提供例子  .............................................................47

4.4.2 重新编译  .............................................................47

4.5 调用智能合约一  .............................................................51

4.6 geth 从头搭建私链  .............................................................52

4.5.1 创建目录  .............................................................52

4.5.2 启动私链  .............................................................55

4.7 部署智能合约二  .............................................................55

4.8 调用智能合约二  .............................................................57

4.9 新版本 geth  .............................................................58

4.10 本章总结  .............................................................59

### 第五章 solidity 语言基础 ...................................60

5.1 创建合约  .............................................................60

5.2 合约接口  .............................................................61

5.3 变量类型  .............................................................62

5.4 变量修饰  .............................................................62

5.5 类型转换  .............................................................63

5.6 数学运算  .............................................................64

5.7 字符串比较  .............................................................64

5.8 结构体及数组  .............................................................64

5.9 普通数组  .............................................................64

5.10 函数定义及修饰符  .............................................................65

5.11 构造函数  .............................................................66

5.12 函数返回值  .............................................................67

5.13 一些内置函数  .............................................................68

5.14 fallback 函数  .............................................................69

5.16 receive 函数  .............................................................72

5.17 msg 和 tx 全局变量  .............................................................73

5.17.1 msg 全局变量  .............................................................73

5.17.2 tx 全局变量  .............................................................74

5.18 创建事件  .............................................................77

5.19 循环结构  .............................................................77

5.20 条件判断  .............................................................77

5.21 以太单位  .............................................................77

5.22 转账操作  .............................................................77

5.23 OpenZeppelin 库  .............................................................78

5.24 本章总结  .............................................................78

### 第六章 solidity 数据存储 ....................................79

6.1 存储中的状态变量存储结构 .............................................................79

6.2 紧凑存储  .............................................................80

6.3 动态大小数据存储  .............................................................81

6.3.1  动态 String  .............................................................81

6.3.2 小疑问 length*2  .............................................................83

6.4  动态数组存储  .............................................................83

6.5 字典 mapping 存储  .............................................................85

6.6 本章总结  .............................................................85

### 第七章 web3.js 和 web3.py ................................86

7.1 web3.js  .............................................................86

7.1.1 安装 web3.js  .............................................................86

7.2 web3.js 配合 Metamsk  .............................................................87

7.2.1 异步请求方式 1  .............................................................87

7.2.2 异步请求方式 2  .............................................................88

7.2.3 异步请求方式 3  .............................................................89

7.3 常用函数  .............................................................89

7.3.1 hash 函数  .............................................................89

7.3.2 地址有关  .............................................................90

7.3.3 单位转换  .............................................................90

7.3.4 字符串转换  .............................................................91

7.3.5 账户函数  .............................................................91

7.3.6 获取插槽数据  .............................................................91

7.3.7 获取区块信息  .............................................................91

7.3.8 获取交易信息  .............................................................92

7.3.9 交易签名  .............................................................93

7.3.10 abi 签名和编码  .............................................................93

7.4 web3.js 连接节点  .............................................................94

7.4.1 WebSockets支持  .............................................................95

7.4.2 本地连接测试  .............................................................95

7.5 web3.js 部署合约  .............................................................96

7.6 web3.js 连接合约  .............................................................100

7.6.1 实例化合约对象  .............................................................100

7.6.2 web3.js call 调用 .............................................................100

7.6.3 web3.js send 调用 .............................................................102

7.6.4 web3.js 监听事件  .............................................................103

7.7 web3.py  .............................................................103

7.7.1 安装 web3.py .............................................................104

7.8 web3.py 部署合约 .............................................................104

7.9 web3.py 连接合约 .............................................................104

### 第八章 call 函数利用漏洞 ......................................106

8.1 关于 call 函数 .............................................................106

8.1.1 函数签名(函数选择器) .............................................................106

8.1.2 call 函数无参数调用 .............................................................108

8.1.3 call 函数有参数调用 .............................................................110

8.1.4 call 函数调用其他合约 .............................................................112

8.2 漏洞场景 .............................................................114

8.3 代码分析 ............................................................. 116

8.4 代码调试 .............................................................116

8.5 本章总结 .............................................................119
### 第九章 重入漏洞 ..................................120

9.1 关于重入漏洞 .............................................................120

9.2 关于 fallback 函数 .............................................................120

9.3 攻击场景 .............................................................120

9.4 漏洞场景 .............................................................121

9.5 攻击演示 .............................................................122

9.6 本章总结 .............................................................125
### 第十章 整型溢出漏洞 .....................................126

10.1 溢出原理 .............................................................126

10.2 溢出场景 .............................................................126

10.2.1 加法溢出 .............................................................126

10.2.2 减法溢出 .............................................................128

10.3 案例分析-BEC .............................................................129

10.3.1 代码片段 .............................................................129

10.3.2 代码分析 .............................................................129

10.4 攻击模拟 .............................................................129

10.5 本章总结 .............................................................133

### 第十一章 访问控制漏洞 .....................................134

11.1 关于访问控制漏洞 .............................................................134

11.1.1 代码层面可见性 .............................................................134

11.1.2 逻辑层面权限约束 .............................................................134

11.2 漏洞场景一[函数定义不当] .............................................................134

11.2.1 漏洞场景分析 .............................................................135

11.2.2 漏洞场景演示 .............................................................135

11.2.3 规避建议 .............................................................137

11.3 漏洞场景二[Constructor 函数定义不当] ................................................138

11.3.1 漏洞场景分析 .............................................................138

11.3.2 漏洞场景演示 .............................................................138

11.3.3 规避建议 .............................................................139

11.4 漏洞场景三[tx.origin使用不当] ................................................140

11.4.1 tx.origin 和 msg.sender .............................................................140

11.4.2 漏洞场景分析 .............................................................140

11.4.3 漏洞场景演示 .............................................................141

11.4.4 规避建议 .............................................................144

11.5 本章总结 .............................................................144

### 第十二章 未检查返回值 .....................................145

12.1 低级别调用函数 .............................................................145

12.2 低级别调用中产生异常的原因 .............................................................145

12.3 低级别调用与普通函数调用的区别 .............................................................145

12.4 漏洞场景 .............................................................145

12.4.1 关于 send 函数 .............................................................146

12.4.2 漏洞场景分析 .............................................................147

12.4.3 漏洞场景演示 .............................................................147

12.5 真实案例-Etherpot .............................................................149

12.6 漏洞预防 .............................................................150

### 第十三章 可预测随机值 .......................................151

13.1 随机数生成 .............................................................151

13.1.1  区块变量作为熵源的 PRNG .............................................................151

13.1.2 区块变量测试 .............................................................151

13.2 漏洞场景 .............................................................153

13.2.1 漏洞场景分析 .............................................................153

13.3 漏洞场景演示 .............................................................154

13.4 漏洞修复 .............................................................155

### 第十四章 时间控制漏洞 ......................................156

14.1 关于 block.timestamp .............................................................156

14.2 以太坊中的时间戳合理要求 .............................................................156

14.3 漏洞场景一 .............................................................156

14.3.1 漏洞场景分析 .............................................................157

14.3.2 漏洞场景演示 .............................................................158

14.3.3 另外攻击姿势 .............................................................163

14.4 漏洞场景二 .............................................................164

14.5 本章总结 .............................................................165

### 第十五章 抢先交易漏洞 .....................................166

15.1 关于抢先交易漏洞 .............................................................166

15.2 满足“抢先交易”的条件 .............................................................166

15.3 交易顺序决定 .............................................................166

15.3.1 手续费高低原则 .............................................................166

15.3.2 先进先出原则 ............................................................. 167

15.3.3 共识节点排序原则 .............................................................167

15.4 交易池 .............................................................167

15.5 攻击流程 .............................................................168

15.6 漏洞场景分析 .............................................................169

15.7 漏洞场景演示 .............................................................169

15.7.1 本地搭建私链 .............................................................169

15.7.2 错误不期而遇 .............................................................170

15.7.3 换用 geth .............................................................171

15.7.4 部署合约 .............................................................171

15.7.5 开始攻击 .............................................................173

15.7.6 总结 .............................................................175

15.8 本章总结 .............................................................178

### 第十六章 短地址攻击漏洞 .....................................179

16.1 关于短地址攻击漏洞 .............................................................179

16.2 漏洞场景分析 .............................................................179

16.3 攻击者地址生成 .............................................................181

16.4 漏洞场景演示 .............................................................181

16.4 本章总结 .............................................................184

### 第十七章 拒绝服务漏洞 .............................................................185

17.1 关于拒绝服务漏洞 .............................................................185

17.1.1 拒绝服务的原因 .............................................................185

17.2 漏洞场景一[selfdestruct] .............................................................185

17.2.1 合约自毁 selfdestruct .............................................................185

17.2.2 漏洞场景演示 .............................................................186

17.2.3 关于 selfdestruct .............................................................187

17.3 漏洞场景二[所有者丢失] .............................................................188

17.3.1 所有者丢失 .............................................................188

17.3.2 漏洞场景演示 .............................................................189

17.4 漏洞场景三[gas 达到区块上限] .............................................................191

17.4.1 gas 达到区块上限 .............................................................191

17.5 漏洞场景四[非预期异常] .............................................................192

17.5.1 非预期异常 .............................................................192

17.5.2 攻击 payload .............................................................193

17.5.3 漏洞场景演示 .............................................................193

17.6 本章总结 .............................................................196

### 第十八章 账户及账户生成 ....................................197

18.1 以太坊账户 .............................................................197

18.2 以太坊地址 .............................................................197

18.2.1 私钥和公钥 .............................................................198

18.2 外部账户生成 .............................................................198

18.3 特定外部账户生成 .............................................................202

18.4 合约账户生成 .............................................................203

18.4.1 已知 nonce 的外部地址 .............................................................203

18.4.2 未知 nonce 的外部地址 .............................................................205

18.5 CREATE2 .............................................................209

18.5.1 关于 CREATE2 .............................................................209

18.5.2 create code .............................................................209

18.5.3 Factory 合约 .............................................................210

18.6 本章总结 .............................................................215

### 第十九章 Ethernaut ...................................216

19.1 关于 Ethernaut .............................................................216

19.2 环境准备 .............................................................216

19.2.1 Hello Ethernaut .............................................................216

19.2.2 安装 Metamsk 插件 .............................................................216

19.2.3 测试网络选择 .............................................................217

19.2.4 Rinkeby 测试币获取 .............................................................218

19.2.5 console 使用 .............................................................219

19.3 本章总结 .............................................................219

### 第二十章 Ethernaut Level 1 ...................................220

20.1 Level-1 Fallback .............................................................220

20.1.1 source .............................................................220

20.2 源码分析 .............................................................221

20.2.1 关于 fallback .............................................................221

20.2.2 攻击过程 .............................................................221

20.3 闯关尝试 .............................................................221

20.3 本章总结 .............................................................227

### 第二十一章 Ethernaut Level 2,3,4,5 ....................................228

21.1 Level-2 Fallout .............................................................228

21.1.1 source .............................................................228

21.1.2 源码分析 .............................................................229

21.1.3 闯关尝试 .............................................................229

21.2 Level-3 Coin Flip .............................................................230

21.2.1 source .............................................................230

21.2.2 源码分析 .............................................................231

21.2.3 闯关尝试 .............................................................231

21.2.4 攻击 payload .............................................................232

21.3.5 问题总结 .............................................................234

21.3 Level-4 Telephone .............................................................234

21.3.1 source .............................................................235

21.3.2 源码分析 .............................................................235

21.3.3 payload .............................................................235

21.3.4 闯关尝试 .............................................................236

21.4 Level-5 Token .............................................................238

21.4.1 source .............................................................239

21.4.2 源码分析 .............................................................239

21.4.3 闯关尝试 .............................................................239

21.5 本章总结 .............................................................240

### 第二十二章 Ethernaut Level 6,7,8,9 ...................................241

22.1 Level-6 Delegation .............................................................241

22.1.1 source .............................................................241

22.1.2 源码分析 .............................................................241

22.1.3 闯关尝试 .............................................................242

22.1.4 另谋出路 .............................................................244

22.2 Level-7 Force .............................................................245

22.2.1 source .............................................................245

22.2.2 源码分析 .............................................................246

22.2.3 攻击 payload .............................................................247

22.2.4 闯关尝试 .............................................................247

22.3 Leval-8 vault .............................................................249

22.3.1 source .............................................................249

22.3.2 源码分析 .............................................................249

22.3.3 闯关尝试 .............................................................250

22.4 Level-9 King .............................................................251

22.4.1 source .............................................................251

22.4.2 源码分析 .............................................................252

22.4.3 攻击 payload .............................................................252

22.4.4 闯关尝试 .............................................................253

22.5 本章总结 .............................................................254

### 第二十三章 Ethernaut Level 10,11,12,13 .................................255

23.1 Level-10 Re-entrancy .............................................................255

23.1.1 source .............................................................255

23.1.2 源码分析 .............................................................255

23.1.3 关于重入漏洞 .............................................................256

23.1.4 攻击 payload .............................................................256

21.1.5 闯关尝试 .............................................................256

23.2 Level-11 Elevator .............................................................258

23.2.1 source .............................................................259

23.2.2 源码分析 .............................................................259

23.2.4 闯关尝试 .............................................................260

23.3 Level-12 Privacy .............................................................261

23.3.1 source .............................................................261

23.3.2 源码分析 .............................................................261

23.3.3 闯关尝试 .............................................................262

23.4 Level-13 GateKeeper One .............................................................263

24.4.1 source .............................................................263

24.4.2 源码分析 .............................................................264

23.4.3 攻击 payload .............................................................264

23.4.4 闯关尝试 .............................................................265

23.5 本章总结 .............................................................269

### 第二十四章 Ethernaut Level 14,15,16,17 ................................270

24.1 Level-14 Gatekeeper Two .............................................................270

24.1.1 source .............................................................270

24.1.2 源码分析 .............................................................270

24.1.3 攻击 payload .............................................................271

24.1.4 闯关尝试 .............................................................272

24.2 Level-15 Naught Coin ............................................................. 273

24.2.1 source .............................................................273

24.2.2 源码分析 .............................................................274

24.2.3 闯关尝试 .............................................................275

24.3 Level-16 Preservation .............................................................276

24.3.1 source .............................................................276

24.3.2 源码分析 .............................................................277

24.3.3 攻击 payload .............................................................278

24.3.4 闯关尝试 .............................................................278

24.4 Level-17 Recovery .............................................................280

24.4.1 source .............................................................280

24.4.2 源码分析 .............................................................281

24.4.3 闯关尝试 .............................................................281

24.5 本章总结 .............................................................283

### 第二十五章 Ethernaut Level 18,19,20 ....................................284

25.1 Level-18 MagicNumber .............................................................284

25.1.2 源码分析 .............................................................285

25.1.4 闯关尝试 .............................................................287

25.2 Level-19 Alien Codex .............................................................288

25.2.1 source .............................................................288

25.2.2 源码分析 .............................................................289

25.2.3 闯关尝试 .............................................................290

25.3 Level-20 Denial .............................................................293

25.3.1 source .............................................................293

25.3.2 源码分析 .............................................................294

25.3.3 payload .............................................................295

25.3.4 闯关尝试 .............................................................295

25.4 本章总结 .............................................................296

### 第二十六章 通用 payload 生成 ............................297

### 参考文献 .................................................300

### 完结 .......................................................301


## 获取方式
等待 3 月 1 日
