
# App_hello_world_python

Running a Hello World Python Web Application Using the Following Steps:

Containerization: Building a Docker image from a Dockerfile.

Provisioning: Creating a Kubernetes cluster using Terraform, then using kubectl and the AWS CLI to configure the cluster and apply Kubernetes manifest files.

Kubernetes Deployment: Running the application on a Kubernetes cluster by creating Deployment, Service, and Ingress YAML files, and accessing the application through a publicly accessible hostname by mapping the Ingress controller (ALB) address to http://hello-python-app.local/.

Helm: Using Helm charts to deploy Kubernetes manifest files across different environments, including updating the Docker image tag.

CI (Continuous Integration): Implementing CI using GitHub Actions, where changes pushed to the main branch trigger a pipeline that builds a new Docker image, pushes it to Docker Hub, and updates the Helm chart with the new image version.

CD (Continuous Deployment): Using Argo CD to continuously monitor the Helm chart for updates and automatically deploy the latest image version to the Kubernetes cluster.
