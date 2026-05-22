# Deployment

kubectl apply -f kubernetes/

Verify:

kubectl get pods -n nexoryx-datalake
kubectl get svc -n nexoryx-datalake
kubectl get ingress -n nexoryx-datalake
