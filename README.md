# VectorCast HelmChart for Kubernetes Deployment

**Below are the Helm Commands:**

**To Check the Version:**
```helm version```

**To create helm chart:**
```helm create <Chart_Name>```

**To get the structure of the helloworld chart:**
```tree <Chart_Name>```

**To validate YAMLs without connecting to K8S api server:**
```helm template <Chart_Name>```


**To validate YAMLs without connecting to K8S api server:**
```helm install <Deployment_Name> --debug --dry-run <Chart_Name>```

**To deploy the helm chart:**
```helm install <Deployment_Name> <Helm_Chart_Name>```

**To see the list of files:**
```helm list -a```

**To access the application, Copy the External_IP after providing this command:**
```kubectl get all```

**To check our application:**
```http://<External_IP>:<Port>``` 

**To upgrade the existing deployed Helm Chart:**
```helm upgrade <Deployed_name> <Chart_Name>```

**To install Hell Diff plugin:**
```helm plugin install https://github.com/databus23/helm-diff```

**To see the list of plugin's:**
```helm plugin list```

**To check the Previous and latest version code:**
```helm diff revision <Deployed_name> <revision_num> <revision_num>```

**To Rollback to Previous Version:**
```helm rollback <Deployed_Name> <revision_num>```


# Step by step helloworld HelmChart Deployment Process:
 ![image](https://user-images.githubusercontent.com/83760515/168247169-c0dd805c-aa9d-4549-8c7a-c2607a371c65.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247186-5cab4388-c9ee-4fa4-93c1-1bdd21230739.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247201-10c8a9b0-1265-4012-ac18-a126ab58c57b.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247215-6d79cf20-4d59-419c-965d-000e184a132d.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247249-7df5bc8e-c0c3-4460-aaf6-df21231bc901.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247263-e278bddb-eeba-4984-a24c-3e891ac457c0.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247266-14a93e42-365b-4721-9921-9907c251d46e.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247296-68d15dd6-812d-4985-8e3b-ea4f51685356.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247323-e963d9da-5c74-4997-b8a6-39135fa91d25.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247342-9eaec8c1-56dc-45a8-9922-39d8fbb54443.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247382-aa83082e-8484-448e-9c9a-d5b9e57f33bd.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247398-88290112-b315-4f5a-966d-8fc42c3a9814.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247425-7d10ce8e-74e7-4e68-89c9-0ae401a83c6a.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247441-959c6958-0d33-4546-93a2-4ae2c5f8d8a3.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247456-b6505fde-7314-4578-84b9-04fa7cc87819.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247465-fd1f5cb4-326a-47c6-a8ed-49a54c839266.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247477-8dd5a4c8-ff10-459c-bd58-46e16fe031fd.png)

 ![image](https://user-images.githubusercontent.com/83760515/168247500-caafa48c-3089-4e01-bc93-dd2830578368.png)


