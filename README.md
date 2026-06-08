# 🏛️ Projeto VOID - Compliance, Quality Assurance e Arquitetura Corporativa

## 🌍 Global Solution 2026.1

---

## 📖 1. Visão Geral do Repositório

Este repositório é dedicado à documentação arquitetural, garantia de qualidade (**QA**) e compliance do **Projeto VOID**.

Ele contém a modelagem oficial da solução estruturada sob o framework **TOGAF**, utilizando a linguagem **ArchiMate** para mapear todas as camadas do sistema, desde a motivação de negócios até a infraestrutura física.

O objetivo desta documentação é garantir a **rastreabilidade total dos requisitos**, a conformidade com as leis de proteção de dados (**LGPD**) e a validação técnica da topologia em nuvem.

---

## 📂 2. Conteúdo do Repositório

### 📄 Arquivos

* `GS-VOID.archimate` → Arquivo de modelo arquitetural completo, visualizável através da ferramenta **Archi**.

---

## 🏗️ 3. Mapeamento Arquitetural (TOGAF)

O modelo `GS-VOID.archimate` está dividido nas seguintes camadas de conformidade:

### 🎯 3.1 Motivação e Negócios (Business & Motivation)

#### Objetivo Principal

Mapear o limite físico exato do paciente para evitar lesões durante a reabilitação.

#### Diretriz de Qualidade (Driver)

* Telemetria Biométrica Extrema (Padrão ISS)

#### Atores

* Pacientes
* Fisioterapeutas
* Gestores Clínicos

#### Processos Mapeados

* Preparação de planos de tratamento
* Realização de sessões de reabilitação
* Análise dos dados capturados pelos sensores

---

### 💻 3.2 Camada de Aplicação (Application)

A arquitetura de software foi validada para garantir **alta coesão** e **baixo acoplamento**.

#### Frontend

* Single Page Application (SPA)
* React
* TypeScript
* Vite

#### Backend

* API REST
* Java
* Quarkus

#### Inteligência

* Módulo de IA para Análise Espacial Biométrica

#### Persistência

* Banco de Dados Oracle isolado

---

### 🔒 3.3 Compliance e Segurança (Security)

#### Proteção de Dados

Implementação rigorosa do módulo de autenticação e segurança utilizando:

* JWT (JSON Web Token)
* Diretrizes da LGPD

Proteção aplicada aos seguintes ativos:

* Dados Clínicos do Paciente
* Dados Brutos dos Sensores

#### Tráfego Seguro

Toda comunicação externa é protegida por:

* TLS 1.3
* HTTPS
* Proxy Reverso Nginx

---

### ☁️ 3.4 Tecnologia e Infraestrutura (Technology)

A topologia de QA valida o cumprimento da restrição de custos (**baixo custo**) mantendo alta disponibilidade.

#### Nuvem

* Azure Virtual Machine Linux B2s
* Região: `canadacentral`

#### Sistema Operacional

* Ubuntu Linux 22.04 LTS

#### Orquestração

Ambiente totalmente contêinerizado utilizando:

* Docker Engine 24
* Docker Compose

Isolamento dos serviços:

* Quarkus
* Vite
* Oracle Database

---

## 🚀 4. Como Visualizar a Arquitetura

### Passo 1

Faça o download e instale a ferramenta open-source **Archi**.

### Passo 2

Clone este repositório em sua máquina local.

### Passo 3

Abra o Archi e carregue o arquivo:

```text
GS-VOID.archimate
```

### Passo 4

Navegue pela pasta **Views** para abrir o diagrama:

```text
VOID – Arquitetura Completa TOGAF/ArchiMate
```

---

## ✅ 5. Padrões de Qualidade Atingidos

### 🔍 Rastreabilidade

Demonstração visual de como os sensores físicos (**IoT**) conectam-se até o banco de dados Oracle, permitindo rastrear todo o fluxo de dados da solução.

### 🛡️ Segurança Designada

A separação de redes:

* Wi-Fi Local
* Internet (TLS)

aliada à autenticação na borda, garante um sistema:

* Auditável
* Seguro
* Compatível com dados sensíveis de saúde

---

## 👥 Integrantes da Equipe

| Nome                             | RM     |
| -------------------------------- | ------ |
| Pedro Henrique Luiz Alves Duarte | 563405 |
| Guilherme Macedo Martins         | 562396 |
| Henrique Martins Oliveira        | 563620 |

---

## 📚 Frameworks e Padrões Utilizados

* TOGAF
* ArchiMate
* LGPD
* JWT
* TLS 1.3
* Docker
* Docker Compose
* Azure Cloud
* Oracle Database
* Quarkus
* React
* TypeScript
* Vite
