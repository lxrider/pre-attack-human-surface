# Exercice 01 — Jeu de données fictives

[← Accueil](../README.md) · [Fiche à remplir](fiche-analyse-fr.md) · [Correction commentée](exemple-revue-fr.md)

**Périmètre :** scénario construit de toutes pièces. L'organisation « Atelier Boréal », les personnes, les publications et les documents cités ci-dessous n'existent **que dans cet exercice**. Aucun appel réseau ni recherche de personnes réelles n'est nécessaire.

## Mission

Vous réalisez une évaluation défensive de l'exposition informationnelle d'une organisation fictive. Vous devez déterminer si les informations présentées facilitent **potentiellement** une demande de modification d'accès et quels contrôles empêcheraient qu'une telle demande soit acceptée sur la seule base du contexte public.

**Valeur à protéger :** comptes privilégiés et intégrité des processus de récupération d'accès.  
**Objectif adverse envisagé :** obtenir qu'une modification d'accès soit acceptée sans vérification appropriée.  
**Limite :** il n'existe dans ce jeu aucune preuve d'une tentative réelle ni de droits effectifs.

## Dossier synthétique

Les cinq pièces ci-dessous constituent l'intégralité des éléments accessibles à l'analyste. Il n'y a **pas de source en ligne** à rechercher.

| Pièce | Extrait fictif fourni | Statut de la pièce | Limite explicite |
| --- | --- | --- | --- |
| **OBS-01** | « Lina Martin — intervention : gouvernance IAM », programme public d'un colloque à date J+14 | Contenu **OBSERVÉ dans la simulation** | Une intervention ne prouve pas des droits techniques |
| **OBS-02** | « Lina Martin — coordination de projets IAM, Atelier Boréal », bio professionnelle publique | Contenu **OBSERVÉ dans la simulation** | Un intitulé peut différer du rôle effectif |
| **OBS-03** | « Présente au colloque le mois prochain », publication professionnelle fictive | Contenu **OBSERVÉ dans la simulation** | La présence future reste incertaine |
| **OBS-04** | Une page publique de l'organisation mentionne un « portail d'assistance aux comptes » | Contenu **OBSERVÉ dans la simulation** | Ni le fonctionnement ni les contrôles du portail ne sont décrits |
| **DOC-01** | Extrait d'une *procédure interne fictive* : « Toute demande de récupération d'accès requiert une vérification indépendante et une approbation distincte » | Contrôle **DOCUMENTÉ dans la simulation** | La bonne application de la procédure n'est **pas démontrée** |

**Attention :** « OBSERVÉ » signifie uniquement *visible dans une pièce fournie pour l'exercice*. Aucun de ces éléments ne constitue une observation sur une organisation réelle.

## Travail demandé

1. Reformulez l'objectif adverse et l'**effet métier redouté** sans inventer de scénario d'intrusion technique.
2. Relevez les faits qui permettent réellement une corrélation. Distinguez ceux qui sont **recopiés** de ceux qui sont **indépendants**.
3. Formulez **trois hypothèses concurrentes** sur l'intérêt des informations publiques et les contrôles internes.
4. Identifiez précisément la frontière entre **connaissance publique** et **décision interne**.
5. Proposez **deux mesures** : une sur l'exposition et une sur la validation des demandes.
6. Définissez ce qu'il faudrait **vérifier dans un cadre autorisé** avant de prétendre que le risque est réduit.

Utilisez la [fiche d'analyse](fiche-analyse-fr.md), puis comparez votre résultat à la [correction](exemple-revue-fr.md).

## Ce qu'il ne faut pas conclure

- Que Lina dispose effectivement de privilèges administratifs.
- Qu'un processus d'assistance est vulnérable parce qu'il est mentionné publiquement.
- Que la procédure DOC-01 est toujours appliquée.
- Que la publication OBS-03 confirme un déplacement effectif.
- Qu'une attaque s'est produite ou serait susceptible de réussir.

**Aucun test actif, contact humain, collecte externe ou outil offensif n'est nécessaire pour terminer cet exercice.**
