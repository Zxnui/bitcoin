## tx
## build-aux
## contrib
## depends
## doc
文档
## share
## src
### 目录
- bench				共识-法官判断
- compat			兼容
- config			配置
- consensus			共识算法
- crypto			加密解密
- index   	
- interfaces		j事件，节点，钱包类
- leveldb			水平数据库
- obj 				cpp编译中间目录
- obj-test			cpp编译中间目录
- policy			策略
- primitives		区块类 交易类
- qt				图形界面类
- rpc				通信
- script 			脚本
- secp256k1			加密算法
- support			功能支持类
- test 				类的功能测试
- univalue			一致性
- wallet			钱包类
- zmq				通信消息

### 接口
- walletinitinterface.h钱包抽象类接口
- validationinterface.h,cpp区块校验接口
- ui_interface.h,cpp图形界面接口

### 运行模块
- bitcoind 			客服端核心模块
- bitcoin-cli 		rpc客户端
- bitcoin-tx		交易处理模块
- bitcoin-qt		qt编写的bitcoin图形化界面客户端

### 功能模块
- addrdb			地址数据库类
- addrman			交易地址
- amount			控制总量
- arith_uint256		大整数de算法类
- base58			编码类
- bech32			编码类
- blockencodings	区块编码
- bloom				筛选器快速查找区块数据
- chainparamsbase	链参数核心类
- chain 			把区块链接在一起的类
- chainparams 		区块参数
- chainparamsseeds	种子
- checkpoints		检查点-校验
- checkqueue		队列校验
- clientversion		处理客户端
- coins 			币的核心类
- compat			兼容32 64 window linux
- compressor		数据压缩类，发送消息
- core_io			核心输入输出
- core_memusage		核心内存管理
- core_read			核心读
- core_write		核心写
- cuckoocache		内存缓存
- dbwrapper			对于数据库进行封装
- fs 				文件打开关闭
- hash 				散列值
- httprpc 			网页通讯协议
- httpserver  		通讯服务器
- indirectmap 		非定向哈希存储结构
- init 				初始化
- key 				秘钥类
- key_io 			key的文件存储
- keystore 			key存储类，存储为文件，存储到内存
- limitedmap 		限制类型的哈希结构
- logging
- memusage 			内存使用
- merkleblock		merkle数的区块链结构
- miner 			挖矿
- net 				处理网络
- net_processing 	执行
- netaddress 		计算机网络地址
- netbase			网络父类
- netmessagemaker	处理网络消息
- noui				链接网络
- pow				工作量证明-挖矿结构
- prevector			c++模板类，自定义的可变化的数组数据结构
- protocol			协议，所有的操作定义
- pubkey			公钥，非对称加密解密
- random			随机数
- rest 				支持类，数据与字符串转换等等
- reverse_iteratior	反转
- reverselock		数据反锁
- scheduler			调度
- serialize			文件读写序列化
- shutdown			
- span 				数据绑定
- streams			文件流
- sync				线程同步
- threadinterrupt	线程中断
- threadsafety		线程安全
- timedata			时间的数据格式化
- tinyformat		数据格式化
- torcontrol		洋葱网络控制
- txdb				文件的存储，读写
- txmempool			内存池
- uint256 			无符号256位整数类	哈希计算
- undo				撤销的功能
- util 				日志，字符串的处理等功能
- utilmoneystr 		显示比特币类，单位
- utilstrencodings 	编码解码
- utiltime			时间处理
- validation 		数据校验
- version 			版本信息
- versionbits		版本判断
- warnings			处理警告信息

## test