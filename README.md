# k8s-starter

1.	Install<br>
`curl -LO https://storage.googleapis.com/minikube/releases/latest/minikube_latest_amd64.deb` <br>
`sudo dpkg -i minikube_latest_amd64.deb`

2.	`minikube start`

3.	`minikube kubectl -- get po -A`

4.	`minikube dashboard`

5.	`kubectl proxy --address 0.0.0.0 --port=9000 --accept-hosts '.*'`

#### https://minikube.sigs.k8s.io/docs/start/
