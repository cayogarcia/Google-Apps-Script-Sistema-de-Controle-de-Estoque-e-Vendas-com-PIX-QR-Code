# 📈 Sistema de Controle de Estoque e Vendas para Google Sheets

Este projeto é um sistema de gerenciamento de vendas e estoque construído utilizando **Google Apps Script (GAS)**, atuando como um poderoso backend para uma planilha do Google Sheets. Ele automatiza o lançamento de vendas, o controle de inventário, a formatação da planilha e a geração de QR Codes PIX dinâmicos.

## ✨ Funcionalidades Principais

* **Lançamento de Vendas Simplificado:** Interface de usuário (UI) modal personalizada para o lançamento rápido de novas vendas, incluindo seleção dinâmica de produtos, modelos e tamanhos.
* **Gestão de Estoque em Tempo Real:** Recálculo automático do estoque disponível (com base nas vendas) e aplicação de formatação condicional para alertar sobre níveis baixos de estoque.
* **Geração de QR Code PIX:** Geração automática e dinâmica de QR Codes PIX (usando a URL de QR Code e o valor da venda) para pagamentos instantâneos.
* **Dashboard Automático:** Atualização em tempo real de um Dashboard com gráficos de vendas por dia e análises de formas de pagamento (Dinheiro, PIX, Cartão).
* **Formatação e Validação:** Aplicação automática de bordas, formatação monetária (`R$`) e validações de dados (ex: Status de Pagamento) para manter a integridade visual da planilha.
* **Menu Personalizado:** Item de menu "Vendas" no Google Sheets para acesso rápido às funcionalidades, incluindo a abertura do pop-up do QR Code da venda selecionada.

## ⚙️ Tecnologias Utilizadas

* **Google Apps Script (GAS):** Lógica de backend e automação de planilhas.
* **Google Sheets:** Banco de dados e visualização de dados.
* **HTML Service (GAS):** Criação das interfaces modais (`Adicionar Venda` e `QR Code PIX`).
