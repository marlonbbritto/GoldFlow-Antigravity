# 🚀 GoldFlow Antigravity: Squad de Desenvolvimento Autônomo (Stack-Agnostic)

Este projeto utiliza a arquitetura de workspace local do **Google Antigravity** para orquestrar um squad de agentes de IA especialistas. O diferencial deste framework é a sua natureza **dinâmica**: todas as definições técnicas, linguagens e padrões arquiteturais são governados centralmente pelo arquivo \STACK.md\.

## 🧠 O Squad (Personas Dinâmicas)
Cada agente possui um papel estrito definido no \AGENTS.md\, adaptando o seu comportamento à stack escolhida:
* **@po (Product Owner)**: Responsável pelos requisitos de negócio e User Stories no modelo INVEST.
* **@architect**: Guardião dos princípios SOLID e da **arquitetura definida no STACK.md** (Hexagonal, Clean, MVC, etc.).
* **@qa_eng**: Responsável pelos critérios de aceite, Shift-Left Testing e validação E2E, respeitando as metas de cobertura de testes do projeto.
* **@ux_ui**: Define o Design DNA e prototipa telas baseadas nos parâmetros do sistema.
* **@agile**: Orquestra o fluxo de tarefas, garantindo que o desenvolvimento siga os padrões técnicos vigentes.
* **@backend_dev / @frontend_dev**: Execução técnica rigorosa conforme a linguagem e frameworks definidos no Stack.
* **@sec**: Auditor de segurança, guardião do fluxo de proteção de dados e do \.gitignore\.
* **@devops**: Gerente do terminal, ambiente local e fluxo de CI/CD.

## 🛠️ Fluxos de Trabalho (Workflows)
1. **\/criar-us\**: Planejamento estratégico onde a tríade (@po, @architect, @qa_eng) desenha a funcionalidade baseada na arquitetura escolhida.
2. **\/desenvolver-us\**: Execução atômica com foco em TDD, garantindo que o código passe nos testes e cumpra as metas de cobertura antes do commit.

## ⚖️ Padrões e Guardrails (A Fonte da Verdade)
* **Governança via \STACK.md\**: Este arquivo define se o projeto será Java, Node, Python, Angular, React, etc.
* **Rigor Técnico**: Aderência total ao Clean Code e SOLID, independentemente da tecnologia.
* **Qualidade Assegurada**: O squad está programado para rejeitar entregas que não atinjam a cobertura de testes mínima definida no Stack.
* **Segurança e Privacidade**: Sistema de **Blindagem Dupla** (\.gitignore\ + \.mcpignore\) para proteção total de dados locais e remotos.

## 📂 Estrutura do Projeto
* **\STACK.md\**: A "Constituição" técnica do projeto.
* **\_planejamento_squad/\**: Blueprints e User Stories validadas.
* **\.agents/\**: Inteligência, regras e skills do squad.
* **\.mcpignore\**: Firewall de I/O exclusivo para a Inteligência Artificial.
