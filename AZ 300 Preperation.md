#### 

---

#### Login Azure Account and Setup Context:

##### PowerShell

```
Login-AzureRmAccount

Select-AzureRmSubscription -SubscriptionName $mySubscription

Set-AzureRmContext -SubscriptionName $mySubscription
```

##### Azure CLI

`az login`



---



```
az group create -n myResourceGroup -l eastus


az vm create --image credativ:Debian:8:latest --admin-username tim --ssh-key-value C:/users/tim/.ssh/id_rsa.pub --public-ip-address-dns-name vm-azuretraining-704 --resource-group myResourceGroup --location eastus --name vm-azuretraining-704

```

```

```




