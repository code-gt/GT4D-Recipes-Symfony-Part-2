# 🌟 TP : Créer une Application Symfony de Gestion de Recettes - Partie 2 !

Bienvenue dans la suite de ce TP ! 🎉 Vous avez déjà créé une base solide avec Symfony dans la première partie. Dans cette **deuxième partie**, vous allez enrichir votre application avec des fonctionnalités avancées : des formulaires interactifs, un système de connexion utilisateur sécurisé et une interface d'administration pour gérer vos données facilement. 🚀

## 🎯 Objectifs pédagogiques

* **Créer des formulaires Symfony** pour interagir avec les données de votre application.

* **Mettre en place un système d'authentification utilisateur** avec un accès sécurisé.

* **Utiliser EasyAdmin** pour ajouter une interface d'administration et gérer les utilisateurs et les recettes.

## 🛠️ Étapes de la Partie 2

### 🛡️ 1. Mettre en Place un Système de Connexion Utilisateur

* Créer une entité utilisateur.

* Configurer un système d'authentification.

* Protéger vos routes grâce au fichier `security.yaml`.

* Créer une page de connexion et d'inscription personnalisée.

### 🧩 1. Ajouter des Formulaires pour les Recettes

* Créer un formulaire Symfony pour les recettes et catégories. A vous de voir la forme que ça va prendre (deux formulaires séparés pour les deux entités, un seul formulaire, des champs select pour choisir parmis les catégories existantes etc...).

* Configurer le contrôleur pour traiter les formulaires.

* Créer les vue Twig pour le formulaire.

**Spécifications :** Commencez par faire un formulaire de création. Puis un formulaire de modification et une action pour pouvoir supprimer une recette. Seul un utilisateur **connecté** peut créer une recette, et il peut modifier et supprimer que ses propres recettes.

### ⚙️ 3. Ajouter une Interface d'Administration avec EasyAdmin

* Installer EasyAdmin.

* Configurer un tableau de bord.

* Générer des CRUD pour vos entités.

* Gérer les rôles utilisateurs dans `security.yaml`

* Tester l'interface admin (`/admin`);

## 💡 Exemple de Fonctionnalités à Implémenter

### Fonctionnalités attendues dans cette partie :

1. **Créer ou modifier une recette :**

    * Via des formulaires Symfony accessible à tous les utilisateurs connectés.

2. **Mettre en place un accès restreint :**

    * Les pages de création/modification des recettes doivent être accessibles uniquement aux utilisateurs authentifiés.

3. **Ajouter une interface d'administration :**

    * Gérer les recettes, catégories et utilisateurs depuis un tableau de bord admin.


## ✅ Livrables

À la fin de cette deuxième partie, vous devez avoir :

1. Un formulaire fonctionnel pour créer et modifier des recettes.

2. Un système de connexion utilisateur sécurisé.

3. Une interface admin pour gérer facilement vos données.

## 🏁 Mot de fin

Bravo d’avoir relevé ce défi ! 🎉 Vous avez maintenant une application Symfony complète, alliant backend robuste, fonctionnalités avancées, et administration simplifiée. Cette expérience est une véritable simulation de projet professionnel. Continuez à explorer Symfony et amusez-vous avec vos nouvelles compétences ! 👨‍💻👩‍💻