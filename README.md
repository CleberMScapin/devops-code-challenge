# Code Challenge DevOps Kanastra
Os requisitos são os seguintes:
* Escolha uma ferramenta de CI/CD apropriada.
* Configure um pipeline de build de contêiner docker da aplicação node.
* Configure um pipeline de deploy contínuo para o aplicativo de demonstração em contêiner
    * Deve conter pelo menos uma fase de testes e uma fase de deploy.
    * A fase de deploy só deve ser executada se a fase de testes for bem-sucedida.
    * Ele deve seguir o fluxo do GitHub flow para o deploy.
    * O deploy deve ser feito no cluster k8s provisionado no Code Challenge.


## Aplicação

A aplicação node é super simples, apenas um express que expõe webserver HTTP na port 3000

Os endpoints são os seguintes:
- `/`
- `/health/check`

## Bonus

- Adicionar pipelines para teste lint, e outras coisas a mais na aplicação
- O deploy de kubernetes tiver interligado com ferramenta de infra as code
