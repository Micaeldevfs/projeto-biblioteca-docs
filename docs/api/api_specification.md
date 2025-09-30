# Especificação da API

## Livros
- **GET /books:** Lista todos os livros.
- **POST /books:** Cadastra novo livro. Body: `{ "title": "...", "author": "..." }`

## Membros
- **GET /members:** Lista todos os membros.
- **POST /members:** Cadastra novo membro. Body: `{ "name": "...", "email": "..." }`

## Empréstimos
- **POST /loans:** Cria novo empréstimo. Body: `{ "book_id": 1, "member_id": 1 }`
- **PUT /loans/:id/return:** Registra devolução.
