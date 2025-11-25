## 1. Le modèle de Lewin : 3 styles de base

Kurt Lewin distingue 3 grands styles de leadership, en observant comment un chef influence son équipe :

1. **Autoritaire (autocratique)**
2. **Démocratique (participatif)**
3. **Laisser-faire**

### 1.1. Style autoritaire

**Principe :**
Le leader décide seul, donne des ordres détaillés, contrôle fortement, peu (ou pas) de consultation de l’équipe.

**Caractéristiques :**

* Décision centrale : le chef prend toutes les décisions.
* Communication descendante : « voilà ce qu’il faut faire, comment et pour quand ».
* Contrôle serré : suivi régulier, peu de marge de manœuvre.
* Peu d’écoute des avis, peu de co-construction.

**Avantages :**

* Très efficace **en situation d’urgence** (incident critique, panne prod, faille de sécurité).
* Donne un cadre clair à une équipe très peu expérimentée ou désorganisée.
* Permet d’aller vite si les décisions doivent être centralisées.

**Limites :**

* Peut démotiver à moyen/long terme (sentiment de ne pas être écouté).
* Bloque la prise d’initiative.
* Dépend fortement de la compétence du leader (si il se trompe, tout le monde suit… dans la mauvaise direction).

**Exemple concret (IT / cyber) :**
Tu es responsable sécurité, un ransomware commence à chiffrer les serveurs.
Tu adoptes un style **autoritaire** :

* Tu dis : « On coupe immédiatement le réseau entre le SI interne et Internet. »
* Tu attribues les tâches : « Maxence, tu t’occupes des sauvegardes, Yannis tu vérifies les journaux, personne ne touche aux serveurs sans validation. »
  On ne discute pas de la philosophie, on exécute.

---

### 1.2. Style démocratique (participatif)

**Principe :**
Le leader implique l’équipe dans la **définition des décisions**, encourage les échanges, mais garde le rôle d’arbitre final.

**Caractéristiques :**

* Consultation de l’équipe avant de trancher.
* Brainstorming, co-construction de solutions.
* Responsabilisation des membres.
* Climat d’écoute, feedback bilatéral.

**Avantages :**

* Forte **motivation** des collaborateurs.
* Meilleure qualité des décisions (intelligence collective).
* Favorise l’autonomie et la montée en compétence.

**Limites :**

* Plus lent (il faut écouter, discuter, arbitrer).
* Peut donner une impression d’hésitation si le leader ne tranche pas clairement.
* Pas adapté en situation d’urgence.

**Exemple concret (projet applicatif) :**
Tu dois choisir la stack technique pour une nouvelle application métier (Node/React vs Spring/Angular vs Django).
Style **démocratique** :

* Tu organises une réunion : chaque dev présente avantages/inconvénients des stacks.
* Tu discutes des contraintes (sécurité, compétences internes, maintenabilité).
* Tu demandes un vote ou un avis argumenté, puis tu **tranches** en expliquant ta décision :
  « On part sur Spring/React pour ces raisons techniques et business… »

---

### 1.3. Style laisser-faire

**Principe :**
Le leader intervient très peu. Il laisse une grande autonomie, se contente de répondre aux questions quand on le sollicite.

**Caractéristiques :**

* Peu de directives, chacun s’organise comme il veut.
* Le leader fournit les ressources, mais n’encadre pas vraiment.
* Très faible contrôle.

**Avantages :**

* Peut très bien fonctionner avec une équipe **très expérimentée, auto-organisée**.
* Stimule la créativité, la prise d’initiative.
* Peu de micro-management.

**Limites :**

* Risque de désorganisation, flou sur les responsabilités.
* Certains membres se retrouvent perdus.
* Peut donner l’impression que « le chef est absent ».

**Exemple concret (équipe senior) :**
Tu as une équipe de 3 seniors fullstack, très autonomes, qui travaillent sur un module « non critique ».
Style **laisser-faire** :

* Tu définis le cadre global et les objectifs (features à livrer, deadline).
* Tu leur dis : « Organisez-vous comme vous voulez, tant que le livrable respecte tel niveau de qualité, sécurité, tests, etc. »
* Tu interviens uniquement sur demande ou aux jalons clés.

---

## 2. Le leadership situationnel de Hersey & Blanchard

Hersey & Blanchard partent d’une idée clé :

> « Il n’existe pas un *bon* style de leadership en soi.
> Le bon style dépend du **niveau de maturité** (ou de développement) du collaborateur. »

### 2.1. Deux axes : Tâche vs Relation

* **Comportement directif (tâche)** :
  À quel point le leader dit **quoi faire, comment, quand**, et contrôle l’exécution.
* **Comportement de soutien (relation)** :
  À quel point le leader écoute, motive, rassure, accompagne émotionnellement.

En combinant les deux, on obtient 4 styles :

1. **S1 – Diriger (Telling)** :
   Fortement directif, peu de soutien.
2. **S2 – Persuader / Vendre (Selling / Coaching)** :
   Fortement directif, fortement soutenant.
3. **S3 – Participer (Participating / Supporting)** :
   Peu directif, fortement soutenant.
4. **S4 – Déléguer (Delegating)** :
   Peu directif, peu de soutien (car le collaborateur est autonome).

### 2.2. Les niveaux de maturité / développement (D1 à D4)

Blanchard parle souvent de **niveaux de développement** (D1 à D4) :

* **D1 – Débutant enthousiaste**

  * Compétence : faible
  * Motivation / engagement : élevé
  * Exemple : stagiaire développeur très motivé mais ne connaît pas encore le stack.

* **D2 – Apprenant désillusionné**

  * Compétence : en progression, mais encore insuffisante
  * Motivation : en baisse (conflit entre ce qu’il croit savoir et la réalité)
  * Exemple : junior dev qui commence à se rendre compte de la complexité réelle du projet.

* **D3 – Performant prudent**

  * Compétence : bonne (il sait faire)
  * Motivation : variable, manque parfois de confiance ou d’envie
  * Exemple : développeur intermédiaire, techniquement bon, mais qui doute un peu ou manque de vision.

* **D4 – Expert autonome**

  * Compétence : très bonne
  * Motivation : élevée et stable
  * Exemple : senior qui maîtrise la techno, les process, a le sens des priorités.

### 2.3. Adapter le style : matrice D1–D4 ↔ S1–S4

Le principe du leadership situationnel :

> À chaque niveau de développement correspond un style de leadership optimal.

* **D1 → S1 (Diriger)**

  * Le collaborateur ne sait pas encore faire, mais est motivé.
  * Le leader donne des consignes très concrètes, étape par étape.

* **D2 → S2 (Persuader / Coaching)**

  * Le collaborateur commence à savoir faire, mais doute et se décourage.
  * Le leader explique **le pourquoi**, écoute les frustrations, motive, tout en restant très directif.

* **D3 → S3 (Participer / Supporting)**

  * Le collaborateur sait faire, mais manque parfois de confiance ou de motivation.
  * Le leader réduit les consignes techniques, augmente l’écoute, le feedback, la co-décision.

* **D4 → S4 (Déléguer)**

  * Le collaborateur sait faire et veut faire.
  * Le leader donne seulement les objectifs et laisse une grande autonomie.

---

### 2.4. Exemples concrets en contexte projet

#### Exemple 1 : nouveau développeur (D1 → S1)

* Contexte : nouveau stagiaire, première mission sur un microservice d’authentification.
* Niveau : motivé, mais ne connaît ni Spring Security, ni la stack du projet.
* Style du leader (S1 Diriger) :

  * Tu expliques exactement :

    * Quel repo cloner.
    * Quelle branche utiliser.
    * Quelles classes modifier.
    * Quels tests lancer.
  * Tu dis : « Tu suis ce tutoriel, tu me poses des questions si tu bloques, on fait un point à 16h. »

#### Exemple 2 : junior qui commence à se décourager (D2 → S2)

* Contexte : après deux semaines, le même junior se perd dans la complexité de JWT, 2FA, etc.
* Niveau : commence à comprendre, mais se sent dépassé, motivation en baisse.
* Style (S2 Persuader / Coaching) :

  * Tu restes directif techniquement (roadmap, tâches précises).
  * Mais tu ajoutes du **soutien** :

    * Tu expliques la logique globale d’authentification.
    * Tu montres que c’est normal de se sentir perdu.
    * Tu fragmentes les tâches pour lui redonner des victoires rapides.
  * Tu dis : « Aujourd’hui, objectif unique : implémenter la génération du JWT et le test unitaire associé. Le reste, on verra plus tard. »

#### Exemple 3 : développeur intermédiaire (D3 → S3)

* Contexte : dev intermédiaire qui sait coder un service, mais n’ose pas proposer des améliorations d’architecture.
* Niveau : compétence bonne, confiance moyenne.
* Style (S3 Participer) :

  * Tu lui demandes son avis : « Toi, comment tu verrais l’architecture de ce nouveau module ? »
  * Tu construis la solution avec lui, tu le laisses proposer.
  * Tu réduis les « ordres » techniques, tu augmentes l’écoute et la co-décision.

#### Exemple 4 : senior autonome (D4 → S4)

* Contexte : ton lead dev backend, très expérimenté, connaît la plateforme et la sécurité ISO 27001 par cœur.
* Niveau : D4.
* Style (S4 Déléguer) :

  * Tu lui donnes la vision globale : « On a besoin d’un service de sauvegarde chiffrée conforme ISO, livrable dans 3 semaines. »
  * Tu signes un « contrat de résultat » avec lui, pas un « contrat de moyens ».
  * Tu le laisses choisir les technos, organiser le travail, et tu fais des points d’arbitrage seulement sur les décisions stratégiques.

---

## 3. Focus Blanchard : Situational Leadership II (SLII)

Blanchard a affiné le modèle initial en insistant sur deux points :

1. La **courbe d’apprentissage** (D1 → D4) n’est pas linéaire : un collaborateur peut repasser de D3 à D2 dans un nouveau contexte (nouvelle techno, nouvelle équipe, changement d’organisation).
2. Le manager doit **re-diagnostiquer régulièrement** le niveau D1–D4 et **adapter son style** en conséquence, plutôt que rester figé dans son style « naturel ».

En pratique, ça donne des comportements très concrets :

* Tu fais souvent des 1:1 pour vérifier où en est la personne :

  * « Est-ce que tu te sens à l’aise techniquement ? »
  * « Est-ce que tu te sens motivé ? »
* Tu observes :

  * Beaucoup de questions techniques basiques → D1/D2 → plus de direction.
  * Remise en question personnelle ou manque de confiance → D2/D3 → plus de soutien.
  * Grande maîtrise + forte motivation → D4 → délégation.
Parfait, on garde la même logique D1 → D4 / S1 → S4, mais cette fois dans une **vraie entreprise**, avec une équipe projet IT.

---

## Exemple en entreprise sur une année de projet

Contexte :
Une PME lance un **nouveau produit SaaS** (par exemple une plateforme de facturation ou un CRM interne).
Tu es **chef de projet / tech lead** d’une équipe composée de :

* 1 développeur junior backend
* 1 développeur intermédiaire frontend
* 1 admin système / DevOps
* 1 product owner métier

L’année se découpe en 4 grandes phases.

---

### Période 1 – Onboarding et kick-off (Janvier–Février)

→ Beaucoup de D1, donc style S1 « Diriger »

* Le projet démarre, l’équipe découvre :

  * La nouvelle architecture (microservices, API, sécurité, RGPD…)
  * Les outils (Git flow, CI/CD, Jira, conventions de code)
  * Le contexte client (réglementation, enjeux métier)

**Niveau de développement :**

* Le dev junior backend est **D1** sur la stack du projet (Spring Security, JWT, etc.).
* Le dev frontend est D1/D2 sur le design system et les bonnes pratiques accessibilité.
* Le DevOps est D1 sur l’infra cloud choisie (nouveau provider ou nouvelle façon de faire).
* Le PO est D1 sur les aspects techniques mais très motivé.

**Ton style (S1 – Diriger) :**

* Tu donnes des consignes extrêmement précises :

  * « Tu clones ce repo, tu crées une branche `feature/auth-login`, tu suis ce guide, tu écris au moins 3 tests unitaires. »
  * « Pour chaque ticket Jira, on suit ce workflow, pas autre chose. »
* Tu imposes des rituels simples : daily fixe, code review obligatoire, définition de done claire.
* Tu contrôles de près :

  * Relecture systématique des MR.
  * Tu valides chaque étape avant de passer à la suivante.

Objectif : sécuriser le décollage et éviter que tout le monde parte dans tous les sens.

---

### Période 2 – Montée en compétence… et première claque (Mars–Avril)

→ Beaucoup de D2, donc style S2 « Persuader / Coaching »

Le projet avance, mais les premières difficultés sérieuses apparaissent :

* Les dépendances techniques sont plus complexes que prévu.
* La sécurité et la conformité prennent du temps.
* Les premiers retours utilisateurs montrent que certaines fonctionnalités ne sont pas claires.

**Niveau de développement :**

* Le dev junior backend devient **D2** :

  * Il comprend mieux le code, mais se rend compte qu’il ne maîtrise pas encore l’architecture.
  * Il commence à douter (« Je ne vais jamais y arriver », « C’est trop complexe »).
* Le frontend est D2 aussi :

  * Il sait faire les écrans mais se bat avec les performances, l’API, les tests end-to-end.
* Le DevOps découvre la réalité de la prod, des logs, des incidents → D2.
* Le PO est D2 sur la priorisation : il se rend compte qu’on ne peut pas tout faire.

**Ton style (S2 – Persuader / Coaching) :**

* Tu restes directif sur le plan technique (quoi faire en priorité) :

  * « Cette semaine, on se concentre uniquement sur la robustesse de l’authentification et la gestion des erreurs. »
* Mais tu ajoutes beaucoup de **soutien** :

  * Tu expliques le « pourquoi » derrière chaque priorité.
  * Tu écoutes les frustrations et tu recentres :

    * « Oui, c’est normal de galérer sur cette partie, elle est complexe pour tout le monde au début. »
  * Tu organises du pair programming, des revues de code pédagogiques, des mini-formations internes.

Objectif : éviter la démotivation, donner du sens, tout en gardant un cadre solide.

---

### Période 3 – Croisière et responsabilisation (Mai–Septembre)

→ Une partie de l’équipe passe en D3, donc style S3 « Participer »

Le projet est lancé en pilote chez quelques clients internes/externes.

**Niveau de développement :**

* Le dev backend est maintenant **D3** :

  * Techniquement, il est bon.
  * Il sait développer un microservice entier, mais manque parfois de confiance.
* Le frontend est D3, très autonome sur l’UI, mais doute sur les décisions d’UX ou d’architecture front.
* Le DevOps est D3 : il gère les déploiements, mais a besoin de validation sur certains choix infra.
* Le PO est D3 sur la priorisation : sait arbitrer, mais hésite parfois à dire non aux demandes.

**Ton style (S3 – Participer / Supporting) :**

* Tu réduis le côté « chef qui dit quoi faire ligne par ligne ».
* Tu augmentes la **co-décision** :

  * Tu demandes : « Quelles options techniques voyez-vous pour implémenter cette nouvelle fonctionnalité ? »
  * Tu fais des ateliers d’architecture où l’équipe propose des solutions, que tu challenges.
* Tu te concentres sur :

  * Le soutien, le feedback, la clarification.
  * La valorisation : « Ce que tu as fait là sur le monitoring, c’est exactement ce qu’il nous fallait. »

Tu laisses plus de latitude :

* Le backend choisit la manière d’implémenter un pattern (CQRS, par exemple), tant que les contraintes de sécurité sont respectées.
* Le frontend propose une nouvelle organisation des composants, tu valides après discussion.
* Le DevOps propose une amélioration du pipeline CI/CD, tu ne lui donnes plus chaque commande à taper.

Objectif : faire grandir la confiance, responsabiliser, préparer la délégation.

---

### Période 4 – Maturité et délégation (Octobre–Décembre)

→ D4 pour plusieurs membres, donc style S4 « Déléguer »

Le produit est en production, plusieurs clients l’utilisent, les process sont en place.

**Niveau de développement :**

* Le backend est **D4** sur son périmètre : il maîtrise la techno, l’architecture, les enjeux sécurité.
* Le frontend est D4 sur l’interface utilisateur.
* Le DevOps est D4 sur l’infra et le monitoring.
* Le PO est D4 sur la roadmap et la priorisation business.

**Ton style (S4 – Déléguer) :**

* Tu donnes des objectifs, pas des micro-tâches :

  * « D’ici la fin du trimestre, on doit améliorer les temps de réponse de 30 % et réduire les incidents en prod de moitié. »
* Tu laisses l’équipe concevoir « comment » y arriver :

  * Le backend propose une refonte de certains endpoints.
  * Le DevOps propose une stratégie de scaling ou de mise en cache.
  * Le frontend revoit certains écrans lourds.
* Tu fais des points réguliers, mais beaucoup plus orientés résultats que moyens :

  * Tu regardes les KPI, les incidents, la satisfaction client.
  * Tu interviens surtout pour débloquer des arbitrages (budget, priorités globales, relations avec d’autres directions).

Objectif : tirer parti de la maturité de l’équipe, libérer ta bande passante pour la stratégie, les nouveaux projets, la relation avec la direction.

---

## Résumé entreprise

* **Début de projet :**
  L’équipe est D1 sur la stack / l’organisation → tu es très directif (S1).

* **Après quelques mois :**
  L’équipe passe en D2 (plein de questions, charge mentale, complexité découverte) → tu coaches, tu expliques, tu rassures, tout en gardant des directives claires (S2).

* **Milieu de projet :**
  Certains deviennent D3, techniquement bons mais pas encore totalement confiants → tu passes en mode participatif, tu les impliques dans les décisions techniques et d’organisation (S3).

* **Fin d’année / Run :**
  Les plus expérimentés sont D4, tu leur délègues des pans entiers du projet (monitoring, sécurité, relation avec le client, management de juniors) → style S4, avec objectifs clairs et forte autonomie.
