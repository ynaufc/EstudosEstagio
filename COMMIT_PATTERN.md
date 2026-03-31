# Commit Pattern

## Estrutura de um Commit

Um commit deve seguir o padrão:

tipo(escopo): mensagem curta

descrição mais detalhada (opcional)

rodapé (opcional)

---

## Tipos de Commit

| Tipo     | Descrição |
|----------|----------|
| feat     | Nova funcionalidade |
| fix      | Correção de bug |
| refactor | Refatoração sem alteração de comportamento |
| perf     | Melhoria de performance |
| docs     | Alterações na documentação |
| test     | Adição ou ajuste de testes |
| chore    | Tarefas gerais (dependências, build, etc.) |

---

## Exemplos

feat(login): adiciona autenticação com JWT  
fix(api): corrige erro 500 ao salvar usuário  
refactor(auth): simplifica validação de token  

---

## Boas Práticas

- Use no máximo 50 caracteres na mensagem principal
- Escreva no imperativo (ex: "corrige", "adiciona")
- Seja claro e direto
- Utilize escopo quando fizer sentido

---

## Corpo do Commit

Utilize quando precisar explicar melhor a mudança:

fix(auth): corrige expiração do token

O token expirava imediatamente devido a erro no cálculo de tempo.
Agora utiliza Date.now() corretamente.

---

## Escopo

Ajuda a identificar onde ocorreu a mudança:

feat(api)
fix(frontend)
refactor(database)

---

## Versionamento Semântico

| Tipo | Impacto |
|------|--------|
| feat | MINOR |
| fix  | PATCH |
| BREAKING CHANGE | MAJOR |

Exemplo:

feat(api): adiciona suporte a múltiplos usuários

BREAKING CHANGE: altera estrutura de retorno da API

---

## Dica Final

Sempre pense: alguém entenderia esse commit daqui a meses?
Se não, melhore a descrição.
