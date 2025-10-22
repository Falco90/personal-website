+++
title = "CryptoChess"
date = 2025-05-01
+++

CryptoChess is a proof-of-concept platform that allows chess players to compete for crypto prizes on the Flare blockchain. This is achieved by using data from the public chess.com JSON API inside smart contracts.

A tournament organizer can create a chess tournament on chess.com and invite the players. Then the organizer can create a smart contract for the tournament and set a participation fee through the CryptoChess web UI. The players can join the tournament contract on CryptoChess by providing their chess.com username. If the username is part of the playerslist of the tournament, obtained through the chess.com API, the player can pay the participation fee and be registered on the smart contract.

After all players have paid the participation fee, the tournament can be played on chess.com. After the tournament is finished, the prize money (the sum of all participation fees) is released and automatically sent to the winner's wallet address.
