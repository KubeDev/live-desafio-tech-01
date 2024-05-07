# Desafio Técnico: Implementação de um Cluster Kubernetes com Terraform e Automação via GitHub Actions

## Esse desafio foi resolvido na live abaixo:

https://www.youtube.com/watch?v=OhV-pXgeVq4

## Contexto
Mr. Fusion Solutions, uma startup de tecnologia inovadora no campo de energia, está buscando expandir suas operações e precisa melhorar a qualidade e eficiência de seus processos de desenvolvimento e deployment dos seus softwares. A empresa deseja implementar uma base escalável e robusta usando Kubernetes, que possa suportar o rápido crescimento e a necessidade de atualizações contínuas de suas aplicações.
E foi definido que você será essa pessoa que vai entregar essa solução escalável para a Mr. Fusion Solutions.

## Objetivo

O objetivo deste desafio é criar um projeto para provisionar um cluster Kubernetes na AWS usando o Amazon EKS (Elastic Kubernetes Service) de forma automatizada. Após a criação do cluster, você deverá configurar uma pipeline usando GitHub Actions que automatize o processo de criação e manutenção desse cluster Kubernetes. Com o objetivo de suportar a escala de diversos microsserviços da Mr. Fusion Solutions.

## Etapas do projeto

1. **Criação do Cluster Kubernetes:**
   - Utilize Terraform para criar um cluster Kubernetes usando Amazon EKS.
   - O cluster deve ter no mínimo dois nós de worker node.

2. **Pipeline com GitHub Actions:**
   - Desenvolva uma pipeline utilizando GitHub Actions.
   - A pipeline deve ser executada sempre que houver alteração na base do projeto Terraform.

3. **Documentação:**
   - Documente o processo de criação e os requisitos necessários para inicializar e gerenciar o cluster.
   - Inclua possíveis melhorias no projeto.

## Critérios de Avaliação

- Modo de Implementação: O cluster Kubernetes deve ser inicializado corretamente e atender os requisitos.
- Qualidade do Código: O código Terraform deve ser claro, bem organizado e seguir as melhores práticas de desenvolvimento e reaproveitamento.
- Funcionalidade da Pipeline: A pipeline de deve funcionar sem erros, realizando todas as tarefas especificadas.
- Documentação: A documentação deve ser completa, clara e fornecer todos os detalhes necessários para que outros profissionais possam reproduzir o processo.
