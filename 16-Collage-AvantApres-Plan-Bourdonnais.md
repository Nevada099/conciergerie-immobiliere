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

> ⚠️ Les photos ne sont **pas numérotées par pièce** (noms génériques `bourdonais97-N.jpg` / `hd (N).jpg`) → l'appariement ci-dessous est **proposé par identification visuelle** (angle de fenêtre, moulures, vue balcon) et **à confirmer** au montage, comme pour 17 CDM.

## ✅ Sélection des paires (proposée — 10 sept.)

| Paire | AVANT (`hd`) | APRÈS (`edited 97bourd day`) | Confiance | Narration |
|---|---|---|---|---|
| **Vue balcon / Tour Eiffel** | `hd (12).jpg` (balcon nu, ferronnerie, vue toits + Tour Eiffel) | `bourdonais97-12.JPG` (même angle exact, balcon fini) | 🟢 **forte** — cadrage identique | « Une vue qui ne change pas. Tout le reste, si. » |
| **Cuisine** | `hd-(5).jpg` (cuisine brute, murs blancs nus) | `bourdonais97-13.JPG` (cuisine bleu-marine équipée — légende PDF : « Cuisine Bleu-marine va accueillir toute la famille ») | 🟢 forte | « On reprend tout, jusqu'au dernier tiroir. » |
| **Salle de bains** | `hd (6).jpg` (baignoire ancienne, carrelage usé) | `bourdonais97-11.JPG` (douche marbre, robinetterie dorée) | 🟡 moyenne — même pièce probable, à confirmer | « On reprend tout. » |
| **Entrée** | `hd (10).jpg` (couloir/entrée brute, moulures, vue balcon au fond) | `bourdonais97-10.JPG` (entrée meublée, console, miroirs dorés — 1er plan de la vidéo) | 🟡 moyenne | — |
| **Suite parentale** | `hd (1).jpg` (chambre brute, pan de mur rouge, radiateur) | `bourdonais97-15.JPG` (chambre finie, tête de lit, appliques dorées — légende PDF : « Bienvenue à la suite parentale ») | 🟡 moyenne — à confirmer sur les photos HD (fenêtre/radiateur) | « Chacun son espace. » |
| **Salon** *(option)* | `hd (9).jpg` (pièce brute, cheminée visible, rideaux jaunes) | *(pas dans le dossier Dropbox — voir `Renovation.pdf` p.4, « Un Salon chaleureux avec cheminée décorative » : après-photo exclusive au PDF)* | 🟡 moyenne | « Le cœur de la maison. » |

*(4 à 6 paires, comme pour 17 CDM — largement suffisant pour un collage ou un carrousel.)*

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
