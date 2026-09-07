# 🗼 Jade — Stratégie Avatar : Funnel de qualification + Concierge + Produit AILAB

> Document de travail — 12 août 2026
> Site concerné : location.collection-privee.fr (appartement 106 av. de Suffren)
> Source : page Notion « Jade — concierge assistance app » + audit Claude in Chrome de la page live.

---

## 1. LA DÉCISION QUI DÉBLOQUE TOUT : il y a DEUX Jade, pas une

C'est le cœur du problème. Aujourd'hui, la base de Jade est un **concierge d'après-réservation** (codes d'accès, wifi, serviettes, serrure, 20 restaurants…) mais elle est posée sur la **page publique**, où 99 % des visiteurs **n'ont pas encore réservé**.

Le contenu sert le **client** ; l'emplacement sert le **prospect**. C'est le mismatch central.

👉 Ce ne sont pas deux versions du même avatar. Ce sont **deux produits, pour deux personnes, à deux moments** :

| | **Jade Qualifieuse** | **Jade Concierge** |
|---|---|---|
| **Pour qui** | Prospect anonyme (n'a pas réservé) | Client confirmé (a payé) |
| **Où** | Page publique (hero) | Email de confirmation / lien privé / QR dans l'appart / message vidéo Messenger |
| **Quand** | AVANT la réservation | APRÈS la réservation |
| **Job** | Transformer le trafic en réservation | Servir le client, réduire les messages répétitifs, expérience premium |
| **Discours** | Entonnoir : dates → voyageurs → tarif → réserver | Accueil chaleureux + réponses pratiques (codes, wifi, quartier) |
| **Base de connaissances** | Réduite : ce qui aide à DÉCIDER | Complète : ce qui aide à SÉJOURNER (la base actuelle, déjà parfaite) |
| **Le prix** | Central (levier de conversion) | Absent (déjà payé) |

**Même personnage, même voix, même marque — mais deux prompts, deux emplacements.**

> ⚠️ Reality gate n°0 (à corriger AVANT tout le reste) : sur la page live, le widget Jade s'ouvre seul, occupe un grand panneau à droite, mais **l'écran vidéo reste noir** (autoplay/micro bloqués). Un avatar en écran noir sur le hero = une **fuite de conversion**, pas un atout. Tant que Jade n'est pas nette et fiable au chargement, elle coûte des réservations. À tester en priorité.

---

## 2. SWOT de Jade (état actuel) + CJM corrigé

### SWOT

**Forces**
- Contenu concierge riche, précis, « anti-invention » (règle « ne rien inventer » = excellente, protège la marque).
- Ton de marque premium bien défini (vouvoiement, luxe discret, phrases courtes).
- Différenciateur fort : peu d'annonces courte durée haut de gamme ont un avatar vivant.

**Faiblesses**
- Avatar en écran noir au chargement (fuite critique).
- Intro trop longue → tronquée (« …Collection Privée. Cet… »).
- 100 % vocal, **zéro élément cliquable** → on perd l'utilisateur au moment de l'action.
- Aucun prix, aucune dispo affichés → le visiteur ne peut pas se qualifier lui-même.
- Contenu concierge (après-résa) posé sur la page publique (avant-résa) = hors-sujet pour 99 % des visiteurs.

**Opportunités**
- En faire un **produit AILAB** revendable à d'autres loueurs / conciergeries (cf. §6).
- Réservation directe = moins de commission plateforme (Airbnb/Booking) + relation client en direct.
- Mode texte → capte les gens qui n'osent pas parler à un avatar (open space, lieu public).

**Menaces**
- Sur-construction (« l'usine » Google Calendar + Stripe + moteur de prix) avant d'avoir prouvé que Jade convertit → temps perdu (cf. §5).
- Un avatar buggé nuit à l'image premium (l'inverse de l'effet recherché).

### CJM visiteur — les points de douleur et leur correction

| Étape | Émotion | Douleur actuelle | Correction |
|---|---|---|---|
| Découverte (hero) | Curiosité | Jade recouvre la page, écran noir → « c'est cassé » | Fiabiliser le lancement ; intro courte ; ne pas recouvrir tout l'écran |
| Exploration (photos) | Séduction | Magnifique mais **aucun prix** → il ne peut pas se qualifier | Afficher **« à partir de X €/nuit »** sur la landing |
| **Considération** 🔴 (pic) | Doute | Pas de dispo, pas de prix. Jade récite wifi/serviettes = hors-sujet | Jade **Qualifieuse** : dates → voyageurs → dispo + tarif |
| Décision (formulaire) | Hésitation | On demande le **moyen de paiement** AVANT tout prix → saut dans le vide | Prix AVANT paiement, toujours ; ne jamais demander le mode de paiement en premier |
| Attente | Incertitude | « on vous confirme rapidement » = manuel, différé | Réponse immédiate (dispo réelle) OU délai annoncé + accusé de réception |

---

## 3. OÙ POSER LE PRIX ? (ta question centrale)

Ta question : « pré-qualification de leads AVANT la résa, ou APRÈS ? »

**Réponse : le prix ne vit QUE dans le funnel AVANT la résa.** Après la réservation, le prix est déjà payé — Jade Concierge n'en parle pas. Donc la vraie question est : **à quel moment du funnel révéler le prix ?**

### Recommandation (règle en 2 temps)

1. **Ancre de prix EN HAUT, dès la landing** → « À partir de X €/nuit ».
   - Pourquoi : sans prix, le visiteur ne peut pas se qualifier lui-même → il rebondit. C'est le pic de douleur (Considération). Une fourchette filtre le trafic **avant** même de parler à Jade.
2. **Prix EXACT seulement après les dates + le nombre de voyageurs.**
   - Pourquoi : le tarif dépend de la saison, de la durée, des frais. « Pour ces dates, c'est X €/nuit, soit Y € au total » = la récompense qui déclenche la réservation.

### ❌ Ce qu'il ne faut PAS faire (mode debug)
- **Ne jamais laisser la page sans aucun prix** (état actuel) = fuite n°1.
- **Ne pas demander « quel est votre budget ? »** comme question de qualification. Pour du luxe, c'est intrusif et c'est un mauvais filtre. On laisse l'**ancre de prix + le calendrier** faire le tri à ta place.
- Ne jamais demander le **moyen de paiement** avant d'avoir montré le prix.

> Le prix n'est donc pas « avant OU après la résa » : il est **avant la résa, en 2 temps** (fourchette d'abord, exact après les dates). Le « après » concerne le concierge, qui lui ne parle pas de prix.

---

## 4. RENDRE LE DISCOURS DE JADE UN ENTONNOIR (le bloc restructuré)

### 4.A — Jade QUALIFIEUSE (page publique, AVANT réservation)

**➤ Nouvelle intro (remplace l'« Opening intro » actuelle, trop longue et tronquée)**

> « Bonjour, je suis Jade, l'hôte de cet appartement avenue de Suffren, vue Tour Eiffel.
> Dites-moi vos **dates** et le **nombre de voyageurs** — je vérifie tout de suite les disponibilités et le tarif. »

Courte (2 phrases), pose d'emblée les 2 questions clés, promet la récompense (dispo + tarif). Ne se fait pas tronquer.

**➤ Règles d'entonnoir à ajouter au prompt (section « OBJECTIFS DE CONVERSATION » à remplacer)**

```
OBJECTIF UNIQUE (page publique) : obtenir les DATES et le NOMBRE DE VOYAGEURS,
puis déclencher l'action « Voir les disponibilités & le tarif ».

Tu n'es PAS un concierge ici. Tu ne parles pas des codes d'accès, du wifi,
des serviettes ni de la serrure : ce sont des infos réservées au client confirmé.

MÉTHODE ENTONNOIR :
1. Réponds BRIÈVEMENT à toute question (2 phrases max), puis relance
   systématiquement vers une question de qualification.
2. Trois questions maximum, tissées naturellement, jamais en interrogatoire :
   a) dates ou période souhaitée
   b) nombre de voyageurs
   c) (facultatif) type de séjour : tourisme, affaires, événement
3. Dès que tu as DEUX infos (ex. dates + voyageurs), BASCULE vers l'action :
   « Je peux vérifier les disponibilités et le tarif exact pour vos dates —
    je vous ouvre le calendrier de réservation. »
   → et affiche la carte cliquable « Voir les disponibilités & le tarif ».

LE PRIX :
- Si on te demande le prix sans dates : donne la fourchette
  « à partir de X €/nuit », puis demande les dates pour un tarif exact.
- Tarif exact : uniquement via le module de réservation, jamais inventé.

GARDE-FOUS :
- Si la conversation traîne (plus de 3-4 échanges sans progression) ou part
  hors-sujet, recentre : « Je suis surtout là pour vérifier votre séjour —
  puis-je avoir vos dates ? »
- Propose toujours un MODE TEXTE en plus du vocal (beaucoup préfèrent taper).
- Escalade vers un humain pour : modification, annulation, paiement, réclamation,
  urgence, demande commerciale exceptionnelle. → [EMAIL / TÉL Collection Privée]

CLÔTURE SYSTÉMATIQUE (rappeler les 2 issues) :
« Soit je vous ouvre le calendrier pour réserver directement,
  soit je transmets votre demande à notre équipe qui vous recontacte. »
```

**➤ L'élément qui manque le plus : un BOUTON.** Un avatar 100 % vocal perd l'utilisateur au moment décisif. Ajouter dans le widget une **carte cliquable « Voir les disponibilités & le tarif »** qui apparaît dès que le funnel est complété, et qui ouvre le calendrier / le module de réservation (idéalement **pré-rempli** avec les dates + voyageurs déjà donnés à Jade).

---

### 4.B — Jade CONCIERGE (APRÈS réservation, message vidéo Messenger / email)

C'est ici qu'on **recase le contenu actuel** (déjà excellent). Il ne disparaît pas : il change juste d'emplacement et de moment. Envoyé **une fois la réservation confirmée**, en message vidéo (Messenger/WhatsApp) ou en email.

**➤ Script vidéo d'accueil post-réservation (~45-60 s, format Luna : phrases courtes < 15 mots)**

> « Bonjour et félicitations, votre séjour avenue de Suffren est confirmé !
> Je suis Jade, votre hôte. Je reste avec vous jusqu'à votre départ.
>
> Avant l'arrivée, retenez l'essentiel. Vous recevez vos codes d'accès juste avant le jour J.
> L'appartement est au dernier étage. À la sortie de l'ascenseur, la porte de droite.
>
> Tout est prêt : le lit est fait, les serviettes vous attendent, le wifi est affiché face à la télévision.
> Sur le balcon, dépliez la table pour profiter de la vue.
>
> Une question pendant le séjour ? Le métro, un bon restaurant, l'aéroport ?
> Écrivez-moi ici à tout moment — je connais le quartier par cœur.
>
> Très beau séjour à Paris. Vous êtes chez vous. »

**➤ Jade Concierge reste ensuite disponible en Q&A** avec toute la base actuelle (transports, gares, aéroports, courses, 20 restaurants, santé, serrure, wifi…). C'est là qu'elle est parfaite.

> 🎯 Effet business de la partie Concierge : elle **n'augmente pas** les réservations, mais elle améliore les avis, le bouche-à-oreille, et te fait **gagner du temps** (moins de messages répétitifs). Utile — mais ce n'est pas le levier de vente. Le levier de vente, c'est Jade Qualifieuse (§4.A).

---

## 5. INTÉGRATION CALENDRIER — 100 % GRATUIT (phase de test)

Objectif : que le visiteur **voie les dates libres** et que Jade **puisse citer le tarif**, sans un centime d'outil payant.

### ✅ Solution recommandée : Google Calendar (gratuit) + case Prix maison

**Le calendrier de dispo = Google Calendar, synchronisé automatiquement depuis Airbnb/Booking, puis affiché (embed) sur le site.**

Étapes concrètes (gratuit, sans développeur) :
1. Crée un **Google Calendar dédié** : « Dispo — 106 Suffren ».
2. **Synchronise-le automatiquement** avec tes plateformes existantes :
   - Dans Airbnb (et/ou Booking) → **Exporter le calendrier** → copie le lien **iCal**.
   - Dans Google Agenda → *Autres agendas → À partir d'une URL* → colle le lien iCal.
   - → Les dates réservées sur Airbnb/Booking se **grisent toutes seules** (mise à jour auto). Zéro double-résa, zéro travail manuel.
   - *(Si location en direct uniquement : bloque les dates à la main, événement « journée entière » = « Réservé ».)*
3. Rends l'agenda **public en « Afficher seulement libre/occupé »** (masque les détails privés) : *Paramètres de l'agenda → Autorisations d'accès → Rendre public → Voir uniquement disponible/occupé*.
4. Récupère le **code d'intégration (iframe)** : *Paramètres → Intégrer l'agenda → copier le code*.
5. Fais coller cet iframe **dans la section réservation du site** (par la personne qui gère location.collection-privee.fr — 5 min, pas de dev).

> Alternative « plus jolie » (calendrier fait maison dans le style du site) : un calendrier HTML/CSS mensuel intégré à la page, dates prises grisées à la main. **Plus beau, mais 100 % manuel** (tu mets à jour toi-même, risque d'oubli → double-résa). Pour la phase de test, **Google Calendar embed gagne** : c'est gratuit ET ça se synchronise tout seul. On fera le calendrier maison plus tard, une fois le concept prouvé.

### 💶 La case PRIX (gratuit, à la main)
Aucun outil gratuit ne calcule un prix dynamique — et on n'en a **pas besoin** maintenant. On affiche une **grille tarifaire simple** par saison, dans une **case au style du site** :

| Période | Tarif indicatif / nuit |
|---|---|
| Basse saison | … € |
| Moyenne saison | … € |
| Haute saison (été, salons, fêtes) | … € |
| Nuits min. + frais de ménage | … |

Cette grille sert 2 choses : (1) l'**ancre de prix** en haut de page, (2) la **donnée que Jade a le droit de citer** (voir ci-dessous).

### 🤖 Comment Jade « accède » au calendrier et aux prix (sans dev, aujourd'hui)
En phase de test, Jade ne fait pas de requête technique en direct. On procède en **2 niveaux** :

- **Niveau 0 — cette semaine, gratuit, zéro dev :**
  - On **met la grille tarifaire dans sa base de connaissances** → elle a le DROIT de citer ces prix (ce n'est plus « inventer », c'est ta grille officielle).
  - Pour la dispo, elle **renvoie au calendrier affiché** : « Le tarif pour vos dates est d'environ X €/nuit. Regardez le calendrier juste en dessous : les dates en gris sont déjà prises. Vos dates sont libres ? Je transmets votre demande. »
  - → Concrètement, Jade **qualifie + donne le prix + pointe vers le calendrier + collecte la demande**. C'est suffisant pour tester si elle convertit.

- **Niveau 1 — plus tard, toujours gratuit, avec ton n8n :**
  - Un workflow **n8n** lit l'**API Google Calendar** (gratuite) et renvoie « libre / occupé » pour des dates données.
  - On branche ça à Jade (tool call / webhook côté HeyGen) → elle répond en direct « oui, ces dates sont libres ».
  - À faire **seulement** si le Niveau 0 prouve que Jade génère des demandes. (C'est ton terrain d'entraînement n8n / ai-systems-architect.)

> ⚠️ Piège à éviter : ne monte PAS le Niveau 1 (n8n + API) ni le paiement en ligne (Stripe) **maintenant**. D'abord, le Niveau 0 doit prouver que Jade convertit. Sinon = « je construis sans fin ».

### Où insérer la case Prix + le calendrier sur la page
1. **Dans le hero (haut de page)** : petite ancre **« À partir de X €/nuit »** (le visiteur se qualifie tout de suite).
2. **Dans la section réservation (#reserver)**, dans cet ordre : **grille de prix** → **calendrier Google embed** → **formulaire de demande**. C'est le point de décision : prix + dispo + action au même endroit.

---

## 6. POSITIONNER JADE COMME PRODUIT AILAB (offre autonome)

Une fois validé sur ton propre appartement, « Jade » devient un **service revendable** de l'agence :

**Nom d'offre (piste)** : « **Hôte IA 24/7** » — un avatar vivant sur la landing + un concierge après-réservation, pour loueurs courte durée haut de gamme, conciergeries, hôtels de charme.

**Ce que ça inclut** :
- Landing page avec live avatar (Qualifieuse) → capte et qualifie le trafic.
- Concierge IA post-réservation (vidéo + Q&A) → expérience premium, moins de SAV.
- Base de connaissances sur-mesure (le bien, le quartier, les règles).
- Branchement au module de réservation du client.

**Preuve = Collection Privée** (ton propre appartement). On ne vend pas avant d'avoir le cas qui marche. C'est ton **founder-market fit** : tu es loueuse ET tu construis l'IA.

---

## 7. PAR OÙ COMMENCER (1 seule chose cette semaine)

Ne construis rien de lourd. **UNE action** pour savoir si Jade vaut le coup :

1. **Répare le lancement de Jade** (écran noir) OU, si ça bloque, mets-la en widget discret cliquable au lieu de plein écran.
2. **Ajoute une fourchette de prix** « à partir de X €/nuit » sur la landing.
3. **Ajoute un champ caché « source : jade / direct »** sur ton formulaire actuel.

→ En 1 semaine, tu sauras si Jade contribue vraiment aux demandes — **avant** de reconstruire quoi que ce soit.

Le reste (funnel §4.A, concierge §4.B, calendrier §5) se déploie ensuite, dans cet ordre.
