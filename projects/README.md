# Proyek

Gunakan satu folder atau repo terpisah untuk tiap proyek utama.

Struktur minimum:

```text
project-name/
|-- README.md
|-- pyproject.toml
|-- src/
|-- tests/
|-- notebooks/
|-- reports/figures/
|-- .github/workflows/tests.yml
`-- LICENSE
```

Notebook dipakai untuk eksplorasi. Kode yang dipakai ulang dipindah ke `src/` dan diuji di `tests/`.

