# 🍕 Sistema de Pedidos Inteligente para Pizzaria

[![GitHub pages](https://img.shields.io/badge/GitHub%20Pages-Ativo-success?style=flat-square&logo=github)](https://seu-usuario.github.io/seu-repositorio/)
[![Hospedagem](https://img.shields.io/badge/Acesso%20Mobile-Mobile--First-orange?style=flat-square)](#)

Um sistema dinâmico e interativo de montagem de pedidos desenvolvido sob medida para smartphones. O projeto guia o usuário de forma fluida através de etapas intuitivas, calculando valores em tempo real e gerando um relatório estruturado pronto para envio via WhatsApp.

---

## 🚀 Demonstração

Visualizar o projeto na prática: [Acesse o Deck R via GitHub Pages](https://angelicalorenz.github.io/SistemaParaDelivery/)

> 📱 **Nota de Design:** Este projeto foi projetado com uma abordagem *Mobile-First*. Para uma experiência ideal em computadores, utilize o modo de inspeção do navegador ajustado para dispositivos móveis (como iPhone ou Android).

---

## ⚙️ Funcionalidades Principais

* **Fluxo de Etapas Guiado (Step-by-Step):** Interface dividida em seções que aparecem progressivamente para evitar a sobrecarga cognitiva do cliente.
* **Validação de Regras de Negócio Dinâmicas:**
  * Limitação automática do número de sabores com base no tamanho selecionado da pizza.
  * Atualização dinâmica da tabela de preços de recheio (**Mais Recheio** vs. **Quantidade Tradicional**) com base no tamanho escolhido.
* **Barra de Progresso Visual:** Indicador de progresso em tempo real na seleção de sabores para garantir que o usuário saiba exatamente quanto pode escolher.
* **Filtros e Busca Inteligente:** Sistema de filtragem de sabores por categorias (Tradicionais, Especiais e Doces) combinado com um campo de busca por texto funcional.
* **Ativação de Ofertas (Gancho de Marketing):** Botão promocional que altera instantaneamente o estado global da aplicação, aplicando regras e preços fixos específicos para a "Oferta do Dia".
* **Fechamento e Integração com WhatsApp:** Compilação de todos os dados do pedido (produtos, adicionais, dados do cliente, troco e entrega) em uma mensagem perfeitamente formatada usando a API do WhatsApp.

---

