# Projeto de Estudo: Controle de Despesas (Refund)

**⚠️ Aviso:** Este é um projeto desenvolvido exclusivamente para fins de estudo e aprimoramento de habilidades em JavaScript intermediário. Não possui fins comerciais ou financeiros e não deve ser utilizado para controle de despesas reais.

## 🎯 Sobre o Projeto

Esta é uma aplicação web simples de front-end que simula um sistema de solicitação de reembolso de despesas. O principal objetivo foi praticar e consolidar conceitos de JavaScript, como manipulação do DOM, gerenciamento de eventos e formatação de dados em tempo real, utilizando apenas JavaScript "puro" (Vanilla JS).

## ✨ Funcionalidades

- **Adicionar Despesa:** Formulário para inserir descrição, valor e categoria.
- **Listar Despesas:** Exibição das despesas em uma lista organizada.
- **Remover Despesa:** Exclusão de itens da lista.
- **Cálculo de Totais:** Atualização automática do valor total e da quantidade de despesas.
- **Formatação de Moeda (BRL):** O campo de valor é formatado dinamicamente para o padrão monetário brasileiro (R$) durante a digitação.

## 🧠 Conceitos de JavaScript Praticados

O desenvolvimento deste projeto focou na aplicação prática dos seguintes conceitos:

- **Manipulação do DOM:**
  - Seleção de elementos (`querySelector`, `getElementById`).
  - Criação dinâmica de elementos (`createElement`).
  - Adição de elementos à página (`append`).
  - Remoção de elementos (`remove`).
  - Manipulação de classes (`classList`) e atributos (`setAttribute`).
- **Gerenciamento de Eventos:**
  - Captura de submissão de formulários (`form.onsubmit`) e prevenção do comportamento padrão (`event.preventDefault()`).
  - Monitoramento de entrada de dados em inputs (`oninput`).
  - Delegação de eventos (`addEventListener` em um elemento pai para observar cliques em filhos).
- **Formatação de Dados:**
  - Uso de `toLocaleString()` para formatar números como moeda.
  - Manipulação de strings e uso de Expressões Regulares (RegExp) para limpar e converter valores.
- **Estrutura e Boas Práticas:**
  - Separação de responsabilidades em funções (`expenseAdd`, `updateTotals`, `formClear`).
  - Uso de `try...catch` para tratamento básico de erros.

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estrutura semântica do conteúdo.
- **CSS3:** Estilização e layout.
- **JavaScript (Vanilla):** Lógica da aplicação, interatividade e manipulação de dados.

## 🚀 Como Executar

1.  Clone este repositório para sua máquina local.
2.  Abra o arquivo `index.html` em seu navegador de preferência.

A aplicação estará pronta para uso.