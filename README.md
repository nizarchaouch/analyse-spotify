![Spotify_Logo_RGB_Green.png](.//img/Spotify_Logo_RGB_Green.png)
# Introduction [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/nizarchaouch/analyse-spotify/master?labpath=Spotify.ipynb)
Cet ensemble de données se compose d'environ 600 chansons qui figuraient parmi les meilleures chansons de l'année de 2010 à 2019 (telles que mesurées par Billboard). Vous pouvez explorer des données de chansons intéressantes extraites de Spotify telles que les battements par minute, la quantité de mots prononcés, le volume et l'énergie de chaque chanson.
|    | Variable   | Explication                                                |
|---:|:-----------|:-----------------------------------------------------------|
|  0 | title      | Le titre de la chanson                                      |
|  1 | artist     | L'artiste de la chanson                                     |
|  2 | top genre  | Le genre de la chanson                                     |
|  3 | year       | L'année où la chanson était dans le Billboard                     |
|  4 | bpm        | Battements par minute : le tempo de la chanson                    |
|  5 | nrgy       | L'énergie de la chanson : des valeurs plus élevées signifient plus d'énergie (rapide, fort)  |
|  6 | dnce       | La dansabilité de la chanson : des valeurs plus élevées signifient qu'il est plus facile de danser sur  |
|  7 | dB         | Décibel : le volume de la chanson  |
|  8 | live       | Liveness : probabilité que la chanson ait été enregistrée avec un public en direct  |
|  9 | val        | Valence : des valeurs plus élevées signifient un son plus positif (joyeux) |
| 10 | dur        | La durée de la chanson |
| 11 | acous      | L'acoustique de la chanson : il est probable que la chanson soit acoustique|
| 12 | spch       | Speechines : des valeurs plus élevées signifient plus de mots parlés |
| 13 | pop        | Popularité : des valeurs plus élevées signifient plus de popularité|
#### 1.Préparation des données
Nous commençons par importer d'abord les bibliothèques qui nous aideront, puis nous enregistrons le jeu de données dans une variable
### 2.Obtenir des informations sur le database
L'ensemble de données a 603 lignes et 14 colonnes
### 3.Information de chaque caractéristique de l’ensemble de 
Comme l’ensemble de données ne contient pas de valeurs NaN, il est prêt pour une analyse ultérieure.données sous forme de moyenne, médiane, écart-type et autres.
### 4.Posons d'abord quelques questions
Pour mieux comprendre le contenu des données et ce que l'on peut s'attendre à y trouver, établissons d'abord quelques questions qui peuvent nous aider à cette fin.
* Quels ont été les genres les plus importants de la décennie ?
* Quels ont été les artistes les plus pertinents de la décennie ?
* Les chansons sont-elles devenues plus tristes ?
* Comment la variable énergie a-t-elle évolué ?
* Comment la variable dansabilité a-t-elle évolué ?
* Existe-t-il une corrélation entre les variables d'énergie, de danse et d'humeur ?
### 5.Quels ont été les genres les plus importants de la décennie ?
 La dance pop a dominé tout au long de la décennie. En plus de la "dance pop", des genres tels que la "pop" et la "pop canadienne" ont également été pertinents au cours de la décennie. Il ne fait aucun doute que, globalement, le genre pop et toutes ses variantes ont dominé la décennie.
 ### 6.Quels ont été les artistes les plus pertinents de la décennie ?
  Justin Bieber, même s'il est dans le top 10 des artistes avec 16 chansons, il n'a obtenu le placement que grâce à un énorme pic entre 2014 et 2016, ayant le reste du temps entre 0 et 2 chansons populaires. De la même manière, Lady Gaga est également une bonne cible à analyser : commençant fort en 2010-2011 avec 3 à 5 chansons faisant un énorme succès, elle a perdu sa popularité jusqu'en 2018-2019 où elle a obtenu une énorme augmentation sur les chansons populaires. C'est logique, puisque fin 2018 elle s'est fait connaître pour une chanson sur le film "A Star is Born"
  ### 7.Les chansons sont-elles devenues plus tristes ?
  Au milieu de la décennie, il y a eu une nette diminution de l'ambiance des chansons et cela s'est poursuivi jusqu'à la fin de la décennie, étant l'année 2017, l'année où les chansons redeviendraient positives.
  ### 8.Comment la variable énergie a-t-elle évolué ?
  Comme pour la variable d'humeur, l'énergie des chansons a également diminué au cours de la décennie.
  ### 9.Comment la variable dansabilité a-t-elle évolué ?
  Bien que le changement d'énergie et d'humeur des chansons ait été négatif, la danse des chansons montre une augmentation à la fin de la décennie.
  ### 10.Existe-t-il une corrélation entre les variables d'énergie, de danse et d'humeur ?
  Il n'y a pas de relation entre ces trois variables.
  ## Conclusion
  En conclusion, La dance pop était le genre le plus populaire de la décennie.
