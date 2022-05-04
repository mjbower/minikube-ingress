# minikube-ingress
example minikube ingress

   # minikube config set vm-driver [driver_name]
   # minikube start --driver=virtualbox

    minikube start --cpus 2 --memory 4906
    # Enable dashboard
    minikube addons enable dashboard
    # minikube dashboard --url

    # Enable ingress
    minikube addons enable ingress

    # get external IP
    minikube ip

    # Create an ingress that points at this IP
