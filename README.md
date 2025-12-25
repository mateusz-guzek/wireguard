# WireGuard installer
Forked from [repo I found very useful](https://github.com/angristan/wireguard-install)

## Usage

Download and execute the script. Answer the questions asked by the script and it will take care of the rest.

```bash
git clone https://github.com/mateusz-guzek/wireguard.git
cd wireguard
chmod +x wireguard-install.sh
./wireguard-install.sh
```

It will install WireGuard (kernel module and tools) on the server, configure it, create a systemd service and a client configuration file.

Run the script again to add or remove clients!
