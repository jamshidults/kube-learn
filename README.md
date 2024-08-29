# kube-learn
minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]" --driver=hyperv 
minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]" --driver=docker
minikube stop
minikube delete --all


kubectl create deployment synergychat-web --image=bootdotdev/synergychat-web:latest
kubectl get deployments

