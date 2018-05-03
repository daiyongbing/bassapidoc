##API 概览

**交易相关接口**
	
接口名		    |请求地址				|请求方式	|功能描述
:--------------:| :-------------------- | :--------:|:----------
系统启动			|/system/start			| GET		|启动系统
系统停止			|/system/stop			| GET		|停止系统
查询区块			|/block					| GET		|查询指定高度的区块信息
查询区块			|/block/hash			| GET		|查询指定ID的区块信息
查询块链信息		|/chaininfo				| GET		|查询当期块链信息
查询交易			|/transaction			| GET		|查询指定ID的交易
查询证书短地址	|/certAddr/getCertByAddr| POST		|由证书字符串查询证书短地址
查询证书字符串	|/certAddr/getAddrByCert| POST		|由证书短地址查询证书字符串
发起交易			|/transaction			| POST		|发起交易，包含deploy和invoke