# mirror-k8s

用于中国境内搭建k8s时，使用[阿里云镜像服务](https://cr.console.aliyun.com/)，提供缺失的镜像。

镜像地址为`registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s`，为节约命名空间，使用tag存储不同镜像。

对照列表：

| origin                                      | mirror                                                       |
| ------------------------------------------- | ------------------------------------------------------------ |
| quay.io/coreos/flannel:v0.14.0              | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:flannel-v0.14.0 |
| k8s.gcr.io/ingress-nginx/controller:v0.45.0 | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:ingress-nginx-controller-v0.45.0 |
| k8s.gcr.io/ingress-nginx/controller:v0.46.0 | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:ingress-nginx-controller-v0.46.0 |
| k8s.gcr.io/ingress-nginx/controller:v0.47.0 | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:ingress-nginx-controller-v0.47.0 |
| k8s.gcr.io/ingress-nginx/controller:v0.48.1 | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:ingress-nginx-controller-v0.48.1 |
| k8s.gcr.io/kube-apiserver:v1.21.4           | registry.cn-hangzhou.aliyuncs.com/wswind/mirror-k8s:kube-apiserver-v1.21.4 |

