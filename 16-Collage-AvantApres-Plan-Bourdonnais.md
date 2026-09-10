# 🖼️ Plan du collage AVANT / APRÈS — 97 avenue de la Bourdonnais

*Créé le 10 sept. 2026 · cahier des charges pour l'agent `ai-visual-creator`. Même gabarit que `13-Collage-AvantApres-Plan.md` (17 CDM).*

---

## 🎯 Objectif
Produire un visuel **AVANT → APRÈS** qui prouve la rénovation tous corps d'état, pour la page « Que faire de votre bien ? » (étude de cas `15`) + réseaux.

## 📁 Sources (Dropbox — dossier partagé par Evgenia Margolis)
- **AVANT** (appartement brut) : dossier `Photos/hd/` — **12 photos** ­— *et son doublon basse résolution `Photos/sd/` (mêmes prises de vue, à ne pas confondre avec des photos différentes)*.
- **APRÈS** (appartement rénové, livré) : dossier `Photos/edited 97bourd day/` — **17 photos** (lumière du jour) + `Photos/edited 97bourd night/` — **16 photos** (ambiance soirée, bonus non indispensable au avant/après).
- **Vidéo finie** : `bourdonnais-dernier-version.m4v` (1 min 36, silencieuse).
- **Portfolio déjà monté** (référence utile, pas la source finale) : `Rénovation/Renovation.pdf` (12 p., co-brandé MMD × Collection Privée) et `Rénovation/Dossier de renovation.pdf` (9 p., même contenu en version Collection Privée seule) — les deux contiennent déjà les paires avant/après par pièce avec légendes ; s'en servir pour **confirmer** les appariements ci-dessous, pas pour les redécouvrir.

> ✅ **Mise à jour du 10 sept. (soir) : appariement vérifié photo par photo** (les 12 avant + les 17 après ont été ouvertes une par une) et **copié dans un nouveau dossier Dropbox** : `/COLLECTION PRIVEE/4. Mandats/97, Avenue de la Bourdonnais/AVANT-APRES TRIE/` (fichiers renommés `<Pièce>-avant.jpg` / `<Pièce>-apres.jpg`, voir `LISEZ-MOI.txt` dans ce dossier). Le tableau ci-dessous reflète ce qui a été confirmé visuellement, pas une simple hypothèse.

## ✅ Sélection des paires (vérifiée le 10 sept.)

| Paire | AVANT (`hd`) | APRÈS (`edited 97bourd day`) | Confiance | Repère de reconnaissance |
|---|---|---|---|---|
| **Salon (cheminée)** | `hd (10).jpg` | `bourdonais97-9.JPG` | 🟢 **confirmée** | Même alcôve à étagères + cheminée ; le tableau « La Grande Vague » est accroché au même endroit après travaux. |
| **Vue balcon / Tour Eiffel** | `hd (12).jpg` | `bourdonais97-12.JPG` | 🟢 **confirmée** | Cadrage et ferronnerie identiques. |
| **Cuisine** | `hd-(5).jpg` | `bourdonais97-13.JPG` | 🟢 **confirmée** | Légende PDF « Cuisine Bleu-marine » ; même fenêtre. |
| **Salle de bains** | `hd (6).jpg` (baignoire ancienne) | `bourdonais97-3.JPG` (douche + double vasque) | 🟢 confirmée | Même volume de pièce, baignoire remplacée par douche. |
| **Suite parentale** | `hd (4).jpg` (chambre papier peint toile de Jouy, avec sa petite salle d'eau visible en arrière-plan) | `bourdonais97-15.JPG` | 🟢 confirmée | Légende PDF « Bienvenue à la suite parentale ». |
| **Entrée** | *(aucune photo avant disponible dans `hd`/`sd`)* | `bourdonais97-10.JPG` (console, miroirs dorés — 1er plan de la vidéo) | ⚪ après seulement | — |
| **Chambre (rideaux bleus)** | `hd (7).jpg` / `hd (8).jpg` | *(pas identifiée avec certitude dans le dossier après)* | 🟡 avant seulement, à confirmer | Chambre à placards muraux, rideaux fleuris bleus. |
| **Chambre (pan de mur rouge)** | `hd (1).jpg` / `hd (2).jpg` | *(pas identifiée avec certitude dans le dossier après)* | 🟡 avant seulement, à confirmer | Chambre avec placard-miroir et niche peinte en rouge. |

*(5 paires confirmées + 2 avant orphelines + 1 après orpheline = les 12 avant et les photos après clés sont toutes couvertes. Largement suffisant pour un collage ou un carrousel.)*

## 🎨 Formats à produire
1. **Collage image (grille avant/après)** — 2 colonnes (Avant | Après), 1 visuel par pièce, format carré 1080×1080 ou 4:5.
2. **Carrousel Instagram** — reprend le découpage de `15` (post JTBD, 7-8 slides).
3. **Reel avant/après** — la vidéo `bourdonnais-dernier-version.m4v` peut servir de plan « après » en mouvement ; pas de plan « avant » filmé disponible (seulement des photos) → transition photo-brute → vidéo-finie plutôt qu'un vrai wipe vidéo/vidéo.

## 🎨 Charte
Identique à `13` : sobre, luxe discret, texte fin sur espace négatif, palette neutre, logo Collection Privée discret.

---

## 📄 Où insèrent les PDF sur le site ?

Les 2 PDF (`Renovation.pdf`, `Dossier de renovation.pdf`) sont un **portfolio déjà mis en page**, pas juste des photos brutes. Deux options, à trancher avec Katerina :

- **Option A — ne pas les publier tels quels.** Le cahier des charges WordPress (`09`, §5) prévoit justement de **retirer** les anciens PDF « collections » du menu (poids mort, mauvais pour le SEO/la vitesse). Dans cette logique, on **n'ajoute pas** un nouveau PDF public : on se sert de son contenu (textes, sélection de photos) pour construire la page HTML de l'étude de cas `15`, qui est bien plus légère et référencée par Google — cohérent avec la direction déjà prise pour la refonte.
- **Option B — les proposer en téléchargement, si Katerina y tient.** Le plugin **PDF Embedder** est déjà installé et à jour sur le site (cf. mémoire technique) → techniquement possible d'ajouter un bouton « Télécharger le dossier complet » sur la page étude de cas. Dans ce cas, choisir **un seul des deux PDF** (le `Dossier de renovation.pdf`, sans le co-branding MMD, est le plus neutre pour usage public).

**Recommandation : Option A.** Le contenu vit mieux comme page web (rapide, indexée) ; garder les 2 PDF en archive interne seulement.

## 🎥 Où insère la vidéo sur le site ?

`bourdonnais-dernier-version.m4v` (1 min 36, silencieuse, format non web-optimisé) :
- **Convertir** en `.mp4` (H.264, compressé) avant toute mise en ligne — le `.m4v` brut est lourd et mal supporté par certains navigateurs.
- **Héberger** en dehors de WordPress (YouTube non-répertorié ou Vimeo) puis **embarquer** le lecteur dans la page étude de cas `15` — évite d'alourdir l'hébergement OVH mutualisé.
- **Usage secondaire :** réutilisable telle quelle comme **Reel Instagram** (silencieuse → ajouter une musique de fond + le texte du hook en overlay, cf. skill `teaser-video-immo`).

*(Décision d'hébergement vidéo à valider avec Katerina — pas encore tranchée dans le cahier des charges WordPress `09`.)*

---

## ▶️ Exécution
- Confié à **`ai-visual-creator`** (production des assets + exports HD) une fois les paires confirmées visuellement.
- Étape suivante possible : ouvrir les 6 paires proposées en plein résolution pour valider/corriger l'appariement avant montage.
