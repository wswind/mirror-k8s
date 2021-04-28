# mirror-k8s

This repo is used to push k8s images to aliyun.  

example to use:

```bash
docker pull registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:controller-v0.45.0
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:controller-v0.45.0 k8s.gcr.io/ingress-nginx/controller:v0.45.0

docker pull registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0
docker tag registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0 k8s.gcr.io/coredns/coredns:v1.8.0

#or ctr
ctr -n=k8s.io i pull registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0
ctr -n=k8s.io i tag registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0 registry.cn-hangzhou.aliyuncs.com/google_containers/coredns/coredns:v1.8.0
ctr -n=k8s.io i ls
crictl -r /run/containerd/containerd.sock images
crictl config runtime-endpoint /run/containerd/containerd.sock
crictl images
```

