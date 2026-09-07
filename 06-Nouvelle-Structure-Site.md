# 🏗️ collection-privee.fr — Structure AVANT / APRÈS + positionnement

*Créé le 15 juil. 2026 · propose la nouvelle arborescence du site (refonte de l'existant).*
*Sources : `03-Bilan-Site` (audit SEO/technique) + `05-Analyse-Structure-Site` (squelette en direct).*

---

## 1. 🩻 Squelette ACTUEL (existant)

```
collection-privee.fr  (Accueil : slider + recherche + « biens d'exception »)
│
├─ Nos services
│   ├─ Vente
│   └─ Location
├─ About Us
├─ Nos collections ……… 5 PDF périmés (2017 → 2020)
├─ Articles
├─ Contact
│
├─ [Recherche biens] → Fiche bien /bien/<nom>/ · Page ville /ville/<zip>
└─ [Login / Register public]  ← inutile

⚠️ Manque : Rénovation (juste un lien en pied de page) · Cycle complet · Conciergerie
⚠️ Invisible sur Google (aucun SEO) · Copyright 2021
```

## 2. 🏛️ Squelette PROPOSÉ (cible)

```
COLLECTION PRIVÉE — Conciergerie Privée Immobilière   (Paris rive gauche)
Accueil : promesse « un seul interlocuteur pour tout le cycle de vie de votre bien »
          + 4 portes d'entrée
│
├─ VENDRE                    ← pilier ① Transaction
├─ LOUER                     ← pilier ② (courte · moyenne · longue durée)
├─ RÉNOVER  (Renovita)       ← pilier ③  [NOUVEAU dans le menu]
├─ ACCOMPAGNEMENT PATRIMONIAL / CYCLE COMPLET   ← 🔵 signature  [NOUVEAU]
│     └─ Études de cas : 17 CDM · rue de la Comète (avant/après)
│
├─ NOS BIENS  (recherche améliorée : prix · pièces · arrondissement)
│     └─ Fiche bien — gabarit unifié (voir §3)
├─ À PROPOS   (15 ans d'expérience · founder-market fit)
├─ JOURNAL / ACTUALITÉS  (articles SEO : marché 7e, fiscalité, rénovation)
└─ CONTACT

🗑️ Supprimé : PDF « collections » périmés · Login/Register public · mention « 2021 »
🔎 + SEO : PHP 8.2, titres/descriptions, données structurées (cf. 03)
```

## 3. 🧱 Gabarit unifié de fiche bien

**Titre type :** `Appartement 3 pièces · 74 m² · Paris 7 Tour-Maubourg · 950 000 €`
- Badges : *À vendre / À louer / Exclusivité / Rénové par Collection Privée*
- Champs obligatoires : **prix · surface · pièces · étage · quartier · DPE**
- Photos soignées · description structurée
- **Un seul nom d'agence** (fini « Katerina - » vs « KATERINA IDYRÉ »)
- Encart cycle *(si applicable)* : « Ce bien a été **rénové** puis **loué** par Collection Privée » → renvoie à l'offre Cycle complet
- CTA clair : *Demander une visite · Faire estimer mon bien*

---

## 4. 🎯 Conciergerie Privée OU Collection Privée ? → **on garde Collection Privée**

**Recommandation : garder le NOM « Collection Privée » et ajouter « Conciergerie Privée » comme LIGNE DE POSITIONNEMENT.**
On ne change pas de nom — on change la façon de se décrire.

**Pourquoi garder « Collection Privée » :**
- Le **domaine existe depuis 2018** (valeur SEO) + réseaux sociaux `@agencecollectionprivee` + reconnaissance.
- Changer de nom = repartir de zéro (référencement, notoriété, cartes de visite, mandats…).

**Comment intégrer « Conciergerie Privée » dans l'existant :**
- **Signature de marque** partout : **« Collection Privée — Conciergerie Privée Immobilière »**.
- Le concept se voit dans la **structure** (les 4 portes : Vendre / Louer / Rénover / Cycle complet), pas dans un nouveau nom.
- Message d'accueil = la promesse « un seul interlocuteur pour tout le cycle de vie de votre bien ».
- *Private Office for Owners* = version anglaise / haut de gamme de la même idée.

> En clair : **même nom, nouvelle promesse, nouvelle structure.** On repositionne, on ne rebaptise pas.

---

## 5. ▶️ Prochaine étape
Valider cette arborescence → elle devient le **cahier des charges de la refonte** (pages à créer/réécrire, gabarit fiche, suppressions), puis on attaque la partie technique (PHP 8.2, SEO).
