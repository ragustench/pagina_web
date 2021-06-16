# DESCOBREIX EL DELTA
## Recopilació d'informació, ubicacions i fotografies del Delta de l'Ebre
Aquí presento la meva primera pàgina web realitzada amb HTML, CSS i JAVA SCRIPT. S'emmarca  en l'assignatura de <b>Producció i Disseny Cartogràfic. Eines Web</b> del Grau de Geografia, Anàlisi Territorial i Sostenibilitat.
En el següent enllaç es pot visualitzar la meva pàgina web: [Descobreix el Delta](https://sergilabert.github.io/primera_pag_web/)

### TEMÀTICA I MOTIVACIÓ
La temàtica ha consistit a crear una pàgina web relacionada amb la fotografia i el Delta de l'Ebre, on s'han afegit fotografies realitzades personalment en la zona.<br>
La meva principal motivació ha estat la passió per la fotografia i per la meva terra.

### CONTINGUT DE LA PÀGINA WEB
La pàgina està formada per un total de 6 elements/pàgines:
1. ***Pàgina d'inici***: Pàgina de presentació del lloc web amb informació bàsica i d'interès de la zona
2. ***Pàgina de contingut***: Galeria d'Imatges del Delta de l'Ebre
3. ***Pàgina amb un mapa***: Mapa de localització de la zona amb diferents llocs per visitar
4. ***Pàgina de meteorologia***: Pàgina per consultar les dades meteorològiques a partir del codi postal (mitjançant una API).
5. ***Pàgina del Delta de l'Ebre***: Pàgina on apareix un mapa amb espais, llocs i rutes d'interès del Delta de l'Ebre (mapa elaborat amb Qgis).
6. ***Pàgina de contacte***: Formulari de contacte.

### REQUISITS MÍNIMS
Referent al contingut tècnic de les pàgines, s'han tingut en compte les següents indicacions:
- <b>Capçalera</b> comuna a totes les pàgines
- <b>Logo</b> del lloc web amb un enllaç a la pàgina d'inici
- <b>Peu de pàgina</b> comú a totes les pàgines
- Enllaços a les diferents xarxes socials</b> amb imatges dels logos. 
- <b>Informació del copyright</b>
- Enllaç per tornar a <b>l'inici de la pàgina</b> en la qual ens trobem.
- <b>Disseny responsive</b>

### OBTENCIÓ DE LES DADES
Per realitzar la pàgina web he extret la informació de diferents llocs webs:
* <b>Contingut de la pàgina</b>:
  * [Turisme Delta de l'Ebre](https://deltadelebreturisme.com/cat/)
  * [Parc Natural del Delta de l'Ebre](https://ca.wikipedia.org/wiki/Parc_Natural_del_Delta_de_l%27Ebre)
  * [Los apuntes del viajero](https://www.losapuntesdelviajero.com/delta-del-ebro-cosas-que-hacer/)
  * [Blog: Litoral Costa Dorada](https://www.litoral.es/guia-de-vacaciones/delta-del-ebro-que-ver-y-hacer/)
* <b>Mapa de localització</b>:
  *  [Leaflet](https://leafletjs.com)
* <b>Meteorologia</b>:
  * [OpenWeatherMap](https://openweathermap.org)
  * [Leaflet](https://leafletjs.com)
* <b>Mapa del Delta de l'Ebre</b>:
  * [Hipermapa](https://sig.gencat.cat/visors/hipermapa.html)
  * [Mermaid Live Editor](https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgICBBW0NocmlzdG1hc10gLS0-fEdldCBtb25leXwgQihHbyBzaG9wcGluZylcbiAgICBCIC0tPiBDe0xldCBtZSB0aGlua31cbiAgICBDIC0tPnxPbmV8IERbTGFwdG9wXVxuICAgIEMgLS0-fFR3b3wgRVtpUGhvbmVdXG4gICAgQyAtLT58VGhyZWV8IEZbZmE6ZmEtY2FyIENhcl0iLCJtZXJtYWlkIjp7fSwidXBkYXRlRWRpdG9yIjpmYWxzZX0)<br>

### PRIMERES PRÀCTIQUES
En les primeres pràctiques de l'assignatura vam executar dues tasques:
1. <b>Disseny de la pàgina web</b>
En aquesta primera pràctica vam realitzar la pàgina web amb llenguatge d'HTML, CSS i Java Script.<br>
L'objectiu d'aquesta va ser intentar tractar tot el treballat en el primer blog de l'assignatura, creant una pàgina web des de zero.<br>
Es van realitzar diferents arxius HTML amb el contingut principal de la pàgina i els seus respectius CSS per donar-li un estil concret.<br>
Es van utilitzar diferents etiquetes d'HTML (enllaços, salts de línia, paràgrafs, imatges...) i una gran varietat d'etiquetes de CSS (mida de lletra, tipus, color, justificació, els fons de les seccions/divisions, el padding, el margin, amplada, alçada...) per donar-li el millor estil possible.
2. <b>Disseny d'una web dinàmica</b>
En la segona pràctica es va seguir amb la dinàmica de la primera, però en aquesta es va introduir dinamisme a la web.<br>
L'objectiu d'aquesta ha estat cercar un servei web que ha proporcionat un conjunt de dades relacionades amb la primera pràctica, i que ha permès actualitzar el contingut de la pàgina web de forma dinàmica.<br>
Es va identificar amb l'ajuda del professor un servei web, i es va estudiar la seva API per veure com demanar la informació. Després es va crear un codi de Java Script capaç de recollir les dades i tractar-les, afegint components que permeten filtrar la informació que es pot demanar al servei web i finalment es va integrar en un mapa.<br>
Com ja s'ha esmentat l’API seleccionada ha estat extreta del <b>OpenWeatherMap</b>.<br>
Referent al desenvolupament de la pràctica, en primer lloc, vaig crear un usuari en la pàgina web d’OpenWeatherMap, ja que era necessari generar una API key per poder afegir-la en l’URL i d’aquesta forma afegir-la al document d’HTML.<br>
Una vegada creat l’usuari i generada l’API key, vaig observar el procediment per obtenir l’API i poder començar a treballar-ho per a la meva pàgina web. En el meu cas vaig utilitzar l’API que oferia les <b>dades meteorològiques actuals</b>, que ofereix dades per a qualsevol ubicació, recopilant informació de diferents fonts, com a models meteorològics globals i locals, satèl·lits, radars... I estava disponible per a subscripcions gratuïtes.
En el document API, t’indicava com buscar les dades actuals per ubicació, mitjançant el codi postal. Seguint les indicacions corresponents, vaig crear l’API que necessitava. Havia de tenir present la meva API key, el codi del país i un codi postal. També vaig afegir les unitats que m’interessaven i el llenguatge en què volia que apareixies en la web.<br>
A partir d’aquí, vaig anar seguint els procediments que havíem treballat a classe.
Primer, vaig realitzar la crida de JavaScript dins del meu HTML, a partir del FETCH. Una vegada ja tenim el JSON carregat a dins del JavaScript es va accedir al seu contingut.<br>
Després vaig afegir el botó per a cercar la informació a partir dels codis postals i també un camp per a entrar la informació del codi postal.

### PROJECTE FINAL
Per finalitzar l'assignatura hem realitzat un últim exercici per completar la nostra pàgina, on es poden observar tots els recursos revisats en l'assignatura i s'ha fet ús de cartografia interactiva. En aquesta s'ha introduït:
* <b>Una taula formatada</b>
* <b>Un mapa web</b> en el qual es mostren:
	* <b>Etiquetes emergents ("popups")</b> amb HTML/CSS. Modificats posteriorment des del codi generat del qgis2web.
	* <b>Icones SVG</b>
	* Capes de <b>polígons, punts i línies</b>
* <b>Diagrama de Mermaid.js</b><br>

#### ELABORACIÓ DE LA CARTOGRAFIA
1. <b>Treball de camp</b> pel municipi de Deltebre, realitzant fotos georeferenciades de diferents bars i restaurants del municipi. Posteriorment s'han exportat al Qgis mitjançant l'eina _d'Importar fotos georeferenciades_.
2. Instauració del QuickMapServices: <b>OSM Standard</b>
3. Atribuir als diferents punts de les imatges exportades una <b>icona.SVG</b> per visualitzar-les en el mapa.
4. Afegir <b>informació de cada bar/restaurant</b> en la capa d'atributs (nom de l'establiment, horari, direcció i número de contacte).<br>
Per a les imatges s'ha creat una columna nova en la taula d'atributs amb la <b>ruta corresponent</b>.
6. <b>Digitalització de diferents rutes</b> (Ajuntament de Deltebre - Llocs d'interès).
7. Descàrrega de la <b>capa d'Espais d'Interès de Protecció Especial de Catalunya</b> i realització de les tasques necessàries per a treballar amb els espais del Delta de l'Ebre.
8. Instal·lació del complement <b>qgis2web</b> per poder exportar el mapa com una pàgina web. 
9. Exportació del mapa amb la indicació corresponent perquè les dades seleccionades es representin com un <b>PopUp</b>.<br>
***Tenir en compte en la realització d'aquests mapes i de les tasques realitzades, les rutes dels diferents arxius i de les imatges.***<br>
Resultat del mapa qgis2web [Mapa de llocs, zones i rutes d'interès del Delta de l'Ebre](https://sergilabert.github.io/primera_pag_web/ruta.html#)

#### TAULA FORMATADA
En la taula formatada es van introduir diferents tipus d'allotjaments de la zona amb els corresponents enllaços de les seves pàgines webs. 

#### MERMAID.JS
En el diagrama Mermaid s'han classificat els diferents Espais de Protecció Especial segons la seva tipologia (Parc Natural i Reserves Naturals)

### DISSENY WEB RESPONSIU
Una de les condicions de l'assignatura, era incorporar a la pàgina web un disseny responsive, que permeti adaptar el format dels continguts del lloc a les característiques de diferents pantalles. <br>
En el meu cas he utilitzat la tècnica de <b>@media queries</b>

### MILLORES REALITZADES
* Reducció de la mida de les imatges (inferior a 1 MB).
* Introducció de les media-queries per adaptar la pàgina a diferents mides de pantalla.
* Comentaris en els diferents documents d'HTML i CSS de les etiquetes realitzades. 

### QUÈ ÉS POT MILLORAR?
* Introduir més dinamisme en la pàgina, mitjançant Java Script.
* Millorar la galeria de les imatges.
* Complementar el mapa final amb més Treball de Camp
* Disseny de la pàgina web 

### REFLEXIÓ I DIFICULTATS
Assignatura interessant on ens hem trobat davant d'un repte acadèmic i personal, en el qual l'objectiu ha estat crear una pàgina web des de zero, utilitzant diferents llenguatges i on utilitzant diferents llenguatges nous.<br>
En el transcurs de l'assignatura ens hem trobat amb moltes dificultats, tot i això, crec que amb dedicació i esforç les hem pogut solucionar. 
