# [VM Scale Set Extensions] (https://docs.microsoft.com/en-us/azure/virtual-machines/virtual-machines-windows-extensions-configuration-samples) - 01/13/2017

* Putting customized microservices on your VM scaleset to do VM specific tasks such as resetting passwords or executing scripts

## How to install <br>

The below command is an example of how to install the CustomScriptForLinux extension on a scale set. You must pass in the necessary settings for a successful install and this will update the VMSS model.
```
juluk@justins-mbp-2:~/documents/github/Azure-For-Everyone-Else$ az vmss extension set --resource-group exportvmss --vmss-name linuxvmss --publisher Microsoft.OSTCExtensions --name CustomScriptForLinux --version 1.5 --settings '{"fileUris": ["https://raw.githubusercontent.com/gatneil/scripts/master/hello.sh"], "commandToExecute": "sh hello.sh"}'
```

## Resources