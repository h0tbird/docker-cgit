# docker-cgit

Clone and build:
```
git clone https://github.com/h0tbird/docker-cgit.git
cd docker-cgit
./bin/build
```

Install and run:
```
sudo ln cgit.service /etc/systemd/system/cgit.service
sudo ln bin/runctl /usr/local/sbin/runctl-cgit
sudo mkdir /etc/bootpaas
sudo cp cgit.conf /etc/bootpaas
sudo systemctl daemon-reload
sudo systemctl start cgit
```

Tail the output:
```
journalctl -f -u cgit
```
