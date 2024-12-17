This is  my protfolio repository
My plan are as below:
Create GitHub account with necessary repositories created by cli
Plan Terraform architecture
create EKS , s3 bucket with event notifications that trigger lambda function to pour load the file into amazon RDS MySQL database.
create Jenkins pipeline and use GitHub plugin
create docker image
write the sh script for pushing the image into docker registry
and write the Kubernetes YAML configuration file for the deployment.


Micro services architecture
micro arch - 1 creating lambda function that was triggered from s3 when something is poured
micro arch - 2 - application front end
micro arch - 3 - backend creation with route 53 alias endpoints website hosting

CI/CD Flow :

VCS - GitHub --> Jenkins/githubactions (ccontinuous Integration) --> Frontend code build in node / Backend code build in maven --> Build success --> Terraform architecture creation in AWS (optional)--> Image build in docker --> puch in Docker registry --> Deploy in kubernetes 
