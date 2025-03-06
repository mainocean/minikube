# minikube

Hi. In this video I setting up a local Kubernetes cluster on Windows.
Minikube is a popular tool designed to help developers run a single-node Kubernetes cluster locally on their machines. It's a lightweight way to get hands-on experience with Kubernetes without needing a full-blown, multi-node cluster.

Minikube allows you to run a local Kubernetes cluster, making it easy to develop and test Kubernetes applications on your own machine. It can be a great way to get hands-on experience with Kubernetes. For this, I install VirtualBox, kuberctl and minikube.

```
https://www.youtube.com/watch?v=QQbE_CUr8P4&list=PL62Nmy7ld-5bCC3PC5z6xVsGlCsl0NfW5&ab_channel=DevOps
```

Need for install:

```
kuberctl   https://kubernetes.io/releases/download/#binaries

Minikube
https://minikube.sigs.k8s.io/docs/start/?arch=%2Fwindows%2Fx86-64%2Fstable%2F.exe+download

VirtualBox   https://www.virtualbox.org/wiki/Downloads
```

Login:

```
root     without password
docker   pass:tcuser
```

Manual with commands:

```
minikube version
minikube start
minikube stop
minikube delete
minikube ssh

minikube start -- cpus=4 -- memory=8gb -- disk-size=5gb
minikube start -- cpus=2 -- memory=6000mb -- disk-size=4000mb
minikube start -p MYSUPERCLUSTER

kubectl version
kubectl version -- client
kubectl get componentstatuses
kubectl cluster-info
kubectl get nodes
```

# Total

[![GitHub license](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://github.com/mainocean/blob/main/LICENSE) [![GitHub contributors](https://img.shields.io/github/contributors/mainocean/git-checkout--b-DP-9-complete-the-task-for-youtube.git)]() [![GitHub pull requests](https://img.shields.io/github/issues-pr/mainocean/git-checkout--b-DP-9-complete-the-task-for-youtube.git)]() [![GitHub commit activity the past week, 4 weeks](https://img.shields.io/github/commit-activity/y/mainocean/git-checkout--b-DP-9-complete-the-task-for-youtube.git)]()

