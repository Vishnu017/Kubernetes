
## To run colima with kubernetes
colima start  --with-kubernetes --network-address

## To port forward to a service ( HostPort : ContainerPort)
kubectl port-forward service/my-express-service  3005:3000


## to install a command like ping inside a container
apt-get update && apt-get install -y iputils-ping
