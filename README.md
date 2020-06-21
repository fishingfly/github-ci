# github-ci
## 测试github公有仓库
修改下secret.yaml中的harbor用户名和密码
当前目录下运行：
```
kubectl apply -f .
```
## 测试github私有仓库
```
cd build-private-repo
```
修改下secret.yaml中的harbor用户名和密码
修改resource.yaml文件中的github的仓库地址，设置成你自己的地址
修改secret.yaml中的github-user,设置你自己的用户名和密码
运行
```
kubectl apply -f .
```
更多tekton知识，请关注微信公众号“云原生手记”
