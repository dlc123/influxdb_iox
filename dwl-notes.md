

# wsl setup

sudo apt-add-repository ppa:hnakamur/flatbuffers
sudo apt update

sudo apt install -y flatbuffers-compiler clang

sudo apt-get install openssl
export OPENSSL_DIR=/usr/lib/ssl

sudo apt install pkg-config
sudo apt install libssl-dev
sudo apt-get install git locales sudo openssh-client ca-certificates tar gzip parallel \
    unzip zip bzip2 gnupg curl make pkg-config libssl-dev \
    musl musl-dev musl-tools clang llvm