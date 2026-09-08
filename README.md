# HumanGov Infrastructure

Projeto de Infrastructure as Code (IaC) desenvolvido com Terraform e AWS para provisionamento automatizado de recursos em nuvem.

## Objetivo

Este projeto faz parte da iniciativa HumanGov e tem como objetivo demonstrar práticas modernas de Cloud Computing, DevOps e automação de infraestrutura utilizando Terraform e serviços AWS.

## Tecnologias Utilizadas

- Terraform
- AWS EC2
- AWS S3
- AWS DynamoDB
- Git
- GitHub

## Arquitetura


┌─────────┐
│ GitHub  │
└────┬────┘
     │
     ▼
┌───────────┐
│ Terraform │
└─────┬─────┘
      │
      ▼
┌─────────────── AWS ───────────────┐
│                                   │
├── S3        → Terraform State     │
├── DynamoDB  → State Locking       │
└── EC2       → Compute Resources   │
│                                   │
└───────────────────────────────────┘

## Funcionalidades

- Provisionamento automatizado de infraestrutura
- Backend remoto para Terraform State
- State Locking com DynamoDB
- Arquitetura escalável
- Versionamento da infraestrutura como código

## Estrutura do Projeto


terraform/

## Status

🚀 Projeto em evolução contínua.

## Autor

Eduardo Silva Carvalho

Engenheiro de Produção | Estudante de Tecnologia da Informação | Especialização em MultiCloud | Cloud Computing | DevOps | Infraestrutura como Código

