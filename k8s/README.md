kubectl create configmap config --from-file config.properties
kubectl create configmap config-redis --from-file config-redis.properties
kubectl port-forward conductor-server-79df5d8d75-52pjr 8080
kubectl port-forward conductor-ui-55cc6bb9c8-6z8k8 5000
