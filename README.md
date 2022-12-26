
# Generator express
https://expressjs.com/en/starter/generator.html


# Deploy on azure
https://learn.microsoft.com/vi-vn/azure/app-service/quickstart-nodejs?pivots=development-environment-vscode&tabs=windows

# Start, stop
```bash
az webapp stop --name stevetesting2022 --resource-group stevetesting2022_group
```
# Log in app
https://learn.microsoft.com/en-us/azure/app-service/troubleshoot-diagnostic-logs

## Log in console
```bash
az login

az webapp log tail --name stevetesting2022 --resource-group stevetesting2022_group

```

## Log stream

<img width="1503" alt="image" src="https://user-images.githubusercontent.com/29280957/198686158-dc181b79-6f78-4369-81ff-295768129b2c.png">



## Log in kudu
https://learn.microsoft.com/en-us/azure/app-service/resources-kudu

<img width="1386" alt="image" src="https://user-images.githubusercontent.com/29280957/198688033-96c0bb1b-de8e-4dde-bf7d-2e3e1bd5391a.png">


## Log in account storage

![image](https://user-images.githubusercontent.com/29280957/209083819-cccdbd62-30a1-41fa-abfa-df55aa48f4ff.png)

![image](https://user-images.githubusercontent.com/29280957/209083950-3b7b26b2-8129-4586-8b11-35d114c428fb.png)



# Console 

## ssh by cli
```bash
az webapp ssh --name stevetesting2022 --resource-group stevetesting2022_group
```

## ssh in portail
<img width="1158" alt="image" src="https://user-images.githubusercontent.com/29280957/198689105-294fe106-ec7b-4e94-90c7-4ef29bd33669.png">

## ssh in kudu

<img width="992" alt="image" src="https://user-images.githubusercontent.com/29280957/198689244-a17e4582-a399-42f2-b4c0-989db08d69fa.png">


# Scale 

<img width="1338" alt="image" src="https://user-images.githubusercontent.com/29280957/198696899-d0ad6dd9-83ea-49da-9b88-ec3495d80c76.png">

# Key Vault 
- Protect configuration. Require permission to get value in key vault
https://learn.microsoft.com/en-us/azure/key-vault/secrets/quick-create-node
https://github.com/Azure-Samples/key-vault-node-getting-started







