
* Add "Container Orchestration Support" to project choosing "Kubernetes/Helm"
* Build Docker File
* Change the values.yaml according to https://blogs.u2u.be/lander/post/2020/08/14/deploying-an-asp-net-core-container-on-your-local-kubernetes-cluster-using-helm
* helm install webapi .\webapi\
* kubectl get deployments
* kubectl get svc
* http://localhost:30878/weatherforecast
* helm uninstall webapi