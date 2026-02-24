# Rapport d'audit SEO – Institut ARRISALA

**Date :** Février 2025  
**Périmètre :** 8 pages HTML (index, qui-sommes-nous, solidarite, cours-langues, 4 pages cours dédiées)

---

## 1. Synthèse

| Critère | Statut | Détail |
|--------|--------|--------|
| Titre unique par page | ✅ | Chaque page a un titre unique et descriptif avec marque + localisation |
| Meta description | ✅ | Présente et unique sur toutes les pages (~150–160 caractères) |
| Meta keywords | ✅ | Présente sur toutes les pages (ajout sur qui-sommes-nous et solidarite) |
| Un seul H1 par page | ✅ | Corrigé : section « Soutien scolaire » en H2 sur l’index (évite double H1) |
| Structure Hn cohérente | ✅ | H1 → H2 → H3 logique sur toutes les pages |
| Attribut lang | ✅ | `lang="fr"` sur toutes les pages |
| Viewport | ✅ | `meta name="viewport"` présent partout (mobile-friendly) |
| Favicon | ✅ | Présent sur toutes les pages |
| Images avec alt | ✅ | Toutes les balises `<img>` ont un attribut `alt` descriptif |
| Open Graph (partage social) | ✅ | Ajouté sur toutes les pages (og:type, og:title, og:description, og:locale) |
| Liens internes | ✅ | Navigation cohérente, ancres (#services, #contact), liens vers pages cours |

---

## 2. Détail par page

### index.html (Accueil)
- **Titre :** « Institut ARRISALA | Cours de Langues & Soutien Scolaire à Bruxelles » (~58 caractères, idéal pour Google).
- **Description :** Claire, avec mots-clés (Bruxelles, cours, soutien scolaire, 2006).
- **H1 unique :** « Institut ARRISALA : Cours de Langues & Soutien Scolaire à Bruxelles » (section visible par défaut). La section « Nos Modules de Soutien Scolaire » (vue affichée au clic) utilise désormais un **H2** pour respecter la règle d’un seul H1 par page.
- **Open Graph :** og:type, og:title, og:description, og:locale (fr_BE).

### qui-sommes-nous.html
- **Titre / description :** Uniques et en lien avec la page.
- **Meta keywords :** Ajoutées (Institut ARRISALA, ASBL Bruxelles, éducation, soutien scolaire, etc.).
- **H1 :** « Qui sommes-nous ? ».
- **Open Graph :** Ajouté.

### solidarite.html
- **Titre / description :** Uniques.
- **Meta keywords :** Ajoutées (solidarité, humanitaire Bruxelles, entraide Molenbeek, etc.).
- **H1 :** « Notre Engagement Humanitaire et Social ».
- **Open Graph :** Ajouté.

### cours-langues.html
- **Titre :** « Cours de langues (Arabe, Anglais, Néerlandais) | Institut ARRISALA Bruxelles ».
- **Description / keywords :** Présentes et pertinentes.
- **H1 :** « Nos cours de langues ».
- **Open Graph :** Ajouté.

### cours-arabe-enfants.html, cours-arabe-adultes.html, cours-anglais-enfants.html, cours-neerlandais-enfants.html
- **Titres :** Uniques, avec type de cours + « Institut ARRISALA Bruxelles ».
- **Descriptions :** Spécifiques (âge, méthode, localisation).
- **Keywords :** Adaptées à chaque cours (Bruxelles, Molenbeek, langue, etc.).
- **H1 :** Un par page, aligné avec le titre de la page.
- **Open Graph :** Ajouté sur chaque page.

---

## 3. Bonnes pratiques déjà en place

- **Contenu textuel :** Pages de cours avec contenu dédié (Pour qui, Notre approche, Horaires / Lieu), peu de risque de contenu dupliqué.
- **Maillage interne :** Liens depuis l’accueil et la nav vers les pages cours et les ancres (#contact, #services).
- **Sémantique :** Usage de `<main>`, `<nav>`, `<section>`, `<footer>`.
- **Accessibilité :** `aria-hidden` sur les éléments décoratifs, `alt` sur les images.
- **Images externes (Unsplash, textures) :** Utilisées en fond ou décoration ; pas d’images de contenu sans alternative textuelle problématique.

---

## 4. Recommandations optionnelles (après mise en ligne)

1. **Canonical :** Une fois le domaine connu, ajouter `<link rel="canonical" href="https://votredomaine.be/page.html">` sur chaque page pour éviter les doublons (www / non-www, HTTP/HTTPS).
2. **og:url :** Compléter avec l’URL absolue du site pour un meilleur partage social.
3. **og:image :** Ajouter une image de partage (ex. logo ou visuel 1200×630 px) pour Facebook/LinkedIn.
4. **Données structurées (JSON-LD) :** Enrichir avec un schéma `Organization` (et éventuellement `LocalBusiness` ou `EducationalOrganization`) pour les extraits enrichis dans Google.
5. **Sitemap XML** et **fichier robots.txt** à la racine du site pour faciliter l’indexation.

---

## 5. Modifications effectuées lors de cet audit

- Remplacement du second H1 de l’index (« Nos Modules de Soutien Scolaire ») par un **H2**.
- **Titre de l’index** raccourci pour rester dans la plage recommandée (~58 caractères).
- Ajout des **meta keywords** sur qui-sommes-nous.html et solidarite.html.
- Ajout des **balises Open Graph** (og:type, og:title, og:description, og:locale) sur les 8 pages.

Votre site est désormais bien optimisé pour le SEO et le partage sur les réseaux sociaux.
