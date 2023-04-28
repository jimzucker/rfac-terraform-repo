# Support repository for RFAC Infra Foundation Project
This repository contains code from open source project that is used in rfac-infra repository code.

_Note: In order for the repo to work as a helm repository, GitHub pages need to be turned on. Please don't change this seeting._

## Software and versions
### Helm Charts
| Chart name                    | Version       | License       | Source link                                                                          |
| ----------------------------- | ------------- | ------------- | ------------------------------------------------------------------------------------ |
| AWS Load Balancer Controller  | 1.4.8         | Apache 2.0    | https://github.com/aws/eks-charts/tree/v0.0.128/stable/aws-load-balancer-controller  |
| Jenkins                       | 4.3.8         | Apache 2.0    | https://github.com/jenkinsci/helm-charts/tree/jenkins-4.3.8                          |

### Terraform modules
| Module name                   | Version       | License       | Source link                                                                    |
| ----------------------------- | ------------- | ------------- | ------------------------------------------------------------------------------ |
| AWS EKS Terraform module      | 18.28.0       | Apache 2.0    | https://github.com/terraform-aws-modules/terraform-aws-eks/tree/v18.28.0       |