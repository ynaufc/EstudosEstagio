# EstudosEstagio

#  Estudo de Git

Repositório dedicado ao aprendizado e documentação dos conceitos fundamentais de controle de versão. Este material serve como guia prático para a equipe nivelar conhecimentos sobre o ecossistema Git.

---

## 📝 Descrição do Estudo
O objetivo principal é dominar o uso do Git para gerenciar o histórico de alterações de um projeto, permitindo um desenvolvimento colaborativo seguro e organizado.

## 📂 Conteúdo da Documentação

### 1. O que é Versionamento?
O controle de versão é um sistema que registra as mudanças em um arquivo ou conjunto de arquivos ao longo do tempo, para que você possa recuperar versões específicas mais tarde.
- **Por que usar?** Facilita a reversão de erros, o trabalho em equipe (branches) e mantém um histórico claro de quem fez o quê.

### 2. Principais Comandos
| Comando | Ação |
| :--- | :--- |
| `git init` | Inicializa o Git na pasta do projeto. |
| `git add <arquivo>` | Adiciona arquivos ao índice (staging). |
| `git commit -m "msg"` | Salva as alterações com uma descrição. |
| `git branch <nome>` | Cria uma nova ramificação de trabalho. |
| `git checkout <nome>` | Alterna entre diferentes ramificações. |
| `git merge <nome>` | Une as alterações de uma branch à atual. |
| `git push` | Envia as alterações para o repositório remoto. |
| `git pull` | Atualiza o repositório local com as mudanças remotas. |

### 3. Fluxo de Trabalho (Workflow)
O fluxo básico adotado neste estudo segue os passos:
1. `Modificar` -> Alteração de arquivos no diretório.
2. `Staging` -> Seleção de arquivos com `git add`.
3. `Commit` -> Snapshot das alterações com `git commit`.
4. `Push` -> Sincronização com o servidor.

---

## ✅ Resultado Esperado
Ao final deste estudo, devo, junto a minha equipe estar apta a:
- [x] Criar e gerenciar branches.
- [x] Resolver conflitos básicos de código.
- [x] Manter um histórico de commits semântico e organizado.

---
---

## 🎓 Certificação Alura
### [Git e GitHub: repositório, commit e versões](https://cursos.alura.com.br/formalCertificate/702ae99e-5047-44a2-9f03-cc4aec8e5f1a)

Neste curso, desenvolvi habilidades fundamentais para o controle de versão de projetos de software, incluindo:

* **Configuração inicial:** Instalação e configuração de identidade no Git.
* **Ciclo de vida de arquivos:** Entendimento dos estados *Untracked*, *Staged*, *Modified* e *Committed*.
* **Gestão de Repositórios:** Criação de repositórios locais e sincronização com repositórios remotos no GitHub.
* **Trabalho com Histórico:** Visualização de logs, comparação de versões e restauração de arquivos.
* **Colaboração:** Utilização de comandos como `git push`, `git pull` e `git fetch` para trabalhar em equipe.
* **Ignorando Arquivos:** Criação e configuração do arquivo `.gitignore` para manter o repositório limpo.

<p align="center">
  <img src="https://inscricoes.alura.com.br/course/git-github-repositorio-commit-versoes/certificate/image" width="500">
</p>
**Desenvolvido por:** [Any Mélani](https://github.com/ynaufc)  
*UFC - Campus Quixadá*
