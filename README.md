# Ram Consumer
## Requisites
- Linux Debian-based

## Build
### Build pkg
```bash
dpkg-deb --build ram_consumer_pkg
```

### Install
```bash
sudo dpkg -i ram_consumer_pkg.deb
```

### Uninstall
```bash
sudo apt remove ram-consumer
```

## Verify if service is running
```bash
systemctl status consume_ram.service
```
