# Cahier des Charges

## 1. Contexte du projet

Décrire le contexte dans lequel le projet s'inscrit. Par exemple : le projet peut être une refonte de site web, une application mobile, ou un développement spécifique pour un besoin particulier. Cela inclut les objectifs du projet, les raisons de sa mise en place et les attentes des parties prenantes.

## 2. Public cible

Décrire le public cible du projet, ses caractéristiques principales, ses besoins et ses attentes. Par exemple : un site destiné à des professionnels du secteur X, ou une application mobile pour des jeunes adultes, etc.

## 3. Fonctionnalité principale

Décrire les fonctionnalités principales de la solution attendue. Cela comprend la liste des pages principales et les interactions de chaque page avec l’utilisateur.

### Exigences fonctionnelles
- **Page principale** : 
  - Présentation des services ou produits
  - Navigation claire et intuitive
- **Page portfolio** : 
  - Affichage des projets réalisés avec détails
  - Filtres de recherche pour naviguer dans le portfolio
- **Page contact** : 
  - Formulaire de contact simple et fonctionnel
  - Carte interactive pour localiser l’entreprise

## 4. Cas d'utilisation

Décrire les cas d’utilisation spécifiques pour la solution demandée. Il s'agit de scénarios décrivant comment les utilisateurs vont interagir avec le système.

### Exigences techniques
Le site doit être développé en utilisant les technologies suivantes :
- **HTML5** : Structuration sémantique du contenu, avec des balises modernes et accessibles.
- **CSS3** : Mise en forme et design responsive. Utilisation de Flexbox ou CSS Grid pour la mise en page, animations CSS3 pour améliorer l’expérience utilisateur.
- **JavaScript (JS)** : Fonctionnalités interactives côté client (formulaires dynamiques, animations, validation de données, etc.). Utilisation de bibliothèques ou frameworks JS comme jQuery ou Vue.js peut être envisagée pour faciliter le développement, en fonction des besoins du projet.

### User Stories
- **En tant qu’utilisateur**, je veux pouvoir consulter un portfolio de projets afin de mieux comprendre les services offerts.
- **En tant qu’utilisateur**, je veux pouvoir envoyer un message via le formulaire de contact pour poser des questions.

### Critères d'acceptation
- **Page principale** : La page d'accueil doit se charger en moins de 3 secondes.
- **Portfolio** : L’utilisateur peut filtrer les projets par catégorie.
- **Formulaire de contact** : Le formulaire doit valider les champs obligatoires avant envoi et afficher un message de confirmation après soumission.

## 5. Contraintes

### Contraintes légales et RGPD
- Le projet doit respecter les exigences du RGPD, en particulier la gestion des données personnelles des utilisateurs.
- Il doit y avoir un bouton pour accepter les cookies, ainsi qu'une politique de confidentialité claire et accessible.
- La gestion des droits d’auteur pour les images et les contenus présents sur le site ou l’application doit être conforme aux lois en vigueur.

### Autres contraintes
- Le site doit être compatible avec les navigateurs les plus courants (Chrome, Firefox, Safari, Edge).
- Les performances doivent être optimisées pour garantir une expérience fluide, notamment sur les appareils mobiles.

## 6. SEO (Optimisation pour les moteurs de recherche)

### Exigences SEO
- **Structure des URLs** : Les URLs doivent être claires, lisibles et inclure des mots-clés pertinents. Par exemple : `www.example.com/portfolio/nom-du-projet`.
- **Balises Meta** : Chaque page doit avoir une balise `title` et une balise `meta description` uniques et optimisées pour le référencement.
  - La **balise title** doit inclure les mots-clés principaux et être concise, entre 50 et 60 caractères.
  - La **meta description** doit fournir un résumé convaincant de la page, incluant les mots-clés, entre 150 et 160 caractères.
- **Balises d'en-tête** : Utilisation correcte des balises HTML (`<h1>`, `<h2>`, `<h3>`) pour structurer le contenu, avec des mots-clés dans les titres principaux et secondaires.
- **Contenu optimisé pour les moteurs de recherche** : Le contenu doit être pertinent et riche en mots-clés naturels, sans être surchargé, pour améliorer la visibilité dans les résultats de recherche.
- **Balises ALT pour les images** : Toutes les images doivent avoir des balises ALT descriptives, optimisées pour les mots-clés associés à chaque image.
- **Vitesse de chargement** : Le site doit se charger rapidement, idéalement en moins de 3 secondes, afin d'améliorer le classement SEO et l’expérience utilisateur.
- **Adaptabilité mobile** : Le site doit être entièrement responsive, ce qui est crucial pour le SEO mobile.
- **Maillage interne** : Créer des liens internes pertinents entre les pages du site pour améliorer la navigation et l’indexation par les moteurs de recherche.
- **Backlinks** : Mettre en place une stratégie pour obtenir des backlinks de qualité afin d’augmenter l’autorité du site.

### Outils SEO recommandés
- Google Search Console pour suivre les performances du site et détecter d'éventuelles erreurs d'indexation.
- Google Analytics pour analyser les visiteurs, leurs comportements et les sources de trafic.
- Outils d’audit SEO (comme SEMrush, Ahrefs ou Moz) pour surveiller et améliorer le SEO du site régulièrement.

## 7. Charte Graphique

La charte graphique définit l’identité visuelle du projet et doit être respectée afin d’assurer la cohérence et l’harmonisation des éléments graphiques.

### 7.1. Identité visuelle
- **Logo** : Le logo doit être utilisé conformément aux directives fournies (dimensions, couleur, espace libre autour du logo, etc.).
- **Typographie** : Utilisation des polices de caractères définies pour les titres, sous-titres, corps de texte et autres éléments. Exemple :
  - Titre principal : **Roboto Bold**, taille 32px
  - Corps de texte : **Roboto Regular**, taille 16px
  - Sous-titres : **Roboto Medium**, taille 24px
- **Couleurs** :
  - Couleur primaire : #1a73e8 (bleu)
  - Couleur secondaire : #ffffff (blanc)
  - Couleur d'accent : #f4f4f4 (gris clair)
  - Couleur de fond : #ffffff
  - Couleur de texte : #333333 (gris foncé)
- **Contraste et lisibilité** : S'assurer que tous les textes sont suffisamment contrastés par rapport aux fonds pour garantir une bonne lisibilité, en particulier sur les appareils mobiles.

### 7.2. Iconographie
- Utilisation d'icônes simples et modernes, sans surcharge graphique.
- Toutes les icônes doivent être cohérentes dans leur style (par exemple, toutes les icônes doivent avoir le même design plat ou linéaire).
- Chaque icône doit être accompagnée d’un texte explicatif ou d’un titre au survol pour améliorer l’accessibilité.

### 7.3. Design des éléments interactifs
- **Boutons** : Les boutons doivent être facilement identifiables avec des couleurs contrastées et un effet de survol (hover) distinct.
  - Boutons principaux : couleur bleue (#1a73e8) avec texte blanc.
  - Boutons secondaires : couleur gris clair (#f4f4f4) avec texte bleu (#1a73e8).
- **Formulaires** : Les champs de formulaire doivent être bien espacés, avec des bordures douces et un indicateur clair des champs obligatoires.

### 7.4. Mise en page
- **Grilles** : Utilisation d’une grille fluide avec un nombre de colonnes défini pour assurer une mise en page équilibrée.
- **Espaces blancs** : Le design doit inclure des espaces blancs suffisants pour que le contenu soit aéré et agréable à lire.
- **Alignement** : Les éléments doivent être alignés de manière cohérente pour garantir une bonne hiérarchisation de l’information.

### 7.5. Accessibilité
- **Contrastes** : Assurer un contraste suffisant entre le texte et le fond (rapport de contraste de 4.5:1 pour les textes normaux et 3:1 pour les textes de grande taille).
- **Navigation clavier** : Le site doit être accessible via un clavier, en respectant les normes d’accessibilité pour permettre une navigation fluide pour les personnes en situation de handicap.

### 7.6. Exemples visuels
- Fournir des maquettes (wireframes ou designs finaux) pour illustrer les concepts visuels définis dans la charte graphique. Ces exemples doivent inclure les pages principales et le style général attendu pour chaque type de contenu.
