## 概要
[Kickstarter](https://www.kickstarter.com/?lang=ja)に似たシステムをEthereum上で構築するプログラムです。  
dApps開発の勉強用です。

<br>

[Ethereum and Solidity: The Complete Developer’s Guide](https://www.udemy.com/course/ethereum-and-solidity-the-complete-developers-guide/)で紹介されています。  
[GitHubはこちら](https://github.com/StephenGrider/EthereumCasts/tree/master/kickstart)

上記のプログラムを少し修正しています。



## システム環境
以下で動作確認済みです。  
OS：macOS 11.2.3  
Node.js：12.19.0



## 実行方法
### ライブラリインストール
```
$ npm install
```


### パラメータを指定
`ethereum/deploy.js`の`METAMASK MNEMONIC PHRAS`、`ENDPOINTS`を指定します。  
`ethereum/web3.js`の`ENDPOINTS`を指定します。


### コンパイル、デプロイ
コンパイルします。
```
$ node compile.js
```
コンパイルが完了すると、`ethereum/build`ディレクトリが作成されます。

<br>

デプロイします。
```
$ node deploy.js
```
デプロイが完了すると、アドレスが表示されますのでそれを`ethereum/factory.js`の`ADDRESS`に指定します。


### 実行
コマンドラインで実行します。
```
$ npm run dev
```
