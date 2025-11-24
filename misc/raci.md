## 1. À quoi sert une matrice RACI ?

* Éviter les flous du type : « Je pensais que c’était toi qui devais le faire… »
* Réduire les conflits de rôles.
* Clarifier les responsabilités **par tâche** ou **par livrable**.
* Aligner tout le monde sur **qui décide**, **qui exécute**, **qui donne son avis**, **qui est juste tenu au courant**.

On liste :

* en **lignes** : les tâches / activités / livrables,
* en **colonnes** : les rôles / fonctions (Chef de projet, Dev, Client, etc.),
  et on remplit chaque case avec R, A, C ou I.

---

## 2. Signification des lettres R, A, C, I

### R – Responsable (Responsible)

* C’est la personne qui **fait le travail**.
* Il/elle exécute la tâche, produit le livrable.
* Il peut y avoir **plusieurs R** pour une tâche (mais si possible, éviter d’en mettre trop).

Exemple : le développeur qui **code** la fonctionnalité.

---

### A – Accountable (souvent : Autorité / Approbateur)

* C’est la personne qui **porte la responsabilité finale** de la tâche.
* Elle **valide** le résultat, **assume** devant la direction ou le client.
* Il doit y avoir **un seul A par tâche** (règle très importante).

Exemple : le chef de projet qui **valide** que la fonctionnalité répond bien au besoin.

---

### C – Consulté (Consulted)

* Ce sont les personnes **consultées avant ou pendant l’action**.
* Elles donnent des **avis, expertises, retours**, souvent de façon bidirectionnelle (on discute).
* Elles ne décident pas forcément, mais influencent la solution.

Exemple : l’expert sécurité, le Product Owner, l’architecte.

---

### I – Informé (Informed)

* Ce sont ceux qu’on doit simplement **tenir au courant**.
* Pas de décision, pas forcément de travail à faire sur la tâche.
* Communication **unidirectionnelle** : on les informe des décisions / résultats.

Exemple : la direction, l’équipe support, un partenaire.

---

## 3. Exemple très simple de matrice RACI

Imaginons un mini-projet IT :

* Rôles :

  * CP = Chef de projet
  * DEV = Développeur
  * EXP = Expert sécurité
  * DIR = Direction

| Tâche / Activité                        | CP | DEV | EXP | DIR |
| --------------------------------------- | -- | --- | --- | --- |
| 1. Rédiger les spécifications           | A  | R   | C   | I   |
| 2. Développer la fonctionnalité         | C  | R   | C   | I   |
| 3. Valider la conformité sécurité       | C  | R   | A   | I   |
| 4. Go/No-Go mise en production          | A  | R   | C   | I   |
| 5. Communication du lancement au client | R  | I   | I   | A   |

Lecture :

* Pour la tâche 2, **DEV** est R (il code), **CP** et **EXP** sont C (consultés), **DIR** est I (informée).
* Pour la tâche 3, **EXP** est A (responsable final de la conformité sécurité), **DEV** exécute (R).

---

## 4. Comment construire une matrice RACI en pratique

1. **Lister les tâches / activités**

   * Par exemple : étapes d’un projet, activités d’un processus, livrables.

2. **Lister les rôles** (pas forcément les noms)

   * Exemples : Chef de projet, Responsable sécurité, Dev Front, Dev Back, Client, etc.

3. **Remplir le tableau**

   * Pour chaque tâche, affecter R, A, C, I dans les colonnes.

4. Vérifier quelques **règles de cohérence** :

   * Chaque ligne (tâche) doit avoir **exactement un A**.
   * Idéalement **au moins un R** par tâche.
   * Éviter d’avoir :

     * Trop de R sur une même tâche (on ne sait plus qui fait vraiment).
     * Personne en A sur une tâche (personne ne prend la décision finale).
   * Vérifier que **personne n’est A sur tout** (risque de surcharge).

5. **Partager et valider avec l’équipe**

   * La matrice RACI est surtout un outil de **discussion** :
   * “Est-ce que tu es d’accord pour être A sur cette tâche ?”
   * “Est-ce que le client doit être C ou seulement I ici ?”

---

## 5. Ce que RACI améliore dans un projet

* On sait qui **contacter** quand il y a un blocage.
* On réduit les mails “en copie à tout le monde” → on cible les C ou I.
* Les responsabilités sont **justifiées** face au diplôme, à l’ISO 27001, à un jury, etc. (très utile pour tes mémoires et dossiers : tu montres “qui fait quoi” de façon crédible).

