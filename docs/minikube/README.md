# Common Commands

- Start minikube: `minikube start`
- Halt the cluster: `minikube stop`
- Pause Kubernetes without impacting deployed applications: `minikube pause`
- Unpause a paused instance: `minikube unpause`
- Delete all of the minikube clusters: `minikube delete --al`
- See minikube pods in cluster: `kubectl get po -A`
- Alias minikube kubectl: `alias kubectl="minikube kubectl --"`

# Minikube Add-Ons

## Using A Private Registry
- Register credentials for GCR: 
  - `minikube addons configure registry-creds`
  - `minikube addons enable registry-creds`
  - `minikube addons enable gcp-auth`

