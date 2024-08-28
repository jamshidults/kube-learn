# kube-learn
minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]" --driver=hyperv 
minikube start --extra-config "apiserver.cors-allowed-origins=["http://boot.dev"]" --driver=docker
minikube stop
minikube delete --all