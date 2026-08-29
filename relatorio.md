# Evidências de Teste da API Connect

## 1. Criação com Sucesso
* **Método HTTP:** `POST`
* **URL:** `http://localhost:3000/users`
* **Payload Enviado (JSON):**
```json
{
  "nome": "Mariana Santos",
  "email": "mariana@email.com"
}

{
  "data": {
    "id": 3,
    "nome": "Mariana Santos",
    "email": "mariana@email.com"
  }
}

{
  "nome": "Mariana Santos"
}

{
  "error": "O campo 'email' é obrigatório e deve ser um texto válido."
}

[
  {
    "id": 1,
    "nome": "Caroline Carone",
    "email": "caroline.carone@email.com"
  },
  {
    "id": 2,
    "nome": "João Pedro",
    "email": "joao.pedro@email.com"
  }
]

{
  "mensagem": "Usuário não encontrado."
}
