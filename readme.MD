* In this, I have taken example of mysql and backend .
* Used helm charts to deploy them. Also used replica set and image tags. 
* Screenshots of logs and describe pods are attached below.

First we are creating namespace
Kubectl create namespace expense

For every helm deployment we have Chart.yaml, values.yaml and templates folder which are mandatory.

The Chart.yaml file is the metadata file of a Helm chart. It contains information that defines the chart, such as its name, version, description, and dependencies.
The values.yaml file is where you define the default values for the variables used in your Helm chart’s templates. This allows users to customize their deployments when installing the chart by overriding the default values.
The templates contains Kubernetes resource manifests. These files define the actual Kubernetes objects (such as Deployments, Services) that will be created when the chart is deployed.

Output logs of the mysql helm chart

![40](https://github.com/user-attachments/assets/ef807141-7390-4f67-a628-12c41ae03da0)

![41](https://github.com/user-attachments/assets/b0a555b7-e197-4972-83a7-45d1990c08d3)

![42](https://github.com/user-attachments/assets/bcb45b1f-e22d-404f-912f-520cce5ccdb7)

Output logs of backend helm chart

![43](https://github.com/user-attachments/assets/17f3074a-bfe2-4d53-a2ed-cee950a2a591)