# Numerical-Algorithms
Introduction to numerical algorithms
2 Possibilites :


1-] Soit vous avez Linux (ou au pire des cas un emulateur Linux sur Windows):

Creer un repertoire TP1
  --> mkdir TP1 : 

Aller dans TP1
  --> cd TP1

Copier les differents progs ( TP1-IFT2425-I.1.c et compilegcc
situes dans mon repertoire http://www.iro.umontreal.ca/~mignotte/IFT2425/ProgTpIFT2425/DevoirIFT2425_1_6/ )
dans votre repertoire avec le browser (firefox, chrome, edge, explorer,...) de votre choix
(avec par exemple l'option "save as" de votre browser)
OU
copiez l'interieur de ces deux fichiers dans un fichier de meme nom dans votre repertoire
TP1 en utilisant un editeur linux quelconque (gedit, emacs, ...).
OU
wget  'http://www.iro.umontreal.ca/~mignotte/IFT2425/ProgTpIFT2425/DevoirIFT2425_1_6/TP1-IFT2425-I.1.c'  .
wget  'http://www.iro.umontreal.ca/~mignotte/IFT2425/ProgTpIFT2425/DevoirIFT2425_1_6/compilegcc'  .
Ensuite faire:

Pour autoriser l'execution de ces progs ou fichiers 
--> chmod 700 *

Pour compiler le programme TP1-IFT2425-I.1.c
--> ./compilegcc TP1-IFT2425-I.1

Pour executer le programme
--> ./TP1-IFT2425-I.1

Pour editer le programme et le modifier
--> emacs TP1-IFT2425-I.1.c

ou (moins gourmand en memoire)
--> gedit TP1-IFT2425-I.1.c   

----
En resume pour ceux qui connaissent un peu Linux:

Pour compiler le programme 
> ./compilegcc TP1-IFT2425-I.1

Pour executer le prog.
> ./TP1-IFT2425-I.1

----------------------------
----------------------------

2-] Si vous voulez utiliser les machines du DIRO qui sont sous Linux.
Installer par exemple X2Go sur votre ordinateur (Linux ou Windows)
https://wiki.x2go.org/doku.php/doc:installation:x2goclient
(cf. Travaillez de chez soi (connexion aux modems de l'UdM) de ma page Web)

Apres s'etre logue sur arcade (avec l'option -X) du style (compteDIRO
est votre login):

ssh -X compteDIRO@arcade.iro.umontreal.ca
ssh -X ens

vous serez connecte sur les machines du DIRO (les blm ou blb)
et faire les operations indiquees plus haut en 1-] cad:

mkdir TP1
cd TP1

wget  'http://www.iro.umontreal.ca/~mignotte/IFT2425/ProgTpIFT2425/DevoirIFT2425_1_6/TP1-IFT2425-I.1.c'  .
wget  'http://www.iro.umontreal.ca/~mignotte/IFT2425/ProgTpIFT2425/DevoirIFT2425_1_6/compilegcc'  .

chmod 700 *
./compilegcc TP1-IFT2425-I.1
./TP1-IFT2425-I.1
gedit TP1-IFT2425-I.1.c



A+
Max
