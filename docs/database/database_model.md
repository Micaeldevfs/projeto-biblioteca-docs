# Modelo de Dados (MongoDB)

## Coleções

O modelo de dados usa três coleções principais: `members`, `books`, e `loans`.

### Coleção: `members`

Armazena os dados dos membros da biblioteca.

```json
{
  "_id": "ObjectId('...')",
  "name": "Nome do Membro",
  "email": "membro@email.com"
}
```

### Coleção: `books`

```json
{
  "_id": "ObjectId('...')",
  "title": "Título do Livro",
  "author": "Autor do Livro",
  "status": "available"
}
```

### Coleção: `loans`

```json
{
  "_id": "ObjectId('...')",
  "book_id": "ObjectId('...')",
  "member_id": "ObjectId('...')",
  "loan_date": "ISODate('...')",
  "return_date": null
}
```
