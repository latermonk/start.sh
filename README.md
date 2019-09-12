# start.sh




```
yum install -y yum-utils \
  device-mapper-persistent-data \
  lvm2
  
  
yum-config-manager \
    --add-repo \
    https://download.docker.com/linux/centos/docker-ce.repo
    
    
yum install -y docker-ce docker-ce-cli containerd.io
    
    
  
  
```

```

apt install docker.io     


docker run -d --restart=unless-stopped -p 80:80 -p 443:443 rancher/rancher



```

