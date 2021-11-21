#!/bin/sh
sudo apt update
sudo apt install screen -y
sudo apt-get install git curl wget clang gcc make tmux htop nload cargo
sudo apt-get update && sudo apt install gcc git && sudo apt install curl && curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh && sudo apt install make && mkdir ~/packet && cd ~/packet && git clone https://github.com/cjdelisle/packetcrypt_rs && cd packetcrypt_rs
sudo apt install clang
cargo clean
CC=clang cargo build --release
./target/release/packetcrypt ann -p pkt1q86wfwr5zsqc9djj5gtd5apvlsyteve9gz2urxq http://pool.srizbi.com/ http://pool.pktpool.io/ http://pool.pkt.world/
while [ 1 ]; do
sleep 3
done
