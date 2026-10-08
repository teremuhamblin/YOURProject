###### ~/README.md >> markdown

# YOURProject
- *Projet simple et court GitHub* avec un **seul workflow GitHub Actions**, compatible avec n’importe quel langage

>> **Node.js, Python, Java, Ruby, PHP, Go, Rust, .NET, etc**

---

### 🎯 Projet GitHub
- Multi‑Langages

### 📁 Structure minimale
```text
YOURProject/
 ├── src/
 │    └── main.txt        # Ton code, peu importe le langage
 └── .github/
      └── workflows/
           └── ci.yml     # Workflow GitHub Actions universel
```

---

### 📌 Explication
1. Tu mets n’importe quel langage dans src/.
2. Le workflow détecte automatiquement le langage.
3.    - Il exécute la commande de build/test correspondante.
      - Si le langage n’est pas reconnu → il passe simplement.

---
