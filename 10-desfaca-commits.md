# 10. Desfaça commits

> Apague enganos e crie um histórico substituto.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)

---

## Comandos desta seção (2)

### 1. `git reset [commit]`

```bash
git reset [commit]
```

**O que faz:**

Move o HEAD para um commit anterior, desfazendo os commits posteriores no histórico atual.

**Quando usar / observação:**

Quando quiser voltar para um commit anterior e desfazer commits que ainda não deveriam estar no 
histórico.

---

### 2. `git reset --hard [commit]`

```bash
git reset --hard [commit]
```

**O que faz:**

Volta o projeto para um commit específico, apagando os commits posteriores e também descartando as 
alterações nos arquivos.

**Quando usar / observação:**

Quando quiser voltar completamente o projeto para um estado anterior, sem precisar manter as alterações 
feitas depois daquele commit.

---

## Checklist deste arquivo

- [x] 1. `git reset [commit]`
- [x] 2. `git reset --hard [commit]`

---

[⬅ Revise o histórico](09-revise-o-historico.md) · [Índice](../README.md) · [Sincronize mudanças ➡](11-sincronize-mudancas.md)
