# dk8s
Day 1 of the Descomplicando Kubernetes course DK8s
Commands learned
kubectl get nodes
kubectl get pods

alias k=kubectl

dry-run simulated a command, this is useful to output a yaml file for pod creation, on this example it outputed to pod.yaml
k run --image nginx --port 80 giropops --dry-run=client -o yaml > pod.yaml
