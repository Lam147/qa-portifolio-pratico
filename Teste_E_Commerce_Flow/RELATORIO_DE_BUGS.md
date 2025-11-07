# 🐛 Relatório de Defeitos (Bugs Report) - Swag Labs E-commerce

**Alvo:** Fluxo de Compra (Carrinho e Checkout)
**Ambiente:** Chrome v100, Windows 10.
**Usuário de Teste:** standard_user

---

### Defeito #001: Item Removido do Carrinho Reaparece no Checkout

**Módulo:** Carrinho e Checkout Overview
**Severidade:** Alta (Prejuízo ao cliente, falha na lógica de pagamento.)

**Passos para Reproduzir:**
1. Fazer login como `standard_user`.
2. Adicionar 3 produtos ao carrinho (Ex: Backpack, Bike Light, Jacket).
3. Navegar para o Carrinho (Cart).
4. Clicar no botão 'Remove' (Remover) no item "Bike Light".
5. Continuar o fluxo (Checkout, Informações, etc.).
6. Chegar à tela de 'Checkout: Overview'.

**Resultado ATUAL:**
O item "Bike Light", que foi removido, aparece novamente na tela de 'Overview' e é incluído no total de pagamento final.

**Resultado ESPERADO:**
O item removido na etapa 4 não deve mais aparecer no carrinho e não deve ser cobrado na tela de Overview.

**Evidência:** [Link para a evidência que será colocada na pasta EVIDENCIAS/]

---

### Defeito #002: Imagem Quebrada (Broken Image) na Tela de Produtos

**Módulo:** Inventário (Página inicial após Login)
**Severidade:** Baixa (Problema cosmético, mas afeta a confiança do usuário.)

**Passos para Reproduzir:**
1. Fazer login como `standard_user`.
2. Scrollar a página de inventário.

**Resultado ATUAL:**
A imagem do produto "Sauce Labs Bolt T-Shirt" não carrega e exibe o ícone de imagem quebrada.

**Resultado ESPERADO:**
Todas as imagens de produtos devem carregar corretamente.

**Evidência:** [Link para a evidência que será colocada na pasta EVIDENCIAS/]

---
