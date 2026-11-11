# Plan d'Activité : Structure du réseau
*(Étude du fonctionnement d'un réseau local et de la communication Internet)*

## 1. Déroulement

### Phase 1 : Le Puzzle du Réseau (Découverte Active – 15 min)
1. **Préparation :** Des cartes sont distribuées aux élèves, chacune représentant un composant du schéma (Ordinateur, Imprimante, Routeur, Internet, etc.).
2. **Consigne :** Les élèves, en groupes, doivent assembler ces cartes de manière à créer un circuit logique où l'information peut circuler de l'appareil local vers Internet et vice-versa.
3. **Observation :** L'enseignant observe les tentatives des groupes pour identifier intuitivement l'ordre et les connexions.
4. **Correction :** La structure est établie au tableau.

### Phase 2 : La Vulgarisation Technique (Formalisation – 15 min)
1. L'enseignant introduit le vocabulaire technique. Il utilise le schéma reconstitué pour définir le rôle de chaque élément.
2. **Focus IP :** Introduction de l'Adresse IP comme "identité numérique".
3. **Focus Routeur :** Explication du rôle de l'aiguillage (trouver la bonne destination) et de la traduction d'adresses (passer de l'IP Privée à l'IP Publique).
4. **Synthèse :** L'enseignant récapitule la différence de rôle entre le Réseau (l'ensemble), la Connexion (le lien), l'Adresse IP (l'identité) et le Routeur (le gestionnaire).

## 2. Objectifs

*   **Cognitif :** Distinguer les fonctions des différents éléments (ordinateur, routeur, réseau).
*   **Savoir-faire :** Utiliser, adéquatement en contexte, les termes *connexion, routeur, réseau, adresse IP*.
*   **Compréhension :** Expliquer le concept de base du fonctionnement d'un réseau (données circulant via des chemins identifiés par des adresses).

## 3. Contenu
*(Ce contenu sera le support de l'enseignant pendant la phase de vulgarisation.)*

| Terme | Définition Technique | Analogie Pédagogique |
| :--- | :--- | :--- |
| **Réseau** | L'ensemble des équipements connectés qui permettent l'échange de données (LAN = Local Area Network). | Un quartier où tous les habitants peuvent se parler. |
| **Connexion** | Le lien physique (câble) ou logique (Wi-Fi) qui permet le flux d'informations. | Les rues qui relient les maisons. |
| **Adresse IP** | Identifiant numérique unique attribué à chaque appareil pour que les données arrivent au bon destinataire. | L'adresse postale exacte de la maison. |
| **Routeur** | Dispositif qui agit comme un aiguilleur. Il lit l'adresse de destination pour diriger les paquets de données vers le bon réseau. | Le centre de distribution qui trie et envoie les colis. |
| **IP Privée** | Adresse utilisée uniquement à l'intérieur du réseau local (ex: 192.168.3.x). Non accessible directement de l'extérieur. | L'adresse intérieure du quartier. |
| **IP Publique** | Adresse unique visible sur Internet (ex: 82.25.124.28). Elle sert de porte d'entrée pour le monde extérieur. | L'adresse officielle de la ville. |

## 4. Prérequis
*   Connaissance générale de ce qu'est un ordinateur.
*   Capacité à suivre une consigne et à travailler en groupe.
*   Compréhension basique du concept de communication (un message doit aller de A à B).

## 5. Matériel
*   Cartes à manipuler représentant les éléments du schéma (ordinateur, routeur, globe, etc.) avec leurs adresses IP.
*   Feutres et papier ou tableau blanc pour la reconstruction collective.
*   Le schéma initial à afficher comme référence finale.

## 6. Difficultés Possibles et Atténuation

| Difficulté Anticipée | Explication du problème | Stratégie d'Atténuation |
| :--- | :--- | :--- |
| **Confondre la fonction du Routeur et l'adresse IP.** | Les élèves voient l'appareil physique (le routeur) et pensent qu'il est uniquement une adresse. | Insister sur la *fonction* (aiguillage) avant la *caractéristique* (adresse IP). Le routeur est le "chef de l'aiguillage". |
| **Incompréhension de la traduction (NAT).** | Difficulté à accepter que le réseau local ait une seule identité face à Internet. | Utiliser l'analogie de l'interprète. Le routeur "traduit" le paquet de données en utilisant son IP publique pour le monde extérieur, puis "re-traduit" la réponse pour l'envoyer au bon appareil privé. |
| **Simplification excessive d'Internet.** | Ne pas voir qu'Internet est un "réseau de réseaux", et non un seul point. | Définir Internet comme une couche complexe ; le rôle du routeur est simplement le *pont* entre votre petite ville (votre LAN) et ce monde extérieur. |

## 7. Prolongements
*   **Cas pratique de débogage :** Présenter un schéma où une connexion est incorrecte (ex: deux appareils locaux tentent d'utiliser la même adresse IP). Demander aux élèves d'identifier le conflit et d'expliquer sa conséquence (absence de communication).
*   **Sécurité :** Introduction des notions de pare-feu (firewall) et de sécurité du réseau, expliquant que le routeur est la première ligne de défense.

##  8. Attendus du Tronc Commun
Ce plan d'activité permet d'atteindre directement les objectifs suivants du référentiel :
*   **Utiliser, adéquatement en contexte, les termes :** connexion, routeur, réseau, adresse IP.
*   **Maîtriser la relation de cause à effet :** Comprendre pourquoi chaque appareil doit avoir une adresse IP pour pouvoir échanger des données sur un réseau.
*   **Expliquer la distinction des réseaux :** Faire la différence entre l'environnement de travail privé (LAN et IP privée) et le monde public (Internet et IP publique).
