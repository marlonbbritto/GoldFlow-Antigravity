# 🚀 GoldFlow Antigravity: Squad de Desenvolvimento Autônomo

Este projeto utiliza a arquitetura de workspace local do **Google Antigravity** para orquestrar um squad de agentes de IA especializados. O objetivo é garantir alta qualidade técnica através de um ciclo de desenvolvimento rigoroso, onde a intervenção humana é focada em aprovações estratégicas.

## 🧠 O Squad (Personas)
Cada agente possui um papel estrito definido no `AGENTS.md` para evitar sobreposição de funções:
* **@po (Product Owner)**: Responsável pelos requisitos de negócio e User Stories no modelo INVEST.
* **@architect**: Guardião da Arquitetura Hexagonal, domínios ricos e princípios SOLID.
* **@qa_eng**: Responsável pelos critérios de aceite, Shift-Left Testing e validação E2E via navegador.
* **@ux_ui**: Define o Design DNA e prototipa telas baseadas nos parâmetros do sistema.
* **@agile**: Orquestra o fluxo de tarefas e garante a disciplina da esteira.
* **@backend_dev / @frontend_dev**: Execução técnica conforme stack definido.
* **@sec**: Auditor de segurança e guardião do fluxo de proteção de dados (senhas, chaves) e do `.gitignore`.
* **@devops**: Manipulação do terminal e fluxo de controle de versão.

## 🛠️ Fluxos de Trabalho (Workflows)
O squad opera através de comandos de barra (`/`) integrados ao Antigravity:

### 1. `/criar-us` (Planejamento)
Inicia o ciclo de **Shift-Left**, onde a tríade (@po, @architect, @qa_eng) debate e documenta a funcionalidade antes de qualquer código existir. O planejamento é salvo na pasta `_planejamento_squad/` (ignorada pelo Git).

### 2. `/desenvolver-us` (Execução)
O @agile quebra a US em subtarefas atômicas. O desenvolvimento segue um ciclo rigoroso de codificação, testes unitários e testes de interface (E2E) simulados no navegador pelo @qa_eng nativo do Antigravity.

## ⚖️ Padrões e Guardrails
* **Backend**: Rigorosa aderência ao Clean Code, princípios SOLID, e Arquitetura Hexagonal.
* **Frontend**: Uso das melhores práticas de web web, com uso estrito de HTML, Vanilla CSS dinâmico (com animações/glassmorphism/cores vibrantes) ou frameworks (Next.js/Vite) se autorizado, priorizando interfaces ricas e modernas em substituição a páginas estáticas.
* **Controle de Versão**:
    * Commits atômicos e descritivos seguindo Conventional Commits.
    * Entregas no branch usando `git merge --no-ff` obrigatoriamente para preservar e evidenciar o trabalho encapsulado em features ou bugs resolvidas.
* **Segurança**: Antes do commit final, garante-se que nenhum dado exposto (chaves públicas/privadas, tokens) transite para o push. Pastas de planejamento técnico (`_planejamento_squad/`) e builds são protegidas via `.gitignore`.
* **Privacidade de Estágio**: O framework utiliza uma abordagem de **Blindagem Dupla** para permitir que a IA trabalhe em arquivos ignorados pelo Git sem sacrificar a segurança do repositório remoto.

## 📂 Estrutura do Projeto

* **`_planejamento_squad/`**: (Ignorado pelo Git) Contém blueprints, US validadas e planos de implementação.
* **`.agents/`**: Contém a "inteligência" do squad (regras, habilidades e workflows).
* **`AGENTS.md`**: Definição central das personas e limites de cada agente.
* **`.mcpignore`**: Firewall de I/O da Inteligência Artificial (protege caches, binários e dados sensíveis).

## 🛡️ Arquitetura de Blindagem Dupla

Para resolver o conflito entre o sigilo do Git e a necessidade de atuação da IA no Antigravity, utilizamos dois níveis de proteção:

1.  **Git Blindado (`.gitignore`)**: Impede que rascunhos técnicos, planos de implementação e pastas de build sejam enviados ao GitHub.
2.  **Firewall de IA (`.mcpignore`)**: É o filtro exclusivo para o Squad. Ele permite que as IAs leiam/escrevam na pasta `_planejamento_squad/`, mas as bloqueia rigorosamente de acessar dados sensíveis (`.env`), caches pesados ou metadados de IDE.

## ⚙️ Configuração do Workspace
Para este framework funcionar com perfeição e segurança, as seguintes políticas do Antigravity devem estar ativas:
1. **Agent Gitignore Access**: `On`. (Obrigatório! Permite que a IA salve planejamentos protegidos pelo Gitignore. A segurança de leitura agora é delegada ao `.mcpignore`).
2. **Shift-Left Testing**: Executar testes E2E pelo SubAgente do navegador nativo do Antigravity.
3. **Commit Governance**: Aprovação humana explícita antes do *push* e uso de `merge --no-ff`.

---
*Este framework de governança foi estruturado para maximizar a autonomia da IA mantendo o controle de qualidade total pelo usuário.*
