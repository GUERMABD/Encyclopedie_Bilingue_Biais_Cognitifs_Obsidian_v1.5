# Encyclopédie bilingue et critique des biais cognitifs — Obsidian

**Version 1.5.1 — README révisé**  
**Dernière mise à jour : 2 août 2026**

Cette base documentaire transforme les listes de biais cognitifs de Wikipédia et le **Cognitive Bias Codex** en une encyclopédie Obsidian structurée, bilingue, critique et navigable.

Elle ne se limite pas à recopier des définitions : chaque concept est replacé dans son contexte scientifique, distingué des heuristiques, sophismes, effets expérimentaux ou principes méthodologiques proches, puis illustré par un exemple concret.

---

## Démarrage rapide

1. Décompresser l’archive dans un **nouveau dossier**.
2. Ouvrir Obsidian.
3. Choisir **Ouvrir un dossier comme coffre**.
4. Sélectionner le dossier de l’encyclopédie.
5. Commencer par :

```text
00 - Navigation/00 - Accueil.md
```

> Ne pas fusionner cette version avec une ancienne extraction. Des fichiers supprimés, renommés ou corrigés pourraient rester présents et provoquer des doublons ou des liens morts.

---

## Contenu de l’encyclopédie

- **265 concepts distincts** après fusion de huit doublons sémantiques vérifiés ;
- **243 concepts** présents dans la liste Wikipédia anglaise contrôlée ;
- **176 concepts distincts** rattachés au Cognitive Bias Codex historique ;
- **265 fiches auditées** avec une analyse critique initiale et des références ;
- **272 notes illustrées** : 265 biais et 7 concepts associés ;
- un exemple pratique et une explication du mécanisme dans chaque fiche ;
- un parcours pédagogique progressif en **9 étapes** ;
- **7 cartes mentales Canvas** ;
- un index alphabétique français–anglais ;
- des tableaux de correspondance CSV et un inventaire JSON ;
- des rapports de contrôle successifs ;
- des scripts de mise à jour et de vérification.

Aucune fiche ne reste marquée comme non auditée dans le périmètre de cette édition.

---

## Trois manières d’utiliser le vault

### Découvrir progressivement

Commencer par :

- [[00 - Navigation/15 - Parcours pédagogique|Parcours pédagogique]]
- [[00 - Navigation/17 - Cartes mentales pédagogiques v1.5|Cartes mentales pédagogiques]]

Le parcours suit une progression allant du fonctionnement général de la cognition vers la mémoire, les probabilités, les décisions, les jugements sociaux et le débiaisement.

### Rechercher un concept précis

Utiliser :

- [[00 - Navigation/02 - Index alphabétique|Index alphabétique]]
- la recherche native d’Obsidian ;
- les liens internes entre les fiches.

### Explorer les classifications

Consulter :

- [[00 - Navigation/03 - Classification actuelle 2026|Classification Wikipédia anglaise contrôlée]]
- [[00 - Navigation/04 - Codex historique|Cognitive Bias Codex historique]]
- [[00 - Navigation/05 - Écart FR-EN|Écart entre les versions française et anglaise]]

---

## Cartes mentales

Les cartes existantes ont été conservées. La version 1.5 ajoute quatre cartes plus synthétiques et pédagogiques.

### Cartes générales et documentaires

- [[02 - Cartes mentales/Vue générale - Classification actuelle.canvas|Vue générale — classification actuelle]]
- [[02 - Cartes mentales/Vue générale - Codex.canvas|Vue générale — Codex historique]]
- [[02 - Cartes mentales/Parcours pédagogique - Découverte progressive.canvas|Parcours pédagogique — découverte progressive]]

### Nouvelles cartes pédagogiques

- [[02 - Cartes mentales/Carte mentale - Fondamentaux des biais cognitifs.canvas|Fondamentaux des biais cognitifs]]
- [[02 - Cartes mentales/Carte mentale - 20 biais du quotidien.canvas|20 biais du quotidien]]
- [[02 - Cartes mentales/Carte mentale - Comment repérer un biais.canvas|Comment repérer un biais ?]]
- [[02 - Cartes mentales/Carte mentale - Débiaisement pratique.canvas|Débiaisement pratique]]

Les cartes générales servent à explorer le corpus. Les nouvelles cartes servent surtout à comprendre, réviser, expliquer ou enseigner les notions principales.

---

## Structure du dossier

```text
00 - Navigation/
    Accueil, méthodologie, index, classifications, parcours et rapports

01 - Fiches/
    Biais/
    Concepts associés/

02 - Cartes mentales/
    Cartes Canvas générales et pédagogiques

03 - Médias/
    Cognitive Bias Codex et médias locaux

04 - Sources et licences/
    Sources principales, versions, attribution et réutilisation

05 - Données/
    Inventaire JSON, statistiques, CSV et rapports automatiques

06 - Modèles/
    Modèles de fiches

07 - Scripts/
    Mise à jour Wikipédia et contrôles du vault

08 - Parcours pédagogique/
    Neuf étapes de découverte progressive
```

---

## Contenu d’une fiche

Une fiche peut contenir :

- le nom français et le nom anglais ;
- les alias et variantes terminologiques ;
- la présence dans Wikipédia et dans le Codex ;
- la nature scientifique du concept ;
- une définition courte en français et en anglais ;
- une explication du mécanisme ;
- un ou plusieurs exemples concrets ;
- les limites et confusions possibles ;
- une appréciation prudente de la robustesse ;
- des méthodes de réduction ou de débiaisement ;
- des références scientifiques ;
- des liens vers les concepts associés.

Exemple de propriétés YAML :

```yaml
---
type: biais-cognitif
nom_fr: "Biais de confirmation"
nom_en: "Confirmation bias"
audit_scientifique: "initial critique avec références"
nature_scientifique: "famille de processus cognitifs"
robustesse: "bien documenté, mais dépendant du contexte et de la méthode"
---
```

---

## Démarche scientifique et critique

La présence d’un terme dans Wikipédia ou dans le Codex constitue une **donnée d’inventaire**, pas une preuve scientifique.

L’encyclopédie distingue notamment :

- les biais cognitifs ;
- les heuristiques ;
- les effets expérimentaux ;
- les phénomènes de mémoire ;
- les biais sociaux ;
- les sophismes ;
- les erreurs statistiques ;
- les principes méthodologiques ;
- les concepts populaires ou insuffisamment stabilisés.

Le statut :

```text
audit_scientifique: initial critique avec références
```

signifie que la fiche a fait l’objet d’une vérification documentaire et bibliographique initiale. Il ne signifie pas qu’une revue systématique exhaustive de toute la littérature a été réalisée pour chaque concept.

Les niveaux de robustesse doivent être lus avec :

- [[00 - Navigation/06 - Légende critique|Légende critique]]
- [[00 - Navigation/01 - Méthodologie, mise à jour et limites|Méthodologie, mise à jour et limites]]

---

## Exemples pratiques

Chaque fiche possède une situation concrète, une anecdote pédagogique, une comparaison ou un scénario permettant de visualiser le mécanisme.

Sauf indication contraire, ces situations sont des **exemples pédagogiques fictifs**. Elles ne constituent pas une preuve scientifique supplémentaire et ne permettent pas de diagnostiquer automatiquement un biais chez une personne réelle.

---

## Mise à jour Wikipédia

Le dossier `07 - Scripts` contient un script de mise à jour destiné à :

- retrouver les pages françaises grâce à Wikidata ;
- récupérer les pages anglaises et françaises disponibles ;
- enregistrer les numéros et dates de révision ;
- importer les médias selon le mode choisi ;
- préserver les analyses critiques déjà rédigées.

Sous Windows, consulter :

```text
07 - Scripts/README.md
```

Puis utiliser, selon le besoin :

```powershell
py mettre_a_jour_wikipedia.py --images none
py mettre_a_jour_wikipedia.py --images lead
py mettre_a_jour_wikipedia.py --images all
```

Le mode `all` peut générer un volume important. Le mode `lead` récupère uniquement l’image principale lorsqu’elle existe.

---

## Contrôles intégrés

Les scripts vérifient notamment :

- la validité des propriétés YAML ;
- les liens internes Obsidian ;
- les fichiers JSON et Canvas ;
- les références de fichiers dans les cartes ;
- les collisions de noms et d’alias ;
- la cohérence entre les fiches, les CSV et l’inventaire JSON ;
- la présence des exemples pratiques ;
- la syntaxe des DOI ;
- l’encodage UTF-8 ;
- les noms de fichiers compatibles avec Windows.

Principaux scripts :

```text
07 - Scripts/controler_integrite.py
07 - Scripts/controler_audit_scientifique.py
07 - Scripts/controler_exemples_pratiques.py
07 - Scripts/controler_encodage_et_liens.py
```

---

## Compatibilité Windows et encodage UTF-8

Cette édition conserve le correctif introduit en version 1.2 pour éviter les noms comme :

```text
v├®rification
M├®dias
├ërosion
```

En cas de caractères déformés :

1. fermer Obsidian ;
2. supprimer ou renommer l’ancienne extraction ;
3. extraire l’archive dans un dossier neuf ;
4. ouvrir uniquement le nouveau dossier comme coffre.

Le fichier suivant contient également les consignes :

```text
LISEZ-MOI - CORRECTIF WINDOWS.txt
```

---

## Sources, licences et réutilisation

Les textes, données et médias peuvent relever de licences différentes.

Consulter avant toute redistribution :

- [[04 - Sources et licences/Sources principales|Sources principales]]
- [[04 - Sources et licences/Versions des sources|Versions des sources]]
- [[04 - Sources et licences/Licence et réutilisation|Licence et réutilisation]]
- [[04 - Sources et licences/Attribution - Cognitive Bias Codex|Attribution du Cognitive Bias Codex]]

Les médias Wikimedia doivent être vérifiés individuellement : la licence d’un article Wikipédia ne s’applique pas automatiquement à toutes les images qu’il contient.

---

## Vérification de l’archive avec SHA-256

L’empreinte SHA-256 permet de vérifier que l’archive téléchargée n’a pas été modifiée ou endommagée.

Sous PowerShell :

```powershell
Get-FileHash "CHEMIN_COMPLET_DU_FICHIER.zip" -Algorithm SHA256
```

Comparer ensuite le résultat avec le fichier `.sha256` fourni avec l’archive.

Cette vérification est facultative pour utiliser le vault dans Obsidian.

---

## Historique synthétique

- **v1.0** : audit initial des 265 concepts terminé ;
- **v1.1** : exemples pratiques ajoutés et contrôlés ;
- **v1.2** : correctif Windows UTF-8 et liens ;
- **v1.3** : ergonomie des cartes et parcours pédagogique ;
- **v1.5** : quatre nouvelles cartes mentales pédagogiques ;
- **v1.5.1** : réécriture complète du README.

Les anciennes versions ne sont pas nécessaires. La version la plus récente contient les corrections et fonctionnalités précédentes.

---

## Point d’entrée recommandé

```text
00 - Navigation/00 - Accueil.md
```

Pour une première découverte :

```text
00 - Navigation/15 - Parcours pédagogique.md
```

Pour les cartes visuelles :

```text
00 - Navigation/17 - Cartes mentales pédagogiques v1.5.md
```
