
# HighLinkPHP
**HighLink** est un plugin permettant de faire en sorte qu'un site (*php*) puisse envoyer des évenements en temps réel sur le serveur !

## Utilisation
*Je vous conseille de configurer [la partie Minecraft](url) avant la partie serveur*
Tout d'abord, il faut configurer la **RCON** de votre serveur dans le début du fichier HighLink.php

    $host = "localhost";
    $port="25566";
    $password="root";
Pour envoyer une requête au serveur, il faut envoyer une requête **POST** pointant vers le fichier HighLink.php avec pour paramètres :

**sk** : String -> Clé secrète,sans espaces, pour assurer une sécurité optimale ! 

**key** : String -> Type d'évenement envoyé au serveur Minecraft, sans espaces .

**val** : String -> Valeur d'évènement envoyé au serveur Minecraft, espaces autorisés .

Et pour les flemmards, voici un code spécialement pour vous !

    <form action="HighLink.php">
      <input type="hidden" name="sk" value="SECRETKEY">
      <input type="hidden" name="key" value="sendmsg">
      <input type="hidden" name="val" value="Je suis sur le site web">
      <input type="submit" value="Embêter le serveur minecraft !">
    </form>
Il ne vous reste plus qu'a remplacer les valeurs des `input:hidden` !
## A propos
Ce plugin à été développé par Fir3rl ! J'espère qu'il vous aidera bien ! N'hésitez pas à ouvrir des issues lors de problèmes où à me contacter sur discord (Fir3rl#5549) !

[Aller voir la partie minecraft](url)
