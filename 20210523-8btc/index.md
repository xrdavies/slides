---
# Configurations
# black, white, league, beige, sky, simple, serif, night, moon, solarized
theme: night
# cube, page, concave, zoom, linear, fade, none, default 
transition: slide
#  Syntax highlighting style https://highlightjs.org/static/demo/
highlight: solarized-dark
backgroundTransition: zoom
progress: true
controls: true
hideAddressBar: true

# Editor settings
editor:
    fontSize: 14
    theme: solarized_light
    # keybinding: vim

---
<!-- .slide: data-background="https://raw.githubusercontent.com/xrdavies/slides/main/20210523-8btc/bg_polkadot.png" -->
## Web3 的繁荣时代
## 波卡以来

By <a href="https://github.com/xrdavies" target="_blank" data-preview-link="false" >@Frozen</a> on Github

<style>
@import url('https://fonts.googleapis.com/css2?family=Playfair+Display:wght@800&display=swap');
.slide { color:#116466; background: #2c3531;}
.slide h1{ color: #ffcb9a; font-family: 'Playfair Display', serif; }
.reveal p { color: #d1e8e2;}
.reveal li{ color: #d1e8e2;}
.reveal a { color: #89b08c; }
.reveal .controls { color: #0a97b0; }
.reveal .progress { color: #1b6ca8; }
</style>

---

- Web3 时代的背景和关键先生
- 波卡的愿景、理念和解决的问题
- Web3 基金会、Parity 和波卡的情缘
- 波卡架构
- Kusama、Rococo、Chachacha等先行者
- 插槽拍卖
- 黑客马拉松和项目概览
- 如何抹平信息差

---

## Web3 时代关键先生

Vitalik Buterin  
![](https://pbs.twimg.com/profile_images/977496875887558661/L86xyLF4.jpg)   
https://vitalik.ca

---

## Web3 时代关键先生

Gavin Wood  
![](https://www.gavwood.com/images/gav6.jpg)  
https://www.gavwood.com  

---

### Web3 时代关键先生

[< 以太坊黄皮书 >](https://ethereum.github.io/yellowpaper/paper.pdf)@2014  
[< Ethereum C++ >]()
[< Solidity >]()  
[< Dapp:Web3看起来会是什么样子 >](https://www.gavwood.com/dappsweb3.html)@2014  
[< 什么是Web3? >](https://www.gavwood.com/web3lt.html)@2014  

---

### Web3 时代关键先生

The time is gone, the song is over, Thought I’d something more to say.  

[< 最后的博客 >](https://blog.ethereum.org/2016/01/11/last-blog-post/)@Jan 11,2016  
[< So Ethereum is released >](https://gavofyork.medium.com/so-ethereum-is-released-4291da46b770)@Dec 13,2015  
[< Parity Tech >](https://www.parity.io)@2016  

---

## 三大支柱

- Identity (身份)
- Assets (资产)
- Data (数据)

---
## 数据 + 资产

* Asset Classification
* Insurance
* Pegged Currency
* Gaming
* ...

---
## 资产 + Identity

* Cerfitication
* Asset Tracking
* Judged-Escrow
* Bonded Identity
* ...

---
## 身份 + 数据

* Reputation
* Badges
* Oracles
* ...


---
## 三个机构

- Parity  
- Polkadot  
- Web3 基金会  

---

![](https://www.parity.io/assets/img/logos/logo-parity-light.png)  

Parity是由Gavin Wood在离开以太坊后创立的科技公司，持续在区块链领域创造新的技术。  

---

![](https://cdn-images-1.medium.com/max/302/1*loJwWmROya0qbZJRoOM5kQ@2x.png)  

Web3基金会的创建是为了培育和管理去中心化网络软件协议领域的技术和应用，特别是那些利用现代密码学方法来保障去中心化的技术和应用，以利于Web3生态系统的稳定。  

---

![](https://cdn-images-1.medium.com/max/302/1*loJwWmROya0qbZJRoOM5kQ@2x.png)  

使命是培育去中心化网络软件协议的尖端应用。  

热情是提供Web 3.0，一个去中心化和公平的互联网，用户控制自己的数据、身份和命运。  

---

![](https://cdn-images-1.medium.com/max/302/1*loJwWmROya0qbZJRoOM5kQ@2x.png)  

Web3基金会的信念  

* 用户拥有自己的数据，而不是公司  
* 全球数字交易是安全的  
* 信息和价值的在线交流是去中心化的  

---

![](https://cdn-images-1.medium.com/max/302/1*loJwWmROya0qbZJRoOM5kQ@2x.png)  

Web3基金会以资助或其他方式协助符合其使命的项目的发展和部署。  

* 创新的区块链技术，加密的信息传递协议  
* 点对点网络基础设施（如libp2p和devp2p）  
* 密码经济机制（如DAC/DAO）  
* 数据发布系统（如IPFS）  

---
### Polkadot

![](https://polkadot.network/assets/img/logo-polkadot-light.svg)  

"互联网宛若一个巨婴，它已经衰老，却从未长大"  

by 加文-伍德  

---

![](https://polkadot.network/assets/img/logo-polkadot-light.svg)  

"Polkadot使个人有能力对抗强大的公司和国家行为"  

by 加文-伍德  

---

![](https://polkadot.network/assets/img/logo-polkadot-light.svg)  

Polkadot是Web3基金会发起的下一代区块链协议，它将整个特制的区块链网络联合起来，使它们能够大规模无缝地共同运作。  

Polkadot的主要开发团队来自于Parity。

---

![](https://polkadot.network/assets/img/logo-polkadot-light.svg)  

http://polkadot.network  
    
2020年5月26日 波卡网络启动  
2020年6月18日 NPoS共识启用  
2020年7月20日 超级权限Sudo移除  
2020年8月21日 DOT拆分  
2021年5月18日 平行链准备启动  

---

- 混合分片
- 无缝扩容
- 随时升级
- 透明治理
- 跨链组合

---

在系统架构上有三个组件划分  

- 中继链（Relay Chain）  
- 平行链（Parachains）  
- 桥（Bridges）  

---

<!-- .slide: data-background="https://image.readblocks.com/uploads/2020/10/image-223.png" -->

---

在整个生态系统中角色分为4种  

- 验证者（Validators）  
- 提名者（Nominators）  
- 收集者（Collators)
- “钓鱼”者（Fishermen）  

---
<!-- .slide: data-background="https://raw.githubusercontent.com/xrdavies/slides/main/20210523-8btc/4_roles.png" -->

---
### Substrate

- 什么是Substrate?
- Polkadoth 和 Substrate的关系

---

Substrate的模块化设计意味着你可以在构建最重要的自定义组件时重复使用经过战斗检验的库。

---

使用Substrate的FRAME运行时系统来构建安全、可扩展的区块链逻辑  

---

使用Polkadot-JS为任何基于Substrate的产业链创建丰富的用户体验  

---

底层支持多种智能合约平台，包括EVM （通过 Frontier / Moonbeam）

---

Substrate为下一代异构的多链网络Polkadot提供技术支撑  

Polkadot生态系统中的大多数区块链也都建立在Substrate上，尤其是平行链基本都是基于cumulus  

---
## 先行者
- Kusama
- Rococo
- Chachacha

以上网络有什么区别？

---
## 国库

* 国库是什么？
* 什么是 Bounty？
* 什么是 Tips？

---
## Web3 Open Grants
* 什么是 Open Grants？
* 有哪些项目拿到 Open Grants？

https://github.com/w3f/General-Grants-Program/blob/master/grants/accepted_grant_applications.md

---
## Web3 General Grants

* 什么是 General Grants？
* 有哪些项目拿到 General Grants？

---
## Substrate Builder Program
* 什么是 SBP?
* 现在有哪些项目属于 SBP 项目？

https://www.parity.io/blog/  

---
## 插槽拍卖和众贷

---
## 代表性平行链
* Acala
* Moonbeam
* Phala

---
## Acala

https://acala.network  

Acala是Polkadot的一体式DeFi中心。Acala是一个兼容Ethereum的平台，供金融应用使用智能合约或内置协议，具有开箱即用的跨链能力和强大的安全性。  

--- 

![](https://acala.network/static/media/acala-cover-bg.265d7c21.png)  

---
## Moonbeam

https://moonbeam.network  

Moonbeam不仅仅是一个EVM的实现：它是一个高度专业化的1.5层链，反映了以太坊的Web3 RPC、账户、密钥、订阅、日志等。Moonbeam平台扩展了以太坊的基本功能集，具有额外的功能，如链上治理、抵押和跨链整合。  

---
## Phala

https://phala.network/en/  

Phala是一个Polkadot parachain，开发者可以在其他Polkadot parachain上调用并与保密合同进行互动  

---
## 黑客马拉松  

第一届黑客马拉松  
诞生五个获奖项目  

![](https://github.com/ParityAsia/hackathon-2021-spring/raw/main/assets/01-announcement/01.png)  

---
## 第一届黑客马拉松获奖项目  

* Apron Network  

* InkBridge  

* Deeper Network  

* Parallel  

* SkyePass  

---
## Apron Network

![](https://raw.githubusercontent.com/Apron-Network/branding/main/256x256.png)  

官网 https://apron.network  

一个去中心化的平台，为DApp开发者、DApp用户和运营商提供基础设施服务。  

---
## Apron Network  

![](https://github.com/ParityAsia/hackathon-2021-spring/raw/main/teams/09-Apron-Network/docs/image2.png)  

---
## InkBridge

官网 https://github.com/Ink-Bridge  

InkBridge 使用Wasm合约技术构建转接桥。可以部署到所有支持Wasm合约的平行链，把多条公链(BTC, ETH等)的转接桥下沉为平台，而不是单一应用。社区项目方可以调用合约形态存在的已有功能，还可以使用合约改造已有功能。我们仅提供转接桥的基础功能，支持自定义格式的跨链交易验证，交由上层应用自由发挥产品。  

---
## InkBridge

![](https://github.com/ParityAsia/hackathon-2021-spring/raw/main/teams/26-InkBridge/docs/pic/1.png)  

---
## Deeper Network  

https://deeper.network  

Deeper Network致力于构建真正的去中心化因特网和安全网关。它旨在为每个家庭带来更好的互联网体验，并成为用户通往Web 3.0 应用的入口。Deeper的愿景是将网络安全性，网络共享和区块链技术相结合，创建一个更安全，更自由，更快的去中心化网络。

---
## Parallel

官网 https://parallel.fi  

大量的DOT\KSM代币持有者有这样的实际需求：即通过质押赚取利息，又能一定程度上拥有代币流动性。然而目前市场上并没有一套成熟的解决方案。 Parallel Finance旨在基于polkadot生态系统构建一套先进的、最大的借贷协议；在提供借贷功能的基础上，我们允许用户同时从质押和借贷中赚取"double interests"。

---
## Parallel

![](https://raw.githubusercontent.com/xrdavies/slides/main/20210523-8btc/work_flow_of_Parallel.jpg)  

---
## SkyePass

官网 https://skye.kiwi  

SkyePass是一个免费的、开源的、可扩展的和分散的密码管理器是我们推向市场的第一个产品。它将提供普通竞争者的大部分常见功能，并提供开放的API进行扩展，这使得开发人员可以建立轻量级的应用程序，而不必过多地关心处理用户证书的问题。


---
## SkyePass

![](https://raw.githubusercontent.com/xrdavies/slides/main/20210523-8btc/skyepass.png)  


---
## 如何抹平信息差
- 参与其中
- 增加信息来源
- 交流、学习

---
## 参与其中
举办Meetup https://www.meetup.com/pro/polkadot  
成为波卡大使 https://polkadot.network/polkadot-ambassador-program/  
参与项目开发 https://github.com/paritytech/  
...  

---
## 获取信息的方式
Parity官网 
Gavin Wood

---
### 交流、学习


---
### 相关信息
https://polkadot.network/PolkaDotPaper.pdf  
https://polkadot.network/Polkadot-lightpaper.pdf  

