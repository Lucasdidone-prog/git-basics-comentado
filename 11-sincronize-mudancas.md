# 11. Sincronize mudanças

> Registre um repositório remoto e troque o histórico de versão.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)

---

## Comandos desta seção (4)

### 1. `git fetch [nome-remoto]`

```bash
git fetch [nome-remoto]
```

**O que faz:**

Busca as atualizações do repositório remoto e traz essas informações para o seu Git local, sem alterar 
seus arquivos ou seu branch atual.

**Quando usar / observação:**

quando quiser verificar se existem atualizações no repositório remoto antes de decidir se quer 
incorporá-las ao seu projeto.

---

### 2. `git merge [nome-remoto]/[branch]`

```bash
git merge [nome-remoto]/[branch]
```

**O que faz:**

Une as alterações de um branch remoto ao branch em que você está atualmente.

**Quando usar / observação:**

Quando quiser incorporar as alterações de um branch remoto ao seu branch atual.

---

### 3. `git push [alias] [branch]`

```bash
git push [alias] [branch]
```

**O que faz:**

Envia os commits do seu branch local para o repositório remoto.

**Quando usar / observação:**

Use quando quiser enviar suas alterações/commits locais para o GitHub ou outro repositório remoto.

---

### 4. `git pull`

```bash
git pull
```

**O que faz:**

Baixa as alterações do repositório remoto e já integra essas alterações ao seu branch atual.

**Quando usar / observação:**

Quando quiser atualizar seu projeto local com as alterações que estão no GitHub/remoto.

---

## Checklist deste arquivo

- [x] 1. `git fetch [nome-remoto]`
- [x] 2. `git merge [nome-remoto]/[branch]`
- [x] 3. `git push [alias] [branch]`
- [x] 4. `git pull`

---

[⬅ Desfaça commits](10-desfaca-commits.md) · [Índice](../README.md)
