
---
title: Generant arxiu en PDF
subtitle: Transformació des de Markdown
author: Rafa Mompó Espí
abstract:
lang: ca
header-includes:
  - '\usepackage{lastpage}'
titlepage: true
titlepage-rule-height: 0
titlepage-rule-color: "00FF1D"
titlepage-background: img/portada.png
toc-own-page: true
toc-title: Continguts
toc-depth: 2
header-left: Introducció a Tracker
header-right: Curs 2026-2027
footer-left: IES María Enríquez
footer-right: \thepage/\pageref{LastPage}
---

# 1. Introducció

## 1.1. Presentació i motivació del projecte

TrackerFish és un projecte d'aplicació multiplataforma orientat als aficionats a la pesca esportiva. La idea sorgeix de la necessitat de reunir en una mateixa aplicació informació que habitualment es troba dispersa en diferents pàgines web i aplicacions, com ara les condicions meteorològiques, l'estat del mar, les espècies de peixos i les zones on es poden trobar.

L'aplicació estarà disponible en diferents plataformes: dispositius mòbils, navegadors web i ordinadors d'escriptori. Totes les versions compartiran la mateixa informació mitjançant un sistema centralitzat, de manera que els usuaris podran accedir al seu compte i consultar les seues dades des de qualsevol dispositiu.

TrackerFish permetrà als usuaris consultar diferents zones de pesca i obtindre informació sobre les espècies que hi habiten, la seua alimentació, les èpoques de l'any i les hores més favorables per a pescar. També es podran consultar les condicions ambientals de cada lloc, com ara la temperatura de l'aigua, la velocitat i direcció del vent, les ratxes i les característiques de l'onatge.

A més, TrackerFish incorporarà funcionalitats socials que permetran als pescadors comunicar-se, compartir experiències, participar en un fòrum i organitzar trobades amb altres aficionats.

La motivació principal del projecte és facilitar la preparació de les jornades de pesca, oferint informació centralitzada que ajude els usuaris a conéixer millor les zones i les espècies que poden trobar-hi, així com fomentar una pràctica de la pesca més responsable i sostenible.

## 1.2. Factor diferenciador del projecte

El principal factor diferenciador de TrackerFish és la combinació d'informació meteorològica, marítima i biològica amb les característiques de les diferents zones de pesca.

A diferència d'una aplicació que únicament mostra el temps o permet registrar captures, TrackerFish pretén relacionar diferents factors per a oferir informació més completa sobre cada zona. Per exemple, permetrà consultar quines espècies poden trobar-se en un lloc determinat, de què s'alimenten, en quines èpoques solen estar presents i quines condicions ambientals caracteritzen la zona.

Un altre aspecte diferenciador serà la incorporació d'una comunitat de pescadors, amb possibilitat de crear grups privats, comunicar-se i organitzar eixides conjuntes.

A més, el projecte contempla una dimensió sostenible, ja que permetrà organitzar trobades entre pescadors pròxims per a compartir vehicle i reduir els desplaçaments individuals. També oferirà informació sobre les talles mínimes legals i les restriccions de pesca per a fomentar el respecte per les espècies i el medi natural.

Finalment, es disposarà d'un sistema d'administració i moderació per a controlar la informació i les publicacions que s'incorporen a la comunitat.

Com a possible evolució futura, es planteja aprofitar les captures registrades pels usuaris per a millorar progressivament la informació disponible i desenvolupar sistemes de recomanació més precisos. També es podria incorporar intel·ligència artificial per a classificar les fotografies publicades.

## 1.3. Anàlisi de la situació de partida

Actualment, per a preparar una jornada de pesca és habitual haver de consultar diferents fonts d'informació. Per exemple, una aplicació per a consultar el vent, una altra per a comprovar l'onatge i altres pàgines per a buscar informació sobre les espècies i els seus hàbitats.

Aquesta dispersió dificulta tindre una visió completa de les condicions d'una zona abans de desplaçar-se fins allí.

A més, la informació relacionada amb les espècies, la seua alimentació, les temporades i els llocs on solen trobar-se no sempre està organitzada de manera que resulte fàcil relacionar-la amb les condicions ambientals.

Pel que fa a la comunitat de pescadors, encara que existeixen diferents plataformes de comunicació, no sempre estan orientades específicament a compartir informació sobre zones de pesca i organitzar trobades entre persones que practiquen aquesta activitat.

També es considera important fomentar la pesca responsable, ja que els pescadors han de conéixer les talles mínimes legals, les restriccions i les condicions aplicables a cada espècie i zona.

Per aquests motius, es planteja desenvolupar TrackerFish com una aplicació que centralitze aquestes necessitats en una mateixa plataforma, facilitant l'accés a la informació i la comunicació entre els usuaris.

## 1.4. Objectius que es pretenen aconseguir amb el projecte

L'objectiu principal és desenvolupar una aplicació multiplataforma que facilite la consulta d'informació relacionada amb la pesca i permeta als usuaris compartir experiències amb altres aficionats.

Els objectius específics són:

- Permetre consultar diferents zones de pesca mitjançant un mapa.
- Mostrar informació sobre les espècies que poden trobar-se en cada zona.
- Oferir informació sobre l'alimentació, els hàbitats i les temporades de les diferents espècies.
- Consultar les condicions meteorològiques i marítimes, com ara la temperatura de l'aigua, el vent i l'onatge.
- Permetre als usuaris registrar-se i gestionar el seu perfil.
- Facilitar l'accés a l'aplicació des de dispositius mòbils, navegadors web i ordinadors.
- Sincronitzar la informació dels usuaris entre les diferents plataformes.
- Incorporar un fòrum per a compartir informació i experiències només relacionades amb la pesca.
- Permetre la comunicació privada entre usuaris.
- Facilitar la creació de grups privats mitjançant invitació, sense necessitat de compartir el número de telèfon.
- Permetre compartir la ubicació per a facilitar l'organització de trobades.
- Facilitar el registre de jornades i captures.
- Actualitzar progressivament la informació de la base de dades mitjançant les aportacions dels usuaris.
- Incorporar un sistema d'administració per a gestionar els continguts i la informació de l'aplicació.
- Disposar d'eines de moderació per a controlar les publicacions i les fotografies de la comunitat.
- Mostrar informació sobre les talles mínimes legals i les restriccions de pesca aplicables a cada espècie.
- Fomentar la devolució al mar dels exemplars que no complisquen els requisits legals de captura.
- Fomentar la mobilitat sostenible mitjançant l'organització de desplaçaments compartits.

## 1.5. Relació amb els continguts dels diferents mòduls

El desenvolupament de TrackerFish permetrà aplicar els coneixements adquirits en diferents mòduls del cicle formatiu de Desenvolupament d'Aplicacions Multiplataforma.

**Accés a dades:**

S'utilitzarà per a dissenyar i gestionar la base de dades de l'aplicació, on s'emmagatzemaran els usuaris, les espècies, les zones de pesca, les captures, les jornades i la informació relacionada amb la comunitat. També s'implementaran les operacions necessàries per a consultar, inserir, modificar i eliminar dades.

**Disseny d'interfícies:**

S'aplicaran els coneixements de disseny i desenvolupament d'interfícies per a crear una aplicació intuïtiva, organitzada i fàcil d'utilitzar. També es tindrà en compte l'adaptació de la interfície als diferents dispositius i grandàries de pantalla.

**Programació multimèdia i dispositius mòbils:**

Es relacionarà amb la gestió de fotografies, la visualització de mapes, la localització dels usuaris i les funcionalitats pròpies dels dispositius mòbils. També es tindrà en compte l'accés a la càmera i a altres recursos del dispositiu.

**Programació de Serveis i Processos:**

S'utilitzarà per a implementar la comunicació amb serveis externs mitjançant APIs, especialment per a obtindre informació meteorològica i marítima. També es podrà aplicar a la sincronització de dades entre plataformes i a la gestió de les comunicacions entre usuaris.

**Sistemes de Gestió Empresarial:**

Es relacionarà amb l'organització i la gestió de la informació, així com amb els processos necessaris per a administrar els recursos i el funcionament del projecte.

**Digitalització aplicada:**

S'aplicaran tecnologies digitals per a integrar diferents fonts d'informació i centralitzar les dades relacionades amb la pesca en una mateixa plataforma. També es treballarà amb serveis digitals externs i sistemes de sincronització d'informació.

**Sostenibilitat aplicada:**

Es fomentarà la mobilitat sostenible mitjançant la possibilitat d'organitzar trobades entre pescadors i compartir vehicle per a reduir els desplaçaments individuals. També es promourà el respecte pel medi natural i les espècies mitjançant informació sobre les talles mínimes legals, les restriccions de pesca i les recomanacions per a retornar al mar els exemplars que no complisquen els requisits de captura.

## 2. Presentació de les diferents tecnologies que es poden utilitzar per a la seua realització

### 2.1. Justificación de la elección de las tecnologías.

## 3. Análisis del proyecto

# 3.1. Requisits funcionals i no funcionals

Els requisits del projecte defineixen les funcionalitats que haurà d'oferir TrackerFish i les característiques que haurà de complir per a garantir un funcionament adequat.

## 3.1.1. Requisits funcionals

Els requisits funcionals descriuen les accions i funcionalitats que els usuaris podran realitzar dins de l'aplicació.

**RF01. Registre d'usuaris:** L'aplicació permetrà crear un compte mitjançant un correu electrònic i una contrasenya.

**RF02. Inici de sessió:** Els usuaris podran accedir al seu compte mitjançant les seues credencials.

**RF03. Perfil d'usuari:** Cada usuari disposarà d'un perfil propi amb la seua informació personal.

**RF04. Consulta de zones de pesca:** Els usuaris podran consultar diferents zones de pesca mitjançant un mapa.

**RF05. Consulta d'espècies:** L'aplicació mostrarà les espècies que, segons la informació disponible i els registres coneguts, poden trobar-se en cada zona. Aquesta informació serà orientativa i no garantirà que una espècie estiga present en un moment determinat.

**RF06. Informació de les espècies:** Es podrà consultar informació sobre l'alimentació, els hàbitats, les temporades i les hores en què solen mostrar més activitat les diferents espècies.

**RF07. Informació ambiental:** L'aplicació mostrarà informació meteorològica i marítima de les zones seleccionades.

**RF08. Consulta del vent:** Es podrà consultar la velocitat del vent en km/h, la direcció i les ratxes.

**RF09. Consulta de l'onatge:** Es mostrarà informació sobre les onades, incloent-hi l'altura, la direcció i, quan estiga disponible, el període.

**RF10. Temperatura de l'aigua:** L'aplicació permetrà consultar la temperatura de l'aigua de les zones de pesca quan hi haja dades disponibles.

**RF11. Informació de profunditat:** El mapa podrà mostrar informació sobre la profunditat de les diferents zones de pesca, sempre que es dispose de les dades necessàries.

**RF12. Consulta meteorològica per zones:** Els usuaris podran consultar el temps i les condicions ambientals corresponents a una zona determinada.

**RF13. Fòrum de la comunitat:** L'aplicació disposarà d'un fòrum on els usuaris podran publicar missatges i compartir informació relacionada amb la pesca.

**RF14. Xat privat:** Els usuaris podran comunicar-se de manera privada amb altres membres de la comunitat.

**RF15. Creació de grups:** Els usuaris podran crear grups privats als quals només es podrà accedir mitjançant una invitació, sense necessitat de compartir el número de telèfon.

**RF16. Compartició d'ubicació:** Els usuaris podran compartir la seua ubicació amb altres membres per a facilitar l'organització de trobades.

**RF17. Registre de captures:** Els usuaris podran registrar les captures realitzades, indicant informació com l'espècie, la data, la ubicació i les característiques del peix, incloent-hi el pes i la longitud.

**RF18. Actualització de la base de dades:** La informació de la base de dades podrà ampliar-se mitjançant les dades aportades pels usuaris, especialment les relacionades amb les captures i les zones de pesca. Les dades aportades s'hauran de gestionar i validar abans d'incorporar-les a la informació general de l'aplicació.

**RF19. Organització de trobades:** Els usuaris podran utilitzar les funcionalitats socials per a organitzar eixides de pesca amb altres aficionats i compartir vehicle per a arribar a les zones de pesca.

**RF20. Categorització de l'aplicació:** L'aplicació disposarà de diferents apartats per a organitzar les seues funcionalitats, com ara inici, espècies, mapa, fòrum i perfil.

**RF21. Vinculació amb Google:** Es planteja oferir la possibilitat d'accedir a l'aplicació mitjançant un compte de Google.

**RF22. Informació inicial de l'aplicació:** Quan un usuari accedisca per primera vegada, se li mostrarà un apartat introductori amb informació sobre el funcionament de TrackerFish.

**RF23. Sincronització entre dispositius:** La informació dels usuaris, com ara el perfil, les captures, els grups i les converses, estarà sincronitzada entre les diferents versions de l'aplicació. D'aquesta manera, es podrà accedir a la mateixa informació des d'un dispositiu mòbil, un navegador web o un ordinador.

**RF24. Administració de l'aplicació:** L'aplicació disposarà d'un perfil d'administrador amb permisos especials per a gestionar el funcionament general de TrackerFish. Podrà administrar els usuaris, gestionar les espècies i les zones de pesca, modificar informació general i controlar els continguts de la plataforma.

**RF25. Moderació de continguts:** Els moderadors podran revisar les publicacions, fotografies i altres continguts compartits pels usuaris per a comprovar que estiguen relacionats amb la pesca i que respecten les normes de la comunitat.

**RF26. Denúncia de continguts:** Els usuaris podran denunciar publicacions o fotografies que consideren inadequades o que no estiguen relacionades amb la temàtica de TrackerFish. Aquestes denúncies podran ser revisades pels moderadors o administradors.

**RF27. Gestió de permisos:** L'aplicació diferenciarà els permisos dels usuaris normals, els moderadors i els administradors. Cada perfil disposarà de les opcions corresponents a les seues responsabilitats.

**RF28. Informació sobre talles mínimes legals:** L'aplicació mostrarà informació sobre les talles mínimes de captura de les diferents espècies, tenint en compte la normativa aplicable a cada zona.

**RF29. Pesca responsable:** Quan un usuari registre una captura i n'indique la longitud, l'aplicació podrà comparar-la amb la talla mínima legal corresponent i mostrar un avís quan l'exemplar no complisca els requisits de captura, recomanant-ne la devolució al mar quan corresponga.

**RF30. Informació sobre restriccions de pesca:** Es podrà consultar informació sobre els períodes de veda, les limitacions i altres restriccions aplicables a les espècies i zones de pesca.

**RF31. Publicació de fotografies:** Els usuaris podran pujar fotografies relacionades amb la pesca, tant de captures com de jornades, espècies i material de pesca. Les imatges estaran subjectes a les normes de la comunitat i podran ser revisades pels moderadors.

## 3.1.2. Requisits no funcionals

Els requisits no funcionals defineixen les característiques de qualitat, seguretat i funcionament que haurà de complir l'aplicació.

**RNF01. Usabilitat:** L'aplicació haurà de disposar d'una interfície intuïtiva i fàcil d'utilitzar, de manera que els usuaris puguen trobar ràpidament la informació que necessiten.

**RNF02. Compatibilitat:** L'aplicació haurà d'estar dissenyada per a funcionar en les plataformes previstes per al projecte: dispositius mòbils, navegadors web i ordinadors d'escriptori.

**RNF03. Seguretat:** Les contrasenyes i les dades personals dels usuaris hauran d'estar protegides mitjançant mecanismes de seguretat adequats.

**RNF04. Privacitat:** La informació personal i la ubicació dels usuaris només es podran compartir amb la seua autorització.

**RNF05. Rendiment:** Les diferents seccions de l'aplicació hauran de carregar-se en un temps raonable, evitant esperes innecessàries.

**RNF06. Fiabilitat:** L'aplicació haurà de gestionar correctament els errors i evitar la pèrdua de la informació registrada pels usuaris.

**RNF07. Disponibilitat de dades:** La informació meteorològica i marítima dependrà de la disponibilitat i actualització dels serveis externs utilitzats.

**RNF08. Mantenibilitat:** El codi haurà d'estar organitzat i estructurat per a facilitar futures modificacions, correccions i ampliacions.

**RNF09. Escalabilitat:** La base de dades haurà d'estar preparada per a poder ampliar la quantitat d'usuaris i informació emmagatzemada a mesura que cresca el projecte.

**RNF10. Qualitat de la informació:** Les dades mostrades hauran de presentar-se de manera clara i organitzada, indicant quan siga possible la seua procedència i actualització.

**RNF11. Disseny adaptable:** La interfície haurà d'adaptar-se a diferents grandàries de pantalla i resolucions, oferint una experiència d'ús adequada tant en dispositius mòbils com en ordinadors i navegadors web.

**RNF12. Protecció de la ubicació:** El sistema haurà de garantir que la ubicació dels usuaris no es compartisca sense el seu consentiment. Els usuaris hauran de poder decidir amb qui comparteixen la seua ubicació i tindre la possibilitat de deixar de compartir-la en qualsevol moment.

**RNF13. Control d'accessos:** L'aplicació haurà de gestionar correctament els permisos dels diferents tipus de comptes, impedint que els usuaris normals accedisquen a funcionalitats exclusives dels moderadors o administradors.

**RNF14. Consistència de les dades:** La informació modificada des d'una plataforma haurà de mantindre's sincronitzada correctament amb la resta de dispositius, evitant discrepàncies entre les diferents versions de l'aplicació.

## 3.1.3. Anàlisi de costos i viabilitat del projecte

El desenvolupament de TrackerFish es planteja com un projecte acadèmic, per la qual cosa es procurarà utilitzar tecnologies i eines de desenvolupament gratuïtes o de codi obert per a reduir els costos.

Els principals recursos necessaris seran:

**Recursos de maquinari:**

- Ordinador personal per al desenvolupament i les proves.
- Dispositiu mòbil per a comprovar el funcionament de les funcionalitats mòbils.
- Connexió a Internet per a consultar documentació, utilitzar serveis externs i provar la sincronització entre plataformes.

**Recursos de programari:**

- Entorn de desenvolupament integrat (IDE).
- Sistema gestor de bases de dades.
- Llenguatges i tecnologies necessaris per al desenvolupament de l'aplicació.
- Eines de control de versions.
- Serveis externs i APIs per a obtindre informació meteorològica, marítima i geogràfica.
- Eines necessàries per a desenvolupar i provar les diferents versions de l'aplicació.

**Possibles costos addicionals:**

- Ús de serveis d'allotjament o servidors per a mantindre l'aplicació i la base de dades.
- Possibles subscripcions a serveis meteorològics, cartogràfics o altres APIs si se superen els límits dels plans gratuïts.
- Costos associats a l'emmagatzematge de fotografies i altres fitxers.
- Recursos necessaris per a mantindre la comunicació i sincronització entre les diferents plataformes.
- Possibles costos de publicació de l'aplicació en plataformes de distribució.

### Viabilitat tècnica

El projecte és tècnicament viable, ja que les funcionalitats principals es poden desenvolupar mitjançant tecnologies habituals en el desenvolupament d'aplicacions multiplataforma.

La consulta d'informació meteorològica i marítima es podrà realitzar mitjançant APIs externes, mentre que les dades pròpies de l'aplicació s'emmagatzemaran en una base de dades centralitzada.

Les diferents versions de TrackerFish es comunicaran amb un servidor central, que gestionarà la informació dels usuaris, les captures, les publicacions, els grups i la resta de dades necessàries.

Algunes funcionalitats, com la comunicació privada, els grups, la gestió d'ubicacions i la moderació dels continguts, requeriran un desenvolupament addicional, però es podran implementar de manera progressiva.

Les funcionalitats més avançades, com la classificació automàtica de fotografies mitjançant intel·ligència artificial i les recomanacions intel·ligents basades en l'anàlisi de les captures, es consideraran possibles ampliacions futures i no seran imprescindibles per a la primera versió.

### Viabilitat econòmica

TrackerFish presenta una viabilitat econòmica favorable per al seu desenvolupament acadèmic, ja que es poden utilitzar eines gratuïtes i serveis amb plans d'ús sense cost.

Els principals costos potencials estarien relacionats amb l'allotjament, l'emmagatzematge, la comunicació entre les plataformes i l'ús d'APIs externes.

Aquests costos es podran controlar seleccionant serveis adequats a les necessitats del projecte i aprofitant els plans gratuïts disponibles.

### Viabilitat temporal

El projecte es desenvoluparà de manera progressiva, prioritzant les funcionalitats principals i deixant les característiques més avançades per a possibles ampliacions futures.

En primer lloc, es prioritzarà la creació de la base de dades, el registre i l'autenticació d'usuaris, la consulta d'espècies i zones de pesca i la informació meteorològica i marítima.

Posteriorment, s'incorporaran les funcionalitats socials, la comunicació entre usuaris, els grups, la gestió de captures i les eines d'administració i moderació.

Aquesta planificació permetrà centrar els esforços en aconseguir una primera versió funcional de TrackerFish sense que la complexitat de les funcionalitats addicionals comprometa el desenvolupament.

### 3.2. Temporalització del projecte

- Fites del projecte.
- Diagrama de Gantt.

### 3.3. Casos d'ús

- Diagrama de casos d'ús.
- Descripció dels casos d'ús.

### 3.4. Diagrama de classes inicial

- Diagrama de classes.
- Descripció de les classes.
- Diagrama entitat-relació (si escau).

## 3.5. Esquemes de les interfícies (wireframes)

### 3.6. Altres diagrames i descripcions (si escau)

## 4. Disseny del projecte

### 4.1. Arquitectura del sistema

- Descripció de l'arquitectura.
- Diagrama de l'arquitectura.
- Diagrama de desplegament.

### 4.2. Diagrama de classes definitiu

- Diagrama de classes.
- Descripció de les classes.
- Diagrama entitat-relació (si escau).

### 4.3. Disseny de la interfície d'usuari

- Maquetes (mockups).
- Diagrama de navegació.

### 4.4. Altres diagrames i descripcions (si escau)

## 5. Implementació del projecte

- Estructura del projecte.
- Descripció dels mòduls i components principals.
- Desplegament de l'aplicació.
- Captures de pantalla i exemples de codi (es recomana incloure el codi en els annexos).

## 6. Estudi dels resultats obtinguts

- Avaluació del projecte respecte als objectius inicials.
- Problemes trobats i solucions aplicades.
- Millores i ampliacions futures.

## 7. Conclusions

- Relació amb els continguts dels diferents mòduls.
- Valoració personal del projecte.

## 8. Bibliografia i recursos utilitzats

## 9. Annexos

- Codi font complet del projecte.
- Guia d'instal·lació i ús.
- Documentació addicional.
- Altres materials rellevants.
