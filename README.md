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

### 2019-01-23

*PASSAGE A WINDOBS...*

### Les ténèbres ou la mise en place de mon environnement de travail

- PATH : Les modification sous W10
    - Dans Rechercher, lancez une recherche et sélectionnez : Système (Panneau de configuration)
    - Cliquez sur le lien Paramètres système avancés.
    - Cliquez sur Variables d'environnement. Dans la section Variables système, recherchez la variable d'environnement PATH et sélectionnez-la. Cliquez sur Modifier. Si la variable d'environnement PATH n'existe pas, cliquez sur Nouvelle.
    - Dans la fenêtre Modifier la variable système (ou Nouvelle variable système), indiquez la valeur de la variable d'environnement PATH. Cliquez sur OK. Fermez toutes les fenêtres restantes en cliquant sur OK.
    - Ouvrez à nouveau la fenêtre d'invite de commande et exécutez votre code Java.

- La recherche de la console correcte
    - Le plus utilisé : [cmdr](http://cmder.net/)
    - Le mieux (le mien) : [babun](http://babun.github.io/) *"a windows shell you will love"*
        - Developper tools <3 :
            - programming languages (Python, Perl, etc.)
            - git (with a wide variety of aliases and tweaks)
            - UNIX tools (grep, wget, curl, etc.)
            - vcs (svn, git)
            - oh-my-zsh
            - custom scripts (pbcopy, pbpaste, babun, etc.)
        - faire : `install.bat`
        - Mise en place du thème [theme](https://www.grafikart.fr/blog/terminal-windows-babun)
        - télécharger et installer [les polices](https://github.com/abertsch/Menlo-for-Powerline) une à une puis double-cliquer dessus
        - modification mon fichier d'interface et de configuation situé dans "C:\Users\joshua\.babun\cygwin\home\joshua"
            - **~/.minttyrc** (par défaut il est vide)
            ```.txt
            Font=Menlo for Powerline
            FontHeight=9

            ForegroundColour=208,208,208
            BackgroundColour=21,21,21
            CursorColour=253,157,79
            Black=21,21,21
            BoldBlack=80,80,80
            Red=172,65,66
            BoldRed=116,44,45
            Green=144,169,89
            BoldGreen=102,119,61
            Yellow=244,191,117
            BoldYellow=238,158,45
            Blue=106,159,181
            BoldBlue=70,120,141
            Magenta=170,117,159
            BoldMagenta=130,80,120
            Cyan=117,181,170
            BoldCyan=77,144,133
            White=208,208,208
            BoldWhite=245,245,245
            ```
            - ~/.zshrc
            ```.txt
            ZSH_THEME="babun"
            devient
            --> ZSH_THEME="agnoster"
            ```
- installation des programmes suivant :
    - [wampserverx64](https://sourceforge.net/projects/wampserver/files/latest/download) : ATTENTION Il faut aussi installer les dernières versions de "visual c++ 2010/2012/2015" en version x64 sinon erreur avec les dll (msver110/msver120/vcruntime140)
    - [php](https://windows.php.net/download/) : ***.zip*** VC15 x64 Non Thread Safe (2019-Jan-10 00:54:24)  et modifier le PATH
    - [mySQL](https://dev.mysql.com/downloads/file/?id=483327) et modifier le PATH
    - [docker]() :
        - `./run`
        - `docker run --rm -p 8088:80 tuto`
        - chrome : http://localhost:8088/basics