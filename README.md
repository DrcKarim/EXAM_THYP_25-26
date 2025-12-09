# Examen THYP du 9 décembre 2025
Karim BOUCHAANE

## 🚀 LANCEMENT RAPIDE

### 1. Démarrer le serveur
```bash
cd /Users/karim/Desktop/EXAM_THYP_25-26
python3 -m http.server 8000
```

### 2. Ouvrir les pages
- **Cours:** http://localhost:8000/cours.html
- **Évaluations:** http://localhost:8000/evals.html

---

## ✅ Exercice 1 - Liste des cours (`cours.html`)

**Fonctions:**
- `getCours()` - Récupère la liste des cours
- `showCours()` - Affiche: ID, Titre, Étudiants inscrits

---

## ✅ Exercice 2 - Évaluations (`evals.html`)

**Fonctions:**
- `setEval()` - Enregistre une évaluation
- `showEval()` - Affiche: ID évaluation, Note, Étudiant, Cours

**Utilisation:**
1. Entrer ID Étudiant (ex: 122)
2. Entrer ID Cours (ex: 112)
3. Entrer Note (ex: 19)
4. Cliquer "Enregistrer"

---

## ⚠️ IMPORTANT
- **Toujours lancer le serveur** (sinon erreur CORS)
- IDs: Cours=110, Étudiant=111, Évaluation=113

