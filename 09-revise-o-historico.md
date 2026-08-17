# 09. Revise o histórico

> Navegue e inspecione a evolução dos arquivos do projeto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)

---

## Comandos desta seção (4)

### 1. `git log`

```bash
git log
```

**O que faz:**

Mostra o histórico de commits do repositório, incluindo informações como autor, data, mensagem e 
identificador do commit.

**Quando usar / observação:**

Use quando quiser ver o histórico do projeto e consultar commits anteriores.

---

### 2. `git log --follow [arquivo]`

```bash
git log --follow [arquivo]
```

**O que faz:**

Mostra o histórico de alterações de um arquivo específico, incluindo alterações feitas antes de ele ser 
renomeado.

**Quando usar / observação:**

Quando quiser ver toda a história de um arquivo, mesmo que ele tenha sido renomeado ou movido.

---

### 3. `git diff [primeiro-branch]...[segundo-branch]`

```bash
git diff [primeiro-branch]...[segundo-branch]
```

**O que faz:**

Mostra as diferenças entre dois branches, indicando o que foi alterado de um para o outro.

**Quando usar / observação:**

Quando quiser comparar dois branches antes de fazer um merge

---

### 4. `git show [commit]`

```bash
git show [commit]
```

**O que faz:**

Mostra os detalhes de um commit específico, incluindo a mensagem, autor, data e as alterações feitas

**Quando usar / observação:**

Quando quiser ver exatamente o que foi alterado em um determinado commit.

---

## Checklist deste arquivo

- [x] 1. `git log`
- [x] 2. `git log --follow [arquivo]`
- [x] 3. `git diff [primeiro-branch]...[segundo-branch]`
- [x] 4. `git show [commit]`

---

[⬅ Salve fragmentos](08-salve-fragmentos.md) · [Índice](../README.md) · [Desfaça commits ➡](10-desfaca-commits.md)
