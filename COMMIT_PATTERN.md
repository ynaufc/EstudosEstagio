# Estudo sobre Padrão de Commits

## 📝 Descrição
Estudar boas práticas de escrita de commits para manter o histórico do projeto organizado e legível.

---

## 📂 Conteúdo da Documentação

### 1. O que são commits?
Um commit é um registro das alterações feitas no código em um determinado momento. Ele funciona como um "ponto de salvamento" (snapshot) que permite rastrear a evolução do projeto e reverter mudanças se necessário.

### 2. Boas práticas
* **Seja atômico:** Cada commit deve conter apenas uma alteração lógica (ex: não misture correção de bug com nova funcionalidade).
* **Use o imperativo:** Escreva mensagens como comandos (ex: "Adiciona", "Corrige", "Remove").
* **Título conciso:** O resumo deve ser breve e direto.

### 3. Padrão escolhido: Conventional Commits
Utilizamos prefixos para identificar o tipo de alteração:
* `feat:` Uma nova funcionalidade.
* `fix:` Correção de um erro.
* `docs:` Alterações apenas na documentação.
* `style:` Formatação e estilo de código (espaços, ponto e vírgula, etc).
* `refactor:` Mudança no código que não corrige bug nem adiciona funcionalidade.

### 4. Exemplos
* `feat: adiciona sistema de login`
* `fix: corrige erro de autenticação no banco de dados`
* `docs: atualiza guia de instalação no README`

---

## ✅ Resultado Esperado
* Equipe entendendo como organizar commits.
