# opmanager
ManageEngine Key Manager Plus on docker

To quickly get started running use the following command:
```bash
docker run --detach --publish 6565:6565 babim/kmp:latest
```
```
volume:
/opt/ManageEngine
port:
6565
```

run manual with CMD /usr/sbin/init and download, install apps
change to CMD default after install apps