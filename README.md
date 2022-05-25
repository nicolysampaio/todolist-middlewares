# TO DO - List

## Requisitos

- [] Deve ser possível criar um usuário
- [] Deve ser possível listar os dados o de um usuário
- [] Deve ser possível listar os To Do de todos os usuários
- [] Deve ser possível criar um novo To Do
- [] Deve ser possível alterar o título e o prazo de um To Do
- [] Deve ser possível marcar um To Do como feito
- [] Deve ser possível excluir um To Do
- [] Deve possuir checksExistsUserAccount
- [] Deve ser possível localizar username pelo header e passá-lo para request.user
- [] Deve possuir checksCreateTodosUserAvailability
- [] Deve ser possível criar um novo To Do no plano grátis se tiver menos de 10 To Do
- [] Deve ser possível criar infinitos novos To Do no plano Pro
- [] Deve possuir checksTodoExists
- [] Deve ser possível alterar usuário e To Do quando ambos existirem
- [] Deve possuir findUserById
- [] Deve ser possível localizar usuário pelo id route param e passá-lo para request.user

## Regras de negócio

- [] Não deve ser possível cadastrar um usuário com username já existente
- [] Não deve ser possível criar um To Do para usuário não existente
- [] Não deve ser possível atualizar um To Do não existente
- [] Não deve ser possível marcar um To Do não existente como feito
- [] Não deve ser possível excluir um To Do não existente
- [] Não deve ser possível localizar username não existente
- [] Não deve ser possível criar um novo To Do no plano grátis se tiver 10 To Do
- [] Não deve ser possível alterar usuário e To Do quando o usuário não existir
- [] Não deve ser possível alterar usuário e To Do quando o id do To Do não for uuid
- [] Não deve ser possível alterar usuário e To Do quando o To Do não existir
- [] Não deve ser possível localizar usuário não existente
