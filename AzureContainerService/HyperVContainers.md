# Hyper-V Containers (Preview)
Although hyper-v containers are in preview stages, the promise is large.
Enabled by Windows container technology, the container ecosystem can now include Windows Server containers and Hyper-V containers. The lifecycle for creation, management, and functionality are identical - they even use the same container images.
It is still early days for Enterprise containers and certainly hyper-v containers, expect updates to this doc in the future!

## Windows Sever Containers
* Multiple run concurrently on a host
* Isolation through namespace, resource control, and process isolation 
* Share same kernel with other WS containers and the host

## Hyper-V Containers
* Multiple run concurrently on a host
* Each container has it's own special virtual machine
* Kernel level isolation between each Hyper-V container AND the container host

## More docs
[Hyper-v container preview doc](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=1&cad=rja&uact=8&ved=0ahUKEwjzk7O-1YHSAhVS_WMKHXN4C-oQFggaMAA&url=https%3A%2F%2Fdocs.microsoft.com%2Fen-us%2Fvirtualization%2Fwindowscontainers%2Fmanage-containers%2Fhyperv-container&usg=AFQjCNHUyoJEvkhV3HHoPDazys8gE8X2Dw&sig2=6WHp_eQXGfe8wVTckehkhw)