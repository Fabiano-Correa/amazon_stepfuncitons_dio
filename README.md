# Resumo Amazon Step Funcion

O step function é um recurso da AWS utilizado em diversas empresas e tem como principal objetivo a facilitação de exeuções de tarefas passo a passo. Com poucos clicks é possível criar um workflow sem a necessidade de programação, isso se torna possível pois o step functions se propões a ser uma ferramenta low code.

A linguagem utilizada é o ASL, uma linguagem baseada em JSON que facilita a criação e configuração das tarefas.

A ferramenta possui diversos fluxos pré definidos proporcionando ao usuário a opção de adicionar ou remover etapas e ferramentas ou até mesmo criar um workflow do absoluto zero.

Em termos de precificação a AWS cobra pela execução dos serviços utilizados pelo Step Funcion, exemplo: S3, Bedrock, etc.

Além disso, para que o workflow funcione é necessário configurar permissões de usuários(o step function utiliza um usuário específico para cada serviço) bem como escolher os recursos disponíveis na região em que estou executando o Workflow.

