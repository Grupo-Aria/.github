# Como contribuir

Este guia vale para todos os repositórios da organização Grupo-Aria, salvo quando o repositório tiver o próprio `CONTRIBUTING.md`.

## Fluxo de trabalho

1. Abra (ou escolha) uma **issue** descrevendo o que será feito.
2. Crie um branch a partir de `main`: `tipo/descricao-curta` (ex.: `feat/login-google`, `fix/assinatura-outlook`, `docs/catalogo`).
3. Faça commits pequenos e descritivos. Recomendamos [Conventional Commits](https://www.conventionalcommits.org/pt-br/): `feat:`, `fix:`, `docs:`, `chore:`, `refactor:`.
4. Abra um **pull request** para `main`, preencha o template e vincule a issue (`Closes #123`).
5. Aguarde a revisão de pelo menos uma pessoa do time responsável antes do merge.

## Padrões dos repositórios

- **Nome:** minúsculo, separado por hífen (`kebab-case`), de preferência com o prefixo do produto (ex.: `crm-aria`).
- **README:** todo repositório tem um README com: o que é, como rodar, como fazer deploy e quem é responsável.
- **Descrição e topics:** preenchidos no GitHub; sempre inclua o topic `aria`.
- **Segredos:** nunca commitar `.env`, chaves ou senhas. Use `.env.example` com valores fictícios.

## Dúvidas

Consulte a base de conhecimento (wiki-aria) ou fale com o time `@Grupo-Aria/admins`.
