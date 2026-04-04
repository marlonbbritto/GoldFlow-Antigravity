# 🚀 GoldFlow Antigravity: Squad de Desenvolvimento Autônomo

![Arquitetura GoldFlow](docs/img/architecture.png)
*Diagrama gerado via PlantUML (Salve a imagem neste caminho)*

O GoldFlow é um framework de engenharia de software orientado a agentes de IA, projetado para garantir que a automação siga rigorosos padrões de qualidade, independente da tecnologia escolhida.

## 🏗️ Arquitetura e Fluxo (Life Cycle)
A governança técnica é centralizada no \STACK.md\, tornando o template dinâmico e "Plug-and-Play".

1. **Definição (\STACK.md\)**: Onde você dita as regras e tecnologias do jogo.
2. **Planejamento (\/criar-us\)**: O squad desenha a solução e salva em \docs/user_stories/\.
3. **Implementação (\/desenvolver-us\)**: Execução técnica com TDD e foco em cobertura.
4. **Entrega**: Código auditado, documentado e seguro.

## 🧠 O Squad (Personas)
* **@po**: Requisitos de negócio e User Stories (INVEST). Salva em \docs/user_stories/\.
* **@architect**: Guardião da arquitetura definida no \STACK.md\.
* **@qa_eng**: Validação E2E e guardião das metas de cobertura de testes.
* **@sec**: Auditor de segurança, segredos e integridade de commits.
* **@agile / @devops**: Orquestração e gestão de ambiente.

## 🛡️ Segurança: Proteção contra Exfiltração
Para evitar ataques de **Indirect Prompt Injection** via Browser Subagent, configure a Allowlist:
- Arquivo: \~/.gemini/antigravity/browserAllowlist.txt\
- Conteúdo recomendado: \http://localhost:* \, \http://127.0.0.1:* \

## 🔌 Expansão via MCP (Superpoderes)
Este template é compatível com o Model Context Protocol. Recomendamos:
- **SonarQube MCP**: Análise estática de código em tempo real.
- **GitHub MCP**: Gestão automática de PRs e Issues.
