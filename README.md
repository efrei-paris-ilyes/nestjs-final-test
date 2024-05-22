Groupe : Ilyès Boulkrinat
Ressources utilisées : 
-   https://www.prisma.io/blog/nestjs-prisma-rest-api-7D056s1BmOL0 (tp entièrement suivi sur ce site)
-   https://docs.nestjs.com/recipes/prisma (Documentation prisma)
-   Cours de NestJS

Comment lancer le projet ?
(Optionnel : supprimer les packages-lock.json déjà installés il est possible que j'utilise un autre registry que celui de base de npm)
Lancer le serveur :
-   npm ci 
-   npm run start

Lancer la DB : 
-   npm run start:postgres

Les scripts de DB ont été changés pour push mon modèle prisma.

Lancer les tests : 
-   npm run test:e2e:postgres

Après plusieurs vérifications les 7 tests passent sans soucis grâce à ces commandes.
Si problème contacter : ilyesb36130@gmail.com ou Ilyès Boulkrinat sur teams.