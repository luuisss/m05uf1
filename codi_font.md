Un cop s’ha acabat d’escriure el programa, el conjunt de fitxers de text
resultants, on es troben les instruccions, es diu que contenen el **codi font**.
Aquest codi font pot ser des d’un nivell molt alt, molt a prop del llenguatge
humà, fins a un de nivell més baix, més proper al codi de les màquines, com
ara el codi assemblador.

El procés anomenat compilació és la traducció del codi font dels fitxers del
programa en fitxers en format binari que contenen les instruccions en un format que el processador pot entendre. El contingut d’aquests fitxers s’anomena **codi
objecte**. El programa que fa aquest procés s’anomena **compilador**.

El **codi objecte** és el codi font traduït (pel compilador) a codi màquina, però
aquest codi encara no pot ser executat per l’ordinador.

El **codi executable** és la traducció completa a codi màquina, duta a terme per
l’enllaçador. El codi executable és interpretat directament
per l’ordinador

L’ **enllaçador** és l’encarregat d’inserir al codi objecte les funcions de les llibreries
necessàries per al programa generant un arxiu executable

Una **llibreria** és un col·lecció de codi predefinit

**1.2.1 Màquina virtual**
l’objectiu de facilitar el desenvolupament de compiladors que generen codi per a diferents processadors.

consta de dues fases:

La primera parteix del codi font a un llenguatge intermedi obtenint un programa equivalent amb un menor nivell d’abstracció que l’original i que no pot ser directament executat.

La segona fase tradueix el llenguatge intermedi a un llenguatge comprensible per la màquina.

per què dividir la compilació en dues fases? L’objectiu és que el codi de la primera fase, el codi intermedi, sigui
comú per a qualsevol processador, i que el codi generat en la segona fase sigui
l’específic per a cada processador

La **màquina virtual Java** (_JVM_) és l’entorn en què s’executen els programes Java.
És un programa natiu, és a dir, executable en una plataforma específica, que és
capaç d’interpretar i executar instruccions expressades en un codi de bytes o (el
bytecode de Java) que és generat pel compilador del llenguatge Java.

El gran avantatge de la **JVM** és que possibilita la portabilitat de l’aplicació a
diferents plataformes i, així, un programa Java escrit en un sistema operatiu
Windows es pot executar en altres sistemes operatius
