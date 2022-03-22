# Kubernet Utils
### **set default name space in current context**
kubectl config set-context --current --namespace=mynamespace

### **forward port (set an service too)**
kubectl port-forward mongo-75f59d57f4-4nd6q 28015:27017