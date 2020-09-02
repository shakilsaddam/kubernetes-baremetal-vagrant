# kubernetes-baremetal-vagrant
1  kubectl get nodes
    2  kubectl get nodes -o wide
    3  kubectl get pods --all-namespaces
   12  kubectl get services
   13  curl 172.42.42.100:32615
   14  kubectl get services -o wide
   30  curl 172.42.42.101:31000
   43  kubectl delete deploy/myapp-deployment
   45  kubectl delete services my-service
   56  kubectl create -f deployment-definition.yml 
   59  kubectl get rc
   60  kubectl get all
   74  kubectl apply -f deployment-definition.yml 
   77  curl http://localhost:31000
   86  kubectl get namespaces
   87  kubectl apply -f https://raw.githubusercontent.com/google/metallb/v0.7.3/manifests/metallb.yaml
   91  kubectl api-versions
   95  kubectl apply -f metllb.yml 
   97  kubectl get all -n metallb-system
   98  kubectl get nodes -o wide
   99  sudo vim metllb-configmap.yml
  100  kubectl apply -f metllb-configmap.yml 
  101  kubectl describe configmap config -n metllb-system
  102  kubectl describe configmap config -n metallb-system
  116  kubectl create -f service-myapp-metallb.yml 
  117  kubect get all
  118  kubectl get all
  119  curl 10.109.135.9
  120  curl 10.109.135.9:8080
  126  kubectl apply -f deployment-definition.yml 
  137  kubectl delete service/my-service-metallb
  138  kubectl create -f service-myapp-metallb.yml 
  140  kubectl describe configmap config -n metallb-system
  151  git init
  152  sudo git init
  155  sudo git add .
  156  git commit
  157  sudo git commit
  158  sudo git commit -m "Initial commit: Bare Metal kubernetes cluster setup on ubuntu20.04 using Vagrant"
  159  sudo git remote add origin git@shakilsaddam
  161  sudo git remote add origin git@github.com:shakilsaddam/kubernetes-baremetal-vagrant
  162  sudo git push -u origin master
  163  sudo git config
  164  sudo git --show-origine
  165  sudo git --show-origin
  166  sudo git remote -v
  167  sudo git remote show origin
  168  sudo git remove
  169  sudo git remote rm
  170  sudo git remote -v
  171  sudo git remote rm git@shakilsaddam
  172  sudo git remote -v
  173  sudo nano .git/config 
  174  sudo git remote rm origin
  175  sudo git remote -v
  176  sudo git remote add origin git@github.com:shakilsaddam/kubernetes-baremetal-vagrant
  177  sudo git push -u origin master
  178  sudo git remote rm origin
  179  sudo git remote add origin git@github.com:shakilsaddam/kubernetes-baremetal-vagrant.git
  180  sudo git push -u origin master
  182  sudo nano .git/config 
  183  sudo git remote -v
  184  sudo git push -u origin master
  187  sudo git push -u origin master
  188  sudo git pull
  189  sudo git remote master
  190  sudo git pull remote master
  191  sudo git pull master
