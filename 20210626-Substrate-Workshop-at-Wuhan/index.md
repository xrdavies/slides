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
## ink! 合约初学者

By <a href="https://github.com/xrdavies" target="_blank" data-preview-link="false" >@Frozen</a> on Github

---
- ink! 简介
- 环境说明
- 环境准备
- ERC20示例

---
### ink!

- 以Rust语言为蓝本
- 可以兼容WebAssembly
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
```
sudo apt update
sudo apt install -y git clang curl libssl-dev llvm libudev-dev
```

---
### 环境准备 Mac
安装 brew
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

安装 openssl
```
brew update
brew install openssl
```

---
### Substrate 环境安装
脚本安装方式
```
curl https://getsubstrate.io -sSf | bash -s -- --fast
```

---
### Substrate 环境安装
手动安装
```
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

```
cargo install cargo-contract --vers ^0.12 --force --locked
```

---
### Canvas节点安装 (可选)

```
cargo install canvas-node --git https://github.com/paritytech/canvas-node.git --tag v0.1.8 --force --locked
```

---
### Canvas Node启动 (可选)
```
canvas --dev --tmp
```

---
### Canvas UI (可选)

https://paritytech.github.io/canvas-ui

---


---
### 相关信息
https://substrate.dev/docs/en/knowledgebase/getting-started/  
https://substrate.dev/substrate-contracts-workshop/#/  
https://github.com/paritytech/canvas-node  
https://github.com/paritytech/substrate/tree/master/frame/contracts  
https://github.com/paritytech/cargo-contract  
https://github.com/paritytech/canvas-ui  
