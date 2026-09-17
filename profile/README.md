# 🎯 Vestibuline

**O gargalo do vestibulando não é acesso a conteúdo — é direção.**

Existe conteúdo gratuito de sobra na internet. O que falta é saber o que estudar agora, por quê, e se aquilo está de fato aproximando o aluno da aprovação. O Vestibuline ataca esse problema transformando comportamento de estudo em dado: cada questão respondida, cada erro, cada tempo por questão alimenta um diagnóstico que devolve um caminho de estudo personalizado.

> 🚧 **Projeto em desenvolvimento ativo (MVP).** Não é uma empresa ou startup — é um projeto de software open-source, de longo prazo, aberto a qualquer pessoa interessada em contribuir.

---

## 💡 Princípios

- **Dados antes de intuição** — a recomendação vem da medição do desempenho real, não de um currículo genérico.
- **Transparência** — sem "fórmula mágica"; o produto mostra o caminho real, incluindo o que ainda não está pronto.
- **Acessibilidade como requisito** — precisa funcionar bem em celular modesto, conexão ruim e para quem tem dificuldade de leitura.
- **Qualidade sobre quantidade de features** — conectar bem o que já existe vale mais do que adicionar mais uma tela.

## 🧩 O que a plataforma oferece

**🏋️ Treino Realista**
Banco de questões das principais universidades do país, simulados que replicam o layout e a pressão das provas oficiais, e simulados personalizados por conteúdo, matéria ou banca.

**🧠 Diagnóstico e IA**
Feedback imediato (tempo por questão, acertos e erros categorizados), resolução de questões com explicação pedagógica via IA, e dashboards com projeção de desempenho.

**🎮 Gamificação e Fixação**
Mini-games de fixação (Flashcards, Lexoo, Nexo, Enigma), ranking e sistema de conquistas.

**📅 Planejamento**
Planner de estudos automatizado, consultor de notas de corte, e curadoria de questões em playlists.

## 🏗️ Arquitetura

| Camada | Tecnologia |
|---|---|
| Frontend | Next.js + React + TypeScript + TailwindCSS |
| BFF | Backend-for-Frontend, orquestrando Web/Mobile/Desktop |
| Backend | Java |
| Banco de dados | SQLite (MVP) → PostgreSQL |
| IA | Google Gemini (explicação de gabarito, ingestão de provas) |
| Comunidade | Discord (Bot + Activities) |

## 📂 Repositórios

| Repositório | O que é |
|---|---|
| [`frontend`](https://github.com/projeto-EdTech/frontend) | Interface do aluno |
| [`backend`](https://github.com/projeto-EdTech/backend) | BFF, regras de domínio e motor de cálculo de desempenho |
| [`IA`](https://github.com/projeto-EdTech/IA) | Processamento de documentos e integração com IA |
| [`APPS`](https://github.com/projeto-EdTech/APPS) | Apps auxiliares do ecossistema |
| [`docs`](https://github.com/projeto-EdTech/docs) | Documentação geral do projeto |

## 🤝 Como contribuir

O projeto está aberto a contribuidores de qualquer nível de experiência. Antes de começar:

1. Leia o [Código de Conduta](./CODE_OF_CONDUCT.md)
2. Siga o [Guia de Contribuição](./CONTRIBUTING.md)
3. Dê uma olhada nas *Issues* abertas nos repositórios acima — issues marcadas `good first issue` são um bom ponto de partida

Encontrou uma vulnerabilidade de segurança? Veja a [Política de Segurança](./SECURITY.md) antes de abrir uma Issue pública.

## 🌐 Links

- Site: [vestibuline.com](https://www.vestibuline.com)

---

<sub>Vestibuline é um projeto open-source, sem estrutura societária, comercial ou financeira.</sub>
