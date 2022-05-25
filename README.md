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
 ![image](https://user-images.githubusercontent.com/96286875/168302629-26153a45-6e1f-4cbd-b183-1a58814d42f4.png)
![image](https://user-images.githubusercontent.com/96286875/168302666-d1f1a757-d6fc-44e9-9546-d9f2fd557dbc.png)
![image](https://user-images.githubusercontent.com/96286875/168302690-4891d3d9-0a2a-4a98-9a5f-f3f0bc819796.png)
![image](https://user-images.githubusercontent.com/96286875/168302704-ed8073f9-701a-4bbc-a60d-3ed9ab0388e5.png)
![image](https://user-images.githubusercontent.com/96286875/168302731-04c0c66b-9bb1-429c-a4bd-148ce3c9e0f7.png)
![image](https://user-images.githubusercontent.com/96286875/168302758-6805af38-52dc-4e7e-b66b-0e7fb900d713.png)
![image](https://user-images.githubusercontent.com/96286875/168302796-8139a2cc-5238-46e6-9c5d-9d0a130e2e0c.png)
![image](https://user-images.githubusercontent.com/96286875/168302850-be879f9c-4a01-42da-8d4b-64f6045ed33d.png)
![image](https://user-images.githubusercontent.com/96286875/168302886-4ad9c1e3-5031-4d98-9db1-730e8a429c68.png)
![image](https://user-images.githubusercontent.com/96286875/168302906-9fe60a09-9254-4bce-8ed4-001807f7d453.png)
![image](https://user-images.githubusercontent.com/96286875/168302935-968ad813-d282-4d5d-be1e-97bd669007ea.png)
![image](https://user-images.githubusercontent.com/96286875/168302964-4dc18243-2749-4e3a-81ed-5cd15f5cbba3.png)
![image](https://user-images.githubusercontent.com/96286875/168302996-69e57fda-2fb6-4e7a-a213-465263eef581.png)
![image](https://user-images.githubusercontent.com/96286875/168303063-455e254d-c4eb-46da-a567-c723f141b3a4.png)
![image](https://user-images.githubusercontent.com/96286875/168303113-ef1be8ee-671d-4fbf-ab94-05856fd79996.png)
![image](https://user-images.githubusercontent.com/96286875/168303169-b5f8a206-3de1-44f0-a983-e621cdbe1436.png)
![image](https://user-images.githubusercontent.com/96286875/168303203-01ae1bbd-e093-4039-aebf-72b816165801.png)
![image](https://user-images.githubusercontent.com/96286875/168303236-69fa685e-39d0-40c2-886d-e84a7f7ee390.png)

