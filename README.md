# TO DO - List

## Requisitos

- [x] Deve ser possível criar um usuário
- [x] Deve ser possível listar os dados o de um usuário
- [x] Deve ser possível listar os To Do de todos os usuários
- [x] Deve ser possível criar um novo To Do
- [x] Deve ser possível alterar o título e o prazo de um To Do
- [x] Deve ser possível marcar um To Do como feito
- [x] Deve ser possível excluir um To Do
- [x] Deve possuir checksExistsUserAccount
- [x] Deve ser possível localizar username pelo header e passá-lo para request.user
- [x] Deve possuir checksCreateTodosUserAvailability
- [x] Deve ser possível criar um novo To Do no plano grátis se tiver menos de 10 To Do
- [x] Deve ser possível criar infinitos novos To Do no plano Pro
- [x] Deve possuir checksTodoExists
- [x] Deve ser possível alterar usuário e To Do quando ambos existirem
- [x] Deve possuir findUserById
- [x] Deve ser possível localizar usuário pelo id route param e passá-lo para request.user

## Regras de negócio

- [x] Não deve ser possível cadastrar um usuário com username já existente
- [x] Não deve ser possível criar um To Do para usuário não existente
- [x] Não deve ser possível atualizar um To Do não existente
- [x] Não deve ser possível marcar um To Do não existente como feito
- [x] Não deve ser possível excluir um To Do não existente
- [x] Não deve ser possível localizar username não existente
- [x] Não deve ser possível criar um novo To Do no plano grátis se tiver 10 To Do
- [x] Não deve ser possível alterar usuário e To Do quando o usuário não existir
- [x] Não deve ser possível alterar usuário e To Do quando o id do To Do não for uuid
- [x] Não deve ser possível alterar usuário e To Do quando o To Do não existir
- [x] Não deve ser possível localizar usuário não existente
