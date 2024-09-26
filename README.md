# Rust-journal :

## Commencer avec Rust :

**Question :**  
Quels types de projets allons-nous construire en apprenant Rust, et comment ces projets vont-ils m'aider à mieux comprendre les principes fondamentaux du langage ?

**Question :** 
Quelle est la différence entre 'Rustlings' et 'Rust by Example', et lequel serait le plus adapté pour un débutant qui souhaite apprendre à utiliser la syntaxe de Rust en ligne de commande ?

**Question :**
Est-ce que 'Rust by Example' est suffisant pour apprendre Rust de manière approfondie, ou devrais-je aussi lire le 'Book' pour bien comprendre les concepts théoriques du langage ?

## Maîtrisez Rust : 

**Question :** (Référence) :  
Si la Référence n'est pas une spécification formelle, en quoi est-elle plus utile que le 'Book' pour approfondir mes connaissances en Rust ?

**Question :** (Le Rustonomicon) :  
Quand et pourquoi devrais-je apprendre à utiliser Rust unsafe, et quelles sont les implications de son utilisation dans des projets réels ?

**Question :**(Le Unstable Book) : 
Qu'est-ce que les fonctionnalités instables de Rust, et quand devrais-je envisager d'utiliser les versions nightly pour les explorer ?

## le langage de programmation Rust :

## Avant-propos: 

1. Le langage de programmation Rust apporte plus de puissance et permet de programmer en toute confiance dans une plus grande diversité de domaines.

**Question :**
Comment Rust améliore-t-il la confiance des développeurs dans divers domaines de programmation ?

2. Rust simplifie la gestion des éléments au niveau système, traditionnellement complexe, en éliminant les pièges et en offrant des outils conviviaux.

**Question :**
Quels avantages Rust offre-t-il pour simplifier la gestion des éléments au niveau système ?   

3. Rust élimine les obstacles de la programmation bas niveau en offrant des outils sûrs et efficaces pour un code fiable.

**Question :**
Comment Rust rend-il la programmation bas niveau plus sûre et efficace ?

4. Rust permet aux développeurs bas niveau d'introduire du parallélisme avec une faible risque, grâce à un compilateur détectant les erreurs.

**Question :**
Comment Rust facilite-t-il l'introduction du parallélisme en minimisant les risques ?

5. Rust est suffisamment expressif pour rendre le développement agréable de divers types de code, avec des compétences transférables entre domaines.

**Question :** 
En quoi Rust est-il expressif et polyvalent pour différents types de développement ?

6. Ce livre exploite le potentiel de Rust pour améliorer les connaissances et les compétences des développeurs avec une documentation accessible.

**Question :**
Quel est l'objectif principal du livre concernant l'amélioration des compétences avec Rust ?


## Introduction :
Rust équilibre puissance et ergonomie pour permettre un contrôle des détails bas-niveau sans les soucis traditionnels.  
**Question :** Comment Rust équilibre-t-il puissance et ergonomie pour la gestion des détails bas-niveau ?

### À qui s'adresse Rust :
Rust est conçu pour divers groupes, notamment les équipes de développeurs, les étudiants, les entreprises, les développeurs de logiciels libres, et ceux qui recherchent rapidité et stabilité.  
**Question :** Quels groupes de personnes peuvent bénéficier de l'utilisation de Rust et pour quelles raisons ?

**1. Équipes de développeurs** :
Rust facilite la collaboration en détectant les bogues subtils, ce qui permet aux équipes de se concentrer sur la logique du programme plutôt que sur le débogage.  
**Question :** Comment Rust aide-t-il les équipes de développeurs à se concentrer sur la logique du programme plutôt que sur le débogage ?

**2. Outils modernes de développement** :
Rust propose des outils modernes comme Cargo, Rustfmt, et le Rust Language Server pour améliorer la productivité et la gestion du code système.  
**Question :** Quels outils modernes de développement Rust offre-t-il pour améliorer la productivité et la gestion du code ?

**3. Étudiants** :
Rust est accessible aux étudiants et aux débutants, offrant une communauté accueillante et des ressources pour apprendre les concepts système.  
**Question :** Comment Rust soutient-il les étudiants et les débutants dans l'apprentissage des concepts système ?

**4. Entreprises** :
De nombreuses entreprises utilisent Rust pour une variété de missions, allant des outils en ligne de commande aux systèmes embarqués et à l'apprentissage automatique.  
**Question :** Pour quelles missions variées les entreprises utilisent-elles Rust ?

**5. Développeurs de logiciel libre** :
Rust est ouvert aux contributions des développeurs intéressés par le développement du langage, des outils et des bibliothèques.  
**Question :** Quel est le rôle des développeurs dans la communauté Rust concernant le développement du langage et des outils ?

**6. Personnes recherchant rapidité et stabilité** :
Rust est conçu pour offrir à la fois rapidité et stabilité, en garantissant des performances élevées et des vérifications rigoureuses du code.  
**Question :** Comment Rust assure-t-il rapidité et stabilité dans le développement de logiciels ?

## À qui est destiné ce livre
Ce livre est destiné aux personnes ayant déjà écrit du code, sans présumer de leur langage de programmation précédent, et est conçu pour être accessible à divers niveaux d'expérience.  
**Question :** À quel public est destiné ce livre et quel est son niveau d'accessibilité ?

## Comment utiliser ce livre
Le livre doit être lu dans l'ordre, avec des chapitres théoriques et de projet, pour appliquer les connaissances acquises et construire des programmes pratiques.  
**Question :** Comment est structuré ce livre pour faciliter l'apprentissage de Rust ?

## Chapitres spécifiques
Le livre couvre l'installation de Rust, la création de programmes, les concepts théoriques et pratiques, avec des chapitres sur la gestion des erreurs, la généricité, les fermetures, et bien plus.  
**Question :** Quels sont les principaux sujets abordés dans les différents chapitres du livre ?

## Annexes
Les annexes fournissent des informations complémentaires sur le langage, les outils, et les éditions de Rust.  
**Question :** Que contiennent les annexes du livre concernant le langage Rust ?

## Messages d'erreur du compilateur
Comprendre les messages d'erreur du compilateur est crucial pour apprendre Rust, et le livre inclut des exemples avec les messages d'erreur correspondants pour guider les lecteurs.  
**Question :** Pourquoi est-il important de comprendre les messages d'erreur du compilateur en apprenant Rust ?


# 1. Prise en main 
## 1.1 installation :

### Installation de Rust

### Première étape : Installer Rust :

La première étape consiste à installer Rust via `rustup`, un outil en ligne de commande qui gère les versions de Rust et les outils associés. Une connexion Internet est requise pour le téléchargement. Si vous préférez ne pas utiliser `rustup`, consultez la page [Autres méthodes d'installation de Rust](https://www.rust-lang.org/tools/install) pour d'autres options.

 **Question :** Quelle est la méthode recommandée pour installer Rust et que faire si vous ne souhaitez pas utiliser `rustup` ?

### Installer la dernière version stable :

Il est recommandé d'installer la dernière version stable du compilateur Rust pour assurer la compatibilité avec les exemples du livre. Bien que les nouvelles versions puissent modifier légèrement les messages d'erreur et les avertissements, elles devraient fonctionner avec le contenu de ce livre.

 **Question :** Pourquoi est-il essentiel d'installer la dernière version stable de Rust pour suivre ce livre ?

## Notation en ligne de commande :

Les commandes tapées dans le terminal commenceront par `$`. Vous n'avez pas besoin de taper le `$`; il indique le début de la commande. Les lignes sans `$` montrent le résultat de la commande. Pour PowerShell, utilisez `>` à la place de `$`.

 **Question :** Quelle est la signification des symboles `$` et `>` dans les exemples de commandes du livre ?

### Sur Linux ou macOS :

1. Ouvrez un terminal.
2. Exécutez la commande suivante pour télécharger et installer `rustup` :

    ```bash
    $ curl --proto '=https' --tlsv1.2 https://sh.rustup.rs -sSf | sh
    ```

    Cette commande télécharge un script et lance l'installation de la dernière version stable de Rust. Si l'installation se passe bien, vous verrez le message :

    ```
    Rust is installed now. Great!
    ```

3. Vous aurez peut-être besoin d'un linker pour regrouper les résultats de compilation. Sur macOS, vous pouvez installer un compilateur C avec :

    ```bash
    $ xcode-select --install
    ```

    Les utilisateurs de Linux doivent installer GCC ou Clang, par exemple sur Ubuntu :

    ```bash
    $ sudo apt-get install build-essential
    ```
**Question :** :Quelle commande devez-vous exécuter pour installer rustup sur Linux ou macOS ?

### Sous Windows :

1. Rendez-vous sur [la page d'installation de Rust](https://www.rust-lang.org/tools/install) et suivez les instructions.
2. Pendant l'installation, vous devrez peut-être installer les outils de compilation C++ pour Visual Studio 2013 ou plus récent. La méthode recommandée est d'installer Build Tools pour Visual Studio 2019 en veillant à sélectionner les "Outils de compilation C++", le SDK Windows 10 et les paquets de langage Anglais.

**Question :**
Quelle version de Visual Studio est nécessaire pour installer Rust sous Windows ?

### Mettre à jour et désinstaller :

- Pour mettre à jour Rust à la dernière version :

    ```bash
    $ rustup update
    ```

- Pour désinstaller Rust et `rustup` :

    ```bash
    $ rustup self uninstall
    ```
**Question :**
Quelle commande permet de mettre à jour Rust vers la dernière version disponible ? 

### Dépannage :

- Pour vérifier si Rust est correctement installé, entrez la commande suivante :

    ```bash
    $ rustc --version
    ```

    Vous devriez voir un message du type :

    ```
    rustc x.y.z (abcabcabc yyyy-mm-dd)
    ```

- Si vous avez des problèmes, assurez-vous que Rust est présent dans votre variable d'environnement système `%PATH%`. Pour obtenir de l'aide, vous pouvez consulter le canal #beginners sur le Discord officiel de Rust, le forum d'utilisateurs, ou Stack Overflow.

**Question :**
Comment pouvez-vous vérifier que Rust est installé correctement ?


### Documentation en local :

- Pour ouvrir la documentation locale de Rust dans votre navigateur :

    ```bash
    $ rustup doc
    ```

    Utilisez cette documentation pour obtenir des informations sur les types et fonctions de la bibliothèque standard.

**Question :**
Quelle commande permet d'accéder à la documentation locale de Rust ?


# 1.2 Hello, World!


Lorsqu'on apprend un nouveau langage, il est de tradition d'écrire un petit programme qui écrit le texte "Hello, world!" à l'écran, donc c'est ce que nous allons faire !

 **Question :** Quelle est la première chose que l'on apprend généralement à faire dans un nouveau langage de programmation ?

### Hello, World! 
Maintenant que vous avez installé Rust, écrivons notre premier programme Rust. Lorsqu'on apprend un nouveau langage, il est de tradition d'écrire un petit programme qui écrit le texte "Hello, world!" à l'écran, donc c'est ce que nous allons faire !

**Question :** Quel est l'objectif d'écrire un programme "Hello, world!" lors de la découverte d'un nouveau langage de programmation ?

## Créer un dossier projet
Nous allons commencer par créer un dossier pour y ranger le code Rust. Là où vous mettez votre code n'est pas important pour Rust, mais pour les exercices et projets de ce livre, nous vous suggérons de créer un dossier `projects` dans votre dossier utilisateur et de ranger tous vos projets là-dedans.

Ouvrez un terminal et écrivez les commandes suivantes pour créer un dossier `projects` et un dossier pour le projet “Hello, world!” à l'intérieur de ce dossier `projects`.

#### Sous Linux, macOS et PowerShell sous Windows :
```bash
$ mkdir ~/projects
$ cd ~/projects
$ mkdir hello_world
$ cd hello_world
```
#### Avec CMD sous Windows, écrivez ceci  :

- mkdir "%USERPROFILE%\projects"
- cd /d "%USERPROFILE%\projects"
- mkdir hello_world
- cd hello_world

## Écrire et exécuter un programme Rust :

Créez un fichier `main.rs` avec le code pour afficher "Hello, world!". Compilez et exécutez le programme avec `rustc` et le fichier exécutable résultant, selon votre système d'exploitation.

**Question :** Quelle commande permet de compiler un programme Rust ?

## Structure d'un programme Rust :

En Rust, la fonction `main` est le point d'entrée du programme. Elle est définie avec des accolades `{}` et n'a ni paramètres ni valeur de retour. Les macros, comme `println!`, sont utilisées pour afficher du texte et se distinguent des fonctions classiques par l'utilisation d'un point d'exclamation `!`. Les instructions se terminent par un point-virgule `;`.

**Question :** Quelle est la fonction spéciale utilisée comme point d'entrée dans un programme Rust ?


## La compilation et l'exécution sont des étapes séparées

En Rust, compiler et exécuter sont deux étapes distinctes. Pour compiler, vous utilisez la commande `rustc`, qui génère un fichier binaire exécutable. Ce fichier peut être exécuté sans que Rust soit installé sur la machine. Contrairement aux langages dynamiques comme Python ou JavaScript, où l'exécution est directe, Rust exige la compilation. Cela permet de distribuer des exécutables sans dépendances supplémentaires. La commande de compilation produit aussi des fichiers auxiliaires, comme des fichiers de débogage sous Windows.

**Question :**  Pourquoi Rust sépare-t-il les étapes de compilation et d'exécution, et comment cela diffère-t-il des langages dynamiques comme Python ?

# 1.3 Hello, cargo!

Cargo est l'outil de gestion de projets et de paquets de Rust. Il permet de compiler le code, gérer les dépendances et télécharger automatiquement les bibliothèques nécessaires. Il s'installe automatiquement avec Rust et est largement utilisé par la communauté Rust.

**Question :** Quelles sont les principales fonctions de Cargo dans la gestion des projets Rust ?

### Créer un projet avec Cargo

Cargo facilite la création et la gestion de projets en Rust. En exécutant la commande `cargo new`, il génère automatiquement la structure de fichiers nécessaire, y compris un fichier `Cargo.toml` pour les configurations et un dossier `src` pour le code source. De plus, Cargo prend en charge l'intégration avec Git, générant un dépôt Git par défaut lors de la création d'un nouveau projet. Il aide également à maintenir un projet bien structuré, séparant le code source des fichiers de configuration et de gestion de projet.
**Question :** Quels sont les principaux avantages d'utiliser Cargo pour créer et structurer un projet Rust ?

### Compiler et exécuter un projet Cargo

Cargo facilite la compilation et l'exécution des projets Rust avec des commandes simples comme `cargo build` pour compiler et `cargo run` pour compiler et exécuter. Il crée un fichier exécutable dans le dossier `target/debug` et permet de vérifier le code sans générer d'exécutable grâce à `cargo check`. Cette approche optimise le développement en séparant la compilation de l'exécution et en accélérant les vérifications.

**Question :** Pourquoi `cargo check` est-il souvent préféré à `cargo build` pendant le développement, même s'il ne produit pas d'exécutable ?

### Compiler pour diffuser

Lorsque le projet est prêt pour la diffusion, utilisez `cargo build --release` pour créer une version optimisée de votre programme, qui sera placée dans le dossier `target/release`. Cette version est plus rapide à l'exécution, mais le temps de compilation est plus long. Rust propose deux profils : un pour le développement (rapide mais non optimisé) et un pour la diffusion (plus long à compiler, mais avec des optimisations).

**Question :** Quel est l'avantage d'utiliser `cargo build --release` par rapport à `cargo build` lors de la diffusion d'un projet ?


### Cargo comme convention

Cargo devient particulièrement utile pour gérer des projets complexes composés de plusieurs crates, en automatisant la coordination de la compilation. Même pour des projets simples comme "hello_cargo", il pose les bases de l'outillage que vous utiliserez fréquemment dans vos projets Rust. Pour travailler sur un projet existant, il suffit de le cloner avec Git, de se rendre dans le dossier du projet et de le compiler avec Cargo. Vous pouvez consulter sa [documentation](https://doc.rust-lang.org/cargo/) pour plus de détails.

**Question :** Pourquoi est-il préférable d'utiliser Cargo plutôt que `rustc` pour des projets Rust complexes ?

### Résumé 

Dans ce chapitre, on a appris à :

- Installer et mettre à jour Rust avec rustup.
- Accéder à la documentation locale.
- Écrire et exécuter un programme simple avec rustc.
- Créer et exécuter un projet en utilisant Cargo.

Le moment est maintenant propice pour aborder un projet plus ambitieux. Dans le chapitre 2, on développera un jeu de devinettes. Pour explorer d'abord les principes de programmation, on peut consulter le chapitre 3 avant de revenir au chapitre 2.

**Question :** Quelles sont les principales différences entre l'utilisation de rustc et Cargo pour compiler et exécuter un programme Rust ?


# 2. Programmer le jeu du plus ou du moins

Dans ce chapitre, on se lance dans la création d'un projet concret : le jeu du plus ou du moins. Ce jeu consiste à tirer au sort un nombre entre 1 et 100, puis à inviter le joueur à deviner ce nombre. Selon la saisie du joueur, le programme indiquera si le nombre est trop grand, trop petit ou correct, et affichera un message de félicitations si le joueur trouve le bon nombre. Ce projet permet d'explorer plusieurs concepts fondamentaux de Rust, tels que les instructions `let` et `match`, les méthodes et fonctions associées, ainsi que l'utilisation des crates.


**Question :** Quels concepts fondamentaux de Rust seront explorés lors de la création du jeu du plus ou du moins ?

### Mise en Place d'un Nouveau Projet

Pour commencer un nouveau projet en Rust, il faut d'abord naviguer dans le dossier de travail souhaité, puis utiliser Cargo pour initialiser le projet. La commande `cargo new` crée un dossier avec le nom du projet, ici "jeu_du_plus_ou_du_moins", et la commande `cd` permet de se déplacer dans ce dossier.

Cargo génère automatiquement un fichier de configuration `Cargo.toml`, qui contient des informations sur le paquet, telles que son nom, sa version et les dépendances nécessaires. De plus, un fichier source `main.rs` est créé avec un programme de base affichant "Hello, world!".

Pour compiler et exécuter le programme, on utilise la commande `cargo run`, qui compile le code et lance l'exécutable en une seule opération. Cela facilite le développement en permettant de tester rapidement les modifications apportées au code.

À ce stade, il est conseillé d'ouvrir le fichier `src/main.rs`, car c'est dans ce fichier que l'ensemble du code du projet sera écrit.

**Question:** Pourquoi est-il avantageux d'utiliser Cargo pour gérer un projet Rust par rapport à la compilation manuelle avec `rustc` ?

### Traitement d'un Nombre Saisi

La première étape du programme consiste à demander au joueur de saisir un nombre et à traiter cette saisie. Le programme importe la bibliothèque d'entrée/sortie `std::io` pour permettre l'interaction avec l'utilisateur. 

Il affiche un message invitant le joueur à deviner un nombre, puis lui demande de saisir son nombre. La saisie est stockée dans une variable mutable `supposition` et affichée ensuite.

#### Points Clés
- **Importation de `std::io`** : Nécessaire pour les entrées/sorties.
- **Fonction `main`** : Point d'entrée du programme.
- **Utilisation de `println!`** : Affichage des messages pour guider l'utilisateur.

Ce processus prépare le programme à gérer les interactions futures avec le joueur.

**Question:** Pourquoi est-il essentiel de traiter les saisies utilisateur dans un programme ?

### Enregistrer des Données dans des Variables

Dans cette section, on apprend à créer une variable pour stocker la saisie de l'utilisateur. L'instruction `let` est utilisée pour déclarer des variables en Rust, qui sont immuables par défaut. Pour rendre une variable mutable, on ajoute `mut` devant son nom. Les commentaires peuvent être ajoutés pour expliquer le code et sont ignorés par le compilateur.

La variable créée pour stocker la saisie contient une nouvelle instance de type `String`, initialisée comme une chaîne vide. Cela permet au programme de commencer à traiter les entrées de l'utilisateur.

**Question:** Pourquoi est-il important de savoir si une variable peut être modifiée ou non dans un programme ?

### Recueillir la Saisie Utilisateur

Dans cette section, on utilise la fonction `stdin` du module `io` pour traiter la saisie de l'utilisateur, après avoir importé les fonctionnalités d'entrée/sortie de la bibliothèque standard. La méthode `read_line` est ensuite appelée sur l'entrée standard pour stocker la saisie de l'utilisateur dans la variable `supposition`.

Pour permettre à `read_line` de modifier le contenu de la variable, il est nécessaire de passer une référence mutable à cette variable. L'utilisation des références en Rust permet de partager des données sans duplication en mémoire, tout en maintenant la sécurité de l'accès. Par défaut, les références sont immuables, d'où la nécessité de spécifier `&mut` pour indiquer que la variable peut être modifiée.

**Question:** Quelle est l'importance de l'utilisation des références mutables lors de la gestion des saisies utilisateur en Rust ?

### Gérer les Erreurs Potentielles avec le Type Result

Dans cette section, on aborde la gestion des erreurs lors de la saisie utilisateur en utilisant le type `Result`. En ajoutant la méthode `expect` après `read_line`, on permet de signaler une erreur si la saisie échoue. Le type `Result`, qui est une énumération, contient deux variantes : `Ok`, qui indique le succès de l'opération, et `Err`, qui représente une erreur.

Si `read_line` retourne `Err`, l'appel à `expect` entraînera l'arrêt du programme tout en affichant un message d'erreur personnalisé. Si `Ok` est retourné, `expect` récupère la valeur contenue dans `Ok`. Cela permet de gérer les erreurs potentielles et d'éviter les avertissements du compilateur concernant l'utilisation d'un `Result` non exploité.

**Question:** Pourquoi est-il important de gérer les erreurs potentielles dans un programme, et quel rôle joue le type `Result` dans cette gestion ?

### Afficher des valeurs grâce aux espaces réservés de println!

La ligne `println!("Votre nombre : {}", supposition);` sert à afficher la chaîne de caractères qui contient la saisie de l'utilisateur. Les accolades `{}` agissent comme des espaces réservés pour les valeurs à afficher. On peut utiliser plusieurs paires d'accolades pour afficher plusieurs valeurs en une seule commande. Par exemple, dans le code suivant, `println!("x = {} et y = {}", x, y);`, les valeurs de `x` et `y` seront affichées respectivement dans les espaces réservés, produisant le résultat `x = 5 et y = 10`.

**Question:** Pourquoi est-il important d'utiliser des espaces réservés lors de l'affichage de valeurs en Rust ?

### Test de la première partie

Le programme est testé en exécutant la commande `cargo run`, ce qui permet d'afficher des messages demandant à l'utilisateur de saisir un nombre. Après la saisie, le nombre est affiché à l'écran, indiquant que cette première partie du programme est terminée.

**Question:** Quel est l'impact de l'affichage de la saisie utilisateur sur l'interaction avec le programme ?

### Générer le nombre secret

Pour rendre le jeu plus amusant, il est nécessaire de générer un nombre secret aléatoire que le joueur doit deviner, ce nombre variant à chaque partie. Ce nombre sera compris entre 1 et 100 pour garder le jeu accessible. Bien que Rust ne propose pas de fonctionnalités de génération de nombres aléatoires dans sa bibliothèque standard, il existe une crate appelée `rand` qui permet d'implémenter cette fonctionnalité.

**Question:** Pourquoi est-il important que le nombre secret change à chaque partie du jeu ?

### Étendre les fonctionnalités de Rust avec une crate

Une crate est un ensemble de fichiers de code Rust. Notre projet est une crate binaire, tandis que `rand` est une crate de bibliothèque. Pour l'utiliser, nous devons l'ajouter comme dépendance dans le fichier `Cargo.toml`, en spécifiant la version souhaitée.

Après avoir ajouté cette dépendance, nous exécutons `cargo build` pour télécharger et compiler `rand` ainsi que ses dépendances, tout en compilant notre projet. Si le code source n'est pas modifié, Cargo ne recompilera pas les dépendances lors des compilations ultérieures.

**Question:** Pourquoi est-il important de gérer les dépendances dans un projet Rust ?

 
### Assurer la reproductibilité des compilations avec le fichier Cargo.lock

Cargo garantit la reproductibilité des compilations en utilisant un fichier `Cargo.lock`, qui consigne les versions précises des dépendances utilisées lors de la première compilation. Si une nouvelle version d'une dépendance est publiée (par exemple, `rand` version 0.8.4), le fichier `Cargo.lock` préserve la version antérieure (0.8.3) jusqu'à ce qu'une mise à jour explicite soit effectuée.

Lors de compilations ultérieures, Cargo se réfère à `Cargo.lock` pour utiliser les versions spécifiées, évitant ainsi des régressions potentielles. Cela assure que le projet reste stable et que les compilations sont reproductibles.

**Question:** Quel rôle joue le fichier `Cargo.lock` dans la gestion des dépendances d'un projet Rust ?

### Mettre à jour une crate vers sa nouvelle version

Pour mettre à jour une crate, Cargo propose la commande `cargo update`, qui ignore le fichier `Cargo.lock` et recherche toutes les versions correspondantes dans `Cargo.toml`. Par défaut, cette commande se limite aux versions supérieures à 0.8.3 et inférieures à 0.9.0. Si de nouvelles versions comme 0.8.4 et 0.9.0 de la crate `rand` sont disponibles, `cargo update` mettra à jour vers 0.8.4, en ignorant 0.9.0.

Pour utiliser une version spécifique, comme 0.9.0, il faut modifier `Cargo.toml` en conséquence. Ensuite, lors du prochain `cargo build`, Cargo mettra à jour ses dépendances en fonction de la version spécifiée.

Cargo simplifie la gestion des dépendances et la réutilisation des bibliothèques, permettant aux développeurs de créer des projets avec des paquets variés.

**Question:** Comment la commande `cargo update` affecte-t-elle le fichier `Cargo.lock` et les dépendances d'un projet ?

### Générer un nombre aléatoire

Nous allons maintenant utiliser la crate `rand` pour générer un nombre à deviner. Dans `src/main.rs`, nous ajoutons le trait `Rng` pour accéder aux méthodes des générateurs de nombres aléatoires. La fonction `rand::thread_rng()` nous fournit un générateur de nombres aléatoires spécifique à l'exécution, et nous utilisons `gen_range(1..101)` pour obtenir un nombre entre 1 et 100. 

Le code affiche également le nombre secret, ce qui est utile pour les tests mais sera retiré dans la version finale pour rendre le jeu authentique. 

En lançant le programme plusieurs fois, on observe des nombres différents entre 1 et 100, comme prévu. Cela confirme que l'intégration de la fonctionnalité de génération de nombres aléatoires fonctionne correctement.

**Question:** Comment la méthode gen_range assure-t-elle que les nombres générés respectent les limites définies (inclusives et exclusives) dans l'intervalle ?

### Comparer le nombre saisi au nombre secret 


Dans cette étape, nous avons introduit la comparaison entre le nombre saisi par l'utilisateur et le nombre secret généré aléatoirement. Pour cela, nous avons utilisé le type `Ordering` de la bibliothèque standard de Rust, qui permet de déterminer si le nombre saisi est inférieur, supérieur ou égal au nombre secret. La méthode `cmp` compare les deux valeurs, et en fonction du résultat, nous affichons un message indiquant si le nombre est plus, moins, ou si l'utilisateur a gagné.

Cependant, nous avons rencontré un problème de types lors de la compilation. La saisie de l'utilisateur est d'abord stockée en tant que chaîne de caractères (String), tandis que le nombre secret est un entier. Pour résoudre ce problème, nous avons converti la saisie de l'utilisateur en un nombre entier (`u32`), ce qui permet la comparaison. Nous avons utilisé la méthode `trim()` pour enlever les espaces superflus, et `parse()` pour convertir la chaîne en un nombre.

**Question:** Pourquoi est-il important de gérer les types lors de la comparaison de valeurs dans un langage de programmation typé comme Rust ?

### Permettre plusieurs suppositions avec les boucles

Dans cette étape, nous avons introduit une boucle infinie à l'aide du mot-clé `loop` pour permettre aux utilisateurs de faire plusieurs suppositions dans le jeu. Nous avons déplacé tout le code qui demande à l'utilisateur d'entrer un nombre à l'intérieur de cette boucle. Cela permet au programme de continuer à demander un nombre tant que l'utilisateur ne devine pas le nombre secret.

Cependant, cette approche présente un inconvénient : le programme continuera de s'exécuter indéfiniment sans moyen évident pour l'utilisateur de quitter.
Si l'utilisateur entre une valeur qui n'est pas un nombre, le programme se bloque et affiche une erreur. Pour améliorer cette fonctionnalité, il serait souhaitable d'arrêter le jeu lorsque l'utilisateur devine correctement le nombre secret ou s'il souhaite quitter le jeu.

**Question:** Comment pourrait-on améliorer l'expérience utilisateur en ajoutant des options pour quitter le jeu ou pour gérer les erreurs de saisie sans que le programme ne se bloque ?

### Arrêter le programme après avoir gagné

Pour améliorer notre jeu de devinette, nous avons ajouté une instruction `break` dans la boucle de jeu afin de permettre au programme de s'arrêter lorsque le joueur devine correctement le nombre secret. En plaçant cette instruction à la suite de l'affichage du message "Vous avez gagné !", nous garantissons que le programme sortira de la boucle et se terminera, ce qui améliore l'expérience utilisateur en évitant une boucle infinie après une victoire.

**Question:**  Quels autres moyens pourrait-on envisager pour améliorer l'interaction avec l'utilisateur dans le jeu, par exemple en offrant des options pour recommencer ou quitter le jeu après une victoire ?

### Gérer les saisies invalides

Pour rendre le **jeu de devinette** plus convivial, nous avons modifié la **gestion des saisies invalides**. Au lieu de faire planter le programme lorsque l'utilisateur entre quelque chose qui n'est pas un nombre, nous utilisons une **expression `match`** pour gérer les erreurs. Si la saisie peut être convertie en nombre, elle est utilisée pour la **comparaison**. Sinon, le programme continue et demande une nouvelle saisie. Cela permet à l'utilisateur de poursuivre ses tentatives sans interruption.

**Question:** Comment pourrait-on améliorer l'interface utilisateur pour donner des indications sur les plages de nombres valides ou sur les erreurs de saisie ?

### Résumé de ce chapitre : 

 Ce projet vous a permis de vous familiariser avec de nombreux concepts de Rust, notamment l'utilisation de `let`, `match`, les méthodes, les fonctions associées et les crates externes.

Dans les prochains chapitres, vous approfondirez ces concepts. Le chapitre 3 abordera des éléments essentiels comme les variables, les types de données et les fonctions en Rust. Le chapitre 4 se concentrera sur la possession (ownership), une fonctionnalité qui distingue Rust des autres langages. Le chapitre 5 traitera des structures et de la syntaxe des méthodes, tandis que le chapitre 6 expliquera comment les énumérations fonctionnent.

**Question:** Quels concepts aimeriez-vous approfondir davantage dans les chapitres suivants ?


# 3. Les concepts courants de programmation

Ce chapitre traite des concepts fondamentaux présents dans presque tous les langages de programmation, tels que les variables, les types de base, et les fonctions, en les appliquant spécifiquement à Rust. Comprendre ces notions vous fournira une base solide pour commencer à programmer en Rust.

**Question:** Quel concept vous semble le plus crucial à maîtriser en premier pour bien débuter avec Rust ?

# 3.1 Les variables et la mutabilité

Dans ce chapitre, nous abordons la notion d'immuabilité des variables en Rust, qui est une caractéristique essentielle pour garantir la sécurité et éviter les bogues. Par défaut, les variables sont immuables, signifiant que leur valeur ne peut pas être modifiée après leur déclaration. Si vous essayez de changer une valeur immuable, le compilateur renverra une erreur. 

Pour permettre la modification d'une variable, il suffit d'ajouter le mot clé `mut` lors de sa déclaration. Cela aide non seulement à éviter les erreurs de compilation, mais indique également aux lecteurs du code que la variable est destinée à être modifiée. L'immuabilité favorise la sécurité du code, tandis que la mutabilité, quand elle est utilisée à bon escient, peut améliorer la performance et la clarté.

**Question:** Pourquoi Rust encourage-t-il l'utilisation de variables immuables par défaut, et quelles sont les situations dans lesquelles vous pourriez préférer utiliser des variables mutables ?

### Les constantes

Les constantes en Rust sont des valeurs immuables qui ne peuvent pas être modifiées et doivent être déclarées avec le mot clé `const`, en indiquant toujours leur type. Elles peuvent être définies à n'importe quel endroit du code et doivent résulter d'expressions constantes, ce qui les rend utiles pour des valeurs partagées tout au long d'un programme. Les constantes améliorent la clarté du code et facilitent les modifications futures.

**Question:** Quelles sont les avantages d'utiliser des constantes plutôt que des variables immuables dans un programme Rust ?

### Le masquage 

Le masquage en Rust permet de déclarer une nouvelle variable avec le même nom qu'une variable existante, masquant ainsi la valeur de la première par celle de la seconde. Cela se fait en utilisant le mot-clé `let` et permet de modifier la valeur ou le type sans provoquer d'erreurs, contrairement à l'utilisation de `mut`, qui ne permet pas de changer le type d'une variable. Le masquage est utile pour simplifier les noms de variables et éviter la confusion dans le code.

**Question:**  Quelle est la principale différence entre le masquage d'une variable et l'utilisation de `mut` dans Rust ?

# 3.2 Les types de données

En Rust, chaque valeur possède un type qui indique au compilateur comment manipuler et traiter les données. Le langage est statiquement typé, ce qui signifie que tous les types doivent être connus au moment de la compilation. Le compilateur peut souvent déduire le type d'une variable, mais dans certains cas, comme lors de la conversion de types, une annotation explicite est nécessaire pour éviter des erreurs de compilation.

**Question:** Pourquoi le compilateur Rust peut-il nécessiter une annotation de type dans certains cas ?

### Types scalaires

Les types scalaires en Rust représentent des valeurs uniques et incluent les entiers, les nombres à virgule flottante, les booléens et les caractères.
**Question:** Quels sont les quatre types principaux de scalaires en Rust ?

#### Types de nombres entiers
Les nombres entiers en Rust peuvent être signés (i) ou non signés (u) et varient en taille (8, 16, 32, 64, 128 bits ou dépendant de l'architecture avec isize/usize). Les entiers signés permettent des valeurs négatives, tandis que les non signés sont toujours positifs. Rust propose divers littéraux pour écrire des entiers et gère les dépassements d'entiers différemment selon le mode de compilation : en mode débogage, le programme panique, tandis qu'en mode publication, un rebouclage du complément à deux se produit.

**Question:** Comment Rust gère-t-il un dépassement d'entier en mode débogage et en mode publication ?

#### Types de nombres à virgule flottante

Rust propose deux types de nombres à virgule flottante : f32 (32 bits) et f64 (64 bits), ce dernier étant le type par défaut pour sa précision et sa rapidité sur les processeurs modernes. Les nombres à virgule flottante en Rust suivent la norme IEEE-754 et peuvent être utilisés avec un signe.

**Question:** Quelle est la différence principale entre les types de nombres flottants f32 et f64 en Rust ?

#### Les opérations numériques

Rust propose les opérations mathématiques de base (addition, soustraction, multiplication, division, modulo) pour tous les types de nombres, avec des résultats arrondis pour les divisions d'entiers.

**Question:** Quelle est la particularité de la division d'entiers en Rust par rapport à la division de nombres à virgule flottante ?

#### Le type booléen

En Rust, le type booléen (`bool`) possède deux valeurs possibles : `true` et `false`, et il est principalement utilisé dans les structures conditionnelles comme `if`.

**Question:** Quel est le rôle principal des valeurs booléennes dans les programmes Rust ?

#### Le type caractère

Le type `char` en Rust représente un caractère Unicode et occupe quatre octets en mémoire. Il peut représenter des lettres, des symboles, et des emojis, allant bien au-delà de l'ASCII.

**Question:** Quelle est la taille en mémoire du type `char` en Rust, et que peut-il représenter au-delà des caractères ASCII ?

### Le type composé 

Les types composés en Rust permettent de regrouper plusieurs valeurs dans un seul type. Les tuples, qui peuvent contenir des valeurs de types différents, sont créés avec des parenthèses et des virgules. Ils ont une taille fixe et permettent l'accès à leurs éléments soit par déstructuration, soit par index. Le type unité `()` est un tuple sans valeur, représentant une seule valeur.

**Question:** Comment accède-t-on aux éléments d'un tuple en Rust, et que représente le type unité `()` ?

### Le type tableau

Les tableaux en Rust sont des collections de valeurs de même type, de taille fixe. Ils sont définis entre crochets et peuvent être initialisés avec des valeurs spécifiques ou avec une valeur répétée. On accède aux éléments d'un tableau par indexation, mais une tentative d'accès à un indice hors limites provoquera une erreur d'exécution. Rust effectue des vérifications pour garantir la sécurité de la mémoire.

**Question:** Quelle est la différence principale entre un tableau et un tuple en Rust, et que se passe-t-il si vous essayez d'accéder à un indice en dehors des limites d'un tableau ?

# 3.3 Les fonctions

Les fonctions jouent un rôle crucial en Rust en organisant le code. La fonction main est le point d'entrée principal des programmes. Elles se définissent avec le mot-clé fn, suivi du nom et des parenthèses. Les fonctions peuvent accepter des paramètres, qui doivent être typés, ce qui aide le compilateur à comprendre le type des données utilisées.

**Question:** Pourquoi est-il important de déclarer le type de chaque paramètre dans la signature d'une fonction en Rust ?

### Les paramétres 

Les paramètres dans les fonctions sont des variables qui font partie de leur signature, permettant de passer des valeurs concrètes, appelées arguments. Chaque paramètre doit avoir un type déclaré, ce qui aide le compilateur à comprendre le type de données que la fonction manipule. Lorsqu'on définit plusieurs paramètres, ils sont séparés par des virgules.

**Question:** Les paramètres sont des variables dans la signature d'une fonction, permettant de passer des valeurs concrètes, appelées arguments, lors de l'appel de la fonction. Pourquoi est-il important de déclarer le type de chaque paramètre dans Rust ?

### Instructions et expressions

En Rust, le corps des fonctions se compose d'instructions et d'expressions. 

- **Instructions** : 
  - Elles réalisent des actions sans retourner de valeur. Par exemple, la déclaration de variables avec `let` est une instruction.
  - Les instructions ne peuvent pas être utilisées comme des valeurs dans d'autres expressions.

- **Expressions** : 
  - Elles peuvent faire partie d'instructions et sont évaluées pour produire une valeur.
  - Les expressions incluent des opérations mathématiques et des blocs de code délimités par des accolades, à condition que la dernière ligne ne se termine pas par un point-virgule.


**Question:** Quelle est l'importance de distinguer entre instructions et expressions lors de l'écriture de fonctions en Rust ?

### Les fonctions qui retournent des valeurs

En Rust, les fonctions peuvent retourner des valeurs, dont le type doit être spécifié après une flèche (->). La valeur de retour correspond généralement à la dernière expression du corps de la fonction. Bien que le mot-clé `return` permette de sortir d'une fonction prématurément en spécifiant une valeur, la plupart des fonctions retournent implicitement la dernière expression. Si un point-virgule est ajouté à la fin d'une expression, cela transforme l'expression en instruction, ce qui peut provoquer une erreur si la fonction est censée retourner une valeur.


**Question:** Comment Rust gère-t-il les valeurs de retour d'une fonction lorsque celle-ci n'a pas de paramètres ?

# 3.4 Les commentaires

Les commentaires sont essentiels pour clarifier le code et le rendre plus compréhensible. En Rust, les commentaires à une seule ligne commencent par deux barres obliques (//) et se poursuivent jusqu'à la fin de la ligne. Pour les commentaires multi-lignes, il faut utiliser deux barres obliques au début de chaque ligne. Les commentaires peuvent également être ajoutés à la fin d'une ligne de code ou être placés au-dessus du code qu'ils expliquent.

**Question:** Comment les commentaires améliorent-ils la lisibilité du code et en quoi diffèrent-ils des commentaires de documentation en Rust ?

# 3.5 Les structures de contrôle

Les deux structures de contrôle principales qui permettent cela sont les expressions `if` et les boucles. Ces constructions sont essentielles dans la plupart des langages de programmation.

**Question:** Quelles sont les principales différences entre les expressions conditionnelles et les boucles en Rust ?

### Les expressions if

Les expressions `if` en Rust permettent de structurer le code en fonction de conditions. Vous spécifiez une condition et indiquez ce qui doit se produire si cette condition est remplie. Par exemple, si la condition est vérifiée, un certain bloc de code s'exécute ; sinon, ce bloc est ignoré.

Lorsque vous écrivez une expression `if`, elle commence par le mot-clé `if`, suivi de la condition à évaluer. Un bloc de code entre accolades suit la condition pour spécifier ce qui doit être exécuté si la condition est vraie. Il est également possible d'ajouter un bloc `else` pour gérer le cas où la condition n'est pas remplie.

Par exemple, avec une variable `nombre`, si sa valeur est inférieure à 5, un message indiquant que la condition est vérifiée sera affiché ; sinon, un message indiquant que la condition n'est pas vérifiée sera affiché. Si la condition n'est pas un booléen, une erreur se produira, car Rust ne réalise pas de conversion automatique des types.

**Question:** Comment pouvez-vous modifier une expression if pour qu'elle fonctionne avec des valeurs autres que des booléens en Rust ?
 
#### Gérer plusieurs conditions avec else if

En Rust, vous pouvez gérer plusieurs conditions en combinant les expressions `if`, `else if` et `else`. Cela vous permet de tester plusieurs conditions de manière séquentielle. Par exemple, dans un programme, si vous avez une variable `nombre`, vous pouvez vérifier si elle est divisible par 4, 3 ou 2, et afficher un message correspondant.

Lors de l'exécution, Rust évalue chaque condition dans l'ordre et exécute le bloc de code associé à la première condition qui est vraie. Une fois qu'une condition est satisfaite, les autres ne sont plus vérifiées. Ainsi, même si une condition plus basse dans la chaîne pourrait être vraie, elle ne sera pas exécutée si une condition précédente a déjà été validée.

Cependant, il est à noter qu'utiliser trop d'expressions `else if` peut rendre le code encombré. Dans des cas complexes avec de nombreuses conditions, il peut être préférable d'explorer d'autres constructions, comme `match`, qui offre une alternative plus propre pour gérer plusieurs chemins.

**Question:** Quelle est la différence entre utiliser `else if` et une expression `match` pour gérer des conditions en Rust ?

#### Utiliser if dans une instruction let

En Rust, comme `if` est une expression, vous pouvez l'utiliser pour assigner une valeur à une variable au moment de la déclaration avec `let`. Par exemple, en utilisant une condition, vous pouvez affecter à une variable `nombre` soit la valeur `5`, soit la valeur `6`, en fonction de la condition évaluée.

Lorsque vous exécutez le code, la valeur de `nombre` dépend du bloc de l'expression `if` qui est exécuté. Il est essentiel que les valeurs retournées par les blocs `if` et `else` soient du même type, car Rust exige une cohérence de type lors de l'assignation.

Si les types des résultats des branches `if` et `else` ne correspondent pas, vous obtiendrez une erreur de compilation, indiquant que les types sont incompatibles. Cela garantit que la variable a un type unique et prévisible à la compilation, permettant ainsi au compilateur d'assurer la sécurité et la robustesse du code.

**Question:** Pourquoi Rust exige-t-il que les branches d'une expression `if` retournent des types compatibles lors de l'assignation à une variable ?

### Les répétitions avec les boucles

En Rust, il peut être nécessaire d'exécuter un bloc de code plusieurs fois. Pour ce faire, Rust propose trois types de boucles : `loop`, `while`, et `for`. Chacune de ces boucles permet de répéter l'exécution du code contenu dans leur corps jusqu'à ce qu'une certaine condition soit remplie ou jusqu'à ce que la boucle soit explicitement interrompue.

Pour explorer ces boucles, vous pouvez créer un nouveau projet appelé `loops` et essayer chacune de ces constructions. 

#### Types de boucles :
- **loop** : exécute indéfiniment le bloc de code jusqu'à ce qu'il soit interrompu par une instruction `break`.
- **while** : continue d'exécuter le bloc tant qu'une condition est vraie.
- **for** : itère sur une collection ou une plage de valeurs, exécutant le bloc pour chaque élément.

**Question:** Dans quel cas serait-il préférable d'utiliser une boucle `for` plutôt qu'une boucle `while` ?

#### Répéter du code avec `loop`

Le mot-clé `loop` en Rust permet d'exécuter un bloc de code de manière répétée jusqu'à ce qu'une instruction explicite lui demande de s'arrêter. Ce mécanisme est particulièrement utile pour les tâches répétitives.

Rust fournit également le mot-clé `break` pour quitter une boucle. De plus, si vous avez des boucles imbriquées, vous pouvez utiliser des étiquettes de boucle pour spécifier laquelle vous souhaitez interrompre. Cela rend le contrôle du flux de votre programme plus clair et précis.

**Question:** Quels sont les avantages d'utiliser des étiquettes de boucle avec `break` et `continue` dans des boucles imbriquées ?

#### Retourner des valeurs d'une boucle

- Une des utilisations des boucles en Rust, en particulier avec `loop`, est de réessayer des opérations qui peuvent échouer, comme vérifier si une tâche est terminée. Vous pouvez également avoir besoin de transmettre le résultat d'une opération à votre code en dehors de la boucle.

- Utilisation de `break` pour retourner une valeur

- En ajoutant la valeur que vous souhaitez retourner après l'instruction `break`, cette valeur sera accessible à l'extérieur de la boucle. Cela permet de stocker le résultat de l'opération dans une variable pour une utilisation ultérieure.

**Question:** Comment l'utilisation de `break` pour retourner des valeurs d'une boucle améliore-t-elle la gestion des erreurs ou des conditions d'achèvement dans un programme Rust ?

#### Les boucles conditionnelles avec `while`

Un programme a souvent besoin d'évaluer une condition au sein d'une boucle. Avec une boucle `while`, tant que la condition est vraie, la boucle s'exécute ; dès que la condition devient fausse, le programme quitte la boucle en appelant `break`. Bien que vous puissiez recréer ce comportement en combinant `loop`, `if`, `else` et `break`, Rust offre une construction dédiée : la boucle `while`.

- Exemple de boucle `while` :

Par exemple, nous pouvons utiliser `while` pour faire une boucle trois fois, en décrémentant une variable à chaque itération et en affichant un message une fois la boucle terminée.

**Question:**  Quels sont les avantages d'utiliser une boucle `while` par rapport à la combinaison de `loop`, `if`, `else`, et `break` pour gérer les conditions dans un programme ?

#### Boucler dans une collection avec for

En Rust, bien que l'on puisse utiliser une boucle `while` pour itérer sur les éléments d'une collection comme un tableau, cela peut entraîner des erreurs si la condition de boucle n'est pas correctement définie. Par exemple, si l'on oublie de modifier la condition après avoir changé la taille du tableau, le programme peut paniquer. En revanche, une boucle `for` offre une approche plus sûre et concise pour parcourir chaque élément d'une collection. Elle élimine le risque de dépasser les limites du tableau et évite la nécessité de gérer manuellement les indices, ce qui améliore la lisibilité et la sécurité du code.

**Question:** Pourquoi est-il plus sûr et plus pratique d'utiliser une boucle `for` plutôt qu'une boucle `while` pour itérer sur une collection en Rust ? 

### Résumé de ce chapitre : 

Le chapitre a permis d'aborder des concepts fondamentaux, notamment les variables, les types scalaires et composés, les fonctions, les commentaires, les expressions if, et les boucles.

La prochaine étape explorera un concept unique à Rust : la possession (ownership).
