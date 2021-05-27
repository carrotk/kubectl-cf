# kubectl-cf

[![Go Report Card](https://goreportcard.com/badge/github.com/wbsnail/kubectl-cf)](https://goreportcard.com/report/github.com/wbsnail/kubectl-cf)
![](https://img.shields.io/github/license/wbsnail/kubectl-cf)
![](https://img.shields.io/github/v/release/wbsnail/kubectl-cf)

> Fork 自 https://github.com/spongeprojects/kubectl-cf, 提供汉化。

切换 kubeconfig 配置文件 (不是切换 context)。

![demo.gif](https://github.com/spongeprojects/kubectl-cf/blob/main/assets/demo.gif?raw=true)

```
kubectl-cf 使用说明:
  cf           选择 kubeconfig
  cf [config]  选择 kubeconfig (无交互)
  cf -         切换到前一个使用的 kubeconfig
```

备注：`kubectl-cf` 是用来切换 kubeconfig 配置文件的，如果你需要切换单个 kubeconfig（也可能是多个 kubeconfigs）当中的不同
context，推荐你使用 https://github.com/ahmetb/kubectx。

## 安装

### 手动安装

首先从发布页面下载 tar 包: https://github.com/wbsnail/kubectl-cf/releases.

解包之后可以得到可执行文件 `kubectl-cf`.

可以把这个文件放在任何地方, 只要它在 `PATH` 当中就可以。可以直接用 `kubectl-cf`
执行, 也可以作为 [kubectl 插件](https://kubernetes.io/docs/tasks/extend-kubectl/kubectl-plugins/) 执行：`kubectl cf`,
因为它包含 `kubectl-` 前缀。

当然也可以把它命名为任何你想要的名称, 或者创建指向它的软链接, 从而更方便地调用它, 比如说 `cf`。

## 多语言

- [English](https://github.com/spongeprojects/kubectl-cf)
- [Chinese](https://github.com/wbsnail/kubectl-cf)

## TODO (欢迎 PR)

- 自动补全;
- [krew](https://krew.sigs.k8s.io/) 集成;
- 测试;

