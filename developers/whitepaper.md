---
id: whitepaper
title: Livre Blanc
slug: /developers/whitepaper
---

*A decentralised Universal Basic Income platform based on personal currencies*

**https://joincircles.net**

<div align="center">
	<img width="80" src="https://raw.githubusercontent.com/CirclesUBI/.github/main/assets/logo.svg" />
</div>

<h1 align="center">Livre blanc Circles</h1>

<div align="center">
 <strong>
  Une plateforme de revenu universel décentralisée baséé sur des monnaies individuelles.
 </strong>
</div>

<br />

<div align="center">
  <!-- License -->
  <a href="https://github.com/CirclesUBI/whitepaper/blob/main/LICENSE">
    <img src="https://img.shields.io/github/license/CirclesUBI/whitepaper?style=flat-square&color=%23cc1e66" alt="License" height="18">
  </a>
  <!-- Discourse -->
  <a href="https://aboutcircles.com/">
    <img src="https://img.shields.io/discourse/topics?server=https%3A%2F%2Faboutcircles.com%2F&style=flat-square&color=%23faad26" alt="chat" height="18"/>
  </a>
  <!-- Twitter -->
  <a href="https://twitter.com/CirclesUBI">
    <img src="https://img.shields.io/twitter/follow/circlesubi.svg?label=twitter&style=flat-square&color=%23f14d48" alt="Follow Circles" height="18">
  </a>
</div>

<div align="center">
  <h3>
    <a href="https://chat.joincircles.net">
      Chat
    </a>
    <span> | </span>
    <a href="https://handbook.joincircles.net">
      Handbook
    </a>
    <span> | </span>
    <a href="https://github.com/CirclesUBI/.github/blob/main/CONTRIBUTING.md">
      Contributing
    </a>
  </h3>
</div>

<br/>

## Résumé

Nous proposons un nouveau système monétaire appelé Circles qui est basé sur des crypto-monnaies individualisées et un graphe social de confiance entre ces monnaies. Ce système monétaire aura pour but de distribuer l'argent d'une manière qui, au fil du temps, conduira à l'égalisation des richesses et fonctionnera comme un revenu de base universel accessible dans le monde entier. Lorsque de nouveaux utilisateurs rejoignent Circles, une nouvelle crypto-monnaie personnelle leur est spécialement créée sur une blockchain compatible avec les contrats intelligents. Cette monnaie est ensuite régulièrement frappée et ajoutée à leur compte, formant la base des propriétés du Revenu Universel de Base Circles. Les utilisateurs ont la possibilité de faire confiance aux monnaies personnelles des autres utilisateurs, ce qui les oblige à traiter cette monnaie personnelle comme identique à toutes les autres monnaies Circles qu'ils détiennent. Au fur et à mesure que le graphe social s'interconnecte, ces monnaies personnelles convergent vers un seul système monétaire mondial.

## Introduction

Le Revenu Universel de Base est l'un des mouvements politiques de l'ère moderne qui suscite le plus d'intérêt dans toutes les cultures. Il a attiré le soutien de penseurs de tous horizons, dont Thomas Paine, Martin Luther King Jr, Stephen Hawking, Guy Standing, Milton Friedman et David Graeber. Il est considéré comme un projet utopique qui pourrait enfin libérer le potentiel créatif de tous les individus, l'aboutissement d'idéaux humanistes vieux de plusieurs siècles.

Le sujet de RUB a explosé en popularité ces dernières années, alors que les inégalités de richesse se creusent et que les salaires corrigés de l'inflation chutent partout dans le monde. Jusqu'à présent, les discussions ont été principalement vues à travers le prisme de la politique publique et de l'action bureaucratique. Le soutien du public à l'idée de RUB n'a jamais été aussi élevé, mais les plans de mise en œuvre progressent lentement et sans coopération à l'échelle internationale. Il semble que les systèmes de RUB aient reçu l'étiquette "trop gros pour être mis en œuvre" aux plus hauts niveaux de l'État, à l'instar de l'action sur le changement climatique, ce qui rend le développement et le déploiement peu probable dans un avenir proche.

L'introduction des réseaux mondiaux de blockchain change considérablement le débat sur l'RUB. Pour la première fois dans l'histoire, il est trivialement facile de créer des applications financières universellement accessibles à tout le monde sur Internet. Depuis le Bitcoin jusqu'aux plateformes de contrats intelligents comme Ethereum, la technologie blockchain est devenue très populaire en contournant les gardes et les obstacles qui rendent l'innovation si difficile dans le système financier traditionnel. Les contrats intelligents et la blockchain créent un environnement très prometteur pour la mise en œuvre d'un nouveau système RUB.

Circles se propose d'être le système monétaire RUB natif de la blockchain. Il intègre sa propre résistance aux attaques Sybil (c'est-à-dire aux faux comptes) et n'importe qui peut rejoindre le réseau à tout moment sans demander la permission de quiconque. Il a été conçu dans l'optique d'un démarrage complètement organique et populaire, mais il est extensible pour permettre à tout système de gouvernance arbitraire de fonctionner au-dessus du protocole de base. Circles est une façon entièrement nouvelle d'envisager la nature de l'argent et la signification de l'échange de valeurs dans un avenir post-RUB.

## Frappe de la monnaie

Circles est un système monétaire qui se compose de monnaies individuelles. Ces monnaies fonctionnent ensemble pour former un "tissu monétaire" unifié qui se comporte comme un Revenu Universel de Base .

Lorsqu'un nouveau compte blockchain rejoint Circles, le système crée et lui attribue une monnaie unique via un contrat intelligent. Il s'agit d'une _Monnaie personnelle_, et toutes les monnaies personnelles fonctionnent selon un ensemble de règles communes.

Chaque monnaie personnelle frappe continuellement de nouvelles pièces et les attribue à la personne qui lui est associée. De plus, la quantité de pièces frappées gonfle chaque année. C'est la seule façon de créer de l'argent frais dans les Cercles et c'est la base de ses caractéristiques RUB. Toutes les monnaies frappent de nouvelles pièces au même rythme, ce qui signifie que de la nouvelle monnaie est coproduite et distribuée de manière égale à tous les membres du système à tout moment.

```
Alice rejoint le système et crée AliceCoin.
Les PersonalCoins sont tous frappés à un rythme de 1 par minute, par exemple.
Cinq minutes plus tard, Alice possède 5 AliceCoins et Bob rejoint le système, créant ainsi des BobCoins.
Cinq minutes plus tard, Alice a 10 AliceCoins et Bob a 5 BobCoins.
```

Il est important de noter que les nouvelles unités monétaires ne sont attribuées qu'à la personne associée à chaque monnaie personnelle :

```
Alice rejoint le système et crée AliceCoin.
Les PersonalCoins sont tous frappés à un rythme de 1 par minute.
Cinq minutes plus tard, Alice possède 5 AliceCoins et Bob rejoint le système, créant ainsi des BobCoins.
Alice transfère ses 5 AliceCoins à Bob
Alice a 0 PersonalCoins et Bob a 5 AliceCoins.
Cinq minutes plus tard, Alice a 5 AliceCoin et Bob a 5 AliceCoin et 5 BobCoin.
```

### Inflation

Afin de dissuader l'accumulation et d'encourager l'activité économique, le système introduira un calendrier annuel d'inflation. Il s'agit d'une surestarie par d'autres termes, où toutes les monnaies personnelles émettront des quantités progressivement plus importantes de jetons par an, payés à la seconde. Les nouveaux utilisateurs commenceront toujours à émettre à un taux qui est cohérent avec celui de toutes les autres monnaies personnelles.

```
Alice rejoint le système et crée AliceCoin.
Les PersonalCoins sont tous frappés au rythme de 1 par minute, et gonflent de 100 % toutes les cinq minutes.
Cinq minutes plus tard, Alice possède 5 AliceCoin et Bob rejoint le système, créant ainsi le BobCoin.
Alice transfère ses 5 AliceCoins à Bob
Alice a 0 PersonalCoin et Bob a 5 AliceCoin.
Cinq minutes plus tard, Alice a 5 AliceCoin et Bob a 5 AliceCoin et 5 BobCoin.
Alice a 5 pièces au total, et Bob a 10 pièces au total. La différence entre leurs portefeuilles est de 5 et Alice possède 0,5 (la moitié) du nombre de pièces que possède Bob.
Le taux d'émission gonfle de 100% et est maintenant de 2 pièces par minute.
Cinq minutes plus tard, Alice a 15 AliceCoin tandis que Bob a 5 AliceCoin et 15 BobCoin.
Au total, Alice possède 15 pièces et Bob 20 pièces. La différence entre leurs portefeuilles est toujours de 5, mais Alice possède maintenant 0,75 (trois quarts) du nombre de pièces que possède Bob. La différence relative entre leurs portefeuilles diminue.
```

## Une monnaie de confiance

Pour créer une monnaie utile, les utilisateurs doivent faire confiance aux monnaies des autres. La confiance est ce qui facilite les échanges dans le système. Lorsqu'un utilisateur fait confiance à une monnaie, il indique au système que celle-ci est équivalente à toutes les autres monnaies Circles qu'il possède déjà. Cela signifie que toute personne possédant cette monnaie de confiance peut automatiquement l'échanger contre l'une de vos monnaies Circles à un taux de change de un pour un.

```
Bob fait confiance à AliceCoin
Bob a 10 CarolCoin
Dave a 10 AliceCoin
Dave donne 5 AliceCoin à Bob et lui prend 5 CarolCoin.
```

Une autre façon de penser à la confiance est que l'utilisateur dit au système qu'il reconnaît des monnaies spécifiques comme "argent réel". Étant donné que n'importe quel compte de la blockchain peut rejoindre le système et commencer à frapper sa monnaie, une attaque triviale consiste à créer plusieurs comptes et à s'inscrire sur chacun d'eux pour obtenir plusieurs revenus de base. C'est ce qu'on appelle une attaque Sybil en termes de sécurité informatique. C'est grâce à l'existence de relations de confiance que les utilisateurs se protègent des faux comptes en précisant ceux dont ils savent pertinemment qu'ils représentent le compte principal d'un individu, formant ainsi une résistance Sybil native dans le système. Au niveau communautaire, la confiance dans le système signifie qu'il existe des ressources que l'on peut réclamer pour les Cercles.

En raison du risque que n'importe quel compte devienne une sybille à tout moment, la confiance peut aussi toujours être révoquée. Si et quand la confiance est révoquée, la personne qui la révoque peut toujours dépenser les pièces de la personne à qui elle ne fait pas confiance, mais elle ne recevra pas de nouvelles pièces de cet utilisateur par le biais de transactions transitives.

Parce que la confiance est un moyen de se protéger de la contrefaçon des monnaies, il s'agit d'une responsabilité sérieuse de la part de l'utilisateur. Les utilisateurs devront s'appuyer fortement sur les connexions mutuelles lorsqu'ils établiront des relations de confiance directes de pair à pair, et les nouveaux utilisateurs sans connexions de confiance devront faire en sorte que leurs proches les plus proches soient leurs connexions initiales. Il est théoriquement possible d'augmenter la fongibilité et la facilité d'utilisation de Circles avec des services professionnels (validateurs) qui peuvent agir comme des courtiers de confiance, ou avec des monnaies de groupe mises en commun, qui peuvent appliquer leurs propres politiques d'adhésion, cependant, ces extensions possibles ne seront pas présentes dans la première itération du système des Cercles. Nous vous invitons à poursuivre les recherches sur ce sujet.

### Échange transitif

Le fait de faire confiance à différentes monnaies crée une forme d'argent utile en raison de la nature transitive des réseaux sociaux. L'argent est utile lorsqu'il permet à de parfaits inconnus de faire des affaires de manière efficace. Lorsqu'un étranger veut envoyer de l'argent à un autre dans Circles, ils recherchent automatiquement une chaîne transitive de monnaies de confiance entre eux. Le payeur négocie alors le long de cette chaîne de monnaies de confiance, l'une après l'autre, jusqu'à ce qu'il obtienne une monnaie que le destinataire accepte.

```
Bob fait confiance à AliceCoin
Alice fait confiance à CarolCoin
Alice a 10 AliceCoin
Carol a 10 CarolCoin
Carol veut payer 5 PersonalCoins à Bob
Carol donne 5 CarolCoin à Alice et lui prend 5 AliceCoin.
Carol donne 5 AliceCoin à Bob
```

![Transitive exchange](https://raw.githubusercontent.com/CirclesUBI/whitepaper/master/assets/diagram_1.png)

La transaction peut être étendue pour inclure également des chaînes de confiance à bonds multiples :

```
Bob fait confiance à AliceCoin
Alice fait confiance à CarolCoin
Carol fait confiance à DaveCoin
Alice a 10 AliceCoin
Carol a 10 CarolCoin
Dave a 10 DaveCoin
Dave veut payer 5 PersonalCoins à Bob
Dave donne 5 DaveCoin à Carol et lui prend 5 CarolCoin
Dave donne 5 CarolCoin à Alice et lui prend 5 AliceCoin
Dave donne 5 AliceCoin à Bob
```

![](https://raw.githubusercontent.com/CirclesUBI/whitepaper/master/assets/diagram_3.png)

Avec ce système, la connectivité du réseau social sert de mesure directe de la capacité des utilisateurs à effectuer des transactions entre eux. Une façon familière de penser à cela est le fameux phénomène des six degrés de séparation qui suggère que toute personne sur terre est reliée à toute autre par une chaîne de six personnes. Circles utilise ces chaînes pour effectuer des transactions dans le système. Si un utilisateur est bien intégré dans le réseau, avec de nombreuses connexions avec d'autres utilisateurs bien intégrés, il lui sera plus facile d'envoyer et de recevoir de la monnaie personnelle.

### Limites de confiance

Comme les monnaies personnelles ne peuvent voyager qu'à travers leurs réseaux de confiance, la fongibilité d'une monnaie personnelle spécifique est une mesure du nombre d'autres comptes qui lui font confiance et des ressources disponibles dans le réseau. Cela signifie que les nouveaux utilisateurs qui n'ont pas beaucoup de relations de confiance ont une monnaie moins fongible que quelqu'un qui est bien établi dans le réseau. Cela signifie également que la monnaie des nouveaux utilisateurs devient plus fongible au fil du temps, à mesure qu'ils créent des relations de confiance.

Puisque le système applique en interne un taux de change de un pour un, et que les monnaies personnelles des nouveaux utilisateurs sont moins fongibles que celles des utilisateurs établis, un problème potentiel émerge :

```
25 personnes font confiance à AliceCoin
Bob est nouveau, donc seule Alice fait confiance à BobCoin
Bob a 100 BobCoin
Alice a 100 AliceCoin
Bob donne 100 BobCoin à Alice et lui prend 100 AliceCoin.
Bob peut maintenant dépenser de l'argent avec 25 personnes (et leurs amis, et les amis de leurs amis, etc.).
Alice ne peut plus dépenser de l'argent qu'avec Bob
```

![Trust limits](https://raw.githubusercontent.com/CirclesUBI/whitepaper/master/assets/diagram_4.png)

Dans l'exemple ci-dessus, Alice a besoin d'un moyen de reconnaître que BobCoin est de l'argent réel, tout en limitant son exposition à cet argent tant que Bob est encore nouveau. Circles y parvient grâce aux limites de confiance. Lorsque vous créez une relation de confiance dans Circles, vous avez la possibilité d'inclure le montant maximum de vos pièces totales que vous êtes prêt à détenir dans la monnaie d'un autre utilisateur. Une limite de confiance est exprimée en pourcentage. Avec les limites de confiance, Alice est en mesure d'aider Bob à s'intégrer dans le système d'une manière plus contrôlée :

```
25 personnes font confiance à AliceCoin
Bob est nouveau, donc seule Alice fait confiance à BobCoin.
Alice limite sa confiance à 10 BobCoin par mois.
Bob a 100 BobCoin
Alice a 100 AliceCoin
Bob donne 10 BobCoin à Alice et lui prend 10 AliceCoin.
Bob peut maintenant dépenser un dixième de son argent avec 25 personnes (et leurs amis, et les amis de leurs amis, etc.).
Alice met de côté ses 10 BobCoins pour les dépenser lorsque Bob aura noué d'autres relations de confiance.
Bob obtient que 10 personnes fassent confiance à BobCoin
Alice augmente sa limite de confiance dans le BobCoin à 100 par mois.
```

Les limites de confiance réduisent le risque de confier de nouveaux comptes au système, ce qui leur permet d'établir plus facilement des relations de confiance.

### Protections contre les faux comptes

Comme nous l'avons montré, les faux comptes sont une considération primordiale lors de la conception des protections dans le système. Puisque l'argent peut être dépensé indirectement par le biais de connexions transitives, montrons comment Circles se défend contre les faux comptes qui sont connectés à vos amis :

```
Bob fait confiance à AliceCoin
Alice crée un faux compte et fait confiance à FakeCoin
Alice a 10 AliceCoin
FakeAlice a 10 FakeCoin
Alice veut acheter quelque chose d'une valeur de 10 PersonalCoins à Bob en utilisant des FakeCoin.
FakeAlice donne 10 FakeCoin à Alice et lui prend 5 AliceCoin.
FakeAlice donne 10 AliceCoin à Bob.
```

![Fake accounts](https://raw.githubusercontent.com/CirclesUBI/whitepaper/master/assets/diagram_2.png)

Cet exemple montre que Bob ne peut recevoir que de l'argent auquel il fait confiance, et qu'Alice ne peut dépenser que de l'argent auquel d'autres utilisateurs font confiance à leur tour. Même si Alice crée 100 faux comptes et qu'ils se font tous confiance, elle ne pourra jamais dépenser plus que le montant d'AliceCoins dont elle dispose, puisque c'est le seul compte auquel les autres utilisateurs feront confiance. C'est pourquoi il est crucial que les utilisateurs prennent au sérieux les relations de confiance directes entre pairs.

## Une devise complémentaire

Circles n'a pas vocation à devenir la monnaie dominante dans le monde, qu'elle soit cryptographique ou autre. Il s'agit plutôt d'une monnaie complémentaire, travaillant en harmonie avec d'autres réserves de valeur et moyens d'échange, elle-même intégrée dans une diversité de monnaies. À l'avenir, les Circles pourraient même servir de devise forte et de fondation pour une devise de groupe plus flexible. Il s'agit d'une devise forte idéale car l'offre de monnaies individuelles spécifiques est parfaitement prévisible et le système global est hautement résilient car il ne dépend pas d'un fournisseur d'identité centralisé. Pour déterminer l'appartenance à un groupe, cette hypothétique devise de groupe pourrait fonctionner selon une logique commerciale arbitraire, par exemple en faisant partie d'un réseau de troc commercial, ou démocratiquement via des assemblées géographiquement limitées. Le groupe pourrait ensuite convertir de manière unidirectionnelle les monnaies personnelles de ses membres en une monnaie de groupe fongible à un taux de change dynamique qui répondrait aux besoins du groupe au fil du temps. Cela permettrait aux Circles d'agir comme un terrain d'expérimentation pour de nombreuses expériences différentes en matière de réalité (et de moralité) consensuelle, tout en offrant aux utilisateurs individuels la liberté de revenir aux monnaies personnelles si un groupe devient corrompu ou inutile. Les possibilités de nouvelles formes politiques sont nombreuses, mais le potentiel de systèmes de niveau 2 au-dessus du protocole de base est de loin l'aspect le plus spéculatif du projet et reste une question résolument ouverte pour des recherches ultérieures.

## Conclusion

Le système monétaire Circles a été conçu pour commencer à créer une économie RUB dès aujourd'hui. Nous pensons que la combinaison de la résilience et de l'accessibilité mondiale offerte par la technologie blockchain est un catalyseur clé qui rendra le revenu de base universel réalisable au cours de la prochaine génération. La résistance native de notre système aux attaques de type Sybil et son identité décentralisée intégrée en font un centre d'intérêt idéal pour les actions de terrain et l'organisation communautaire, qui ont été les caractéristiques des économies UBI envisagées au fil des ans. Nous étudions activement les implications économiques des différents compromis de conception de Circles dans le but de créer un système monétaire aussi utile et stable que possible. Notre feuille de route est conçue pour commencer à tester des applications dès que possible afin de voir comment cette nouvelle forme d'échange de valeurs se comporte dans des contextes économiques réels. Nous sommes très enthousiastes quant au potentiel de ce projet et espérons qu'il pourra servir de base essentielle à un nouveau paradigme économique dans les décennies à venir.

```
Alice joins the system, creating AliceCoin
PersonalCoins are all minted at a rate of 1 per minute
Five minutes later Alice has 5 AliceCoin and Bob joins the system, creating BobCoin
Alice transfers her 5 AliceCoin to Bob
Alice has 0 PersonalCoins and Bob has 5 AliceCoin
Five minutes later Alice has 5 AliceCoin while Bob has 5 AliceCoin and 5 BobCoin
```

### Inflation

In order to disincentivize hoarding and to encourage economic activity, the system will introduce an annual inflation schedule. This is demurrage by other means, where all personal currencies will issue progressively larger amounts of tokens per year, paid out per second. New users will always start issuing at a rate that is consistent with all other personal currencies.

```
Alice joins the system, creating AliceCoin
PersonalCoins are all minted at a rate of 1 per minute, and inflates 100% every five minutes
Five minutes later Alice has 5 AliceCoin and Bob joins the system, creating BobCoin
Alice transfers her 5 AliceCoin to Bob
Alice has 0 PersonalCoins and Bob has 5 AliceCoin
Five minutes later Alice has 5 AliceCoin while Bob has 5 AliceCoin and 5 BobCoin
Alice has 5 coins total, and Bob has 10 coins total. The difference between their holdings is 5 and Alice has .5 (half) the amount of coins that Bob has.
The issuance rate inflates 100% and is now 2 coins per minute.
Five minutes later Alice has 15 AliceCoin while Bob has 5 AliceCoin and 15 BobCoin.
Alice has 15 coins total and Bob has 20 coins total. The difference between their holdings is still 5, but now Alice has .75 (three quarters) the amount of coins that Bob has. The relative difference between their holdings is decreasing.
```

## Trusting Currency

In order to create useful money, users trust each other’s currencies. Trust is what facilitates exchange in the system. When a user trusts a currency, they tell the system that it is equivalent to any other Circles currencies that they already have. This means that anyone with this trusted currency can automatically trade it for one of your Circles currencies at a one-to-one exchange rate.

```
Bob trusts AliceCoin
Bob has 10 CarolCoin
Dave has 10 AliceCoin
Dave gives 5 AliceCoin to Bob and takes 5 CarolCoin from him
```

Another way of thinking about trust is that it is the user telling the system that they acknowledge specific currencies as “real money.” Since any blockchain accounts can join the system and start minting currency, a trivial attack is to create multiple accounts and register with each to get multiple basic incomes. This is called a Sybil attack in computer security terms. The existence of trust relationships is how users protect themselves from fake accounts by specifying which ones they know for a fact represent an individual human’s primary account, forming a native Sybil resistance in the system. At a community level, trust in the system means that there are resources one can claim for Circles.

Because of the danger of any account becoming a sybil at any time, trust can also always be revoked. When and if trust is revoked, the person who is revoking trust can still spend the coins of the person they are untrusting, but they will not receive any new coins from that user via transitive transactions.

Because trust is a way to protect from counterfeit currencies, it is a serious responsibility on the part of the user. Users will have to rely heavily on mutual connections when making direct peer-to-peer trust relationships, and new users with no trust connections will have to get their closest loved ones to be their initial connections. It is theoretically possible to increase fungibility and ease of use in Circles with professional services (validators) which can act as brokers for trust, or with pooled group currencies, which can enforce their own policies for joining, however, these possible extensions will not be present in the first iteration of the Circles system. Further research on this subject is invited.

### Transitive Exchange

Trusting different currencies creates a useful form of money because of the transitive nature of social networks. Money is useful when it allows complete strangers to efficiently conduct business. When one stranger wants to send money to another in Circles, they automatically search for a transitive chain of trusted currencies between each other. The payer then trades along this chain of trusted currencies, one after the other, until they have one that the recipient accepts.

```
Bob trusts AliceCoin
Alice trusts CarolCoin
Alice has 10 AliceCoin
Carol has 10 CarolCoin
Carol wants to pay Bob 5 PersonalCoins
Carol gives 5 CarolCoin to Alice and takes 5 AliceCoin from her
Carol gives 5 AliceCoin to Bob
```

![Transitive exchange](assets/diagram_1.png)

The transaction can be extended to include multi-hop chains of trust as well:

```
Bob trusts AliceCoin
Alice trusts CarolCoin
Carol trusts DaveCoin
Alice has 10 AliceCoin
Carol has 10 CarolCoin
Dave has 10 DaveCoin
Dave wants to pay Bob 5 PersonalCoins
Dave gives 5 DaveCoin to Carol and takes 5 CarolCoin from her
Dave gives 5 CarolCoin to Alice and takes 5 AliceCoin from her
Dave gives 5 AliceCoin to Bob
```

![Transitive exchange with multi-hops](assets/diagram_3.png)

With this system, the connectedness of the social network serves as a direct measure of users’ ability to transact with each other. A familiar way of thinking about this is the famous six degrees of separation phenomenon that suggests everyone on earth is connected to everyone else by a chain of six people. Circles uses these chains to transact through the system. If a user is well-integrated into the network, with many connections to other well-integrated users, they will find it easier to send and receive personal currency.

### Limits to Trust

Because personal currencies are only able to travel through their networks of trust, the fungibility of a specific personal currency is a measure of how many other accounts trust it and the resources available in the network. This means that users who are new to the system and don’t have many trusted relationships have a less fungible currency than someone who is well-established in the network. It also means that the currency of new users gets more fungible over time as they create more trust relationships.

Since the system internally enforces a one-to-one exchange rate, and new users’ personal currencies are less fungible than established users personal currencies, a potential problem emerges:

```
25 people trust AliceCoin
Bob is new, so only Alice trusts BobCoin
Bob has 100 BobCoin
Alice has 100 AliceCoin
Bob gives 100 BobCoin to Alice and takes 100 AliceCoin from her
Bob can now spend money with 25 people (and their friends, and friends of friends, etc)
Alice can now only spend money with Bob
```

![Trust limits](assets/diagram_4.png)

In the example above, Alice needs a way to acknowledge that BobCoin is real money, while limiting her exposure to it while Bob is still new. Circles achieves this with Trust Limits. When you create a trust relationship in Circles, you have the option to include the maximum amount of your total coins you are willing to hold in another user’s currency.  A trust limit is expressed as a percentage.. With trust limits, Alice is able to help Bob integrate into the system in a more controlled way:

```
25 people trust AliceCoin
Bob is new, so only Alice trusts BobCoin
Alice puts a limit of 10 BobCoin per month on her trust
Bob has 100 BobCoin
Alice has 100 AliceCoin
Bob gives 10 BobCoin to Alice and takes 10 AliceCoin from her
Bob can now spend one tenth of his money with 25 people (and their friends, and friends of friends, etc)
Alice sets aside her 10 BobCoins to spend once Bob has made more trust relationships
Bob gets 10 people to trust BobCoin
Alice raises her trust limit on BobCoin to 100 per month
```

Trust limits reduce the risk of trusting new accounts to the system, making it easier for them to build trust relationships.

### Defending Against Fake Accounts

As we’ve shown, fake accounts are a primary consideration when designing protections into the system. Since money can be spent indirectly through transitive connections, let’s show how Circles defends against fake accounts that are connected to your friends:

```
Bob trusts AliceCoin
Alice makes a fake account and trusts FakeCoin
Alice has 10 AliceCoin
FakeAlice has 10 FakeCoin
Alice wants to buy something worth 10 PersonalCoins from Bob using FakeCoin
FakeAlice gives 10 FakeCoin to Alice and takes 5 AliceCoin from her
FakeAlice gives 10 AliceCoin to Bob
```

![Fake accounts](assets/diagram_2.png)

This example demonstrates that Bob can only ever receive money that he trusts, and Alice can only ever spend money that other users trust in turn. Even if Alice makes 100 fake accounts and has them all trust each other, she will never be able to spend more than the amount of AliceCoins she has, since that’s the only account that other users will trust. This is why it is crucial that users take direct peer-to-peer trust relationships seriously.

## Complementary Currency

Circles is not meant to become the world's dominant currency, cryptographic or otherwise. Rather, it is a complementary currency, working in harmony alongside other stores of value and mediums of exchange, itself embedded in a diversity of currencies. In the future Circles could even serve as a foundational "hard currency" for a more flexible group currency built on top. It is ideal as a hard currency because the supply of specific individual currencies is perfectly predictable and the aggregate system is highly resilient due to its lack of reliance on a centralized identity provider. To determine group membership, this hypothetical group currency could function with an arbitrary business logic such as being part of a business barter network, or democratically via geographically bounded assemblies. The group could then one-way convert the personal currencies of its members into a fungible group currency at a dynamic exchange rate that meets the group's needs over time. This would allow Circles to act as a staging ground for many different experiments in consensus reality (and morality), while still providing individual users the freedom to revert back to personal currencies if any one group becomes corrupted or useless. The possibilities for new political forms are numerous, but the potential for layer 2 systems on top of the base protocol is by far the most speculative aspect of the project and remains a decidedly open question for further research.

## Conclusion

The Circles Money System was designed to get started creating a UBI economy today. We believe that the combination of resilience and global accessibility afforded by blockchain technology is a key catalyst that makes a Universal Basic Income achievable within the next generation. Our system's native Sybil-attack resistance and inbuilt decentralized identity make it an ideal focus for grassroots action and community organization, which have been hallmarks of envisioned UBI economies over the years. We are actively researching the economic implications of Circles' various design tradeoffs with the intention of creating a money system that is as useful and stable as possible. Our roadmap is designed to get started with trial applications as soon as possible in order to see how this new form of value exchange behaves in real economic settings. We are very excited about the potential of this project and hope that it can serve as a critical foundation for a new economic paradigm in the decades to come.
