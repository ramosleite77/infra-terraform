# Infra Terraform

Descrição Atual: Repositório para armazenar o código de Infraestrutura como Código (Terraform) para provisionar os recursos na AWS.

Objetivo Principal: Este repositório encapsula os arquivos de configuração do Terraform necessários para provisionar automaticamente toda a infraestrutura na AWS, garantindo consistência e escalabilidade.
Abordagem Arquitetural:
Recursos de infraestrutura: Inclui relatórios para configurar bancos de dados, containers no ECS ou EKS (Kubernetes) e ajuste de redes privadas (VPCs).
Escopos possíveis: Ambientes isolados para desenvolvimento (dev), homologação (staging) e produção (prod).
Automação no CI/CD: Por ser público, pode ser integrado diretamente em pipelines do GitHub Actions para aplicar alterações em tempo real usando terraform apply.


Relevância:
Base para todos os demais microsserviços, sendo responsável pela resiliência e disponibilidade operacional.
O único repositório público, possivelmente sem dados críticos armazenados por questões de segurança.
