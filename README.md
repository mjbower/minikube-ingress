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

## Deploy
'''bash
kubectl apply -f https://raw.githubusercontent.com/mjbower/minikube-ingress/main/k8s/apples.yaml
'''


'''bash
kubectl apply -f https://raw.githubusercontent.com/mjbower/minikube-ingress/main/k8s/bananas.yaml
'''

'''bash
kubectl apply -f https://raw.githubusercontent.com/mjbower/minikube-ingress/main/k8s/ingress.yaml
'''
