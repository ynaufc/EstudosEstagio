# Estudo de Testes de API com Robot Framework

## 📝 Descrição
Estudar como utilizar o Robot Framework para automatizar testes de API, garantindo a qualidade das comunicações entre serviços.

---

## 📂 Conteúdo da Documentação

### 1. O que é teste de API
Testes de API verificam se as interfaces de programação de aplicações funcionam conforme o esperado, validando respostas, códigos de status (como 200 OK ou 404 Not Found) e o tempo de resposta.

### 2. Uso do Robot Framework para API
O Robot Framework é uma ferramenta de automação baseada em palavras-chave (keywords), o que torna os testes legíveis tanto para desenvolvedores quanto para analistas de negócios.

### 3. RequestsLibrary (conceito básico)
É a biblioteca padrão do Robot Framework para realizar requisições HTTP. Ela permite criar sessões e enviar comandos como GET, POST, PUT e DELETE.

### 4. Exemplo simples de requisição (GET)
```robotframework
*** Settings ***
Library    RequestsLibrary

*** Test Cases ***
Validar Consulta de Usuário
    Create Session    api_github    [https://api.github.com](https://api.github.com)
    ${response}=      GET On Session    api_github    /users/ynaufc
    Status Should Be  200    ${response}
