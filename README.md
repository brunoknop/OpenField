# ⚽ Campo Aberto: Predição de Futebol Open Source

**Campo Aberto** é uma API de alto desempenho desenvolvida em **.NET 9** voltada para a análise estatística e previsão de resultados do futebol brasileiro. O projeto combina dados técnicos (estatísticas de jogo) com o "calor" das notícias extra-campo (crises, desfalques e momento do time).

> **Status:** 🚧 Em Desenvolvimento (Fase de Modelagem)

---

## 🎯 Objetivo do Projeto

O mercado de dados esportivos é vasto, mas poucas ferramentas abertas conseguem cruzar **estatísticas frias** com **variáveis subjetivas**. O Campo Aberto nasce para preencher essa lacuna, inicialmente focado no **Campeonato Brasileiro**, transformando dados brutos em inteligência preditiva.

### 🚀 Diferenciais Técnicos

- **Arquitetura Limpa (Clean Architecture):** Organização profissional para garantir escalabilidade e testabilidade.
- **Engenharia de Dados:** Integração com APIs externas e processamento de notícias via Web Scraping.
- **Resiliência e Performance:** Uso estratégico de **Redis** para cache e **Polly** para tolerância a falhas.

---

## 🛠️ Tech Stack

| Tecnologia                | Finalidade                                           |
| :------------------------ | :--------------------------------------------------- |
| **.NET 10**               | Framework principal (C#)                             |
| **PostgreSQL**            | Banco de dados relacional (Histórico e Tabelas)      |
| **Redis**                 | Cache de alta performance e redução de latência      |
| **Docker**                | Containerização do ambiente (DevOps)                 |
| **Entity Framework Core** | ORM para persistência de dados                       |
| **Polly**                 | Implementação de Resiliência (Retry/Circuit Breaker) |

---

## 📈 Roadmap

- [ ] **Fase 1: Estrutura Base**
  - [ ] Configuração do ambiente Docker (Postgres/Redis).
  - [ ] Modelagem das entidades principais (Time, Jogo, Campeonato).
  - [ ] Implementação do serviço de consumo da API-Football.
- [ ] **Fase 2: Inteligência Extra-Campo**
  - [ ] Desenvolvimento de Worker Services para Web Scraping de portais (GE, UOL).
  - [ ] Implementação de lógica de pesos para notícias (sentimento e impacto).
- [ ] **Fase 3: O "Oráculo" (Cálculo)**
  - [ ] Motor de predição baseado em Distribuição de Poisson.
  - [ ] API Endpoints para consulta de rodadas e probabilidades.

---

## 🤝 Como contribuir

Este é um projeto **Open Source**. Se você gosta de futebol, estatística ou quer praticar as novidades do ecossistema .NET, sinta-se convidado para:

1. Abrir **Issues** com sugestões de novas variáveis para o modelo.
2. Contribuir com código via **Pull Requests**.
3. Melhorar a documentação técnica.

---

## 📄 Licença

Distribuído sob a licença **MIT**. Veja o arquivo `LICENSE` para mais detalhes.

---

_Desenvolvido com ❤️ por **Bruno Gabriel Knop**._
