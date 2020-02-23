# learning-kubernetes
a repo created in order to learn the basics of kubernetes with my personal notes

installation
------------

```
sudo pacman -S minikube
sudo pacman -S kubectl
```

overview:
- `minikube` is local instance of kubernetess cluster running as VM in VirtualBox
- `kubectl` is kube controller used for controlling things inside kubernetess cluster

requirements for minikube (arch linux specific):

```
sudo pacman -S virualbox
sudo pacman -S virtualbox-host-modules-arch
sudo modprobe vboxdr
sudo modprobe vboxnetadp
sudo modprobe cboxnetflt
sudo /sbin/rcvboxdrv setup
```

starting cluster:
- to start `minikube`, type `minikube start` and to see help, type `minikube`
- to see help of `kubectl`, type `kubectl`

Pods and containers
-------------------

references
----------
- https://kubernetes.io/
- https://cloudowski.com/kubernetes-po-polsku/
