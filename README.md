# 🎀 Mallulu Doces - Sistema de Gestão e Precificação

Este é um sistema web leve e intuitivo desenvolvido para a **Mallulu Doces**. Ele permite que confeiteiras organizem seus custos de produção, criem fichas técnicas detalhadas e calculem preços de venda de forma automática e precisa.

## 🚀 Funcionalidades

O sistema é dividido em três pilares principais:

1.  **📦 Cadastro de Ingredientes:** - Registro de nome, unidade de medida (kg, g, un, ml), quantidade da embalagem e preço pago.
    - Cálculo automático do custo por unidade de medida.
2.  **🧾 Fichas Técnicas (Receitas):**
    - Criação de receitas personalizadas.
    - Seleção de ingredientes cadastrados com cálculo de custo proporcional à quantidade usada.
    - Definição de rendimento (porções) para saber o custo unitário de cada doce.
3.  **💰 Calculadora de Precificação:**
    - Soma automática dos custos da ficha técnica.
    - Inclusão de custos fixos adicionais (como embalagens).
    - Definição de margem de lucro desejada (%) com sugestão instantânea de preço de venda.
4.  **📊 Exportação de Dados:**
    - Botão para exportar um resumo das precificações em formato **CSV** (Excel), permitindo backups externos.

## 🛠️ Tecnologias Utilizadas

Este projeto foi construído como um **Single Page Application (SPA)** simples, utilizando:

- **HTML5:** Estrutura semântica.
- **CSS3:** Design personalizado com a identidade visual da Mallulu Doces (paleta rosa e marrom) e responsividade para dispositivos móveis.
- **JavaScript (Vanilla):** Lógica de cálculos, manipulação do DOM e persistência de dados.
- **LocalStorage:** Banco de dados local do navegador, permitindo que as informações fiquem salvas sem a necessidade de um servidor/banco de dados online.

## 📱 Como usar no Celular

Para que o sistema funcione como um "aplicativo" no celular:

1.  Abra o arquivo `index.html` no navegador do celular (Chrome ou Safari).
2.  Toque no ícone de **Compartilhar** ou nos **Três Pontinhos** do menu.
3.  Selecione a opção **"Adicionar à Tela de Início"**.
4.  Pronto! Um ícone da Mallulu Doces aparecerá na tela principal do celular.

## 💾 Persistência de Dados

> [!IMPORTANT]
> Os dados são salvos no **navegador do aparelho** (computador ou celular). 
> - Se você limpar o histórico/cache do navegador, os dados podem ser apagados.
> - Os dados inseridos no celular não aparecem automaticamente no computador (e vice-versa), pois não há sincronização em nuvem. Use a função **Exportar** para fazer backups.

---
Desenvolvido para  Mallulu Doces.
