# 📋 Plano Simples de Teste: Parabank - Login e Cadastro

**URL da Aplicação Alvo:** https://parabank.parasoft.com/parabank/index.htm
**Data do Teste:** 2025-11-07
**Foco:** Validar o acesso e a integridade dos dados na criação de novas contas.

---

## 🎯 Escopo de Teste

A execução exploratória focou nas seguintes áreas:

| Área | Status | Notas |
| :--- | :--- | :--- |
| **1. Login (Autenticação)** | A testar | Sucesso e falha com credenciais inválidas. |
| **2. Registro (Cadastro)** | A testar | Validação de todos os campos obrigatórios. |
| **3. Validação de Campo** | A testar | Inserção de dados nulos, muito longos, e formatos inválidos. |
| **4. Segurança Básica (Senhas)** | A testar | Tentativa de cadastrar senhas fracas. |

## 📝 Regras de Validação Verificadas

1.  **Campos Vazios:** O sistema deve impedir o envio de qualquer formulário com campos obrigatórios vazios.
2.  **Senhas:** Senhas devem ser iguais nos campos 'Password' e 'Confirm'.
3.  **Mensagens de Erro:** As mensagens devem ser claras e indicar o erro específico ao usuário.

---
