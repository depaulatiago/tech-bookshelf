# Tech Bookshelf

🇺🇸 English | [🇧🇷 Português](README.pt-BR.md)

Notes and summaries of the programming books I'm reading.

## Books

| Book | Author | Status | Notes |
|---|---|---|---|
| Learning Functional Programming | Jack Widman | 📖 Reading | [Notes](books/learning-functional-programming/README.md) |

**Status:** 📖 Reading · ✅ Finished · ⏸️ Paused · 📚 Up next

## Structure

```
books/
  <book-slug>/
    README.md            # book overview (EN)
    README.pt-BR.md      # book overview (PT)
    chapters/
      01.md              # chapter notes (EN)
      01.pt-BR.md        # chapter notes (PT)
templates/               # templates for new books and chapters
```

Every file has an English version (`.md`) and a Portuguese version (`.pt-BR.md`).

## Adding a new book

1. Create `books/<book-slug>/` (lowercase, hyphenated, English title)
2. Copy `templates/book.md` → `README.md` and `templates/book.pt-BR.md` → `README.pt-BR.md`
3. For each chapter, copy `templates/chapter.md` and `templates/chapter.pt-BR.md` into `chapters/`
4. Add a row to the table above (and in `README.pt-BR.md`)
