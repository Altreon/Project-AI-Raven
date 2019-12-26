# Intelligence Artificielle pour le Jeu Vidéo : Fuckin-Raven :sleeping_bed: :sleeping_bed: :sleeping_bed:

**Un groupe de personnes qui savent pas trop ce qu'elles font :+1:**


![Image of albert einstein](https://upload.wikimedia.org/wikipedia/commons/thumb/1/14/Albert_Einstein_1947.jpg/220px-Albert_Einstein_1947.jpg)
> La vie, c'est comme une bicyclette, il faut avancer pour ne pas perdre l'équilibre.
> - Albert Einstein


## Fonctionnalités demandées ***(90pts)*** :heart_eyes: :

- [ ] Enrichir les règles concernant le choix d’une arme de type RocketLauncher :astonished: ***Anthouane (5pts)***
  - Il s’agit d’augmenter jusqu’à 5 le nombre d’ensembles pour les variables floues (maximum de 25 règles) : 
    - Distance à la cible
    - État des munitions
    - Désirabilité
    
- [ ] Modifier la visée et le tir de l’agent en introduisant un comportement flou :confounded: ***Anthouane (5pts)***
  - A traves un ensemble de nouvelles règles à formuler
  
- [ ] Introduire un joueur (humain) dans le jeu :rage: ***Matmat (30pts)***
  - Capacités joueur humain :
    - [ ] Le joueur humain peut créer une équipe d’agent-raven qui attaque une même cible
    - [ ] Choisir une cible, un agent ennemi
  - Règles équipes :
    - [ ] Quand un membre de l’équipe meurt, il laisse ses armes à un des coéquipiers dans un endroit connu et dédié à l’équipe
    - [ ] Communication au sein de l’équipe basée sur le protocole de communication du TP1
    
- [ ] Créer un bot-apprenant capable d’apprendre :sob: ***Léooooooooo & Samsam (40pts)***
  - Le bot a toutes les capacités de base des autres bot mais ne sait pas tirer
  - Fonctionnalités à lui faire apprendre : le tir
  - Tâches :
    - [ ] Créer des données d’apprentissage à partir des observations de tirs du joueur humain
    - [ ] Faire jouer l’humain pendant un certain temps pour générer échantillon apprentissage (afin de collecter les différentes situations de tir et celles où le joueur n’a pas pu tirer). 
    - [ ] Décrire les situations par :
      - Distance en pixels du bot-ennemi
      - Visibilité
      - Angle
      - Quantité de munitions
      - Type d’arme utilisé
      - Niveau de vie du bot-ennemi
      - Autres paramètres jugés utiles
    - [ ] Implémenter réseaux de neurones (celui proposé ou n'importe quel autre en C++) de type perceptron ou un perceptron multi-couches
    - [ ] Adapter le RN à la décision de tirer en fonction des variables d’entrées citées ci-dessus
    - [ ] Mesure la performance du bot apprenant en comptant le nombre de bot-ennemis atteints et sa durée de vie
  
- [ ] Améliorer le comportement de l’agent-raven :confused: ***(10pts)***
  - Introduire un nouveau but qui peut s’inscrire dans une stratégie d’attaque ou un autre contexte d’application

## Fonctionalités bonus ***(60pts)*** :dizzy_face: :

- [ ] Création d’une nouvelle arme : grenade ***(10pts)***
- [ ] Stratégie de comportement au sein d’une équipe ***(10pts)***
  - Introduire un mouvement de groupe de type Offsetpoursuit en protégeant le leader
- [ ] Stratégie d’attaque guidée par le leader de l’équipe ***(10pts)***
- [ ] Compétition entre deux bots ayant des comportements différents ***(10pts)***
- [ ] Compétition entre deux équipes de bots ayant des comportements différents ***(10pts)***
- [ ] Qualité ***(10pts supp)***
  - professionnalisme
  - originalité
  - réalité
  - toute autre nouvelle fonctionnalité non demandée


### Equipe Tsuneni Glitch :sunglasses:

##### Avec :

- **Matmat :ghost:**
- **Léooooooooo :alien:**
- **Anthouane :smiley_cat:**
- **Samsam :older_woman:**

![Image of team](https://image.shutterstock.com/image-photo/african-american-businessman-boss-group-260nw-665953069.jpg)

### Rappel fonctionnement IA

![Image of IA](https://photos.lci.fr/images/613/344/intelligence-artificielle-machine-circuits-cerveau-e7eaa0-0@1x.jpeg)

