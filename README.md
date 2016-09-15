# Arbitrage_Bot

Création d'un robot d'arbitrage. 
Préambule : Ce robot d'arbitrage fonctionne avec une seule pair d'actif. Ici : BTC et EUR. On achete et on vend des BTC ou des euros. Rien d'autres.

Prérequis
-Définition du capital d'investissement : 200€ (100€ sur Kraken.com, 100€ sur Bitstamp. Sur chaque site, on va acheter 50 de BTC au prix du marché. Peu importe le cout, c'est le capital pour notre entrée sur le marché.)
  Ce capitale d'investissement est déjà considéré comme perdu. Il a été décidé de jeter 200€ ds cette aventure et de ne pas regarder ce qu'il adviendra de cette somme. 
  
-Marché : BTC/EUR UNIQUEMENT ! 
-Sites cibles : Kraken.com , Bitstamp.net (pour le moment, on se cantonne à 2 sites) 

Procédure :
-Recueil de données : -Prix d'achat de BTC sur Kraken.com 
                      -Prix d'achat de BTC sur Bitstamp.net 
                      -Prix de vente de BTC sur Kraken.com
                      -Prix de vente de BTC sur Bitstamp.net
                      -Frais de transaction sur Kraken.com
                      -Frais de transaction sur Bitstamp.net

-Calcul du cout des frais de transaction. 
-Définition d'un opportunité d'arbitrage : -Si prix de vente (frais inclus) < prix d'achat (frais inclus), déclenchement d'une commande
-Passage des ordres au prix du marché. (ordres quasi instantannés) 
-??????
-Profit
