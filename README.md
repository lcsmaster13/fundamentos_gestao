markdown
# 🚀 Automação: Do Problema ao Produto com IA

**Planejamento Estratégico de Produto Digital | MVP | Roadmap | Gestão de Riscos**

---

## 1. 📄 Sobre o Projeto

Este repositório documenta o planejamento estratégico completo para o **Automação IA**, um produto digital SaaS baseado em IA Generativa. O objetivo é resolver a dor de times de atendimento ao cliente que possuem um alto volume de interações (tickets, chats, e-mails) e não conseguem extrair insights para priorizar ações críticas.

Este projeto foi desenvolvido como parte do desafio "Do Problema ao Produto", aplicando na prática os fundamentos de Gestão de Projetos e Produtos, com foco em visão, MVP, roadmap e riscos no contexto de IA.

**Status do Projeto:** `Planejamento Concluído`

---

## 2. 🗂️ Entregáveis do Projeto

A documentação completa está organizada nas seguintes ferramentas e arquivos:

### 📚 Documentação Teórica e Estratégica
*   **Documento Completo (Parte Teórica):** [`docs/1-documento-teorico.md`](docs/1-documento-teorico.md) - Visão, MVP, Roadmap, Ciclo de Vida e Riscos detalhados.
*   **Canvas de Visão do Produto:** [Link para o quadro no Miro](https://miro.com/app/board/uXjVH3VDTRw=/?share_link_id=859492094251)
*   **Prints dos Artefatos:** [`docs/prints/`](docs/prints/) - Capturas de tela do Canvas e Roadmap.

### 🗺️ Artefatos Práticos (Parte Visual e Documental)
*   **Documento do MVP:** [`docs/2-documento-mvp.md`](docs/2-documento-mvp.md) - Funcionalidades, priorização e critérios de aceitação.
*   **Roadmap Visual Interativo:** [Link para a página pública do Notion](https://app.notion.com/p/Planejamento-e-implementa-o-3ac5aea62357801abf27e7c792ac107e)
*   **Matriz de Riscos:** [`docs/3-matriz-de-riscos.md`](docs/3-matriz-de-riscos.md) - Identificação, classificação e planos de mitigação.

---

## 3. 🧠 Lógica do Planejamento e Como Interpretar os Artefatos

Aqui está o raciocínio estratégico por trás de cada decisão e como ler os artefatos criados.

### 🎯 A Visão Estratégica (Canvas no Miro)
O **Lean Canvas** no Miro foi a peça inicial. Ele nos forçou a validar o problema antes da solução.
*   **Problema vs. Solução:** Identificamos 3 problemas principais do cliente e os vinculamos diretamente a 3 funcionalidades-chave da nossa solução. Isso garante que cada feature combata uma dor real.
*   **Proposta de Valor Única:** "Transformar dados não estruturados de CX em planos de ação priorizados em minutos, não semanas." Esta frase guia toda a priorização do MVP. Qualquer funcionalidade que não a sustente diretamente foi movida para fases futuras.

### 🚀 A Definição do MVP (Documento MVP.md)
O MVP é um "motor de insights", não um dashboard complexo. A lógica de priorização foi baseada na matriz **Valor x Esforço**.
*   **Funcionalidade Core (Alto Valor, Alto Esforço):** O **motor de IA para sumarização de tickets**, que é o coração do produto. Sem ele, não há solução.
*   **Funcionalidade de Entrega (Alto Valor, Baixo Esforço):** O **painel de insights** mostrando os 3 principais temas e o plano de ação. É a interface que prova valor para o usuário em minutos.
*   **Funcionalidades Adiadas:** Busca avançada, integrações complexas e dashboards customizáveis foram deixadas para o Roadmap pós-MVP, pois exigem um esforço de desenvolvimento que não valida a hipótese central mais rápido.

### 🗺️ O Roadmap Evolutivo (Página do Notion)
O Roadmap no Notion é uma **Timeline View** de uma base de dados. Ele foi estruturado em 3 fases, seguindo a lógica do duplo-diamante: divergir para explorar, convergir para entregar.
*   **Fase 1 - Fundação (MVP):** Foco exclusivo em **Viabilidade Técnica e Valor Central**. O objetivo é ter 1 cliente usando o motor de sumarização e provando que a IA gera insights úteis. O critério de sucesso não é receita, é tempo economizado.
*   **Fase 2 - Crescimento:** Foco em **Desejabilidade e Escala**. Após validar o valor, adicionamos integrações (Zendesk, Salesforce) para reduzir o atrito de entrada de dados e dashboards para diferentes personas (analistas vs. gestores).
*   **Fase 3 - Liderança:** Foco em **Diferenciação e Ecossistema**. Introduzimos features que ninguém copia rápido, como previsão de churn ("Clientes em Risco") e recomendações prescritivas, transformando o produto de reativo para preditivo.

### ⚠️ A Gestão de Riscos Aplicada à IA (Matriz de Riscos)
A matriz de riscos não é genérica; ela é contextualizada para IA. Três riscos são críticos e definiram ações no roadmap:
1.  **Alucinação da IA:** Não podemos recomendar ações baseadas em informações falsas. **Mitigação essencial:** Incluímos um "Módulo de Confiança" no MVP que sempre mostra o ticket original como referência, adicionando transparência. O sistema deve priorizar "precisão" em vez de "criatividade".
2.  **Viés Algorítmico:** A IA pode sub-representar reclamações de um grupo específico de clientes. **Mitigação:** Auditoria manual de uma amostra semanal de tickets como tarefa obrigatória na Fase 1, antes de escalar.
3.  **Segurança de Dados (LGPD):** Vamos lidar com dados sensíveis de clientes (PII). **Mitigação:** Anonimização de dados como um passo do pipeline *antes* de enviar para a API da IA. Este requisito funcional está explicitamente no Critério de Aceitação do MVP.

---

## 4. 🤝 Ferramentas e Tecnologias Utilizadas

*   **Documentação e Roadmap:** Notion
*   **Canvas de Produto:** Miro
*   **Versionamento e Entrega:** GitHub
*   **Linguagem de Marcação:** Markdown