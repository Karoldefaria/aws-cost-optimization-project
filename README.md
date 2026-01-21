# aws-cost-optimization-project
# Projeto AWS – Otimização de Custos e Arquitetura em Nuvem

## 📌 Desafio DIO
Este projeto foi desenvolvido como parte de um desafio prático da DIO, com foco na aplicação dos conceitos de **Computação em Nuvem, AWS e Arquitetura de Soluções**, visando a **redução imediata de custos operacionais**, escalabilidade e boas práticas.

O objetivo é demonstrar domínio conceitual e capacidade de tomada de decisão técnica, indo além da simples utilização de serviços.

---

## 🎯 Objetivo
Projetar e documentar uma solução em AWS utilizando **três serviços principais**, escolhidos estrategicamente para:
- Reduzir custos
- Automatizar escalabilidade
- Aumentar eficiência operacional
- Seguir boas práticas de arquitetura em nuvem

---

## 🧱 Serviços AWS Utilizados

### 1️⃣ Amazon EC2 Auto Scaling
**Função:** Escalabilidade horizontal automática  
**Benefício:**  
Ajusta a quantidade de instâncias conforme a demanda, evitando recursos ociosos e reduzindo custos em períodos de baixa utilização.

---

### 2️⃣ Amazon S3 com Intelligent-Tiering
**Função:** Armazenamento de objetos com otimização automática  
**Benefício:**  
Move os dados entre camadas de armazenamento conforme o padrão de acesso, reduzindo custos sem necessidade de intervenção manual.

---

### 3️⃣ Amazon RDS (Gerenciado)
**Função:** Banco de dados relacional gerenciado  
**Benefício:**  
Elimina custos operacionais com manutenção, backups e patches, garantindo alta disponibilidade e recuperação de desastres.

---

## 🗺️ Arquitetura Proposta
A solução utiliza uma **VPC** com separação entre sub-redes públicas e privadas, garantindo segurança, organização e escalabilidade.

- Camada Web: EC2 + Auto Scaling
- Armazenamento: Amazon S3
- Banco de Dados: Amazon RDS (sub-rede privada)

---

## 📁 Estrutura do Repositório

