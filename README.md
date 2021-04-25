# mirror-k8s

This repo is used to push k8s images to aliyun.  

example to use:

```bash
docker pull registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:controller-v0.40.2
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:controller-v0.40.2 k8s.gcr.io/ingress-nginx/controller:v0.40.2

docker pull registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0 k8s.gcr.io/coredns/coredns:v1.8.0
```

