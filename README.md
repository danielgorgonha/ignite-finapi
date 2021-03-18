## FinAPI - Financeira

---

### Requisitos

- [x] Deve ser possível criar uma conta 
- [x] Deve ser possível buscar o extrato bancário do cliente
- [x] Deve ser possível realizar um depósito
- [x] Deve ser possível realizar um saque
- [x] Deve ser possível buscar o extrato bancário do client por data
- [] Deve ser possível atualizar dados da conta do cliente
- [] Deve ser possível obter dados da conta do cliente
- [] Deve ser possível deletar uma conta

---

## Regras de negócio

- [x] Não deve possível cadastrar uma conta com CPF já existente
- [x] Não deve possível fazer depósito em uma conta não existente
- [x] Não deve possível buscar extrato em uma conta não existente
- [x] Não deve possível fazer saque em uma conta não existente
- [x] Não deve possível fazer saque quando o saldo for insuficiente
- [] Não deve possível excluir uma conta não existente