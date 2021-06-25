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
### 环境准备
Ubuntu
```
sudo apt update
sudo apt install -y git clang curl libssl-dev llvm libudev-dev
```

Mac
```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
brew update
brew install openssl
```

---
### Rust安装

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
### Canvas节点安装

```
cargo install canvas-node --git https://github.com/paritytech/canvas-node.git --tag v0.1.8 --force --locked
```

---
### 相关信息
https://polkadot.network/PolkaDotPaper.pdf  
https://polkadot.network/Polkadot-lightpaper.pdf  

