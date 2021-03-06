layout: true
  
<div class="my-header"></div>

<div class="my-footer">
  <table>
    <tr>
      <td>DWDS &ndash; Digitales Wörterbuch der deutschen Sprache</td>
      <td style="text-align:right"><a href="https://www.dwds.de">www.dwds.de</a></td>
    </tr>
  </table>
</div>

---

class: title-slide

# DWDS &ndash; Digitales Wörterbuch der deutschen Sprache  
## Mittels Computerlinguistik zum Wörterbuch der Zukunft

| Frank Wiegand   | Kay-Michael Würzner |
|:---------------:|:-------------------:|
| [wiegand@bbaw.de](mailto:wiegand@bbaw.de) | [wuerzner@bbaw.de](mailto:wuerzner@bbaw.de) |

---

# Überblick

+ Konzepte der Computerlinguistik
+ mit ihren Möglichkeiten und Grenzen
+ anhand des Digitalen Wörterbuchs der deutschen Sprache
+ mit praktischen Übungen

---

# Was ist Computerlinguistik?

- Teildisziplin der **Sprachwissenschaft**
    + Philologie: Beschäftigung mit den sprachlichen Zeugnissen **einer** Sprache/Sprachfamilie
        * *Germanistik*, *Anglistik*, *Romanistik* etc.
    + Linguistik: Beschäftigung mit **sprachübergreifenden** Phänomenen
        * Ebenen: *Phonologie*, *Morphologie*, *Syntax*, *Semantik* etc.
        * Anwendungsfelder: *Sprachverarbeitung*, *Spracherwerb*, *Sprachstörungen* etc.
- <span style="font-variant:small-caps;">Ferdinand de Saussure</span> (1857&ndash;1913)
    + Begründer des **sprachwissenschaftlichen Strukturalismus**
        * *Langage*: das (biologische) Sprachvermögen
        * *Langue*: Sprache als ein abstraktes System von Regeln
        * *Parole*: Sprechen, konkete Sprachverwendung

---

# Was ist Computerlinguistik?

- Zwei **Teildisziplinen**
    + *Natural Language Processing* (NLP, etwa Linguistische Datenverarbeitung)
        * Verfahren zur automatischen **Analyse** und **Generierung** von Sprache auf allen Ebenen
        * wichtiger Bestandteil unseres medialen Umfelds
    + *Computational Linguistics* (CL, etwa berechenbare, rechenbetonte Sprachwissenschaft)
        * theoretische Beschreibungen der formalen Grundlagen von Sprache
        * Berechenbarkeit, Beweisbarkeit, Modellierung
- <span style="font-variant:small-caps;">Noam Chomsky</span> (&#x2A;1928)
    + Begründer der **generativen Linguistik**
        * *Universalgrammatik*: alle Sprachen folgen gemeinsamen, angeborenen Prinzipien
        * *Tiefen- vs. Oberflächenstruktur*: unterschiedliche Realisierungen gleicher Bedeutungen basieren auf einer gemeinsamen abstrakten Struktur

---

# Computerlinguistik im Alltag

.center[![Websiete](figures/websiete.png)]

---

# Computerlinguistik im Alltag

<table>
  <tr>
    <td><img src="figures/wetter_bild.png"/></td>
    <td><img src="figures/wetter_text.png"/></td>
  </tr>
</table>

---

# Computerlinguistik im Alltag

.center[![Websiete](figures/mtl.png)]

---

# Computerlinguistik im Alltag

.center[<img src="https://media.diepresse.com/images/uploads_640/3/1/8/705304/020111102110031.jpg" width="300"/>]


---

# Computerlinguistik im Alltag

.center[![DWDS-Webseite](figures/dwds.png)]

---

# Das DWDS

- Institution: Berlin-Brandenburgische Akademie der Wissenschaften (BBAW)
- Langzeitvorhaben
- 15 Mitarbeiter/innen
- Wörterbücher, Textsammlungen (Korpora), Tools
- ca. 465 000 Wörterbucheinträge
- ca. 13 Milliarden Textbelege aus über vier Jahrhunderten


- (nur!) online: [https://www.dwds.de](https://www.dwds.de) (seit 2004)

---

# Lexikografische Arbeit

> In keiner Sprache kann man sich so schwer verständigen wie in der Sprache.  
*(<span style="font-variant:small-caps;">Karl Kraus</span>, österr. Schriftsteller, 1874&ndash;1936)*

+ (oft mühevolle) Handarbeit
+ viel Recherche:
    - in anderen Wörterbüchern
    - in Bibliotheken
    - im Internet
    - in Textsammlungen
    - ...
+ Teamsitzungen zur Absprache und Nachfrage

---

# Lexikografische Arbeit

+ *Deutsches Wörterbuch* (DWB), 1838&ndash;1961
    - von <span style="font-variant:small-caps;">Jacob</span> und <span style="font-variant:small-caps;">Wilhelm Grimm</span>
        * Gründungsväter der Germanistik
        * Herausgeber der weltberühmten *Kinder- und Hausmärchen*
    - das größte und umfassendste Wörterbuch zur deutschen Sprache
    - Belegwörterbuch zur Herkunft und zum Gebrauch jedes deutschen Wortes
    - 32 Bände, ca. 320&#x202f;000 Stichwörter, ca. 600&#x202f;000 Belege
    - konsequente Kleinschreibung

---

# Deutsches Wörterbuch (DWB)

.center[![¹DWB](http://dwb.bbaw.de/band1.jpg)]

---

# DWDS: Formteil

.center[<img src="figures/leiter1.png" width="700"/>]

- Zusammenfassung der **formalen Eigenschaften** eines Wortes
- teils manuell, teils automatisch erhoben

---

count:false

# DWDS: Formteil

.center[<img src="figures/leiter2.png" width="700"/>]

- Zusammenfassung der **formalen Eigenschaften** eines Wortes
- teils manuell, teils automatisch erhoben

---

# DWDS: Formteil

+ Wortart (Substantiv, Verb, Adjektiv, ...)
    + inklusive Eck- und Stammformen; Komparationsangaben
+ Schreibungen
    * alles zulässig: **Delfin**, **Delphin**
    * neue Rechtschreibung: **Ablass**, ~~Ablaß~~
    * war schon immer falsch: **E-Mail**, ~~Email~~
+ weitere Informationen
    * **die** E-Mail, **das** E-Mail
.diasys[süddeutsch, österreichisch, schweizerisch]
    * **das** Virus, **der** Virus
.diasys[umgangssprachlich]
    * **Ferien**
.diasys[wird nur im Plural verwendet]

---

# DWDS: Formteil

+ Homographie
    - gleich geschriebene Wörter
    - verschieden nach: Herkunft, Formen, Genus, Aussprache, Zusammensetzung
    - Beispiele:
        + **Bug**: Vorderteil eines Schiffes, (Software-)Fehler
        + **Band**: Pl. Bänder/Bande, Bände, Bands
        + **Bank**: Pl. Bänke, Banken
        + **sein**: Pronomen, Verb
        + **Dichtung**: von *dicht*, von *(er)dichten*
        + **Hut**: der, die
        + **Wachstube**: *Wach* + *Stube*, *Wachs* + *Tube*
+ Aussprache und Worttrennung
+ Wortzerlegung, Wortbildung

---

# NLP: morphologische Analyse

- Aufgabe
    + Bestimmung der **möglichen** Wortarten eines Wortes
      ```
      grünen ↦ {Verb, Adjektiv}
      Müller ↦ {Substantiv, Eigenname}
      ```
    + Abbildung auf eine kanonische **Grundform**
      ```
      grünen  ↦ grün
      Müllers ↦ Müller
      ```
    + Identifikation der beteiligten Wortbildungsprozesse
      ```
      Grünspan ↦ grün<A>#Span<N>
      verirren ↦ ver<p>+irren<V>
      ```

---

# NLP: morphologische Analyse

- Rezept `Finite State Morphology`:
    + Man nehme
        * eine **große** Liste einfacher Wörter
        * deren **morphosyntaktische** Eigenschaften
        * Vor- und Nachsilben,
    + packe dies in einen **endlichen Automaten** und
    + bilde dessen **Kleenesche Hülle**
- <span style="font-variant:small-caps;">Stephen Cole Kleene</span> (1909&ndash;1994)
    + Mitbegründer der Theoretischen Informatik
        * formale Sprachen
        * **Reguläre Ausdrücke**

---

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

.center[.img-orig[![Lexikon](figures/morph_ex.svg)]]

---

count: false

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

.center[.img-orig[![Lexikon](figures/morph_ex2.svg)]]

---

count: false

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

<center><img src="figures/morph_ex3.svg" width="650" /></center>

---

count: false

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

<center><img src="figures/morph_ex4.svg" width="880" /></center>

---

count: false

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

<center><img src="figures/morph_ex6.svg" width="880" /></center>

---

count: false

# NLP: morphologische Analyse

- Illustration
    + Lexikon `{schön<A>,Geist<N>}`
    + Vorsilben `{un<p>,ur<p>}`
    + Nachsilben `{heit<N>,lich<A>}`

<center><img src="figures/morph_ex5.svg" width="880" /></center>

---

# NLP: morphologische Analyse

- Zahlen
    + 1&#x202f;864&#x202f;991 Lexikoneinträge
    + 7&#x202f;678 Vorsilben
    + 1&#x202f;073 Nachsilben
    + 2&#x202f;679&#x202f;741 Zustände
- klassischer **regelbasierter** Ansatz,
    + manuell gepflegte **Daten** als Operanden und
    + manuell erstellte **Regeln** zu deren Kombination
- Bestandteil der meisten Sprachverarbeitungssysteme
- Wörterbuch unendlicher Größe:
    - [Dampfschifffahrtsgesellschaftskapitän](https://www.dwds.de/?q=Dampfschifffahrtsgesellschaftskapit%C3%A4n)
    - [Dampfschifffahrtsgesellschaftskapitänsmütze](https://www.dwds.de/?q=Dampfschifffahrtsgesellschaftskapit%C3%A4nsm%C3%BCtze)

---

# NLP: Worttrennung

- Aufgabe
    + Bestimmung aller möglichen Stellen für die Worttrennung **am Zeilenende**
      ```
      Elektrik ↦ Elek·t·rik ↦ {Elek-trik,Elekt-rik}
      ```
    + nicht zu verwechseln mit **Silbentrennung**
      ```
      Elektrik ↦ E·lek·trik ↦ {E-lek-trik}
      ```
    + Herausforderung durch **Lehnwörter**
      ```
      Software ↦ Soft·ware ↦ {Soft-ware}
      ```

---

# NLP: Worttrennung

- Rezept `Sequenzklassifizierung`
    + Man nehme
        * eine **sehr große** Liste **manuell annotierter** Daten und
        * einen **Trainingsalgorithmus**,
    + modelliere eine **`n:n`-Beziehung** zwischen Eingabe und Ausgabe,
        * jedes Eingabelement (Buchstabe) wird auf eine Klasse abgebildet
    + induziere ein **statistisches Modell**,
    + und evaluiere dessen Qualität anhand von **Evaluationsdaten**
- <span style="font-variant:small-caps;">Andrei Andrejewitsch Markov</span> (1856&ndash;1922)
    + wesentliche Beiträge zur **Wahrscheinlichkeitstheorie**
    + arbeitete früh (1913) mit Häufigkeitsanalysen in Textsammlungen
    + formulierte die Grundlagen sog. *Hidden Markov Models*

---

# NLP: Wortrennung

- Illustration
    + Daten
        * http://de.wiktionary.org
        * Wortrennungsangaben für > 250 000 deutsche Wörter
        * `Elektrik ↦ Elek·t·rik`
    + Kodierung `\(f: \Sigma\rightarrow\mathbb{B}\)` 
      $$
      f(x) = \begin{cases} 1 & x\,\text{gefolgt von Trennstelle} \\\\
      0 & \, \text{sonst}\end{cases}
      $$ 
      ```
      E l e k t r i k
      0 0 0 1 1 0 0 0
      ```
    + Training
        * Zählen von Sequenzen aus Eingabe-Ausgabe-Paaren unter der Markov-Annahme
        * Berechnung einer Wahrscheinlichkeitsverteilung
        * Repräsentation als statistisches Modell (HMM, CRF, neuronales Netz)

---

# NLP: Wortrennung

- Zusammenhang zu Morphologie!
    ```
    v e r i f i z i e r e n
    0 1 0 1 0 1 0 0 1 0 0 0
    v e r i r r e n
    0 0 1 0 1 0 0 0
    ```
- klassischer Ansatz: **überwachtes Lernen**,
    + manuell gepflegte **Daten** als Operanden und
    + **Induktionsverfahren** zu deren Modellierung
    + Grundlage von *Deep Learning* (**tiefe** neuronale Netze)
    - Einsatz auch außerhalb der Sprachverarbeitung
        + personalisierte Werbung
        + Kundenprofilierung etc.
    - Motivation für „Datensammelwut“

---

# Lexikografische Arbeit

+ Wortschatz der deutschen Sprache im Auge behalten
+ das eigene Wörterbuch kennen


1. neue Wörterbuchartikel schreiben: **Brexit**, **posten**
2. bestehende Artikel ergänzen:
    - neue Bedeutungen: **Maus**, **Ampel**
    - Anpassung an gesellschaftlichen Wandel: **Ehe**, **Eskimo**, **Gutmensch**
    - Artikel erweitern (weil bislang nur minimal)
3. bestehende Artikel überarbeiten:
    - Bedeutungswandel: **klicken**
    - Rechtschreibreform: ~~Ketschup~~, **Co-Trainer**

---

# Digitale Lexikografie

- Ziel:
    + Rückbindung der lexikografischen Arbeit an **repräsentative Quellen**
    + priorisierte Bearbeitung **wichtiger** (also häufiger) Phänomene
    + Möglichkeit **unmittelbar** auf interessante Bedeutungsverschiebungen oder Wortneuschöpfungen zu reagieren
- Methode:
    + Rückgriff auf **große Textsammlungen** (*Korpora*) verschiedener Genres
    + Einnahme verschiedener Blickwinkel (repräsentiert durch verschiedene Abfragewerkzeuge) zur vereinfachten Abfrage
    + Repräsentation auf **digitaler Plattform** (anstatt in Buchform)

---

# DWDS: Digitale Textkorpora

- (Sprachwissenschaftliche) Referenzkorpora
    + repräsentative Erfassung der Gesamtheit einer Sprache (bzw. eines Sprachstandes)
    + Englisch: British National Corpus (Burnard, 1995)
    + Deutsch:
        * DWDS-Kernkorpus (Geyken, 2007)
        * Deutsches Textarchiv (Geyken und Klein, 2009)
- Spezialkorpora
    + repräsentative Erfassung eines speziellen Ausschnitts einer Sprache
        * medial: Zeitungskorpora, Filmuntertitelkorpora, Internetkorpora
        * inhaltlich: Berliner Wendekorpus, JuSpiL-Korpus (Dittmar, 2005)
        * forschungsbezogen: childLex

---

# DWDS: Bedeutungsteil

- (Unter)Bedeutungen eines Wortes:
    + **scharf**: schneidend, spitz, stark reizend, genau, deutlich, streng, ...
    + **Läufer**: jmd. der läuft, Teppich, Schachfigur, ...
    + **Birne**: Frucht, Baum, Glühlampe, Kopf
- Markierungen:
    + 
.diasys[bildlich] den Teufel an die Wand **malen**
    + 
.diasys[salopp, abwertend] jmdn. nicht **riechen** können
    + 
.diasys[vertraulich] altes **Haus**!
    + 
.diasys[gehoben, veraltend] jemanden einer Tat **zeihen** *(= bezichtigen)*
    + 
.diasys[Medizin] **Exazerbation:** Verschlimmerung, zeitweise Steigerung, Wiederaufleben einer Krankheit
    + 
.diasys[Schülersprache, landschaftlich] **Giftzettel:** Schulzeugnis

---

# DWDS: Bedeutungsteil

- (konstruierte) Beispiele:
    + die allgemeinbildende, berufsbildende, zehnklassige **Schule**
- Belege aus Textsammlungen:
    + „Urlaub in der eigenen Stadt ist nicht traurig, sondern **trendy**, und das schon seit einer ganzen Weile.“ *[Welt am Sonntag, 25.09.2016, Nr. 39]*
- Konstruktionsmuster:
    + etwas **gilt**
    + etwas **gelten** lassen
    + etwas **geltend** machen
    + es **gilt** etwas (zu tun)
- Kollokationen (= Stellung, Anordnung):
    + *mit Akkusativobjekt:* **Drogen** beschlagnahmen, sicherstellen
    + *mit vergleichender Wortgruppe:* **Drogen** wie Kokain, Ecstasy, Heroin

---

# DWDS: Etymologie

- altgriechisch: *ἐτυμολογία (etymología)*
    + *ἔτυμος (étymos):* „wahr, echt, wirklich“
    + *λόγος (lógos):* „Wort“
- Wissenschaft von der Entstehung und geschichtlichen Veränderung einzelner Wörter 
- im DWDS mit ca. 25 000 Einträgen:
    + <span style="font-variant:small-caps;">Wolfgang Pfeiffer</span> (&#x2A;1922) &ndash; *Etymologisches Wörterbuch des Deutschen*

---

# DWDS: Etymologie &ndash; Beispiele

.smaller[**Fake News:** Übernahme von gleichbedeutend *fake news* (amerik.-engl.)]

.smaller[**Eskimo:** Genaue Herkunft unsicher; wohl über **eskimoda**<sub>en</sub> oder **esquimau**<sub>frz</sub> aus einer indigenen nordostamerikanischen Algonkin-Sprache (Innu-aimun bzw. Montagnais), vermutlich mit einer ursprünglichen Bedeutung ‘Schneeschuh-Knüpfer’. Eine zunächst angenommene ursprüngliche Bedeutung ‘Esser von rohem Fleisch’ gilt als widerlegt, war aber der Grund, die Bezeichnung **Eskimo** als abwertend einzuschätzen.]

.smaller[**Maulwurf:** Der Name hat mehrfach volksetymologische Umdeutungen erfahren. Die älteste Bezeugung ahd. (8. Jh.), mhd. *mūwerf*, ahd. *mūwerfo* (11. Jh.) enthält in ihrem ersten Glied ein zu aengl. *mūga*, *mūha*, *mūwa* ‘Kornhaufen’, engl. *mow* ‘Heu-, Kornhaufen’, anord. *mūgi*, *mūgr* ‘Menge, Haufen’, mhd. *mocke* ‘Klumpen, Brocken’ gehörendes Substantiv, das vielleicht mit griech. *mýkōn* (*μύκων*) ‘(Korn)haufen’ verwandt ist ...]

---

# DWDS: Etymologie &ndash; Aufgaben

+ Bestimme die Herkunft eines der folgenden Wörter:
    + *Ampel*
    + *Brille*
    + *Hängematte*
    + *heulen*
    + *Krawatte*
    + *Laune*
    + *Muckefuck*
    + *Teddy*

---

# DWDS: Thesaurus

- altgriechisch:
  + *θησαυρός (thesaurós)* → „Schatz, Schatzhaus“
  + später lateinisch *thesaurus* → *Tresor*
- Wortnetz: listet systematisch Wörter
    + gleichbedeutend, ähnlich (Synonyme)
    + Oberbegriffe (Hyperonyme)
    + Unterbegriffe (Hyponyme)
    + thematisch verwandt (Assoziationen)
    + Gegenwörter (Antonyme)
- im DWDS:
    + [OpenThesaurus](http://www.openthesaurus.de) mit ca. 160 000 Einträgen
    + GermaNet

---

# DWDS: Thesaurus

- Synonyme:
    * **Kreuz:**
        + Bürde, Crux, Fron, Joch, Knechtschaft, Krux, Last, Plage
        + Autobahnknoten
        + Rücken, Rückgrat, Wirbelsäule
- Oberbegriffe (Hyperonyme):
    + **Tomate:** Fruchtgemüse, essbare Pflanzen(teile), Grünzeug
- Unterbegriffe (Hyponyme):
    + **Fahrzeug:** Bahn, Bus, Zug
- Assoziationen:
    + **Apfel:** Birne, Apfelsaft
- Gegenworte (Antonyme):
    + **Ernst:** Spaß

---

# DWDS: Wortverlaufskurven

+ **Häufigkeit eines Wort über einen zeitlichen Verlauf**
+ nutzen Textsammlungen als Basis:
    - Zeitungen (1945 bis heute)
    - Deutsches Textarchiv und DWDS-Kernkorpus (1600&ndash;2000)
+ Metadaten für jeden Text:
    - *Datum* (Jahr)
    - *Textklasse* (Belletristik, Gebrauchsliteratur, Wissenschaft, Zeitung)
    - und viele weitere ...
+ Darstellung:
    - relativ (Vorkommen pro Million)
        + 
.red[Achtung!] Kurven werden geglättet, da nicht für jedes Jahr ausreichend und gleich viele Daten verfügbar sind
    - in absoluten Zahlen

---

# DWDS: Wortverlaufskurven

.center[<img src="figures/stress.svg" style="width:800px"/>]

---

# DWDS: Wortverlaufskurven

.center[<img src="figures/flugzeug_vs_eisenbahn.svg" style="width:800px"/>]

---

# DWDS: Wortverlaufskurven

.center[<img src="figures/kanzler_vs_kanzlerin.svg" style="width:800px"/>]

---

# NLP: Linguistische Annotation

- Aufgabe:
    + Auszeichnung bestimmter linguistischer Eigenschaften
    + Strukturierung und Anreicherung der Rohtexte
        * bessere Durchsuchbarkeit
        * einfachere Belegidentifikation
        * moderne Korpuspräsentationsformen
        * quantitative Auswertungen
    + Korpusumfang bedingt vollautomatische Analysekette

---

# NLP: Linguistische Annotation

- Rezept:
    + Zerlegung des Fließtextes in Wörter und Sätze: **Tokenisierung**
    + Bestimmung der Grundform der Wörter: **Lemmatisierung**
    + Bestimmung der tatsächlichen Wortart eines Wortes: **PoS-Tagging**
    + Klassifizierung der Beziehungen der Wörter untereinander: **Dependenzparsing**
- vollautomatisch möglich (mit akzeptabler Qualität)

---

# NLP: Tokenisierung

- Unterteilung von Fließtext in **Wörter** (bzw. *Tokens*) und **Sätze**
- (Vor-)Klassifizierung der Tokens zur Beschleunigung der morphologischen Analyse
    + Abkürzungen
    + Zahlen
    + Sonderzeichen
    + Fremdalphabete
- Normalisierung der Worttrennung
- Ansatz: Trennung an Leerraum
- im DWDS: statistischer Ansatz, **überwachtes Lernen**

---

# NLP: Tokenisierung

Problembereich *Satz*
```
Nach einer Schätzung des Industrieministeriums sind es mehr als 800.
»Österreich wurde alleingelassen in Europa«, beschwerte sich SPÖ-
Zentralsekretär Josef Cap.
SZ: Auf die Wahlerfolge der rechtsradikalen Parteien ...
```
Problembereich *Token*
```
Kaiser's-Netz → Kaiser 's-Netz
Jeanne d'Arc → Jeanne d' Arc
mm. → mm. [ORD]
CDU/CSU → CDU / CSU
(Verwaltungs-)Personal → ( Verwaltungs- ) Personal
```

---

# NLP: PoS-Tagging

- Auswahl der **wahrscheinlichsten Wortart** im konkreten Satzkontext aus der Menge der **möglichen** Wortarten eines
Wortes
- statistischer Ansatz, trainiert auf **manuell kategorisierten** Daten
    + Modell über Trigramme aus Wörtern und Kategoriemengen (i.e. Wortklasse)
    + Bestimmung der wahrscheinlichsten Kategoriesequenz fur einen Satz
    + heuristische Auswahl der »einfachsten« **Grundform**
    + angepasste Modelle fur historische Sprache, gesprochene Sprache, Kindersprache etc.

---

# DWDS: Wortverlaufskurven (rev.)

.center[<img src="figures/kohl1.svg" style="width:800px"/>]

---

count: false

# DWDS: Wortverlaufskurven (rev.)

.center[<img src="figures/kohl.svg" style="width:800px"/>]

---

# DWDS: Verwendungsbeispiele

+ **automatisch** gefundene Beispiele für Wörter
+ **gut** gewählte Beispiele und Belege
+ Belege aus **echten Texte**n:
    - aus verschiedenen Zeiten
    - aus verschiedenen Textsorten


- Kriterien:
    + Stichwort an prominenter Stelle
    + keine zu kurzen oder zu langen Sätze
    + Beleg soll nur gebräuchliche Wörter enthalten

---

# DWDS: Verwendungsbeispiele

+ früher: hunderte Zettelkästen mit Belegstellen

.center[![lexikografischer Arbeitsplatz](http://dwb.bbaw.de/arbeitsstelle/archiv/archiv1-m.jpg)]

---

# DWDS: Verwendungsbeispiele

+ heute: automatisch ausgesucht

.center[![Stress](figures/roulade.png)]

---

# DWDS: Typische Verbindungen

- **DWDS-Wortprofil**
    + statistisch signifikante und damit typische Wortverbindungen
    + als Schlagwortwolke (Tagcloud) oder als Tabelle
    + kombiniert distributionelle Semantik mit Dependenzparsing

.center[.img-orig[![Stress](figures/wp_kaffee_objekt.png)]]

---

# DWDS: Typische Verbindungen

.center[<img src="figures/wp_kaffee.png" style="width:700px"/>]

---

# NLP: Distributionelle Semantik

- Semantik: Theorie von der sprachlichen Bedeutung
    + **lexikalische** Semantik: Wortbedeutungen
    + **kompositionelle** Semantik: Phrasen- und Satzbedeutung
    * **ontologische** Beziehungen: Synonyme, Hyponyme, Hyperonyme
- mit automatischen Verfahren sehr schwer zu erfassen
- distributionelle Ähnlichkeit: gleiche Kontexte ⇒ ähnliche Bedeutung
- <span style="font-variant:small-caps;">John Rupert Firth</span> (1890&ndash;1960)
    + »You shall know a word by the company it keeps« (Firth, J. R. 1957)
    + `Er versenkte den .... im Tor.`

---

count: false

# NLP: Distributionelle Semantik

- Semantik: Theorie von der sprachlichen Bedeutung
    + **lexikalische** Semantik: Wortbedeutungen
    + **kompositionelle** Semantik: Phrasen- und Satzbedeutung
    * **ontologische** Beziehungen: Synonyme, Hyponyme, Hyperonyme
- mit automatischen Verfahren sehr schwer zu erfassen
- distributionelle Ähnlichkeit: gleiche Kontexte ⇒ ähnliche Bedeutung
- <span style="font-variant:small-caps;">John Rupert Firth</span> (1890&ndash;1960)
    + »You shall know a word by the company it keeps« (1957)
    + `Er versenkte den Ball im Tor.`

---

# NLP: Distributionelle Semantik

- Rezept:
    + Man definiere einen **Kontext** und **interessante** Wörter (z.B. *Satz* sowie *Nomen* und *Verben*),
    + werfe für jedes Zielwort alle interessanten Wörter aus dem Kontext in einen Topf (*Bag of Words*),
    + repräsentiere den Topf als **hochdimensionalen Vektorraum** und
    + vergleiche die Vektoren miteinander.
- Illustration:
    + `Der Säufer randalierte in der Kneipe. Die Polizei sperrte den Säufer ein, weil er randalierte.`
.right[<img src="figures/distr.svg" style="width:180px"/>]

---

# NLP: Dependenzparsing

- Bestimmung der **strukturellen** Beziehungen zwischen Wörtern im Satz
- **regelbasierter** Ansatz
    + handgeschriebene Grammatik
    + Grundform, Kategorie und morphosyntaktische Merkmale als Beschreibungseinheit
    + Implementierung mit Hilfe endlicher, gewichteter Automaten
(schnell!)

---

# NLP: Dependenzparsing

.center[<img src="figures/dependency_ex.svg" style="width:800px"/>]

---

# DWDS: Typische Verbindungen

+ Wortvergleiche: Gemeinsamkeiten und Unterschiede

.center[<span style="color:#5B7BB6;font-weight:bold">verkünden</span> und <span style="color:#c30c60;font-weight:bold">bekanntgeben</span>]

.center[<img src="figures/wp_vergleich.png" style="height:400px"/>]

---

# Spiel: Profilardy

.center[[**Klick mich!**](https://docs.google.com/presentation/d/1qPfvBRmpPNAV6Y3zHGoYXAj-MuKy84E1ZJPvgMjwezA)]

---

# Zusammenfassung

- Wörterbücher schreiben sich nicht komplett allein von selbst
- aber vieles ist maschinell (automatisch) machbar
- https://www.dwds.de


- Vielen Dank!


.center[<img src="https://www.golem.de/1309/101460-64454-i_rc.jpg"/>]
