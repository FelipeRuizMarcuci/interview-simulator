# 📄 Simulação de Entrevista + Plano de Estudos (Dev Jr NestJS)

---

## 🗣️ Simulação de Entrevista

**Assistant:**
Olá! Vou fazer perguntas sobre a vaga que você está estruturando. Para começar:

**Qual é o título da vaga e qual o propósito principal desse cargo?**

**User:**
Dev Jr NestJS

---

**Assistant:**
Qual é o propósito principal desse cargo?

**User:**
Junior

---

**Assistant:**
Qual a senioridade esperada e por quê?

**User:**
Junior

---

**Assistant:**
Quais tecnologias, frameworks e práticas são essenciais?

**User:**
NestJS, Prisma ORG, typescript e MySQL

---

**Assistant:**
Quais comportamentos ou atitudes são mais valorizados?

**User:**
Comunicação e transparencia

---

**Assistant:**
Qual é o tipo de projeto ou produto em que essa pessoa vai atuar?

**User:**
Manuntenção de um projeto legado

---

**Assistant:**
Qual é o principal desafio técnico ou de negócio dessa vaga?

**User:**
Analisar se o desenvolvedor está apito

---

**Assistant:**
Quem essa pessoa vai impactar diretamente no dia a dia (time, clientes, stakeholders)?

**User:**
Time e clientes

---

**Assistant:**
Perfeito — com base nas suas respostas, aqui está a vaga estruturada 👇

# 🧾 Vaga: Desenvolvedor(a) Júnior NestJS

## 🎯 Propósito da vaga

Atuar na manutenção e evolução de um sistema legado, garantindo estabilidade, melhorias contínuas e suporte às demandas do time e dos clientes.

## 🧠 Senioridade

**Júnior**

Buscamos alguém em início de carreira, com base técnica sólida e potencial de crescimento, capaz de aprender rapidamente e se adaptar a um ambiente com código legado.

## 🛠️ Tecnologias essenciais

- **NestJS**
- **TypeScript**
- **Prisma ORM**
- **MySQL**

## 💡 Principais responsabilidades

- Manutenção e evolução de funcionalidades existentes em sistema legado
- Correção de bugs e melhorias incrementais
- Apoio na análise e entendimento de regras de negócio existentes
- Colaboração com o time técnico para garantir qualidade do código
- Comunicação com o time e, quando necessário, apoio em demandas relacionadas a clientes

## ⚠️ Principais desafios

- Trabalhar com código legado (estrutura nem sempre ideal)
- Entender regras de negócio já existentes
- Demonstrar capacidade técnica suficiente para atuar com autonomia progressiva

## 🤝 Soft skills valorizadas

- Comunicação clara
- Transparência no dia a dia
- Proatividade para tirar dúvidas
- Organização

## 🎯 Impacto da função

Essa posição impacta diretamente:

- O **time de desenvolvimento**
- Os **clientes**

## 🔍 O que vamos avaliar

- Capacidade de entender e trabalhar com código existente
- Base sólida em Node.js / TypeScript
- Raciocínio lógico
- Clareza na comunicação
- Potencial de crescimento

---

**User:**
Preciso que me entreviste para a vaga

---

**Assistant:**
Perfeito — vamos simular uma entrevista real 👇

**Regras:**

- Vou fazer 1 pergunta por vez
- Vou avaliar como recrutador técnico
- Seja direto

## 🎤 Pergunta 1

Me conte brevemente sobre você e sua experiência com NestJS, TypeScript e banco de dados.

---

**User:**
Fui dev para diversos projetos, incluindo um gerador de documentos de uma empresa de advocacia médica. Fiz todo o backend e configuração do banco de dados

---

**Assistant:**
Boa — resposta direta, isso é positivo 👍

## 🎤 Pergunta 2

Como você estruturou o backend com NestJS?

---

**User:**
Utilizando o Prisma ORM

---

**Assistant:**
Boa — mas resposta fraca para entrevista ⚠️

## 🎤 Pergunta 3

Como você organizaria um projeto NestJS para manutenção de um sistema legado?

---

**User:**
A estruturação de pastas deve ser com base no que é necessitado como endpoint, como por exemplo a parte de "Usuários":

- A pasta principal teria o nome "user"
- Dentro dessa pasta teria todo o escopo, no caso: user.module, user.controller e user.service
- Como o endpoint nesse caso entraria como um CRUD, ele precisaria ter uma pasta chamada entities ou DTO, para conter o Body da requisição.

Em um sistema desses, é necessário ter um cargo para cada usuário, dependendo de quantos acessos ele pode ter. Nesse caso, o banco de dados consegue cuidar do "role" e juntamente com o "Guard", é possível fazer essa separação de responsabilidade de cada usuário.

Para não bagunçar o código original, seria interessante criar novas pastas e funções com base no que é necessário

---

**Assistant:**
Boa resposta. Você mostrou noção de organização por feature.

## 🎤 Pergunta 4

Como você investigaria um bug de dados incompletos no banco?

---

**User:**
Investigar o problema é simples: debugar.
Em NestJS, o melhor jeito para debugar é a utilização do console.log(), para ele retornar no terminal as informações que você quer passar.
Porém, esse bug de dados incompletos geralmente ocorre entre dois fatores:

- Informações obrigatórias sendo passadas como opcionais no banco de dados
- Body de requisição está faltando as informações

---

**Assistant:**
Boa direção, mas resposta básica.s

---

**User:**
Você pode finalizar com um diagnostico do que preciso evoluir para conseguir a vaga?

---

## 📊 Diagnóstico

### 🎯 Nível geral: Júnior com prática real

### ✅ Pontos fortes

- Experiência prática
- Entendimento de estrutura
- Raciocínio técnico correto

### ⚠️ Pontos críticos

- Comunicação técnica fraca
- Falta de estrutura nas respostas
- Debug muito básico
- Pouca menção a boas práticas

### 📈 O que evoluir

- Explicar melhor o que você já sabe
- Estruturar respostas
- Aprofundar backend
- Justificar decisões técnicas

---

**User:**
Poderia montar um plano de estudos com vídeos, onde eu consiga me dedicar por 2hr/dia

---

## 📚 Plano de Estudos (4 semanas)

### 🧠 Estrutura diária

- 1h vídeo
- 1h prática + explicação

---

### 📆 Semana 1 — Fundamentos

- Arquitetura NestJS
- DTO + validação
- Prisma
- Fluxo completo
- Tratamento de erros

---

### 📆 Semana 2 — Backend real

- JWT
- Guards
- Middleware
- Boas práticas
- Debug

---

### 📆 Semana 3 — Entrevista

- Perguntas comuns
- Treino em voz alta
- Gravação

---

### 📆 Semana 4 — Simulação

- Entrevistas completas
- Respostas estruturadas

---

### 🎯 Resultado esperado

- Júnior forte
- Melhor comunicação
- Aprovação em entrevistas

---

### 🔥 Dica principal

Falar em voz alta TODOS OS DIAS

---

**User:**
transforme em README.MD para mim com todas as respostas suas e minhas, sem alterar nada

---
