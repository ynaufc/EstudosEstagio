# Estudo – Postman

## 📝 Descrição
Aprender conceitos básicos de testes de API e o uso da ferramenta Postman para exploração e validação de endpoints.

---

## 📂 Conteúdo da Documentação

### 1. O que é API
API (Application Programming Interface) é um conjunto de definições e protocolos que permite que diferentes softwares se comuniquem entre si. Ela atua como um intermediário que permite que um aplicativo solicite dados ou ações de outro.

### 2. Métodos HTTP (GET, POST, PUT, DELETE)
Os métodos HTTP definem a ação que se deseja realizar no servidor:
* **GET**: Utilizado para buscar informações de um recurso específico.
* **POST**: Utilizado para enviar dados e criar um novo recurso.
* **PUT**: Utilizado para atualizar um recurso já existente de forma integral.
* **DELETE**: Utilizado para remover um recurso específico.

### 3. Como usar o Postman
O Postman é uma ferramenta que facilita o teste e desenvolvimento de APIs através de uma interface amigável:
* **Collections**: Servem para organizar e agrupar requisições relacionadas.
* **Environments**: Permitem alternar rapidamente entre diferentes conjuntos de variáveis (ex: Produção vs. Desenvolvimento).
* **Params e Body**: Local onde são configurados os parâmetros de URL e os dados enviados em requisições POST/PUT.

### 4. Exemplo de requisição com explicação
Ao realizar uma chamada **GET** para `https://api.github.com/users/github`:
1. **Request**: O cliente (Postman) envia o método GET para o endpoint informado.
2. **Status Code**: O servidor responde com um código (ex: **200 OK** para sucesso).
3. **Response Body**: O Postman exibe o JSON retornado com os dados do perfil solicitado.

---

## ✅ Resultado Esperado
* Equipe entendendo como testar APIs.
