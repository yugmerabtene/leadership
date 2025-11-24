# **JOUR 1 — LEADERSHIP & GOUVERNANCE D’ÉQUIPE IA**

*Mastère Data & Intelligence Artificielle — RNCP37137*
*Objectifs C4.4 et C4.5 — Document officiel Nexa School* 
Durée : 3h30 le matin + 3h30 l’après-midi (7h)

---

# **INTRODUCTION GÉNÉRALE AU MODULE**

## **1.1. Pourquoi un module Leadership dans un Mastère IA ?**

L’IA transforme les organisations, mais aucun projet IA ne réussit uniquement grâce à la technique.
Les échecs en entreprise sont majoritairement liés à :

* des **problèmes humains**,
* une **vision floue**,
* des **conflits internes**,
* une **communication insuffisante**,
* un rôle mal défini entre PO, Data Scientist, Data Engineer, DevOps, QA, Métier.

Ce cours a pour ambition de professionnaliser les futurs chefs de projet IA en leur apportant :

* des modèles de leadership appliqués au numérique,
* une compréhension fine de la dynamique humaine en équipe technique,
* des méthodes d’organisation (RACI),
* des stratégies de communication adaptées,
* et des outils concrets pour gérer les situations réelles rencontrées en entreprise.

## **1.2. Objectifs pédagogiques du Jour 1**

Conformément au dossier RNCP :

* **C4.4** – Manager l’équipe IA, répartir les rôles, définir les objectifs, s’adapter aux charges, intégrer les PSH.
* **C4.5** – Engager l’équipe, ajuster la communication, traiter les écarts, anticiper les risques humains.

---

# **PARTIE 1 — COMPRENDRE LE LEADERSHIP EN ÉQUIPE TECHNIQUE (3h30)**

---

# **2. Le leadership : définitions, enjeux, périmètre**

### **2.1. Leadership vs Management vs Expertise**

| Concept                   | Définition                                     | Impact projet IA                           |
| ------------------------- | ---------------------------------------------- | ------------------------------------------ |
| **Leadership**            | Influence, inspiration, vision, accompagnement | Donne du sens, crée l’adhésion             |
| **Management**            | Organisation, ressources, suivi, planification | Structure le travail, évite le chaos       |
| **Autorité hiérarchique** | Pouvoir formel lié au poste                    | Peut imposer mais pas engager              |
| **Expertise technique**   | Maîtrise d’un domaine                          | Renforce la crédibilité mais ne suffit pas |

Le **chef de projet IA** doit maîtriser les quatre simultanément, dans des proportions adaptées à l’équipe.

---

# **3. Les modèles de leadership (Lewin, Blanchard, Hersey)**

## **3.1. Les trois styles de leadership de Kurt Lewin**

**1. Autoritaire (Directif)**

* Décisions rapides, peu de consultation
* Adapté : crise, risques majeurs, deadlines
* Inconvénients : résistance, démotivation

**2. Participatif**

* Décisions partagées, co-construction
* Adapté : projets IA nécessitant créativité
* Avantage : engagement, innovation

**3. Délégatif**

* Autonomie très forte
* Adapté : experts seniors (DS/DE)
* Risque : perte de cohérence si absence de vision claire

## **3.2. Leadership situationnel (Hersey & Blanchard)**

L’efficacité dépend de la capacité à **adapter son style au niveau de maturité du collaborateur**.

Niveaux de maturité des profils IA :

* M1 : Junior motivé mais peu compétent
* M2 : Intermédiaire compétent mais instable
* M3 : Confirmé autonome mais peu confiant
* M4 : Senior autonome et stable

Correspondance :

* M1 → Directif
* M2 → Persuasif
* M3 → Participatif
* M4 → Délégatif

## **3.3. Application au monde IA**

Exemple :

* Un Data Engineer junior → leadership directif : cadrage strict, processus CI/CD, guides techniques.
* Un Data Scientist senior → leadership délégatif avec vision stratégique.
* Une QA expérimentée → participatif, car expertise en qualité logicielle.
* Un PO peu technique mais très métier → leadership persuasif pour aligner technique/métier.

---

# **4. Les dynamiques humaines en équipe IA**

## **4.1. Les phases d’évolution de l’équipe (Tuckman revisité)**

1. **Forming** – décollage
2. **Storming** – confrontations : essentiels dans les projets IA
3. **Norming** – harmonisation des pratiques
4. **Performing** – équipe autonome, vélocité stable
5. **Rebond** – adaptation à un nouvel enjeu IA

## **4.2. Biais cognitifs fréquents en environnement IA**

* **Biais d’expertise** : “ma solution est forcément la meilleure”
* **Biais du survivant** : “cela a toujours marché comme ça”
* **Biais d’autorité** : influence excessive du senior
* **Biais technique** : sur-optimisation non pertinente
* **Biais de complexité** : rendre technique ce qui devrait rester simple
* **Biais data-centric** : focalisation trop forte sur la performance modèle et oubli du besoin métier

Le rôle du chef de projet IA : **identifier, neutraliser, recadrer**.

---

# **PARTIE 2 — ORGANISATION : DÉFINIR LES RÔLES AVEC LA RACI**

---

# **5. La matrice RACI : outil central du management IA**

## **5.1. Pourquoi une RACI ?**

Parce que les équipes IA sont multidisciplinaires et que les frontières sont floues :

* Qui valide un modèle ?
* Qui prépare les données ?
* Qui décide de la mise en production ?
* Qui est responsable de la conformité RGPD ?

Sans RACI : conflits, lenteur, zones d’ombre.

## **5.2. Structure de la RACI**

* **R – Responsible** : exécute
* **A – Accountable** : responsable final
* **C – Consulted** : expert
* **I – Informed** : tenu informé

## **5.3. Exemple complet pour un projet IA**

Tâche : Création d’un modèle de prédiction en assurance

| Tâche                | R                 | A                 | C      | I         |
| -------------------- | ----------------- | ----------------- | ------ | --------- |
| Définition du besoin | PO                | Chef de projet IA | Métier | Direction |
| Collecte des données | Data Engineer     | Chef de projet IA | DPO    | PO        |
| Construction modèle  | Data Scientist    | Chef de projet IA | DE     | QA        |
| MEP (CI/CD)          | DevOps            | Chef de projet IA | DS     | Direction |
| Documentation        | Chef de projet IA | Direction         | QA     | DPO       |

---

# **PARTIE 3 — ADAPTER SON LEADERSHIP À LA DIVERSITÉ**

---

# **6. Intégration du handicap et inclusion**

## **6.1. Pourquoi c’est essentiel ?**

* Obligation légale
* Protection humaine
* Performance collective
* Conformité aux objectifs pédagogiques C4.4 et C4.5

## **6.2. Exemples d’adaptation**

* Troubles dys → supports visuels structurés
* Surdité → privilégier l’écrit et la documentation
* TDAH → fractionner les tâches
* Troubles moteurs → outils adaptés

---

# **PARTIE 4 — COMMUNIQUER UNE VISION CLAIRE ET INSPIRANTE (3h30)**

---

# **7. Comment formuler une vision de projet IA**

Une vision efficace répond à 4 questions :

1. Où allons-nous ?
2. Pourquoi cela compte ?
3. Comment allons-nous avancer ensemble ?
4. Comment mesurer la réussite ?

## **7.1. Caractéristiques d’une vision IA**

* Accessible non-tech
* Connectée au business
* Mesurable
* Inclusive
* Mobilisatrice

---

# **8. Les techniques de storytelling pour les chefs de projet IA**

## **8.1. Structure du storytelling**

1. Situation actuelle
2. Problème à résoudre
3. Transformation souhaitée
4. Contribution des équipes

## **8.2. Exemple appliqué**

« Aujourd’hui, nos analystes passent 60 % de leur temps à vérifier manuellement des documents.
Notre modèle IA permettra de réduire ce temps à moins de 10 %, tout en améliorant la précision et en permettant aux équipes de se concentrer sur les tâches à forte valeur ajoutée.
Votre rôle dans cette transformation est essentiel. »

---

# **9. Communication inclusive et engageante**

## **9.1. Principes clés**

* Reformulation
* Transparence
* Sécurité psychologique
* Canaux multiples
* Adaptation aux profils

## **9.2. Gestion de désaccords**

Outils :

* écoute active,
* questionnement ouvert,
* arbitrage structuré,
* analyse d’impact.

---

# **PARTIE 5 — TRAVAUX PRATIQUES ET ÉTUDES DE CAS**

---

# **TP1 — Construction d'une RACI réelle**

Projet : pipeline IA de détection d’anomalies
Livrable : RACI complète, justification de chaque rôle

# **TP2 — Choisir le bon style de leadership**

Études de cas :

* Conflit Data Scientist / DevOps
* PO qui change les specs en cours de sprint
* Data Engineer surchargé

# **TP3 — Créer un storytelling inspirant**

Objectif : écrire un pitch de vision orienté IA, structuré, puissant.

