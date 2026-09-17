# Contribuindo com o Vestibuline

Antes de mais nada: obrigado pelo interesse em contribuir! O Vestibuline é um projeto de software em construção, aberto a contribuidores de qualquer nível de experiência. Este guia serve como padrão para todos os repositórios da organização — cada repositório específico pode ter um `CONTRIBUTING.md` próprio com detalhes adicionais (setup local, scripts, etc.); quando existir, ele complementa este documento.

Ao contribuir, você concorda em seguir nosso [Código de Conduta](./CODE_OF_CONDUCT.md).

## Antes de começar

- Dê uma olhada nas *Issues* abertas do repositório que te interessa — pode já existir alguém trabalhando no mesmo problema.
- Para mudanças grandes ou que envolvam decisão de arquitetura, abra uma *Issue* de discussão antes de começar a codar. Isso evita retrabalho.
- Issues marcadas como `good first issue` são um bom ponto de partida para quem está chegando agora.

## Como o projeto está organizado

O Vestibuline é dividido em repositórios por camada:

| Repositório | Stack | O que é |
|---|---|---|
| `frontend` | Next.js + React + TypeScript + TailwindCSS | Interface do aluno |
| `backend` | Java | BFF, regras de domínio e motor de cálculo de desempenho |
| `IA` | Node.js + Google Gemini | Processamento de documentos e integração com IA |
| `APPS` | — | Apps auxiliares do ecossistema |
| `docs` | — | Documentação geral do projeto |

Vários fluxos (ex.: VestIA, integração Planner ↔ desempenho) ainda estão em construção — se algo parecer incompleto, provavelmente é porque está mesmo. Sinta-se à vontade para perguntar na Issue antes de assumir que é um bug.

## Fluxo de contribuição

1. Faça um fork do repositório desejado.
2. Crie uma branch a partir de `main` com um nome descritivo:
   `feature/nome-da-feature`, `fix/nome-do-bug`, `docs/o-que-mudou`.
3. Faça commits pequenos e com mensagens claras. Recomendamos o padrão [Conventional Commits](https://www.conventionalcommits.org/pt-br/):
   - `feat: adiciona X`
   - `fix: corrige Y`
   - `docs: atualiza Z`
   - `refactor:`, `test:`, `chore:` conforme o caso
4. Garanta que o projeto builda e os testes existentes passam localmente antes de abrir o Pull Request.
5. Abra o Pull Request contra a branch `main`, preenchendo o template que aparece automaticamente.
6. Aguarde a revisão — pode ser que peçamos ajustes antes do merge.

## Padrões de código

- Siga o estilo já usado no arquivo/módulo que você está editando (indentação, nomenclatura, organização de pastas).
- Evite misturar refatoração de código não relacionado com a mudança principal do PR — isso dificulta a revisão.
- Comente código complexo, especialmente lógica de cálculo de desempenho e regras pedagógicas, que não são óbvias só lendo o código.
- Não commite segredos, chaves de API ou credenciais. Use `.env.example` como referência do que precisa ser configurado localmente.

## Reportando bugs

Abra uma *Issue* usando o template de bug (`🐛 Bug Report`) e inclua:
- Passos para reproduzir
- Comportamento esperado vs. observado
- Ambiente (navegador, SO, versão do Node/Java, etc.)
- Prints ou logs, se fizer sentido

## Sugerindo melhorias

Abra uma *Issue* usando o template de sugestão (`✨ Feature Request`) explicando o problema que a melhoria resolve, não só a solução — isso ajuda a avaliar se ela se encaixa na direção do produto.

## Dúvidas

Se não tiver certeza de algo, abra uma *Issue* com a tag `question` ou pergunte na comunidade do Discord do Vestibuline.
