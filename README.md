
## To run colima with kubernetes
colima start  --with-kubernetes --network-address

## To port forward to a service ( HostPort : ContainerPort)
kubectl port-forward svc/my-service  3005:3000