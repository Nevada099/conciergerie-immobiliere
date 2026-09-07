# 🗺️ collection-privee.fr — Structure actuelle & analyse

*Créé le 15 juil. 2026 · visite en direct du site (homepage + recherche biens).*
*Complète l'audit technique/SEO `03-Bilan-Site`. Ici = le SQUELETTE et l'ergonomie.*

---

## 1. Le squelette du site (ce qui existe)

**Menu principal :**
- **Nos services** → *Vente* (`/vendre/`) · *Location* (`/louer/`)
- **About Us** (`/about-us/`)
- **Nos collections** → 5 PDF saisonniers (Printemps 2017 → 2020)
- **Articles** (`/actualites/`)
- **Contact** (`/contact/`)

**Types de pages :**
- Recherche de biens (`/recherche-biens/`) : filtres *Localisation · Type de bien · À louer/À vendre*.
- Fiche bien : `/bien/<nom-du-bien>/` (ex. `/bien/clichy-appartement-renove/`).
- Page ville : `/ville/75010/`.
- Pages fixes : accueil, vendre, louer, about, contact, actualités, mentions légales, plan du site.
- Comptes utilisateurs : **Login / Register / Reset password** en page d'accueil (module WPResidence).

**Éléments d'accueil :** slider (10 visuels) · widget de recherche · bloc « NOS DERNIÈRES NOUVEAUTÉS – Des biens d'exception, pour une clientèle d'exception » · cartes de biens.
**Coordonnées :** 14 rue du Champ de Mars 75007 · 07 63 77 17 17 · contact@collection-privee.fr · FB / LinkedIn / Instagram (@agencecollectionprivee).
**Détail notable :** un widget **« 🤖 Assistant IA »** est présent sur le site.

---

## 2. La structure des biens est-elle efficace / confortable / visible ?

### ✅ Ce qui marche déjà
- **Positionnement premium** clair (« biens d'exception, clientèle d'exception »).
- Cartes de biens correctes : photo, prix, statut (**Exclusivité** = bon signal), quartier, surface, agent.
- Recherche par type + projet + localisation présente.
- Vrai stock : ~142 biens, quartiers prisés (Paris 7, 16, 6, Neuilly…).

### ⚠️ Ce qui coince (confort & efficacité)
- **La Rénovation n'est PAS dans le menu** (seulement un petit lien en pied de page). Ton **pilier ③ est quasi invisible**.
- **Aucune trace de la Conciergerie Privée / du Cycle complet** : le cœur de ta nouvelle offre n'existe nulle part.
- **Données incomplètes** sur plusieurs biens : prix manquant, surface/pièces manquantes → le visiteur ne peut pas se décider.
- **Noms d'agents incohérents** : « KATERINA IDYRÉ » vs « Katerina - » vs « JULIA TRUCHOT » → manque de soin.
- **Titres de biens = quartier seul** (« Paris VII – Gros Caillou ») : ni type, ni prix, ni surface → mauvais pour scanner ET pour Google (cf. audit).
- **Filtres pauvres** : pas de fourchette de prix, pas de nombre de pièces, pas d'arrondissement → inconfortable pour un acheteur.
- **« Nos collections » = 5 PDF de 2017-2020** : périmés, invisibles pour Google, donnent une image d'abandon.
- **Login / Register public** : inutile pour une agence privée, ça encombre et ça expose.
- **« Copyright 2021 »** en pied de page → le site paraît figé.

### 🔴 Verdict
La **base est bonne** (stock premium, cartes correctes) mais la structure **ne raconte plus ton activité réelle** : elle montre *Vente + Location* alors que tu fais *Transaction + Location + Rénovation + Cycle complet*. Et elle est **invisible sur Google** (cf. audit). → **efficace à 40 %**, à restructurer autour des 3 piliers.

---

## 3. Ce qu'il faut changer (aligné sur la nouvelle offre)

1. **Refaire le menu autour des 3 piliers + la signature :**
   `Vendre · Louer · Rénover · Accompagnement (Cycle complet) · À propos · Contact`.
2. **Ajouter la page « Rénovation »** (Renovita) dans le menu + une page **« Cycle complet / Conciergerie privée »** avec études de cas (17 CDM, Comète).
3. **Uniformiser les fiches biens** : titre = *type + surface + quartier + prix* ; compléter prix/surface/pièces partout ; un seul nom d'agence.
4. **Améliorer les filtres** : prix, pièces, arrondissement.
5. **Retirer le poids mort** : PDF « collections » périmés, Login/Register public, mention « 2021 ».
6. (Technique/SEO : voir `03-Bilan-Site` — PHP 8.2, titres/descriptions, données structurées.)

---

## 4. 🆕 Biens à mettre en ligne (reçus de Katerina, 15 juil.)

| Bien | Détails | Statut | Sources |
|---|---|---|---|
| **Les Lilas (93)** — 70 rue de Paris | 69 m², 3 pièces / 2 chambres, cuisine fermée, 3e ét., immeuble ancien, ascenseur. **À rénover.** | En vente | [SeLoger](https://www.seloger.com/annonces/achat/appartement/les-lilas-93/la-mairie/265638791.htm) · [Dropbox photos](https://www.dropbox.com/scl/fo/7uqbz68b5k8abe8736byq/AMR5HliPNNBA7t0KggQMpBA?rlkey=ow3bpbkz2n8ablo3aa9mr4ccs&dl=0) |
| **Vaugirard / Saint-Sulpice (Paris 6)** — 80 rue de Vaugirard | 147 m², 3 chambres, double séjour, terrasse 90 m², de plain-pied. | À vendre | [Fiche PDF](https://www.dropbox.com/scl/fi/nzxq0iqvhcxeti1tz7o8o/Fiche-Appartment-Saint-Sulpice.pdf?rlkey=q7cjm4q35xggzk5vcnfy0wm32&dl=0) · [Dropbox photos](https://www.dropbox.com/scl/fo/hebj7m6hurz2naag1717h/AAlTZJmGsnqBIA380ghnAWs?rlkey=3gt1hofck8r3fgogc78wy31xn&dl=0) |

> Les 2 biens sont notés. On les met en ligne **après** avoir figé le nouveau modèle de fiche bien (point 3 ci-dessus), pour ne pas les saisir deux fois.
