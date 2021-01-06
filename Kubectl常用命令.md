#  KubeCtl常用命令

* kubectl api-resources 查看支持的API资源
* kubectl get [kind] -n [namespace] 查看某一个Namespce下的资源
* kubectl get [kind] [name] -o wide 查看某一个资源
* kubectl get [kind] [name] -o yaml 查看某一个资源的yaml
* kubectl describe [kind] [name] 查看资源的详细信息
* kubectl apply -f [yaml] 
* kubectl logs -f [pod] 查看Pod的实时日志
* kubectl exec [pod] -it bash 登录容器
* kubectl edit 编辑资源
* kubectl scale [kind] [name] --replicas [num] 扩容/缩容
* kubectl rollout history [kind]/[name] 查看历史版本
* kubectl rollout undo [kind]/[name]  回滚到上一个版本
* kubectl rollout undo [kind]/[name] --to-revision=[revision] 回滚到指定版本

