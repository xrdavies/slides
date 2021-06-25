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
    fontSize: 10
    theme: solarized_light
    # keybinding: vim

---
<!-- .slide: data-background="https://raw.githubusercontent.com/xrdavies/slides/main/20210523-8btc/bg_polkadot.png" -->
## ink! 合约初学者

By <a href="https://github.com/xrdavies" target="_blank" data-preview-link="false" >@Frozen</a> on Github

---
- ink! 简介
- 环境说明
- 环境准备
- ERC20示例

---
### ink!

- 以 Rust 为蓝本
- 可以兼容 WebAssembly
- 服务于 Substrate 构建的区块链
- 智能合约

---
### 环境说明

- Rust + Cargo
- cargo-contract # ink! CLI
- Substrate构建的区块链
- 区块链激活 contracts pallet
- Substrate UI

---
### 环境准备 Ubuntu
```bash
sudo apt update
sudo apt install -y git clang curl libssl-dev llvm libudev-dev
```

---
### 环境准备 Mac
安装 brew
```bash
/bin/bash -c "$(curl -fsSL\
https://raw.githubusercontent.com\
/Homebrew/install/master/install.sh)"
```

安装 openssl
```bash
brew update
brew install openssl
```

---
### Substrate 环境安装
脚本安装方式
```bash
curl https://getsubstrate.io -sSf | bash -s -- --fast
```

---
### Substrate 环境安装
手动安装
```bash
curl https://sh.rustup.rs -sSf | sh
source ~/.cargo/env

rustup default stable
rustup update
rustup update nightly
rustup component add rust-src --toolchain nightly
rustup target add wasm32-unknown-unknown --toolchain nightly
```

---
### ink! cli 安装

```bash
cargo install cargo-contract --vers ^0.12 --force --locked
```

---
### binaryen 安装

* Debian/Ubuntu: `apt-get install binaryen`
* Homebrew: `brew install binaryen`
* Arch Linux: `pacman -S binaryen`
* Windows: binary releases at https://github.com/WebAssembly/binaryen/releases

---
### Canvas Node 安装 (可选)

```bash
cargo install canvas-node --git \
https://github.com/paritytech/canvas-node.git \
--tag v0.1.8 \
--force \
--locked
```

---
### Canvas Node 启动 (可选)

```bash
canvas --dev --tmp --ws-external --rpc-external
```
or
```bash
canvas --chain=./res/testnet-1.json
```

---
### Canvas UI (可选)

```bash
git clone https://github.com/paritytech/canvas-ui.git
yarn install
yarn start
```

线上可用版本
https://paritytech.github.io/canvas-ui

---
### Polkadot JS Extension (可选)
使用 Canvas UI 时，需要下载插件钱包
https://polkadot.js.org/extension/

创建对应的钱包

---
### 弄点钱
需要从水龙头弄点测试币

---
###  创建项目
```bash
cargo contract new erc20
cd erc20
```

---
### 测试
```bash
cargo +nightly test
```

---
### 编译
```bash
cargo +nightly contract build
```

---
### 演示


---
### 相关信息

https://substrate.dev/substrate-contracts-workshop/  
https://github.com/paritytech/canvas-node  
https://github.com/paritytech/canvas-ui  
https://github.com/paritytech/cargo-contract  