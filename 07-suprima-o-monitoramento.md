# 07. Suprima o monitoramento

> Ignore arquivos e diretórios temporários.

> Seção do [GitHub Git Cheat Sheet (pt-BR)](https://training.github.com/downloads/pt_BR/github-git-cheat-sheet/).


[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)

---

## Itens desta seção (2)

### 1. Arquivo `.gitignore`

```gitignore
*.log
build/
temp-*
```

**O que este arquivo faz:**

O gitignore é um arquivo usado para dizer ao Git quais arquivos ou pastas ele não deve acompanhar.
.log ignora todos os arquivos que terminam em .log
build/ ignora a pasta build inteira
temp-* ignora arquivos ou pastas que começam com temp-

**Quando usar / observação:**

quando quiser impedir que arquivos desnecessários, temporários ou gerados automaticamente sejam 
enviados para o Git.

---

### 2. `git ls-files --others --ignored --exclude-standard`

```bash
git ls-files --others --ignored --exclude-standard
```

**O que faz:**

mostra na tela os arquivos que o Git está ignorando, de acordo com as regras do .gitignore.

**Quando usar / observação:**

Quando quiser ver quais arquivos estão sendo ignorados pelo .gitignore, principalmente para verificar 
se uma regra está funcionando corretamente.

---

## Checklist deste arquivo

- [x] 1. Arquivo `.gitignore`
- [x] 2. `git ls-files --others --ignored --exclude-standard`

---

[⬅ Refatore nomes de arquivos](06-refatore-nomes-de-arquivos.md) · [Índice](../README.md) · [Salve fragmentos ➡](08-salve-fragmentos.md)
