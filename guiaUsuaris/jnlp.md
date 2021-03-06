<h2>Com executar el <i>JNLP</i>?</h2>

Per tal de poder realitzar l'operació de signatura en si, un cop accedit al servei del **Signador** es descarregarà un fitxer amb extensió *.jnlp*. 
Per tal de dur a terme la signatura serà necessari executar aquest fitxer.

A diferència de l'applet de signatura el *JNLP* s'executa fora del context del navegador, per tant en aquest sentit hauria de funcionar independentment de amb quin navegador s'hagi descarregat el fitxer *.jnlp*.

<h3>Sistemes operatius</h3>

Donem suport a l'execució del *JNLP* per a ser executat en els següents sistemes operatius:

 - *Ubuntu* - Versions [12.04 i superiors](https://wiki.ubuntu.com/Releases) 
 - *Windows* - Versions client [Vista i superiors](https://en.wikipedia.org/wiki/List_of_Microsoft_Windows_versions#Client_versions)
 - *Windows* - Versions servidor [Server2003 R2 i superiors](https://en.wikipedia.org/wiki/List_of_Microsoft_Windows_versions#Server_versions)
 - *MAC OS X* - Versions [OS.X 10.9 i superiors](https://en.wikipedia.org/wiki/MacOS#Release_history)
 
**Nota**: Igual que en el cas dels navegadors pot funcionar en altres versions de sistemes operatius (e.g. altres distribucions de Linux com pot ser [Mint](https://www.linuxmint.com/)), però també igual que en el cas dels navegadors, aquestes altres versions no rebran suport per part nostra en cas de problemes d'execució.
 
<h3>Requeriments</h3>

És necessari tenir instal·lada una versió de la Java JRE en l'ordinador on volem executar el *.jnlp*. 
Donem suport fins a _tres versions anteriors_ a l'actual de JRE.

Pots descarregar-te [l'última versió de la JRE d'Oracle aqui](https://www.java.com/es/download/).

**Nota**: Si disposes d'un entorn/versió diferent dels especificats anteriorment es possible que igualment tot et funcioni correctament, però en cas de necessitar de suport només serà disponible per a les versions/entorns específicats.

<h3>Com utilitzar-ho</h3>

Si teniu problemes executant el _JNLP_ del signador podeu revisar la [FAQ oficial d'Oracle de com executar _JNLP_ aqui.](https://www.java.com/es/download/faq/java_webstart.xml)

Per comprovar que teniu tot correctament instal·lat podeu fer una prova [executant un _JNLP_ oficial d'Oracle d'exemple](https://docs.oracle.com/javase/tutorialJWS/samples/deployment/dynamictree_webstartJWSProject/dynamictree_webstart.jnlp), que en cas d'executar-se correctament mostra el següent pop-up:

![JNLPSample](https://github.com/ConsorciAOC/signador/blob/master/guiaUsuaris/imgs/JNLPSample.png)

Podeu veure aquest exemple i un altre [aqui](https://docs.oracle.com/javase/tutorial/deployment/webstart/examplesIndex.html).


