# Upgrade-to-nibiru-testnet-2-


cd && rm -rf nibiru
git clone https://github.com/NibiruChain/nibiru.git
cd nibiru
git checkout v0.16.3
make build
sudo mv build/nibid /usr/local/bin/nibid
sudo systemctl restart nibid
