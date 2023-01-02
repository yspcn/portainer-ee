# portainer-ee portainer企业版汉化
**不要问我怎么安装**

**AMD64**
``` Bash
cd /root && git clone https://github.com/yspcn/portainer-ee
docker run -d --restart=always --name="portainer" -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data -v /root/portainer-ee:/public portainer/portainer-ee:linux-amd64-2.12.2
```

**ARM64**
``` Bash
cd /root && git clone https://github.com/yspcn/portainer-ee
docker run -d --restart=always --name="portainer" -p 9000:9000 -v /var/run/docker.sock:/var/run/docker.sock -v portainer_data:/data -v /root/portainer-ee:/public portainer/portainer-ee:linux-arm64-2.12.2
```
