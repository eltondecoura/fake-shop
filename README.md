# Dasafio CI/CD - Fake Shop

- Criação do Workflow no Github Action

A açõao que irá disparar o Workflow será o push do código, assim que o push do código for feito o workflow será executado.

### Criação da Pipeline 
 CI:
 Etapas da Pipeline CI
      - Obter Codigo
      - Executar o Login no Docker
      - Executar o Docker Builder
      - Enviar a Imagem Docker para Docker Hub

CD:
Etapas da Pipeline CI
      - Obter Codigo
      - Configurar o Kubeconfig
      - Executar o apply
