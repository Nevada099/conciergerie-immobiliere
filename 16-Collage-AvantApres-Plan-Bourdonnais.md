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

> ✅ **Mise à jour du 11 sept. : appariement corrigé par Katerina, puis toutes les pièces couvertes.** Katerina a signalé que cuisine et salle de bains avaient été inversées (l'ancienne cuisine est devenue la salle de bains, et inversement) et que les 2 chambres orphelines avaient bien chacune leur photo après. Les 12 avant sont maintenant **tous** rattachés à une pièce identifiée. **Copié dans le dossier Dropbox** `/COLLECTION PRIVEE/4. Mandats/97, Avenue de la Bourdonnais/AVANT-APRES TRIE/` (fichiers renommés `<Pièce>-avant.jpg` / `<Pièce>-apres.jpg`, voir `LISEZ-MOI.txt` dans ce dossier) et assemblé en visuel collage (envoyé à Katerina en direct, pas archivé ici en image).

## ✅ Sélection des paires (corrigée le 11 sept.)

| Paire | AVANT (`hd`) | APRÈS (`edited 97bourd day`) | Confiance | Repère de reconnaissance |
|---|---|---|---|---|
| **Salon (cheminée)** | `hd (10).jpg` | `bourdonais97-9.JPG` | 🟢 confirmée | Même alcôve à étagères + cheminée ; le tableau « La Grande Vague » est accroché au même endroit après travaux. |
| **Vue balcon / Tour Eiffel** | `hd (12).jpg` | `bourdonais97-12.JPG` | 🟢 confirmée | Cadrage et ferronnerie identiques. |
| **Cuisine** | `hd (6).jpg` *(ancienne salle de bains à baignoire)* | `bourdonais97-13.JPG` | 🟢 **confirmée par Katerina** | L'ancienne salle de bains est devenue la cuisine bleu-marine. |
| **Salle de bains** | `hd-(5).jpg` *(ancienne cuisine, évier + frigo)* | `bourdonais97-3.JPG` (douche + double vasque) | 🟢 **confirmée par Katerina** | L'ancienne cuisine est devenue la salle de bains. |
| **Suite parentale** | `hd (4).jpg` (chambre papier peint toile de Jouy, avec sa petite salle d'eau visible en arrière-plan) | `bourdonais97-15.JPG` | 🟢 confirmée | Légende PDF « Bienvenue à la suite parentale ». |
| **Chambre d'enfant** | `hd (7).jpg` | `bourdonais97-6.JPG` | 🟢 **confirmée par Katerina** | Chambre à placards muraux → chambre d'enfant murs verts (bureau, dinosaure en bois). |
| **Chambre** | `hd (1).jpg` | `bourdonais97-8.JPG` | 🟢 **confirmée par Katerina** | Chambre avec niche peinte en rouge → chambre neutre, tête de lit capitonnée. |
| **Entrée** | *(aucune photo avant disponible dans `hd`/`sd`)* | `bourdonais97-10.JPG` (console, miroirs dorés — 1er plan de la vidéo) | ⚪ après seulement | — |

*(7 paires confirmées + 1 après orpheline (entrée) = les 12 avant et les photos après clés sont toutes couvertes.)*

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
