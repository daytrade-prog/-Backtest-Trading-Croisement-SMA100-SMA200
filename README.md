 Backtest d'une stratégie de croisement de moyennes mobiles (SMA100/SMA200)
(Analyse de stratégie technique)



Description
Ce projet met en œuvre une stratégie simple d'analyse technique basée sur le croisement de deux moyennes mobiles :  
 La SMA100 (moyenne mobile sur 100 jours)  
 La SMA200 (moyenne mobile sur 200 jours)

Logique de la stratégie
 -Un signal d'achat (position acheteuse) est généré lorsque la SMA100 passe au-dessus de la SMA200  
 -Un signal de vente (position vendeuse) est généré lorsque la SMA100 passe en dessous de la SMA200
 -La stratégie **prend une seule position à la fois soit en position acheteuse, soit en position vendeuse



 Fonctionnalités
Téléchargement automatique des données historiques de l'ETH via yfinance
 Calcul des moyennes mobiles SMA100 et SMA200
 Génération automatique des signaux d'achat/vente

Technologies utilisées
 -Python 3.x
 -Pandas
 -Numpy
 -Jupyter Notebook



