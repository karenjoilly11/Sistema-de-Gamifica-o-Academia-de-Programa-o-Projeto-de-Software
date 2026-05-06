# 🏷️ DevLevel - Plataforma de Gamificação para Academia de Programação 👨‍💻

> [!NOTE]
> **Transforme o aprendizado de programação em uma jornada épica!** O DevLevel é uma plataforma que utiliza mecânicas de jogos (XP, níveis, missões diárias, rankings e conquistas) para aumentar o engajamento e reduzir a evasão em academias de programação.

<div align="center">
  <img src="https://via.placeholder.com/800x200/2d2d2d/00ff88?text=DevLevel+-+Level+Up+Your+Coding+Journey" alt="DevLevel Banner" width="100%"/>
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
        <img src="https://via.placeholder.com/120x120/2d2d2d/00ff88?text=D" alt="Logo DevLevel" width="120px"/>
      </div>
    </td>
  </tr>
</table>

---

## 🚧 Status do Projeto

[![GitHub Workflow Status](https://img.shields.io/github/actions/workflow/status/devlevel/devlevel/main.yml?branch=main)](https://github.com/devlevel/devlevel/actions/workflows/main.yml)
[![Test Coverage](https://codecov.io/gh/devlevel/devlevel/branch/main/graph/badge.svg)](https://codecov.io/gh/devlevel/devlevel)
[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue)](https://github.com/devlevel/devlevel/releases)
[![Licença](https://img.shields.io/github/license/devlevel/devlevel)](#licença)

[![Versão](https://img.shields.io/badge/Versão-v1.0.0-blue?style=for-the-badge)](https://github.com/devlevel/devlevel/releases)
![React](https://img.shields.io/badge/React-19.1.1-007ec6?style=for-the-badge&logo=react&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-7.1.2-007ec6?style=for-the-badge&logo=vite&logoColor=white)
![Java](https://img.shields.io/badge/Java-17-007ec6?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-3.3.5-007ec6?style=for-the-badge&logo=springboot&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-16-007ec6?style=for-the-badge&logo=postgresql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-27.0-007ec6?style=for-the-badge&logo=docker&logoColor=white)
![GitHub repo size](https://img.shields.io/github/repo-size/devlevel/devlevel?style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/devlevel/devlevel?style=for-the-badge)
![GitHub forks](https://img.shields.io/github/forks/devlevel/devlevel?style=for-the-badge)

---

## 📚 Índice
- [Links Úteis](#-links-úteis)
- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades Principais](#-funcionalidades-principais)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Arquitetura](#-arquitetura)
- [Instalação e Execução](#-instalação-e-execução)
- [Deploy](#-deploy)
- [Estrutura de Pastas](#-estrutura-de-pastas)
- [Demonstração](#-demonstração)
- [Testes](#-testes)
- [Documentações utilizadas](#-documentações-utilizadas)
- [Autores](#-autores)
- [Contribuição](#-contribuição)
- [Agradecimentos](#-agradecimentos)
- [Licença](#-licença)

---

## 🔗 Links Úteis

- 🌐 **Demo Online:** [Acesse a Aplicação Web](https://devlevel-demo.vercel.app)
  > 💻 **Descrição:** Ambiente de demonstração do DevLevel hospedado na Vercel.
- 📱 **Download Mobile:** Em desenvolvimento (previsto para v2.0)
- 📖 **Documentação Técnica:** [Acesse a Wiki](https://github.com/devlevel/devlevel/wiki)
  > 📚 **Descrição:** Documentação completa da API (Swagger/OpenAPI) e guias de arquitetura.

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
- **Redução comprovada da evasão** (projetada: de 45% para <15%)
- **Gamificação baseada em ciência comportamental** (reforço positivo, metas atingíveis)
- **Arquitetura escalável** (suporta dezenas de milhares de alunos)
- **Código aberto** (pode ser adaptado para outras áreas de ensino)

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

## 🛠 Tecnologias Utilizadas

### 💻 Front-end
- **Framework/Biblioteca:** React v18.3.1
- **Linguagem:** TypeScript 5.6
- **Estilização:** Tailwind CSS 3.4 + Shadcn/ui
- **Gerenciamento de Estado:** Zustand 4.5 + React Query 5.0
- **Build Tool:** Vite 5.4
- **Gráficos:** Recharts 2.12

### 🖥️ Back-end
- **Linguagem/Runtime:** Java 17 (JDK 17 LTS)
- **Framework:** Spring Boot 3.3.5
- **Banco de Dados:** PostgreSQL 16
- **ORM / Query Builder:** Hibernate 6.5 / JPA 3.1
- **Autenticação:** JWT (jjwt 0.12) + Spring Security 6.3
- **Cache:** Redis 7.2 (para rankings)
- **Documentação API:** SpringDoc OpenAPI 2.5

### ⚙️ Infraestrutura & DevOps
- **Containerização:** Docker 27.0 + Docker Compose 2.29
- **Orquestração:** Kubernetes (k3s para produção) - previsto v2.0
- **Cloud:** AWS (EC2, RDS, ElastiCache) + Vercel (Front-end)
- **CI/CD:** GitHub Actions + SonarQube
- **Monitoramento:** Prometheus + Grafana
- **Logs:** ELK Stack (Elasticsearch, Logstash, Kibana)

---

## 🏗 Arquitetura

A arquitetura do **DevLevel** segue o padrão **Monólito Modular** com clara separação de responsabilidades, preparado para futura migração para microsserviços.

### Visão Geral (Camadas)

| Camada | Responsabilidade | Tecnologia |
|--------|------------------|------------|
| **Apresentação** | Interface com usuário (Web) | React + Tailwind |
| **Gateway** | API Gateway, autenticação, rate limiting | Spring Cloud Gateway |
| **Aplicação** | Orquestração de casos de uso | Spring Boot Controllers |
| **Domínio** | Regras de negócio (XP, níveis, missões) | Java POJOs + Services |
| **Infraestrutura** | Acesso a dados, cache, mensageria | JPA/Hibernate + Redis + RabbitMQ |

### Padrões de Design Adotados
- **Repository Pattern:** Abstração do acesso a dados
- **Service Layer Pattern:** Encapsulamento da lógica de negócio
- **DTO Pattern:** Transferência de dados entre camadas
- **Strategy Pattern:** Diferentes algoritmos de geração de missões e cálculo de XP
- **Observer Pattern:** Notificações de level up e conquistas
- **Factory Pattern:** Criação de missões diárias
- **Decorator Pattern:** Cálculo de bônus (streaks, rankings)

### Fluxo de Dados Principal

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
