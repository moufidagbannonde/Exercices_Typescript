
## tableaux 
 # Exo 1
    Objectif :
    Apprendre à créer, accéder et modifier des éléments dans un tableau.
    Instructions :
    Créez un tableau de chaînes de caractères contenant les noms des jours de la semaine.
    Remplacez le troisième élément (index 2) par "Wednesday".
    Ajoutez "Sunday" à la fin du tableau.
    Supprimez le premier élément du tableau.
    Affichez le tableau final.


 # Exo 2
    Objectif :
    Utiliser des méthodes avancées pour transformer les tableaux.
    Instructions :
    Créez un tableau de nombres contenant les éléments suivants : 1, 2, 3, 4, 5, 6, 7, 8, 9, 10.
    Utilisez la méthode filter pour ne garder que les nombres pairs.
    Utilisez la méthode map pour multiplier chaque élément par 10.
    Utilisez la méthode reduce pour calculer la somme de tous les éléments.
    Affichez le tableau transformé et la somme des éléments.

 # Exo 3
    Apprendre à trier un tableau et à rechercher des éléments spécifiques.
    Instructions :
    Créez un tableau de nombres contenant les éléments suivants : 34, 7, 23, 32, 5, 62.
    Triez le tableau par ordre croissant (méthode sort).
    Trouvez le premier nombre supérieur à 20 dans le tableau trié.
    Affichez le tableau trié et le premier nombre trouvé supérieur à 20.

## tuples 
 # Exo 1
    Apprendre à créer et accéder aux éléments d'un tuple.
    Instructions :
    Créez un tuple person avec les éléments suivants :
    "John" (string)
    25 (number)
    true (boolean)
    Affichez les éléments du tuple individuellement.

 # Exo 2
    Manipuler et modifier les éléments d'un tuple.
    Instructions :
    Créez un tuple product avec les éléments suivants :
    "Laptop" (string)
    1200 (number)
    "Available" (string)
    Modifiez le deuxième élément pour qu'il soit 1000.
    Modifiez le troisième élément pour qu'il soit "Out of Stock".
    Affichez le tuple modifié.

 # Exo 2
    Passer des tuples en argument et en retourner depuis des fonctions.
    Instructions :
    Créez une fonction swap qui prend un tuple de deux éléments et retourne un nouveau tuple avec les éléments échangés.
    Testez la fonction swap avec les tuples suivants :
    (1, "one")
    (true, "false")
    Affichez les résultats des appels à la fonction swap.


## objets 
 # Exo 1
    Apprendre à créer et accéder aux propriétés d'un objet.
    Instructions :
    Créez un objet car avec les propriétés suivantes :
    make (string) : "Toyota"
    model (string) : "Corolla"
    year (number) : 2020
    Accédez et affichez chaque propriété de l'objet.

 # Exo 2
    Manipuler et modifier les propriétés d'un objet.
    Instructions :
    Créez un objet book avec les propriétés suivantes :
    title (string) : "1984"
    author (string) : "George Orwell"
    pages (number) : 328
    Modifiez la propriété pages pour qu'elle soit 300.
    Ajoutez une nouvelle propriété publisher (string) avec la valeur "Secker & Warburg".
    Supprimez la propriété author.
    Affichez l'objet modifié.

 # Exo 2
    Créez un objet person avec les propriétés suivantes :
    name (string) : "Alice"
    age (number) : 30
    address (objet) avec les propriétés :
    street (string) : "123 Main St"
    city (string) : "Wonderland"
    greet (méthode) qui affiche un message de salutation utilisant les propriétés name et city.
    Appelez la méthode greet de l'objet person.

 # Exo 4
    Apprendre à manipuler des objets contenant des tableaux en tant que propriétés.
    Instructions :
    Créez un objet student avec les propriétés suivantes :
    name (string) : "Bob"
    age (number) : 21
    grades (tableau de nombres) : [85, 92, 78, 88]
    Ajoutez une nouvelle note 95 à la fin du tableau grades.
    Calculez et affichez la moyenne des notes.
    Affichez l'objet student mis à jour.

 # Exo 5
    Travailler avec des tableaux d'objets et ajouter des méthodes pour manipuler les données.
    Instructions :
    Créez un objet library avec une propriété books qui est un tableau d'objets. Chaque objet représente un livre (type) avec les propriétés suivantes :
    title (string)
    author (string)
    year (number)
    Ajoutez une méthode addBook qui prend un titre, un auteur, et une année comme paramètres, et ajoute un nouveau livre à la bibliothèque.
    Ajoutez une méthode findBooksByAuthor qui prend un nom d'auteur comme paramètre et retourne tous les livres de cet auteur.
    Testez les méthodes addBook et findBooksByAuthor :
    Ajoutez deux nouveaux livres à la bibliothèque.
    Recherchez et affichez tous les livres d'un auteur spécifique.

 # Exo 6
    Apprendre à utiliser les unions de types avec des objets.
    Instructions :
    Créez un type alias Shape qui peut être soit un objet Circle soit un objet Square.
    Circle a les propriétés radius (number).
    Square a les propriétés sideLength (number).
    Créez une fonction calculateArea qui prend un Shape en paramètre et retourne l'aire correspondante.
    Si c'est un Circle, l'aire est calculée avec la formule π * radius^2.
    Si c'est un Square, l'aire est calculée avec la formule sideLength^2.
    Testez la fonction avec un cercle et un carré, et affichez les résultats.


 # Exo 7
    Apprendre à utiliser les alias de types et les fonctions génériques avec des objets.
    Instructions :
    Créez un type alias ApiResponse<T> représentant une réponse d'API générique avec les propriétés suivantes :
    status (string)
    data (T)
    error (string | null)
    Créez une fonction générique handleApiResponse qui prend une ApiResponse<T> en paramètre et affiche soit les données (si status est "success"), soit l'erreur (si status est "error").
    Testez la fonction avec des réponses d'API de différents types de données (par exemple, string et number).

 # Exo 8
    Apprendre à utiliser les alias de types et les intersections de types avec des objets.
    Instructions :
    Créez deux types alias Person et Employee :
    Person a les propriétés name (string) et age (number).
    Employee a les propriétés employeeId (number) et department (string).
    Créez un type alias StaffMember qui est une intersection de Person et Employee.
    Créez un objet staff de type StaffMember et initialisez-le avec des valeurs.
    Affichez les propriétés de l'objet staff.


## enum 
 # Exo 1
    Définissez une énumération Day pour représenter les jours de la semaine. Ensuite, créez une fonction isWeekend qui prend un jour de la semaine en tant qu'argument et renvoie true si c'est un week-end (samedi ou dimanche), sinon false.

 # Exo 2
    Créez une énumération PrivilegeLevel pour représenter différents niveaux de privilège dans une application (par exemple, Admin, User, Guest). Ensuite, écrivez une fonction canEdit qui prend un niveau de privilège et renvoie true si le niveau de privilège permet de modifier des données, sinon false.

 # Exo 2
    Définissez une énumération OrderStatus pour représenter les différents états possibles d'une commande (par exemple, Pending, Shipped, Delivered, Cancelled). Créez une fonction getOrderMessage qui prend un état de commande et renvoie un message correspondant à cet état (par exemple, "Votre commande est en cours de traitement" pour Pending).