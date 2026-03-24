# 🎙️💸 Finanças na Voz - Desafio DIO

Este repositório contém a documentação e o processo de criação do MVP "Finanças na Voz", um projeto prático desenvolvido para exercitar o conceito de Vibe Coding e a estruturação de Prompts (PRD).

## 📱 Sobre o Aplicativo (Resumo)
O **Finanças na Voz** é um aplicativo de controle financeiro "mobile-first" que elimina o atrito das planilhas manuais. Através de uma interface de chat fluida, o usuário simplesmente digita (ou fala) seus gastos, como "Gastei 50 no almoço", e o sistema utiliza processamento de linguagem natural para extrair o valor, categorizar a despesa e atualizar o dashboard financeiro em tempo real. O foco é simplicidade e redução de carga cognitiva para o usuário.

---

## 📄 Prompt Final (PRD - Product Requirements Document)

Abaixo está o documento base utilizado para guiar a Inteligência Artificial (Lovable) na construção da interface e da lógica do aplicativo:

**Contexto:** Criar um aplicativo de Organização de Finanças Pessoais via chat em linguagem natural.
**Problema:** Alta desistência no controle de gastos devido à entrada manual e formulários complexos.
**Público-Alvo:** Iniciantes que buscam praticidade.

**Funcionalidades-Chave:**
1. Registrar gastos via chat em linguagem natural.
2. Classificar automaticamente as transações.
3. Definir e acompanhar metas financeiras.
4. Receber dicas de economia do “Agente Financeiro”.
5. Visualizar relatórios simples e personalizados.

**Stack Sugerida:** React, Tailwind CSS, Lucide Icons e lógica de extração simulada (NLP) via Vibe Coding.

---

## 📸 Demonstração e Interações com a IA

> **Nota:** Abaixo estão os registros visuais de como a IA interpretou os comandos e gerou a interface do aplicativo.

* **[Substitua este texto pela Imagem 1: Print da interface inicial do chat gerada pelo Lovable]**
* **[Substitua este texto pela Imagem 2: Print ou GIF mostrando a extração de um gasto no chat]**
* **[Substitua este texto pela Imagem 3: Print do dashboard atualizado]**

---

## 🧠 Reflexão sobre o Processo

### O que funcionou bem?
* A estruturação do PRD antes de codar fez toda a diferença. A IA entendeu o contexto e gerou uma interface muito próxima do imaginado logo na primeira tentativa.
* O uso do conceito de *Vibe Coding* permitiu focar no fluxo do usuário e no design (a "vibe"), deixando a complexidade do React e do Tailwind CSS para a IA resolver rapidamente.

### O que não funcionou como o esperado?
* Pedir para a IA implementar a interface visual e a lógica de processamento de dados (NLP) no mesmo prompt gerou confusão. Foi necessário dividir o processo em etapas: primeiro a "casca" (UI) e depois a inteligência do chat.
* Alguns pequenos ajustes de layout exigiram comandos mais específicos de CSS, pois a IA tendia a usar padrões genéricos se não fosse bem direcionada.

### O que aprendi sobre conversar com IAs?
* **Contexto é rei:** Quanto mais detalhado for o cenário (como o uso de um PRD), menor é a chance de alucinação.
* **Iteração em passos curtos:** É muito mais eficiente construir o app em camadas (UI primeiro, dados mockados depois, lógica complexa por último) do que pedir um sistema completo de uma vez.
* **A IA é uma parceira de execução, não de estratégia:** Eu precisei definir as regras de negócio; a IA apenas traduziu isso para código.
