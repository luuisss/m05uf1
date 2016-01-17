La programació es basa en el denominat teorema de l’estructura (_seqüència_, _selecció_ i _iteració_)

D’aquesta forma les característiques de la programació estructurada són la claredat,
el teorema de l’estructura i el disseny descendent.

**Claredat**
Hi haurà d’haver prou informació al codi per tal que el programa pugui ser
entès i verificat.

**Teorema de l’estructura**
Demostra que tot programa es pot escriure utilitzant únicament les tres estructures
bàsiques de control: (_seqüència_, _selecció_ i _iteració_)

**Disseny descendent**
El disseny descendent és una tècnica que es basa en el concepte de “divideix i
venceràs” per tal de resoldre un problema en l’àmbit de la programació. Es tracta
de la resolució del problema al llarg de diferents nivells d’abstracció partint d’un
nivell més abstracte i finalitzant en un nivell de detall.

**Programació modular**
divisió d’un programa en parts més manejables i independents 

En la majoria de llenguatges, els mòduls es tradueixen a:

• Procediments: són subprogrames que duen a terme una tasca determinada
i retornen 0 o més d’un valor. S’utilitzen per estructurar un programa i
millorar la seva claredat.

• Funcions: són subprogrames que duen a terme una determinada tasca i
retornen un únic resultat o valor. S’utilitzen per crear operacions noves que
no ofereix el llenguatge.

**Tipus abstractes de dades (TAD)**

és el conjunt de valors que la variable pot assumir i les seves possibles operacions.

**1.5.2 Característiques de la programació orientada a objectes**
**L’orientació a objectes** és un paradigma de construccióde programes basat en una abstracció del món real.

Un **objecte** és una combinació de dades (anomenades atributs) i mètodes (funcions i procediments) que ens permeten interactuar amb ell

La programació orientada a objectes es basa en la integració de 5 conceptes:

**Abstracció:** per mitjà de l’abstracció es defineixen les
característiques essencials d’un objecte del món real, els atributs i comportaments
que el defineixen com a tal, per després modelar-lo en un objecte de programari.

**Encapsulació:**  Permet als objectes triar quina informació és publicada i quina informació és
amagada a la resta dels objectes
Les característiques que es poden atorgar són:
**• Públic:** , **• Protegit:**, **• Privat:**

**Modularitat:** Permet poder modificar les característiques de cada una de les classes que defineixen
un objecte, de forma independent de la resta de classes en l’aplicació.

**Jerarquia:** Permet l’ordenació de les abstraccions. Les dues jerarquies més importants d’un
sistema complex són l’herència i l’agregació.

**L’herència:** quan s’utilitza per definir una nova classe només s’ha d’afegir allò
que sigui diferent, és a dir, reaprofita els mètodes i variables

**L’agregació** és un objecte que està format de la combinació d’altres objectes o
components.

**polimorfisme:** És una característica que permet donar diferents formes a un mètode, ja sigui en
la definició com en la implementació.

La sobrecàrrega (overload) de mètodes consisteix a implementar diverses vegades
un mateix mètode però amb paràmetres diferents, de manera que, en invocar-lo, el
compilador decideix quin dels mètodes s’ha d’executar, en funció dels paràmetres
de la crida.

La sobreescriptura (override) de mètodes consisteix a reimplementar un mètode
heretat d’una superclasse exactament amb la mateixa definició (incloent nom de
mètode, paràmetres i valor de retorn).

