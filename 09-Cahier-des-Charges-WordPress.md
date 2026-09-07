# 🛠️ Cahier des charges WordPress — refonte collection-privee.fr

*Créé le 15 juil. 2026 · document technique d'exécution, destiné à un prestataire WordPress OU à Katerina accompagnée.*
*Base technique : audit `03-Bilan-Site`. Contenu & structure : `08-Cahier-des-Charges-Refonte`.*

> **Comment lire ce document :** chaque bloc a une ligne « 🎯 Pourquoi » (en clair) et une ligne « ✅ À faire » (technique). Les blocs sont dans l'ordre d'exécution : **ne pas sauter une étape**.

---

## 0. Périmètre
- **Refonte sur le site existant** (WordPress + thème WPResidence) — on ne reconstruit pas un nouveau site.
- Objectif : site **rapide, sécurisé, visible sur Google**, structuré autour de **Vendre / Louer / Rénover / Que faire de votre bien** + fiches biens propres.

## 1. Accès nécessaires (à préparer avant de commencer)
- Admin **WordPress** (rôle administrateur).
- Espace client **OVH** (hébergement + domaine) — n° client + accès.
- Compte **Google** (pour Search Console, Analytics, Google Business Profile).
- Accès **Dropbox** (photos des biens & études de cas).
- Licence **WPResidence / Envato** (si active) + licence **Slider Revolution**.

## 2. Sauvegarde & environnement *(obligatoire avant toute modification)*
- 🎯 Pour pouvoir revenir en arrière si quelque chose casse.
- ✅ **Sauvegarde complète** (fichiers + base de données) via extension (UpdraftPlus) ou OVH.
- ✅ Idéalement, travailler sur un **site de préproduction (staging)** puis publier.

## 3. Socle technique
- 🎯 Un site sur PHP 7.1 (2019) est lent, vulnérable et bloque les mises à jour.
- ✅ **Passer l'hébergement en PHP 8.2** (OVH — appeler le **1007** avec l'identifiant client). Mentionner l'**incident 403 d'août 2026 (ticket OVH CS16618128)** pour vérifier la config serveur.
- ✅ Après PHP 8.2 : mettre à jour **WordPress**, puis **extensions**, puis **thème** (dans cet ordre, avec sauvegarde préalable).
- ✅ Vérifier que **EPL Immobilier / WpEstate CRM** refonctionnent après PHP 8.2 (sinon décider : réparer ou retirer).

## 4. Nettoyage & sécurité
- 🎯 Un site encombré et non sécurisé perd la confiance de Google et des visiteurs.
- ✅ Purger les **2 556 commentaires spam** + **désactiver les commentaires** sur biens/pages.
- ✅ **Wordfence** : mettre à jour les règles de pare-feu.
- ✅ Supprimer les **8 thèmes inutilisés** (garder le thème actif + 1 thème de secours par défaut).
- ✅ Choisir **UN SEUL constructeur de page** : **Elementor OU WPBakery** (pas les deux) → désactiver l'autre.
- ✅ Mettre à jour ou remplacer **Slider Revolution** (failles connues sur v5.x).
- ✅ Retirer les extensions redondantes/inutiles.

## 5. Désactivations fonctionnelles
- 🎯 Retirer ce qui n'a pas d'usage et brouille le message.
- ✅ **Désactiver l'inscription publique** (Login/Register en page d'accueil).
- ✅ Retirer les **PDF « collections » (2017-2020)** du menu (les archiver hors navigation).
- ✅ Corriger le pied de page (mention **« Copyright 2021 »** → année dynamique).

## 6. Arborescence & menu (voir `08` §2-3)
- 🎯 Faire apparaître la vraie activité : 3 piliers + l'offre signature.
- ✅ Nouveau menu principal : **Vendre · Louer · Rénover · Que faire de votre bien ? · Nos biens · À propos · Journal · Contact**.
- ✅ **Conserver** `/vendre/` et `/louer/` (existent) ; **créer** `/renover/` et `/que-faire-de-votre-bien/`.
- ✅ Renommer « Articles » → **Journal** ; « About Us » → **À propos**.

## 7. Redirections 301
- 🎯 Ne pas perdre le référencement des anciennes URL.
- ✅ Créer une **redirection 301** pour toute URL supprimée ou modifiée (extension *Redirection*).
- ✅ Vérifier qu'aucun lien interne ne pointe vers une page supprimée.

## 8. Gabarit de fiche bien (WPResidence)
- 🎯 Des fiches homogènes, lisibles et comprises par Google.
- ✅ **Format de titre standardisé** : `Type · X pièces · Y m² · Quartier · Prix` (ex. *Duplex · 3 pièces · 74 m² · Paris 7 Tour-Maubourg · 950 000 €*).
- ✅ Champs **obligatoires** remplis sur chaque bien : statut, prix, surface, pièces, chambres, étage, **DPE**, quartier, ≥ 8 photos, **un seul agent** (« Collection Privée »).
- ✅ Activer les **données structurées** (annonce immobilière) + **Open Graph** (image + titre au partage).
- ✅ Encart « cycle » optionnel (« Rénové puis loué par Collection Privée » → lien vers la page signature).
- ✅ Appliquer le gabarit aux **142 biens** existants + **ajouter Les Lilas & Vaugirard**.

## 9. Recherche & filtres
- 🎯 Un acheteur doit pouvoir filtrer confortablement.
- ✅ Ajouter les filtres **prix · nombre de pièces · arrondissement** à la recherche de biens.

## 10. Référencement & mesure
- 🎯 C'est la seule catégorie qui génère du trafic — et elle est absente aujourd'hui.
- ✅ Installer un **plugin SEO** (RankMath ou Yoast).
- ✅ Remplir **titre + description** de l'accueil et des pages clés ; activer données structurées + Open Graph + sitemap.
- ✅ Installer **Google Search Console + Google Analytics 4** ; soumettre le sitemap.
- ✅ Créer / vérifier la **fiche Google Business Profile** (visibilité locale Paris 7).

## 11. Performance
- 🎯 Un site rapide est mieux classé et convertit mieux (objectif TTFB < 0,6 s).
- ✅ Un seul page builder (cf. §4), réduire scripts/CSS, **lazy-load** des images, mise en **cache** + compression.
- ✅ Refaire un test **PageSpeed Insights** après passage à PHP 8.2.

## 12. Contenus à intégrer *(fournis par Katerina / Claude, pas par le prestataire)*
- Textes réécrits : Accueil, Vendre, Louer, Rénover, **Que faire de votre bien ?** (`07`), À propos.
- **2 études de cas** (17 CDM, rue de la Comète) + photos avant/après (Dropbox).
- Sujets d'articles Journal (déterminés selon l'actualité SEO).

## 13. Recette — « le site est prêt à être montré » quand :
*(règle-frontière anti « on construit sans fin », cf. audit)*
- ✅ PHP 8 + WordPress à jour · **0 spam** · Wordfence à jour.
- ✅ **Titre + description** remplis sur toutes les pages du menu.
- ✅ **Search Console active** + **fiche Google vérifiée**.
- ✅ Nouveau menu en ligne + pages Rénover & « Que faire de votre bien ? » publiées.
- ✅ Gabarit de fiche appliqué au moins aux biens en vitrine.
> Tout le reste (toutes les fiches, pages quartiers, design avancé) se fait **après**, en mesurant.

## 14. Livrables attendus du prestataire
- Site en PHP 8.2, à jour, nettoyé, sécurisé.
- Nouveau menu + pages créées + redirections en place.
- Plugin SEO + Analytics + Search Console configurés.
- Gabarit de fiche opérationnel + données structurées actives.
- Court **compte-rendu** des actions + accès transmis à Katerina.

## 15. Rôles
- **Prestataire (ou Katerina + Claude)** : exécution technique (§2-11).
- **Katerina / Claude** : fourniture des contenus (§12), validation, textes SEO.

## 16. Lots (pour découper si prestataire)
1. **Lot technique** (§2-5) — socle + nettoyage + sécurité.
2. **Lot structure** (§6-9) — menu, pages, redirections, gabarit fiche, filtres.
3. **Lot SEO/mesure** (§10-11) — référencement + performance.
4. **Lot contenu** (§12) — intégration des textes & études de cas.
