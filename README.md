# mirror-k8s

用于中国境内搭建k8s时，使用阿里云镜像服务(https://cr.console.aliyun.com/)构建缺失的镜像。

对照列表：

```bash
k8s.gcr.io/ingress-nginx/controller:v0.40.2 => registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:controller-v0.40.2
k8s.gcr.io/coredns/coredns:v1.8.0 => registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:coredns-v1.8.0
quay.io/coreos/flannel:v0.14.0 => registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:flannel-v0.14.0
```

