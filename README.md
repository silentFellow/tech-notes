# 📚 silentFellow Notes

A sharable notes collection built with [mdBook](https://github.com/rust-lang/mdBook) and hosted on GitHub Pages.

🔗 Website: https://notes.silentFellow.dev

---

## ✨ Features

- Clean and fast static site
- Markdown-based notes
- Full-text search
- Mobile-friendly UI
- Easy Git-based workflow
- Powered by Rust’s `mdBook`

---

## 📂 Project Structure

```text
.
├── book/              # Generated static site
├── src/               # Notes content
├── book.toml          # mdBook configuration
├── README.md
└── .github/
    └── workflows/    # GitHub Actions
```

---

## 🚀 Getting Started

### 1. Install mdBook

Using Cargo:

```bash
cargo install mdbook
```

Or download prebuilt binaries from:

https://github.com/rust-lang/mdBook/releases

Verify installation:

```bash
mdbook --version
```

---

### 2. Create a New Book

```bash
mdbook init
```

---

### 3. Run Locally

```bash
mdbook serve
```

Open your browser:

```text
http://localhost:3000
```

---

### 4. Build Static Files

```bash
mdbook build
```

Generated files will be available in:

```text
book/
```

---

## 📝 Writing Notes

- Add markdown files inside `src/`
- Register pages in `src/SUMMARY.md`
- Rebuild or run the live server

Example page:

```md
# Linux Notes

Useful commands and workflows.
```

Example `SUMMARY.md`:

```md
# Summary

- [Introduction](./README.md)
- [Linux Notes](./linux.md)
- [Rust Notes](./rust.md)
```

---

## 🌐 Deployment

This project is deployed using GitHub Pages.

### Typical Flow

1. Push changes to GitHub
2. GitHub Actions builds the book
3. Static site gets deployed automatically

---

## 🤝 Contributing

Issues and pull requests are welcome.

If you spot mistakes, outdated information, or improvements, feel free to contribute.

---

## 📄 License

MIT License

---

## 🙌 Acknowledgements

Built using the amazing [mdBook](https://github.com/rust-lang/mdBook) project from the Rust ecosystem.
