---
title: Introduction au System Design Frontend
layout: cover
description: Concevoir des applications frontend évolutives et performantes
transition: slide-left
theme: bricks
---

<!-- Slide 1: Introduction -->

# Introduction au System Design Frontend
### Concevoir des applications frontend évolutives et performantes  

<!-- Introduction -->
---
glowSeed: 14
---

# Epoundor TANDA

<div class="leading-8 opacity-80">
Développeur Frontend chez Kkiapay.<br>
A passionate developer from Benin🇧🇯.
</div>

<div my-20 w-min flex="~ gap-1" items-center justify-center>
<mdi-dev-to />
  <div><a href="https://dev.to/epoundev" target="_blank" class="border-none! font-300">epoundev</a></div>
  <mdi-github />
  <div><a href="https://github.com/epoundor" target="_blank" class="border-none! font-300">epoundor</a></div>
  <mdi-twitter />
  <div><a href="https://twitter.com/epoundev" target="_blank" class="border-none! font-300">epoundev</a></div>
   <mdi-npm />
  <div><a href="https://www.npmjs.com/~epoundor" target="_blank" class="border-none! font-300">epoundor</a></div>
</div>

<img src="https://avatars.githubusercontent.com/u/91498943?v=4" rounded-full w-40 abs-tr mt-16 mr-12/>
<img src="https://media-cdg4-3.cdn.whatsapp.net/v/t61.24694-24/413629530_319816870626680_3132319637535185569_n.jpg?stp=dst-jpg_s96x96_tt6&ccb=11-4&oh=01_Q5AaICLX6-6pRenQXGlhP-IebSBFWZQl8Rs1Z4ZSQMjdsGlJ&oe=67BE0F20&_nc_sid=5e03e0&_nc_cat=105" />

---
transition: fade
---


# Qu'est-ce que le System Design Frontend ?

## **Definition** 
🔹 Le processus de définition des éléments d'un système, ainsi que de leurs interactions et relations, afin de satisfaire un ensemble d'exigences spécifiées.

<!-- 
Il s'agit de prendre un énoncé de problème, de le décomposer en composants plus petits et de concevoir chaque composant de manière à ce qu'il fonctionne ensemble efficacement pour atteindre l'objectif global du système. Ce processus comprend généralement l'analyse du système actuel (le cas échéant) et la détermination des éventuelles déficiences, la création d'un plan détaillé pour le nouveau système et le test de la conception pour s'assurer qu'elle répond aux exigences. Il s'agit d'un processus itératif qui peut impliquer plusieurs cycles de conception, de tests et d'améliorations.

En génie logiciel, la conception du système est une phase du processus de développement logiciel qui se concentre sur la conception de haut niveau d'un système logiciel, y compris l'architecture et les composants.

C'est également l'un des aspects importants du processus d'entretien pour les ingénieurs logiciels. La plupart des entreprises organisent un entretien dédié à la conception de systèmes, au cours duquel elles demandent aux candidats de concevoir un système pour un problème donné. Les candidats doivent proposer une conception détaillée du système, y compris l'architecture, les composants et leurs interactions. Ils doivent également discuter des compromis impliqués dans leur conception et des alternatives qu'ils ont envisagées.
 -->
---

## **Exemples de composants de système:**

<v-clicks>

- Gestion de l'état et des composants.
- Optimisation des performances.
- Expérience utilisateur sous forte charge.

</v-clicks>
<!-- 
- Le system design en frontend, c'est comme être architecte d'une maison : il faut penser à la structure, à la décoration, et à la façon dont les gens vont l'utiliser.
- Aujourd'hui, les applications frontend sont de plus en plus complexes (ex : Netflix, Airbnb), et une bonne conception est essentielle pour garantir performance, maintenabilité et évolutivité.

Exemples: 
- Imaginez une application de chat (comme WhatsApp Web). Si elle est mal conçue, les messages peuvent mettre du temps à s'afficher, l'interface peut bugger, et l'expérience utilisateur sera mauvaise.
 -->
---
transition: fade
---

## System Design vs Design System
La différence entre **System Design** et **Design System** est majeure, bien qu'ils partagent des mots similaires  

### **1. System Design (Conception de système)**  
**Objectif** : Concevoir l'architecture technique d'un système logiciel.  
**Domaine** : Ingénierie logicielle, architecture logicielle et scalabilité.  
**Exemples** :  
   - Comment concevoir un système de paiement en ligne ?  
   - Comment gérer un million d'utilisateurs en temps réel ?  
   - Architecture backend (microservices, bases de données, API, load balancing).  

<!-- 💡 **C'est ce que tu veux présenter sur le frontend : comment concevoir des systèmes scalables et performants.**   -->


---
transition: fade
---

## System Design vs Design System
### **2. Design System (Système de design)**  
**Objectif** : Assurer la cohérence visuelle et UX d'une interface utilisateur.  
**Domaine** : UI/UX, design et développement frontend.  
**Exemples** :  
   - Définir une charte graphique (couleurs, typographies, icônes).  
   - Créer une bibliothèque de composants UI réutilisables (boutons, formulaires, modals).  
   - Exemples célèbres : Material Design (Google), Carbon Design System (IBM), Ant Design.

<!--
💡 **C'est un guide de design et développement frontend pour créer des interfaces homogènes.**
-->

---
transition: fade
---

## System Design vs Design System
### **Résumé rapide :**  
| | **System Design** | **Design System** |
|---|---|---|
| **But** | Concevoir l'architecture logicielle | Assurer la cohérence visuelle/UI |
| **Domaine** | Backend, frontend scalable | UI/UX, design, composants frontend |
| **Exemples** | Architecture d’un service de messagerie | Bibliothèque de composants UI |
| **Public** | Ingénieurs logiciels, architectes | Designers, développeurs frontend |
| **Exemples connus** | Architecture Netflix, Uber, etc. | Material Design, Ant Design |

<!-- **👉 Si tu fais une présentation sur System Design pour le frontend**, tu vas parler de **performance, scalabilité, gestion des états, architecture des composants**, etc. et non pas de chartes graphiques ou de design UI.   -->


---
transition: fade
---

## System Design vs Design System
<img class="max-h-full" src="https://siddarthkanted.wordpress.com/wp-content/uploads/2022/12/screenshot-2022-12-23-at-2.56.25-pm.png" />

###### __System Design Example__
---
transition: fade
---

## System Design vs Design System
<img class="max-h-full" src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*fKrxdQ-ZX0V9rZnEtvVHAg.jpeg" />

###### __Design System Example__

---
transition: fade
layout: fact
---

# Les Fondamentaux du System Design en Frontend 

---
layout: fact
---

Le system design en frontend consiste à concevoir une architecture logicielle qui organise et structure les différents éléments
d'une application côté client. Cette conception vise à garantir que l'application soit performante, scalable, maintenable, et sécurisée,
tout en offrant une excellente expérience utilisateur (UX).

---

## Différence entre Architecture Frontend et Backend
Le frontend et le backend ont des responsabilités distinctes :

- **Frontend** : Axé sur l'expérience utilisateur, la performance, et l'interface. Il doit être réactif, accessible, et optimisé pour différents appareils et navigateurs.
- **Backend** : Concentré sur la logique métier, la gestion des données, et la sécurité. Il fournit les données et les services nécessaires au frontend.

Le system design en frontend doit donc tenir compte des contraintes spécifiques au client, comme la limitation des ressources (mémoire, CPU) et la variabilité des environnements (navigateurs, appareils).
---
transition: fade
---

## Concepts Clés du System Design en Frontend

### 1. Modularité
<v-clicks>

- **Définition** : Diviser l'application en petits composants réutilisables et indépendants.
- **Avantages** :
   - Facilite la maintenance et les mises à jour.
   - Permet une meilleure collaboration entre développeurs.
- **Exemples** : Composants React, Vue.js, ou Angular.

</v-clicks>

---
transition: fade
---

## Concepts Clés du System Design en Frontend

### 2. Scalabilité
<v-clicks>

- **Définition** : Capacité de l'application à gérer une augmentation de la charge (utilisateurs, données, etc.).
- **Enjeux en frontend** :
   - Optimisation des performances pour éviter les ralentissements..
   - Utilisation de techniques comme le lazy loading ou le code splitting.
- **Exemples** : Micro-frontends pour diviser une grosse application en parties indépendantes.

</v-clicks>

---
transition: fade
---

## Concepts Clés du System Design en Frontend

### 3. Maintenabilité
<v-clicks>

- **Définition** : Facilité à mettre à jour, corriger, et faire évoluer l'application.
- **Bonnes pratiques** :
   - Code "propre" et bien documenté.
   - Utilisation de standards et de conventions.
   - Tests automatisés (unitaires, d'intégration).
- **Outils** : ESLint, Prettier, Storybook.

</v-clicks>

---
transition: fade
---

## Concepts Clés du System Design en Frontend

### 4. Performance
<v-clicks>

- **Définition** : Capacité de l'application à charger et à fonctionner rapidement.
- **Techniques d'optimisation** :
   - Minimisation des fichiers CSS, JavaScript.
   - Utilisation de CDN pour les assets.
   - Réduction du nombre de requêtes HTTP.
- **Outils** : Google Lighthouse, WebPageTest.

</v-clicks>

---
transition: fade
---

## Concepts Clés du System Design en Frontend

### 5. Sécurité
<v-clicks>

- **Définition** : Protection de l'application contre les attaques et les vulnérabilités..
- **Risques courants** :
   - Cross-Site Scripting (XSS).
   - Cross-Site Request Forgery (CSRF).
- **Bonnes pratiques** : 
   - Validation des inputs côté client et côté serveur.
   - Utilisation de HTTPS.
   - Protection des données sensibles (localStorage, cookies).

</v-clicks>
<!-- 

### Les Différents Types d'Architectures Frontend
## Single Page Application (SPA) :
Une seule page HTML, mise à jour dynamiquement via JavaScript.
- Avantages : Expérience utilisateur fluide, performances améliorées.
- Inconvénients : SEO plus complexe, charge initiale plus lourde.
- Exemples : React, Angular, Vue.js.

## Multi-Page Application (MPA) :
Plusieurs pages HTML, chargées à chaque navigation.
- Avantages : Meilleur SEO, simplicité.
- Inconvénients : Expérience utilisateur moins fluide, plus de requêtes serveur.
- Micro-Frontends :
   - Division de l'application en plusieurs petites applications indépendantes.
   - Avantages : Scalabilité, indépendance des équipes.
   - Inconvénients : Complexité accrue, gestion des dépendances.

__Maintenant que nous avons couvert les fondamentaux du system design en frontend, passons à l'étude des composants clés qui constituent une architecture frontend moderne.__
 -->
---
transition: fade
---

## Les Composants d'un System Design Frontend

- **Structure de l'application** :
   - Single Page Application (SPA) vs Multi-Page Application (MPA).
   - Architecture monolithique vs micro-frontends.

- **Gestion des états** :
   - State management (Redux, Vuex, Context API, etc.).
   - Local vs global state.
---
transition: fade
---

## Les Composants d'un System Design Frontend

- **Routage** :
   - Gestion des routes (React Router, Vue Router, etc.).
   - Dynamic routing et lazy loading.

- **Communication avec le backend** :
   - API REST, GraphQL, WebSockets.
   - Gestion des erreurs et des timeouts.

<!-- 
Dans une application de chat, le routage permet de passer de la liste des conversations à une conversation spécifique sans recharger la page. -->
---
transition: fade
---

## Les Composants d'un System Design Frontend
- **Gestion des assets** :
   - Optimisation des images, polices, et autres ressources.
   - Bundling (Webpack, Vite, etc.) et tree shaking.

---

## Cas d'étude

- WhatsApp Web (scalabilité + WebSockets).
- Twitter (optimisation de flux d’actualités).
- Facebook Messenger 
- Google Sheet
- Google Calendar
- ChatGPT (accessibilité et SSE)

---
layout: center
---
[Go to board](https://excalidraw.com/)
---
layout: center
---

**Ressources complémentaires :**
- [roadmap.sh/system-design](https://roadmap.sh/system-design)
- [tigerabrodi.blog](https://tigerabrodi.blog/frontend-system-design-chat-application)

---

🎤 **Questions ?**
