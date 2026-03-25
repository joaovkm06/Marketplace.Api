# PROJETO DE SOFTWARE – Marketplace para Microempresas

---

## 👥 Stakeholders

| Nome                     | Cargo/Papel        | E-mail/Contato                     |
|--------------------------|-------------------|------------------------------------|
|       Gilberto           | orientador |       |

---

## 💻 Equipe de Desenvolvimento

| Nome                  | Cargo/Papel   | E-mail/Contato                              |
|-----------------------|--------------|---------------------------------------------|
| João Kmniecik         | Desenvolvedor | joaokmniecik2006@gmail.com        |

---

## 📌 Resumo do Projeto

**Nome:**  
 Market

**Principal Objetivo:**  
Desenvolver uma plataforma web de marketplace para microempresas criarem suas lojas e venderem produtos online.

**Benefícios Esperados:**  
Facilitar vendas, reduzir custos e promover inclusão digital.

**Período:**  
10/02/2026 - 23/06/2026

---

##   Introdução

Com o crescimento do comércio digital, muitas microempresas enfrentam dificuldades para manter uma presença online devido a custos e limitações técnicas. Além disso, podem perder vendas ao não estarem sempre disponíveis para seus clientes.

Diante disso, propõe-se o desenvolvimento de uma plataforma web de marketplace que permita a criação de lojas virtuais de forma simples, acessível e eficiente.

###  Propósito

Este documento descreve os requisitos, estrutura e funcionamento do sistema, servindo como base para desenvolvimento e manutenção.

---

###  Concepção do Sistema

O sistema foi idealizado para atender microempresas que não possuem recursos para manter um site próprio e que perdem vendas ao estarem ausentes fisicamente.

---

###  Descrição Geral

A plataforma permitirá que lojistas criem lojas e cadastrem produtos, enquanto clientes poderão navegar, comprar e avaliar produtos.

---

##  Usuários do Sistema

| Ator        | Descrição |
|-------------|----------|
| Lojista     | Cria loja, gerencia produtos e pedidos |
| Cliente     | Compra produtos e avalia |
| Administrador | Aprova lojas e gerencia sistema |

---

##  Abrangência

Sistema acessível via navegador, sem necessidade de instalação.

---

##  Suposições e Dependências

**Suposições:**
- Acesso à internet  
- Conhecimento básico de uso web  

**Dependências:**
- Node.js  
- MongoDB  
- Navegador moderno  

---

##  Estudo de Viabilidade

**Técnica:** Viável com tecnologias modernas  
**Econômica:** Baixo custo  
**Operacional:** Fácil uso  
**Legal:** Adequado à LGPD  

---

##  Metodologia

Metodologia ágil (Kanban):

- Backlog  
- A Fazer  
- Em andamento  
- Concluído  

---

##  Requisitos Funcionais

| ID    | Descrição |
|-------|----------|
| RF001 | Cadastro e login |
| RF002 | Criação de loja |
| RF003 | Cadastro de produtos |
| RF004 | Listagem de produtos |
| RF005 | Realizar pedidos |
| RF006 | Aprovação de lojas |
| RF007 | Avaliação de produtos |
| RF008 | Gerenciamento de pedidos |

---

##  Requisitos Não Funcionais

| ID    | Descrição |
|-------|----------|
| RNF001 | Sistema responsivo |
| RNF002 | Alta performance |
| RNF003 | Segurança de dados |
| RNF004 | Disponibilidade |

---

##  Casos de Uso

### Lojista
- Criar loja  
- Cadastrar produtos  
- Gerenciar pedidos  

### Cliente
- Navegar produtos  
- Comprar produtos  
- Avaliar produtos  

### Administrador
- Aprovar lojas  
- Gerenciar sistema  

---

##  Especificação de Casos de Uso

### UC-01 – Criar Loja

**Ator:** Lojista  
**Pré-condição:** Usuário logado  

**Fluxo:**
1. Acessa criar loja  
2. Preenche dados  
3. Envia para aprovação  

---

### UC-02 – Comprar Produto

**Ator:** Cliente  

**Fluxo:**
1. Seleciona produto  
2. Adiciona ao carrinho  
3. Finaliza compra  

---

##  Diagramas

- Diagrama de Casos de Uso  
- Diagrama de Classes  
- Diagrama de Sequência  
- Diagrama de Atividades  

---