# mirror-k8s.gcr.io-ingress-nginx-controller

This repo is used to push `k8s.gcr.io/ingress-nginx/controller` image to aliyun.  
k8s.gcr.io/ingress-nginx/controller:v$version => registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version

example to use:

```bash
version=0.40.2
docker pull registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/ingress-nginx-controller:$version k8s.gcr.io/ingress-nginx/controller:v$version 
```

This repo's git tag is like `release-v$version`. Aliyun will read the tag to auto build images.
So check the tag list of this repo for supported image version list.

参考：<https://blog.csdn.net/sinat_35543900/article/details/103290782>
