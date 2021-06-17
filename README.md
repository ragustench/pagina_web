# RUTA MODERNISTA DE REUS
## Recopilació d'informació, ubicacions i fotografies dels habitatges de la Ruta Modernista
Aquí presento la meva primera pàgina web realitzada amb HTML, CSS i JAVA SCRIPT. S'emmarca dins l'assignatura de <b>Producció i Disseny Cartogràfic. Eines Web</b> del Grau de Geografia, Anàlisi Territorial i Sostenibilitat. Realitzada l’any 2021
Enllaç de la pàgina web: [Ruta Modernista]( https://ragustench.github.io/pagina_web/)

### TEMÀTICA
La Ruta del Modernisme és un tema interessant per una persona nascuda a Reus, ja que el principal referent del modernisme, com Antoni Gaudí. Al passejar per Reus sempre havia passat per alguna de les cases modernistes, però mai havia fet la ruta sencera i poder fotografiar les cases.
No hi ha cap pàgina relacionada amb la ruta, només el nom de les cases, l’objectiu d’aquesta pàgina és: conèixer la ciutat de Reus i la ruta modernista que hi ha, com les imatges dels habitatges modernistes i diversos mapes on s’ubiquen totes els edificis. 

### ESTRUCTURA DE LA PÀGINA WEB
La pàgina està formada per un total de 6 elements/pàgines:
1. ***Pàgina d'inici***: Pàgina de presentació de la temàtica de la web amb informació bàsica i d’interès.
2. ***Pàgina de fotografies***: Galeria d’imatges dels habitatges modernistes .
3. ***Pàgina amb un mapa***: Mapa la localització de tots els habitatges i altres construccions modernistes de Reus.
4. ***Pàgina de l’API***: Pàgina per consultar altres municipis amb edificis modernistes de Catalunya (amb el codi postal).
5. ***Pàgina de la Ruta Modernista (QGIS)***: Pàgina on apareix la ruta i les principals zones verdes de Reus
6. ***Pàgina de contacte***: Formulari de contacte.

### REQUISITS MÍNIMS
Referent al contingut tècnic de les pàgines, s'han tingut en compte les següents indicacions:
- <b>Capçalera</b> comuna a totes les pàgines
- <b>Peu de pàgina</b> comú a totes les pàgines
- Enllaços a les diferents xarxes socials</b> amb imatges dels logos. 
- <b>Informació del copyright</b>
- Enllaç per tornar a <b>l'inici de la pàgina</b> en la qual ens trobem.
- <b>Disseny responsive</b>

### OBTENCIÓ DE LES DADES
Per realitzar la pàgina web he extret la informació de diferents llocs webs:
* <b>Contingut de la pàgina</b>:
  * [Reus Turisme](https://www.reusturisme.cat)
  * [Patrimoni cultural]( http://patrimoni.gencat.cat/cat)
  * [Plànol Turístic de Reus]
 * <b>Mapes </b>:
  *  [Leaflet](https://leafletjs.com)
* <b>Ruta Modernista </b>:
  * [OSM Tracker (App)]
  * [Mermaid Live Editor]

### PROJECTE FINAL
1. <b>Disseny de la pàgina web</b>
Amb llenguatge d'HTML, CSS i Java Script per la realització de tota la pàgina web.<br>
L'objectiu d'aquesta va ser intentar tractar tot el treballat en el primer blog de l'assignatura, creant una pàgina web des de zero.<br>
Es van realitzar diferents arxius HTML amb el contingut principal de la pàgina i els seus respectius CSS per donar-li un estil concret.<br>
Es van utilitzar diferents etiquetes d'HTML (enllaços, salts de línia, paràgrafs, imatges...) i una gran varietat d'etiquetes de CSS (mida de lletra, tipus, color, justificació, els fons de les seccions/divisions, el padding, el marge, amplada, alçada...) per donar-li el millor estil possible.
2. <b>Disseny d'una web dinàmica</b>
En la segona pràctica es va seguir amb la dinàmica de la primera, però en aquesta es va introduir dinamisme a la web.<br>
L'objectiu d'aquesta ha estat cercar un servei web que ha proporcionat un conjunt de dades relacionades amb la primera pràctica, i que ha permès actualitzar el contingut de la pàgina web de forma dinàmica.<br>
Es va identificar amb l'ajuda del professor un servei web, i es va estudiar la seva API per veure com demanar la informació. Després es va crear un codi de Java Script capaç de recollir les dades i tractar-les, afegint components que permeten filtrar la informació que es pot demanar al servei web i finalment es va integrar en un mapa.<br>
Referent al desenvolupament de la pràctica, en primer lloc, vaig crear un usuari en la pàgina web d’OpenWeatherMap, ja que era necessari generar una API key per poder afegir-la en l’URL i d’aquesta forma afegir-la al document d’HTML.<br>
Per finalitzar l'assignatura hem realitzat un últim exercici per completar la nostra pàgina, on es poden observar tots els recursos revisats en l'assignatura i s'ha fet ús de cartografia interactiva. En aquesta s'ha introduït:
* <b>Un mapa web</b> en el qual es mostren:
	* <b>Etiquetes emergents ("popups")</b> amb HTML/CSS. Modificats posteriorment des del codi generat del qgis2web.
	* <b>Icones SVG</b>
	* Capes de <b>polígons, punts i línies</b>
* <b>Diagrama de Mermaid.js</b><br>

#### ELABORACIÓ DE LA CARTOGRAFIA
1. <b>Treball de camp</b> pel municipi de Reus, realitzant fotos georeferenciades de diferents habitatges. Posteriorment s'han exportat al Qgis mitjançant l'eina _d'Importar fotos georeferenciades_.
2. Instauració del QuickMapServices: <b>OSM Standard</b>
3. Atribuir als diferents punts de les imatges exportades una <b>icona.SVG</b> per visualitzar-les en el mapa.
4. Afegir <b>informació de cada casa</b> en la capa d'atributs (nom de la casa, arquitecte, direcció i any de construcció).<br>
Per a les imatges s'ha creat una columna nova en la taula d'atributs amb la <b>ruta corresponent</b>.
5. <b>Creació dels polígons de les diferents zones verdes de Reus diferenciant entre parcs i places</b>
6. <b>Digitalització de diferents rutes</b> 
7. Instal·lació del complement <b>qgis2web</b> per poder exportar el mapa com una pàgina web. 
8. Exportació del mapa amb la indicació corresponent perquè les dades seleccionades es representin com un <b>PopUp</b>.<br>
***Tenir en compte en la realització d'aquests mapes i de les tasques realitzades, les rutes dels diferents arxius i de les imatges.***<br>
#### MERMAID.JS
En el diagrama Mermaid s'han classificat la informació del mapa anterior amb les cases modernistes per un costat i les zones verdes per l’altre.

### DISSENY WEB RESPONSIU
Una de les condicions de l'assignatura, era incorporar a la pàgina web un disseny responsive, que permeti adaptar el format dels continguts del lloc a les característiques de diferents pantalles. <br>
En el meu cas he utilitzat la tècnica de <b>@media queries</b>

### QUÈ ÉS POT MILLORAR?
* Introduir més dinamisme en la pàgina, mitjançant Java Script.
* Millorar la galeria de les imatges.
* Complementar el mapa final amb més Treball de Camp
* Disseny de la pàgina web 

### REFLEXIÓ I DIFICULTATS
Assignatura interessant on ens hem trobat davant d'un repte acadèmic i personal, en el qual l'objectiu ha estat crear una pàgina web des de zero, utilitzant diferents llenguatges i on utilitzant diferents llenguatges nous.<br>
En el transcurs de l'assignatura ens hem trobat amb moltes dificultats, tot i això, crec que amb dedicació i esforç les hem pogut solucionar.

