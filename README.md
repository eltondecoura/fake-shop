# Dasafio CI/CD - Fake Shop

Criação do Workflow no Github Action

Pipeline CI/CD esta no diretório .github/workflows/.

A açõao que irá disparar o Workflow será o push do código, assim que o push do código for feito o workflow será executado.

### Criação da Pipeline 
 CI:

 Etapas do Pipeline CI

      - Obter Codigo

      - Executar o Login no Docker

      - Executar o Docker Builder

      - Enviar a Imagem Docker para Docker Hub

CD:

Etapas do Pipeline CI

      - Obter Codigo

      - Configurar o Kubeconfig

      - Executar o apply
