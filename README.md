
# 🌐 Mini Blog Statique — Articles JSON, Filtrage & Routing

Bienvenue dans mon projet de développement web : **un mini-blog statique entièrement conçu en HTML, CSS et JavaScript**, capable d’afficher des articles depuis un fichier JSON, de filtrer par catégorie, d’effectuer une recherche en temps réel, et de naviguer entre les articles grâce à un mini-système de routage.

Ce projet a été réalisé dans le cadre du module **Développement Web** et répond à toutes les consignes pédagogiques : utilisation exclusive des technologies front-end natives, ergonomie, propreté de code, créativité et déploiement sur GitHub Pages.
Le liens de Github Pages:
https://ahmedami19.github.io/mini-blog-static/

---

## 🛠️ Technologies utilisées

### **Front-end**
- **HTML5** → structure sémantique, sections, navigation claire  
- **CSS3** → design responsive, variables CSS, animations légères  
- **JavaScript Vanilla (ES6+)**  
  - `fetch()` pour charger le JSON  
  - Manipulation du DOM  
  - Filtrage dynamique  
  - Routing à base de `window.location.hash`  
  - Gestion d’états (recherche, catégories, articles)  

### **Hébergement**
- **GitHub Pages** (déploiement du site statique)

---

## ✨ Fonctionnalités principales

### ✔ **Affichage d’articles depuis un fichier JSON**
Le blog charge un fichier `articles.json` contenant une liste d’articles avec :
- titre  
- catégorie  
- image  
- résumé  
- contenu  
- date  

Si le JSON n’est pas accessible, une **liste fallback** interne est utilisée.

---

### ✔ **Filtrage par catégories**
Les articles peuvent être filtrés via :
- la liste dans l’aside  
- le menu déroulant  
Les catégories sont automatiquement générées depuis le JSON.

---

### ✔ **Recherche intelligente**
Le champ de recherche filtre :
- le titre  
- l’extrait  
- le contenu  

La recherche est instantanée et ignore la casse.

---

### ✔ **Navigateur d’article / mini routing**
Chaque article possède une URL unique :


