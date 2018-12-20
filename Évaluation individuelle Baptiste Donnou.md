# Évaluation individuelle

## Programmation - Coaching

```
Nom : Donnou	
Prénom : Baptiste
URL de votre compte Github : https://github.com/Baptiste-Donnou
```

## Déroulé et fonctionnement. 

L'évaluation est à faire sur [Typora](https://typora.io/). Les réponses sont à écrire dans les blocks de code. 
Pour la partie Ruby, testez votre code sur [repl.it](https://repl.it/) et copiez le dans les blocks de code prévu à cet effet. 
Une fois fini, pushez votre feuille sur Github, dans un nouveau repository que vous appelerez "evaluation-inseec".
L'évaluation est individuelle et durera 1h30. Elle intègre des notions d'HTML, CSS, Ruby et computer science. 

![alt](https://media.giphy.com/media/26xBBfd0ii1khakpy/giphy.gif)

## Quelques mises en garde.

Je connais très bien ce merveilleux site qu'est Wikipédia. Je vous saurais gré de ne pas me remplir certaines questions avec les définitions de Wikipédia. Accessoirement, je sais aussi faire une recherche Google. Si j'ai un doute, je n'hésiterais pas rechercher "Qu'est-ce qu'une API" et comparer les définitions en tête de recherche avec les votre. Si je trouve une similarité trop grande et que je doute de votre bonne foi, je n'hésiterais pas à mettre 0 à la question. 
Pareil pour la copie sur les voisins. Si c'est trop gros et que j'ai un doute trop prononcé... 🔫

![alt](https://media.giphy.com/media/BtedgmzGNCiuk/giphy.gif)



------

### 1. Avec vos mots, expliquez l'interaction client-serveur

```t
Un client est un ordinateur qui va envoyer une requette à un serveur pour lui demander d'afficher une page.
```



 ### 2. HTML est un langage côté... 

```
Client notre ordinateur
```



### 3. Donnez-moi la structure de base d'une feuille HTML

```html
<!DOCTYPE html>
<!-- Completez après cette ligne -->
<html>
    <link>
      <meta charset="utf-8">
    <title> </title>
    <body>
        
    </body>
</html>
```



### 4. Changez la couleur du texte "J'adore la programmation" en rose en utilisant du CSS.

```html
<div>
   <p>J'adore la programmation</p>
</div>
```

```css
/* Ecrire le code CSS sous cette ligne */

.p {
    color:deeppink ;
}

```



### 5. Qu'est-ce que Bootstrap ?

```
Bootstrap est un outil de design de site. En liant notre feuille a bootstrap un certain sype de code est lisible via bootstrap. 
```



### 6. Reprenez votre code de la question 3 et ajoutez Bootstrap à votre feuille HTML, au bon endroit.

```html

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <link rel="stylesheet" type="text/css" href="style.css">

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title></title>
  </head>
  <body> <body>
</html>
```



### 7. Mettez ces trois divs sur le même plan horizontal avec trois colonnes de même taille.

```html
<div class="container">
  <div class="row">
    <div class="col-sm">
        Google
    </div>
    <div class="col-sm">
Microsoft    </div>
    <div class="col-sm">
Apple
      
      </div>
  </div>
</div>
      
```



### 8. Avec le même code, changez le texte par le logo de la marque en question

```html
<div class="container">
  <div class="row">
    <div class="col-sm">
        Google
        <img src="https://www.google.fr/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" height="42" width="42" alt="Google">
    </div>
    <div class="col-sm">
Microsoft
        
         <img src="https://1000logos.net/wp-content/uploads/2016/10/Apple-Logo.png" alt="Apple">
      </div>
    <div class="col-sm">
Apple
   <img src="https://1000logos.net/wp-content/uploads/2016/10/Apple-Logo.png" alt="Apple" >
      </div>
  </div>
</div>
      
```

 

### 9. Toujours sur le même bout de code, rendez les logos cliquables. Quand on clique sur le logo, on doit arriver sur le site officiel de la marque.

```html

<!doctype html>
<html lang="en">
  <head>
    <!-- Required meta tags -->
    <link rel="stylesheet" type="text/css" href="style.css">

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">

    <title></title>
  </head>


  <body>
    
<div class="container">
  <div class="row">
    <div class="col-sm">
       <a href="https://www.google.com">
<img border="0" alt="google" src="https://www.google.fr/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png" width="100" height="100">
    </div>
    <div class="col-sm">
        
<a href="https://www.microsoft.com">
<img border="0" alt="microsoft" src="http://itac.ca/wp-content/uploads/2014/05/microsoft-logo.jpg" width="100" height="100">

      </div>
    <div class="col-sm">
<a href="https://www.apple.com">
<img border="0" alt="apple" src="https://1000logos.net/wp-content/uploads/2016/10/Apple-Logo.png" width="100" height="100" hover >
   
      </div>
  </div>
</div>
      
      
  </body>
</html>
```

![Mon gars sûr !](https://media.giphy.com/media/l0K4mbH4lKBhAPFU4/giphy.gif)

### 10. Parlons Ruby. Ruby est un langage côté...

```
Machines ou serveur c'est comme on veut 
```



### 11. Listez-moi tous les types de données que vous connaissez.

```
Les Num / boulean / strings
```



### 12. Assignez à des variables votre prénom, nom et le lien de votre compte Github puis affichez chacune des variables. En 6 lignes.

```ruby
nom = "Baptiste"
prenom = "Donnou"
github = "https://github.com/Baptiste-Donnou"

 puts "le compte de #{nom} #{prenom} est:  {https://github.com/Baptiste-Donnou}"
```



### 13. Assignez 674 et 311 à des variables `a` et `b` et stockez le résultat `a` modulo `b` dans une variable `c` et affichez la. 

```ruby

a = 674
b = 311  

a*b =c
c= result
puts c 


```



### 14. Qu'est-ce qu'une gem ? 

```texte
Il s'agit de codes produits par des développeurs extérieurs à RUBY.
```



### 15. Qu'est-ce qu'une API et qu'est-ce qui nous permet de nous y connecter ?

```
C'est une Clé,elle permet de parler au serveur et lui donner des ordres. 
```



### 14. On va créer un script pour dire bonjour ou bonsoir, en fonction de l'heure de la journée. Votre script doit demander à l'utilisateur de rentrer son prénom. Si `hour` est inférieur à 12, lui dire `Bonjour Anthony` sinon `Bonsoir Anthony` (évidemment, le prénom doit être celui renseigné par l'utilisateur).

```Ruby
# <- Demander le prénom de l'utilisateur

hour = 15 
prenom = gets.chomp
if hour < 12
puts "bonjour #{prenom}"
else
puts "Bonsoir #{prenom}"
end

# Si hour est inférieur à 12
	# j'écris mon code permettant de dire Bonjour prénom

# sinon
	# j'écris mon code permettant de dire Bonsoir prénom

```



### 15. Itérer sur l'array contenant des noms de twitos un peu famous et follow chacun d'eux grâce à une méthode trouvée dans la [doc de la gem twitter](https://github.com/sferik/twitter). Pas besoin de lancer le code et de faire la partie authentification. Juste le bloc d'itération suffira. 

```ruby
{
  "users": [
      ["@richardbranson", "@jeffweiner", "@LinkedInQueen", "@ericschmidt", "@elonmusk", "@petecashmore", "@SteveForbesCEO", "@mtbarra"]
  ],
  "next_cursor": 1489467234237774933,
  "next_cursor_str": "1489467234237774933",
  "previous_cursor": 0,
  "previous_cursor_str": "0"
}
```



### 16. Félicitations, vous êtes arrivé·e à la fin, pushez cette feuille sur votre Github dans un repo appelé `evaluation-inseec`. N'oubliez pas de remplir le premier block avec votre identité tout en haut ! 

![alt](https://media.giphy.com/media/l0MYJnJQ4EiYLxvQ4/giphy.gif)

