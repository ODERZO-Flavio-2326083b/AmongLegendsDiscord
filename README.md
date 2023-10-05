# AmongLegendsDiscord

Un programme python utilisant l'API de Discord pour donner des rôles et tâches additionnelles à des joueurs 
dans une partie de LoL, inspiré d'Among Us. *(vrai projet à la base..)*

## Fonctionnement

Les utilisateurs intéragissent avec le bot en utilisant des commandes dans un serveur où le bot est présent. En "ping"-ant les joueurs, une partie est lancée et chaque joueur reçoit un rôle en particulier. On peut y jouer à 5 ou à 10, pour une ou deux équipes. Le jeu se termine lorsque la partie de LoL est terminée, et le but est de deviner le rôle des autres. En fonction des 

### Les rôles

- **L'imposteur** : le but de cet individu de la plus basse espèce humaine est de ruiner la partie de ses compères, en mourant le plus de fois possibles, sans que cela soit ~~trop~~ évident. 

- **Le robot** : ce joueur reçoit des ordres de manière périodiques par message, qu'il doit effectuer le plus vite possible dans la partie.

- **Double-face** : ce joueur est un peu schizophrène, le bot lui envoie un message lorsqu'il doit jouer au mieux, et lorsqu'il doit jouer très très mal. 

- **Faker** : doit jouer le mieux possible, avoir le plus de kills, tout le long de la partie

- **Serpentin** : doit avoir le plus de morts ET de kills

## Commandes
*Chaque commande est un message qui doit commencer par le préfixe paramétré pour le bot*

*Tip : [argument obligatoire], (argument facultatif)*

Commande | Arguments | Description | Permissions nécessaires?
--- | --- | --- | ---
startGame | [joueurs] | Lance une parite avec les joueurs mentionnées (5 ou 10)| ❎
prefix | [nouveau_prefixe] | modifie le préfixe des commandes | ✅
roleEnable | [role] [true/false] | active ou désactive le rôle précisé dans les prochaines parties | ✅
endGame | / | Termine la partie en cours, s'il y en a une, et lance la phase de votes | ❎
history | (joueur) | Montre votre historique, ou celui du joueur mentionné | ❎
quitGame | / | Quitte la partie en cours, annulant celle-ci (pas cool) | ❎
kickFromGame | [joueur] | Exclue le joueur de la partie, parce qu'il n'est pas très sympa | ✅

## Idées / Features à venir

- [ ] Ajouter plus de rôles
- [ ] Rendre le bot utilisable interserveurs
- [x] Ajouter plus de tâches pour le robot, afin qu'elles ne soient pas redondantes
- [ ] Classement par points à la fin des parties en fonction des votes
- [ ] Rendre League of Legends jouable (impossible)






