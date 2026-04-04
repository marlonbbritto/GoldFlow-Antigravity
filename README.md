# 🚀 GoldFlow Antigravity: Squad de Desenvolvimento Autônomo

Este framework utiliza o **Google Antigravity** para orquestrar um squad de agentes de IA. A governança técnica é centralizada no \STACK.md\, tornando o template compatível com qualquer tecnologia.

## 🧠 O Squad (Personas)
* **@po**: Requisitos de negócio e User Stories (INVEST).
* **@architect**: Guardião da arquitetura definida no \STACK.md\.
* **@qa_eng**: Validação E2E e guardião das metas de cobertura de testes.
* **@agile**: Orquestração de tarefas e disciplina da esteira.
* **@backend_dev / @frontend_dev**: Execução técnica conforme a Stack.
* **@sec**: Auditor de segurança e integridade de commits.
* **@devops**: Gestão de ambiente e controle de versão.

## 🛠️ Fluxos de Trabalho
1. **/criar-us**: Planejamento salvo em \docs/user_stories/\.
2. **/desenvolver-us**: Desenvolvimento orientado a testes (TDD) e conformidade com a Stack.

## 📂 Estrutura
* **STACK.md**: Definições de tecnologia e metas de qualidade.
* **docs/user_stories/**: Documentação oficial e versionada das funcionalidades.
* **.agents/**: Inteligência e regras do squad.

## 🛡️ Segurança: Prevenção contra Exfiltração
Para evitar ataques de **Indirect Prompt Injection** via Browser Subagent, recomendamos fortemente configurar a Allowlist do Antigravity:
1. Localize ou crie o arquivo: \~/.gemini/antigravity/browserAllowlist.txt\
2. Adicione apenas URLs locais confiáveis, por exemplo:
   \\\	ext
   http://localhost:3000
   http://localhost:4200
   http://localhost:8080
   http://127.0.0.1:*
   \\\
*Isso garante que o @qa_eng nunca acesse sites externos que possam tentar roubar o contexto do seu projeto.*

## 🚀 Superpoderes (Opcional - MCP)
Para elevar este squad ao nível máximo, recomendamos a instalação dos seguintes servidores MCP:
| Servidor | Agente Beneficiado | Função |
| :--- | :--- | :--- |
| **SonarQube MCP** | @sec & @qa_eng | Bloqueio de commits com Code Smells ou vulnerabilidades. |
| **Stitch MCP** | @ux_ui | Leitura de design tokens e geração de CSS pixel-perfect. |
| **GitHub MCP** | @devops | Automação total de Pull Requests e gestão de Issues. |
