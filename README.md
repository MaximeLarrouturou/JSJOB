# JSJOB 2018

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.5.4.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

# Démarrer le projet avec deux lancement de consoles
A l'aide de cd, démarrer nodemon dans backend (cd backend, puis nodemon)
Dans une autre console ng serve
# Angular CLI
1. Initialiser un nouveau projet à l'aide de Angular CLI

2. Structure du projet Angular généré par Angular CLI

3. Générer un composant Angular

4. Importer le module HttpModule ou HttpClientModule

# Créer la partie Frontend avec Angular 4
5. Effectuer une requête Ajax à l'aide de RxJS

6. Intégrer (twitter) bootstrap

7. Créer le service job-service

8. Créer le modèle d'un formulaire de type 'reactive forms'

9. Créer la vue d'un formulaire de type 'reactive forms'

10. Générer un menu déroulant

11. Générer des boutons radio

12. Gérer les dates à l'aide de date-fns et créer le pipe 'daysAgo'

13. Utiliser un input de type date

14. Faire communiquer des composants frères à l'aide d'un Subject RxJS

15. Créer un panel à l'aide de (twitter) bootstrap

# Le routage côté Frontend
16. Mettre en oeuvre le routage

17. Créer un menu de navigation

18. Afficher les données existantes et ajoutées

# Créer un backend Node et interagir avec un client Angular 4
19. Créer une API REST avec Express.js

20. Envoyer un tableau d'objets via notre API REST

21. Créer un middleware autorisant l'accès de notre API à tous les clients

22. Gérer le POST

23. Gérer le POST (suite)

24. Vider un formulaire après soumission

25. Créer une route comportant un paramètre permettant un GET par id

26. Créer un lien dynamique

27. Gérer les requêtes visant à obtenir le détail d'un objet

28. Créer le pipe toShortDate

29. Créer une page de détails

30. Créer un pipe de formatage de monnaie

# Implémenter la recherche en Node et Angular
31. Implémenter la recherche côté serveur

32. Implémenter la recherche côté client

33. Afficher les résultats de recherche à l'aide d'un subject RxJS

34. Désactiver le bouton de soumission du formulaire de recherche

# Implémenter un système de création de comptes et de login avec JWT
35. Créer le composant 'authentication'

36. Gérer le login côté Frontend et Backend

37. Générer un token JWT

38. Persister le token reçu du serveur dans localStorage

39. Afficher une vue spécifique à l'état "authentifié"

40. Gérer la déconnexion (le logout)

41. Créer le composant 'register'

42. Création du nouvel utilisateur côté Backend et Frontend

43. Décoder le token et l'afficher dans la page de profil

44. Corriger l'authentification vérifiée sur notre fakeUser + divers

45. Générer un 'claim' de type 'role' qui varie en fonction des privilèges

46. Afficher du contenu différent en fonction du rôle décodé depuis le token JWT

# Gérer l'accès à des ressources protégées à l'aide de JWT
47. Créer un middleware permettant de récupérer un Header de type Authorization

48. Afficher le formulaire d'ajout d'annonces uniquement aux utilisateurs connectés

49. Envoyer un Authorization Header depuis un client Angular

50. Vérifier le token côté serveur

# Enrichir la page de profil
51. Afficher le pseudo de l'utilisateur

52. Récupérer les annonces passées par un utilisateur de base

53. Récupérer toutes les annonces lorsque l'on est logué en tant qu'admin

54. Afficher les annonces passées par l'utilisateur connecté

55. Créer un pipe qui tronquera les descriptions trop longues
