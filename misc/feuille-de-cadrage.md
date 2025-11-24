# **FEUILLE DE CADRAGE – CHEF DE PROJET INFORMATIQUE**

**Version :** 1.0
**Date :** [à compléter]
**Chef de projet :** [Nom, Prénom]
**Projet :** [Nom du projet]
**Client / Commanditaire :** [Nom de l’entreprise, direction, ou service]
**Durée estimée :** [XX semaines / mois]
**Date de début :** [JJ/MM/AAAA]
**Date de fin prévisionnelle :** [JJ/MM/AAAA]

---

## **1. CONTEXTE DU PROJET**

Présentez brièvement :

* Le **problème métier ou technique** à résoudre.
* Les **enjeux** pour le client / l’entreprise.
* Le **contexte existant** (infrastructure, outils, processus).
* Les **opportunités ou contraintes** (ex. conformité ISO 27001, RGPD, budget, délais).

> *Exemple :*
> Le service comptabilité souhaite automatiser le traitement des factures électroniques en conformité avec la réforme 2026. Le projet vise à développer une application SaaS connectée aux API de la DGFiP et PEPPOL, avec un espace client sécurisé.

---

## **2. OBJECTIFS DU PROJET**

### **Objectif général**

Décrire la finalité principale du projet.

> *Exemple :* Créer une application web sécurisée permettant la facturation électronique et le suivi des paiements clients.

### **Objectifs spécifiques**

* [ ] Automatiser l’émission et la réception des factures.
* [ ] Intégrer les API gouvernementales (PDP, PPF, etc.).
* [ ] Mettre en place un tableau de bord d’indicateurs (KPI, MTTR, disponibilité).
* [ ] Respecter les normes ISO/IEC 27001, RGPD, OWASP.

---

## **3. PÉRIMÈTRE DU PROJET**

### **Inclus dans le projet**

Liste des livrables ou fonctionnalités prévues :

* Application web et API backend.
* Base de données MySQL sécurisée.
* Authentification (JWT, 2FA).
* Tableau de bord utilisateur.
* Documentation technique + utilisateur.

### **Hors périmètre**

Liste explicite de ce qui **ne sera pas** réalisé :

* Application mobile.
* Support multilingue.
* Interconnexion avec ERP externe.

---

## **4. PARTIES PRENANTES**

| **Rôle**                    | **Nom / Service**       | **Responsabilités principales**   |
| --------------------------- | ----------------------- | --------------------------------- |
| Commanditaire               | [Nom, poste]            | Validation globale du projet      |
| Chef de projet informatique | [Nom]                   | Pilotage, planification, suivi    |
| Équipe technique            | [Noms des développeurs] | Développement, tests              |
| Utilisateurs finaux         | [Service, profil]       | Tests et validation fonctionnelle |
| RSSI / DPO (si applicable)  | [Nom]                   | Conformité sécurité et RGPD       |

---

## **5. LIVRABLES ATTENDUS**

| **Livrable**                  | **Description**             | **Responsable** | **Date prévue** |
| ----------------------------- | --------------------------- | --------------- | --------------- |
| Spécifications fonctionnelles | Cahier des charges complet  | Chef de projet  | Semaine 2       |
| Prototype / Maquette          | Interface graphique validée | UX/UI designer  | Semaine 3       |
| Version Alpha                 | Fonctionnalités principales | Développeurs    | Semaine 6       |
| Version Beta                  | Tests utilisateurs          | QA / Testeurs   | Semaine 8       |
| Version finale                | Livraison en production     | Chef de projet  | Semaine 10      |
| Documentation technique       | Architecture, sécurité, API | Développeurs    | Semaine 10      |

---

## **6. ORGANISATION DU PROJET**

### **Méthodologie**

* Type de gestion : Agile (Scrum / Kanban) ou Cycle en V
* Outils de gestion : Jira / Trello / GitLab / Notion
* Communication : réunions hebdomadaires, compte-rendus de sprint, reporting KPI

### **Rôles et responsabilités (RACI simplifié)**

| **Tâche**           | **Responsable (R)**   | **Approbateur (A)** | **Consulté (C)** | **Informé (I)** |
| ------------------- | --------------------- | ------------------- | ---------------- | --------------- |
| Analyse des besoins | Chef de projet        | Client              | Équipe technique | DSI             |
| Développement       | Développeur principal | Chef de projet      | QA               | Client          |
| Tests et validation | QA / Testeur          | Chef de projet      | Client           | Équipe          |
| Déploiement         | DevOps                | Chef de projet      | RSSI             | Client          |

---

## **7. CONTRAINTES ET RISQUES**

### **Contraintes**

* Délai maximal : [date butoir]
* Budget limité à : [montant en €]
* Sécurité : conformité ISO/IEC 27001 & RGPD
* Environnement technique imposé : [ex. Java Spring Boot, React.js, MySQL]

### **Risques identifiés**

| **Risque**                          | **Impact** | **Probabilité** | **Plan d’action / mitigation**                  |
| ----------------------------------- | ---------- | --------------- | ----------------------------------------------- |
| Retard sur le développement backend | Élevé      | Moyenne         | Recrutement d’un stagiaire / plan de rattrapage |
| Non-conformité sécurité             | Critique   | Faible          | Audit interne, tests OWASP                      |
| Manque de documentation             | Moyen      | Élevée          | Template documentaire imposé                    |

---

## **8. PLANIFICATION (SYNTHÈSE)**

| **Phase**             | **Durée** | **Objectif**                | **Livrable clé**      |
| --------------------- | --------- | --------------------------- | --------------------- |
| Analyse & cadrage     | S1-S2     | Définir besoins & périmètre | Cahier des charges    |
| Conception            | S3-S4     | Architecture, maquettes     | Dossier de conception |
| Développement         | S5-S8     | Réalisation technique       | Version Alpha / Beta  |
| Tests & validation    | S9        | Vérification qualité        | Rapport de test       |
| Déploiement & clôture | S10       | Mise en production          | PV de recette finale  |

---

## **9. INDICATEURS DE SUIVI (KPI)**

| **Indicateur**               | **Objectif cible** | **Fréquence de mesure** |
| ---------------------------- | ------------------ | ----------------------- |
| Respect du planning          | ±10 %              | Hebdomadaire            |
| Taux de couverture des tests | ≥ 80 %             | À chaque sprint         |
| Disponibilité du service     | ≥ 99,5 %           | Mensuel                 |
| Satisfaction utilisateur     | ≥ 8/10             | Fin de projet           |

---

## **10. VALIDATION DE LA FEUILLE DE CADRAGE**

| **Nom**                 | **Fonction**       | **Date**     | **Signature** |
| ----------------------- | ------------------ | ------------ | ------------- |
| [Nom du chef de projet] | Chef de projet     | [JJ/MM/AAAA] |               |
| [Nom du commanditaire]  | Client / Direction | [JJ/MM/AAAA] |               |

---

## **Annexes**

* Schéma d’architecture (si disponible)
* Diagramme Gantt (si applicable)
* RACI complet
* Documents de référence (ISO, RGPD, cahier des charges initial)
(ex. Nexa School / Clairfact),
4. Et si tu veux la version **Cycle en V** ou **Agile (Scrum)**.
