---
description: Retrouvez ici toutes les informations concernant la création de playerwarp
---

# 🚩 Les Pwarps

{% embed url="https://www.youtube.com/watch?index=1&list=PL1QLnkRl9WVyR0eGUtFoTo8a9MBJHBFwa&v=DQan4FHVdeM" %}
**Tuto : Créer et gérer votre propre ville sur Evolucraft**
{% endembed %}

## <mark style="color:green;">Informations Générales</mark>

Le Pwarp est une fonctionnalité essentielle sur notre serveur qui permet aux joueurs de créer leurs propres points de téléportation personnalisés, appelés warps.

Ces warps peuvent être utilisés pour se déplacer rapidement à travers le monde et faciliter l'exploration, les échanges commerciaux, ou tout simplement pour rendre la navigation plus pratique.

<figure><img src="../../.gitbook/assets/Les_Villes/PlayerWarp.png" alt=""><figcaption><p><strong>Aperçu du </strong><mark style="color:green;"><strong><code>/pwarp</code></strong></mark></p></figcaption></figure>

## <mark style="color:green;">Utilité des Warps</mark>

* <mark style="color:green;">**Exploration Rapide**</mark>**&#x20;:** Les warps permettent aux joueurs de se déplacer instantanément vers des endroits qu'ils ont déjà visités, facilitant ainsi l'exploration de nouvelles régions.
* <mark style="color:green;">**Commerce et Échanges**</mark>**&#x20;:** En créant des warps vers des endroits spécifiques comme des marchés, des magasins ou des zones d'échanges, les joueurs peuvent simplifier leurs transactions commerciales.
* <mark style="color:green;">**Gestion de Ville**</mark>**&#x20;:** Les maires de villes peuvent utiliser les warps pour permettre à leurs citoyens de se déplacer facilement à des endroits clés de la ville, comme les mairies, les arènes ou les fermes communautaires.

## <mark style="color:green;">Commandes de PlayerWarp</mark>

### <mark style="color:green;">Warps Personnels</mark>

* <mark style="color:green;">**`/pwarp create [nom du warp]`**</mark> : Crée un nouveau warp personnel avec le nom spécifié.
* <mark style="color:green;">**`/pwarp delete [nom du warp]`**</mark> : Supprime le warp personnel spécifié.
* <mark style="color:green;">**`/pwarp list`**</mark> : Affiche la liste de vos warps personnels.
* <mark style="color:green;">**`/pwarp setowner set [nom du warp] [nom du joueur]`**</mark> : envoyer une demande a un joueur de devenir le chef du warp
* <mark style="color:green;">**`/pwarp setowner accept [nom du warp]`**</mark> : accepter la demande de devenir chef d’un warp
* <mark style="color:green;">**`/pwarp setowner cancel [nom du warp]`**</mark> : refuser la demande de devenir chef d’un warp
* <mark style="color:green;">**`/pwarp cost remove`**</mark> : met le prix de teleportation au warp à 0
* <mark style="color:green;">**`/pwarp cost set [nom du warp] [prix]`**</mark> : mettre un prix à la teleportation au warp (max 500$)
* <mark style="color:green;">**`/pwarp ban set [nom du pwarp] [nom du joueur]`**</mark> : bannir un joueur du pwarp
* <mark style="color:green;">**`/pwarp ban list [nom du pwarp]`**</mark> : afficher la liste des joueurs bannis du pwarp
* <mark style="color:green;">**`/pwarp ban remove [nom du pwarp] [nom du joueur]`**</mark> : dé-bannir un joueur du pwarp
* <mark style="color:green;">**`/pwarp lock [nom du pwarp]`**</mark> <mark style="color:green;"></mark><mark style="color:green;">: Permet d'ouvrir ou fermer l'accès public à votre warp.</mark>
* <mark style="color:green;">**`/pwarp desc set [description]`**</mark> <mark style="color:green;"></mark><mark style="color:green;">: Permet de rajouter une description à votre warp.</mark>
* <mark style="color:green;">**`/pwarp desc remove [description]`**</mark> <mark style="color:green;"></mark><mark style="color:green;">: Permet de retirer une description à votre warp.</mark>



### <mark style="color:green;">Warps Publics</mark>

* <mark style="color:green;">**`/pwarp [nom du warp]`**</mark> : Téléporte-vous au warp public spécifié.
* <mark style="color:green;">**`/pwarp info [nom du warp]`**</mark> : Affiche des informations sur le warp public spécifié.
* <mark style="color:green;">**`/pwarp list`**</mark> : Affiche une liste de tous les warps publics disponibles.
* <mark style="color:green;">**`/pwarp setlocation [nom du warp]`**</mark> : Définit la position actuelle comme emplacement du warp public spécifié.


## <mark style="color:green;"><strong>🚩 Les pwarps</strong></mark>

Les <mark style="color:green;"><strong>pwarps</strong></mark> sont un <mark style="color:green;"><strong>moyen de déplacement essentiel</strong></mark> permettant aux <mark style="color:green;"><strong>joueurs</strong></mark> de se <mark style="color:green;"><strong>téléporter directement</strong></mark> vers votre <mark style="color:green;"><strong>ville</strong></mark> afin de la <mark style="color:green;"><strong>visiter</strong></mark>, mais aussi d’<mark style="color:green;"><strong>acheter</strong></mark> ou de <mark style="color:green;"><strong>vendre</strong></mark> dans votre <mark style="color:green;"><strong>shop</strong></mark>.

Ils jouent donc un rôle clé dans la <mark style="color:green;"><strong>visibilité</strong></mark> de votre ville et dans le <mark style="color:green;"><strong>développement de votre activité commerciale</strong></mark>.

Mais alors, comment <mark style="color:green;"><strong>créer</strong></mark> et <mark style="color:green;"><strong>utiliser</strong></mark> un <mark style="color:green;"><strong>pwarp</strong></mark> efficacement ? Découvrons cela ensemble !

### <mark style="color:green;"><strong>🆕 Créer un pwarp</strong></mark>

Chaque <mark style="color:green;"><strong>joueur</strong></mark> dispose de <mark style="color:green;"><strong>2 pwarps</strong></mark> qu’il peut <mark style="color:green;"><strong>créer librement</strong></mark>. Vous pouvez ainsi les <mark style="color:green;"><strong>regrouper</strong></mark> dans une <mark style="color:green;"><strong>même ville</strong></mark> afin de centraliser votre activité, ou les <mark style="color:green;"><strong>disperser</strong></mark> dans <mark style="color:green;"><strong>deux villes différentes</strong></mark> pour toucher un public plus large.

Pour <mark style="color:green;"><strong>créer un pwarp</strong></mark>, utilisez la commande suivante : <mark style="color:green;"><strong>`/pwarp create [nom]`</strong></mark>

Une fois la commande effectuée, vous devrez la <mark style="color:green;"><strong>répéter une seconde fois</strong></mark> dans le délai imparti afin de <mark style="color:green;"><strong>confirmer la création</strong></mark>.

*(image de validation du pwarp)*

Lorsque vous recevrez le message de validation, votre <mark style="color:green;"><strong>pwarp sera actif</strong></mark> et <mark style="color:green;"><strong>les joueurs pourront s’y téléporter</strong></mark> via la commande : <mark style="color:green;"><strong>`/pwarp [nom du pwarp]`</strong></mark>

{% hint style="info" %}
<mark style="color:green;"><strong>💡 REMARQUE :</strong></mark> Pensez à créer votre pwarp <mark style="color:green;"><strong>au plus proche de votre zone de shop</strong></mark> afin d’éviter que les joueurs soient téléportés trop loin ou qu’ils ne puissent pas y accéder facilement.
{% endhint %}

### <mark style="color:green;"><strong>🎨 Customiser un pwarp</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Ouvrir ou fermer un pwarp</strong></mark>

Si vous effectuez des <mark style="color:green;"><strong>travaux</strong></mark> ou une <mark style="color:green;"><strong>rénovation</strong></mark> sur votre pwarp, vous pouvez <mark style="color:green;"><strong>empêcher temporairement l’accès</strong></mark> aux joueurs.

Utilisez la commande suivante pour <mark style="color:green;"><strong>ouvrir ou fermer votre pwarp</strong></mark> : <mark style="color:green;"><strong>`/pwarp lock [Nom du pwarp]`</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Relocaliser l’emplacement du pwarp</strong></mark>

Si vous souhaitez déplacer votre pwarp afin qu’il soit <mark style="color:green;"><strong>plus proche de votre zone de shop</strong></mark>, utilisez la commande :<mark style="color:green;"><strong>`/pwarp reset [Nom du pwarp]`</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Billet d’entrée</strong></mark>

Vous pouvez appliquer une <mark style="color:green;"><strong>taxe d’entrée</strong></mark> (jusqu’à <mark style="color:green;"><strong>500💲 maximum</strong></mark>) lorsqu’un joueur se téléporte à votre pwarp : <mark style="color:green;"><strong>`/pwarp cost set [Nom du pwarp] [Prix]`</strong></mark>. Ou alors, si <mark style="color:green;"><strong>vous ne souhaitez pas avoir cette taxe</strong></mark>, vous pouvez réaliser la commande : <mark style="color:green;"><strong>`/pwarp cost remove [Nom du pwarp]`</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Blacklist</strong></mark>

Si un joueur cause des <mark style="color:green;"><strong>problèmes</strong></mark> dans votre pwarp, vous pouvez l’en <mark style="color:green;"><strong>exclure</strong></mark> grâce à la commande : <mark style="color:green;"><strong>`/pwarp ban set [Nom du pwarp] [Pseudo du joueur]`</strong></mark>. Mais si vous souhaitez <mark style="color:green;"><strong>lever son bannissement</strong></mark>, il vous suffira de faire <mark style="color:green;"><strong>`/pwarp ban remove [Nom du pwarp] [Pseudo du joueur]`</strong></mark>

Si vous souhaitez avoir <mark style="color:green;"><strong>la liste complète des joueurs bannis de votre pwarp</strong></mark>, il vous suffira de faire : <mark style="color:green;"><strong>`/pwarp ban list [Nom du pwarp]`</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Description</strong></mark>

Vous pouvez ajouter une <mark style="color:green;"><strong>description personnalisée</strong></mark> à votre pwarp afin de le <mark style="color:green;"><strong>mettre en valeur</strong></mark> dans le menu <mark style="color:green;"><strong>`/pwarp`</strong></mark> et donner envie aux joueurs de le visiter via la commande <mark style="color:green;"><strong>`/pwarp desc set [Nom du pwarp] [Description]`</strong></mark>.

*(image description pwarp)*

{% hint style="info" %}
<mark style="color:green;"><strong>💡 REMARQUE :</strong></mark> Pour utiliser des <mark style="color:green;"><strong>couleurs personnalisées</strong></mark> dans votre description, vous devez posséder [<mark style="color:green;"><strong>l’abonnement Premium</strong></mark>](https://wiki.evolucraft.fr/le-gameplay/les-grades#abonnement-premium) 👑. Sans celui-ci, la description sera affichée en vert par défaut.
{% endhint %}

Si au contraire, vous souhaitez <mark style="color:green;"><strong>supprimer la description</strong></mark>, vous pourrez effectuez la commande : <mark style="color:green;"><strong>`/pwarp desc remove [Nom du pwarp]`</strong></mark>

#### 🔹 <mark style="color:green;"><strong>Changer de propriétaire</strong></mark>

Si vous souhaitez transférer la <mark style="color:green;"><strong>propriété</strong></mark> de votre pwarp à un autre joueur, il faudra réaliser la commande : <mark style="color:green;"><strong>`/pwarp setowner [Nom du pwarp] [Pseudo du joueur]`</strong></mark>

Le <mark style="color:green;"><strong>joueur devra ensuite accepter</strong></mark> avec le <mark style="color:green;"><strong>`/pwarp setowner accept [Nom du pwarp]`</strong></mark>. Ou de <mark style="color:green;"><strong>refuser avec le <mark style="color:green;"><strong>`/pwarp setowner cancel [Nom du pwarp]`</strong></mark>.

### <mark style="color:green;"><strong>📔 Informations sur les pwarps</strong></mark>

Pour obtenir des informations sur un pwarp</strong></mark> ou sur ceux gérés par un joueur</strong></mark>, plusieurs commandes sont disponibles.

* Pour connaître <mark style="color:green;"><strong>le propriétaire d’un pwarp</strong></mark>, rien de plus simple qu'un <mark style="color:green;"><strong>`/pwarp info [Nom du pwarp]`</strong></mark>. Vous aurez les informations affichées comme ci-dessous.

*(image info pwarp)*

* À l'inverse, pour afficher <mark style="color:green;"><strong>la liste des pwarps d’un joueur</strong></mark>, il faudra réaliser la commande <mark style="color:green;"><strong>`/pwarp list [Pseudo]`</strong></mark>.

### <mark style="color:green;"><strong>❌ Supprimer un pwarp</strong></mark>

Si votre pwarp ne vous est plus utile, vous pouvez le <mark style="color:green;"><strong>supprimer définitivement</strong></mark> avec la commande suivante : <mark style="color:green;"><strong>`/pwarp remove [Nom du pwarp]`</strong></mark>.

{% hint style="warning" %}
<mark style="color:green;"><strong>⚠️ ATTENTION :</strong></mark> Cette action est <mark style="color:green;"><strong>irréversible</strong></mark>. Vous ne pourrez pas revenir en arrière, mais une <mark style="color:green;"><strong>place de création</strong></mark> sera libérée.
{% endhint %}


