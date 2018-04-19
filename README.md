# Liste des Markdowns

## Summary

- [Titres](#titres)
- [Accentuation](#accentuation)
- [Retour à la ligne](#retour-à-la-ligne)
- [Listes](#listes)
- [Liste de tâches](#liste-de-tâches)
- [Liens](#liens)
- [Images](#images)
- [Code and Syntax Highlighting](#code-and-syntax-highlighting)
- [Tableaux](#tableaux)
- [Blockquotes](#blockquotes)
- [Inline code](#inline-code)
- [Inline HTML](#inline-html)
- [Horizontal Rule](#horizontal-rule)
- [Line Breaks](#line-breaks)
- [YouTube Videos](#youtube-videos)
- [A regarder](#a-regarder)

## Titres

```
# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternative, pour H1 and H2 :

Alt-H1
======

Alt-H2
------
```

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternative, pour H1 and H2 :

Alt-H1
======

Alt-H2
------

## Accentuation
```
Accentuation Italique : *asterisks* or _underscores_.

Accentuation Gras : **asterisks** or __underscores__.

Accentuation Combinée : **asterisks and _underscores_**.

Accentuation Barrée avec deux tildes : ~~Rature moi.~~

Centrer du texte :

<p align="center">Texte centré</p>
```

Accentuation Italique : *asterisks* or _underscores_.

Accentuation Gras : **asterisks** or __underscores__.

Accentuation Combinée : **asterisks and _underscores_**.

Accentuation Barrée avec deux tildes : ~~Rature moi.~~



<p align="center">Centrer du texte fonctionne aussi</p>

## Retour à la ligne

```
Écrire du texte (retour à la ligne)
sans le séparer par un espace (retour à la ligne)
le rédige sur une seule ligne.

---

Il faut laisser un espace entre les lignes (2 retours à la ligne)

pour l'écrire sur plusieurs lignes

---

Si on veut écrire du texte sur plusieurs lignes sans laisser d'interligne entre elles (mais à la ligne),  
Il faut laisser en fin de ligne 2 espaces (  ).  
Ca créé des paragraphes sans interlignes.
```

Écrire du texte (retour à la ligne)
sans le séparer par un espace (retour à la ligne)
le rédige sur une seule ligne.

---

Il faut laisser un espace entre les lignes (2 retours à la ligne)

pour l'écrire sur plusieurs lignes

---

Si on veut écrire du texte sur plusieurs lignes sans laisser d'espace entre elles,  
Il faut laisser en fin de ligne 2 espaces (  ).  
Ca créé des paragraphes sans interlignes.

## Listes

__-- /!\ Attention les sous-listes ordonnées ont 3 espaces de tabulation /!\ --__

```
- Liste 1                  + Liste 1                  * Liste 1
  - Liste 1i                 + Liste 1i                 * Liste 1i
    - Liste 1ia                + Liste 1ia                * Liste 1ia
    - Liste 1ib      ou        + Liste 1ib      ou        * Liste 1ib
  - Liste 1ii                + Liste 1ii                * Liste 1ii
- Liste 2                  + Liste 2                  * Liste 2
- Liste 3                  + Liste 3                  * Liste 3

1. Numéro 1
2. Numéro 2
   1. Sous-numéro 2i
   2. Sous-numéro 2i
      1. Sous-sous-numéro 2ia
      2. Sous-sous-numéro 2ib
3. Numéro 3
L'ordre des numéros de la liste importe peu, il sera toujours dans l'ordre.
```

- Liste 1 
  - Liste 1i
    - Liste 1ia
    - Liste 1ib
  - Liste 1ii
- Liste 2
- Liste 3

1. Numéro 1
2. Numéro 2
   1. Sous-numéro 2i
   2. Sous-numéro 2i
      1. Sous-sous-numéro 2ia
      2. Sous-sous-numéro 2ib
3. Numéro 3

## Liste de tâches

```
- [x] @mentions, #references, [liens](), **accentuation** et <del>tags</del> supporté
- [x] syntaxe des listes requise (toute sorte de liste supportée : ordonnée et non-ordonnée)
- [x] tâche terminée
- [ ] tâche incomplète
```

- [x] @mentions, #references, [liens](), **accentuation** et <del>tags</del> supporté
- [x] syntaxe des listes requise (toute sorte de liste supportée : ordonnée et non-ordonnée)
- [x] tâche terminée
- [ ] tâche incomplète

## Liens 
```
[Lien http](https://www.google.com)

[Lien http avec titre](https://www.google.com "Google's Homepage")

[Lien http avec le style "référence"][Texte de référence pour le lien]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[On peut utiliser des nombres comme style de "référence" ainsi qu'un titre][1]

Ou laisser vide et utiliser le [lien texte lui-même].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[Texte de référence pour le lien]: https://www.mozilla.org
[1]: https://github.com/MushuLeDragon "MushuLeDragon"
[lien texte lui-même]: http://www.reddit.com
```

[Lien http](https://www.google.com)

[Lien http avec titre](https://www.google.com "Google's Homepage")

[Lien http avec le style "référence"][Texte de référence pour le lien]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[On peut utiliser des nombres comme style de "référence" ainsi qu'un titre][1]

Ou laisser vide et utiliser le [lien texte lui-même].

URLs and URLs in angle brackets will automatically get turned into links. 
http://www.example.com or <http://www.example.com> and sometimes 
example.com (but not on Github, for example).

Some text to show that the reference links can follow later.

[Texte de référence pour le lien]: https://www.mozilla.org
[1]: https://github.com/MushuLeDragon "MushuLeDragon"
[lien texte lui-même]: http://www.reddit.com


## Images
```
![Image](http://url/a.png "MushuLeDragon")
```

![MushuLeDragon](https://avatars2.githubusercontent.com/u/22367990?s=460&v=4 "MushuLeDragon")


## Code and Syntax Highlighting

## Tableaux

Les tables ne font pas partie de la spécification __Markdowns__ principale mais ils font partie de __GitHub Flavored Markdown (GFM)__ et __Markdown Here__ les prend en charge.

```
Les deux-points (:) peuvent être utilisés pour aligner les colonnes.

| Un  | Tablal        | Des              | Tableaux   |
|-----| :------------ |:----------------:| ----------:|
| la  | colonne 1 est | alignée à gauche | par défaut |
| la  | colonne 2 est | alignée à gauche |      3800€ |
| la  | colonne 3 est | centrée          |      1600€ |
| la  | colonne 4 est | alignée à droite |        24€ |
| X   | zebra stripes | are neat         |         2€ |

Il doit y avoir au moins 3 tirets qui séparent chaque cellule d'en-tête.
Les pipes (|) sont optionnels et pas besoin d'aligner les Mardowns proprement. Les autres Markdowns peuvent être utilisés dans les tableaux.

Markdown | moins | beau
--- | --- | ---
_toujours_ | `affiché` | __proprement__
1 | 2 | 3
```

Les deux-points (:) peuvent être utilisés pour aligner les colonnes.

| Un  | Tablal        | Des              | Tableaux |
|-----| ------------- |:----------------:| --------:|
| la  | col 3 e       | alignée à droite |    3800€ |
| la  | col 2 est     | centrée          |      24€ |
| X   | zebra stripes | are neat         |       2€ |

Il doit y avoir au moins 3 tirets qui séparent chaque cellule d'en-tête.
Les pipes (|) sont optionnels et pas besoin d'aligner les Mardowns proprement. Les autres Markdowns peuvent être utilisés dans les tableaux.

Markdown | moins | beau
--- | --- | ---
_toujours_ | `affiché` | __proprement__
1 | 2 | 3

## Blockquotes

```
> Blockquote 
```

> Blockquote 


## Inline code

```
Code dans une ligne : `Inline Code`
```


Code dans une ligne : `Inline Code`


## Inline HTML
## Horizontal Rule

```
Horizontal Rule         or         Horizontal Rule
---                                ***
```

Horizontal Rule
---

## Line Breaks
## YouTube Videos



---

## A regarder

- [repo markdown à check](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet)
- [ponctuation en anglais (listes)](http://www.plainenglish.co.uk/punctuating-bulleted-lists.html)

[Source : GitHub Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
