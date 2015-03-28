# docker-cgit

This container is member of the [*booddies*](https://github.com/h0tbird/booddies) fellowship.

Clone and build:
```
git clone https://github.com/h0tbird/docker-cgit.git
cd docker-cgit
./bin/build
```

Install and run:
```
sudo ./bin/install
sudo systemctl start cgit
```

Tail the output:
```
journalctl -f -u cgit
```
