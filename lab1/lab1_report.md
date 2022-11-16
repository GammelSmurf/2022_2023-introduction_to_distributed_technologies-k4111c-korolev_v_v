**Lab1: Install Docker and minikube. My first manifest.**

After installing a minikube it was started by *minikube start*, so the cluster was raised.
![img_1.png](assets/img_1.png)
Then a manifest file *vault_pod_manifest.yaml* was created with following content to describe new pod *lab1-vault-pod*.
```aidl
apiVersion: v1
kind: Pod
metadata:
  name: lab1-vault-pod
  labels:
    app: lab1-vault
spec:
  containers:
    - name: lab1-vault-container
      image: vault
      resources:
        limits:
          memory: "1Gi"
        requests:
          memory: "500Mi"
```
Created earlier manifest file was applied and pod was created successfully.
![img.png](assets/img.png)

Then the service for *lab1-vault-pod* was created. It serves 8200 port.
![img_1.png](assets/img_4.png)

And also local port 8200 was forwarded to a pod same port 8200.
![img_2.png](assets/img_2.png)

Now we can access the vault by *localhost:8200* address.
![](assets/vault_login.png)

To get the access token we should check vault logs. There is a *root token* string with needed value.
![img_3.png](assets/img_3.png)

Using this token it was logged in vault.
![](assets/vault_logged.png)


