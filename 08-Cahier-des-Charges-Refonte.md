# 📐 Cahier des charges — Refonte collection-privee.fr

*Créé le 15 juil. 2026 · document d'exécution de la refonte.*
*Sources : `03-Bilan-Site` (technique/SEO) · `05-Analyse-Structure` · `06-Nouvelle-Structure` · `07-Conciergerie-Privee`.*

---

## 1. Cadre
- **Nom (inchangé) :** Collection Privée.
- **Positionnement :** Conciergerie Privée Immobilière — Paris rive gauche.
- **Promesse d'accueil :** « Un seul interlocuteur pour tout le cycle de vie de votre bien. »
- **Principe :** on **refond l'existant** (on ne repart pas de zéro), autour des **3 piliers + l'offre signature**.

---

## 2. Arborescence cible

```
Accueil (promesse + 4 portes + preuve)
├─ VENDRE                       ← ① Transaction
├─ LOUER (courte/moyenne/longue)← ② Gestion locative
├─ RÉNOVER                      ← ③  [NOUVEAU au menu] (coord. par Collection Privée)
├─ QUE FAIRE DE VOTRE BIEN ? 🔵 ← signature [NOUVEAU] → études de cas (17 CDM, Comète)
├─ NOS BIENS (filtres : prix · pièces · arrondissement)
│     └─ Fiche bien = gabarit unifié
├─ À PROPOS (15 ans · founder-market fit)
├─ JOURNAL (articles SEO)
└─ CONTACT
```

---

## 3. Migration : de l'existant vers la cible (page par page)

| Page actuelle | Devient | Action | URL |
|---|---|---|---|
| Accueil | Accueil (nouvelle promesse + 4 portes) | **Réécrire** | `/` (garder) |
| Nos services › Vente | **VENDRE** | Garder + enrichir | `/vendre/` ✅ existe |
| Nos services › Location | **LOUER** (courte/moyenne/longue) | Garder + enrichir | `/louer/` ✅ existe |
| (lien « Rénovation » en pied de page) | **RÉNOVER** | **Créer** + mettre **au menu** | `/renover/` ✅ confirmé |
| — | **QUE FAIRE DE VOTRE BIEN ?** 🔵 | **Créer** (contenu = `07`) | `/que-faire-de-votre-bien/` |
| Nos collections (5 PDF 2017-2020) | — | **Retirer du menu** (archiver les PDF) | — |
| Articles | **JOURNAL** | Garder + optimiser les 7 articles | `/actualites/` |
| About Us | **À PROPOS** | Réécrire | `/about-us/` |
| Contact | **CONTACT** | Garder | `/contact/` |
| Recherche biens | **NOS BIENS** | Améliorer filtres + gabarit fiche | `/recherche-biens/` |
| Login / Register public | — | **Désactiver** le module public | — |
| Fiches `/bien/<slug>/` | Fiches (gabarit unifié) | Réécrire titres + compléter champs (142 biens) | `/bien/...` |

> ⚠️ **Redirections 301** pour toute URL supprimée/modifiée → on ne perd pas le référencement acquis.

---

## 4. Brief court de chaque page

- **Accueil :** promesse cœur + les 4 portes (Vendre/Louer/Rénover/Que faire de votre bien) + 1 étude de cas en aperçu + CTA.
- **Vendre :** pour propriétaires vendeurs · commission 3-5 % · discret/off-market · qualification acquéreurs · CTA « Faire estimer mon bien ».
- **Louer :** 2 formules (mandat 22 % / location-sous-location revenu garanti) · courte/moyenne/longue durée · gestion déléguée · CTA « Estimer le potentiel locatif ».
- **Rénover :** Collection Privée **coordonne et supervise** les chantiers, **délégués à plusieurs sociétés partenaires** (Renovita ou autres) · devis par projet · casquette architecte si besoin · avant/après · CTA « Demander un devis ». *(Marque = Collection Privée, pas Renovita.)*
- **Que faire de votre bien ? :** contenu complet dans `07` (question → diagnostic → scénarios → pilotage → juridique → études de cas → CTA « Parlons de votre bien »).
- **Nos biens :** recherche filtrable (prix, pièces, arrondissement) + gabarit fiche.
- **À propos :** **contenu entièrement refait** sous l'angle **conciergerie immobilière** (15 ans d'expérience, founder-market fit loueuse + bâtisseuse, l'équipe).
- **Journal :** réécrire les articles ; **déterminer d'abord les sujets les plus à jour, reliés à l'actualité** pour aider le SEO (marché 7e, fiscalité, rénovation). 2 articles/mois, réutilisables en vidéo/avatar.
- **Contact :** coordonnées, formulaire (avec champ source), lien réseaux.

---

## 5. Gabarit unifié de fiche bien

**Format du titre :** `Type · X pièces · Y m² · Ville/Quartier · Prix`
> ex. `Duplex · 3 pièces · 74 m² · Paris 7 Tour-Maubourg · 950 000 €`

**Champs obligatoires :** statut (À vendre / À louer / **Exclusivité** / **Rénové par Collection Privée**) · prix · surface · pièces · chambres · étage · **DPE** · quartier · description structurée · **≥ 8 photos** soignées · **un seul nom d'agence** (Collection Privée).
**Encart cycle** *(si applicable)* : « Ce bien a été rénové puis loué par Collection Privée » → lien vers la page signature.
**CTA :** « Demander une visite » / « Faire estimer mon bien ».
**SEO (par fiche) :** balise title + meta description remplies · **données structurées** (annonce immobilière) · Open Graph (image + titre au partage).

---

## 6. Ce qu'est une « étude de cas » (réponse détaillée)

Une **étude de cas = 1 page qui raconte l'histoire d'un bien** que tu as accompagné sur plusieurs étapes. C'est ta **preuve vivante**. Structure :

1. **Titre :** « [Quartier] — le cycle complet ».
2. **Le bien :** type, surface, quartier, **état initial**.
3. **La situation du propriétaire :** son besoin / sa contrainte (fiscale, succession, délai…).
4. **Ce que Collection Privée a fait, étape par étape** (Transaction → Rénovation → Location/Revente), avec dates si dispo.
5. **Photos AVANT / APRÈS** (depuis Dropbox).
6. **Le résultat :** gain, délai, bénéfice concret.
7. *(Optionnel)* une **phrase du propriétaire** (verbatim).

**Les 2 premières à rédiger :** 17 CDM · 17 rue de la Comète.
**Usage :** page « Que faire de votre bien ? » + posts LinkedIn/Instagram.

---

## 7. Suppressions & SEO technique (rappel de l'audit `03`)
- Supprimer : PDF collections périmés, module Login/Register, mention « 2021 ».
- Technique (pré-requis) : **PHP 8.2** (OVH 1007) · MàJ WordPress/extensions · purge des 2 556 spams · Wordfence à jour.
- SEO : plugin SEO (RankMath/Yoast) · titres + descriptions des pages · données structurées · Search Console + Analytics + fiche Google Business.

---

## 8. Ordre d'exécution
1. **Technique** : PHP 8.2 + MàJ + nettoyage *(débloque tout — 1 appel OVH)*.
2. **Mesure** : Search Console + Analytics + fiche Google.
3. **Structure** : nouveau menu + créer Rénover & « Que faire de votre bien ? » + retirer le poids mort (+ redirections 301).
4. **Contenu** : réécrire Accueil / Vendre / Louer / À propos + les 2 études de cas.
5. **Fiches biens** : appliquer le gabarit unifié (+ mettre en ligne Les Lilas & Vaugirard).
6. **SEO éditorial** : champ sémantique (quartiers × services) + Journal (2 articles/mois).

---

## ▶️ Décisions restantes
- Confirmer l'URL de la page Rénover (vérifier l'existant).
- Qui exécute la partie WordPress (toi / prestataire / moi en accompagnement) ?
