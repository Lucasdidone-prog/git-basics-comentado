# 08. Salve fragmentos

> Arquive e restaure mudanças incompletas.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)

---

## Comandos desta seção (4)

### 1. `git stash`

```bash
git stash
```

**O que faz:**

Guarda temporariamente suas alterações que ainda não foram commitadas e deixa o projeto no estado do 
último commit.

**Quando usar / observação:**

Quando você está trabalhando em algo, mas precisa mudar de branch ou fazer outra tarefa sem querer 
fazer um commit ainda.

---

### 2. `git stash pop`

```bash
git stash pop
```

**O que faz:**

Recupera as alterações que foram guardadas anteriormente pelo git stash e remove essas alterações da 
lista do stash.

**Quando usar / observação:**

Quando você terminou a outra tarefa e quer continuar o trabalho que tinha deixado temporariamente 
guardado.

---

### 3. `git stash list`

```bash
git stash list
```

**O que faz:**

Mostra todas as alterações que foram guardadas temporariamente com git stash.

**Quando usar / observação:**

Use quando quiser ver o que você tem salvo no stash antes de recuperar alguma alteração.

---

### 4. `git stash drop`

```bash
git stash drop
```

**O que faz:**

Apaga uma alteração específica que está guardada no stash.

**Quando usar / observação:**

Quando não precisa mais das alterações guardadas no stash e quer excluí-las.

---

## Checklist deste arquivo

- [x] 1. `git stash`
- [x] 2. `git stash pop`
- [x] 3. `git stash list`
- [x] 4. `git stash drop`

---

[⬅ Suprima o monitoramento](07-suprima-o-monitoramento.md) · [Índice](../README.md) · [Revise o histórico ➡](09-revise-o-historico.md)
