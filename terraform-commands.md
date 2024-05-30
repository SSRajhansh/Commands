### Basic Terraform Commands

| Command | Description |
| ------- | ----------- |
| `terraform plan` | To get plan before execution. |
| `terraform plan -var "varName=varValue"` | To get plan before execution with variables. |
| `terraform init` | To download and initialize the plugin before execution. |
| `terraform validate` |  To validate if create tf files are correct with reference. |
| `terraform fmt` |  Use this command for tf files contents formatting. |
| `terraform apply` |  To execute the command and create resource on provider. |
| `terraform apply --auto-approve` |  To execute the command and create resource on provider with accepted approval. |
| `terraform destroy` |  To destroy created resource on provider. |
| `terraform refresh` |  To update/refresh the state file which was manually updated on resource. |
| `terraform output` |  To get the output of the resource attributes. |
| `terraform console` |  To provides an interactive console for evaluating expressions. |
| `terraform providers` |  To shows all the providers required by configuration. |


### Reference: 
[Terraform Configuration Language](https://developer.hashicorp.com/terraform/language)
[Tutorial](https://learning-ocean.com/tutorials/terraform/terraform-what-why-and-how/)
[Video Tutorial](https://youtube.com/playlist?list=PL6XT0grm_TfgdaAjTmLb4QedMCCMQHISm&si=I4GKjGcTrGFLqkgy)
