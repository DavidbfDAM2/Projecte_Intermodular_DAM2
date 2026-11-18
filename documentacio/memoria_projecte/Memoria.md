---
cssclasses:
  - dam-memoria
memoria_titol: Borsa de pràctiques de l’institut
memoria_autors: Isaac Martínez Boada i David Baños Fàbregas
memoria_centre: Institut Rafael Campalans
memoria_css: ProjecteFinal/Memoria/memoria-pdf.css
---

<div class="cover">
<p class="cover-centre">Institut Rafael Campalans</p>
<h1 class="cover-title">Borsa de pràctiques de l’institut</h1>
<p class="cover-subtitle">Projecte final del cicle de DAM</p>
<p>Aplicació per connectar alumnat i empreses col·laboradores</p>
<p>Desenvolupament d’Aplicacions Multiplataforma<br>Nivell: 2n de DAM</p>
<div class="cover-details">
<p>Autors: Isaac Martínez Boada i David Baños Fàbregas<br>Tutor: Julià Fernàndez Martínez<br>Anglès · Maig de 2027</p>
</div>
</div>

## Índex

- [[#Orientacions per emplenar la plantilla|Orientacions per emplenar la plantilla]]
  - [[#Criteris de redacció i presentació|Criteris de redacció i presentació]]
  - [[#Dades i decisions inicials|Dades i decisions inicials]]
- [[#1 Introducció i objectius|1 Introducció i objectius]]
  - [[#1.1 Descripció i context|1.1 Descripció i context]]
  - [[#1.2 Motivació i finalitats|1.2 Motivació i finalitats]]
  - [[#1.3 Alternatives i elecció tecnològica|1.3 Alternatives i elecció tecnològica]]
  - [[#1.4 Organització de la memòria|1.4 Organització de la memòria]]
- [[#2 Pla d’empresa i viabilitat|2 Pla d’empresa i viabilitat]]
  - [[#2.1 Client i estudi de mercat|2.1 Client i estudi de mercat]]
  - [[#2.2 Proposta de valor i model de sostenibilitat|2.2 Proposta de valor i model de sostenibilitat]]
  - [[#2.3 Anàlisi DAFO|2.3 Anàlisi DAFO]]
    - [[#2.3.1 Fortaleses|2.3.1 Fortaleses]]
    - [[#2.3.2 Debilitats|2.3.2 Debilitats]]
    - [[#2.3.3 Oportunitats|2.3.3 Oportunitats]]
    - [[#2.3.4 Amenaces|2.3.4 Amenaces]]
    - [[#2.3.5 Línies d’actuació derivades del DAFO|2.3.5 Línies d’actuació derivades del DAFO]]
  - [[#2.4 Pressupost i finançament|2.4 Pressupost i finançament]]
  - [[#2.5 Forma jurídica proposada|2.5 Forma jurídica proposada]]
- [[#3 Planificació i metodologia|3 Planificació i metodologia]]
  - [[#3.1 Fases i temporització|3.1 Fases i temporització]]
  - [[#3.2 Scrum i seguiment|3.2 Scrum i seguiment]]
  - [[#3.3 Control de versions i canvis|3.3 Control de versions i canvis]]
  - [[#3.4 Riscos del projecte|3.4 Riscos del projecte]]
- [[#4 Abast i requeriments|4 Abast i requeriments]]
  - [[#4.1 Àmbit i límits|4.1 Àmbit i límits]]
  - [[#4.2 Actors i permisos|4.2 Actors i permisos]]
  - [[#4.3 Requeriments funcionals|4.3 Requeriments funcionals]]
  - [[#4.4 Requeriments no funcionals|4.4 Requeriments no funcionals]]
- [[#5 Anàlisi funcional i casos d’ús|5 Anàlisi funcional i casos d’ús]]
  - [[#5.1 Diagrama de casos d’ús|5.1 Diagrama de casos d’ús]]
  - [[#5.2 Fitxes de casos d’ús|5.2 Fitxes de casos d’ús]]
  - [[#5.3 Diagrames d’activitat|5.3 Diagrames d’activitat]]
  - [[#5.4 Estats i regles del procés|5.4 Estats i regles del procés]]
- [[#6 Arquitectura i disseny tècnic|6 Arquitectura i disseny tècnic]]
  - [[#6.1 Arquitectura del sistema|6.1 Arquitectura del sistema]]
  - [[#6.2 Disseny modular i dependències|6.2 Disseny modular i dependències]]
  - [[#6.3 Diagrama de classes|6.3 Diagrama de classes]]
  - [[#6.4 Accés a fonts de dades|6.4 Accés a fonts de dades]]
- [[#7 Estructura i persistència de dades|7 Estructura i persistència de dades]]
  - [[#7.1 Model entitat relació|7.1 Model entitat relació]]
  - [[#7.2 Model relacional|7.2 Model relacional]]
  - [[#7.3 Diccionari de dades|7.3 Diccionari de dades]]
  - [[#7.4 Integritat i conservació|7.4 Integritat i conservació]]
  - [[#7.5 Inicialització i migracions|7.5 Inicialització i migracions]]
- [[#8 Interfícies i interacció amb l’usuari|8 Interfícies i interacció amb l’usuari]]
  - [[#8.1 Navegació i recorreguts|8.1 Navegació i recorreguts]]
  - [[#8.2 Disseny de pantalles|8.2 Disseny de pantalles]]
  - [[#8.3 Formularis i estats de la interfície|8.3 Formularis i estats de la interfície]]
  - [[#8.4 Usabilitat i accessibilitat|8.4 Usabilitat i accessibilitat]]
- [[#9 Construcció seguretat i desplegament|9 Construcció seguretat i desplegament]]
  - [[#9.1 Implementació|9.1 Implementació]]
  - [[#9.2 Seguretat i accés a les dades|9.2 Seguretat i accés a les dades]]
  - [[#9.3 Còpies de seguretat i restauració|9.3 Còpies de seguretat i restauració]]
  - [[#9.4 Desplegament i posada en marxa|9.4 Desplegament i posada en marxa]]
- [[#10 Proves resultats i incidències|10 Proves resultats i incidències]]
  - [[#10.1 Estratègia de proves|10.1 Estratègia de proves]]
  - [[#10.2 Traçabilitat i resultats|10.2 Traçabilitat i resultats]]
  - [[#10.3 Errors i problemes durant el desenvolupament|10.3 Errors i problemes durant el desenvolupament]]
  - [[#10.4 Avaluació amb el client|10.4 Avaluació amb el client]]
- [[#11 Seguiment diari|11 Seguiment diari]]
  - [[#11.1 Registre individual|11.1 Registre individual]]
  - [[#11.2 Resum del seguiment|11.2 Resum del seguiment]]
- [[#12 Conclusions i comentari personal|12 Conclusions i comentari personal]]
  - [[#12.1 Assoliment dels objectius|12.1 Assoliment dels objectius]]
  - [[#12.2 Limitacions i línies futures|12.2 Limitacions i línies futures]]
  - [[#12.3 Comentari personal|12.3 Comentari personal]]
- [[#13 Referències bibliogràfiques|13 Referències bibliogràfiques]]
  - [[#13.1 Models per completar|13.1 Models per completar]]
  - [[#13.2 Llista definitiva|13.2 Llista definitiva]]
- [[#14 Annexos|14 Annexos]]
  - [[#14.1 Proposta i acords|14.1 Proposta i acords]]
  - [[#14.2 Manual d’usuari|14.2 Manual d’usuari]]
  - [[#14.3 Manual tècnic i evidències|14.3 Manual tècnic i evidències]]
  - [[#14.4 Materials de la defensa|14.4 Materials de la defensa]]
  - [[#14.5 Documents de treball disponibles|14.5 Documents de treball disponibles]]

## Orientacions per emplenar la plantilla

Aquesta plantilla organitza la memòria del projecte d’una borsa de pràctiques per a l’alumnat de l’institut. Cal completar-la durant el desenvolupament amb les decisions, els resultats i les evidències del treball.

Els textos entre claudàtors són camps o instruccions que s’han de substituir. Els exemples identificats com a propostes s’han de validar abans d’incorporar-los com a requisits. Elimineu aquest apartat d’orientacions abans del lliurament.

### Criteris de redacció i presentació

L’índex utilitza enllaços interns d’Obsidian al text exacte de cada encapçalament. Si es canvia un títol, cal actualitzar-ne també l’entrada. El fitxer [memoria-pdf.css](memoria-pdf.css) defineix DIN A4, marges de 30 mm a dalt, baix i esquerra i 25 mm a la dreta, Times New Roman de 12 punts, interlineat d’1,5 i text justificat. Cada capítol comença en pàgina nova i la portada queda fora de la numeració.

L’exportació paginada completa es prepara amb el complement local **Memòria PDF**. La [guia d’exportació](Guia_exportacio_Obsidian.md) descriu l’activació i l’ús. El fragment CSS d’Obsidian permet també aplicar els estils bàsics a l’exportació nativa. La numeració de l’índex i les capçaleres depenen de la paginació, no només del CSS.

Numereu les figures i les taules, afegiu-hi un peu descriptiu i indiqueu la font o l’elaboració pròpia. Citeu les fonts dins del text i a les referències amb un únic sistema. La plantilla adopta APA 7 per a les citacions, pendent de validar amb el tutor.

### Dades i decisions inicials

| Element | Dada o estat actual |
| --- | --- |
| Nom definitiu de l’aplicació | [Nom] |
| Centre destinatari i persona interlocutora | Institut Rafael Campalans, Anglès. [Persona interlocutora del centre pendent de concretar] |
| Autoria i responsabilitats | Projecte en parella: Isaac Martínez Boada i David Baños Fàbregas. [Justificació del treball en parella i repartiment de tasques pendents] |
| Tutoria acadèmica | Julià Fernàndez Martínez |
| Nivell dels autors | 2n de Desenvolupament d’Aplicacions Multiplataforma |
| Inici previst | 27 d’octubre de 2026 |
| Presentació acadèmica prevista | 14 de maig de 2027 |
| Plataformes i tecnologies | Android amb Kotlin, API pròpia i base de dades relacional. Tecnologia del servidor, SGBD i versions pendents de concretar. |
| Abast aprovat i data | [Acord amb el tutor i el client pendent] |
| Estat actual | Plantilla, DAFO, proposta de forma jurídica i simulació econòmica a tres anys preparats. Implementació i validació amb usuaris pendents. |

## 1 Introducció i objectius

### 1.1 Descripció i context

Aquest projecte final de Desenvolupament d’Aplicacions Multiplataforma es planteja per a l’Institut Rafael Campalans, a Anglès. Parteix d’una idea del professorat: desenvolupar una aplicació per gestionar les ofertes de pràctiques destinades a l’alumnat dels cicles formatius que imparteix el centre.

Com a proposta inicial, l’aplicació permetria consultar ofertes de pràctiques, presentar candidatures i facilitar-ne el seguiment per part de l’institut. El funcionament concret i les funcionalitats s’hauran de definir amb el centre i validar amb el tutor.

El projecte s’inicia des de zero. El primer pas demanat pel tutor ha estat preparar una plantilla de memòria, que s’anirà completant a mesura que avancin l’anàlisi, la planificació i el desenvolupament de l’aplicació.

En aquesta fase també s’han elaborat un DAFO, una justificació de la forma jurídica proposada i un pressupost empresarial a tres anys. Aquests documents aporten decisions inicials i estimacions; no acrediten encara la implementació del producte ni l’acceptació per part del centre.

[Pendent d’analitzar amb el centre: com es gestionen actualment les ofertes i les pràctiques, quines dificultats es detecten i quines necessitats ha de cobrir l’aplicació.]

### 1.2 Motivació i finalitats

La nostra motivació neix de la proposta del professorat de crear una eina per gestionar les ofertes de pràctiques dels cicles formatius del centre. Ens interessa desenvolupar una aplicació vinculada a una necessitat del nostre entorn educatiu i estudiar com pot facilitar la connexió entre l’alumnat i les empreses col·laboradores.

Considerem que la idea té possibilitats d’evolució i que, en el futur, podria servir com a referència per a iniciatives semblants. L’escalabilitat i les possibles ampliacions s’hauran de valorar durant l’anàlisi i el disseny; en aquesta fase inicial encara no estan demostrades ni formen part d’un abast aprovat.

Com a objectiu general provisional, ens proposem desenvolupar una aplicació que centralitzi les ofertes de pràctiques adreçades a l’alumnat de l’Institut Rafael Campalans i faciliti la connexió amb les empreses col·laboradores. Els objectius específics següents són una proposta inicial pendent de validació:

| Objectiu proposat | Criteri de verificació pendent |
| --- | --- |
| Centralitzar les ofertes | [Una oferta validada és consultable pels perfils autoritzats] |
| Facilitar les candidatures | [Un alumne pot presentar i consultar una candidatura] |
| Facilitar el seguiment | [Coordinació consulta els estats que li corresponen] |

### 1.3 Alternatives i elecció tecnològica

S’ha escollit inicialment una aplicació Android amb Kotlin. L’arquitectura prevista utilitza una API pròpia com a intermediària entre el mòbil i una base de dades relacional. Cal completar la comparació d’alternatives i concretar la tecnologia del servidor, el SGBD i les versions que s’utilitzaran.

El projecte web desenvolupat per un equip de DAW és independent i no es preveu integrar-lo en la primera versió. L’elecció d’Android permet centrar el treball en una única plataforma inicial, però caldrà validar amb els usuaris si cobreix les seves necessitats d’accés.

[Compareu el procés actual, l’adaptació d’una solució existent i el desenvolupament propi. Completeu la justificació tècnica amb fonts i criteris de cost, manteniment i adequació a DAM.]

### 1.4 Organització de la memòria

La memòria s’organitza en una introducció al projecte i als seus objectius, un pla d’empresa i viabilitat i un apartat de planificació. A continuació es preveuen els requeriments, l’anàlisi funcional, l’arquitectura, el disseny de les dades i les interfícies. Els capítols posteriors recolliran la construcció, la seguretat, el desplegament, les proves i les incidències.

El document també inclou un dietari de seguiment, les conclusions, el comentari personal, les referències bibliogràfiques i els annexos. En aquesta fase, aquests apartats constitueixen l’estructura de treball i s’ompliran amb les decisions i les evidències que es generin durant el projecte.

## 2 Pla d’empresa i viabilitat

### 2.1 Client i estudi de mercat

El centre destinatari del projecte és l’Institut Rafael Campalans, a Anglès, i la iniciativa parteix d’una proposta del professorat. Els destinataris principals són els alumnes dels cicles formatius del centre que han de realitzar pràctiques.

Com a usuaris potencials també es preveuen les empreses col·laboradores i les persones del centre responsables de gestionar les ofertes i el seguiment de les pràctiques. La participació de cada perfil i els seus permisos s’hauran de concretar durant l’anàlisi.

No hi ha contracte ni adjudicació. L’ampliació a altres centres de la Generalitat forma part de la simulació empresarial, condicionada a validar el producte i obtenir els contractes corresponents.

[Pendent: identificar la persona interlocutora del centre, recollir les necessitats dels usuaris i comparar alternatives amb fonts documentades. L’estudi de mercat i la demanda multicentre encara no estan validats.]

### 2.2 Proposta de valor i model de sostenibilitat

La proposta de valor és reunir les ofertes de pràctiques i facilitar la connexió entre alumnat, empreses i centre. Cal comprovar l’avantatge respecte dels canals actuals mitjançant entrevistes i una prova pilot.

El model empresarial estudiat combina el desenvolupament del pilot amb serveis posteriors d’implantació, allotjament, suport i manteniment. S’han simulat **45.000 € sense IVA** per al pilot i **3.000 € anuals sense IVA per centre** a partir del segon any operatiu. El primer any de manteniment es considera inclòs al pilot. Són hipòtesis comercials, no preus acceptats.

La continuïtat dependrà de les vendes, els cobraments i el cost de prestar el servei. L’expansió a altres centres requerirà nous acords i definir els drets sobre el programari. El pressupost global de l’empresa no equival a una factura a càrrec de l’institut.

### 2.3 Anàlisi DAFO

Aquest DAFO analitza la situació inicial del projecte d’una borsa de pràctiques per a l’Institut Rafael Campalans. El desenvolupament parteix de zero i el duen a terme dos alumnes de segon de DAM. Les oportunitats i les amenaces es plantegen com a possibilitats que caldrà contrastar durant l’estudi de mercat i les consultes amb el centre.

#### 2.3.1 Fortaleses

- **F1. Públic destinatari delimitat.** El projecte s’adreça inicialment a l’alumnat dels cicles formatius d’un institut concret. Aquest enfocament facilita centrar l’anàlisi en un entorn identificable i acotar la primera versió.
- **F2. Perspectiva de l’alumnat.** Com a estudiants del centre, podem aportar la nostra visió sobre la consulta d’ofertes i la informació que ens resultaria útil per buscar pràctiques. Aquesta perspectiva es complementarà amb la dels altres usuaris.
- **F3. Treball en parella.** Disposar de dos membres permet repartir tasques, revisar les aportacions i compartir la resolució dels problemes tècnics.
- **F4. Formació vinculada al producte.** Els continguts de DAM ofereixen una base relacionada amb les necessitats del projecte, com la programació, les bases de dades i les interfícies.

#### 2.3.2 Debilitats

- **D1. Requeriments encara per definir.** No s’ha analitzat prou el funcionament actual de la gestió de pràctiques ni s’han concretat els permisos, les dades i les funcionalitats necessàries. Desenvolupar abans de resoldre aquestes qüestions podria provocar canvis importants.
- **D2. Capacitat de treball limitada.** L’equip està format per dues persones i ha de compatibilitzar el projecte amb la resta del cicle. Caldrà assumir també les tasques de documentació, proves i desplegament.
- **D3. Absència d’un producte validat.** Encara no disposem d’un prototip ni de proves amb usuaris que permetin comprovar la utilitat i la facilitat d’ús de la proposta.
- **D4. Organització i continuïtat pendents.** Encara s’han de definir el repartiment de responsabilitats, la documentació tècnica i el procediment de manteniment. Sense aquesta preparació, el coneixement podria quedar massa concentrat en els desenvolupadors.

#### 2.3.3 Oportunitats

- **O1. Proposta sorgida del professorat.** L’interès inicial del professorat ofereix una via per contrastar la idea i identificar les persones del centre que poden ajudar a definir les necessitats.
- **O2. Possibilitat de validació en un entorn proper.** Si el centre ho autoritza i els participants estan disponibles, es podria provar una primera versió amb un grup reduït d’alumnes i responsables de pràctiques.
- **O3. Participació potencial de les empreses.** Consultar empreses que ofereixen pràctiques permetria conèixer quina informació necessiten publicar i com voldrien gestionar les candidatures.
- **O4. Possible ampliació a altres grups o centres.** Si la primera versió demostra utilitat i es detecten necessitats semblants, es podria estudiar una ampliació. Aquesta oportunitat no implica que l’escalabilitat estigui demostrada.

#### 2.3.4 Amenaces

- **A1. Alternatives i canals ja establerts.** Les eines o els procediments que utilitzi el centre podrien cobrir prou bé la necessitat. Cal comprovar si una aplicació nova aportaria un benefici suficient per justificar-ne l’adopció.
- **A2. Participació insuficient d’alumnat i empreses.** La utilitat de la borsa depèn de disposar d’ofertes i d’usuaris interessats. Una participació baixa d’una de les parts podria desincentivar l’altra.
- **A3. Dependència de tercers per validar el projecte.** La disponibilitat del professorat, dels responsables de pràctiques i de les empreses pot condicionar les entrevistes, les revisions i les proves.
- **A4. Recursos i gestió del servei no garantits.** L’ús real dependrà de disposar d’allotjament, autorització del centre i persones que mantinguin les ofertes actualitzades i administrin el servei després del lliurament.

#### 2.3.5 Línies d’actuació derivades del DAFO

| Finalitat | Actuació proposada |
| --- | --- |
| Reduir les debilitats | Analitzar el procés actual, acordar un abast mínim, repartir responsabilitats i preparar un prototip abans d’ampliar el desenvolupament. |
| Minimitzar les amenaces | Comparar els canals existents, planificar les validacions amb antelació i aclarir les condicions d’allotjament i administració. |
| Potenciar les fortaleses | Centrar la primera versió en el centre, incorporar la perspectiva de l’alumnat i revisar conjuntament les aportacions dels dos membres. |
| Aprofitar les oportunitats | Proposar entrevistes i una prova pilot amb participants del centre i empreses, i valorar ampliacions a partir dels resultats obtinguts. |

El DAFO s’haurà de revisar quan disposem d’entrevistes, d’una comparació d’alternatives i de les primeres proves del prototip.

### 2.4 Pressupost i finançament

S’ha preparat una simulació per al període octubre de 2026 – setembre de 2029, detallada al [llibre de pressupost](Pressupost_financament_3_anys.xlsx) i a l’[informe explicatiu](Informe_pressupost_i_financament_3_anys.md). Els imports següents són orientatius; les vendes i els costos comptables s’expressen sense IVA deduïble.

| Element | Previsió inicial |
| --- | --- |
| Desenvolupament i valoració comercial | 900 h × 45 €/h = 40.500 €; amb un 10 % de contingència, 44.550 €. Pilot simulat arrodonit a 45.000 €. |
| Arrencada i organització empresarial | 100 h addicionals; total de llançament de 1.000 h conjuntes. |
| Equips | 3.600 €: portàtils existents valorats en 2.000 € aportats sense caixa i compres de 1.600 € més IVA. |
| Retribució dels dos socis | 1.800 € bruts mensuals per persona més compensació bruta RETA estimada en 400 €/persona/mes. |
| Serveis recurrents inicials | 5.330 €/any; s’hi afegeixen infraestructura variable i suport extern segons l’escenari. |
| Aportació dinerària dels socis | 20.000 € en total, 10.000 € per persona. |
| Préstec simulat | 30.000 €, tipus nominal del 7 %, termini de 60 mesos, comissió de l’1 % i quota aproximada de 594 €/mes. |
| Subvencions al cas base | 0 €; no es pressuposten ajuts sense concessió. |

Les hores valoren comercialment el projecte, però no es tornen a sumar com a despesa als sous. Les aportacions dels socis i els préstecs són finançament, no ingressos per vendes. Les compres d’equips afecten la caixa i l’actiu; el resultat recull l’amortització.

**Resultat net anual estimat**, amb imports arrodonits a euros:

| Escenari | Any 1 | Any 2 | Any 3 |
| --- | ---: | ---: | ---: |
| Prudent | −17.565 € | −55.234 € | −50.560 € |
| Central | −17.565 € | −15.198 € | 14.632 € |
| Expansió | −17.565 € | 4.394 € | 47.936 € |

Els anys operatius van d’octubre a setembre. Els centres previstos al final dels tres anys són 1/1/3 en el prudent, 1/12/24 en el central i 1/20/40 en expansió; els ingressos es prorrategen segons la incorporació efectiva. Cap desplegament està garantit.

En l’escenari central, el dèficit màxim de caixa és de **12.289 €** i el patrimoni net mínim és de **−15.480 €**. Es planteja una aportació complementària orientativa de **31.000 € a fons propis des de l’inici**, que també cobriria la reserva objectiu de tres mesos. No està compromesa ni es considera disponible al cas base. Les necessitats de caixa i patrimoni no se sumen: una mateixa aportació pot cobrir totes dues.

La fiscalitat, les quotes i els proveïdors són estimacions pendents de validar. El pressupost empresarial assumeix el cost íntegre de la infraestructura; la disponibilitat inicial d’una base de dades al centre no es tracta com un recurs gratuït garantit.

### 2.5 Forma jurídica proposada

Es proposa una **SL amb dos socis al 50 %**, treballadors enquadrats en principi al RETA societari, per gestionar conjuntament contractes, recursos i continuïtat del servei. La comparació amb una societat civil i amb dos autònoms independents es desenvolupa a la [justificació de la forma jurídica](Justificacio_forma_juridica.md).

La constitució, el pacte de socis, les remuneracions i la formalització de les aportacions continuen pendents. Els 20.000 € són aportacions dineràries previstes; la distribució entre capital social i altres fons propis no està acordada. L’Excel utilitza una hipòtesi de capital inicial per a les alertes patrimonials que caldrà adaptar a la constitució real.

## 3 Planificació i metodologia

### 3.1 Fases i temporització

L’inici previst és el **27/10/2026** i la presentació acadèmica, el **14/05/2027**. Es proposa analitzar el procés actual, acordar l’abast, preparar un prototip, desenvolupar les funcions prioritàries i validar-les. La documentació i el dietari s’actualitzaran durant totes les fases.

| Fase | Hores conjuntes previstes | Hores reals | Dates |
| --- | ---: | --- | --- |
| Anàlisi i abast | 80 h | [Pendent de registrar] | [A concretar al Gantt] |
| Disseny UX i model de dades | 120 h | [Pendent de registrar] | [A concretar al Gantt] |
| Construcció: API i Android | 460 h | [Pendent de registrar] | [A concretar al Gantt] |
| Proves i desplegament | 160 h | [Pendent de registrar] | [A concretar al Gantt] |
| Documentació i defensa | 80 h | [Pendent de registrar] | [A concretar al Gantt] |
| **Total desenvolupament** | **900 h** | [Pendent] | Fins a la primera versió i validació |
| Arrencada empresarial, separada del desenvolupament | 100 h | [Pendent] | [A concretar] |

Abans del 9 d’abril s’han considerat 5 h setmanals al centre i 16 h a casa **per persona**; aquesta interpretació de les hores de casa s’ha de confirmar. Per a la fase intensiva del 9 d’abril al 14 de maig es preveuen un màxim de 17 h setmanals al centre per persona, sense afegir hores de casa al pressupost base.

La capacitat conjunta de 1.010 h és una estimació amb 20 setmanes efectives inicials i cinc d’intensives. El marge sobre les 1.000 h de llançament és petit. Les hores reals, els períodes no lectius i les dependències s’hauran de concretar al Gantt. La referència de 297 h de la documentació docent s’ha de contrastar amb el tutor: no equival automàticament a aquesta dedicació conjunta empresarial.

La simulació financera diferencia una beta al març de 2027, una versió funcional al maig i el lliurament comercial al juny. Aquest calendari comercial és una hipòtesi i no modifica la data de presentació acadèmica.

### 3.2 Scrum i seguiment

L’equip del projecte està format per Isaac Martínez Boada i David Baños Fàbregas, amb la tutoria acadèmica de Julià Fernàndez Martínez. La justificació del treball en parella i el repartiment de responsabilitats es concretaran durant la planificació. Les hores estimades es contrastaran amb dos dietaris individuals; encara no s’han assignat mòduls concrets a cada autor.

[Documenteu els sprints setmanals, el backlog, la planificació, les revisions i les retrospectives a Jira o una eina similar compartida amb el professorat. Indiqueu com s’adapten els rols a la mida de l’equip.]

### 3.3 Control de versions i canvis

[Indiqueu el repositori Git compartit amb el professorat, el criteri de branques, els commits regulars i documentats i les versions de lliurament. Relacioneu tasques, requisits i commits. Registreu els canvis d’abast i el vistiplau del tutor abans de descartar funcionalitats proposades.]

### 3.4 Riscos del projecte

Primera identificació de riscos a partir del DAFO. La probabilitat, l’impacte i els responsables encara s’han de valorar i assignar.

| Risc | Probabilitat i impacte | Resposta proposada i responsable pendent |
| --- | --- | --- |
| Requeriments poc definits i canvis d’abast (D1) | [Pendent de valorar] | Validar necessitats i prioritats amb el centre abans de desenvolupar. [Responsable] |
| Excés de feina per a dos membres (D2) | [Pendent de valorar] | Acotar la primera versió i repartir les tasques. [Responsable] |
| Retard en les validacions externes (A3) | [Pendent de valorar] | Acordar revisions amb antelació. [Responsable] |
| Poca participació dels usuaris (A2) | [Pendent de valorar] | Proposar una prova pilot i recollir les dificultats d’ús. [Responsable] |
| Infraestructura o continuïtat no confirmades (A4) | [Pendent de valorar] | Contrastar proveïdor, costos i administració del servei. [Responsable] |
| Finançament insuficient i retard de cobrament | [Pendent de valorar] | Revisar mensualment la caixa i obtenir finançament abans dels dèficits previstos. [Responsable] |
| Expansió inferior a la prevista | [Pendent de valorar] | Contrastar demanda i revisar costos i preus abans d’assumir més compromisos. [Responsable] |
| Pèrdues i deteriorament patrimonial | [Pendent de valorar] | Revisar fons propis i viabilitat; un préstec addicional no compensa les pèrdues. [Responsable] |

## 4 Abast i requeriments

### 4.1 Àmbit i límits

L’àmbit inicial es limita a una borsa de pràctiques per a l’alumnat dels cicles formatius de l’Institut Rafael Campalans. Es proposa prioritzar les ofertes, les candidatures i el seguiment, amb l’abast pendent de validació. La plataforma inicial és Android. La integració amb el projecte web de DAW i el desplegament multicentre queden fora de la primera versió proposada; l’ampliació es valorarà posteriorment.

[Concreteu què cobreix la borsa de pràctiques i què queda fora. Acordeu si l’aplicació només gestiona candidatures o també adjudica places. No pressuposeu que substituirà la gestió administrativa de les pràctiques.]

### 4.2 Actors i permisos

| Perfil proposat | Responsabilitat per validar |
| --- | --- |
| Alumnat | Consultar ofertes i gestionar les pròpies candidatures. |
| Empresa | Gestionar les seves ofertes i les candidatures autoritzades. |
| Coordinació de pràctiques | Validar ofertes i fer seguiment segons els permisos acordats. |
| Administració del sistema | Gestionar comptes, rols i configuració. |

### 4.3 Requeriments funcionals

Exemples de partida pendents de validació:

| ID | Requeriment proposat | Acceptació pendent |
| --- | --- | --- |
| RF01 | Accés amb rols diferenciats | [Operacions permeses i denegades] |
| RF02 | Publicació i validació d’ofertes | [Flux i estat de visibilitat] |
| RF03 | Consulta i filtratge d’ofertes | [Filtres acordats] |
| RF04 | Presentació de candidatures | [Regles i control de duplicats] |
| RF05 | Seguiment de candidatures | [Estats i transicions autoritzades] |

### 4.4 Requeriments no funcionals

Com a prioritats inicials es proposen una interfície senzilla per afavorir l’adopció, un control d’accés segons el perfil i una estructura de codi documentada que faciliti el manteniment. Aquests criteris s’hauran de transformar en requeriments mesurables durant l’anàlisi.

[Assigneu un identificador a cada requisit de seguretat, usabilitat, accessibilitat, rendiment, disponibilitat, compatibilitat i mantenibilitat. Definiu una mètrica, un llindar acordat i una prova; no useu únicament qualificatius com ràpid o segur.]

## 5 Anàlisi funcional i casos d’ús

### 5.1 Diagrama de casos d’ús

[Inseriu el diagrama amb els actors i els límits del sistema. Manteniu coherència amb els requeriments RF i els permisos. Afegiu número, títol i font a cada diagrama.]

### 5.2 Fitxes de casos d’ús

Dupliqueu el model següent per a les funcionalitats principals.

| Camp | Contingut a completar |
| --- | --- |
| Identificador i nom | CU01 Presentar candidatura [exemple proposat] |
| Actors i requisits vinculats | [Actor principal, secundaris i RF relacionats] |
| Precondicions | [Sessió, perfil i oferta disponibles segons les regles acordades] |
| Flux principal | [Passos numerats de l’actor i resposta del sistema] |
| Alternatives i errors | [Duplicat, oferta tancada, permisos i fallada del servei] |
| Postcondicions | [Canvi persistent i estat final esperat] |
| Regles de negoci | [Terminis, elegibilitat i restriccions acordades] |

### 5.3 Diagrames d’activitat

[Modeleu com a mínim els fluxos principals acordats, com la validació d’una oferta i la tramitació d’una candidatura. Representeu decisions, responsables, alternatives i finals.]

### 5.4 Estats i regles del procés

[Definiu els estats de les ofertes i candidatures, qui pot canviar-los i quines transicions són vàlides. Acordeu el tractament de retirades, tancaments i candidatures pendents.]

## 6 Arquitectura i disseny tècnic

### 6.1 Arquitectura del sistema

L’arquitectura prevista és **aplicació Android en Kotlin → API pròpia → base de dades relacional**. El mòbil enviarà peticions a l’API, que haurà de validar l’usuari, els permisos i les dades abans d’accedir a la persistència. Les credencials de la base de dades es mantindran al servidor.

La tecnologia de l’API, el motor de base de dades, les versions i la configuració encara s’han de concretar. Aquest esquema és una proposta, no una implementació comprovada.

[Inseriu el diagrama d’arquitectura i justifiqueu responsabilitats, comunicacions, límits i decisions.]

### 6.2 Disseny modular i dependències

| Mòdul proposat | Responsabilitat | Dependències pendents |
| --- | --- | --- |
| Identitat i accés | Comptes i permisos | [Mòduls o serveis] |
| Ofertes | Cicle de vida de les ofertes | [Mòduls o serveis] |
| Candidatures | Sol·licituds i seguiment | [Mòduls o serveis] |
| Gestió del centre | Validació i administració | [Mòduls o serveis] |

### 6.3 Diagrama de classes

[Inseriu classes, atributs, operacions i relacions rellevants, amb multiplicitats. Expliqueu la correspondència amb els mòduls i les regles de negoci.]

### 6.4 Accés a fonts de dades

Es preveu una API pròpia per connectar l’aplicació amb la base de dades. phpMyAdmin és una eina d’administració de bases de dades, no l’API ni el motor del SGBD. Cal confirmar el motor, la versió i els recursos disponibles abans de definir la connexió del servidor.

[Documenteu els contractes de l’API, l’autenticació, les respostes d’error i les dependències. Confirmeu amb el tutor si el requisit acadèmic de fonts externes exigeix alguna integració addicional a la base de dades i l’API pròpies.]

## 7 Estructura i persistència de dades

### 7.1 Model entitat relació

[Inseriu el model conceptual amb entitats, atributs, relacions i cardinalitats. Possibles entitats per validar: usuari, alumne, empresa, oferta i candidatura. Justifiqueu si coordinació i administració són rols o entitats diferenciades.]

### 7.2 Model relacional

[Transformeu el model conceptual en taules amb claus primàries, claus foranes, tipus, nul·labilitat i restriccions. Justifiqueu la normalització i els índexs segons les consultes previstes.]

### 7.3 Diccionari de dades

| Taula i camp | Tipus | Restriccions | Significat |
| --- | --- | --- | --- |
| [taula.camp] | [tipus i mida] | [PK, FK, únic, nul] | [Definició] |
| [taula.camp] | [tipus i mida] | [Validació] | [Definició] |

### 7.4 Integritat i conservació

[Definiu com es gestionen duplicats, concurrència, eliminacions i historial. Acordeu quines dades i documents són necessaris, qui hi accedeix i durant quant temps es conserven. Utilitzeu dades fictícies a les proves i a les captures de la memòria.]

### 7.5 Inicialització i migracions

[Documenteu l’esquema, les migracions, les dades de demostració i els passos per reproduir l’entorn sense credencials ni dades personals reals.]

## 8 Interfícies i interacció amb l’usuari

### 8.1 Navegació i recorreguts

[Inseriu el mapa de pantalles per perfil i expliqueu el recorregut des de l’accés fins a completar les tasques principals. Relacioneu pantalles, casos d’ús i permisos.]

### 8.2 Disseny de pantalles

| Pantalla proposada | Objectiu | Evidència pendent |
| --- | --- | --- |
| Catàleg i detall d’oferta | Trobar i consultar pràctiques | [Prototip i captura] |
| Les meves candidatures | Consultar i gestionar sol·licituds | [Prototip i captura] |
| Gestió d’ofertes | Crear i revisar ofertes | [Prototip i captura] |
| Seguiment del centre | Validar i supervisar | [Prototip i captura] |

### 8.3 Formularis i estats de la interfície

[Expliqueu les validacions, els missatges d’error i els estats de càrrega, absència de dades i confirmació. Especifiqueu què passa quan no hi ha permisos o la connexió falla.]

### 8.4 Usabilitat i accessibilitat

Per contrastar el risc de poca participació identificat al DAFO, es proposa revisar un prototip amb possibles usuaris abans d’ampliar el desenvolupament. La prova pilot dependrà de l’acord amb el centre i de la disponibilitat dels participants.

[Definiu per a Android criteris d’etiquetatge accessible, contrast, mida de text, lector de pantalla, formularis i diferents mides de dispositiu. Recolliu proves amb usuaris, incidències i canvis derivats de les evidències.]

## 9 Construcció seguretat i desplegament

### 9.1 Implementació

[Descriviu l’estructura del codi, els components principals i les decisions que expliquen el funcionament. Relacioneu funcionalitats amb versions i tasques. Incloeu només fragments de codi que aportin una explicació rellevant.]

### 9.2 Seguretat i accés a les dades

Els permisos es preveuen a l’API per usuari i recurs, encara que la interfície també amagui les opcions no autoritzades. S’haurà de comprovar que un compte no pugui consultar ni modificar ofertes o candidatures d’altres comptes fora dels permisos acordats. L’aplicació no disposarà d’accés directe ni de credencials d’administració de la base de dades.

[Documenteu autenticació, autorització al servidor, validació d’entrades, protecció de credencials i comunicacions, i gestió de fitxers si n’hi ha. Afegiu una matriu de permisos i proves d’accés indegut entre comptes i rols.]

[Identifiqueu els requisits de privacitat aplicables i valideu-los amb el centre. Documenteu les decisions i les fonts consultades sense afirmar compliment normatiu sense comprovació.]

### 9.3 Còpies de seguretat i restauració

| Element | Configuració i verificació pendents |
| --- | --- |
| Abast i periodicitat | [Dades, fitxers, configuració i freqüència] |
| Custòdia i retenció | [Ubicació, permisos, protecció i terminis] |
| Restauració | [Procediment, responsable i data de prova] |
| Objectius de recuperació | [Pèrdua de dades i temps màxim acordats] |

### 9.4 Desplegament i posada en marxa

La simulació pressuposta allotjament extern assumit per l’empresa per a l’API, la base de dades i les còpies de seguretat. Encara no s’ha contractat el proveïdor ni configurat o verificat el desplegament. El recurs inicial de base de dades ofert pel centre no s’utilitza com a infraestructura gratuïta en el pressupost empresarial.

Abans de l’ús real, s’hauran d’acordar amb el centre la distribució de l’app Android, l’administració dels comptes, l’actualització de les ofertes i les responsabilitats de manteniment.

[Documenteu el destí real del desplegament, requisits d’instal·lació, configuració sense secrets, versions, verificació del servei i reversió. La presentació exigeix desplegar el producte en servidor o botiga d’aplicacions segons el tipus de projecte.]

## 10 Proves resultats i incidències

### 10.1 Estratègia de proves

Es proposa començar pels recorreguts principals: consultar una oferta, presentar una candidatura i comprovar els permisos dels perfils. Posteriorment es podria fer una prova pilot amb participants del centre. Aquestes proves estan pendents de concretar i executar.

[Expliqueu entorns, dades i criteris d’acceptació. Incloeu proves de funcionalitat, integració, permisos, integritat de dades i recorreguts complets. Afegiu rendiment i accessibilitat segons els requisits acordats.]

### 10.2 Traçabilitat i resultats

| Requisit | Prova i resultat esperat | Resultat real i evidència |
| --- | --- | --- |
| RF01 | [Accés permès i denegat per rol] | [Pendent d’executar] |
| RF04 | [Candidatura vàlida i duplicada] | [Pendent d’executar] |
| [RNF] | [Mètrica i llindar] | [Pendent d’executar] |

[Assigneu un ID a cada prova i registreu data, versió i estat. No confongueu una prova planificada amb una prova superada. Enllaceu les evidències detallades als annexos o al repositori.]

### 10.3 Errors i problemes durant el desenvolupament

| Incidència | Causa i impacte | Solució i verificació |
| --- | --- | --- |
| INC01 [descripció] | [Diagnòstic i efectes] | [Canvi, commit i prova] |

### 10.4 Avaluació amb el client

[Registreu la demostració, els participants, la data, les observacions i l’acceptació o els canvis sol·licitats. Diferencieu les funcionalitats lliurades de les limitacions conegudes.]

## 11 Seguiment diari

Registreu la feina de cada jornada durant tot el projecte. Com que el projecte es desenvolupa en parella, Isaac Martínez Boada i David Baños Fàbregas han de mantenir cadascun el seu propi dietari identificat. Dupliqueu el registre següent tantes vegades com calgui i indiqueu-hi l’autor corresponent.

### 11.1 Registre individual

| Camp | Registre |
| --- | --- |
| Data i autor | [Data i nom] |
| Temps dedicat | [Hores de la jornada] |
| Sprint i tasca | [Identificadors i enllaç] |
| Objectiu de la sessió | [Feina prevista] |
| Feina realitzada | [Accions i resultat concret] |
| Evidència | [Commit, document, captura o prova] |
| Dificultats i decisions | [Problema, solució o suport pendent] |
| Pas següent | [Tasca per a la sessió següent] |

### 11.2 Resum del seguiment

[Compareu dedicació prevista i real, resumiu les desviacions i relacioneu-les amb les revisions dels sprints. Documenteu reunions amb el tutor i el client, acords, responsables i terminis.]

## 12 Conclusions i comentari personal

### 12.1 Assoliment dels objectius

[Recupereu els objectius del capítol 1 i valoreu cadascun amb una evidència. Expliqueu què funciona, què queda parcial i què no s’ha assolit, amb les causes corresponents.]

| Objectiu | Grau d’assoliment | Evidència |
| --- | --- | --- |
| [Objectiu] | [Assolit, parcial o no assolit] | [Prova, versió o validació] |

### 12.2 Limitacions i línies futures

Com a possibilitat futura, identificada al DAFO, es podria estudiar l’ampliació a altres grups o centres. Aquesta línia dependrà de la validació de la primera versió i de les necessitats que es detectin; encara no forma part d’un abast aprovat.

La simulació econòmica central obté benefici el tercer any, però encara acumula aproximadament 18.131 € de pèrdues en els tres anys. Les vendes, els costos i el finançament pendents s’han de validar; el pressupost no demostra per si mateix la sostenibilitat definitiva.

[Descriviu les limitacions del producte lliurat i les millores futures prioritzades. Diferencieu allò implementat, allò validat i allò proposat.]

### 12.3 Comentari personal

[Valoreu els aprenentatges tècnics i organitzatius, les dificultats superades i què canviaríeu en una nova iteració. En equip, identifiqueu la reflexió i l’aportació de cada membre.]

## 13 Referències bibliogràfiques

Substituïu aquestes instruccions per les referències realment citades a la memòria, ordenades alfabèticament. Manteniu correspondència entre citacions i referències i apliqueu APA 7 de manera coherent, d’acord amb el criteri validat amb el tutor.

### 13.1 Models per completar

[Paràfrasi al text: (Cognom, any). Citació literal: afegiu el localitzador corresponent. Utilitzeu només autoria, dates i dades comprovades.]

[Llibre: Cognom, N. (Any). Títol del llibre en cursiva. Editorial.]

[Recurs web: Autor o organisme. (Data de publicació o actualització). Títol del recurs en cursiva. Nom del lloc si correspon. URL.]

[Documentació tècnica: Organització o autor. (Data). Títol i versió del recurs si correspon. URL del contingut consultat.]

### 13.2 Llista definitiva

Documents de treball citats en aquesta versió, d’elaboració pròpia (2026):

- Martínez Boada, I., i Baños Fàbregas, D. *Anàlisi DAFO*. [Document de treball](DAFO.md).
- Martínez Boada, I., i Baños Fàbregas, D. *Justificació de la forma jurídica*. [Document de treball](Justificacio_forma_juridica.md).
- Martínez Boada, I., i Baños Fàbregas, D. *Pressupost i finançament a tres anys*. [Llibre de càlcul](Pressupost_financament_3_anys.xlsx).
- Martínez Boada, I., i Baños Fàbregas, D. *Informe explicatiu del pressupost i del finançament a tres anys*. [Informe](Informe_pressupost_i_financament_3_anys.md).

[Afegiu les fonts externes realment consultades, incloses les fonts oficials dels documents jurídic i econòmic. Completeu dates i APA 7 i apliqueu sagnat francès de 1,27 cm. No incorporeu fonts sense comprovar.]

## 14 Annexos

Incloeu només material que complementi la memòria i citeu cada annex des del cos del treball. Si un document es lliura separat, indiqueu-ne el nom, la versió i la ubicació.

### 14.1 Proposta i acords

[Proposta aprovada: autors i repartiment, descripció, client final, tipus d’aplicació, tecnologies, SGBD i Gantt. Afegiu actes rellevants i canvis d’abast autoritzats.]

### 14.2 Manual d’usuari

[Prepareu un document identificable per al lliurament: accés, funcions per perfil, procediments amb captures, errors habituals i ajuda. Indiqueu aquí el fitxer i la versió; la presentació l’avalua separadament de la memòria.]

### 14.3 Manual tècnic i evidències

[Instruccions reproduïbles de desplegament i restauració, esquema de dades, contractes de serveis, proves detallades, prototips i captures complementàries. Excloeu secrets i dades personals reals.]

### 14.4 Materials de la defensa

[Identifiqueu la presentació i el guió de demostració. La documentació facilitada fixa un màxim de 20 minuts per a presentació i demostració; confirmeu les condicions de la convocatòria.]

### 14.5 Documents de treball disponibles

| Document | Contingut i estat |
| --- | --- |
| [DAFO](DAFO.md) | Anàlisi inicial, pendent de revisar amb evidències d’usuaris i mercat. |
| [Forma jurídica](Justificacio_forma_juridica.md) | Proposta de SL; constitució i acords pendents. |
| [Pressupost i finançament](Pressupost_financament_3_anys.xlsx) | Model de 36 mesos i tres escenaris, amb hipòtesis editables. |
| [Informe econòmic](Informe_pressupost_i_financament_3_anys.md) | Explicació del pressupost, els escenaris i les necessitats de finançament. |
| [Estil de la memòria](memoria-pdf.css) | Format de referència per a l’exportació paginada. |
