# cluster-hpa

## Estrutura das pastas

```bash
cluster-hpa
  |__ eks
  |    |__ eks-cluster-role-trust-policy.json
  |
  |__ minikube
       |__ deployment.yaml
       |
       |__ service.yaml
       |
       |__ hpa.yaml
```

### eks
Esta pasta contem o arquivo **eks-cluster-role-trust-policy.json ** usado para criar o perfil IAM que contem as políticas de gerenciamento necessárias para criar o cluster EKS.

### minikube
Esta pasta contem os arquivos em formato yaml que são necessarios para a implantação do cluster e autoescalametno horizontal.