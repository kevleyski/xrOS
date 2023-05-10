# xrOS

Kevs WebGL Wasm example

curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y

git clone https://github.com/kevleyski/xrOS.git

cd xrOS/webxr/kevs-webgl-blit

cargo build

wasm-pack build

cd api

npm install

npm run start
