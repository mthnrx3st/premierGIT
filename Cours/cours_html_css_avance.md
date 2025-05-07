# 🚀 HTML & CSS - Niveau Supérieur

Bienvenue dans la suite du cours HTML & CSS. Dans cette partie, nous allons aborder des notions plus avancées pour rendre vos sites plus dynamiques, responsives et mieux structurés.

---

## 1. Structure HTML avancée

### 🔹 Sémantique HTML

Utilisez des balises sémantiques pour améliorer l’accessibilité et le référencement :

| Balise | Rôle |
|--------|------|
| `<header>` | En-tête du site ou section |
| `<nav>` | Menu de navigation |
| `<main>` | Contenu principal |
| `<section>` | Section de contenu |
| `<article>` | Contenu autonome (ex : blog) |
| `<aside>` | Contenu complémentaire |
| `<footer>` | Pied de page |

### Exemple :

```html
<main>
  <article>
    <h2>Article 1</h2>
    <p>Contenu de l'article...</p>
  </article>
</main>
```

---

## 2. CSS Avancé

### 🔸 Sélecteurs complexes

```css
article > p {
  color: blue;
}

nav a:hover {
  text-decoration: underline;
}
```

### 🔸 Pseudo-classes & pseudo-éléments

```css
a:hover {
  color: red;
}

p::first-line {
  font-weight: bold;
}
```

### 🔸 Variables CSS

```css
:root {
  --main-color: #3498db;
}

body {
  background-color: var(--main-color);
}
```

---

## 3. Flexbox

Permet de créer des mises en page flexibles et adaptables.

### Exemple :

```html
<div class="flex-container">
  <div>Bloc 1</div>
  <div>Bloc 2</div>
  <div>Bloc 3</div>
</div>
```

```css
.flex-container {
  display: flex;
  justify-content: space-around;
  align-items: center;
}
```

---

## 4. Grid Layout

Un autre système puissant de mise en page.

```css
.grid-container {
  display: grid;
  grid-template-columns: 1fr 2fr;
  gap: 10px;
}
```

---

## 5. Responsive Design

### 🔹 Media Queries

```css
@media (max-width: 768px) {
  body {
    background-color: lightgray;
  }
}
```

Permet d’adapter l’affichage selon la taille de l’écran.

---

## 6. Animation et transitions

### 🔹 Transitions

```css
button {
  transition: background-color 0.3s ease;
}

button:hover {
  background-color: #555;
}
```

### 🔹 Animation

```css
@keyframes slide-in {
  from { transform: translateX(-100%); }
  to { transform: translateX(0); }
}

.element {
  animation: slide-in 1s ease-in-out;
}
```

---

## 7. Bonnes pratiques avancées

- Utilisez des **classes BEM** (`.block__element--modifier`)
- Utilisez des **fichiers CSS modulaires**
- Commentez et structurez votre CSS
- Testez sur plusieurs navigateurs et appareils

---

## 8. Outils à découvrir

- [SASS / SCSS](https://sass-lang.com/)
- [Tailwind CSS](https://tailwindcss.com/)
- [Bootstrap](https://getbootstrap.com/)
- [Figma](https://www.figma.com/) pour le design

---

## 🎯 Conclusion

Avec ces notions avancées, vous avez les outils pour créer des sites web modernes, responsifs, esthétiques et performants. Continuez à pratiquer, explorez les frameworks CSS, et amusez-vous à créer !

