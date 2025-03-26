# Deploy an encrypted contract Devnet Seismic 

# Use Gitpod to depoly 

```
sudo apt update
sudo apt upgrade -y
sudo apt install -y curl git build-essential
```
```
sudo apt install file -y
```
```
sudo apt install unzip -y
```
```
curl https://sh.rustup.rs -sSf | sh
source "$HOME/.cargo/env"
rustc --version
```
```
sudo apt install -y jq
jq --version
```
```
curl -L \
     -H "Accept: application/vnd.github.v3.raw" \
     "https://api.github.com/repos/SeismicSystems/seismic-foundry/contents/sfoundryup/install?ref=seismic" | bash
```
```
source ~/.bashrc
```
Note - Foundry take 15 mins to complete
```
sfoundryup 
```
```
git clone --recurse-submodules https://github.com/SeismicSystems/try-devnet.git
cd try-devnet/packages/contract/
```
```
bash script/deploy.sh
```

#### Next, you will see a wallet address, Send some faucet 0.15 ETH to that address then enter, Below is an example of what it looks like.

[![Screenshot-8.png](https://i.postimg.cc/28Xv1JhD/Screenshot-8.png)](https://postimg.cc/56LjGss7)

### Now 1st contract completed...

### Interaction with an Bun contract: 

```
curl -fsSL https://bun.sh/install | bash
```
```
source ~/.bashrc
```
```
bun --version
```
```
cd ../cli/
bun install
```
```
bash script/transact.sh  / executing a transaction
```
### Now we completed the devnet contract interaction, Next step follow the telegram thread...


### Star this Repo...
