# Le Racket des Carottes — Cahier de conception

## Vision
Jeu de poursuite humoristique dans un grand pré en 3D cartoon, vu en trois quarts. Le joueur incarne tour à tour trois poneys et tente de dérober les carottes de Papa avant qu'il ne s'échappe du pré.

## Décor
Prairie verdoyante avec relief léger, fleurs, arbres, clôtures en bois, barrière et petite écurie. Caméra trois quarts, déplacements fluides, éclairage naturel. Direction artistique soignée, personnages reconnaissables et animés : pas d'emojis ni de portraits découpés servant de sprites.

## Personnages
- **Quoccinelle** : poney alezan rond, crinière rousse/blonde ébouriffée. Attaque **Le Plaquage de Bidou** : percute Papa, fait tomber des carottes. Réplique : « C'EST PAS DU GRAS, C'EST DE LA PUISSANCE ! »
- **Mandarine** : poney alezan, longue crinière blonde, marque blanche au front. Attaque **Le Fouet Blond** : tourbillon de crinière, Papa perd ses repères. Réplique : « L'ORÉAL, PARCE QUE JE LE VAUX BIEN ! »
- **Pétrole** : petit poney brun chocolat, longue crinière blond cendré. Attaque **La Tornade Miniature** : tourne très vite autour des jambes de Papa. Réplique : « PETITE MAIS DANGEREUSE ! »
- **Taiho** : bouledogue anglais trapu, robe bringée et blanche. Attaque ultime **Le Plaquage Judiciaire** : saute sur Papa de façon burlesque, le seau s'envole et Taiho vole une chaussure. Réplique : « VOUS ÊTES EN ÉTAT D'ARRESTATION ! »
- **Papa** : environ 60 ans, grand, casquette, tenue campagne chic, bottes en caoutchouc, seau de carottes. Il cherche à sauver ses carottes et atteindre la sortie.

## Boucle de jeu
1. Papa entre dans le pré avec son seau.
2. Le joueur se déplace librement, change de poney et déclenche des capacités à temps de recharge.
3. Les collisions cartoon font tomber des carottes à ramasser. Papa essaie de récupérer son seau et de fuir.
4. Le joueur gagne en récupérant toutes les carottes avant la fuite de Papa ; sinon, il recommence.
5. Un combo des trois poneys peut débloquer l'intervention spectaculaire de Taiho.

## Écran de victoire
« PAPA A ENCORE ÉTÉ VICTIMISÉ ! » — « 3 poneys, 1 Taiho, 0 carotte, 0 dignité. »

## Exigences de réalisation
- Prototype navigateur jouable sur ordinateur et mobile.
- Priorité à un **vrai environnement 3D** et à une boucle de jeu agréable avant les cinématiques avancées.
- Les modèles 3D et animations devront être créés ou obtenus sous licence appropriée, puis adaptés aux photos de référence.
- Ne pas publier le dépôt ni déployer publiquement sans accord.

## Jalons
1. Terrain 3D, caméra, déplacements et contrôles tactiles.
2. Papa, seau et carottes : poursuite, ramassage, score et victoire/défaite.
3. Modèles distincts des trois poneys et capacités.
4. Taiho, combos, effets, sons et cinématique finale.
5. Optimisation mobile et déploiement privé de démonstration.
