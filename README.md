# learning kubernetes
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

**note**: not all the things above are probably required, but I had to play around with VirtualBox in order to make minikube work on arch linux

basic commands:
- `minikube start` starts the cluster
- `minikube stop` stops the cluster
- `minikube dashboard` opens dashboard in the web browser
- `minikube` shows help
- `kubectl` shows help
- `VBoxManage list runningvms` show running VMs
- `VBoxManage list vms` shows all VMs

pods and containers
-------------------

Pod is the element, which may contain one or more docker containers, which can communicate with each other.

TBD.

scaling with replicaset
-----------------------

TBD.

communication between services
------------------------------

TBD.

automatic reverse proxy with ingress
------------------------------------

TBD.

managing application, its lifecycle and deployment
--------------------------------------------------

TBD.

application config with configmap
---------------------------------

TBD.

managing virtual environments (namespace)
-----------------------------------------

TBD.

installing applications with helm
----------------------------------

TBD.

creating and publishing applications for helm
---------------------------------------------

TBD.

kubernetess in the cloud - AWS EKS
----------------------------------

TBD.

storing data in volumens
------------------------

TBD.

references
----------
- https://kubernetes.io/
- https://cloudowski.com/kubernetes-po-polsku/
- https://github.com/cloudowski/kubernetes-po-polsku
- https://github.com/pwittchen/learning-docker
