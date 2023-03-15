# k8s-starter

1.	`curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb` <br>
2. `sudo dpkg -i minikube_latest_amd64.deb`

3.	`minikube start`

4.	`minikube kubectl -- get po -A`

5.	`minikube dashboard`

6.	`kubectl proxy --address 0.0.0.0 --port=9000 --accept-hosts '.*'`
