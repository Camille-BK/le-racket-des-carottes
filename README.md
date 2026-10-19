# 🥕 Le Racket des Carottes 🐴

### Trois poneys. Un bouledogue. Un papa. Et beaucoup trop de carottes.

**Le Racket des Carottes** est un jeu vidéo humoristique en **3D cartoon** qui se déroule dans un grand pré verdoyant. Trois poneys particulièrement déterminés ont une mission : dérober toutes les carottes de Papa.

Mais Papa ne compte pas se laisser faire. Armé de son seau de carottes et de ses bottes en caoutchouc, il tente désespérément d'échapper à ses poursuivants. Et lorsque la situation dégénère… **Taiho entre en scène**.

## 🌿 L'univers du jeu

L'aventure se déroule dans une prairie en 3D, entourée de clôtures en bois, d'arbres et d'une petite écurie.

Le joueur explore librement cet environnement avec une caméra en vue trois quarts, poursuit Papa, récupère les carottes et utilise les capacités spéciales des différents personnages.

**Objectif : récupérer toutes les carottes avant que Papa ne réussisse à quitter le pré.**

## 🐴 Les personnages

### Quoccinelle — La force tranquille (ou presque)
Poney alezan aux formes généreuses et à la crinière ébouriffée.

**Attaque spéciale : LE PLAQUAGE DE BIDOU**

> « C'EST PAS DU GRAS, C'EST DE LA PUISSANCE ! »

### Mandarine — La diva du pré
Magnifique ponette alezane à la longue crinière blonde et à la marque blanche sur le front.

**Attaque spéciale : LE FOUET BLOND**

> « L'ORÉAL, PARCE QUE JE LE VAUX BIEN ! »

### Pétrole — Petite mais redoutable
Petit poney brun chocolat à la crinière blond cendré. Sa taille est trompeuse : personne ne tourne aussi vite qu'elle.

**Attaque spéciale : LA TORNADE MINIATURE**

> « PETITE MAIS DANGEREUSE ! »

### 🐶 Taiho — L'arme secrète
Bouledogue anglais trapu à la robe bringée et blanche. Son intervention spectaculaire est prévue dans une future version.

**Attaque ultime : LE PLAQUAGE JUDICIAIRE**

> « VOUS ÊTES EN ÉTAT D'ARRESTATION ! »

### 👨 Papa — La victime officielle
Un homme d'environ 60 ans, adepte du style campagne chic, reconnaissable à sa casquette et à ses bottes en caoutchouc.

**Mission :** protéger ses précieuses carottes et sortir du pré avec un minimum de dignité.

*Spoiler : ce n'est pas gagné.*

## 🎮 Gameplay

- Exploration et déplacements libres dans un environnement 3D.
- Possibilité de changer de poney pendant la partie.
- Poursuite de Papa et récupération des carottes.
- Attaques spéciales propres à chaque personnage (première logique de jeu déjà présente).
- Combos et intervention ultime de Taiho **prévus**.
- Animations et interactions humoristiques à enrichir.
- Contrôles pour ordinateur et téléphone.

**Ce n'est pas un jeu de combat traditionnel** : pas d'arène façon Street Fighter. C'est un jeu de poursuite dans un pré.

## 🛠️ Technologies

Le prototype actuel utilise :

- **JavaScript** pour la logique du jeu.
- **Three.js** pour l'environnement et les personnages 3D.
- **HTML / CSS** pour l'interface et les commandes.
- **GitHub** pour le suivi du développement.

## 🚧 État du développement

**Statut : prototype initial — en cours de développement.**

Le fichier [`index.html`](./index.html) contient une première version jouable avec un pré en 3D, une caméra, des déplacements, des carottes à ramasser et un Papa qui essaie de s'échapper.

Les modèles 3D sont **provisoires**. Les apparences fidèles des animaux, leurs animations personnalisées, les effets spéciaux avancés et l'intervention de Taiho ne sont pas encore réalisés.

## 🚀 Lancer le prototype

1. Télécharger ou cloner le dépôt.
2. Ouvrir un terminal dans le dossier du projet.
3. Lancer un serveur web local :

   ```bash
   python -m http.server 8000
   ```

4. Ouvrir [http://localhost:8000](http://localhost:8000) dans un navigateur moderne.

Une connexion Internet est nécessaire pour charger Three.js depuis son CDN.

### Commandes

| Action | Ordinateur |
| --- | --- |
| Se déplacer | `ZQSD`, `WASD` ou flèches |
| Attaquer | `Espace` |
| Changer de poney | `Tab` |

Sur téléphone, les commandes tactiles sont affichées à l'écran.

## 🗺️ Feuille de route

1. **Base jouable :** pré 3D, caméra, déplacements et collecte de carottes.
2. **Gameplay :** améliorer les déplacements de Papa, les collisions et les attaques.
3. **Personnages :** créer des modèles et animations distincts et fidèles à Quoccinelle, Mandarine et Pétrole.
4. **Taiho :** ajouter son intervention et les combos.
5. **Finitions :** effets visuels, sons, cinématique de victoire et optimisation mobile.

Pour le cahier de conception détaillé, voir [`GAME_DESIGN.md`](./GAME_DESIGN.md).

## 🎯 Notre ambition

Créer un jeu familial original, drôle et visuellement soigné, inspiré de véritables animaux et de leurs personnalités.

Pas de combats traditionnels, pas d'arène : simplement un immense pré, des courses-poursuites absurdes, des attaques spectaculaires et un père qui regrette d'avoir acheté des carottes.

---

## 🏆 Victoire !

### PAPA A ENCORE ÉTÉ VICTIMISÉ !

*3 poneys. 1 Taiho. 0 carotte. 0 dignité.*

🥕 **Le Racket des Carottes — Aucun papa n'a été blessé pendant le développement de ce jeu.**
