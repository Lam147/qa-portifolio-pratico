# 📋 Plano Simples de Teste: E-commerce - Swag Labs

**URL da Aplicação Alvo:** https://www.saucedemo.com/
**Data do Teste:** 2025-11-06
**Foco:** Testar o fluxo de compra de ponta a ponta (E2E) e a funcionalidade de filtros.

---

## 🎯 Escopo de Teste (Fluxo E2E)

A execução exploratória focará no "Caminho Crítico do Dinheiro":

1.  **Login:** Acesso com usuário padrão (`standard_user`).
2.  **Seleção de Produtos:** Adicionar itens ao carrinho.
3.  **Carrinho de Compras:** Verificar subtotal e remoção de itens.
4.  **Checkout (Informações):** Submeter dados do comprador.
5.  **Checkout (Overview):** Revisar valores finais e impostos.
6.  **Confirmação de Pedido:** Finalização da compra.

## 📝 Testes de Filtros e Ordenação

| Funcionalidade | Resultado Esperado | Status |
| :--- | :--- | :--- |
| **Filtro (A-Z)** | Produtos devem ser ordenados alfabeticamente. | A testar |
| **Filtro (Z-A)** | Produtos devem ser ordenados em ordem alfabética reversa. | A testar |
| **Filtro (Preço Baixo > Alto)** | Produto mais barato deve ser o primeiro da lista. | A testar |
| **Filtro (Preço Alto > Baixo)** | Produto mais caro deve ser o primeiro da lista. | A testar |

---
