# rbd-provisioner

Using StorageClass and PVC to provision volume.
PVC is stuck in Pending state and log indicates the following error.
rbd: create volume failed, err: executable file not found in $PATH

Now deploy standalone rbd-provisioner controller avoid using customized kube-controller image
