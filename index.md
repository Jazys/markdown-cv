Jacquemet Julien
============

-------------------     ----------------------------
93 chemin des guilloudières         jacquemet.julien@gmail.com
Marcilloles                          @twitter_handle
FRANCE                           XXXXXXXXXX
-------------------     ----------------------------

Formation
---------

2010-2011
:   **Master MAE - Management des Administration et Entreprise**; IAE Grenoble

    *Gestion d'entreprise, économie, finance, droit du travail*

2006-2011
:   **Diplöme d'ingénieur Informatique et Réseaux, INP- **; ESISAR valence

    *Semestre Spécial MANINTEC: Management de l'innovation et la technologie*
    *Informatique, développement, réseaux, administration système*

Experience
----------

**Chargé de projets informatique**
2016-2021
* Gestion de projet de A à Z, allant de l'offre commerciale (Appel d'offre), conditionnement du besoin, mise en place de l'équipe, rédaction des documents techniques,
aide au développement, gestion de la sous-traitance, mise en place/écriture (script) des campagnes de tests et intégration, mise en place des sites pilotes et suivi/supports.

** ENEDIS (de 2017 à ajourd'hui) : Suivi client (réunion mensuel, assistance ..), mise en place de l'architecture backend, suivi et aide au déploiement logiciel Serveur et Embarqué (Yocto), développement des scripts de tests et mise en place de tests et recette. En charge des déploiements de sites pilotes (2) et support client.
** DIRNO, DIRIF ( de 2018 à aujourd'hui): Du démarchage commerciale jusqu'au déploiement logiciel, pilotage d'une équipe interne
** Tunnels (de 2016 à 2020) : Vuache, ATMB, Rocade L2, pilotage des développements, recette, installation et support
** ...


**Lead Developpeur / Gestion d'équipe**
2011-2020
Edition des documents techniques, mise en place de l'architecture, développement et intégration.

* Développement d'application sous Android
* Développement d'application en Python
* Développement d'application sous QT (C/C++) sous Linux et Windows (REST API)
* Développement de page page Web (JS, Jquery, HTML/CSS) pour la supervision
* Adaptation de logiciel OpenSource (Multi Language)

Technical Experience
--------------------

My Cool Side Project
:   For items which don't have a clear time ordering, a definition
    list can be used to have named items.

    * These items can also contain lists, but you need to mind the
      indentation levels in the markdown source.
    * Second item.

Open Source
:   List open source contributions here, perhaps placing emphasis on
    the project names, for example the **Linux Kernel**, where you
    implemented multithreading over a long weekend, or **node.js**
    (with [link](http://nodejs.org)) which was actually totally
    your idea...

Programming Languages
:   **first-lang:** Here, we have an itemization, where we only want
    to add descriptions to the first few items, but still want to
    mention some others together at the end. A format that works well
    here is a description list where the first few items have their
    first word emphasized, and the last item contains the final few
    emphasized terms. Notice the reasonably nice page break in the pdf
    version, which wouldn't happen if we generated the pdf via html.

:   **second-lang:** Description of your experience with second-lang,
    perhaps again including a [link] [ref], this time placing the url
    reference elsewhere in the document to reduce clutter (see source
    file). 

:   **obscure-but-impressive-lang:** We both know this one's pushing
    it.

:   Basic knowledge of **C**, **x86 assembly**, **forth**, **Common Lisp**

[ref]: https://github.com/githubuser/superlongprojectname

Extra Section, Call it Whatever You Want
----------------------------------------

* Human Languages:

     * English (native speaker)
     * ???
     * This is what a nested list looks like.

* Random tidbit

* Other sort of impressive-sounding thing you did


---
layout: default
---

Tired of using LaTeX to make your CV look pretty? Can't remember how to set margins in your TeX file? Refusing to compromise and "just use Word"?

[markdown-cv](http://elipapa.github.io/markdown-cv/) is a simple template to list all your accomplishments in a readable Markdown file. It uses CSS to style your text into a stylish web page. It can also be printed as PDF.

### what does that mean?

Write your CV like this...

<img src="img/mdown.png" style="width: 60%; -webkit-filter: drop-shadow(5px 5px 5px #222); filter: drop-shadow(5px 5px 5px #222);" >

and use [jekyll](https://jekyllrb.com/) or [github pages](https://pages.github.com/) to make it look like this..

<img src="img/output.png" style="width: 60%; -webkit-filter: drop-shadow(5px 5px 5px #222); filter: drop-shadow(5px 5px 5px #222);" >



## Usage

To start, simply [fork the markdown-cv repo](https://github.com/elipapa/markdown-cv)

![](https://help.github.com/assets/images/help/repository/fork_button.jpg)

and then [edit directly in github](https://help.github.com/articles/editing-files-in-your-repository/) the `index.md` file

![](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png)

adding your skills, jobs and education.

![](https://help.github.com/assets/images/help/repository/edit-readme-light.png)

To transform your plain text CV into a beautiful looking HTML page and share it you then have two options:

### 1) Using Github Pages to publish it online

1. Delete the existing `gh-pages` branch from your fork. It will only contain this webpage. You can either use git or [the github web interface](https://help.github.com/articles/creating-and-deleting-branches-within-your-repository/#deleting-a-branch)
2. Create a new branch called `gh-pages` (which will then be a copy of master)
3. Head to *yourusername*.github.io/markdown-cv to see your CV live.

Any change you want to make to your CV from then on would have to be done on the `gh-pages` branch and will be immediately rendered by Github Pages.

### 2) Build it locally
1. [install jekyll](https://jekyllrb.com/docs/installation/) on your computer. `gem install jekyll` will do for most users.
2. Clone your fork on your computer
3. Type `jekyll serve` and you'll be able to see your CV on your local host (the default address is http://localhost:4000).
4. You can edit the `index.md` file and see changes live in your browser.

## How do I print the PDF?
Whether you used Github Pages or a local installation of Jekyll, to print a PDF just press *Print* in your browser. Print specific [CSS media queries](http://www.joshuawinn.com/css-print-media-query/) will take care of the styling.

## is this the only style available?

The included CSS renders your CV in different styles:

- `kjhealy` the original default, inspired by [kjhealy's vita
template](https://github.com/kjhealy/kjh-vita)

<img src="img/styles/kjhealy.png" style="width: 60%; -webkit-filter: drop-shadow(5px 5px 5px #222); filter: drop-shadow(5px 5px 5px #222);" >

- `davewhipp` is a tweaked version of `kjhealy`, with bigger fonts and dates
  right aligned, authored by [David Whipp](https://davewhipp.github.io/markdown-cv/)

<img src="img/styles/davewhipp.png" style="width: 60%; -webkit-filter: drop-shadow(5px 5px 5px #222); filter: drop-shadow(5px 5px 5px #222);" >

To change the default style, one needs to simply change `site` the variable in the
`_config.yml` file.

Any other styling is possible. More CSS style contributions and forks are welcome!



### Author

Eliseo Papa ([Twitter](http://twitter.com/elipapa)/[GitHub](http://github.com/elipapa)/[website](https://elipapa.github.io)).

![Eliseo Papa](https://s.gravatar.com/avatar/eae1f0c01afda2bed9ce9cb88f6873f6?s=100)

### License

[MIT License](https://github.com/elipapa/markdown-cv/blob/master/LICENSE)

<a href="https://github.com/elipapa/markdown-cv" class="github-corner"><svg width="80" height="80" viewBox="0 0 250 250" style="fill:#151513; color:#fff; position: absolute; top: 0; border: 0; right: 0;"><path d="M0,0 L115,115 L130,115 L142,142 L250,250 L250,0 Z"></path><path d="M128.3,109.0 C113.8,99.7 119.0,89.6 119.0,89.6 C122.0,82.7 120.5,78.6 120.5,78.6 C119.2,72.0 123.4,76.3 123.4,76.3 C127.3,80.9 125.5,87.3 125.5,87.3 C122.9,97.6 130.6,101.9 134.4,103.2" fill="currentColor" style="transform-origin: 130px 106px;" class="octo-arm"></path><path d="M115.0,115.0 C114.9,115.1 118.7,116.5 119.8,115.4 L133.7,101.6 C136.9,99.2 139.9,98.4 142.2,98.6 C133.8,88.0 127.5,74.4 143.8,58.0 C148.5,53.4 154.0,51.2 159.7,51.0 C160.3,49.4 163.2,43.6 171.4,40.1 C171.4,40.1 176.1,42.5 178.8,56.2 C183.1,58.6 187.2,61.8 190.9,65.4 C194.5,69.0 197.7,73.2 200.1,77.6 C213.8,80.2 216.3,84.9 216.3,84.9 C212.7,93.1 206.9,96.0 205.4,96.6 C205.1,102.4 203.0,107.8 198.3,112.5 C181.9,128.9 168.3,122.5 157.7,114.1 C157.9,116.9 156.7,120.9 152.7,124.9 L141.0,136.5 C139.8,137.7 141.6,141.9 141.8,141.8 Z" fill="currentColor" class="octo-body"></path></svg></a><style>.github-corner:hover .octo-arm{animation:octocat-wave 560ms ease-in-out}@keyframes octocat-wave{0%,100%{transform:rotate(0)}20%,60%{transform:rotate(-25deg)}40%,80%{transform:rotate(10deg)}}@media (max-width:500px){.github-corner:hover .octo-arm{animation:none}.github-corner .octo-arm{animation:octocat-wave 560ms ease-in-out}}</style>
