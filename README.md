# Langage de Programmation BATEN

BATEN est un langage de programmation innovant conçu pour gérer quatre types d'états dans différents contextes. Son objectif est de permettre une programmation intuitive et modulaire, tout en explorant des concepts tels que les cascades, les états secondaires et la synchronisation stricte.

---

## 🚀 Features | Fonctionnalités

- **Hidden and Visible States | États Cachés et Visibles**:
  Simultaneous management of visible and hidden instructions via suffixes.
  Gestion simultanée d'instructions visibles et cachées via des suffixes.
  
- **Dynamic Contexts | Contextes Dynamiques**:
  Context-specific prefixes (e.g., DB_, NET_, FS_) for flexibility.
  Préfixes spécifiques aux contextes (DB_, NET_, FS_, etc.) pour une flexibilité accrue.

- **Innovative Instructions | Instructions Innovantes**:
  - `DB_combined_read`: Unified reading of visible and hidden data.
  - `DB_combined_read` : Lecture unifiée des données visibles et cachées.
  - Enhanced logging with `DB_log`.
  - Journaux améliorés avec `DB_log`.

---

## 📂 Project Structure | Structure du Projet

- `src/`: Source code for the compiler and interpreter.
- `src/` : Code source du compilateur et de l’interpréteur.
- `examples/`: `.btn` files to test the language’s features.
- `examples/` : Fichiers `.btn` pour tester les fonctionnalités du langage.
- `docs/`: Comprehensive documentation.
- `docs/` : Documentation détaillée.

---

## 💡 Usage | Utilisation

### 1. Install Dependencies | Installer les Dépendances
Clone the project and install necessary dependencies.
Clonez le projet et installez les dépendances nécessaires.
```bash
git clone https://github.com/your_username/BATEN.git
cd BATEN
pip install -r requirements.txt
