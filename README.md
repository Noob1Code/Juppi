# Juppi

> **Marketplace de espaços esportivos que conecta clientes e atletas a estabelecimentos esportivos de todos os portes, com foco inicial em pequenos e médios proprietários.**

---

## 📱 Sobre o projeto

O **Juppi** é um aplicativo marketplace desenvolvido para conectar pessoas interessadas em praticar esportes a **estabelecimentos e proprietários de espaços esportivos**.

A plataforma permitirá que clientes encontrem espaços esportivos próximos de sua localização, consultem modalidades, horários e valores disponíveis e realizem reservas.

Do outro lado, proprietários poderão cadastrar seus estabelecimentos e seus espaços esportivos, disponibilizando informações, modalidades, horários e preços para que clientes possam realizar agendamentos.

O Juppi será pensado principalmente como um **aplicativo mobile**, com possibilidade de acesso através de navegador em computadores.

A proposta original define o produto como um aplicativo estilo marketplace para conectar proprietários de arenas esportivas a atletas/clientes que procuram espaços próximos para prática de esportes e agendamentos.

---

# 🎯 Visão do produto

O Juppi não será limitado a grandes complexos esportivos.

O foco inicial será atender principalmente:

- Pequenos proprietários;
- Médios estabelecimentos;
- Proprietários independentes;
- Pessoas que possuem uma ou poucas quadras;
- Estabelecimentos que ainda realizam reservas manualmente;
- Espaços esportivos que precisam de maior visibilidade.

Ao mesmo tempo, a plataforma será construída para atender também:

- Grandes empresas;
- Clubes;
- Centros esportivos;
- Complexos esportivos;
- Estabelecimentos com múltiplas quadras;
- Redes de estabelecimentos esportivos.

### Estratégia de mercado

```text
                  JUPPI
                    │
       ┌────────────┴────────────┐
       │                         │
       ▼                         ▼
 FOCO INICIAL                ATENDIMENTO
       │                         │
       ▼                         ▼
 Pequenos e médios          Todos os portes
 proprietários              de estabelecimentos
       │                         │
       ├── 1 quadra              ├── 1 quadra
       ├── 2 quadras             ├── 5 quadras
       ├── 3 quadras             ├── 10 quadras
       └── poucos espaços        └── grandes complexos
```

**Foco inicial ≠ exclusividade.**

O Juppi será projetado para começar com uma experiência simples e acessível para pequenos e médios proprietários, mas sem criar limitações arquiteturais que impeçam a entrada de estabelecimentos maiores no futuro.

---

# 💡 Problema

Pequenos proprietários de espaços esportivos podem ter dificuldades para divulgar seus espaços e organizar reservas.

Em muitos casos, o controle pode ser realizado através de:

```text
WhatsApp
Telefone
Anotações
Planilhas
Agenda física
Mensagens diretas
```

Isso pode dificultar:

- Controle de horários;
- Divulgação do espaço;
- Organização das reservas;
- Visualização de disponibilidade;
- Atendimento simultâneo de vários clientes;
- Controle de preços;
- Histórico de reservas.

O Juppi pretende centralizar essas operações em uma única plataforma.

---

# 💎 Proposta de valor

## Para o cliente

O Juppi deverá tornar mais simples:

```text
Encontrar
    ↓
Comparar
    ↓
Escolher
    ↓
Consultar disponibilidade
    ↓
Reservar
```

## Para o pequeno proprietário

O Juppi deverá funcionar como uma ferramenta simples para:

```text
Cadastrar espaço
      ↓
Divulgar
      ↓
Cadastrar horários
      ↓
Definir preços
      ↓
Receber reservas
```

O proprietário não precisa possuir um grande complexo esportivo para utilizar a plataforma.

Um proprietário com **uma única quadra** também faz parte do público-alvo do Juppi.

---

# 🏟️ O que é um espaço esportivo no Juppi?

No Juppi, o conceito de espaço esportivo deverá ser flexível.

Um estabelecimento pode possuir:

```text
1 espaço
```

ou:

```text
vários espaços
```

Exemplo de pequeno proprietário:

```text
João
└── Arena do João
    └── Quadra 1
```

Exemplo de proprietário médio:

```text
Maria
└── Centro Esportivo Maria
    ├── Quadra 1
    ├── Quadra 2
    └── Quadra 3
```

Exemplo de estabelecimento maior:

```text
Complexo Esportivo X
├── Quadra 1
├── Quadra 2
├── Quadra 3
├── Campo 1
├── Campo 2
└── Piscina
```

Dessa forma, a arquitetura não assume que todo proprietário possui uma grande estrutura.

---

# 👥 Público do sistema

## 👤 Cliente / Atleta

Pessoa que procura um local para praticar esporte.

Pode:

- Criar uma conta;
- Fazer login;
- Utilizar localização;
- Encontrar espaços próximos;
- Filtrar modalidades;
- Visualizar informações;
- Consultar horários;
- Realizar reservas;
- Avaliar espaços.

---

## 🧑‍💼 Proprietário

Pessoa ou empresa responsável por um ou mais estabelecimentos esportivos.

Pode:

- Criar uma conta;
- Cadastrar estabelecimento;
- Cadastrar espaços esportivos;
- Informar modalidades;
- Adicionar fotos;
- Definir horários;
- Definir valores;
- Gerenciar disponibilidade;
- Acompanhar reservas.

---

# 🏢 Estabelecimentos de todos os portes

O Juppi será construído com uma estratégia de **entrada simples e escalabilidade estrutural**.

### Pequeno

```text
1 proprietário
1 estabelecimento
1 quadra
```

### Médio

```text
1 proprietário
1 estabelecimento
2-5 espaços
```

### Grande

```text
Empresa
├── Estabelecimento A
│   ├── Quadra 1
│   ├── Quadra 2
│   └── Campo 1
│
├── Estabelecimento B
│   ├── Quadra 1
│   └── Quadra 2
│
└── Estabelecimento C
    └── Piscina
```

O modelo deverá permitir esses diferentes cenários.

---

# ⚽ Modalidades

A proposta inicial considera modalidades como:

- Futebol;
- Vôlei;
- Natação;
- Paintball.

O sistema deverá ser desenvolvido de forma que novas modalidades possam ser adicionadas futuramente sem necessidade de alteração estrutural significativa.

---

# 📱 Plataformas

O Juppi será um **aplicativo**, não um site tradicional.

A plataforma será dividida em:

```text
                  JUPPI
                    │
       ┌────────────┴────────────┐
       │                         │
       ▼                         ▼
📱 Aplicativo Mobile       💻 Aplicação Web
 Android / iOS             Navegador
       │                         │
       └────────────┬────────────┘
                    │
                    ▼
                REST API
                    │
                    ▼
             Spring Boot
                    │
                    ▼
               PostgreSQL
```

O aplicativo mobile será a interface principal.

A aplicação web permitirá acesso pelo computador através do navegador.

As duas interfaces deverão consumir a mesma API.

---

# 🏗️ Arquitetura

A arquitetura inicial será dividida em:

```text
Frontend Mobile
React Native + Expo

Frontend Web
React + Vite

Backend
Java + Spring Boot

Banco
PostgreSQL
```

Fluxo:

```text
┌───────────────────────────────┐
│          USUÁRIO              │
└───────────────┬───────────────┘
                │
       ┌────────┴─────────┐
       │                  │
       ▼                  ▼
┌─────────────┐    ┌─────────────┐
│ React       │    │ React       │
│ Native      │    │ + Vite      │
│ + Expo      │    │ Web         │
└──────┬──────┘    └──────┬──────┘
       │                  │
       └────────┬─────────┘
                │
           HTTPS / JSON
                │
                ▼
┌───────────────────────────────┐
│       Java + Spring Boot      │
│                               │
│ Controller                    │
│ Service                       │
│ Repository                   │
│ Security                      │
│ DTO                           │
└───────────────┬───────────────┘
                │
          JPA / Hibernate
                │
                ▼
┌───────────────────────────────┐
│          PostgreSQL           │
└───────────────────────────────┘
```

---

# 🧰 Stack tecnológica

A stack abaixo é a **proposta técnica inicial**.

Ela poderá sofrer alterações conforme as necessidades identificadas durante as Sprints.

## 📱 Mobile

| Tecnologia | Função |
|---|---|
| React Native | Desenvolvimento do aplicativo |
| Expo | Ambiente e ferramentas React Native |
| TypeScript | Linguagem recomendada |
| React Navigation | Navegação |
| Axios / Fetch | Comunicação com API |
| Expo Location | Localização |
| AsyncStorage | Armazenamento local simples |

---

## 💻 Web

| Tecnologia | Função |
|---|---|
| React | Interface web |
| Vite | Desenvolvimento e build |
| TypeScript | Linguagem recomendada |
| React Router | Navegação |
| Axios / Fetch | Comunicação com API |

---

## ☕ Backend

| Tecnologia | Função |
|---|---|
| Java | Linguagem |
| Spring Boot | Framework |
| Spring Web | API REST |
| Spring Data JPA | Persistência |
| Hibernate | ORM |
| Spring Security | Segurança |
| JWT | Autenticação |
| Jakarta Validation | Validação |
| Maven | Build e dependências |

---

## 🐘 Banco de dados

| Tecnologia | Função |
|---|---|
| PostgreSQL | Banco relacional |
| SQL | Consultas |
| JPA | Persistência |
| Hibernate | ORM |

---

## 🛠️ Ferramentas

- Git;
- GitHub;
- VS Code;
- IntelliJ IDEA;
- Android Studio;
- Node.js;
- npm;
- Maven;
- Postman;
- Insomnia;
- PostgreSQL;
- Docker — opcional inicialmente.

---

# 🧱 Arquitetura do Backend

O backend seguirá inicialmente o padrão:

```text
Controller
     ↓
Service
     ↓
Repository
     ↓
Database
```

## Controller

Recebe requisições HTTP.

Exemplo:

```text
POST /api/auth/login
GET /api/estabelecimentos
GET /api/espacos/{id}
POST /api/espacos
POST /api/reservas
```

---

## Service

Responsável pelas regras de negócio.

Exemplos:

```text
Verificar disponibilidade
Criar reserva
Cancelar reserva
Validar proprietário
Calcular preço
Validar avaliação
Filtrar espaços
Buscar espaços próximos
```

---

## Repository

Responsável pela persistência.

Exemplos:

```text
UsuarioRepository
EstabelecimentoRepository
EspacoRepository
ModalidadeRepository
HorarioRepository
ReservaRepository
AvaliacaoRepository
```

---

# 🧩 Modelo de domínio

Uma mudança importante em relação à primeira versão da documentação é separar:

```text
Proprietário
Estabelecimento
Espaço esportivo
```

Isso evita que a aplicação trate uma arena como se fosse obrigatoriamente uma única quadra.

O modelo conceitual será:

```text
PROPRIETÁRIO
      │
      │ 1:N
      ▼
ESTABELECIMENTO
      │
      │ 1:N
      ▼
ESPAÇO ESPORTIVO
      │
      ├──── Modalidades
      ├──── Horários
      ├──── Preços
      └──── Reservas
```

---

# 🗄️ Banco de dados

O PostgreSQL será utilizado inicialmente como banco de dados principal.

A estrutura deverá refletir o domínio do Juppi.

---

# 📊 Modelo inicial de dados

## Usuario

```text
USUARIO
---------
id
nome
email
senha
tipo
created_at
updated_at
```

Tipos:

```text
CLIENTE
PROPRIETARIO
```

---

## Estabelecimento

Representa o local administrado pelo proprietário.

```text
ESTABELECIMENTO
---------
id
proprietario_id
nome
descricao
endereco
numero
bairro
cidade
estado
cep
latitude
longitude
created_at
updated_at
```

---

## Espaço esportivo

Representa o espaço que será efetivamente reservado.

```text
ESPACO_ESPORTIVO
---------
id
estabelecimento_id
nome
descricao
capacidade
ativo
created_at
updated_at
```

Exemplos:

```text
Quadra 1
Quadra 2
Campo Society
Piscina
Quadra de Vôlei
```

---

## Modalidade

```text
MODALIDADE
---------
id
nome
descricao
ativo
```

Exemplos:

```text
Futebol
Vôlei
Natação
Paintball
```

---

## EspaçoModalidade

Um espaço pode possuir uma ou várias modalidades.

```text
ESPACO_MODALIDADE
---------
espaco_id
modalidade_id
```

---

## Horário

```text
HORARIO
---------
id
espaco_id
data
hora_inicio
hora_fim
valor
disponivel
```

---

## Reserva

```text
RESERVA
---------
id
usuario_id
espaco_id
horario_id
status
valor
created_at
updated_at
```

---

## Avaliação

```text
AVALIACAO
---------
id
usuario_id
espaco_id
nota
comentario
created_at
```

---

# 🔗 Relacionamentos

Modelo conceitual:

```text
                         ┌───────────────┐
                         │    USUARIO    │
                         └───────┬───────┘
                                 │
                                 │
                                 ▼
                         ┌───────────────┐
                         │    RESERVA    │
                         └───────┬───────┘
                                 │
                                 │
                                 ▼
┌───────────────┐        ┌───────────────┐
│ PROPRIETÁRIO  │───────▶│ ESTABELECIMENTO│
└───────────────┘   1:N  └───────┬───────┘
                                 │
                                1:N
                                 │
                                 ▼
                         ┌───────────────┐
                         │     ESPAÇO    │
                         │   ESPORTIVO   │
                         └───────┬───────┘
                                 │
                    ┌────────────┼────────────┐
                    │            │            │
                    ▼            ▼            ▼
                HORÁRIOS    AVALIAÇÕES   MODALIDADES
```

---

# 🧑‍💼 Exemplo: pequeno proprietário

O banco deverá conseguir representar algo simples:

```text
Proprietário:
João

Estabelecimento:
Arena do João

Espaços:
└── Quadra 1

Modalidade:
└── Futebol

Horários:
├── 18:00 - 19:00
├── 19:00 - 20:00
└── 20:00 - 21:00
```

O sistema não deverá exigir que João tenha várias quadras para utilizar o Juppi.

---

# 🏢 Exemplo: grande empresa

A mesma estrutura deverá permitir:

```text
Empresa Esportiva X

├── Unidade Centro
│   ├── Quadra 1
│   ├── Quadra 2
│   └── Quadra 3
│
├── Unidade Norte
│   ├── Campo 1
│   └── Quadra 1
│
└── Unidade Sul
    ├── Quadra 1
    ├── Quadra 2
    └── Piscina
```

A arquitetura permite que a mesma plataforma atenda ambos os cenários.

---

# 🔌 Comunicação entre sistemas

O aplicativo e a aplicação web **não acessarão diretamente o PostgreSQL**.

O fluxo será:

```text
React Native ──┐
               │
               ├── HTTPS / JSON ──▶ Spring Boot ──▶ PostgreSQL
               │
React Web ─────┘
```

---

# 📦 JSON

JSON será o formato inicial de comunicação entre frontend e backend.

## Cadastro de usuário

```json
{
  "nome": "João Silva",
  "email": "joao@email.com",
  "senha": "senha123",
  "tipo": "PROPRIETARIO"
}
```

## Cadastro de estabelecimento

```json
{
  "nome": "Arena do João",
  "descricao": "Espaço esportivo para futebol",
  "endereco": {
    "logradouro": "Rua Exemplo",
    "numero": "100",
    "bairro": "Centro",
    "cidade": "Goiânia",
    "estado": "GO",
    "cep": "74000000"
  }
}
```

## Cadastro de espaço

```json
{
  "nome": "Quadra 1",
  "descricao": "Quadra de futebol society",
  "capacidade": 14,
  "modalidades": [
    "FUTEBOL"
  ]
}
```

---

# 🌐 API REST

Os endpoints abaixo são uma proposta inicial.

## Autenticação

```http
POST /api/auth/register
POST /api/auth/login
```

## Usuários

```http
GET    /api/usuarios/{id}
PUT    /api/usuarios/{id}
DELETE /api/usuarios/{id}
```

## Estabelecimentos

```http
GET    /api/estabelecimentos
GET    /api/estabelecimentos/{id}
POST   /api/estabelecimentos
PUT    /api/estabelecimentos/{id}
DELETE /api/estabelecimentos/{id}
```

## Espaços

```http
GET    /api/estabelecimentos/{id}/espacos
GET    /api/espacos/{id}
POST   /api/estabelecimentos/{id}/espacos
PUT    /api/espacos/{id}
DELETE /api/espacos/{id}
```

## Modalidades

```http
GET /api/modalidades
```

## Horários

```http
GET  /api/espacos/{id}/horarios
POST /api/espacos/{id}/horarios
PUT  /api/horarios/{id}
```

## Reservas

```http
GET  /api/reservas
GET  /api/reservas/{id}
POST /api/reservas
PUT  /api/reservas/{id}
```

## Avaliações

```http
GET  /api/espacos/{id}/avaliacoes
POST /api/espacos/{id}/avaliacoes
```

---

# 🔐 Autenticação

A proposta inicial será:

```text
Spring Security
+
JWT
```

Fluxo:

```text
Aplicativo
     │
     │ email + senha
     ▼
Spring Boot
     │
     ├── valida usuário
     ├── valida senha
     └── gera JWT
             │
             ▼
        Aplicativo
             │
             │ Authorization: Bearer TOKEN
             ▼
       API protegida
```

---

# 👥 Autorização

A autenticação identifica o usuário.

A autorização define o que ele pode fazer.

Exemplo:

```text
CLIENTE
├── Consultar espaços
├── Fazer reservas
└── Avaliar espaços

PROPRIETARIO
├── Cadastrar estabelecimento
├── Cadastrar espaços
├── Gerenciar horários
└── Gerenciar reservas
```

O backend deverá validar essas permissões.

---

# 📍 Geolocalização

O aplicativo poderá solicitar acesso à localização do dispositivo.

Fluxo:

```text
Usuário
   ↓
Permite localização
   ↓
React Native / Expo
   ↓
Latitude + Longitude
   ↓
API
   ↓
Busca espaços próximos
```

Exemplo:

```http
GET /api/espacos/proximos?latitude=-16.6869&longitude=-49.2648
```

A estratégia de cálculo de distância ainda poderá ser definida durante as Sprints.

---

# 🔎 Busca

O cliente poderá buscar espaços por:

- Localização;
- Modalidade;
- Estabelecimento;
- Disponibilidade;
- Outros filtros que forem adicionados posteriormente.

Exemplo:

```http
GET /api/espacos?modalidade=FUTEBOL
```

Ou:

```http
GET /api/espacos/proximos?latitude=...&longitude=...
```

---

# 📅 Reservas

A reserva deverá ser realizada sobre o **espaço esportivo**, e não simplesmente sobre o proprietário.

Exemplo:

```text
Arena do João
│
├── Quadra 1
│   ├── 18:00 → disponível
│   ├── 19:00 → reservado
│   └── 20:00 → disponível
│
└── Quadra 2
    ├── 18:00 → disponível
    └── 19:00 → disponível
```

Isso permite que um proprietário com várias quadras gerencie os horários individualmente.

---

# 🔒 Concorrência de reservas

O backend deverá impedir que duas pessoas reservem simultaneamente o mesmo horário.

Fluxo:

```text
Cliente A ─────┐
               ├──▶ API
Cliente B ─────┘
                  │
                  ▼
           Verificação
           de disponibilidade
                  │
          ┌───────┴────────┐
          │                │
          ▼                ▼
       Disponível       Ocupado
          │                │
          ▼                ▼
       Reserva          HTTP 409
```

Essa validação deverá acontecer no backend e no banco de dados conforme a estratégia de concorrência adotada.

---

# ⭐ Avaliações

Clientes poderão avaliar espaços utilizados.

Exemplo:

```json
{
  "nota": 5,
  "comentario": "Quadra muito boa e bem cuidada."
}
```

A avaliação será relacionada ao espaço esportivo.

---

# ❌ Tratamento de erros

A API deverá utilizar códigos HTTP apropriados.

| Código | Significado |
|---:|---|
| 200 | Sucesso |
| 201 | Recurso criado |
| 204 | Sucesso sem conteúdo |
| 400 | Requisição inválida |
| 401 | Não autenticado |
| 403 | Sem permissão |
| 404 | Recurso não encontrado |
| 409 | Conflito |
| 500 | Erro interno |

Exemplo:

```json
{
  "status": 409,
  "message": "O horário selecionado já está reservado.",
  "timestamp": "2026-08-05T19:00:00"
}
```

---

# ✅ Validação

Exemplos:

```text
Email obrigatório
Email válido
Senha obrigatória
Nome obrigatório
Nota entre 1 e 5
Valor maior que zero
Data válida
Horário válido
Estabelecimento existente
Espaço existente
Proprietário autorizado
Horário disponível
```

As validações críticas deverão ocorrer no backend.

---

# 🧪 Testes

## Backend

Possíveis ferramentas:

```text
JUnit
Mockito
Spring Boot Test
```

Testes prioritários:

- Services;
- Controllers;
- Repositories;
- Regras de negócio;
- Autenticação;
- Reservas;
- Validação;
- Permissões.

## Mobile

Possíveis ferramentas:

```text
Jest
React Native Testing Library
```

## Web

Possíveis ferramentas:

```text
Vitest
React Testing Library
```

## API

```text
Postman
Insomnia
```

---

# 📁 Estrutura do repositório

```text
juppi/
│
├── mobile/
│   ├── src/
│   │   ├── components/
│   │   ├── screens/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── contexts/
│   │   ├── utils/
│   │   └── assets/
│   ├── package.json
│   └── app.json
│
├── web/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── services/
│   │   ├── hooks/
│   │   ├── contexts/
│   │   ├── routes/
│   │   └── utils/
│   ├── package.json
│   └── vite.config.ts
│
├── backend/
│   ├── src/
│   │   └── main/
│   │       ├── java/
│   │       │   └── br/com/juppi/
│   │       │       ├── controller/
│   │       │       ├── service/
│   │       │       ├── repository/
│   │       │       ├── entity/
│   │       │       ├── dto/
│   │       │       ├── security/
│   │       │       ├── exception/
│   │       │       └── config/
│   │       │
│   │       └── resources/
│   │           └── application.properties
│   │
│   └── pom.xml
│
├── docs/
│   ├── arquitetura/
│   ├── api/
│   ├── banco/
│   └── requisitos/
│
├── .gitignore
└── README.md
```

---

# 🗂️ Organização do Mobile

```text
mobile/
└── src/
    ├── components/
    │   ├── Button/
    │   ├── Input/
    │   ├── SpaceCard/
    │   ├── EstablishmentCard/
    │   └── Rating/
    │
    ├── screens/
    │   ├── Login/
    │   ├── Register/
    │   ├── Home/
    │   ├── Search/
    │   ├── SpaceDetails/
    │   ├── Booking/
    │   ├── Profile/
    │   └── Owner/
    │
    ├── services/
    │   └── api.ts
    │
    ├── hooks/
    ├── contexts/
    ├── utils/
    └── assets/
```

---

# 🗂️ Organização do Backend

```text
backend/
└── src/main/java/br/com/juppi/
    │
    ├── controller/
    │   ├── AuthController
    │   ├── UsuarioController
    │   ├── EstabelecimentoController
    │   ├── EspacoController
    │   ├── ReservaController
    │   └── AvaliacaoController
    │
    ├── service/
    │
    ├── repository/
    │
    ├── entity/
    │   ├── Usuario
    │   ├── Estabelecimento
    │   ├── EspacoEsportivo
    │   ├── Modalidade
    │   ├── Horario
    │   ├── Reserva
    │   └── Avaliacao
    │
    ├── dto/
    │
    ├── security/
    │
    ├── exception/
    │
    └── config/
```

---

# 🔀 Git e GitHub

O projeto utilizará Git para versionamento.

Branches sugeridas:

```text
main
develop
feature/*
bugfix/*
```

Exemplos:

```text
feature/login
feature/cadastro-estabelecimento
feature/cadastro-espaco
feature/busca-localizacao
feature/reserva
feature/avaliacao
```

---

# 📝 Commits

Padrão sugerido:

```text
feat: adiciona cadastro de estabelecimento

feat: adiciona cadastro de espaço esportivo

feat: implementa busca por localização

fix: corrige conflito de horário na reserva

test: adiciona testes de reserva

refactor: reorganiza camada service

docs: atualiza documentação da arquitetura
```

---

# 🔀 Pull Request

Fluxo:

```text
Issue
  ↓
Branch
  ↓
Desenvolvimento
  ↓
Teste
  ↓
Commit
  ↓
Push
  ↓
Pull Request
  ↓
Code Review
  ↓
Aprovação
  ↓
Merge
```

---

# 🏃 Scrum

O projeto utilizará Scrum com acompanhamento das atividades através de Kanban.

## Equipe

| Integrante | Papel |
|---|---|
| Felipe Borges | Product Owner / Desenvolvimento |
| Kayque de Freitas | Scrum Master / Desenvolvimento |
| Gabriel Braga Oliveira | Desenvolvimento |

Os papéis foram definidos no planejamento original.

---

# 📋 Product Backlog inicial

| ID | User Story | Pontos |
|---|---|---:|
| US01 | Cadastro/Login | 2 |
| US02 | Arenas próximas | 5 |
| US03 | Filtro por modalidade | 3 |
| US04 | Cadastro de arena | 5 |
| US05 | Horários e preços | 3 |
| US06 | Reserva de arena | 8 |
| US07 | Avaliação e comentários | 3 |

As estimativas foram definidas utilizando Planning Poker e Fibonacci.

---

# 🚀 MVP — Sprint 1

A Sprint 1 terá como objetivo construir a primeira versão funcional do Juppi.

## US01 — Cadastro/Login

> Como cliente, quero cadastrar/fazer login com e-mail e senha para acessar a plataforma de forma personalizada.

**2 Story Points**

---

## US04 — Cadastro de arena

> Como empresa/proprietário, quero cadastrar minha arena com detalhes (nome, fotos, endereço e modalidades) para disponibilizá-la no app.

**5 Story Points**

### Adaptação técnica

Dentro da evolução do modelo de domínio, essa funcionalidade será interpretada como:

```text
Proprietário
   ↓
Estabelecimento
   ↓
Espaço esportivo
```

Isso permite que o MVP funcione para um proprietário com uma única quadra, mas também permite crescimento futuro.

---

## US02 — Arenas próximas

> Como cliente, quero visualizar arenas próximas com base na minha localização geográfica para encontrar opções acessíveis.

**5 Story Points**

---

## Total da Sprint

```text
US01 = 2
US04 = 5
US02 = 5

TOTAL = 12 Story Points
```

O planejamento original estabelece essas três histórias como escopo da Sprint 1.

---

# 📌 Backlog posterior

Após o MVP:

```text
US03
Filtro por modalidade

US05
Cadastro de horários e preços

US06
Reserva / agendamento

US07
Avaliações e comentários
```

A ordem poderá ser alterada conforme as decisões do Product Owner e as necessidades encontradas durante as Sprints.

---

# ✅ Definition of Done

Uma tarefa será considerada concluída quando:

- [ ] Código implementado;
- [ ] Código testado localmente;
- [ ] Pull Request criado;
- [ ] Pull Request revisado;
- [ ] Outro integrante aprovou a alteração;
- [ ] Alterações mescladas na branch principal.

Esses critérios seguem a Definition of Done do planejamento original.

---

# 🟢 Execução do Mobile

Requisitos:

```text
Node.js
npm
Expo
Android Studio (opcional)
```

Criação:

```bash
npx create-expo-app@latest mobile
```

Instalação:

```bash
cd mobile
npm install
```

Execução:

```bash
npx expo start
```

O aplicativo poderá ser testado em:

```text
Android
iOS
Emulador
Dispositivo físico
```

---

# 💻 Execução da Web

Criar:

```bash
npm create vite@latest web
```

Instalar:

```bash
cd web
npm install
```

Executar:

```bash
npm run dev
```

---

# ☕ Execução do Backend

Linux/macOS:

```bash
cd backend
./mvnw spring-boot:run
```

Windows:

```bash
cd backend
mvnw.cmd spring-boot:run
```

---

# 🐘 PostgreSQL

Configuração inicial:

```properties
spring.datasource.url=jdbc:postgresql://localhost:5432/juppi
spring.datasource.username=postgres
spring.datasource.password=${DB_PASSWORD}

spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
```

Em ambientes de produção, credenciais não deverão ser armazenadas diretamente no código.

---

# 🔐 Variáveis de ambiente

Exemplo:

```env
DB_HOST=localhost
DB_PORT=5432
DB_NAME=juppi
DB_USER=postgres
DB_PASSWORD=senha

JWT_SECRET=chave-secreta
```

`.env` deverá estar no `.gitignore`:

```gitignore
.env
.env.*
```

---

# 🐳 Docker

Docker será considerado uma ferramenta opcional inicialmente.

Posteriormente poderá ser utilizado para padronizar:

```text
PostgreSQL
Backend
Web
Outros serviços
```

Uma configuração futura poderá utilizar:

```text
docker-compose.yml
```

---

# 🛡️ Segurança

A aplicação deverá considerar:

- Spring Security;
- JWT;
- Hash seguro de senhas;
- Controle de acesso;
- Validação no backend;
- HTTPS;
- Variáveis de ambiente;
- Proteção das credenciais;
- Controle de permissões por usuário.

Principalmente, nenhuma regra de autorização deverá depender exclusivamente do frontend.

---

# 🖼️ Imagens

Os estabelecimentos poderão possuir fotos.

Inicialmente, a arquitetura poderá armazenar referências para imagens.

Possíveis soluções futuras:

```text
Object Storage
Cloud Storage
Serviço especializado
```

A escolha definitiva poderá ser feita conforme a necessidade do projeto.

---

# 📍 Evolução geográfica

A funcionalidade de localização poderá evoluir:

```text
Sprint inicial
      ↓
Latitude + Longitude
      ↓
Cálculo de distância
      ↓
Busca geográfica otimizada
      ↓
Integração com mapas
```

A tecnologia definitiva será escolhida conforme os requisitos do produto.

---

# 📈 Roadmap

```text
SPRINT 0
│
├── Repositório
├── Estrutura do projeto
├── Backend
├── Mobile
├── Web
└── Banco
        │
        ▼
SPRINT 1 — MVP
│
├── Cadastro/Login
├── Cadastro de estabelecimento
└── Arenas próximas
        │
        ▼
SPRINT FUTURA
│
└── Filtro por modalidade
        │
        ▼
SPRINT FUTURA
│
└── Horários e preços
        │
        ▼
SPRINT FUTURA
│
└── Reservas
        │
        ▼
SPRINT FUTURA
│
└── Avaliações
        │
        ▼
EVOLUÇÃO
│
├── Gestão de múltiplos espaços
├── Gestão de múltiplos estabelecimentos
├── Notificações
├── Mapas
├── Favoritos
├── Histórico
├── Pagamentos
├── Dashboard
├── Docker
├── CI/CD
└── Deploy
```

O roadmap é uma proposta de organização técnica. As futuras Sprints poderão ser reorganizadas de acordo com o backlog e as decisões da equipe.

---

# 🏢 Escalabilidade do produto

Uma preocupação arquitetural importante será garantir que o foco inicial em pequenos estabelecimentos não impeça o crescimento do Juppi.

A arquitetura deverá suportar:

```text
                    PROPRIETÁRIO
                         │
             ┌───────────┴───────────┐
             │                       │
       Pequeno negócio          Grande empresa
             │                       │
             ▼                       ▼
      1 estabelecimento       vários estabelecimentos
             │                       │
         1 espaço              vários espaços
             │                       │
             └───────────┬───────────┘
                         │
                         ▼
                       JUPPI
```

O mesmo modelo de domínio atende os dois cenários.

---

# 🧠 Princípio de desenvolvimento

O Juppi deverá seguir o princípio:

> **Começar simples, mas não construir de forma limitada.**

O MVP deverá ser pequeno o suficiente para ser desenvolvido e validado rapidamente, mas a arquitetura deverá permitir evolução.

Isso significa:

```text
MVP
↓
Poucos recursos
↓
Modelo simples
↓
Validação com usuários
↓
Aprendizado
↓
Evolução
```

A complexidade deverá ser adicionada conforme houver necessidade real.

---

# 🔄 Tecnologias sujeitas a mudança

A stack inicial:

```text
Mobile
└── React Native + Expo

Web
└── React + Vite

Backend
└── Java + Spring Boot

Database
└── PostgreSQL

Comunicação
└── REST + JSON

Segurança
└── Spring Security + JWT

Versionamento
└── Git + GitHub
```

Essa stack **não é definitiva**.

Durante as Sprints, qualquer tecnologia poderá ser substituída caso uma alternativa seja tecnicamente mais adequada.

Exemplos:

```text
JavaScript → TypeScript

Axios → Fetch

React Native / Expo → outra solução mobile

PostgreSQL → outra solução de persistência

JWT → outra estratégia de autenticação

Docker → adoção futura

React + Vite → evolução da camada web
```

Mudanças relevantes deverão ser discutidas pela equipe e justificadas tecnicamente.

---

# 🧭 Princípio arquitetural

O Juppi deverá centralizar as regras de negócio no backend.

Evitar:

```text
❌ Mobile → PostgreSQL

❌ Web → PostgreSQL

❌ Regra de reserva somente no frontend
```

Priorizar:

```text
✅ Mobile → API → Backend → PostgreSQL

✅ Web → API → Backend → PostgreSQL
```

Assim, todas as plataformas utilizam as mesmas regras.

---

# 📊 Visão final

```text
                              JUPPI
                                │
              ┌─────────────────┴─────────────────┐
              │                                   │
              ▼                                   ▼
       📱 MOBILE                              💻 WEB
   React Native + Expo                     React + Vite
              │                                   │
              └─────────────────┬─────────────────┘
                                │
                           HTTPS / JSON
                                │
                                ▼
                   ┌─────────────────────────┐
                   │      SPRING BOOT        │
                   │                         │
                   │ Controllers             │
                   │ Services                │
                   │ DTOs                    │
                   │ Security / JWT          │
                   │ Repositories            │
                   └────────────┬────────────┘
                                │
                           JPA / Hibernate
                                │
                                ▼
                   ┌─────────────────────────┐
                   │       POSTGRESQL        │
                   │                         │
                   │ Usuários                │
                   │ Proprietários           │
                   │ Estabelecimentos        │
                   │ Espaços                 │
                   │ Modalidades             │
                   │ Horários                │
                   │ Reservas                │
                   │ Avaliações              │
                   └─────────────────────────┘
```

---

# 📌 Exemplo completo do funcionamento

Imagine um pequeno proprietário:

```text
João possui uma quadra.
```

Ele cria uma conta:

```text
João
└── Proprietário
```

Cadastra seu estabelecimento:

```text
Arena do João
```

Cadastra seu espaço:

```text
Arena do João
└── Quadra 1
```

Define a modalidade:

```text
Quadra 1
└── Futebol
```

Define os horários:

```text
18:00 → R$ 100
19:00 → R$ 100
20:00 → R$ 120
```

Um cliente abre o Juppi:

```text
📱 Juppi
   ↓
Localização
   ↓
Espaços próximos
   ↓
Arena do João
   ↓
Quadra 1
   ↓
Futebol
   ↓
20:00
   ↓
Reservar
```

O mesmo sistema poderá atender uma empresa muito maior:

```text
Empresa Esportiva
│
├── Unidade A
│   ├── Quadra 1
│   ├── Quadra 2
│   └── Campo 1
│
├── Unidade B
│   ├── Quadra 1
│   └── Piscina
│
└── Unidade C
    ├── Campo 1
    └── Campo 2
```

A diferença está na **quantidade de dados**, não em uma arquitetura completamente diferente.

---

# 🚧 Status

**Projeto:** Juppi

**Tipo:** Aplicativo marketplace esportivo

**Foco inicial:** Pequenos e médios estabelecimentos/proprietários

**Mercado atendido:** Estabelecimentos de todos os portes

**Status:** Planejamento / Desenvolvimento inicial

**Versão:** `0.2.0`

### Plataformas

```text
Android
iOS
Web / Desktop Browser
```

### Stack inicial

```text
React Native
Expo
React
Vite
TypeScript
Java
Spring Boot
Spring Data JPA
Hibernate
Spring Security
JWT
PostgreSQL
REST
JSON
Node.js
npm
Maven
Git
GitHub
```

---

# 👨‍💻 Equipe

| Integrante | Papel |
|---|---|
| Felipe Borges | Product Owner / Desenvolvimento |
| Kayque de Freitas | Scrum Master / Desenvolvimento |
| Gabriel Braga Oliveira | Desenvolvimento |

---

# 📚 Base do planejamento

Este README foi construído com base no planejamento inicial do projeto Juppi, que define:

- A proposta do aplicativo;
- Os papéis da equipe;
- O Product Backlog;
- As User Stories;
- As estimativas;
- O escopo inicial da Sprint 1;
- A Definition of Done.



A definição de **pequenos e médios estabelecimentos como foco inicial**, mantendo estabelecimentos de todos os portes como mercado atendido, é uma decisão de posicionamento adicionada posteriormente pela equipe.

As tecnologias descritas neste README são uma **proposta técnica inicial** e não estavam definidas no documento original.

---

# 📄 Licença

Projeto acadêmico desenvolvido para aplicação prática de conceitos de:

- Engenharia de Software;
- Desenvolvimento de aplicativos;
- Arquitetura de software;
- APIs REST;
- Banco de dados;
- Scrum;
- Kanban;
- Controle de versão;
- Testes de software.

---

# 🏟️ Juppi

> **Do pequeno proprietário ao grande complexo.  
> Encontre. Escolha. Reserve. Pratique.**
