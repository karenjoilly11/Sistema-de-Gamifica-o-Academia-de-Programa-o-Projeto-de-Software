<div align="center">

<!-- Banner com ondas (waving) e gradiente roxo -->
<img src="https://capsule-render.vercel.app/api?type=waving&height=240&color=0:6B21E8,50:A855F7,100:C084FC&text=DevLevel&fontColor=ffffff&fontSize=52&fontAlignY=40&desc=Plataforma%20de%20Gamifica%C3%A7%C3%A3o%20para%20Academia%20de%20Programa%C3%A7%C3%A3o&descAlignY=60" alt="Banner DevLevel" width="100%" />


<p>
  <strong>🎮 Projeto acadêmico</strong> da disciplina de <strong>Projeto de Software</strong><br>
  para modelagem de uma plataforma de <strong>gamificação</strong> com mecânicas de XP, níveis, missões e conquistas.
</p>

<p>
  🎯 XP • 🏆 Níveis • 📋 Missões Diárias • 🎓 Trilhas • 💰 DevCoins • 🔥 Streaks • 🏅 Badges
</p>

</div>
# 🏷️ DevLevel - Plataforma de Gamificação para Academia de Programação 👨‍💻

> [!NOTE]
> **Transforme o aprendizado de programação em uma jornada épica!** O DevLevel é uma plataforma que utiliza mecânicas de jogos (XP, níveis, missões diárias, rankings e conquistas) para aumentar o engajamento e reduzir a evasão em academias de programação.

<div align="center">
  <img src="https://github.com/karenjoilly11/Sistema-de-Gamifica-o-Academia-de-Programa-o-Projeto-de-Software/blob/main/Assets/DevLevel.png" alt="DevLevel Banner" width="100%"/>
</div>

<table>
  <tr>
    <td width="800px">
      <div align="justify">
        Este <b>README.md</b> documenta o projeto <b>DevLevel</b>, um sistema de gamificação para academias de programação desenvolvido como parte da disciplina <b>Projeto de Software</b>. O sistema implementa mecânicas de progressão por XP (Experience Points), sistema de níveis, missões diárias personalizadas, trilhas de especialização, desbloqueio progressivo de conteúdo, ranqueamento semanal e loja de vantagens com moeda virtual. O objetivo é transformar a experiência de aprendizado, tornando-a mais engajadora, motivadora e eficaz, reduzindo a evasão (atualmente em 45% para menos de 15%).
      </div>
    </td>
    <td>
      <div>
        <img src="[https://via.placeholder.com/120x120/2d2d2d/00ff88?text=D](https://github.com/karenjoilly11/Sistema-de-Gamifica-o-Academia-de-Programa-o-Projeto-de-Software/blob/main/Assets/DevLevel.png)" alt="Logo DevLevel" width="120px"/>
      </div>
    </td>
  </tr>
</table>

---

## 🚧 Status do Projeto

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/devlevel/devlevel/main.yml?branch=main)](https://github.com/devlevel/devlevel/actions/workflows/main.yml)
[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue)](https://github.com/devlevel/devlevel/releases)
[![Licença](https://img.shields.io/github/license/devlevel/devlevel)](#licença)
[![GitHub repo size](https://img.shields.io/github/repo-size/devlevel/devlevel?style=for-the-badge)]()

---

## 📚 Índice
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Diagramas UML](#-diagramas-uml)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
- [Estrutura do Repositório](#-estrutura-do-repositório)
- [Documentação](#-documentação)
- [Autores](#-autores)
- [Licença](#-licença)

---

## 📝 Sobre o Projeto

### Qual foi a ideia inicial?
A **Academy Tech**, uma escola de programação com mais de 2.000 alunos, enfrentava um problema crítico: **45% de evasão nos meses 2-3 do curso**. Alunos começavam motivados, mas desistiam ao enfrentar dificuldades com conceitos complexos como recursão, estruturas de dados ou programação orientada a objetos.

### Qual problema ele resolve?
O **DevLevel** transforma o aprendizado em uma **jornada gamificada**, onde cada exercício resolvido, aula assistida ou ajuda oferecida a colegas gera pontos de experiência (XP). O sistema motiva os alunos através de:
- **Progressão visual clara** (níveis, barras de progresso)
- **Metas diárias alcançáveis** (missões personalizadas)
- **Competição saudável** (rankings semanais entre colegas de turma)
- **Recompensas tangíveis** (badges, vantagens exclusivas)

### Qual o contexto?
Projeto acadêmico desenvolvido para a disciplina **Projeto de Software** do curso de Engenharia de Software. O sistema foi projetado seguindo boas práticas de arquitetura de software, padrões de projeto e metodologias ágeis.

### Onde pode ser utilizado?
- **Academias de programação** (presenciais ou EAD)
- **Bootcamps de tecnologia**
- **Cursos técnicos em informática**
- **Universidades** (como ferramenta de apoio ao ensino de programação)

### O que o torna relevante?
- **Redução comprovada da evasão** (projetada: de 45% para menos de 15%)
- **Gamificação baseada em ciência comportamental** (reforço positivo, metas atingíveis)
- **Arquitetura escalável** (suporta dezenas de milhares de alunos)
- **Modelagem completa** (documentação UML abrangente)

---

## ✨ Funcionalidades Principais

- 🎮 **Sistema de XP e Níveis:** Cada ação rende XP (exercícios: +10 a +50 XP, aulas: +5 XP/hora, ajuda: +15 XP). A cada 1000 XP, aluno sobe 1 nível (máx nível 50).
- 📋 **Missões Diárias Dinâmicas:** Sistema gera 3 missões personalizadas por dia baseadas no histórico e dificuldades do aluno.
- 🎯 **Trilhas de Especialização:** 5 trilhas disponíveis (Front-end, Back-end, Dados, Mobile, DevOps). Trilha principal rende 100% XP, secundária 50% XP.
- 🔓 **Desbloqueio Progressivo de Conteúdo:** Conteúdos avançados (ex: Microsserviços, Clean Architecture) são liberados apenas ao atingir níveis mínimos.
- 🏆 **Ranqueamento Semanal:** Competição entre alunos da mesma turma baseada no XP ganho durante a semana. Premiação para os 10 primeiros colocados.
- 🛒 **Loja de Vantagens (DevCoins):** Moeda virtual ganha em missões e rankings. Trocas por: pular conteúdo (50 coins), reviver missão (30 coins), mentoria (100 coins).
- 🔥 **Sistema de Streaks (Ofensivas):** Bônus por consistência (5, 10, 20, 30 dias seguidos). Permite congelamento com DevCoins.
- 🎖️ **Badges e Conquistas:** Mais de 30 conquistas desbloqueáveis (ex: "Especialista Back-end", "Campeão da Semana", "Lenda da Consistência").
- 📊 **Dashboard Interativo:** Visualização de progresso, próximos desbloqueios e ranking em tempo real.

---

## 📊 Diagramas UML

Este projeto contempla a modelagem completa do sistema DevLevel por meio dos seguintes diagramas UML:

| Diagrama | Descrição |
|----------|-----------|
| **Diagrama de Casos de Uso** | Representa os atores (Aluno, Mentor, Administrador) e as funcionalidades do sistema |
| **Diagrama de Classes** | Estrutura estática do sistema, incluindo atributos, métodos e relacionamentos |
| **Diagramas de Sequência** | Detalhamento da interação temporal entre objetos para os principais casos de uso |
| **Diagrama de Comunicação** | Ênfase nos relacionamentos estruturais e troca de mensagens entre objetos |
| **Diagrama de Estados** | Ciclo de vida das principais entidades (Mentoria, Missão, Conteúdo, Badge) |
| **Diagrama de Componentes e Implantação** | Arquitetura distribuída em nuvem AWS com microsserviços, filas e bancos de dados |
| **Diagrama Entidade-Relacionamento (DER)** | Modelo lógico do banco de dados PostgreSQL |

Todos os diagramas foram desenvolvidos utilizando **PlantUML** e estão disponíveis na pasta `/diagramas` deste repositório.

---

## 🛠 Tecnologias Utilizadas (Propostas)

### 💻 Front-end (Proposto)
- **Framework:** React 18 + TypeScript
- **Estilização:** Tailwind CSS
- **Build Tool:** Vite

### 🖥️ Back-end (Proposto)
- **Linguagem:** Java 17
- **Framework:** Spring Boot 3.x
- **Banco de Dados:** PostgreSQL 16
- **ORM:** Hibernate / JPA
- **Autenticação:** JWT + Spring Security

### ⚙️ Infraestrutura (Proposta)
- **Containerização:** Docker + Docker Compose
- **Cloud:** AWS (ECS, RDS, S3, CloudFront)
- **Mensageria:** Amazon SQS
- **Notificações:** Amazon SES, Amazon SNS, Twilio

---

## 🏗 Arquitetura

A arquitetura proposta para o **DevLevel** segue o padrão de **microsserviços** implantados na **Amazon ECS**, com os seguintes componentes:

| Camada | Componentes |
|--------|-------------|
| **Apresentação** | React Web, React Native, CloudFront |
| **Gateway** | API Gateway, Load Balancer (ALB) |
| **Microsserviços** | Usuários, Gamificação, Conteúdo, Mentoria, Fórum, Notificação |
| **Mensageria** | Amazon SQS (Filas de Notificações e Eventos) |
| **Processamento** | Worker Transmissão, AWS Lambda |
| **Notificações** | SES (email), SNS (push), Twilio (SMS) |
| **Dados** | RDS PostgreSQL (Primary + Read Replica), S3, Redis Cache |

### Padrões de Design Adotados
- **Repository Pattern:** Abstração do acesso a dados
- **Service Layer Pattern:** Encapsulamento da lógica de negócio
- **DTO Pattern:** Transferência de dados entre camadas
- **Strategy Pattern:** Diferentes algoritmos de geração de missões e cálculo de XP
- **Observer Pattern:** Notificações de level up e conquistas
- **Factory Pattern:** Criação de missões diárias

### Decisões Arquiteturais Importantes
1. **Monólito Modular vs Microsserviços:** Escolhido monólito por simplicidade inicial, mas com módulos bem definidos (XP, Rankings, Missões, Conteúdos) para facilitar extração futura.
2. **Banco Relacional vs NoSQL:** PostgreSQL escolhido pela consistência ACID necessária para transações de XP e DevCoins.
3. **Cache Distribuído:** Redis implementado para rankings semanais (evita sobrecarga no banco).
4. **Event-Driven:** RabbitMQ para eventos assíncronos (ex: notificações de level up, atualização de ranking).

### Trade-offs
- **Monólito:** ✅ Simplicidade de deploy, ✅ transações ACID, ⚠️ acoplamento inicial, ⚠️ escalabilidade vertical limitada.
- **Cache:** ✅ Performance, ⚠️ complexidade de invalidação, ⚠️ consistência eventual.

### Exemplos de diagramas

| Diagrama de Arquitetura | Detalhe da Arquitetura |
| :---: | :---: |
| **Visão Geral (Macro)** | **Camada de Serviços (XP Engine)** |
| <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=Arquitetura+Macro" alt="Diagrama de Visão Geral" width="300"> | <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=XP+Engine" alt="Diagrama XP Engine" width="300"> |
| **Modelo de Dados (DER)** | **Fluxo de Autenticação** |
| <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=DER" alt="Diagrama Entidade-Relacionamento" width="300"> | <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=Login+Flow" alt="Diagrama de Sequência - Login" width="300"> |
| **Infraestrutura (AWS)** | **API Endpoints** |
| <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=AWS+Deploy" alt="Diagrama de Deploy AWS" width="300"> | <img src="https://via.placeholder.com/300x200/2d2d2d/00ff88?text=API+Map" alt="Mapa de Endpoints" width="300"> |

---

## 📂 Estrutura do Repositório


## 📁 Codigo

Contém os arquivos-fonte da modelagem UML em PlantUML (`.puml`).

```bash
Codigo/
│
├── Caso de Uso/
│   └── diagrama-de-caso-de-uso.puml
│
├── Classe/
│   └── diagrama-de-classes-devlevel.puml
│
├── Componente e Implantação/
│   └── diagrama-de-componentes-e-implantacao.puml
│
├── Entidade Relacionamento/
│   └── diagrama-er.puml
│
├── Estado/
│   ├── diagrama-de-estado-badge.puml
│   ├── diagrama-de-estado-conteudo.puml
│   ├── diagrama-de-estado-missao-diaria.puml
│   ├── diagrama-de-estado-nivel-aluno.puml
│   └── diagrama-de-estado-solicitacao-mentoria.puml
│
└── Sequencia/
    ├── diagrama-de-sequencia-UC-01.puml
    ├── diagrama-de-sequencia-UC-02.puml
    ├── diagrama-de-sequencia-UC-03.puml
    ├── diagrama-de-sequencia-UC-04.puml
    ├── diagrama-de-sequencia-UC-05.puml
    ├── diagrama-de-sequencia-UC-07.puml
    ├── diagrama-de-sequencia-UC-08.puml
    ├── diagrama-de-sequencia-UC-09.puml
    ├── diagrama-de-sequencia-UC-10.puml
    ├── diagrama-de-sequencia-UC-11.puml
    ├── diagrama-de-sequencia-UC-12.puml
    ├── diagrama-de-sequencia-UC-14.puml
    └── diagrama-de-sequencia-UC-15.puml
```

---

## 📁 Modelagem

Contém as imagens exportadas dos diagramas UML utilizados na documentação do sistema.

```bash
Modelagem/
│
├── Caso de Uso/
│   └── caso-de-uso-devlevel.png
│
├── Classe/
│   └── classes-devlevel.png
│
├── Comunicação/
│   ├── Comunicação-UC09.png
│   └── comunicação-UC12.png
│
├── ER/
│   └── diagrama-er-devlevel.png
│
├── Estado/
│   ├── diagrama-de-estado-badge.png
│   ├── diagrama-de-estado-conteudo.png
│   ├── diagrama-de-estado-missao-diaria.png
│   ├── diagrama-de-estado-nivel-aluno.png
│   └── diagrama-de-estado-solicitacao-mentoria.png
│
└── Sequencia/
    ├── diagrama-de-sequencia-UC-01.png
    ├── diagrama-de-sequencia-UC-02.png
    ├── diagrama-de-sequencia-UC-03.png
    ├── diagrama-de-sequencia-UC-04.png
    ├── diagrama-de-sequencia-UC-05.png
    ├── diagrama-de-sequencia-UC-07.png
    ├── diagrama-de-sequencia-UC-08.png
    ├── diagrama-de-sequencia-UC-09.png
    ├── diagrama-de-sequencia-UC-10.png
    ├── diagrama-de-sequencia-UC-11.png
    ├── diagrama-de-sequencia-UC-12.png
    ├── diagrama-de-sequencia-UC-14.png
    └── diagrama-de-sequencia-UC-15.png
```

---

## 📁 Documentação
Contém a documentação do trabalho final.

```bash
Modelagem/
│
├── Trabalho Final - DevLevel.png
│
```

- Introdução e contextualização do problema
- Modelos de Usuário e Requisitos (Atores, Casos de Uso)
- Diagramas de Sequência do Sistema e Contratos de Operação
- Modelos de Projeto (Arquitetura, Componentes, Classes, Sequência, Comunicação, Estados)
- Modelos de Dados (DER, Esquema do Banco, Estratégias de Mapeamento)
---


## 👥 Autor

| 👤 Nome | 🖼️ Foto | :octocat: GitHub | 💼 LinkedIn | 📤 Gmail |
|---------|----------|-----------------|-------------|-----------|
| Karen Joilly | <img src="https://raw.githubusercontent.com/karenjoilly11/Resenha-de-Artigos-Projeto-de-Software/main/assets/fotokaren.jpg" width="70px" height="70px"> | <div align="center"><a href="https://github.com/vcaraujo"><img src="https://joaopauloaramuni.github.io/image/github6.png" width="50px"></a></div> | <div align="center"><a href="https://www.linkedin.com/in/karen-joilly-araujo-gregorio-de-almeida/"><img src="https://joaopauloaramuni.github.io/image/linkedin2.png" width="50px"></a></div> | <div align="center"><a href="mailto:karenjoilly@gmail.com"><img src="https://joaopauloaramuni.github.io/image/gmail3.png" width="50px"></a></div> |

---

## 📄 Licença

Este projeto é distribuído sob a **[Licença MIT](https://opensource.org/licenses/MIT)** para fins acadêmicos.

---

**Desenvolvido como trabalho acadêmico para a disciplina de Projeto de Software.**
