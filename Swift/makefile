install_emscripten_sdk:
	sudo apt-get install -y build-essential cmake python nodejs git-core
	wget https://s3.amazonaws.com/mozilla-games/emscripten/releases/emsdk-portable.tar.gz
	tar -zxvf emsdk-portable.tar.gz
	echo 'export PATH="$$PATH:/home/ubuntu/emsdk-portable"' >> /home/ubuntu/.bashrc

install_rustup:
	curl https://sh.rustup.rs -sSf | sh -s -- -y

install_emscripten: install_emscripten_sdk
	emsdk update
	emsdk install sdk-incoming-64bit
	emsdk activate sdk-incoming-64bit

install_emscripten_rust: install_rustup
	rustup target add wasm32-unknown-emscripten

build: install_emscripten, install_emscripten_rust
	rustc --target=wasm32-unknown-emscripten hello.rs -o hello.html

default: build
