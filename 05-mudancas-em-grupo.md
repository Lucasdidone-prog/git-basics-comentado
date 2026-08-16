# 05. Mudanças em grupo

> Nomeie uma série de commits e combine os esforços completos.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)

---

## Comandos desta seção (5)

### 1. `git branch`

```bash
git branch
```

**O que faz:**

lista todas as branches locais que existem no seu computador e destaca qual delas você está usando no 
momento.

**Quando usar / observação:**

Usar para listar as branches do seu computador e conferir em qual delas você está trabalhando no 
momento.

---

### 2. `git branch [nome-do-branch]`

```bash
git branch [nome-do-branch]
```

**O que faz:**

cria uma nova branch local no seu projeto a partir do ponto exato onde você está no momento, sem mudar 
você para dentro dela.

**Quando usar / observação:**

Usar quando você quiser criar um novo ramo de trabalho do zero para desenvolver um ajuste ou exercício 
de forma isolada

---

### 3. `git switch -c [nome-do-branch]`

```bash
git switch -c [nome-do-branch]
```

**O que faz:**

cria uma nova branch e altera o seu terminal para dentro dela imediatamente em um único passo.

**Quando usar / observação:**

Usar quando você quiser criar uma branch nova e entrar nela imediatamente para começar a trabalhar

---

### 4. `git merge [nome-do-branch]`

```bash
git merge [nome-do-branch]
```

**O que faz:**

junta o histórico e as alterações da branch que você escolheu para dentro da branch onde você está no 
terminal no momento.

**Quando usar / observação:**

Usar quando você terminar um trabalho quiser juntar essas alterações dentro da sua branch atual.

---

### 5. `git branch -d [nome-do-branch]`

```bash
git branch -d [nome-do-branch]
```

**O que faz:**

exclui uma branch local do seu computador.

**Quando usar / observação:**

Usar para deletar uma branch local que você já terminou e as alterações já foram salvas ou mescladas.

---

## Checklist deste arquivo

- [x] 1. `git branch`
- [x] 2. `git branch [nome-do-branch]`
- [x] 3. `git switch -c [nome-do-branch]`
- [x] 4. `git merge [nome-do-branch]`
- [x] 5. `git branch -d [nome-do-branch]`

---

[⬅ Faça mudanças](04-faca-mudancas.md) · [Índice](../README.md) · [Refatore nomes de arquivos ➡](06-refatore-nomes-de-arquivos.md)
