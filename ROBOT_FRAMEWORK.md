# Estudo de Testes de API com Robot Framework

## Descrição
Estudo sobre o uso do Robot Framework para automatizar testes de API, garantindo a qualidade da comunicação entre serviços.

---

## Conteúdo

### 1. O que é teste de API

Testes de API verificam se uma interface de comunicação entre sistemas funciona corretamente.

Eles validam:
- Código de status (ex: 200, 404)
- Estrutura da resposta
- Dados retornados
- Tempo de resposta

---

### 2. Robot Framework para APIs

O Robot Framework é uma ferramenta de automação baseada em palavras-chave (keywords).

Principais características:
- Sintaxe simples e legível
- Fácil manutenção
- Reutilização de testes

---

### 3. RequestsLibrary

Biblioteca utilizada para realizar requisições HTTP.

Permite:
- Criar sessões
- Enviar requisições GET, POST, PUT, DELETE
- Validar respostas

---

### 4. Exemplo de requisição (GET)

```robot
*** Settings ***
Library    RequestsLibrary

*** Test Cases ***
Validar Consulta de Usuário
    Create Session    api_github    https://api.github.com
    ${response}=      GET On Session    api_github    /users/ynaufc
    Status Should Be  200    ${response}
