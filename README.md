create a aws account
open elastic kubernetes service(EKS) and create an eks cluster.
Create VPC using Cloud Formation because default vpc not recommendent.
Create IAM role for EKS worker nodes (usecase as EC2) with below policies.
Create Worker Node Group.
Once Node Group added then check nodes in K8s_client_machine .
Go to the Istio release page to download the installation file for your OS, or download and extract the latest release automatically.
Install Istio.
Add a namespace label to instruct Istio to automatically inject Envoy sidecar proxies when you deploy your application later.
Deploy the Bookinfo sample application.
The application will start. As each pod becomes ready, the Istio sidecar will be deployed along with it.
Open the application to outside traffic.
Determining the ingress IP and ports.
Verify the external access.
View the dashboard.
