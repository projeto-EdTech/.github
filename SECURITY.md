# Política de Segurança

## Reportando uma Vulnerabilidade

Se você encontrou uma vulnerabilidade de segurança em qualquer repositório da organização Vestibuline, **por favor não abra uma Issue pública**. Divulgação pública antes da correção coloca usuários em risco.

Em vez disso, reporte de forma privada por um dos canais abaixo:

- **GitHub Security Advisories** (preferencial): na aba *Security* do repositório afetado, use "Report a vulnerability" para abrir um relatório privado diretamente com os mantenedores.
- **E-mail**: [inserir e-mail de contato de segurança da organização]

Inclua, sempre que possível:
- Descrição da vulnerabilidade e impacto potencial
- Passos para reproduzir (ou uma prova de conceito)
- Componente/repositório afetado e versão/commit
- Sugestão de mitigação, se tiver uma

## O que esperar depois do reporte

- Confirmação de recebimento em até 3 dias úteis.
- Avaliação inicial de severidade e impacto em até 7 dias úteis.
- Combinaremos com você um prazo razoável para correção antes de qualquer divulgação pública, e daremos crédito pelo reporte (a menos que você prefira anonimato).

## Escopo

Esta política cobre os repositórios públicos da organização `projeto-EdTech` (Vestibuline). Isso inclui, mas não se limita a:
- Vulnerabilidades de código (injeção, autenticação, autorização, exposição de dados)
- Segredos ou credenciais expostos acidentalmente no histórico de commits
- Configurações inseguras em integrações (Discord Bot, processamento de IA, pagamentos)

## Fora de escopo

- Vulnerabilidades que dependem de acesso físico ao dispositivo do usuário
- Ataques que exigem engenharia social contra mantenedores ou usuários
- Relatórios sobre dependências de terceiros já reportados publicamente e sem correção disponível (nesse caso, reporte diretamente ao mantenedor da dependência)

## Versões suportadas

O Vestibuline está em desenvolvimento ativo (MVP). Como ainda não há versionamento formal de releases, considere sempre a branch `main` de cada repositório como a versão suportada para fins de reporte de segurança.
