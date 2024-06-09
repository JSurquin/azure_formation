---
layout: intro
introImage: "https://ff695b5dd2960f41cb75835a324f0804.r2.cloudflarestorage.com/drp-cl/thumbs/7f23ebef-ed0a-42d2-955e-aa44aa714524/7671326b-75d5-4400-ae9b-1652c40898d0/f871b6aa-7474-4c8f-81d1-b48a5f42299b.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=fed7aac277aea51eca0c294ada409f61%2F20240609%2Fauto%2Fs3%2Faws4_request&X-Amz-Date=20240609T104342Z&X-Amz-Expires=300&X-Amz-SignedHeaders=host&X-Amz-Signature=2f0e60e7500cfcf9cecbad983a26fe06bd987e30804f9739c00bb67113a2d3f6"

# try also 'default' to start simple
theme: unicorn
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Azure - 2024
info: |
  ## Andromed
  Formation Azure pour tous.

  En savoir plus sur [andromed.fr](https://andromed.fr)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

# 🌐 Azure - 2024

Cette formation couvre les bases d'Azure, y compris les services cloud, la sécurité, la scalabilité, les outils de développement, l'intelligence artificielle, l'analyse de données et la gestion des réseaux virtuels. Les élèves apprendront à utiliser et à intégrer ces services dans leurs propres projets.

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Allons y <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Ouvrir dans l'éditeur" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---

<!-- ## transition: fade-out -->

# ❓ Qu'est-ce que Azure

## Qu'est ce que le cloud computing ?

Aujourd'hui nous allons faire une formation Azure sur ces points précis :

- ☁️ **Services Cloud** - découvrez les différents services offerts par Azure
- 🔒 **Sécurité** - apprenez comment sécuriser vos applications et données sur Azure
- 📈 **Scalabilité** - comprenez comment faire évoluer vos applications avec Azure
- 🛠 **Outils de Développement** - explorez les outils et SDKs fournis par Azure
- 💡 **Intelligence Artificielle** - intégrez des services d'IA dans vos solutions Azure
- 📊 **Analyse de Données** - utilisez Azure pour analyser et visualiser vos données
- 🌐 **Réseau** - configurez et gérez les réseaux virtuels sur Azure
  <br>
  <br>

En savoir plus sur [Andromed.fr](https://andromed.fr)

<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

<!--
Here is another comment.
-->

---
layout: image-center
image: "https://picsum.photos/536/354"
imageWidth: "450"
imageHeight: "950"
---

# 🚀 Introduction Rapide à Azure

Azure est une plateforme de cloud computing proposée par Microsoft. Elle permet aux entreprises et aux développeurs de créer, déployer et gérer des applications à travers un réseau mondial de centres de données. Azure offre une large gamme de services, y compris le calcul, le stockage, les bases de données, l'analytique, le machine learning, et bien plus encore.

## Pourquoi choisir Azure ?

- 📈 **Évolutivité** : Azure permet de faire évoluer vos applications en fonction de la demande.
- 🔒 **Sécurité** : Profitez des mesures de sécurité avancées et de la conformité aux normes internationales.
- 🔧 **Flexibilité** : Supporte une variété de langages de programmation, frameworks et outils.
- 💰 **Économie** : Payez uniquement pour ce que vous utilisez avec des options de tarification flexibles.

Pour plus d'informations, visitez le [site officiel d'Azure](https://azure.microsoft.com).

<!--
transition: slide-up
level: 2
-->

---
layout: table-contents
---

## Services Clés

- 💻 **Azure Virtual Machines** : Créez des machines virtuelles sous Windows ou Linux.
- 🌐 **Azure App Services** : Déployez des applications web et mobiles rapidement.
- 🗃️ **Azure SQL Database** : Base de données relationnelle en tant que service.
- 🛠️ **Azure DevOps** : Outils pour la gestion de projets et le déploiement continu.

Azure est conçu pour aider les entreprises à innover plus rapidement, à économiser de l'argent et à être plus agiles. Que vous soyez une startup ou une grande entreprise, Azure offre les outils et les services nécessaires pour réussir dans le cloud.

---

# 🧭 Navigation

Survolez le coin inférieur gauche pour voir le panneau de contrôle de la navigation, [en savoir plus](https://sli.dev/guide/navigation.html)

## Raccourcis clavier

|                                                       |                                     |
| ----------------------------------------------------- | ----------------------------------- |
| <kbd>droite</kbd> / <kbd>espace</kbd>                 | prochaine animation ou diapositive  |
| <kbd>gauche</kbd> / <kbd>shift</kbd><kbd>espace</kbd> | animation ou diapositive précédente |
| <kbd>haut</kbd>                                       | diapositive précédente              |
| <kbd>bas</kbd>                                        | diapositive suivante                |

<!-- https://sli.dev/guide/animations.html#click-animations -->

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

---
layout: two-cols
layoutClass: gap-16
---

# 📝 Avant de commencer

Nous allons voir le tableau des matières :

---

# 📚 Table des matières

Voici notre table des matières :
<Toc/>

---

# 🌐 Introduction à Azure

Azure est une plateforme de cloud computing de Microsoft, offrant une gamme de services pour le développement, le déploiement et la gestion d'applications à travers un réseau mondial de centres de données.

---

# 🛠️ Services Principaux d'Azure

## Calcul

- 💻 **Machines Virtuelles** : Créez des machines virtuelles Windows et Linux en quelques secondes.
- 🌐 **App Services** : Créez et hébergez des applications web sans gérer l'infrastructure.

## Stockage

- 🗄️ **Blob Storage** : Stockez de grandes quantités de données non structurées.
- 📁 **File Storage** : Partagez des fichiers via des protocoles SMB et NFS.

## Réseautage

- 🌐 **Virtual Network** : Créez des réseaux privés dans le cloud.
- ⚖️ **Load Balancer** : Distribuez le trafic réseau pour une haute disponibilité.

---

# 🖥️ Démonstration : Création d'une Machine Virtuelle

## Étapes pour créer une VM

1. 🖥️ Connectez-vous au portail Azure.
2. ➕ Accédez à "Machines Virtuelles" et cliquez sur "Ajouter".
3. ⚙️ Configurez les paramètres de base (nom, région, image, taille).
4. 🔒 Configurez les paramètres de réseau et de sécurité.
5. ✅ Vérifiez et créez la VM.

---

# 🛠️ Gestion des Ressources

🛠️ Azure Resource Manager (ARM) permet de gérer vos ressources Azure via des modèles de déploiement, des groupes de ressources et des rôles de contrôle d'accès.

## Groupes de Ressources

📦 Un groupe de ressources est un conteneur qui contient les ressources associées pour une solution Azure.

## Modèles ARM

📄 Les modèles ARM sont des fichiers JSON qui définissent l'infrastructure et la configuration de vos ressources Azure.

# 🏁 Conclusion

Azure offre une vaste gamme de services pour répondre à vos besoins en matière de cloud computing. Que vous soyez développeur, administrateur système ou architecte, Azure a des outils pour vous aider à réussir.

---

# ❓ Questions ?

N'hésitez pas à poser des questions ou à demander des démonstrations supplémentaires.

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

## <p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

# 🔒 Sécurité sur Azure

Azure offre une gamme complète de services pour sécuriser vos applications et données.

## Azure Security Center

🛡️ Azure Security Center fournit une gestion unifiée de la sécurité et une protection avancée contre les menaces pour les charges de travail dans le cloud et sur site.

## Azure Key Vault

🔑 Azure Key Vault permet de protéger les clés cryptographiques et autres secrets utilisés par les applications cloud et les services.

---

# 📊 Surveillance et Gestion

Azure propose des outils pour surveiller et gérer vos ressources de manière efficace.

## Azure Monitor

📈 Azure Monitor maximise la disponibilité et les performances de vos applications en fournissant une solution complète pour la collecte, l'analyse et l'action sur les données de télémétrie.

## Azure Log Analytics

📊 Azure Log Analytics vous permet de collecter et d'analyser les données de journalisation de vos ressources Azure.

---

# 🚀 DevOps avec Azure

Azure DevOps fournit des services de bout en bout pour le développement et le déploiement d'applications.

## Azure Pipelines

🚀 Azure Pipelines permet de créer, tester et déployer en continu sur n'importe quelle plateforme et cloud.

## Azure Repos

📂 Azure Repos offre un contrôle de version avec Git et des dépôts Git privés.

---

# 🧠 Intelligence Artificielle et Machine Learning

Azure propose des services pour intégrer l'intelligence artificielle et le machine learning dans vos applications.

## Azure Cognitive Services

🧠 Azure Cognitive Services permet d'ajouter des fonctionnalités d'IA telles que la vision par ordinateur, la reconnaissance vocale et la compréhension du langage naturel à vos applications.

## Azure Machine Learning

🤖 Azure Machine Learning est un service qui permet de créer, entraîner et déployer des modèles de machine learning à grande échelle.

---

# 🏁 Conclusion

Azure est une plateforme puissante et flexible qui peut répondre à une variété de besoins en matière de cloud computing. Que vous cherchiez à héberger des applications, à gérer des ressources ou à intégrer des capacités d'intelligence artificielle, Azure a des solutions pour vous.

---

# ❓ Questions ?

N'hésitez pas à poser des questions ou à demander des démonstrations supplémentaires.

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

---

# 🖥️ Services de Calcul

Azure propose divers services de calcul pour répondre à vos besoins en matière de traitement et d'hébergement.

## Azure Virtual Machines

💻 Azure Virtual Machines vous permet de créer et d'utiliser des machines virtuelles dans le cloud, offrant une flexibilité et un contrôle complets sur l'environnement de calcul.

## Azure App Services

🌐 Azure App Services est une plateforme entièrement gérée pour créer, déployer et mettre à l'échelle des applications web, des API et des applications mobiles.

---

# 🗄️ Services de Stockage

Azure offre des solutions de stockage pour gérer vos données de manière sécurisée et évolutive.

## Azure Blob Storage

🗄️ Azure Blob Storage est conçu pour stocker de grandes quantités de données non structurées, telles que des images, des vidéos et des documents.

## Azure Disk Storage

💾 Azure Disk Storage fournit des disques durables et hautement disponibles pour les machines virtuelles Azure.

---

# 🌐 Services de Réseautage

Azure propose des services de réseautage pour connecter et gérer vos ressources de manière sécurisée.

## Azure Virtual Network

🌐 Azure Virtual Network permet de créer des réseaux privés dans le cloud et de connecter des ressources Azure de manière sécurisée.

## Azure Load Balancer

⚖️ Azure Load Balancer distribue le trafic réseau entrant vers plusieurs ressources pour assurer une haute disponibilité et une résilience.

---

# 🗃️ Services de Base de Données

Azure offre des services de base de données pour gérer vos données de manière efficace et sécurisée.

## Azure SQL Database

🗃️ Azure SQL Database est un service de base de données relationnelle entièrement géré, basé sur le moteur SQL Server.

## Azure Cosmos DB

🌍 Azure Cosmos DB est une base de données NoSQL distribuée à l'échelle mondiale, conçue pour des applications modernes avec des besoins de faible latence et de haute disponibilité.

---

# 📊 Services d'Analyse

Azure propose des services pour analyser et visualiser vos données.

## Azure Synapse Analytics

📊 Azure Synapse Analytics est un service d'analyse qui permet de fusionner les entrepôts de données et les systèmes de Big Data.

## Azure Data Lake

🌊 Azure Data Lake permet de stocker et d'analyser de grandes quantités de données de manière économique et sécurisée.

---

# 🔒 Services de Sécurité

Azure offre une gamme complète de services pour sécuriser vos applications et données.

## Azure Security Center

🛡️ Azure Security Center fournit une gestion unifiée de la sécurité et une protection avancée contre les menaces pour les charges de travail dans le cloud et sur site.

## Azure Key Vault

🔑 Azure Key Vault permet de protéger les clés cryptographiques et autres secrets utilisés par les applications cloud et les services.

---

# 🛠️ Services de Gestion

Azure propose des outils pour surveiller et gérer vos ressources de manière efficace.

## Azure Monitor

📈 Azure Monitor maximise la disponibilité et les performances de vos applications en fournissant une solution complète pour la collecte, l'analyse et l'action sur les données de télémétrie.

## Azure Log Analytics

📉 Azure Log Analytics vous permet de collecter et d'analyser les données de journalisation de vos ressources Azure.

---

# 🚀 Services de DevOps

Azure DevOps fournit des services de bout en bout pour le développement et le déploiement d'applications.

## Azure Pipelines

🚀 Azure Pipelines permet de créer, tester et déployer en continu sur n'importe quelle plateforme et cloud.

## Azure Repos

📂 Azure Repos offre un contrôle de version avec Git et des dépôts Git privés.

---

# 🧠 Services d'Intelligence Artificielle et de Machine Learning

Azure propose des services pour intégrer l'intelligence artificielle et le machine learning dans vos applications.

## Azure Cognitive Services

🧠 Azure Cognitive Services permet d'ajouter des fonctionnalités d'IA telles que la vision par ordinateur, la reconnaissance vocale et la compréhension du langage naturel à vos applications.

## Azure Machine Learning

🤖 Azure Machine Learning est un service qui permet de créer, entraîner et déployer des modèles de machine learning à grande échelle.

---

# 🏁 Conclusion

Azure est une plateforme puissante et flexible qui peut répondre à une variété de besoins en matière de cloud computing. Que vous cherchiez à héberger des applications, à gérer des ressources ou à intégrer des capacités d'intelligence artificielle, Azure a des solutions pour vous.

---

# ❓ Questions ?

N'hésitez pas à poser des questions ou à demander des démonstrations supplémentaires.

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

---

# 🔒 Sécurité et Conformité

Azure offre des services pour garantir la sécurité et la conformité de vos applications et données.

## Azure Policy

📜 Azure Policy permet de créer, attribuer et gérer des politiques pour garantir que vos ressources restent conformes aux normes de votre organisation.

## Azure Blueprints

📘 Azure Blueprints permet de définir un ensemble de ressources Azure pour implémenter et gérer des environnements conformes.

---

layout: cover

# Slidev

This is the cover page.

---

# 🚚 Migration vers Azure

Azure propose des outils pour faciliter la migration de vos applications et données vers le cloud.

## Azure Migrate

🚚 Azure Migrate fournit un hub centralisé pour évaluer et migrer vos infrastructures locales vers Azure.

## Azure Site Recovery

🔄 Azure Site Recovery permet de répliquer, de basculer et de récupérer des charges de travail avec un minimum de temps d'arrêt.

---

# 📦 Services de Conteneurs

Azure offre des services pour déployer et gérer des conteneurs.

## Azure Kubernetes Service (AKS)

📦 Azure Kubernetes Service (AKS) simplifie le déploiement, la gestion et les opérations de Kubernetes.

## Azure Container Instances

🐳 Azure Container Instances permet de déployer des conteneurs Docker sans gérer d'infrastructure.

---

# Services de Messagerie

Azure propose des services pour la communication entre applications.

## Azure Service Bus

📬 Azure Service Bus est un service de messagerie entièrement géré pour la communication entre applications.

## Azure Event Grid

📅 Azure Event Grid permet de gérer les événements `à grande échelle avec une faible latence.

---

# Services de Gestion des Identités

Azure offre des services pour gérer les identités et les accès.

## Azure Active Directory

🆔 Azure Active Directory est un service de gestion des identités et des accès basé sur le cloud.

## Azure AD B2C

👥 Azure AD B2C permet de gérer les identités des clients pour vos applications.

---

# Services de Blockchain

Azure propose des services pour développer et gérer des applications blockchain.

## Azure Blockchain Service

🔗 Azure Blockchain Service permet de créer, gérer et développer des réseaux blockchain.

## Azure Blockchain Workbench

🛠️ Azure Blockchain Workbench fournit des outils pour simplifier le développement d'applications blockchain.

---

# Services de Gestion des API

Azure offre des services pour gérer vos API.

## Azure API Management

🔧 Azure API Management permet de publier, sécuriser, transformer, maintenir et surveiller vos API.

## Azure Logic Apps

🔄 Azure Logic Apps permet de créer des workflows automatisés pour intégrer vos applications et services.

---

# Services de Réalité Mixte

Azure propose des services pour développer des applications de réalité mixte.

## Azure Spatial Anchors

📌 Azure Spatial Anchors permet de créer des expériences de réalité augmentée persistantes et multi-utilisateurs.

## Azure Remote Rendering

🖼️ Azure Remote Rendering permet de rendre des modèles 3D complexes en temps réel.

---

# Services de Jeux

Azure offre des services pour développer et héberger des jeux.

## Azure PlayFab

🎮 Azure PlayFab est une plateforme de services backend pour les jeux, offrant des outils pour gérer les joueurs, les analyses et les économies de jeu.

## Azure Game Development Virtual Machines

🖥️ Azure Game Development Virtual Machines fournit des environnements de développement optimisés pour les jeux.

---

# Conclusion

Azure continue d'innover et d'élargir ses services pour répondre aux besoins variés des entreprises modernes. Explorez les possibilités et trouvez les solutions qui conviennent le mieux à vos projets.

---

# Questions ?

N'hésitez pas à poser des questions ou à demander des démonstrations supplémentaires.

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

---

# Services de Données et d'IA

Azure propose des services pour gérer et analyser vos données avec des capacités d'intelligence artificielle.

## Azure Data Factory

🏭 Azure Data Factory est un service d'intégration de données qui permet de créer, planifier et orchestrer des workflows de données.

## Azure Databricks

🔥 Azure Databricks est une plateforme d'analyse rapide, facile et collaborative basée sur Apache Spark.

---

# Services de Sécurité Avancée

Azure offre des services pour renforcer la sécurité de vos applications et données.

## Azure Sentinel

🕵️ Azure Sentinel est une solution de gestion des informations et des événements de sécurité (SIEM) basée sur le cloud.

## Azure Bastion

🛡️ Azure Bastion permet d'accéder en toute sécurité à vos machines virtuelles sans exposer de ports RDP/SSH.

---

# Services de Gestion des Coûts

Azure propose des outils pour surveiller et optimiser vos dépenses cloud.

## Azure Cost Management

💰 Azure Cost Management permet de suivre, allouer et optimiser les coûts de vos ressources Azure.

## Azure Advisor

💡 Azure Advisor fournit des recommandations personnalisées pour optimiser vos ressources Azure en termes de coût, sécurité, performance et fiabilité.

---

# Services de Gouvernance

Azure offre des services pour assurer la gouvernance de vos ressources cloud.

## Azure Policy

📜 Azure Policy permet de créer, attribuer et gérer des politiques pour garantir que vos ressources restent conformes aux normes de votre organisation.

## Azure Blueprints

📘 Azure Blueprints permet de définir un ensemble de ressources Azure pour implémenter et gérer des environnements conformes.

---

# Services de Sauvegarde et de Récupération

Azure propose des services pour protéger vos données et assurer la continuité des activités.

## Azure Backup

🔄 Azure Backup est une solution de sauvegarde basée sur le cloud pour protéger vos données et applications.

## Azure Site Recovery

🔄 Azure Site Recovery permet de répliquer, de basculer et de récupérer des charges de travail avec un minimum de temps d'arrêt.

---

# Services de Réseau

Azure offre des services pour connecter et sécuriser vos ressources réseau.

## Azure ExpressRoute

🔌 Azure ExpressRoute permet de créer des connexions privées entre les centres de données Azure et votre infrastructure sur site.

## Azure Firewall

🔥 Azure Firewall est un service de sécurité réseau géré et basé sur le cloud pour protéger vos ressources Azure.

---

# Services de Développement

Azure propose des outils pour faciliter le développement et le déploiement d'applications.

## Azure DevTest Labs

🧪 Azure DevTest Labs permet de créer des environnements de développement et de test rapidement et à moindre coût.

## Azure App Configuration

⚙️ Azure App Configuration permet de gérer les paramètres de configuration de vos applications de manière centralisée.

---

# Services de Surveillance

Azure offre des outils pour surveiller et diagnostiquer vos applications et infrastructures.

## Azure Application Insights

🔍 Azure Application Insights est un service de surveillance des performances des applications pour détecter et diagnostiquer les problèmes.

## Azure Monitor

📈 Azure Monitor maximise la disponibilité et les performances de vos applications en fournissant une solution complète pour la collecte, l'analyse et l'action sur les données de télémétrie.

---

# Services de Conteneurs

Azure propose des services pour déployer et gérer des conteneurs.

## Azure Kubernetes Service (AKS)

📦 Azure Kubernetes Service (AKS) simplifie le déploiement, la gestion et les opérations de Kubernetes.

## Azure Container Instances

🐳 Azure Container Instances permet de déployer des conteneurs Docker sans gérer d'infrastructure.

---

# Conclusion

Azure continue d'innover et d'élargir ses services pour répondre aux besoins variés des entreprises modernes. Explorez les possibilités et trouvez les solutions qui conviennent le mieux à vos projets.

---

# Questions ?

N'hésitez pas à poser des questions ou à demander des démonstrations supplémentaires.

<img
  v-click
  class="absolute -bottom-9 -left-7 w-80 opacity-50"
  src="https://sli.dev/assets/arrow-bottom-left.svg"
  alt=""
/>

<p v-after class="absolute bottom-23 left-45 opacity-30 transform -rotate-10">Ici!</p>

---

# Exemple de code Typescript

#### ici un petit exemple d'utilisation du ts

```ts
const http = require("http");

const hostname = "127.0.0.1";
const port = 3000;

const server = http.createServer((req, res) => {
  res.statusCode = 200;
  res.setHeader("Content-Type", "text/plain");
  res.end("Bonjour, monde!\n");
});

server.listen(port, hostname, () => {
  console.log(`Le serveur tourne à l'adresse http://${hostname}:${port}/`);
});
```

---
layout: image-center
image: "https://learn.microsoft.com/en-us/azure/azure-monitor/media/overview/azure-portal.png"
imageWidth: "800"
imageHeight: "500"
---

## L'interface de Azure

Azure propose une interface de gestion graphique pour gérer vos ressources.

---

# Cas de figure concret d'utilisation d'azure dans votre fil rouge

### Rapellez vous votre fil rouge est un site de création de formations

### à partir de la donc comment utiliser azure sur ce projet ?

Nous allons :

- Créer un compte Azure si ce n'est pas déjà fait.
- Configurer un environnement de développement avec les outils Azure.
- Déployer une application web sur Azure App Services.
- Utiliser Azure SQL Database pour stocker les données de l'application.
- Mettre en place des mesures de sécurité avec Azure Security Center.
- Surveiller et analyser les performances de l'application avec Azure Monitor.

---
layout: table-contents
gradientColors: ["#8EC5FC", "#E0C3FC"]
---

# Quel est l'idée derrière notre formation?

L'idée est de pouvoir vous faire comprendre par l'exemple ce qu'on peut faire de magique avec Azure et rapidement avec Visual Studio

---

# Sécurité sur Azure

Azure offre une gamme complète de services pour sécuriser vos applications et données.

## Azure Security Center

- **Surveillance continue** 👍 : Surveillez la sécurité de vos ressources Azure en temps réel.
- **Évaluations de sécurité** 🛡️ : Recevez des recommandations pour améliorer la sécurité de vos ressources.
- **Gestion des menaces** 🚨 : Détectez et répondez aux menaces potentielles.

## Azure Active Directory

- **Gestion des identités** 👥 : Gérez les identités et les accès pour vos utilisateurs.
- **Authentification multi-facteurs** 🔐 : Ajoutez une couche de sécurité supplémentaire pour l'accès aux ressources.
- **Intégration avec des applications tierces** 🔗 : Utilisez Azure AD pour authentifier les utilisateurs sur des applications externes.

---

# Scalabilité sur Azure

Azure permet de faire évoluer vos applications en fonction de la demande.

## Azure Virtual Machine Scale Sets

- **Automatisation de la scalabilité** 🤖 : Créez et gérez un groupe de machines virtuelles identiques.
- **Équilibrage de charge** ⚖️ : Distribuez le trafic réseau entre plusieurs instances pour une haute disponibilité.
- **Mise à l'échelle automatique** 📈 : Ajustez automatiquement le nombre de VM en fonction de la demande.

## Azure Kubernetes Service (AKS)

- **Orchestration de conteneurs** 🐳 : Déployez et gérez des applications conteneurisées avec Kubernetes.
- **Scalabilité automatique** 📊 : Ajustez automatiquement le nombre de pods en fonction de la charge.
- **Intégration avec CI/CD** 🔄 : Intégrez AKS avec des pipelines de déploiement continu pour des mises à jour rapides.

---

# Outils de Développement sur Azure

Azure propose une variété d'outils pour les développeurs.

## Azure DevOps

- **Gestion de projet** 📅 : Utilisez Azure Boards pour planifier et suivre le travail.
- **CI/CD** 🚀 : Configurez des pipelines de build et de déploiement avec Azure Pipelines.
- **Dépôts Git** 🗂️ : Hébergez votre code source avec Azure Repos.

## Visual Studio Code

- **Extension Azure** 🔌 : Utilisez l'extension Azure pour gérer vos ressources directement depuis VS Code.
- **Débogage** 🐞 : Déboguez vos applications Azure localement.
- **Intégration Git** 🌐 : Gérez votre code source avec l'intégration Git.

---

# Intelligence Artificielle sur Azure

Azure propose des services d'IA pour intégrer des capacités intelligentes dans vos applications.

## Azure Cognitive Services

- **Vision par ordinateur** 👁️ : Analysez des images et des vidéos pour extraire des informations.
- **Traitement du langage naturel** 🗣️ : Comprenez et générez du texte en langage naturel.
- **Reconnaissance vocale** 🎤 : Convertissez la parole en texte et vice versa.

## Azure Machine Learning

- **Entraînement de modèles** 🏋️ : Utilisez des environnements gérés pour entraîner vos modèles de machine learning.
- **Déploiement de modèles** 🌐 : Déployez vos modèles en tant que services web pour les utiliser dans des applications.
- **Suivi et gestion** 📊 : Surveillez les performances de vos modèles et gérez les versions.

---

# Analyse de Données sur Azure

Azure offre des outils pour analyser et visualiser vos données.

## Azure Synapse Analytics

- **Intégration de données** 🔄 : Combinez des données provenant de différentes sources pour une analyse complète.
- **Analyse en temps réel** ⏱️ : Analysez des données en temps réel pour des insights immédiats.
- **Visualisation de données** 📊 : Utilisez des outils comme Power BI pour créer des rapports interactifs.

## Azure Data Lake

- **Stockage de données** 🗄️ : Stockez des quantités massives de données non structurées.
- **Analyse Big Data** 📈 : Utilisez des frameworks comme Hadoop et Spark pour analyser vos données.
- **Sécurité des données** 🔒 : Protégez vos données avec des contrôles d'accès et des audits.

---

# Réseau sur Azure

Azure propose des services pour configurer et gérer des réseaux virtuels.

## Azure Virtual Network

- **Isolation réseau** 🛡️ : Créez des réseaux privés pour isoler vos ressources.
- **Connexion hybride** 🔗 : Connectez vos réseaux locaux à Azure avec des VPN ou ExpressRoute.
- **Sécurité réseau** 🔐 : Utilisez des groupes de sécurité réseau (NSG) pour contrôler le trafic entrant et sortant.

## Azure Load Balancer

- **Distribution de charge** ⚖️ : Répartissez le trafic réseau entre plusieurs instances pour une haute disponibilité.
- **Scalabilité** 📈 : Ajustez automatiquement la capacité en fonction de la demande.
- **Surveillance** 🔍 : Suivez les performances et la santé de vos applications avec des métriques et des alertes.

---

