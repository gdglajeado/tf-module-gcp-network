# Google Instances Terraform module

Simples Módulo para Terraform que cria redes no Google Cloud Platform.

## Terraform versão

Terraform > 0.12.19

Esta definição encontra-se no arquivo `versions.tf`

## Como utilizar

```hcl
module "instance" {
  source = "git@github.com/gdglajeado/tf-module-gcp-network.git?ref=v1.0"

  name                    = "rundeck"
  description             = "Rede para o projeto Rundeck"
  auto_create_subnetworks = false
}
```