### Dependencies 
A installer avec la commande ``gem install``

* sinatra
* dm-core
* dm-timestamps
* do_sqlite3
* dm-sqlite-adapter
* dm-migrations
* authorization

===============

### Sinatra et DataMapper

Attention : ce code rentre dans le dur, l'idée encore une fois n'est pas de tout comprendre et de tout copier/coller dans son éditeur de texte, pour faire tourner l'application

Attachez-vous à lire/décrypter/comprendre le fichier adserver.rb (fichier principal)

### Quelques questions pour creuser

#### Sur l'application en elle-meme (http://www.sinatrarb.com/intro-fr.html )
 - Pourquoi il y a t il autant de 'require' en début de fichier
 - Qu'est-ce qu'une dépendance ?
 - Combien y'a-t-il d'objet dans cette application ? comment les reconnait-on
 - Qu'est-ce qu'une requete GET / POST ?
 - Qu'est-ce qu'une route ?

#### Sur les vues html.erb
 - Ou sont les pages web, comment les appelent-t-on ?
 - A quoi sert le fichier layout.erb dans le dossier views ?

#### Sur la bases de données (http://datamapper.org/why.html )
 - Qu'est-ce que DataMapper, quel rapprochement avec ActiveRecord peut-on faire ?
 - Qu'est-ce qu'une migration ? Quelle lien fait-elle avec la base de donnée
 - Dans quel fichier devrait etre inscrit la base de données, si jamais dataMapper fonctionnerait.

    **N'hésitez pas a insérer entre chaque question, des liens qui vous ont aidés à répondre aux question ci-dessus**



### Pourquoi cette app ne fonctionne pas

Essayez de lancer l'application, elle ne marchera pas (c'est fait exprès). Il faut lire le code, ne pas juste vouloir essayer si ca marche. 

Il y a volontairement une erreur dans ce code (vieux de 4 ans). Aujourd'hui on ne peut plus installer facilement DataMapper. Il faut donc trouver un autre logiciel (ActiveRecord) pour faire le lien avec la base de donnée (ici Sqlite3)

Quand vous aurez compris un peu comment tout cela marche, et que  vous aurez fait votre petite application sinatra (todo, formulaire, blog) on pourra passer à Ruby on Rails !

# Remplacer DataMapper par ActiveRecord
