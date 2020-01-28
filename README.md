# NEO Airlines Case Study by Ibrahim Dauda.
## Container CI/CD using Jenkins and Kubernetes on Azure Container Service (AKS)

<a href="https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fraw.githubusercontent.com%2Fibrolive%2Fneo-airlines-jenkins-ci-cd-azure-kubernetes%2Fmaster%2Fazuredeploy.json" rel="nofollow">
<img src="https://raw.githubusercontent.com/ibrolive/neo-airlines-jenkins-ci-cd-azure-kubernetes/master/images/deploytoazure.png" style="max-width:100%;">
</a>

<a href="http://armviz.io/#/?load=https%3A%2F%2Fraw.githubusercontent.com%2Fibrolive%2Fneo-airlines-jenkins-ci-cd-azure-kubernetes%2Fmaster%2Fazuredeploy.json" rel="nofollow">
<img src="https://raw.githubusercontent.com/ibrolive/neo-airlines-jenkins-ci-cd-azure-kubernetes/master/images/visualizebutton.png" style="max-width:100%;">
</a>

## Architecture Diagram

![](images/architecture.png)

1. Change application source code.
2. Commit code to GitHub.
3. Continuous Integration Trigger to Jenkins.
4. Jenkins triggers a build job using Azure Container Service (AKS) for a dynamic build agent.
5. Jenkins builds and pushes Docker container to Azure Container Registry.
6. Jenkins deploys new containerized app to Kubernetes on Azure Container Service (AKS) backed by Azure Cosmos DB.
7. Grafana displays visualization of infrastructure and application metrics via Azure Monitor.
8. Monitor application and make improvements.


