In this, I have taken example of mysql and backend . used helm charts to deploy them. Also used replica set and image tags. Screenshots of logs and describe pods are attached below.

First we are creating namespace
Kubectl create namespace expense

For every helm deployment we have Chart.yaml, values.yaml and templates folder which are mandatory.

The Chart.yaml file is the metadata file of a Helm chart. It contains information that defines the chart, such as its name, version, description, and dependencies.
The values.yaml file is where you define the default values for the variables used in your Helm chart’s templates. This allows users to customize their deployments when installing the chart by overriding the default values.
The templates contains Kubernetes resource manifests. These files define the actual Kubernetes objects (such as Deployments, Services) that will be created when the chart is deployed.

Output logs of the mysql helm chart

--
--
--

Output logs of backend helm chart

--
--