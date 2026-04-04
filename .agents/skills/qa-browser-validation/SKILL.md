---
name: qa-browser-validation
description: Aciona o Browser Subagent nativo para abrir o navegador, navegar na aplicação web local e realizar testes manuais E2E simulados na interface para validar os Critérios de Aceite da User Story. Use sempre que uma subtarefa de Frontend ou integração for finalizada.
---

## Objetivo
Atuar como um Analista de QA realizando o teste de interface do usuário via navegação web real, garantindo que a implementação reflete os requisitos de negócio.

## Instruções Passo a Passo
1. **Validar Stack:** Leia o arquivo \STACK.md\ para identificar as tecnologias de Backend e Frontend e as portas padrão configuradas.
2. **Levantar Ambiente:** Verifique se os serviços de Backend e Frontend estão rodando conforme as instruções da tecnologia definida.
3. **Iniciar Browser Subagent:** Abra a URL local da aplicação (ex: localhost:4200, localhost:3000, etc., conforme a stack).
4. **Execução de Teste:** Siga rigorosamente os Critérios de Aceite na interface (cliques, preenchimento de formulários, fluxos).
5. **Captura de Evidências:** Gere screenshots ou gravações que comprovem o comportamento esperado ou as falhas encontradas.
6. **Aprovação:** Compare o resultado visual e funcional com o blueprint definido pelo @ux_ui e os critérios do @po.

## Restrições (Constraints)
- O teste DEVE ser feito interagindo com a interface gráfica real via Browser Subagent.
- **Sincronia Técnica:** Se o ambiente não subir, valide os comandos de execução no \STACK.md\ antes de reportar erro.
- Se falhar, documente com screenshot do console do navegador e devolva ao @backend_dev ou @frontend_dev conforme a natureza do bug.
