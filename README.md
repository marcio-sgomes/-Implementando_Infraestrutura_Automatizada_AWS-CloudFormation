# Implementando Infraestrutura Automatizada com AWS CloudFormation

Repositório criado para documentar o desafio prático do módulo de AWS da DIO, focado na criação e gestão de infraestrutura como código (IaC) utilizando o **AWS CloudFormation**.

---

## 📋 Sobre o Desafio
O objetivo deste projeto é demonstrar a capacidade de automatizar o provisionamento de recursos na AWS de forma repetível e estruturada, utilizando modelos (*templates*) do CloudFormation escritos em formato YAML ou JSON.

---

## 🚀 Tecnologias e Conceitos Utilizados
* **AWS CloudFormation:** Serviço de Infraestrutura como Código (IaC) para modelar e provisionar recursos da AWS.
* **AWS IAM / EC2 / S3** *(Ajusta conforme os recursos que incluíste no teu template)*: Serviços provisionados via stack.
* **Git e GitHub:** Controlo de versões e documentação técnica.

---

## 🛠️ Arquitetura e Implementação

1. **Criação do Template (`template.yaml`):**
   * Definição dos parâmetros, recursos e saídas (*Outputs*).
   * Estruturação limpa seguindo as boas práticas de segurança e arquitetura da AWS.

2. **Criação da Stack:**
   * Submissão do modelo através da consola da AWS ou AWS CLI.
   * Monitorização dos eventos de criação (`CREATE_IN_PROGRESS` -> `CREATE_COMPLETE`).

---

## 📁 Estrutura do Repositório

```text
├── template.yaml       # Ficheiro de configuração do CloudFormation
├── images/             # Capturas de tela do processo e da stack criada
└── README.md           # Documentação técnica do projeto
