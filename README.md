# Helm app

#### Start by containerize the application https://github.com/tradebyte/DevOps-Challenge

```
![alt](./screenshots/1.png)

```

### Create helm chart

```
helm create web-app
```

### run chart on minikube

```
helm install webapp ./web-app
```

![alt](./screenshots/2.png)

### Run the python application

![alt](./screenshots/3.png)

### Cleaning up

```
helm delete webapp
```
## Deploy jenkins 

### Add repo
```
helm repo add jenkins https://charts.jenkins.io
helm repo update
```
### install jenkins

```
helm install jenkins jenkins/jenkins
```

### output
![alt](./screenshots/4.png)

![alt](./screenshots/5.png)

