# 06. Refatore nomes de arquivos

> Mude e remova os arquivos versionados.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)

---

## Comandos desta seção (3)

### 1. `git rm [arquivo]`

```bash
git rm [arquivo]
```

**O que faz:**

Remove um arquivo do projeto e também informar ao Git que ele foi removido.

**Quando usar / observação:**

Usar quando quer apagar um arquivo do projeto e quer que o Git registre essa exclusão.

---

### 2. `git rm --cached [arquivo]`

```bash
git rm --cached [arquivo]
```

**O que faz:**

tira um arquivo do controle do Git, mas sem apagar o arquivo do seu computador.

**Quando usar / observação:**

Quando quiser remover um arquivo do Git, mas mantê-lo no seu computador.

---

### 3. `git mv [arquivo-original] [arquivo-renomeado]`

```bash
git mv [arquivo-original] [arquivo-renomeado]
```

**O que faz:**

Renomeia ou move um arquivo e já informa ao Git sobre essa alteração.

**Quando usar / observação:**

Quando quiser renomear ou mover um arquivo dentro do projeto e manter essa alteração registrada pelo Git.

---

## Checklist deste arquivo

- [x] 1. `git rm [arquivo]`
- [x] 2. `git rm --cached [arquivo]`
- [x] 3. `git mv [arquivo-original] [arquivo-renomeado]`

---

[⬅ Mudanças em grupo](05-mudancas-em-grupo.md) · [Índice](../README.md) · [Suprima o monitoramento ➡](07-suprima-o-monitoramento.md)
