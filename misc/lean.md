## 1. C’est quoi le Lean ? (version simple)

Le Lean, à la base (Toyota), c’est une manière d’organiser le travail pour :

* **Maximiser la valeur pour le “client”** (au sens large : client final, utilisateur, direction, etc.)
* **Minimiser les gaspillages** (tout ce qui consomme du temps, de l’énergie, de l’argent sans apporter de vraie valeur).

En une phrase :

> Lean = faire **mieux**, **plus vite** et **plus simple**, avec **moins de gaspillage**.

On ne commence pas par “travailler plus”, on commence par **enlever ce qui ne sert à rien**.

---

## 2. Les 5 grands principes du Lean

Référence classique (Womack & Jones) :

1. **Définir la valeur**

   * Qu’est-ce qui a vraiment de la valeur pour le client ?
   * Exemple IT : “Une fonctionnalité livrée, stable et utile” = valeur.
   * Une réunion de 3h avec 10 personnes sans décision = peu de valeur.

2. **Cartographier le flux de valeur (Value Stream)**

   * On dessine le chemin complet d’un “produit” ou d’un “service” :
     idée → spécifications → dev → tests → mise en prod → support.
   * Objectif : voir où ça bloque, où ça attend, où ça double le travail.

3. **Créer le flux (Flow)**

   * On essaie de faire en sorte que le travail **circule sans interruption**.
   * Moins de files d’attente, moins de “en attente de validation”, moins de re-travail.

4. **Passer en flux tiré (Pull)**

   * On produit **à la demande**, pas pour stocker.
   * En IT : ne pas lancer 15 développements en parallèle alors que l’équipe de test ne peut en traiter que 3.

5. **Tendre vers la perfection (Kaizen)**

   * On améliore **en continu**, par petits pas.
   * Pas besoin de révolutionner tout : on corrige chaque semaine un point concret.

---

## 3. Les gaspillages (le cœur du Lean)

Lean parle de **“muda”** = gaspillage.
Classiquement, on compte **8 types de gaspillages**, que tu peux adapter à l’IT :

1. **Surproduction**

   * Faire plus que nécessaire, trop tôt.
   * Exemple : développer des fonctionnalités que personne n’utilise.

2. **Attente**

   * Temps perdu à attendre une validation, une info, un environnement, un accès.

3. **Transports inutiles**

   * Déplacements inutiles d’objets, de dossiers, OU d’informations.
   * Exemple : 6 outils différents pour suivre un ticket.

4. **Sur-processus**

   * Faire plus compliqué que nécessaire.
   * Exemple : 4 niveaux de validation pour une petite modification sans impact critique.

5. **Stocks / en-cours inutiles**

   * Trop de tâches en parallèle, backlog monstrueux, tickets jamais traités.

6. **Mouvements inutiles**

   * Multiplication des clics, navigation compliquée, manque d’automatisation.

7. **Défauts / re-travail**

   * Bugs, corrections, retours utilisateurs faute d’analyse correcte.

8. **Non-utilisation des talents**

   * Ne pas utiliser les compétences des gens :
     développeur qui ne donne jamais son avis sur l’architecture, etc.

---

## 4. Méthodologie de mise en œuvre (comment on applique Lean)

### Étape 1 – Choisir un processus précis

Ne pas “faire du Lean partout” d’un coup.
Choisir un **processus concret** :

* Par exemple : traitement d’un ticket support, déploiement en production, onboarding d’un nouveau client, etc.

### Étape 2 – Cartographier le processus actuel

* On liste les étapes **telles qu’elles sont vraiment**, pas “comme sur le PowerPoint”.
* Exemple pour un ticket support :

  1. Réception du mail du client
  2. Création du ticket dans l’outil
  3. Affectation à un technicien
  4. Analyse
  5. Résolution
  6. Retour client
  7. Clôture

Pour chaque étape, on peut noter :

* Temps moyen
* Attentes (file d’attente, validations)
* Qui intervient

### Étape 3 – Identifier les gaspillages

Sur chaque étape, on demande :

* Où est-ce qu’on attend ?
* Où est-ce qu’on refait deux fois la même chose ?
* Où est-ce que c’est compliqué pour rien ?
* Où est-ce qu’il y a beaucoup d’erreurs ?

On repère et on classe les “muda”.

### Étape 4 – Proposer des améliorations simples (Kaizen)

On choisit **quelques actions simples**, rapides à mettre en place :

* Regrouper des validations inutiles.
* Automatiser une étape (script, modèle d’email, template).
* Supprimer un doublon d’outils.
* Clarifier “qui fait quoi” (lien naturel avec RACI).

Important : on ne cherche pas “LA solution parfaite”, on cherche **un premier progrès**.

### Étape 5 – Tester et mesurer

On applique l’amélioration sur une période courte (par exemple 1 semaine, 2 semaines).

* Avant : temps moyen de traitement = 5 jours.
* Après : 3 jours ? 4 jours ? Plus ?
  On mesure pour voir si ça marche.

C’est le cycle PDCA classique :

* **P**lan : analyser, définir l’action
* **D**o : mettre en œuvre
* **C**heck : mesurer
* **A**ct : standardiser ou corriger

### Étape 6 – Standardiser

Si l’amélioration fonctionne :

* On la **formalise** : procédure, check-list, modèle de document, automatisation.
* On forme les personnes concernées.

Et on recommence sur un autre point : c’est une amélioration **continue**, pas un “one shot”.

---

## 5. Travaux pratiques (TP) Lean – Version “cours” utilisable

Je te propose 2 TPs structurés comme tu aimes (objectifs, consignes, livrables).

---

### TP1 – Identifier les gaspillages dans un processus simple

**Objectif pédagogique :**

* Comprendre les notions de “valeur” et de “gaspillage”.
* Savoir lire un processus et repérer les 8 mudas.

**Durée :** 1h à 1h30 (en groupe de 3–4).

**Sujet :**

> On s’intéresse au processus suivant :
> “Traitement d’une demande d’accès VPN pour un nouvel employé dans une PME”.

**Étapes données aux étudiants (tu les fournis) :**

1. Le manager envoie un mail à l’IT pour demander un accès VPN.
2. Le service RH envoie séparément un mail à l’IT pour déclarer l’arrivée du salarié.
3. Le technicien IT crée le compte AD.
4. Le technicien IT crée le compte VPN.
5. Le technicien IT envoie un mail avec les identifiants au manager.
6. Le manager transmet le mail au salarié.
7. Le salarié teste l’accès, ça ne fonctionne pas, il renvoie un mail au manager.
8. Le manager renvoie un mail à l’IT.
9. Le technicien corrige la configuration VPN.
10. Le salarié teste à nouveau, ça fonctionne.

**Consignes :**

1. Représenter ce processus sous forme de **schéma simple** (liste numérotée ou boîte → flèche).
2. Pour chaque étape, indiquer :

   * Est-ce que cette étape **ajoute de la valeur** pour le salarié ou l’entreprise ? (OUI/NON)
   * Quel type de gaspillage est présent (s’il y en a) : surproduction, attente, transport, etc.
3. Proposer au moins **3 améliorations Lean** :

   * Par exemple : formulaire unique RH + manager, envoi direct au salarié, template automatique, etc.

**Livrables :**

* Une **carte du processus** (papier ou fichier).
* Un **tableau** avec : Étape / Valeur ou non / Type de muda / Idées d’amélioration.
* Une **courte synthèse** (5–10 lignes) :
  “Ce que nous avons compris sur Lean et les gaspillages”.

---

### TP2 – Mini Kaizen + standardisation

**Objectif pédagogique :**

* Mettre en pratique le cycle PDCA.
* Apprendre à formaliser une amélioration en “nouveau standard”.

**Durée :** 1h30 à 2h.

**Sujet :**

> Vous choisissez un **processus réel de votre vie d’étudiant ou de votre travail** :
>
> * préparation d’un cours,
> * réponse à des mails,
> * rendu de projets,
> * installation d’un poste pour un nouveau stagiaire, etc.

**Consignes :**

1. **Plan (P)**

   * Décrire le processus actuel en 5–10 étapes.
   * Identifier au moins **2 gaspillages** (type Lean).
   * Choisir **UNE** amélioration simple, réaliste, à tester tout de suite.
2. **Do (D)**

   * Imaginer concrètement comment cette amélioration serait appliquée
     (exemple : modèle d’email, checklist, script, raccourci, regroupement de tâches…).
3. **Check (C)**

   * Définir **un indicateur simple** pour vérifier l’amélioration :
     temps gagné, nombre d’erreurs, nombre d’allers-retours, etc.
   * Faire une simulation (sur un cas fictif ou réel) et estimer l’impact.
4. **Act (A)**

   * Écrire le **“nouveau standard”** :

     * une mini-procédure de 5–10 lignes,
     * ou une check-list,
     * ou un template (mail, ticket, script).

**Livrables :**

* Description “avant/après”.
* Indicateur choisi et estimation de l’amélioration.
* Nouveau standard (document simple).
