# k8s-kustomize

## 概要

- KusTOMizeを使って遊んでみる

## コマンド

### 各環境のマニフェスト生成

```shell
kustomize build 環境名
```

### デプロイ

```shell
kubectl apply -k 環境名
```

## 参考資料

- [Kustimize](https://kubectl.docs.kubernetes.io/guides/)
- [KusTOMize を使用した Kubernetes オブジェクトの宣言的管理](https://kubernetes.io/docs/tasks/manage-kubernetes-objects/kustomization/)
- [Kustomize使ってみた](https://zenn.dev/yusekita/articles/5738746d5ab8e8)
