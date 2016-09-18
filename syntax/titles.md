# Titles

As we started writing a markdown document, we need to add a title and some sub-headers.

Markdown supports two styles of headers, Setext and atx.

Setext-style headers are “underlined” using equal signs (for first-level headers) and dashes (for second-level headers). For example:

```
This is an H1
=============

This is an H2
-------------
```

Any number of underlining =’s or -’s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

```
# This is an H1

## This is an H2

###### This is an H6
```


Optionally, you may “close” atx-style headers. This is purely cosmetic — you can use this if you think it looks better. The closing hashes don’t even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

```
# This is an H1 #

## This is an H2 ##

### This is an H3 ######
```


---

Here's a quiz about markdown titles.

Select the valid headers:
- [x] `# hello`
- [ ] `#hello`

> Headers need space between the hash characters and the text.

Select the valid headers:
- [ ]  
```
test
########
```
- [x]   
```
test
=======
```

> Only '=' and '-' are accepted for underlining an header.

---


# Traduction de l'anglais vers le français pour la quête.

# Titres

Lorsque que l'on commence à écrire un texte en markdown, il est nécessaire d'ajouter un titre et des sous-titres.

Le markdown a deux types d'en-têtes : Setext et atx.

Avec Setext les titres sont soulignés en utilisant le signe égal (pour les titres de premier niveau et le tirer (pour les titres de second niveau). Par exemple :

```
C'est un H1
===========

C'est un H2
-----------
```

Tout nombre souligné par ='s ou -'s fonctionnera.

Avec Atx les titres utilisent 1 à 6 hashtag au début de la ligne, le nombre de hastag correspondant à des niveaux de 1 à 6. Par exemple :

```
# C'est un H1

## C'est un H2

### C'est un H3

#### C'est un H4

##### C'est un H5

###### C'est un H6
```

De manière optionnelle, on peut fermer un titre atx. C'est purement esthétique, on peut le faire si l'on trouve que cela rend mieux. On fermera avec un hashtag, qui n'a pas besoin d'être proptionnel aux hastags qui ont servi à ouvrir le titre. (Le nombre de hastag "ouvrant" détermine l'importance du titre.

```
# C'est un H1 #
##### C'est un H5 #
```

