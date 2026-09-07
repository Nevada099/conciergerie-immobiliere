# 🌐 Bilan du site collection-privee.fr — synthèse

*Source : « Bilan complet du site collection-privee.fr » (audit technique, sécurité & SEO, établi le 3 sept. 2026). PDF original reçu par WhatsApp le 15 juil. 2026.*
*Sert de base à la REFONTE du site, dans le cadre de la nouvelle organisation en 3 piliers.*

---

## ⚠️ La décision de positionnement (« Reality Gate » — étape 0 de l'audit)

> **Le site doit-il rester « Collection Privée », ou devenir la vitrine d'un « Private Office for Owners » ?**
> C'est LA décision à trancher avant toute refonte. Si c'est le second, on part directement sur un plan de refonte complet.
> 👉 À décider avec l'agent `offer-strategy` au moment du repackaging.

---

## Le verdict en 5 lignes

1. Le site **fonctionne** mais tourne sur une base technique de 2019 (**PHP 7.1**) — ça bloque déjà des mises à jour.
2. Le site est **invisible pour Google** : pas de plugin SEO, titre d'accueil vide, aucune description, aucun mot-clé.
3. **Impossible de savoir s'il génère du trafic** : ni Google Analytics ni Search Console installés.
4. **Le contenu existe** : 142 biens en ligne + 13 pages + 7 articles. La matière première est là, pas exploitée.
5. Ce qui est payé aujourd'hui (hébergement, thème, extensions) **ne produit aucun trafic**.

## Chiffres clés

| Élément | Constat |
|---|---|
| Biens en ligne | **142 fiches** + 13 pages + 7 articles |
| Zone | Paris 7 / Gros-Caillou (Champ-de-Mars, Tour-Maubourg, Rue Cler, Invalides…) |
| SEO | 0/13 pages avec description · titre d'accueil vide · aucune donnée structurée |
| Technique | PHP 7.1 (fin de vie 2019) · WordPress 6.4.10 · TTFB 1,7 s (objectif < 0,6 s) |
| Sécurité | Wordfence pas à jour depuis janv. 2026 · 2 556 spams en attente |
| Mesure | Aucune (ni Analytics ni Search Console) |
| Atout | Domaine ancien (depuis 2018) — à conserver · HTTPS/sitemap/robots OK |
| Thème | WPResidence (ThemeForest) · doublon Elementor + WPBakery à nettoyer |

## Le plan en 9 étapes (chaque étape dépend de la précédente)

0. **Reality Gate** — décider le positionnement (voir ci-dessus).
1. **Base technique** — sauvegarde → PHP 8.2 (appel OVH au 1007) → MàJ WordPress/extensions/thème.
2. **Nettoyage** — purger les 2 556 spams, MàJ Wordfence, retirer extensions inutiles.
3. **Mesure** — installer Search Console + Analytics + fiche Google Business Profile.
4. **SEO technique** — plugin SEO (RankMath/Yoast), titres + descriptions des 13 pages, données structurées, Open Graph.
5. **Champ sémantique** — 20-30 expressions cibles (quartiers × services), 1 page = 1 intention, pages par quartier.
6. **Fiches biens** — modèle de titre auto (« Appartement 3 pièces 85 m² – Paris 7 Tour-Maubourg – 1 250 000 € ») pour les 142.
7. **Contenu régulier** — 2 articles/mois (réutilisables en vidéo/avatar pour LinkedIn & Instagram).
8. **Autorité** — avis Google, annuaires locaux, liens partenaires (notaires, architectes).

**Règle-frontière (anti « je construis sans fin ») :** le site est « assez bon pour être montré » quand PHP 8 + WordPress à jour + 0 spam + titres/descriptions des 13 pages + Search Console active + fiche Google vérifiée. Le reste vient après, en mesurant.

## ⭐ La 1re action (5 min, gratuite)

Appeler **OVH au 1007** avec l'identifiant client et demander de passer l'hébergement de collection-privee.fr de **PHP 7.1 à PHP 8.2**. Tout le reste en dépend.

---

## 🔗 Lien avec le projet

- Le champ sémantique du site reprend exactement les **3 piliers** : Vendre (Transaction) · Louer (Gestion Locative) · Rénovation → une page par intention.
- Les **7 articles** existants (IFI, taux de crédit, marché Triangle d'Or, Monaco) = base de contenu à optimiser.
- La refonte du site est un **chantier à part** du Dashboard, mais nourri par lui (biens, cas cycle complet, offre).
