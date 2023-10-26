helm install redis-cluster oci://registry-1.docker.io/bitnamicharts/redis-cluster --values redis-cluster/values.yaml -n default
from client user = redis-cli -c -p IP:PORT
