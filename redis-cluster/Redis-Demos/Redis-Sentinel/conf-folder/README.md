kubectl create configmap -n default redis-config --from-file=redis-config=redis.conf
kubectl create configmap -n default redis-config-slave --from-file=redis-config=redis-slave.conf

