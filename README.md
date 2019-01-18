# What did I learned today

## What is it

**wdilt** aims to:

- encourage me to **learn something new** every day
- see my progression **over time**
- become **better**

> As much as possible related to the **front-end development**

## Generate a Markdown Calendar

```JavaScript
class Calendar(year, month)
```

### Parameters

- `year` : the year of the **month you choose**
- `month` : the **month** you choose

### Run it

- **Create** a new `Calendar` with specific parameters
- Add `.fill()` **method**
- run `node app.js` in a **large terminal** to see the **results**

__Exemple:__

```JavaScript
const December2018 = new Calendar(2018, 12).fill();
```

> You can see the result in markdown below ⬇️

# Progression

## Janvier 2019
| 🗓 |        Su       |        Mo       |        Tu       |        We       |        Tu       |        Fr       |        Sa       |
| -- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- | --------------- |
| W1 |                 |                 |[01](#2019-01-01)|[02](#2019-01-02)|[03](#2019-01-03)|[04](#2019-01-04)|[05](#2019-01-05)|
| W2 |[06](#2019-01-06)|[07](#2019-01-07)|[08](#2019-01-08)|[09](#2019-01-09)|[10](#2019-01-10)|[11](#2019-01-11)|[12](#2019-01-12)|
| W3 |[13](#2019-01-13)|[14](#2019-01-14)|[15](#2019-01-15)|[16](#2019-01-16)|[17](#2019-01-17)|[18](#2019-01-18)|[19](#2019-01-19)|
| W4 |[20](#2019-01-20)|[21](#2019-01-21)|[22](#2019-01-22)|[23](#2019-01-23)|[24](#2019-01-24)|[25](#2019-01-25)|[26](#2019-01-26)|
| W5 |[27](#2019-01-27)|[28](#2019-01-28)|[29](#2019-01-29)|[30](#2019-01-30)|[31](#2019-01-31)|                 |                 |

### 2019-01-16

C'est muy bien ! On commence avec un peu de rigueur et de bonnes résolutions !

Aujourd'hui j'ai appris à comprendre [wdilt](https://github.com/blyndusk/wdilt) (merci [blyndusk](https://github.com/blyndusk) <3) :
- Command line interpretor (cli) **wdilt** :
    - mordre
    - `mordre`
    - ``mordre``
    - 
    ```Javascipt
    mordre
    ```
    - (mordre)
    - [mordre]()
    - "mordre"
    - *mordre*
    - **mordre**
    - ***mordre***
- Avec GitHub : 
`git init wdilt_jay` (créer dossier local)<br>
Create repository (créer repo distant sur github.com)<br>
`git clone http://github.com/...`(cloner le nouveau repo)<br>
Copier/coller les fichiers utiles dans le nouveau dossier cloné<br>
Raccourcis zsh : 
    - `git statut`= `gst`
    - `git add *` = `gaa`
    - `git commit -m "***-**-**"` = `gc -m"****-**-**"`
    - `git push`= `gp`
    - `git pull`= `gl`(récuperer modification du repo)
- Sur le web :
[SQL](https://sql.sh/ressources/document/mysql-aide-memoire-sql.pdf) Memento des commandes
- Tips : [htop](https://hisham.hm/htop/) <br>This is htop, an interactive process viewer for Unix systems. It is a text-mode application (for console or X terminals) and requires ncurses : `brew install htop`

### 2019-01-17

### tuto-php
Aujourd'hui, j'ai commencé ma journée en utilisant **tuto-php** mis en place par mon mentor de 3ème année et un ancien professeur de PHP : 
- Lancer docker (si pas installé, faire : `brew install docker cask && brew cask install docker`)
- Se mettre dans le dossier **tuto-php** puis :
    - Pour rebuild docker : `docker build -t [nom] dossier`
    - Démarrage avec : `docker run -it --rm -p 8088:80 tuto`
    - Lancer avec : `./run`

### 2019-01-18

### [devbreak.fr](https://github.com/sundowndev/devbreak.fr)

Découvert du répo [devbreak.fr](https://github.com/sundowndev/devbreak.fr) d'un élève de W2 de l'école : [Raphael](https://github.com/sundowndev) (Remerciement ^^).<br> 
***Devbreak*** est une sorte de boite à outils. Le contenu étant limité, je vais le modifier avec mes infos afin de l'améliorer et de faire une petite update. <br>
Le contenu est gérer en Javascript se qui rend d'autant plus simple son utilisation.