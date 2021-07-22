# Ethereum-Wallet-Solidity

Dans cette vidéo nous allons apprendre à créer un portefeuille (Wallet) Ethereum avec Solidity (Smart Contract).

Dans un premier temps, nous allons utiliser remix.ethereum.org comme IDE pour créer nos deux contrats :

- Le premier contrat est Owner.sol. Ce dernier nous permettra de donner un propriétaire au deuxième contrat Wallet.sol. Owner.sol contiendra un modifier qui pourra s'appliquer aux fonctions créées dans le contrat Wallet.sol.

- Le deuxième contrat est Wallet.sol. Il contiendra des structures (structs) et des mapping afin de construire les données utiles au contrat.
Ensuite, nous aurons une fonction getBalance() pour obtenir le nombre de Wei total présent sur le contrat.
Une autre fonction permettra de mettre de l'argent sur le Wallet.
Enfin, nous aurons deux fonctions permettant de retirer de l'argent du contrat.
