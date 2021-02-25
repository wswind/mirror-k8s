aliyun mirror build 

k8s.gcr.io/ingress-nginx/controller:v$version to registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version

version support list:
v0.40.2

example to use:

```bash
version=0.40.2
docker pull registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version k8s.gcr.io/ingress-nginx/controller:v$version 
```


