- Ubuntu

```bash
curl -O https://raw.githubusercontent.com/mosleim/wireguard-install/master/wireguard-install.sh
chmod +x wireguard-install.sh
./wireguard-install.sh
```

on local pc:

```bash
scp user@ip:wg0-client.conf .
sudo mv wg0-client.conf /etc/wireguard/wg0.conf
```

cheers...!
