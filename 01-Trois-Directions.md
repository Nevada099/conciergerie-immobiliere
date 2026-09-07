# 🏠 Conciergerie Immobilière — Les 3 directions

*Créé le 14 juillet 2026 · document de travail principal du projet*
*Base récupérée des sessions : SUPERPOWERS – Lesson 8 (décomposition activité) · Veille tendances (contenu).*

> ⚠️ **À valider par Katerina** : tout ce qui est marqué 🟡 est une **hypothèse** de ma part (surtout les prix et le « ce qui existe / ce qui manque »). Corrige-les — c'est TA connaissance du terrain qui compte ici.
>
> ✅ = confirmé par les anciennes sessions · 🟡 = hypothèse à valider · ❓ = info manquante à me donner

---

## Vue d'ensemble

| Direction | En une phrase | Actif rattaché | Skill/agent existant |
|---|---|---|---|
| ① 🏷️ **Ventes** | Vendre des biens immobiliers | AI Broker immo, alertes | `ai-broker-immo` |
| ② 🔑 **Location courte & longue durée** | Gérer la location pour les propriétaires | Collection Privée / Booking | `booking-assistant` |
| ③ 🔨 **Rénovation & Refurbishment** | Rénover, remettre à neuf, home staging | Renovita | `renovita-estimator` |

**Le fil rouge entre les 3 :** un propriétaire a un bien → tu peux le **rénover** (③), le **louer** (②) ou le **vendre** (①). Les 3 directions se nourrissent l'une l'autre (un bien rénové se vend/loue mieux).

**⭐ Le modèle = 3 services combinables (à la carte)** *(confirmé 15 juil.)* : **les 3 → cycle complet** (la signature) · **2 sur 3 → cycle partiel** · **Transaction seule → agence immobilière classique**. → inventaire des biens dans `00-DASHBOARD` (section « Les 3 services combinables »).

---

## 📊 Timeline d'avancement

*Étapes : Idée → Défini → Actif → Packagé → Vendu.  ● atteint · ◐ en cours · ○ à faire*

```
Étape →       Idée   Défini   Actif   Packagé   Vendu
① Ventes       ●───────●───────◐────────○────────○
② Location     ●───────●───────●────────◐────────◐   ← la + avancée (déjà du revenu)
③ Rénovation   ●───────●───────●────────○────────◐
```

*Mise à jour : 15 juil. 2026. On travaille actuellement l'étape « Packagé » des 3 (ÉTAPE 1→3 de la mission).*

---

## ① 🏷️ VENTES

**Offre.** Vente de biens immobiliers (accompagnement vendeur et/ou acheteur).
🟡 À préciser : simple mise en relation, mandat complet, ou chasse de biens pour acheteurs ?

**Cible.**
- 🟡 Propriétaires qui veulent vendre (particuliers, investisseurs).
- 🟡 Acheteurs/investisseurs à la recherche d'un bien.

**Process (parcours type).**
1. Captation du bien / du besoin (leads, réseau, annonces).
2. Qualification 🟡 (avec `ai-broker-immo` : qualification auto des leads + alertes Telegram).
3. Estimation / mise en valeur du bien (lien possible avec ③ rénovation / home staging).
4. Diffusion, visites, négociation.
5. Signature.

**Pricing.** ✅ *(confirmé par Katerina, 15 juil.)*
- **Commission de 3 à 5 %** du prix de vente.
- Le taux exact **se négocie à l'oral, à la signature du mandat** (selon le bien et l'occasion).

**Ce qui existe déjà.** ✅ Skill `ai-broker-immo` (qualification leads, réponses auto, alertes Telegram). 🟡 Réseau / historique immobilier de Katerina.

**Ce qui manque.** ❓ À définir avec toi (mandats types, page de présentation, tunnel de captation vendeurs).

---

## ② 🔑 LOCATION COURTE & LONGUE DURÉE

**Offre.** Gestion locative pour les propriétaires :
- **Courte durée** : Airbnb / Booking (annonces, voyageurs, ménage, check-in).
- **Longue durée** : bail classique (recherche locataire, bail, gestion).

**Cible.**
- 🟡 Propriétaires de biens qui veulent des revenus locatifs **sans gérer eux-mêmes**.
- 🟡 Investisseurs Airbnb / gestionnaires débordés.

**Process (parcours type).**
1. Mise en ligne des annonces (Booking / Airbnb).
2. Réponses voyageurs automatisées ✅ (`booking-assistant` + n8n).
3. Coordination ménage / check-in / check-out.
4. Suivi des réservations + reporting propriétaire (Google Sheets).

**Pricing.** ✅ *(confirmé par Katerina, 15 juil. — 2 formules, choisies selon le bien)*

**Formule A — Mandat de gestion au %**
- **22 % des revenus locatifs** pour le propriétaire (gestion complète).
- Pour les biens **haut de gamme** (ex. > 500 €/nuit) → c'est la formule à privilégier.

**Formule B — Location / sous-location (Katerina devient locataire)**
- Katerina **loue le bien au propriétaire à loyer fixe**, puis **reloue derrière** (avec son autorisation).
- Avantage propriétaire : **un revenu régulier garanti** (peu importe l'occupation).
- Pour les **petites surfaces / petit budget** relouables ~90-100 €/nuit → plus intéressant pour Katerina.

> 🗣️ Le choix de la formule **se discute à l'oral** : on explique au propriétaire les 2 façons de travailler et on regarde ce qui est le plus intéressant pour lui **et** pour Collection Privée.

**Ce qui existe déjà.** ✅ **C'est ta direction la plus mature.** Workflow Booking actif (déjà du revenu, cf. session AI OFFRE), skill `booking-assistant`, automatisations n8n. Marque « Collection Privée ».

**Ce qui manque.** 🟡 Passer du « ça tourne » au « c'est packagé et vendable » : offre écrite, grille de prix claire, page de présentation.

---

## ③ 🔨 RÉNOVATION & REFURBISHMENT

**Offre.** Travaux, remise à neuf, home staging — pour valoriser un bien (avant vente ou location). **Collection Privée coordonne et supervise** les chantiers, **délégués à plusieurs sociétés partenaires** (Renovita ou autres). La marque de façade reste **Collection Privée**.

**Cible.**
- 🟡 Propriétaires avant vente/location (valoriser le bien).
- 🟡 Investisseurs qui achètent pour rénover-revendre / rénover-louer.

**Process (parcours type).**
1. Visite / diagnostic du bien.
2. Devis structuré ✅ (`renovita-estimator`).
3. Coordination des artisans / suivi de chantier.
4. Livraison + home staging éventuel.

**Pricing.** ✅ *(confirmé par Katerina, 15 juil.)*
- **Toujours sur devis, par projet.** On commence par **comprendre le projet**.
- **Cas 1 — il y a un architecte** : on demande le **descriptif + les plans**, puis on chiffre.
- **Cas 2 — pas d'architecte** : Collection Privée porte la **casquette architecte + suivi** → on **dessine les plans** et on **rédige le descriptif** (travail supplémentaire facturé), puis on réalise les travaux.

**Ce qui existe déjà.** ✅ Devis via `renovita-estimator` · **réseau de sociétés de travaux partenaires** · Katerina supervise (casquette archi + suivi). 🟡 Chantiers en cours (ex. Rue Mornay). *(Renovita = un partenaire d'exécution, pas la marque de façade.)*

**Ce qui manque.** 🟡 Grille de prix / forfaits lisibles, page de présentation, avant/après pour la preuve sociale.

---

## 📈 Ce que l'inventaire des 9 biens révèle (à intégrer à l'offre)

*(inventaire complet dans `00-DASHBOARD`, section « Les 3 services combinables »)*

**Constats :**
- **2 vrais cycles complets** (17 CDM · 17 rue de la Comète) → ce sont les **cas phares / preuve** à raconter.
- La réalité quotidienne = surtout des **combinaisons de 2 services** (cycle partiel). Deux combos reviennent :
  - **Transaction + Rénovation** (5 Mornay ×2, passage de l'Union, Bourdonnais).
  - **Transaction + Location** (rue du Laos, Pérignon).
- **Enchaînements naturels** observés : *Location → Vente* et *Vente → Rénovation*.
- **Le bien revient** (17 CDM revendu, Comète remis en location) = **relation récurrente** = rétention.
- **Effet cascade** (Rue Pascal → réemploi du capital sur d'autres biens) = **un client, plusieurs opérations sur des années** = forte valeur-vie client + optimisation patrimoniale/fiscale.
- **Zone très concentrée** : Paris 7 (Champ-de-Mars, Laos, Pérignon, Bourdonnais, Comète), Paris 4 (Mornay), Paris 5 (Pascal) → **hyper-local rive gauche / Paris 7** — cohérent avec le site (Paris 7 / Gros-Caillou).

**Ce que ça change pour l'offre :**
- Positionner Collection Privée comme **« un seul interlocuteur pour tout le cycle de vie de votre bien »** : on entre **par n'importe quelle étape**, les 3 services se **combinent à la carte**. Le **cycle complet = l'offre signature (premium)**, mais la porte d'entrée peut être un seul service.
- Mettre en avant la **confiance dans la durée** (« vos biens reviennent chez nous ») et l'**accompagnement patrimonial** (cascade, optimisation fiscale) → cible = **propriétaires-investisseurs, Paris rive gauche**.

**Comment l'insérer dans le site collection-privee.fr :**
- 3 pages piliers **Vendre / Louer / Rénover** (= le champ sémantique de l'audit).
- 1 page **« Accompagnement cycle complet »** (ou « Private Office for Owners ») avec **17 CDM + Comète en études de cas** (photos avant/après Dropbox).
- Les **142 biens** alimentent la page Vendre ; chaque bien = mini étude de cas potentielle.

---

## 🎯 État & prochaine étape

✅ **Les modèles de prix sont confirmés** (15 juil.) pour les 3 directions (voir ci-dessus).

⭐ **Atout différenciant confirmé par Katerina — le « cycle complet » :** sur plusieurs appartements, Collection Privée est intervenue sur les **3 étapes à la suite** — Transaction (achat/vente) → Rénovation → Location (courte/moyenne/longue) ou Revente. C'est LA preuve que les 3 piliers se nourrissent. → collecté dans le Dashboard (`00-DASHBOARD`, section « Cas cycle complet »).

**Reste à faire avant le repackaging `offer-strategy` :**
1. Lister 2-3 **cas cycle complet** concrets (biens réels) → matière de preuve.
2. Trancher le positionnement : **Collection Privée** vs **Private Office for Owners** (cf. `03-Bilan-Site`).
3. Puis packager les 3 offres (nom, promesse, cible, prix, inclus, prochaine action).
