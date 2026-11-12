# Projet-choix-multiple

## Arborescence de La Traque de Gollum

Les flèches représentent les choix du joueur. Les fins rouges sont des échecs ; la fin verte est la victoire. Chaque fin permet de recommencer à l’accueil (ces liens sont omis pour garder le schéma lisible).

```mermaid
flowchart TD
    A["Accueil : ordre de mission à Barad-dûr"] -->|Rejoindre la Porte Noire| B["La Porte Noire"]
    B -->|Suivre les empreintes| C["Les Marais des Morts"]
    B -->|Prendre le sentier des bois| D["La Lisière des bois"]

    C -->|Obéir au Nazgûl| E["Les Traces de Gollum"]
    C -->|Prétendre que Gollum est mort| F["FIN : La Colère du Mordor"]
    D -->|Contourner les Elfes| E
    D -->|Charger la patrouille| G["FIN : Une charge très courte"]

    E -->|Suivre le passage rocheux| H["Le Concours de flatterie"]
    E -->|Rejoindre le feu| I["Le Feu dans la vallée"]
    I -->|Reprendre la piste| H
    I -->|Rester avec les déserteurs| J["FIN : La Dernière Écuelle"]

    H -->|Le soleil et Sauron envient votre majesté| K["Un compliment salvateur"]
    H -->|Vieux lézard et beaux restes| L["FIN : Un Orc bien cuit"]
    H -->|Même les pierres vous contemplent| L
    K -->|Entrer dans la grotte| M["La Grotte de Gollum"]

    M -->|Piège avec la corde et le poisson| N["Une prise très bavarde"]
    M -->|Se jeter sur Gollum| O["FIN : Un pas de trop"]
    N -->|Ramener Gollum au capitaine| P["VICTOIRE : Retour à Barad-dûr"]
    N -->|Le libérer contre un trésor| Q["FIN : Les Promesses de Gollum"]

    classDef echec fill:#421e1e,stroke:#d78989,color:#fff;
    classDef victoire fill:#203d2a,stroke:#8ac69a,color:#fff;
    class F,G,J,L,O,Q echec;
    class P victoire;
```

17 pages : 10 scènes de départ ou de progression, 6 fins d’échec et 1 fin de victoire.

