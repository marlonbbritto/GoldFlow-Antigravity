---
description: Guia o desenvolvimento seguro e atÃ´mico de uma User Story validada, passando por codificaÃ§Ã£o, testes automatizados, testes de tela e commit --no-ff
---

## Passos a Seguir
1. **SeleÃ§Ã£o e Quebra de Tarefas:** Solicite ao usuÃ¡rio o nome do arquivo da US localizada em docs/user_stories/. Atue como @agile para ler o documento e criar uma lista de subtarefas atÃ´micas separando Backend e Frontend. Apresente a lista e **peÃ§a autorizaÃ§Ã£o** para iniciar.
2. **Desenvolvimento Backend:** Para a subtarefa de backend atual:
   - Atue como @backend_dev para escrever o cÃ³digo utilizando as tecnologias definidas no STACK.md.
   - Escreva e execute os testes unitÃ¡rios e de integraÃ§Ã£o obrigatÃ³rios.
   - Pare, atue como @devops para explicar os comandos de terminal necessÃ¡rios e **peÃ§a autorizaÃ§Ã£o** antes de rodÃ¡-los.
3. **Desenvolvimento Frontend:** Para a subtarefa de frontend atual:
   - Atue como @frontend_dev para escrever o cÃ³digo utilizando as tecnologias definidas no STACK.md.
   - Pare, explique comandos de compilaÃ§Ã£o via @devops e **peÃ§a autorizaÃ§Ã£o** para executÃ¡-los no terminal.
4. **Teste de Interface (QA E2E):** Com a aplicaÃ§Ã£o rodando, atue como @qa_eng e ative a habilidade qa-browser-validation para utilizar o Browser Subagent. Navegue pela aplicaÃ§Ã£o simulando um usuÃ¡rio para validar os CritÃ©rios de Aceite da US. Apresente os resultados ou screenshots ao usuÃ¡rio.
5. **Entrega e Commit:**
   - Atue como @sec para verificar se todos os testes passaram e se nada sensÃ­vel vazarÃ¡ no commit.
   - Se aprovado, atue como @devops INVOCANDO OBRIGATORIAMENTE a habilidade pr-commit-standards. Prepare os comandos de commit utilizando a semÃ¢ntica correta (Conventional Commits) e a uniÃ£o via git merge --no-ff.
   - **PeÃ§a autorizaÃ§Ã£o final** antes de rodar os comandos do Git.
