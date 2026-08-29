# API-Connect

API RESTful desenvolvida em Node.js e Express para o gerenciamento de usuários da startup Connect. A aplicação permite realizar operações completas de CRUD (Create, Read, Update, Delete) em memória, contando com validação de dados de entrada, tratamento de erros HTTP e padronização de respostas JSON.

---

## Tecnologias Utilizadas

- **Node.js**: Ambiente de execução JavaScript no lado do servidor.
- **Express**: Framework web minimalista para gerenciamento de rotas e requisições HTTP.
- **Nodemon**: Ferramenta de desenvolvimento para reinício automático do servidor durante alterações.

---

## Como Executar o Projeto Localmente

### **Pré-requisitos**
Possuir o **Node.js** e o **npm** instalados na sua máquina.

### **Passos para Instalação e Execução**

1. **Clonar o repositório:**
   ```bash
   git clone [https://github.com/CarolineCarone/API-Connect.git](https://github.com/CarolineCarone/API-Connect.git)

cd API-Connect

npm install

npm run dev

O servidor estará rodando no endereço http://localhost:3000.

Tratamento de Erros e Respostas
400 Bad Request: Retornado quando a validação no cadastro identifica ausência ou invalidade dos campos obrigatórios (nome e email).

404 Not Found: Retornado quando o parâmetro :id informado em buscas, atualizações ou remoções não é localizado na base de dados.
