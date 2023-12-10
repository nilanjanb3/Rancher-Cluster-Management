```
$ sudo docker run --privileged -d \
-v /opt/rancher:/var/lib/rancher \
--restart=unless-stopped \
-p 80:80 -p 443:443 \
rancher/rancher:latest
```