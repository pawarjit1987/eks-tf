# eks-tf
EKS provisioning using terraform 

### EKS cluster creation

```
terraform init
terraform plan
terraform apply
```
### EKS cluster cleanup
```
terraform destroy
```

### Set Up Secrets in GitHub
Configure AWS Credentials: Go to your repository on GitHub, navigate to Settings > Secrets and variables > Actions, and add the following secrets:

```
1. AWS_ACCESS_KEY_ID
2. AWS_SECRET_ACCESS_KEY
```

### Test the Pipeline
#### Make Changes:
Modify any Terraform configuration in your repository.
#### Push Changes:
Push your changes to the main branch (or the branch you specified).
#### Check Actions:
Go to the Actions tab in your repository to see the workflow in action.