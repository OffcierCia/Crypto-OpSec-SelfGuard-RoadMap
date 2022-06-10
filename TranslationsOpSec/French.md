**Nous rassemblons et discutons ici des meilleures recherches et données OpSec relatives à la DeFi, à la Blockchain et aux cryptos - toute contribution est bienvenue.**

**N'hésitez pas à soumettre une pull request, qu'il s'agisse de petites corrections, de traductions, de documents ou d'outils que vous aimeriez ajouter.**

[![Soutenir le projet](https://img.shields.io/badge/Support-Project-critical)](https://github.com/OffcierCia/DeFi-Developer-Road-Map#support-project) [![Soutenir sur Gitcoin](https://img.shields.io/badge/Support%20via-GitCoin-yellowgreen)](https://gitcoin.co/grants/3150/defi-developer-roadmap)
  [![Base de recherche](https://img.shields.io/badge/Research-Base-lightgrey )](https://github.com/OffcierCia/ultimate-defi-research-base)
       [![Mail](https://img.shields.io/badge/Mail-offcierciapr%40protonmail.com-brightgreen)](mailto:offcierciapr@protonmail.com) 

```
_________                        __           ________          _________               .____    .__          __   
\_   ___ \_______ ___.__._______/  |_  ____   \_____  \ ______ /   _____/ ____   ____   |    |   |__| _______/  |_ 
/    \  \/\_  __ <   |  |\____ \   __\/  _ \   /   |   \\____ \\_____  \_/ __ \_/ ___\  |    |   |  |/  ___/\   __\
\     \____|  | \/\___  ||  |_> >  | (  <_> ) /    |    \  |_> >        \  ___/\  \___  |    |___|  |\___ \  |  |  
 \______  /|__|   / ____||   __/|__|  \____/  \_______  /   __/_______  /\___  >\___  > |_______ \__/____  > |__|  
        \/        \/     |__|                         \/|__|          \/     \/     \/          \/       \/        
```

> Note : OpSec est un terme issu de l'armée, qui signifie sécurité opérationnelle. Il a été largement utilisé pour décrire les mesures de sécurité dans diverses activités sensibles, et plus récemment aussi dans la gestion des crypto-monnaies.

<details>
<summary>Traductions</summary>
<br />

- [Portuguese-Brazilian](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/Portuguese.md)
- [Russian](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/Russian.md)
- [French](https://github.com/OffcierCia/Crypto-OpSec-SelfGuard-RoadMap/blob/main/TranslationsOpSec/French.md)

</details>


# Guide d'auto-protection OpSec

**| Notes de l'auteur (en anglais):**

- [Tout sur la sécurité des NFTs ](https://graph.org/NFT-security-01-28) 
- [Scanners de données du navigateur ](https://graph.org/Checkers-01-19)
- [Tous les outils de sécutité ETH existants](https://graph.org/ETHSec-Tools-02-13)
- [Tous les bons TG de communautés de dev ](https://graph.org/Crypto-Telegram-Channels--Chats-04-19)
- [Ressources pour les attaques connues sur les utilisateurs et les smart-contracts](https://graph.org/Data-02-14)
- [Anti-sèche Solidity, liste des outils et références ](https://graph.org/Solidity-Cheatsheets-Pack-03-20)
- [Toutes les attaques et vecteurs d'attaques sur les smart-contracts et les utilisateurs](https://graph.org/All-known-smart-contract-side-and-user-side-attacks-and-vulnerabilities-in-Web30--DeFi-03-31)
- [Liste et références de tous les outils d'analyse des transactions, de crypto-forensics et d'investigation possibles dans une seule note.](https://graph.org/TX-Analysis-tools-04-19)
- [Principes clés du stockage de crypto cold wallet, attaques, méthodes de défense et meilleures pratiques](https://graph.org/Key-principles-of-storing-crypto-cold-wallet-attacks-defense-methods-best-practices--Bonus-04-23)


#### Problème 1

Utilisez un fournisseur de messagerie sécurisé comme protonmail ou tutanota. Utilisez un VPN de confiance comme Mullvad ou ProtonVPN. 

[En savoir plus](https://www.youtube.com/channel/UCYVU6rModlGxvJbszCclGGw)

---

#### Problème 2

Utilisez des emails différents / des mots de passe forts différents. Stockez-les au même endroit. N'utilisez jamais de mots de passe répétitifs, en particulier pour les comptes contenant des informations personnelles identifiables et sensibles (par exemple Facebook, Gmail, AppleID, Twitter, banques/paiements, comptes crypto...). Utilisez des mots de passe générés de manière aléatoire et comportant plus de 20 caractères. Si vous constatez une activité suspecte au niveau des mots de passe ou un échec de connexion sur l'un de vos comptes, changez tous vos mots de passe, en commençant par les comptes sensibles et d'autorisation, tels que votre messagerie principale et vos comptes bancaires/crypto. [Keepass](keepass.info) ou BitWarden sont de bons gestionnaires de mots de passes.

[En savoir plus](https://blog.keys.casa/7-ways-to-level-up-your-bitcoin-opsec/)

---

#### Problème 3

Ne liez jamais vos numéros de téléphone aux plateformes crypto. Utilisez des e-sims multiples de confiance si vous devez lier un numéro. Pour verrouiller votre carte SIM, contactez votre opérateur de téléphonie mobile. Demandez-lui de ne JAMAIS modifier votre numéro de téléphone/SIM à moins que vous ne vous présentiez physiquement dans un magasin spécifique avec au moins deux pièces d'identité. Cela devrait empêcher les pirates d'appeler Orange, SFR ou Free, en se faisant passer pour vous, et de leur demander de transférer votre numéro de téléphone sur un nouveau téléphone.

[En savoir plus](https://medium.com/the-business-of-crypto/fundamentals-of-opsec-in-crypto-7844ba701b1d)

---

#### Problème 4

Au lieu du système 2FA par SMS, utilisez Google Authenticator (iOS/Android) ou l'application Authy pour iOS ou Android. Google Authenticator est plus rapide et plus facile à configurer, mais Authy offre des options de récupération de compte plus robustes. N'oubliez pas que les codes générés par les applications 2FA sont spécifiques à chaque appareil. Votre compte n'est pas sauvegardé dans le nuage Google ou iCloud, donc si vous perdez votre téléphone, vous devrez passer un certain temps à prouver votre identité pour restaurer votre 2FA. La sécurité supplémentaire en vaut la peine !

[En savoir plus](https://www.threatstack.com/blog/five-opsec-best-practices-to-live-by)

---

#### Problème 5

Utilisez le stockage à froid, ET un porte-monnaie "chaud" séparé. Utilisez le multisig (gnosis-safe par exemple) ou au moins un porte-monnaie matériel. Ne stockez jamais votre seed phrase sous forme numérique. Les seed phrases sont destinées à être stockées sur la carte papier fournie avec les portefeuilles matériels ! Cela signifie qu'il ne faut jamais la taper, la stocker en ligne ou prendre une photo de la carte. Stockez votre clé sur un support physique.

[En savoir plus](https://digitalguardian.com/blog/what-operational-security-five-step-process-best-practices-and-more)

---

#### Problème 6

Backupez vos clés hors ligne (sur du papier par exemple). Stockez-les dans un coffre-fort. 

[En savoir plus](https://www.gocivilairpatrol.com/programs/emergency-services/operations-support/operational-security-opsec)

---

#### Problème 7

Ne faites jamais rien que vous ne comprenez pas. Vérifiez toujours quel token vous approuvez, quelle transaction vous signez, quels actifs vous envoyez, etc. - soyez extrêmement précis lorsque vous effectuez une opération financière. N'oubliez pas que l'un des vecteurs d'attaque possibles consiste à vous mettre dans une situation qui vous incitera à faire quelque chose de malicieux (connexion ou autre) en vous faisant croire que vous faites une autre chose normale. Vous pouvez installer un antivirus comme malwarebytes ou Comodo ou DrWeb, mais il ne vous sera d'aucune utilité si vous ne le comprenez pas. Maintenez à jour votre ensemble d'outils de défense de base. 

[En savoir plus](https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817)

---

#### Problème 8

Soyez prudent lorsque vous utilisez votre adresse postale personnelle réelle en ligne pour des livraisons. Les violations de données sont désormais quotidiennes, et nombre d'entre elles concernent les noms et adresses des clients. Votre adresse physique n'est pas aussi facilement modifiable qu'un numéro de téléphone ou une adresse électronique, alors faites particulièrement attention à l'endroit où vous l'utilisez sur Internet. Si vous commandez une pizza avec de la crypto-monnaie, demandez à ce qu'elle soit enlevée plutôt que livrée. Lorsque vous faites des achats en ligne, utilisez une adresse différente (et accessible au public) pour la livraison des colis. Vous pouvez par exemple utiliser votre lieu de travail ou des points-relais.

[En savoir plus](https://www.cnbc.com/2017/11/02/heres-how-to-protect-your-bitcoin-and-ethereum-from-hacking.html)

---

#### Problème 9

Rappelez-vous : vous pourriez être une cible. Nous sommes une cible naturelle pour toutes sortes d'attaques - des cybercriminels de base à l'espionnage concurrentiel (cela semble dramatique, mais c'est réel !). Cela dit, le secteur dans lequel vous évoluez n'a pas vraiment d'importance. Si vous possédez des informations sensibles ou exclusives (et, avouons-le, la plupart des personnes travaillant dans le domaine de la crypto en possèdent), vous pourriez très bien être une cible. C'est une bonne chose à garder à l'esprit.

[Lire plus](https://www.cnbc.com/2021/06/11/tips-to-help-keep-your-crypto-wallet-secure.html)

[En savoir plus](https://www.usenix.org/system/files/1401_08-12_mickens.pdf)


---

#### Problème 10

Restez vigilant - Créez une culture du scepticisme dans votre entreprise dans laquelle les employés prennent l'habitude de vérifier à deux fois avant de cliquer sur un lien ou de répondre à une demande d'informations sensibles, et vous aurez une organisation beaucoup plus sûre dans l'ensemble. 

[Lire plus](https://www.ledger.com/academy/security/hack-wifi)

[Lire plus](https://anonymousplanet.org/guide.html)


---

#### Problème 11

L'OpSec intervient souvent dans des contextes publics. Par exemple, si des membres de votre équipe discutent de sujets liés au travail lors d'un déjeuner, d'une conférence ou autour d'une bière, il y a de fortes chances que quelqu'un puisse les entendre. Comme on dit, les murs ont des oreilles, alors assurez-vous de ne pas discuter d'informations sensibles concernant votre entreprise en public.  De nombreux faux-pas OpSec peuvent être évités en étant plus conscient de votre environnement et du contexte dans lequel vous parlez : ce que vous dites, où vous êtes, à qui vous parlez et qui pourrait vous entendre. Il est bon de passer en revue les "interdits" propres à votre entreprise lors de l'intégration et de les rappeler périodiquement aux employés. 

[En savoir plus](https://www.youtube.com/watch?v=hxHqE2W8scQy)

---

#### Problème 12

Identifiez vos données sensibles, notamment vos recherches sur les produits, la propriété intellectuelle, les états financiers, les informations sur les clients et les informations sur les employés. C'est sur ces données que vous devrez concentrer vos ressources pour les protéger.


[En savoir plus](https://www.youtube.com/watch?v=0aSQMeoz9ow)

---

#### Problème 13

Identifiez les menaces possibles. Pour chaque catégorie d'informations que vous jugez sensibles, vous devez identifier les types de menaces qui existent. Si vous devez vous méfier des tiers qui tentent de voler vos informations, vous devez également faire attention aux menaces internes, telles que les employés négligents et les travailleurs mécontants et revanchards.

[En savoir plus](https://datatracker.ietf.org/wg/opsec/documents/)

---

#### Problème 14

Analysez les failles de sécurité et autres vulnérabilités. Évaluez vos mesures de protection actuelles et déterminez quelles sont, le cas échéant, les failles ou les faiblesses qui pourraient être exploitées pour accéder à vos données sensibles.

| Exemple : Utilisez [AirGap](http://airgap.it), [OpenSource Wallet](http://alphawallet.com), [OpenSource Password storage](http://keepass.info), multi-sig, [Selfhosted link system](https://obsidian.md), lisez cette [fiche](https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md), utilisez [OpSec Services](https://github.com/x13a/Duress) - (vous pouvez également utiliser [tenderly.co](https://tenderly.co) alertes contrat/adresse + SMS). Pour les transactions, utilisez [escrow](github.com/JackBekket/escrow-eth/blob/master/contracts/EscrowAdvansed.sol) et [tx alarm clock](github.com/ethereum-alarm-clock/ethereum-alarm-clock) et des services spéciaux comme [safient.io](https:safient.io), [sarcophagus.io](https://sarcophagus.io), [safehaven.io](https://safehaven.io).

N'oubliez jamais les méthodes de défense non triviales comme celles que j'ai partagées [ici](https://twitter.com/officer_cia/status/1516181065634824203) et [ici](https://twitter.com/officer_cia/status/1516581048792289280).

[En savoir plus](https://www.lopp.net/bitcoin-information/security.html)

---


#### Problème 15

Évaluez le niveau de risque associé à chaque vulnérabilité. Classez vos vulnérabilités en fonction de facteurs tels que la probabilité qu'une attaque se produise, l'étendue des dommages que vous subirez et la quantité de travail et de temps dont vous aurez besoin pour vous rétablir. Plus une attaque est probable et dommageable, plus vous devez donner la priorité à l'atténuation du risque associé.

[En savoir plus](https://www.reddit.com/r/opsec/)

---

#### Problème 16

Mettez en place des contre-mesures. La dernière étape de la sécurité opérationnelle consiste à créer et à mettre en œuvre un plan pour éliminer les menaces et atténuer les risques. Il peut s'agir de mettre à jour votre matériel, de créer de nouvelles politiques concernant les données sensibles ou de former les employés aux bonnes pratiques de sécurité et aux politiques de l'entreprise. Les contre-mesures doivent être directes et simples. Les employés doivent être en mesure de mettre en œuvre les mesures requises de leur part, avec ou sans formation supplémentaire.

[En savoir plus](https://hackernoon.com/5-tips-to-prevent-hackers-from-stealing-your-crypto-assets-e2243zig)

---

#### Problème 17

Mettez en place un double-contrôle. Assurez-vous que les personnes qui travaillent sur votre réseau ne sont pas les mêmes que celles chargées de la sécurité.

[En savoir plus](https://arxiv.org/abs/2106.10740)

---

#### Problème 18

Automatisez les tâches pour réduire le besoin d'intervention humaine. L'homme est le maillon faible des initiatives de sécurité opérationnelle de toute organisation car il fait des erreurs, néglige des détails, oublie des choses et contourne des processus.

[En savoir plus](https://web.mit.edu/smadnick/www/wp/2019-05.pdf)

[En savoir encore plus](https://medium.com/immunefi/how-not-to-get-hacked-on-telegram-2db2b93a5fa2v)


---

#### Problème 19

La réponse aux incidents et la planification de la reprise après un sinistre sont toujours des éléments cruciaux d'une bonne posture de sécurité. Même lorsque les mesures de sécurité opérationnelles sont solides, vous devez disposer d'un plan pour identifier les risques, y répondre et atténuer les dommages potentiels.

[En savoir plus](https://airgapcomputer.com)

[En savoir encore plus](https://trustwallet.com/blog/how-to-stay-safe-on-the-internet-crypto-guide)


---

#### Problème 20

La gestion des risques implique d'être capable d'identifier les menaces et les vulnérabilités avant qu'elles ne deviennent des problèmes. La sécurité opérationnelle oblige les responsables à se plonger dans leurs opérations et à déterminer où leurs informations peuvent être facilement violées. En examinant les opérations du point de vue d'un tiers malveillant, les responsables peuvent repérer des vulnérabilités qu'ils n'auraient pas remarquées autrement, afin de mettre en œuvre les contre-mesures appropriées pour protéger les données sensibles. Le plus important ici est de comprendre conventionnellement le processus d'attaque. Leur vecteur. 

Prenons un exemple : un pirate vous a livré un RAT (cheval de Troie permettant un accès à distance) sur votre ordinateur et maintenant le pirate a deux possibilités. Si le hack est "fan", c'est-à-dire massif, alors le voleur volera vos cookies, et d'autres informations, de sorte que plus tard les données seront vendues sur le marché secondaire pour le traitement de ces logs. La sécurité opérationnelle classique mentionnée dans les paragraphes 1 à 10 devrait permettre d'y remédier. 

La deuxième option est une attaque directe dans laquelle un pirate créera une page de phishing sur votre routeur, par laquelle vous entrerez votre mot de passe (DNS poisoning). Autrement dit, pour prévenir une attaque, l'idéal est de séparer les machines et les réseaux. Vous devez également vérifier les certificats. 

Le hacker peut aussi faire une attaque sur le presse-papiers lorsque vous copiez l'adresse d'envoi et qu'elle se transformera en l'adresse du hacker. De plus, le début et la fin coïncideront avec l'adresse d'origine, ce qui constituera un mélange de vecteurs d'attaque - vecteur d'ingénierie sociale, phishing et malware classique. 

[En savoir plus](https://www.youtube.com/watch?v=pGcerfVqYyU)

[En savoir encore plus](https://medium.com/@cryptochatjoe/remaining-anonymous-in-todays-crypto-market-a-101-guide-for-the-badass-not-so-techies-7091edffa9aa)



---

#### Problème 21

Votre niveau d'opsec dépend généralement de votre modèle de menace et de l'adversaire auquel vous vous confrontez. Il est donc difficile de définir la qualité de votre sécurité opérationnelle. Mais je dirais que ça a l'air plutôt bon. Je vous recommande de regarder : 

[Cette vidéo](https://www.youtube.com/watch?v=9XaYdCdwiWU)

[Cette autre vidéo](https://www.youtube.com/watch?v=ixLuRvYlrlw)


---

#### Problème 22

Si vous utilisez un smartphone, soyez extrêmement vigilant.

[En savoir plus](https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817)

---

#### Problème 23

N'interagissez qu'avec les protocoles DeFi en lesquels vous avez confiance - Prenez le temps de lire les concepts que nous avons déjà abordés, tels que le staking, le yield farming, le NFT farming, et recherchez tous les autres nouveaux termes que vous pourriez rencontrer avant de déposer des crypto-monnaies dans une DApp qui propose l'une de ces stratégies d'investissement. 

[En savoir plus](https://github.com/OffcierCia/ultimate-defi-research-base)

[En savoir encore plus](https://assets.website-files.com/5ffef4c69be53b44bd10b438/6012f54022181b0d0a3a948c_CryptoCurrency%20Security%20Standards%20Checklist.pdf)


### Table des matières

| Vidéos                                        |
|----------------------------------------------|
| https://www.youtube.com/watch?v=hxHqE2W8scQy |
| https://www.youtube.com/watch?v=0aSQMeoz9ow  |
| https://www.youtube.com/watch?v=pGcerfVqYyU  |
| https://www.youtube.com/watch?v=9XaYdCdwiWU  |
| https://www.youtube.com/watch?v=ixLuRvYlrlw  |

| Lecture                                                                                                                                    |
|------------------------------------------------------------------------------------------------------------------------------------------|
| https://blog.keys.casa/7-ways-to-level-up-your-bitcoin-opsec                                                                             |
| https://medium.com/the-business-of-crypto/fundamentals-of-opsec-in-crypto-7844ba701b1d                                                   |
| https://www.threatstack.com/blog/five-opsec-best-practices-to-live-by                                                                    |
| https://digitalguardian.com/blog/what-operational-security-five-step-process-best-practices-and-more                                     |
| https://www.gocivilairpatrol.com/programs/emergency-services/operations-support/operational-security-opsec                               |
| https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817                                                 |
| https://www.cnbc.com/2017/11/02/heres-how-to-protect-your-bitcoin-and-ethereum-from-hacking.html                                         |
| https://www.cnbc.com/2021/06/11/tips-to-help-keep-your-crypto-wallet-secure.html                                                         |
| https://www.ledger.com/academy/security/hack-wifi                                                                                        |
| https://datatracker.ietf.org/wg/opsec/documents/                                                                                         |
| https://www.lopp.net/bitcoin-information/security.html                                                                                   |
| https://www.reddit.com/r/opsec/                                                                                                          |
| https://hackernoon.com/5-tips-to-prevent-hackers-from-stealing-your-crypto-assets-e2243zig                                               |
| https://arxiv.org/abs/2106.10740                                                                                                         |
| https://web.mit.edu/smadnick/www/wp/2019-05.pdf                                                                                          |
| https://airgapcomputer.com                                                                                                               |
| https://joelgsamuel.medium.com/how-to-keep-your-smartphone-safe-from-spying-d7d50fbed817                                                 |
| https://assets.website-files.com/5ffef4c69be53b44bd10b438/6012f54022181b0d0a3a948c_CryptoCurrency%20Security%20Standards%20Checklist.pdf |
| https://blog.eduonix.com/cryptocurrency/cryptocurrency-security-checklist-investors-adopt/                                               |
| https://github.com/jlopp/physical-bitcoin-attacks/blob/master/README.md                                                                  |
| https://cryptosec.info/checklist/                                                                                                        |



## Soutenir le projet:

Le soutien est **très** important pour moi, avec cela je peux passer moins de temps au travail et faire ce que j'aime - éduquer les utilisateurs de DeFi & Crypto :sparkling_heart :

Si vous voulez soutenir mon travail, vous pouvez m'envoyer un don à l'adresse :

- **[0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A](https://etherscan.io/address/0xB25C5E8fA1E53eEb9bE3421C59F6A66B786ED77A)** — ERC20 & ETH [officercia.eth](https://etherscan.io/enslookup-search?search=officercia.eth)

- **[17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU](https://blockchair.com/bitcoin/address/17Ydx9m7vrhnx4XjZPuGPMqrhw3sDviNTU)** - BTC

##


(👍 ͡❛ ͜ʖ ͡❛)👍
