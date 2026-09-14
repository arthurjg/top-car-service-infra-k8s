# top-car-service-infra-k8s

![Docker](https://img.shields.io/badge/Docker-Enabled-blue)
![Kubernetes](https://img.shields.io/badge/Kubernetes-Enabled-blue)
![Terraform](https://img.shields.io/badge/Terraform-Enabled-purple)

## Propósito

infra cloud terraform/kubernetes do do app da officina

## Técnologias

- **Docker**
- **Kubernetes**
- **Terraform**
- **Github Actions**

## Passos para execução e deploy

### 1.1. Execução Local

* Clone e Execução  do repositório:
```bash
git clone https://github.com/arthurjg/top-car-service-infra-k8s
cd top-car-service-infra-k8s
terraform init
terraform plan
terraform apply
```

### 1.2. Deploy

- commitar o código e fazer push na branch release/**

## Arquitetura

![arquitetura](/docs/top-car-service-k8s-aws.drawio.png)
