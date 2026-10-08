# Tech Bookshelf

[🇺🇸 English](README.md) | 🇧🇷 Português

Anotações e resumos dos livros de programação que estou lendo.

## Livros

| Livro | Autor | Status | Notas |
|---|---|---|---|
| Aprenda Programação Funcional | Jack Widman | 📖 Lendo | [Notas](books/learning-functional-programming/README.pt-BR.md) |

**Status:** 📖 Lendo · ✅ Concluído · ⏸️ Pausado · 📚 Próximo

## Estrutura

```
books/
  <slug-do-livro>/
    README.md            # visão geral do livro (EN)
    README.pt-BR.md      # visão geral do livro (PT)
    chapters/
      01.md              # notas do capítulo (EN)
      01.pt-BR.md        # notas do capítulo (PT)
templates/               # modelos para novos livros e capítulos
```

Todo arquivo tem uma versão em inglês (`.md`) e uma em português (`.pt-BR.md`).

## Adicionando um livro

1. Crie `books/<slug-do-livro>/` (minúsculo, com hífen, título em inglês)
2. Copie `templates/book.md` → `README.md` e `templates/book.pt-BR.md` → `README.pt-BR.md`
3. Para cada capítulo, copie `templates/chapter.md` e `templates/chapter.pt-BR.md` para `chapters/`
4. Adicione uma linha na tabela acima (e no `README.md`)
