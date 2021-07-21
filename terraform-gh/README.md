# Github version

This alternate version of the stack uses a *GitHub* repo as source instead of AWS CodeCommit. This makes use of [AWS CodePipline GitHub connections](https://docs.aws.amazon.com/codepipeline/latest/userguide/connections-github.html).

## Assumptions

The Terraform stack assumes that a *GitHub* repo has already been created.

## Configuration variables

Edit `terraform.tfvars` and on the line

```
source_repo_id="<insert your repo id here>"
```

replace the value with your full repo id. For example, if your github account is "joebloggs" and your repo name is "test", then use "joebloggs/test".


wget https://releases.hashicorp.com/terraform/1.0.2/terraform_1.0.2_linux_amd64.zip

unzip terraform_1.0.2_linux_amd64.zip




