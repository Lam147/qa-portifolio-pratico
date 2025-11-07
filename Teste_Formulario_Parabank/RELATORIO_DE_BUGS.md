# 🐛 Relatório de Defeitos (Bugs Report) - Parabank

**Alvo:** Módulos de Login e Registro.
**Ambiente:** Chrome v100, Windows 10.

---

### Defeito #001: Cadastro Permite Senha Fraca

**Módulo:** Cadastro de Usuário (Register)
**Severidade:** Alta (Risco de Segurança)

**Passos para Reproduzir:**
1. Acessar a página de Cadastro (/register.htm).
2. Preencher o formulário.
3. Inserir a senha simples: `123456`.
4. Clicar em 'REGISTER'.

**Resultado ATUAL:**
Conta criada e autenticada com sucesso, aceitando a senha fraca ('123456').

**Resultado ESPERADO:**
Exibir mensagem de erro de validação de segurança, exigindo maior complexidade (ex: no mínimo 8 caracteres, com números e letras).

**Evidência:** [Screenshot do Bug 001](EVIDENCIAS/bug_001_senha_fraca.png)

---

### Defeito #002: Erro Interno ao Deixar Campo Obrigatório Vazio

**Módulo:** Cadastro de Usuário (Register)
**Severidade:** Média (Prejudica a usabilidade e expõe erro de sistema.)

**Passos para Reproduzir:**
1. Acessar a página de Cadastro (/register.htm).
2. Preencher todos os campos obrigatórios, **exceto** o campo 'Last Name' (deixá-lo vazio).
3. Clicar em 'REGISTER'.

**Resultado ATUAL:**
O sistema exibe a mensagem de erro: "An internal error has occurred and has been logged."

**Resultado ESPERADO:**
O sistema deve exibir uma mensagem de validação amigável e clara, específica para o campo, como: "Last Name é um campo obrigatório."

**Evidência:** [Screenshot do Bug 002](EVIDENCIAS/bug_002_erro_interno.png)

---
