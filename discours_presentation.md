# 🎙️ Script de Présentation - Projet FormaPro (20 min)

Ce document contient le discours suggéré pour la présentation orale. Il est divisé en **3 parties** équilibrées pour 3 intervenants.

**👥 Répartition suggérée :**

- **Intervenant 1 (Cadrage & Enjeux)** : Slides 1 à 6 (~7 min)
- **Intervenant 2 (Réalisation & Déploiement)** : Slides 7 à 12 (~7 min)
- **Intervenant 3 (Pilotage & Conclusion)** : Slides 13 à 17 (~6 min)

---

## 🟢 PARTIE 1 : CADRAGE & ENJEUX (Intervenant 1)

### Slide 1 : Titre / Intro (30 sec)

**Intervenant 1 :**
"Bonjour à tous. Nous sommes ravis de vous présenter aujourd'hui le projet de transformation digitale de **FormaPro**.
Face aux mutations du secteur de la formation, nous lançons un projet ambitieux de modernisation de nos outils.
Nous allons vous détailler notre démarche complète, du cadrage stratégique jusqu'au déploiement de notre nouveau LMS."
_(Passer à la slide suivante)_

### Slide 2 : Contexte & Enjeux (1 min 30)

**Intervenant 1 :**
"FormaPro, c'est aujourd'hui 3 500 stagiaires par an et 120 entreprises clientes. Mais notre gestion actuelle sur Excel et papier freine notre croissance.
Nous faisons face à trois défis majeurs :

1.  **L'inefficacité administrative** et les risques d'erreurs.
2.  **Une offre e-learning vieillissante** (45% de complétion seulement).
3.  **L'urgence Qualiopi** : notre audit de renouvellement est dans 18 mois, et la traçabilité manuelle ne suffira plus."

### Slide 3 : Objectifs SMART (1 min)

**Intervenant 1 :**
"Notre objectif est clair : déployer une plateforme LMS intégrée d'ici juin 2026.
Nous visons :

- **-50%** de temps administratif.
- **70%** de complétion e-learning.
- **100%** de conformité Qualiopi.
  C'est un projet vital pour notre compétitivité."

### Slide 4 : Périmètre (IN / OUT) (1 min)

**Intervenant 1 :**
"Pour réussir, nous avons strictement délimité le périmètre.
**INCLUS (IN)** :

- Le LMS SaaS (Web & Mobile).
- L'automatisation administrative (Sage, Yousign).
- La migration des contenus existants.
- Le portail client.

**EXCLU (OUT)** :

- Pas de développement sur-mesure.
- Pas de création de contenus from scratch (rôle des formateurs).
- Pas de refonte du CRM Salesforce."

### Slide 5 : Parties Prenantes (1 min)

**Intervenant 1 :**
"Ce projet implique de nombreux acteurs.
En interne :

- La **Direction** et le **Responsable Pédagogique** (Sponsors).
- Nos **100 formateurs** (Utilisateurs clés à accompagner).
  En externe :
- Nos **Clients Entreprises** (Demandeurs de suivi).
- L'**Auditeur Qualiopi** (Garant de la conformité)."

### Slide 6 : Solution & Méthodologie (1 min 30)

**Intervenant 1 :**
"Nous avons choisi un **LMS en mode SaaS**.
C'est le choix de la raison : déploiement rapide (6 mois), coûts maîtrisés et conformité native.
Nous pilotons ce projet en **Agile Scrum** avec des sprints de 2 semaines pour rester flexibles et livrer de la valeur régulièrement.
Je laisse la parole à [Nom Intervenant 2]."

---

## 🔵 PARTIE 2 : RÉALISATION & DÉPLOIEMENT (Intervenant 2)

### Slide 7 : Fonctionnalités Clés (1 min)

**Intervenant 2 :**
"Merci. Notre backlog est priorisé par valeur utilisateur :

- **Stagiaires** : Accès mobile, parcours blended, certificats auto.
- **Formateurs** : Gestion sessions, émargement numérique.
- **Entreprises** : Dashboard de pilotage.
- **Admin** : Intégration SI (Salesforce, Sage)."

### Slide 8 : Planning & Estimation (1 min 30)

**Intervenant 2 :**
"Nous avons estimé la charge totale à **185 jours/homme** (PERT) sur 12 mois.
Le planning se découpe en 3 phases :

1.  **Cadrage** (Mois 1-2).
2.  **Réalisation** (Mois 3-8) : Paramétrage et API.
3.  **Déploiement** (Mois 9-12) : Lancement progressif."

### Slide 9 : WBS (Structure de Découpage) (1 min)

**Intervenant 2 :**
"Pour sécuriser cette charge, nous avons découpé le projet en tâches fines (WBS).
Des phases amont (Choix LMS, Audit SI) jusqu'aux phases de réalisation (Migration contenus, Paramétrage) et de déploiement.
Rien n'est laissé au hasard, chaque tâche a un responsable."

### Slide 10 : Matrice RACI (1 min)

**Intervenant 2 :**
"Justement, qui fait quoi ? Notre matrice RACI est claire :

- Le **Chef de Projet** est Responsable (R) du pilotage global.
- L'**Équipe IT** est Responsable de l'intégration technique.
- La **Direction** Valide (A) les choix stratégiques (Budget, LMS).
- Le **Resp. Pédagogique** est Responsable de la qualité des contenus."

### Slide 11 : Stratégie de Tests (1 min)

**Intervenant 2 :**
"La qualité est non négociable. Nous appliquons une pyramide de tests :

- 70% de tests unitaires automatisés.
- Mais surtout des **Tests d'Acceptation (UAT)** avec des formateurs et stagiaires réels pour valider les parcours critiques (Inscription, Certificat)."

### Slide 12 : Plan de Déploiement (1 min 30)

**Intervenant 2 :**
"Enfin, pour le déploiement, nous jouons la sécurité avec une **Canary Release**.

- **Étape 1** : Pilote sur 5% (2 entreprises amies).
- **Étape 2** : Montée à 20% pour vérifier la charge.
- **Étape 3** : Généralisation à 100%.
  Cela nous permet de corriger les bugs sans impacter tout le monde.
  [Nom Intervenant 3] va conclure sur le pilotage."

---

## 🟠 PARTIE 3 : PILOTAGE & CONCLUSION (Intervenant 3)

### Slide 13 : KPI & Suivi (1 min 30)

**Intervenant 3 :**
"Merci. Pour piloter ce projet, nous suivons 4 KPI majeurs :

1.  **Avancement** : J/H consommés vs prévus.
2.  **Budget** : Écart Coût Réel vs Prévu.
3.  **Adoption** : Le taux d'utilisateurs actifs (c'est le juge de paix).
4.  **Qualité** : La satisfaction stagiaire (> 4/5)."

### Slide 14 : Budget Détaillé (1 min 30)

**Intervenant 3 :**
"Le budget est de **90 610 €** en interne (185 J/H), couvrant l'IT et le pilotage.
Les coûts externes (Licence SaaS) sont des charges de fonctionnement (OPEX).
Nous avons prévu une enveloppe de maintenance (MCO) de 10-20% par an pour assurer la pérennité."

### Slide 15 : Analyse des Risques (1 min 30)

**Intervenant 3 :**
"Nous restons vigilants sur les risques.

- **Intégration SI** (Critique) : Nous testons les API en Sandbox.
- **Migration Données** (Élevé) : Nous faisons des backups complets.
- **Adoption** (Élevé) : Nous misons tout sur la formation et l'accompagnement des formateurs."

### Slide 16 : Conclusion (1 min)

**Intervenant 3 :**
"En conclusion, le projet FormaPro est structuré pour réussir.
Il répond à nos enjeux de productivité (-50% admin), de qualité (Qualiopi) et de business (Offre moderne).
Nous sommes prêts à lancer la réalisation."

### Slide 17 : Questions / Réponses (30 sec)

**Intervenant 3 :**
"Merci de votre attention. Nous sommes prêts à répondre à vos questions."
