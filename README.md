## Application de vente de fromages

### Description
Ce projet est une application de gestion de la vente de fromages. Il permet d'afficher différents types de fromages, d'ajouter des fromages à un panier et d'appliquer des filtres pour rechercher des fromages spécifiques. Le projet est construit avec Java et inclut des tests unitaires pour valider certaines fonctionnalités.

### Fonctionnalités
- Affichage de la liste des fromages disponibles avec leurs images.
- Filtrage des fromages par type ou par caractéristiques.
- Ajout de fromages dans un panier.
- Validation du panier et calcul du total.
  
### Structure du projet

- **Images des fromages** : Les images sont stockées dans le répertoire `src/main/resources/images/fromages/` avec des sous-dossiers selon les dimensions des images (par exemple, `hauteur40`, `hauteur100`, etc.).
  
- **Tests unitaires** : Des tests pour les fonctionnalités principales du modèle sont disponibles dans `src/test/java/modele/`, incluant :
  - `TestFiltreTypeDeFromage.java` : Teste la fonctionnalité de filtre par type de fromage.
  - `TestPanier.java` : Teste la gestion du panier d'achat.
  - `TestSaisieFromage.java` : Valide la saisie des fromages.

### Prérequis

- Java 8 ou plus récent
- Maven (pour la gestion des dépendances)

### Installation

1. Clonez le dépôt :

   ```bash
   git clone https://github.com/AirMaTy/Application-de-vente-de-fromage.git
   ```

2. Accédez au dossier du projet :

   ```bash
   cd Application-de-vente-de-fromage
   ```

3. Compilez et exécutez les tests avec Maven :

   ```bash
   mvn clean install
   ```

### Utilisation

Pour lancer l'application, exécutez la commande suivante après la compilation :

```bash
mvn exec:java
```

Cela démarrera l'application et vous permettra d'explorer les différents fromages, de filtrer les résultats et de gérer un panier d'achat.

### Contributions

Les contributions sont les bienvenues. Veuillez créer une *issue* avant de proposer des modifications importantes afin que nous puissions en discuter.

### Auteurs

- **Lacoste Maxime**
