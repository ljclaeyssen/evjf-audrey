# 🥂 EVJF d'Audrey

Le planning du week-end EVJF d'Audrey — **Reims & la Montagne de Reims**, du **17 au 19 juillet 2026**.

Page unique, HTML + JS vanilla (aucune dépendance, aucun build), hébergée sur GitHub Pages.

## Voir la page

👉 https://ljclaeyssen.github.io/evjf-audrey/

## Modifier

Tout est dans [`index.html`](index.html) :

- **Le programme** : chaque activité est une carte `.item` dans la section `<section class="day">` de son jour.
- **Les horaires** : la balise `.time` en haut de chaque carte.
- **Le compte à rebours** : la ligne `var target = new Date(2026, 6, 17, 17, 0, 0)` (attention, les mois JS commencent à 0 → `6` = juillet).
- **Les couleurs & polices** : les variables CSS `:root` en haut du `<style>`.

Un commit sur `main` met la page à jour automatiquement. 💛
