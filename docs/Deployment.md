# Deployment Commands

- Create a deployment: `kubectl create deployment my-dep --image=busybox`
- Create a deployment named my-dep that runs the busybox image and expose port 5701: `kubectl create deployment my-dep --image=busybox --port=5701`
- Create a deployment with replicas: `kubectl create deployment my-dep --image=nginx --replicas=3`

```shell
k create -f minimal.yaml
```
