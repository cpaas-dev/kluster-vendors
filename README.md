# Kluster Vendors

> 将上游软件重新打包为 OCI 镜像，通过容器镜像仓库进行分发。

本仓库是 Kluster 各上游组件打包项目的索引。每个组件对应一个独立的 `kluster-vendor-*` 仓库。

## 组件一览

### Kubernetes

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| kubernetes | ✅ | [kluster-vendor-kubernetes](https://github.com/cpaas-dev/kluster-vendor-kubernetes) |
| k3s | 🚧 TODO | — |

### High-level Container Runtime

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| containerd | ✅ | [kluster-vendor-containerd](https://github.com/cpaas-dev/kluster-vendor-containerd) |
| cri-o | 🚧 TODO | — |
| docker with cri-dockerd | 🚧 TODO | — |

### Container Runtime

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| crun | ✅ | [kluster-vendor-crun](https://github.com/cpaas-dev/kluster-vendor-crun) |
| runc | 🚧 TODO | — |

### OCI Registry

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| zot | ✅ | [kluster-vendor-zot](https://github.com/cpaas-dev/kluster-vendor-zot) |
| distribution registry | 🚧 TODO | — |

### Sealos

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| sealos | ✅ | [kluster-vendor-sealos](https://github.com/cpaas-dev/kluster-vendor-sealos) |

### Tools

| 组件 | 状态 | 仓库 |
| --- | --- | --- |
| CRI Tools (crictl) | ✅ | [kluster-vendor-cri-tools](https://github.com/cpaas-dev/kluster-vendor-cri-tools) |
| Helm | ✅ | [kluster-vendor-helm](https://github.com/cpaas-dev/kluster-vendor-helm) |

## 状态说明

| 标记 | 含义 |
| --- | --- |
| ✅ | 已完成打包并可用 |
| 🚧 TODO | 规划中，尚未开始 |
