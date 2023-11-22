# To Run the Code:
git clone "https://github.com/Shraggus/RustChain"
**CPP Blockchain:**
cd RustChain/code-external/chain_block
cd build
cmake ..
make
./chain_block
You can create new blocks from the terminal
**Rust blockchain**
cd RustChain/code-orig/rust-blockchain
RUST_LOG=info cargo run
This starts the client locally. The blockchain is not persisted anywhere.
You can start it in multiple terminals to get multiple connected peer-to-peer clients.
In each client, you can enter the following commands:
ls p - list peers
ls c - print local chain
create b $data - $data is just a string here - this creates (mines) a new block with the data entry $data and broadcasts it