# kubectl-cf

> Fork 自 https://github.com/spongeprojects/kubectl-cf，提供汉化。

切换 kubeconfig 配置文件 (不是切换 context)。

![demo.gif](https://github.com/spongeprojects/kubectl-cf/blob/main/assets/demo.gif?raw=true)

```
kubectl-cf 使用说明:
  cf           选择 kubeconfig
  cf [config]  选择 kubeconfig (无交互)
  cf -         切换到前一个使用的 kubeconfig
```

备注：`kubectl-cf` 是用来切换 kubeconfig 配置文件的，如果你需要切换单个 kubeconfig（也可能是多个 kubeconfigs）当中的不同 context，推荐你使用 https://github.com/ahmetb/kubectx。
