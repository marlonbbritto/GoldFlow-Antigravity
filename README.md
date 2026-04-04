# 🚀 GoldFlow Antigravity: Squad de Desenvolvimento Autônomo

Este projeto utiliza a arquitetura de workspace local do **Google Antigravity** para orquestrar um squad de agentes de IA especializados[cite: 1, 2]. O objetivo é garantir alta qualidade técnica através de um ciclo de desenvolvimento rigoroso, onde a intervenção humana é focada em aprovações estratégicas[cite: 2].

## 🧠 O Squad (Personas)
Cada agente possui um papel estrito definido no `AGENTS.md` para evitar sobreposição de funções[cite: 16, 18]:
* **@po (Product Owner)**: Responsável pelos requisitos de negócio e User Stories no modelo INVEST[cite: 19].
* **@architect**: Guardião da Arquitetura Hexagonal, domínios ricos e princípios SOLID[cite: 20, 21].
* **@qa_eng**: Responsável pelos critérios de aceite, Shift-Left Testing e validação E2E via navegador[cite: 22, 23].
* **@ux_ui**: Define o Design DNA e extrai metadados visuais via Google Stitch[cite: 24, 25].
* **@agile**: Orquestra o fluxo de tarefas e garante a disciplina da esteira[cite: 26].
* **@backend_dev / @frontend_dev**: Execução técnica em Java 21+ e Angular LTS[cite: 27, 28].
* **@sec**: Auditor de segurança e guardião do `.gitignore`[cite: 29].
* **@devops**: Manipulação do terminal e fluxo de Git seguro[cite: 31].

## 🛠️ Fluxos de Trabalho (Workflows)
O squad opera através de comandos de barra (`/`) integrados ao Antigravity[cite: 47, 48]:

### 1. `/criar-us` (Planejamento)
Inicia o ciclo de **Shift-Left**, onde a tríade (@po, @architect, @qa_eng) debate e documenta a funcionalidade antes de qualquer código existir[cite: 49, 50, 52]. O planejamento é salvo na pasta `_planejamento_squad/` (ignorada pelo Git)[cite: 56, 57].

### 2. `/desenvolver-us` (Execução)
O @agile quebra a US em subtarefas atômicas[cite: 58, 60]. O desenvolvimento segue um ciclo rigoroso de codificação, testes unitários e testes de interface (E2E) simulados no navegador pelo @qa_eng[cite: 61, 63, 64, 66].

## ⚖️ Padrões e Guardrails
* **Backend**: Java 21+, Spring/Quarkus, Arquitetura Hexagonal e Clean Code[cite: 27, 37].
* **Frontend**: Angular (últimas versões LTS) com componentização estrita[cite: 28, 38].
* **Controle de Versão**:
    * Commits atômicos (máximo de ~300 linhas alteradas)[cite: 39].
    * Merges obrigatoriamente realizados com a flag `--no-ff` para preservar o histórico[cite: 40, 67].
* **Segurança**: A pasta de planejamento técnico (`_planejamento_squad/`) nunca deve ser commitada[cite: 10, 57].

## 📂 Estrutura do Projeto

* **`_planejamento_squad/`**: (Ignorado pelo Git) Contém blueprints, US validadas e planos de implementação.
* **`.agents/`**: Contém a "inteligência" do squad (regras, habilidades e workflows).
* **`AGENTS.md`**: Definição central das personas e limites de cada agente.

## ⚖️ Padrões de Engenharia

* **Backend**: Java 21+, frameworks Spring/Quarkus e domínios ricos.
* **Frontend**: Angular LTS e componentização estrita.
* **Git**: Commits atômicos (máximo ~300 linhas) e uso obrigatório de `git merge --no-ff`.

## ⚙️ Configuração do Workspace
Para este framework funcionar, as seguintes **Settings** devem estar ativas no Antigravity[cite: 3, 4]:
1. **Agent Mode**: `Planning Mode`[cite: 5].
2. **Artifact Review Policy**: `Request Review`[cite: 6].
3. **Terminal Command Execution**: `Request Review`[cite: 7].

---
*Este framework de governança foi estruturado para maximizar a autonomia da IA mantendo o controle de qualidade total pelo usuário.*
