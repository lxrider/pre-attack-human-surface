# Démarche OSINT défensive

**Objectif :** établir si une exposition publique facilite réellement un chemin de compromission plausible, puis déterminer un traitement proportionné. Cette démarche est une **aide à la décision**, pas un guide de collecte exhaustive.

## 1. Partir de la valeur

Définir l’actif, le processus ou la décision à protéger : compte à privilèges, validation d’une opération financière, continuité de service, capacité d’administration ou informations sensibles. Préciser l’effet redouté : fraude, usurpation, accès non autorisé ou perturbation opérationnelle.

**Question :** que chercherait à obtenir un adversaire, et quel dommage pourrait en résulter ?

## 2. Formuler un objectif adverse

Décrire une intention plausible **sans la confondre avec un fait**. Exemple : « Une personne pourrait tenter de se faire passer pour un collaborateur afin d’obtenir une modification d’accès. » Il ne s’agit pas de conclure qu’une telle tentative existe.

Préciser le mécanisme supposé de manière générale, puis la condition qui devrait être remplie pour qu'il produise un effet.

## 3. Relever les faits strictement nécessaires

Examiner uniquement les sources publiques ou explicitement autorisées utiles à l’objectif : page institutionnelle, programme d’événement, profil professionnel, dépôt public ou document diffusé volontairement. Éviter de conserver une copie nominative si une référence assainie suffit.

Pour chaque observation, noter :

| Champ | Exemple fictif |
| --- | --- |
| Référence | OBS-01 |
| Fait observé | Un programme public mentionne un intervenant et son domaine d’expertise |
| Catégorie | Identité / responsabilité |
| Source et date | Référence de démonstration / date de consultation |
| Statut | **OBSERVÉ** |
| Limite | Ne démontre aucun droit technique ni aucun accès effectif |

Une réponse produite par une IA peut proposer une piste, mais **ne constitue pas une preuve**. Toute affirmation utile doit être rattachée à une source primaire ou à une source documentaire identifiée.

## 4. Corréler et tester les hypothèses

Rapprocher uniquement les faits pertinents. Une corrélation peut révéler un rôle, un contexte organisationnel ou une période d’absence ; elle ne suffit jamais à démontrer une vulnérabilité exploitable.

Appliquer une lecture contradictoire :

- **H1 :** les informations publiques augmentent la crédibilité d’un scénario d’usurpation.
- **H2 :** ces informations ne créent aucun avantage opérationnel mesurable, car le contrôle d’identité est indépendant du contexte présenté.
- **H3 :** la principale exposition se situe ailleurs, dans un processus ou une délégation d’autorité non documenté.

Associer à chaque hypothèse les faits qui la soutiennent, ceux qui la contredisent et les **inconnues**.

## 5. Identifier la frontière de confiance

La question décisive n’est pas « Que sait-on sur une personne ? », mais **« Quelle décision sensible pourrait être influencée, et quel contrôle empêcherait l’information publique d’être utilisée comme preuve d’identité ou d’autorité ? »**

Distinguer :

| Notion | Exemple de question |
| --- | --- |
| Identité | Qui la source publique désigne-t-elle ? |
| Fonction déclarée | Quel rôle est publiquement présenté ? |
| Permission effective | Quel droit technique existe réellement ? **Inconnu sans preuve** |
| Autorité reconnue | Qui peut approuver une opération ? Selon quel processus ? |
| Frontière de confiance | À quel moment une information extérieure devient-elle une décision interne ? |

## 6. Choisir une mesure proportionnée

Réduire l’exposition lorsqu’elle est inutile ; limiter la précision, différer une information temporelle ou cloisonner des contextes lorsqu’une justification existe. Surtout, renforcer les procédures qui pourraient confondre **connaissance d’un contexte** et **preuve d’identité**.

Il peut être légitime de conserver une information publique qui apporte une valeur professionnelle. La visibilité n’est pas un défaut en soi.

## 7. Vérifier le résultat

Comparer la situation avant et après selon des critères explicites :

| Question de vérification | Résultat à documenter |
| --- | --- |
| L’information inutile est-elle encore visible ? | Oui / Non / Inconnu, avec date et périmètre |
| La corrélation reste-t-elle possible ? | Démontrée / Partiellement réduite / Non évaluée |
| Une procédure sensible accepte-t-elle des informations publiques comme preuve ? | Conformité à la procédure, **uniquement par une revue autorisée** |
| L’hypothèse d’impact reste-t-elle plausible ? | Argumentée, contredite ou toujours inconnue |

La disparition d’une donnée d’une page ne prouve pas sa disparition des archives, des index ou de sources tierces. **Ne pas annoncer une réduction du risque démontrée si seule une mesure a été engagée.**

## Périmètre

L’OSINT utilise ici des informations ouvertes ou autorisées. La compromission de comptes, la surveillance physique, l’usurpation et la collecte intrusive sont hors du laboratoire. L’existence d’une information dans une base issue d’une violation de données ne constitue pas une autorisation de l’exploiter.

[← Retour à la présentation](../README.md) · [Exercice fictif](../examples/exemple-revue-fr.md)
