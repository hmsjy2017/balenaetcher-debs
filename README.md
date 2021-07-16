# balenaEtcher arm builds

Automatically compiled and uploaded for each new Etcher release. (arm64 only for now)

Thanks to [**@Itai-Nelken**](https://github.com/Itai-Nelken/) for creating scripts.

### How to install the repository...
```
sudo wget https://chunky-milk.github.io/balenaetcher-debs/etcher.list -O /etc/apt/sources.list.d/etcher.list
wget -qO- https://chunky-milk.github.io/balenaetcher-debs/KEY.gpg | sudo apt-key add -
sudo apt update && sudo apt install balena-etcher-electron -y
```
