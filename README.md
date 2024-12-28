
# ⚡♠️ Affichage de cartes animées au survol de souris

## 1. Description
Ce projet est un exercice pratique en **HTML/CSS**.
**Flexbox** est utilisé pour une disposition dynamique des éléments du contenu principal.
Le projet utilise des conventions de **Responsive Design** pour une accessibilité sur tous supports.
Des paramètres de **CSS** avancé sont utilisés pour rendre les cartes dynamiques au survol de la souris par l'utilisateur.
Connexion à **Google Fonts** et à **Font Awesome** pour des ajouts de typographies et d'icônes.

---

## 2. Fonctionnalités
- Changement fluide de couleur et de taille de l'entête de la carte au passage de la souris par l'utilisateur

```
.card-header img {
    filter: grayscale(1);
    transition: 300ms;
}

.card:hover img {
    filter: grayscale(0);
    transform: scale(1.1);
}
```

- Apparition fluide d'une icône type **Favori** cliquable au passage de la souris par l'utilisateur

```
.heart {
    position: absolute;
    top: 0;
    left: -40px;
    transition: 300ms;
}

.card:hover .heart {
    left: 0;
}
```

---

## 3. Accès
1. Accédez directement au projet via [ce lien](https://xylo87.github.io/Exos-FlexCards/)

2. Clonez ce projet depuis GitHub :
```bash
   git clone https://github.com/Xylo87/Exos-FlexCards.git
   cd Exos-FlexCards
```
---

## 4. Auteur
Projet réalisé par Théo Arbogast (aka Xylo87).
N'hésitez pas à ouvrir une issue ou à me contacter pour toute suggestion ou question.