# 🎙️ Script de Présentation - Projet FormaPro (20 min)

Ce document contient le discours suggéré pour la présentation orale. Il est divisé en **3 parties** équilibrées pour 3 intervenants.

**👥 Répartition suggérée :**

- **Intervenant 1 (Intro & Cadrage)** : Slides 1, 2, 3 (~6 min)
- **Intervenant 2 (Solution & Réalisation)** : Slides 4, 5, 6 (~8 min)
- **Intervenant 3 (Pilotage & Conclusion)** : Slides 7, 8, 9, 10 (~6 min)

---

## 🟢 PARTIE 1 : CONTEXTE & OBJECTIFS (Intervenant 1)

### Slide 1 : Titre / Intro (30 sec)

**Intervenant 1 :**
"Bonjour à tous. Nous sommes ravis de vous présenter aujourd'hui le projet de transformation digitale de **FormaPro**.
Comme vous le savez, le secteur de la formation professionnelle est en pleine mutation, et notre projet vise à moderniser radicalement nos outils pour rester compétitifs.
Nous allons vous détailler notre démarche pour déployer notre nouveau LMS et optimiser l'ensemble de notre gestion de formation."
_(Passer à la slide suivante)_

### Slide 2 : Contexte & Enjeux (3 min)

**Intervenant 1 :**
"Commençons par le contexte. **FormaPro** est un organisme solide : nous formons 3 500 stagiaires par an pour le compte de 120 entreprises clientes. Nous gérons une équipe de plus de 100 formateurs (permanents et vacataires) sur 150 formations différentes.

Cependant, notre fonctionnement actuel a atteint ses limites.
Aujourd'hui, nous sommes confrontés à trois problèmes majeurs :

1.  **L'inefficacité administrative** : Nous gérons tout sur Excel, papier et via des outils non connectés comme Zoom. Cela génère des erreurs et une perte de temps considérable.
2.  **Une offre pédagogique vieillissante** : Notre taux de complétion en e-learning plafonne à 45%, ce qui est très faible. Nos contenus ne sont pas assez engageants.
3.  **L'absence de visibilité** : Nos clients entreprises nous réclament des tableaux de bord de suivi que nous sommes incapables de fournir automatiquement.

À cela s'ajoute une urgence absolue : **l'audit Qualiopi** dans 18 mois. Si nous ne sommes pas capables de garantir une traçabilité numérique parfaite, nous risquons de perdre notre certification. C'est donc une question de survie et de compétitivité."

### Slide 3 : Objectifs SMART (2 min 30)

**Intervenant 1 :**
"Face à ce constat, nous avons fixé des objectifs clairs et mesurables pour ce projet, à horizon juin 2026.
Notre ambition est de déployer une plateforme unique qui centralise tout.

Concrètement, nous visons :

- **Sur la performance** : Réduire de **50%** le temps passé sur les tâches administratives grâce à l'automatisation.
- **Sur la pédagogie** : Faire passer le taux de complétion e-learning de 45% à **70%** en proposant une expérience moderne.
- **Sur la qualité** : Garantir **100% de conformité Qualiopi** grâce à la traçabilité native des données.

Nous voulons également offrir une véritable valeur ajoutée à nos utilisateurs :

- Un **portail client** pour nos 120 entreprises partenaires.
- Un accès **mobile** pour que nos apprenants puissent se former partout.
- Et la digitalisation totale des processus, de l'inscription jusqu'à la délivrance du certificat.

Je laisse maintenant la parole à [Nom Intervenant 2] pour vous présenter la solution retenue."

---

## 🔵 PARTIE 2 : SOLUTION & DÉPLOIEMENT (Intervenant 2)

### Slide 4 : Solution & Méthodologie (2 min 30)

**Intervenant 2 :**
"Merci. Pour répondre à ces objectifs ambitieux, nous avons étudié plusieurs scénarios.
Nous avons écarté le développement sur-mesure, trop long et coûteux à maintenir, ainsi que les solutions Open Source comme Moodle, qui demandaient trop d'expertise technique interne pour l'UX.

Nous avons donc fait le choix d'un **LMS en mode SaaS (Software as a Service)**.
Pourquoi ce choix ?

- Pour la **rapidité de déploiement** : le 'Time-to-market' est critique avec l'échéance Qualiopi.
- Pour la **conformité native** : les éditeurs SaaS mettent à jour leur outil selon les réglementations.
- Et pour maîtriser nos **coûts** via un abonnement mensuel plutôt qu'un lourd investissement initial.

Côté méthodologie, nous partons sur de l'**Agile Scrum**. Avec des sprints de 2 semaines, nous pourrons livrer des fonctionnalités régulièrement et ajuster le tir selon les retours de nos formateurs et stagiaires, ce qui est essentiel pour l'adoption."

### Slide 5 : Fonctionnalités Clés / Backlog (3 min)

**Intervenant 2 :**
"Concrètement, que va faire cette plateforme ? Nous avons structuré notre backlog autour de nos différents utilisateurs.

- **Pour les Stagiaires** : Ils auront enfin un espace unique pour suivre leurs parcours e-learning et blended, voir leur progression en temps réel et télécharger leurs certificats automatiquement. L'accès mobile est une priorité.
- **Pour les Formateurs** : Ils pourront déposer leurs contenus (PDF, vidéos), gérer leurs sessions et faire l'émargement numérique directement sur la plateforme.
- **Pour les Entreprises** : Elles disposeront d'un dashboard pour inscrire leurs collaborateurs et suivre leur montée en compétences.

Enfin, le cœur du réacteur, c'est l'intégration avec notre Système d'Information existant :

- Synchronisation avec **Salesforce** pour les données clients.
- Lien avec **Sage** pour automatiser la facturation.
- Et intégration de **Yousign** pour la signature électronique des documents légaux."

### Slide 6 : Planning & Déploiement (2 min 30)

**Intervenant 2 :**
"Comment allons-nous déployer tout cela ?
Nous avons une roadmap claire jusqu'en septembre 2026.

Actuellement, nous avons validé la phase de **Conception et Choix**.
Nous entrons dans la phase d'**Intégration et Tests** (Phases 6 à 9), où nous allons configurer le LMS et développer les connecteurs API.

Pour le déploiement final, nous avons opté pour une stratégie de **Canary Release**. C'est crucial pour sécuriser le lancement.
Nous n'allons pas ouvrir la plateforme à tout le monde d'un coup.

- Nous commencerons par un pilote avec **5%** des utilisateurs (quelques formateurs et 2 entreprises test).
- Puis nous monterons progressivement à 20%, 50%, pour atteindre **100% en septembre 2026**.

Cela nous permet de vérifier la charge, de corriger les bugs sans impacter tout le monde, et d'assurer un support de qualité.
Je passe la main à [Nom Intervenant 3] pour les aspects pilotage et budget."

---

## 🟠 PARTIE 3 : PILOTAGE & CONCLUSION (Intervenant 3)

### Slide 7 : Budget Détaillé (2 min)

**Intervenant 3 :**
"Merci. Parlons maintenant des moyens.
Nous avons estimé le coût du projet interne à environ **90 610 €**, ce qui correspond à **185 jours/homme** de travail sur l'année.

Ce budget interne couvre principalement :

- L'équipe IT pour l'intégration technique (27k€).
- Le pilotage par le Chef de Projet (26k€).
- Et le temps passé par la pédagogie et l'administration pour la migration des contenus et les recettes.

À cela s'ajoutent les coûts externes liés au SaaS :

- La licence du LMS (entre 800 et 2000€/mois selon le volume).
- Les outils tiers comme Yousign.
- Et une enveloppe pour l'audit Qualiopi et la communication de lancement.

Nous avons aussi prévu un budget de **MCO (Maintenance en Condition Opérationnelle)** de 10 à 20% par an pour assurer la pérennité de la solution."

### Slide 8 : Analyse des Risques (2 min)

**Intervenant 3 :**
"Un projet de cette ampleur comporte des risques que nous avons identifiés et anticipés.

Le risque le plus critique (Coté 9) concerne l'**Intégration SI**. Si les connecteurs avec Salesforce ou Sage ne fonctionnent pas, on bloque l'administratif.

- _Notre réponse_ : Nous mettons en place une 'Sandbox' technique pour tester ces flux bien avant la mise en prod.

Nous avons aussi deux risques majeurs (Cotés 6) :

1.  **La Migration des données** : Peur de perdre l'historique.
    - _Réponse_ : Back-ups complets et tests de migration sur des échantillons.
2.  **L'Adoption utilisateurs** : Le risque que les formateurs refusent de changer leurs habitudes.
    - _Réponse_ : C'est tout l'enjeu de notre conduite du changement. Nous allons nommer des ambassadeurs et former massivement les équipes.

Enfin, le risque de **Conformité Qualiopi** est géré par des audits blancs réguliers."

### Slide 9 : Conclusion (1 min)

**Intervenant 3 :**
"Pour conclure, ce projet 'FormaPro' n'est pas juste un projet informatique, c'est la clé de voûte de notre stratégie future.

En déployant cette plateforme, nous allons :

1.  Gagner un temps précieux sur l'administratif (-50%).
2.  Sécuriser notre certification Qualiopi.
3.  Et surtout, offrir une expérience d'apprentissage moderne qui fidélisera nos clients et nos stagiaires.

Nous sommes prêts à lancer la prochaine phase et nous sommes confiants dans notre capacité à tenir les délais pour 2026.
Merci de votre attention."

### Slide 10 : Questions / Réponses (1 min)

**Intervenant 3 :**
"Nous sommes maintenant disponibles pour répondre à toutes vos questions."
