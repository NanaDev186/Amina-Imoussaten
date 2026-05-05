### Amina-Imoussaten
### Développeuse Logiciel Backend & Full-Stack 🦋| De l'architecture à l'application

## Présentation 
Vous avez l'idée et le design. Je vous accompagne pour donner vie à votre projet en toute simplicité et sérénité.

### **Qui suis-je ?**
Après 3 ans d'expérience en CDI, j'ai créé ma propre structure freelance, Krisopée, pour accompagner les entrepreneurs et les agences avec plus de proximité et de liberté.
Toujours en veille, j'aime explorer les nouvelles tendances et outils pour offrir des solutions modernes. Je développe également mes propres SaaS.

### **Mon rôle ?**
M'assurer que le cœur de votre application est robuste, sécurisé et performant. Spécialisée dans l'architecture backend, je peux également prendre en charge la partie mobile ou l'intégration de votre interface de manière fluide. 
Mon but est de vous expliquer simplement les choix techniques et de construire des fondations durables pour votre produit.

## **Expertise technique ?**
**Langages** : Kotlin (mon expertise principale), Java, Python, TypeScript, Go, Rust.
J'adapte mon choix selon les contraintes de performance et les besoins réels de votre projet.

**Backend Robuste & Sécurisé** : Conception d'APIs performantes et pensées pour durer.
Frameworks : principalement Spring Boot, NestJS, Gin, Axum.

**Mobile** : Des applications pensées pour l'écosystème mobile.
Technos : KMP (Kotlin Multiplatform), Android, iOS.

**Intégration & Frontend** : Des interfaces modernes et fluides.
Framework: NextJs

**Conception & Architecture**
* Base de données : modélisation claire et optimisée. Maîtrise de SQL/NoSQL
* Architecture : pas d'usine à gaz. On construit uniquement ce dont vous avez besoin de façon intelligente.
* Infrastructure & uutils : Docker pour des environnements maîtrisés, et Redis pour la gestion du cache et les données en mémoire.

**Déploiement & Hébergement**
Solutions agiles et adaptées (comme Railway ou Firebase) pour une mise en ligne rapide et sans friction.

## **Comment nous travaillons ensemble ?**
* **L'intelligence d'intégration** : Vos fonctionnalités complexes (comme les tâches lourdes ou l'IA) sont isolées pour ne jamais ralentir l'expérience de vos utilisateurs.
* **Un accompagnement bienveillant** : Je ne suis pas juste une exécutante, je suis un partenaire. Je vous conseille sur les meilleures pratiques pour faire avancer votre projet sereinement.
* **Des fondations durables (Scalabilité)** : L'application est pensée pour grandir avec vos utilisateurs. Le code est sécurisé, testé et optimisé pour éviter les pannes.
* **Une documentation claire et structurée** : Je vous fournis tous les éléments nécessaires pour suivre le projet (modélisation de base de données, schémas d'architecture, comptes-rendus).
* **Votre projet dans un "second cerveau"** : J'organise les connaissances et les documentations techniques dans un outil dédié (Obsidian). Tout est centralisé et cohérent. Et si vous souhaitez brancher une IA dessus plus tard, toutes les données sont déjà au bon format.

## Réalisations & projets SaaS
Voici un tour d'horizon des applications, architectures et outils que j'ai pu concevoir et développer, aussi bien lors de mes expériences en entreprise que dans le cadre de mon activité freelance et de l'édition de mes propres SaaS via Krisopée.

### Auropus, Saas d'audit de code 🧬
Un interprète technique qui transforme le code d'une application web en un rapport PDF clair et actionnable (sécurité, coûts, stabilité). Conçu spécialement pour les fondateurs non-tech.

**Pourquoi je l'ai créé ?**
Pour répondre à quatre peurs concrètes : les fuites de données, les pannes, la dépendance vis-à-vis d'un prestataire, et le coût des nouvelles fonctionnalités.

**Ce qu'il produit**
Un rapport exécutif notant l'application sur 5 axes (Sécurité des données, Stabilité, Coût des features, Maîtrise du projet, Passage à l'échelle), accompagné d'une lettre prête à être transmise au développeur.

**Garantie non-négociable**
La confidentialité absolue. Le code source n'est jamais sauvegardé. Il est analysé en mémoire et détruit instantanément.

**Architecture & Fonctionnement** 
* Traitement asynchrone : API Kotlin / Spring Boot qui publie un job dans une queue PostgreSQL, consommé par un worker Python dans un container séparé.
* Analyse multicouche : Exécution d'outils open-source éprouvés (Semgrep, Trivy, Gitleaks, tsc) combinée à 27 règles propriétaires.
* Intelligence Artificielle : Un appel unique au LLM (Claude) pour l'interprétation, la narration et le scoring.
* Restitution : Génération PDF avec OpenPDF et stockage sécurisé. Communication en temps réel avec le client via polling/SSE.

**Stack technique**
* Backend & API : Kotlin, Spring Boot, jOOQ, Supabase (PostgreSQL), Railway.
* Worker & Analyse : Python, Gitleaks, Semgrep, Trivy.
* IA & Restitution : Claude API (Sonnet), OpenPDF.
  
### Refonte et modernisation d'une application solidaire 🧡 (Expérience en CDI)
Modernisation et migration d'une architecture backend pour assurer la pérennité et l'évolution d'une application mobile d'entraide.

**Bénéfices & Fonctionnalités**
* Continuité de service : Maintien de l'application mobile existante sans interruption pour les utilisateurs pendant la migration.
* Gestion des acteurs : Structuration des espaces pour les particuliers et les associations.
* Parcours dynamiques : Gestion de formulaires et parcours utilisateurs complexes et évolutifs.

**Cœur Technique**
* Langage & Framework : Migration de Symfony vers Kotlin et Spring Boot.
* Sécurité & APIs : Création d'APIs RESTful sécurisées.
* Données : Base de données MariaDB, modélisation avec Hibernate et gestion des schémas avec Liquibase.
* Traitement avancé : Sérialisation polymorphe JSON avec Jackson pour gérer dynamiquement les réponses à des parcours complexes.
* Services : Gestion des emails, stockage et notifications

### Application de gestion pour agences immobilières 🏢 (Expérience en CDI)
Une plateforme complète conçue pour gérer des agences, les utilisateurs et leurs activités au quotidien.

**Bénéfices & Fonctionnalités**
* Organisation et sécurité : Gestion des accès selon les rôles (Admin, Agence, Membre) pour garantir la confidentialité des données.
* Automatisation : Envoi d'emails et de bilans programmés (via templates HTML) pour simplifier le suivi.
* Gestion des paiements : Intégration d'un système d'abonnement (notamment pour des cartes de visite virtuelles).
* Pilotage : Génération de statistiques pour mesurer les performances des équipes.
* Stockage : Centralisation et sécurisation des documents (images, vidéos) par agence.

**Cœur Technique**
* Langage & Framework : Kotlin et Spring Boot.
* Sécurité & APIs : APIs RESTful sécurisées avec Spring Security.
* Données : Base de données MariaDB, modélisation avec Hibernate et gestion des versions de schéma avec Liquibase.
* Services tiers : Stripe pour la gestion des transactions.
* Tâches asynchrones : Exécution de tâches en arrière-plan et notifications automatisées via l'annotation @Scheduled.

### 📬 Contact
* **Email :** `amina.imsst.dev@gmail.com`
* **LinkedIn :** `www.linkedin.com/in/amina-imoussaten`
