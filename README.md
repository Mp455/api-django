
# Primeira API

Projeto de criação de API por utilizando o framework Django

## Documentação da API

#### Retorna todos os itens

```http
  GET http://marcospaulosousa48.pythonanywhere.com/livros/
```

| Parâmetro   | Tipo       | Descrição                           |
| :---------- | :--------- | :---------------------------------- |
| `api_key` | `string` | **Obrigatório**. A chave da sua API |

#### Retorna um item

```http
  GET /api/items/${id}
```

| Parâmetro   | Tipo       | Descrição                                   |
| :---------- | :--------- | :------------------------------------------ |
| `id`      | `string` | **Obrigatório**. O ID do item que você quer |



## Deploy

Foi utilizado o PythonAniwhere para deploy

```bash
  http://marcospaulosousa48.pythonanywhere.com/livros/
```

