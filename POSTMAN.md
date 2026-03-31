# Postman

## O que é

O Postman é uma ferramenta para testar, automatizar e documentar APIs.

---

## Estrutura

### Collection
Conjunto de requisições organizadas.

### Request
Uma chamada HTTP (GET, POST, PUT, DELETE).

### Environment
Variáveis reutilizáveis:

{{base_url}}  
{{token}}  
{{user_id}}  

---

## Configuração de Ambiente

Exemplo:

base_url = https://api.meusistema.com  
token = abc123  

---

## Criando Requisições

URL:
{{base_url}}/users  

Headers:
Authorization: Bearer {{token}}  

---

## Testes Automatizados

Na aba "Tests":

```javascript
pm.test("Status code é 200", function () {
    pm.response.to.have.status(200);
});

pm.test("Resposta contém usuário", function () {
    const jsonData = pm.response.json();
    pm.expect(jsonData.name).to.exist;
});
