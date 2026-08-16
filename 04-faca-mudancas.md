# 04. Faça mudanças

> Revise edições e crie uma transação de commit.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)

---

## Comandos desta seção (6)

### 1. `git status`

```bash
git status
```

**O que faz:**

Mostra a situação atual do repositório, quais arquivos foram modificados e quais ainda não estão sendo 
monitorados pelo Git.

**Quando usar / observação:**

Usar como uma boa prática para verificar a situação dos seus arquivos e saber quais alterações estão 
prontas para serem salvas.

---

### 2. `git diff`

```bash
git diff
```

**O que faz:**

Mostra as alterações linha por linha exibindo o que foi adicionado e o que foi apagado desde o último 
salvamento.

**Quando usar / observação:**

Para revisar linha por linha o que foi alterado no seu código antes de preparar o salvamento.

---

### 3. `git add [arquivo]`

```bash
git add [arquivo]
```

**O que faz:**

adiciona um arquivo específico modificado ou novo à área de preparação, preparando para ser incluído no 
seu próximo salvamento.

**Quando usar / observação:**

Usar quando terminar de mexer em um arquivo e quiser prepará-lo para o salvamento (commit).

---

### 4. `git diff --staged`

```bash
git diff --staged
```

**O que faz:**

mostra as alterações linha por linha apenas dos arquivos que já foram adicionados (git add) comparando 
com o último commit realizado.

**Quando usar / observação:**

Usar quando você quiser revisar linha por linha o que já foi preparado (git add) antes de confirmar o 
salvamento final.

---

### 5. `git reset [arquivo]`

```bash
git reset [arquivo]
```

**O que faz:**

remove um arquivo específico da área de preparação, cancelando o efeito do git add sem apagar as 
alterações que você fez no código.

**Quando usar / observação:**

Usar quando você adicionar um arquivo por engano com git add e quiser tirá-lo do salvamento sem 
perder o código escrito.

---

### 6. `git commit -m "[mensagem descritiva]"`

```bash
git commit -m "[mensagem descritiva]"
```

**O que faz:**

Grava e salva as alterações que estavam na fila (git add) no histórico local do seu repositório, 
anexando a mensagem que explica o que foi feito.

**Quando usar / observação:**

Usar quando quiser gravar definitivamente as alterações preparadas, criando um ponto de salvamento com 
uma mensagem explicativa no histórico.

---

## Checklist deste arquivo

- [x] 1. `git status`
- [x] 2. `git diff`
- [x] 3. `git add [arquivo]`
- [x] 4. `git diff --staged`
- [x] 5. `git reset [arquivo]`
- [x] 6. `git commit -m "[mensagem descritiva]"`

---

[⬅ Crie repositórios](03-crie-repositorios.md) · [Índice](../README.md) · [Mudanças em grupo ➡](05-mudancas-em-grupo.md)
