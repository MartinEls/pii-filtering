Okay, here's the German translation, keeping the structure, removing doubled terms, and using the provided German/English terms where applicable:

# Personenbezogene Daten (PII) - Kernbegriffe

Hier ist eine Liste von Begriffen, die für die Einhaltung der DSGVO relevant sind und vor der Speicherung aus einem Dokument gefiltert werden sollten. Diese Begriffe sind grob kategorisiert und können eine Orientierungshilfe dafür sein, wonach gesucht werden sollte. Diese Liste ist umfassend, erhebt aber keinen Anspruch auf Vollständigkeit. Es ist wichtig, immer den spezifischen Kontext der Daten zu berücksichtigen und Rechtsexperten für Datenschutz zu konsultieren, um die vollständige Einhaltung der DSGVO zu gewährleisten. Die Verwendung dieser Liste als Ausgangspunkt für die Filterung von Dokumenten vor der Speicherung kann das Risiko von DSGVO-Verstößen erheblich reduzieren.

## Allgemeine Übersicht

### Direkte Identifikatoren

*   **Namen:** Vollständige Namen, Vornamen, Nachnamen, Zweitnamen, Aliasnamen, Geburtsnamen, Spitznamen
*   **Adressen:** Wohnadressen, Rechnungsadressen, Lieferadressen, frühere Adressen, E-Mail-Adressen
*   **Kontaktdaten:** Telefonnummern (Mobil, Festnetz, Arbeit), Faxnummern
*   **Identifikationsnummern:** Sozialversicherungsnummern (SSN), nationale Versicherungsnummern (NIN), Passnummern, Führerscheinnummern, Steueridentifikationsnummern (TIN), Mitarbeiternummern, Studentenausweisnummern, Patienten-IDs, Bankkontonummern, Kreditkartennummern
*   **Online-Identifikatoren:** IP-Adressen, MAC-Adressen, Usernames, User-IDs, eindeutige Gerätekennungen (UDIDs), Social-Media-Handles

### Indirekte Identifikatoren (potenziell identifizierend in Kombination mit anderen Daten)

*   **Geburtsdatum:** Vollständiges Geburtsdatum oder in bestimmten Kontexten auch nur das Geburtsjahr
*   **Geburtsort:** Stadt, Bundesland oder Land der Geburt
*   **Geschlecht:** Männlich, weiblich, nicht-binär, andere Geschlechtsidentitäten
*   **Berufsbezeichnung/Position:** Spezifische Berufsbezeichnungen, insbesondere wenn sie innerhalb einer Organisation einzigartig sind
*   **Arbeitgeber/Firma:** Name des Unternehmens, für das eine Person arbeitet
*   **Gehalt/Einkommen:** Angaben zum Verdienst einer Person
*   **Familienstand:** Ledig, verheiratet, geschieden, verwitwet usw.
*   **Bildung:** Abschlüsse, besuchte Schulen, Qualifikationen
*   **Fahrzeug-Identifikationsnummer (VIN)**

### Sensible personenbezogene Daten (besondere Kategorien nach DSGVO)

*   **Rassische oder ethnische Herkunft:** Informationen über die Rasse, Ethnie oder Nationalität einer Person.
*   **Politische Meinungen:** Zugehörigkeit zu politischen Parteien, politische Überzeugungen, Abstimmungsverhalten.
*   **Religiöse oder weltanschauliche Überzeugungen:** Informationen über die Religion, den Glauben oder die weltanschaulichen Überzeugungen einer Person.
*   **Gewerkschaftszugehörigkeit:** Mitgliedschaft in einer Gewerkschaft oder einem Berufsverband.
*   **Genetische Daten:** Informationen, die aus Gentests gewonnen wurden.
*   **Biometrische Daten (zur Identifizierung verwendet):** Fingerabdrücke, Gesichtserkennungsdaten, Iris-Scans, Stimmaufnahmen, die zur Identifizierung verwendet werden.
*   **Gesundheitsdaten:** Krankengeschichte, Diagnosen, Behandlungen, Medikamente, Behinderungen, Informationen zur psychischen Gesundheit.
*   **Sexualleben oder sexuelle Orientierung:** Informationen über die sexuellen Vorlieben oder Aktivitäten einer Person.

### Andere potenziell sensible Informationen

*   **Strafrechtliche Verurteilungen und Straftaten:** Informationen über das Strafregister einer Person.
*   **Finanzinformationen:** (über Kontonummern hinaus) Details über die finanzielle Situation, die Kredithistorie und die Schulden einer Person.
*   **Standortdaten:** GPS-Koordinaten, Standortverfolgungsdaten, Reiseverlauf.
*   **Kommunikationsdaten:** Inhalt von E-Mails, Nachrichten, Telefonanrufen (nicht nur die Metadaten).
*   **Fotos und Videos:** Bilder oder Videos, die Personen identifizieren können.
*   **Verhaltensdaten:** Informationen über das Online-Verhalten einer Person, den Browserverlauf, Präferenzen und Interessen, die aus Online-Aktivitäten abgeleitet werden.

### Kontextspezifische sensible Informationen

*   **Mitarbeiterbeurteilungen:** Informationen über die Leistung, Bewertungen und Disziplinarmaßnahmen eines Mitarbeiters.
*   **Kundendienstnotizen:** Notizen, die persönliche Meinungen über einen Kunden oder sein Verhalten enthalten könnten.
*   **Umfrageantworten:** Je nach Art der Umfrage können die Antworten sensible Informationen preisgeben.

### Wichtige Überlegungen

*   **Pseudonymisierung vs. Anonymisierung:** Verstehen Sie den Unterschied. Pseudonymisierung ersetzt identifizierende Informationen durch Pseudonyme, ermöglicht aber dennoch eine Re-Identifizierung. Anonymisierung entfernt Identifikatoren irreversibel, so dass eine Re-Identifizierung unmöglich ist.
*   **Datensparsamkeit:** Erheben und speichern Sie nur die Mindestmenge an personenbezogenen Daten, die für den jeweiligen Zweck erforderlich ist.
*   **Kontext ist entscheidend:** Die Sensibilität von Daten hängt oft vom Kontext ab. Beispielsweise ist eine Berufsbezeichnung in einem öffentlichen Verzeichnis möglicherweise nicht sensibel, könnte es aber in internen Firmendokumenten sein.
*   **Rechtsgrundlage für die Verarbeitung:** Stellen Sie sicher, dass Sie eine rechtmäßige Grundlage für die Verarbeitung aller personenbezogenen Daten haben, die Sie nach der Filterung aufbewahren.

## Spezifische Begriffe für die Filterung nach §9 DSGVO

### Direkte Begriffe - Rasse, Ethnizität, Nationalität

*   **Rasse (Race):**  Aufgrund der Verbindung zur Nazi-Ideologie ist "Rasse" im Deutschen ein hochproblematischer Begriff. **Er sollte generell vermieden und immer herausgefiltert werden.** Es gibt keinen perfekten, universell akzeptierten Ersatz, was diesen Bereich komplex macht.
*   **Ethnische Herkunft (Ethnic Origin):** Dies ist der aktuell bevorzugte und neutralere Begriff, der in offiziellen Kontexten verwendet wird.
*   **Volkszugehörigkeit (Ethnic/National Affiliation):** Ein weiterer Begriff, der sich auf Ethnizität oder Nationalität beziehen kann, aber je nach Kontext auch historisch belastet sein kann.
*   **Nationalität (Nationality):** Bezieht sich auf die Staatsbürgerschaft und ist oft ein Pflichtfeld in Formularen. Obwohl weniger sensibel als "Rasse," kann es dennoch dazu beitragen, die Herkunft einer Person zu identifizieren, und sollte herausgefiltert werden, wenn es nicht gesetzlich vorgeschrieben ist.
*   **Staatsangehörigkeit (Citizenship):** Ähnlich wie "Nationalität" bezieht es sich auf das Land der Staatsbürgerschaft.
*   **Herkunft (Origin):** Ein allgemeinerer Begriff, der sich auf die geografische Herkunft, die Abstammung oder den ethnischen Hintergrund beziehen kann.
*   **Abstammung (Descent/Ancestry):** Bezieht sich auf die Abstammung oder Ahnenreihe.

### Spezifische ethnische Gruppen und Herkünfte

Hier sind einige Beispiele, aber beachten Sie, dass sich Empfindlichkeiten und bevorzugte Terminologien ändern können:

*   **Allgemeine Regionen/Kontinente:**
    *   Afrikanisch (African)
    *   Asiatisch (Asian)
    *   Europäisch (European)
    *   Nordamerikanisch (North American)
    *   Südamerikanisch (South American)
    *   Lateinamerikanisch (Latin American)
    *   Australisch (Australian)
*   **Länder/Nationalitäten (Beispiele - Diese Liste muss in der Praxis umfangreich sein):**
    *   Deutsch (German)
    *   Türkisch (Turkish)
    *   Italienisch (Italian)
    *   Griechisch (Greek)
    *   Polnisch (Polish)
    *   Russisch (Russian)
    *   Arabisch (Arabic) - Kann sich auch auf die Sprache beziehen.
    *   Chinesisch (Chinese)
    *   Japanisch (Japanese)
    *   Koreanisch (Korean)
    *   Indisch (Indian)
    *   Brasilianisch (Brazilian)
    *   Mexikanisch (Mexican)
*   **Spezifische ethnische Gruppen (Beispiele - Sensibel und erfordert sorgfältige Überlegung):**
    *   Sinti und Roma (Sinti and Roma) - **Wichtig:** Immer den vollen Begriff "Sinti und Roma" verwenden, da "Roma" allein oft als Oberbegriff angesehen wird und Gruppen einschließen könnte, die sich nicht als solche identifizieren. Niemals veraltete, abwertende Begriffe wie "Zigeuner" verwenden.
    *   Kurdisch (Kurdish)
    *   Jüdisch (Jewish) - Bezieht sich auch auf die Religion.
    *   Slawisch (Slavic)
    *   Baskisch (Basque)
*   **Begriffe für "Ausländer" und verwandte Wörter (Sehr sensibel und oft diskriminierend):**
    *   Ausländer (Foreigner) - Obwohl ein gebräuchlicher Begriff, kann er als ausgrenzend empfunden werden.
    *   Ausländisch (Foreign)
    *   Migrationshintergrund (Migration Background) - Ein neutralerer Begriff, der verwendet wird, um Personen zu beschreiben, die nach Deutschland eingewandert sind oder deren Eltern eingewandert sind.
    *   Nicht-deutsch (Non-German)

### Adjektive und beschreibende Begriffe

Achten Sie auf Adjektive, die indirekt die Herkunft verraten könnten:

*   **Schwarz (Black):** Kann sich auf die Hautfarbe beziehen.
*   **Weiß (White):** Kann sich auf die Hautfarbe beziehen.
*   **Braun (Brown):** Kann sich auf die Hautfarbe beziehen.
*   **Südländisch (Southern/Mediterranean):** Wird oft stereotyp verwendet, um Menschen aus Südeuropa zu beschreiben.
*   **Exotisch (Exotic):** Problematisch aufgrund seiner kolonialen Konnotationen und sollte vermieden werden.

### Politische Parteien

*   **Großparteien (und ihre Abkürzungen):**
    *   **CDU:** Christlich Demokratische Union Deutschlands
    *   **CSU:** Christlich-Soziale Union in Bayern (nur in Bayern aktiv, während die CDU im Rest Deutschlands aktiv ist)
    *   **SPD:** Sozialdemokratische Partei Deutschlands
    *   **Bündnis 90/Die Grünen:** (oft zu "Die Grünen" oder nur "Grüne" verkürzt)
    *   **FDP:** Freie Demokratische Partei
    *   **Die Linke:** (oft nur "Linke")
    *   **AfD:** Alternative für Deutschland
*   **Andere/Kleinere Parteien (Beispiele):**
    *   **NPD:** Nationaldemokratische Partei Deutschlands (rechtsextrem, jetzt "Die Heimat")
    *   **Die PARTEI:** (Satirepartei)
    *   **Piratenpartei Deutschland**
    *   **Freie Wähler:** (eher ein Verband als eine Partei, regional unterschiedlich)
    *   **ÖDP:** Ökologisch-Demokratische Partei
    *   **Tierschutzpartei**
    *   **Volt Deutschland:** (paneuropäische Partei)
    *   **Die Basis:** Basisdemokratische Partei Deutschland

### Politische Überzeugungen und Ideologien

*   **Allgemeine Begriffe:**
    *   **links**
    *   **rechts**
    *   **liberal**
    *   **konservativ**
    *   **sozialistisch**
    *   **kommunistisch**
    *   **sozialdemokratisch**
    *   **grün** (ökologisch)
    *   **nationalistisch**
    *   **rechtsextrem**
    *   **linksextrem**
    *   **faschistisch**
    *   **anarchistisch**
    *   **feministisch**
    *   **christdemokratisch**
    *   **christsozial**
    *   **neoliberal**
    *   **libertär**
    *   **rechtspopulistisch**
    *   **linkspopulistisch**

### Begriffe im Zusammenhang mit Abstimmung/Wahl

*   **Allgemeine Begriffe:**
    *   **Wahl**
    *   **Abstimmung**
    *   **wählen**
    *   **Wähler**
    *   **Wählerin**
    *   **Stimme**
    *   **Stimmzettel**
    *   **Briefwahl**
    *   **Urnenwahl**
    *   **Wahllokal**
    *   **Wahlbeteiligung**
    *   **Wahlkreis**
    *   **Erststimme** (für einen Direktkandidaten)
    *   **Zweitstimme** (für eine Parteiliste)
*   **Begriffe, die auf eine politische Präferenz hinweisen können:**
    *   **hat gewählt** (könnte gefolgt von einem Parteinamen sein)
    *   **stimmte für** (könnte gefolgt von einem Parteinamen sein)
    *   **unterstützt** (könnte gefolgt von einem Parteinamen sein)
    *   **Mitglied** (könnte gefolgt von einem Parteinamen sein)
    *   **Anhänger** (könnte gefolgt von einem Parteinamen sein)
    *   **Sympathisant** (könnte gefolgt von einem Parteinamen sein)

### Hauptreligionen & Konfessionen

*   **Christentum**
    *   **Katholizismus**
        *   **Römisch-katholisch**
    *   **Protestantismus**
        *   **Evangelisch** (umfasst oft **Lutherisch** und **Reformiert**)
        *   **Evangelisch-lutherisch**
        *   **Evangelisch-reformiert**
        *   **Freikirche** (z.B. **Baptisten**, **Methodisten**, **Pfingstbewegung**, **Adventisten**)
    *   **Orthodox**
        *   **Griechisch-Orthodox**
        *   **Russisch-Orthodox**
        *   **Serbisch-Orthodox**
*   **Islam**
    *   **Sunnitisch**
    *   **Schiitisch**
    *   **Aleviten**
    *   **Sufismus** (mystische Strömung)
*   **Judentum**
    *   **Orthodoxes Judentum**
    *   **Konservatives Judentum**
    *   **Liberales Judentum**
*   **Buddhismus**
    *   **Theravada**
    *   **Mahayana**
    *   **Vajrayana**
        *   **Tibetischer Buddhismus**
    *   **Zen**
*   **Hinduismus**
*   **Bahaitum**
*   **Jesidentum**
*   **Zeugen Jehovas**
*   **Neuapostolische Kirche**

### Religiöse Titel & Rollen

*   **Pfarrer/Pfarrerin** (evangelisch)
*   **Priester** (katholisch)
*   **Diakon/Diakonin**
*   **Bischof/Bischöfin**
*   **Papst**
*   **Imam**
*   **Rabbiner/Rabbinerin**
*   **Mönch/Nonne**

### Philosophische Überzeugungen & Weltanschauungen

*   **Atheismus**
*   **Agnostizismus**
*   **Humanismus**
    *   **Säkularer Humanismus**
*   **Existenzialismus**
*   **Nihilismus**
*   **Spiritualität**
*   **Esoterik**
*   **Anthroposophie**
*   **Konfuzianismus**
*   **Neopaganismus**

### Andere verwandte Begriffe

*   **Kirche**
*   **Moschee**
*   **Synagoge**
*   **Tempel**
*   **Kloster**
*   **Gemeinde**
*   **Glaubensgemeinschaft**
*   **Weltanschauung**
*   **Sekte** (Begriff kann kontrovers sein)
*   **Glaube**
*   **Religion**
*   **Philosophie**
*   **Ethik**
*   **Moral**
*   **Konfessionslos**
*   **Religionszugehörigkeit**
*   **Heide** (historisch, manchmal abwertend)

### Allgemeine Begriffe für Gewerkschaften

*   **Gewerkschaft:** (Trade Union/Labor Union)
*   **Gewerkschaften:** (Trade Unions/Labor Unions) - Plural
*   **Arbeitnehmerverband:** (Employee Association)
*   **Arbeitnehmerverbände:** (Employee Associations) - Plural
*   **Berufsverband:** (Professional Association)
*   **Berufsverbände:** (Professional Associations) - Plural
*   **Mitgliedschaft:** (Membership)
*   **Mitglied:** (Member)
*   **Gewerkschaftsmitglied:** (Trade Union Member)
*   **Gewerkschaftsmitgliedschaft:** (Trade Union Membership)

### Namen großer deutscher Gewerkschaften (Names of Major German Trade Unions)

*   **DGB (Deutscher Gewerkschaftsbund):** (German Trade Union Confederation)
*   **ver.di (Vereinte Dienstleistungsgewerkschaft):** (United Services Trade Union)
*   **IG Metall (Industriegewerkschaft Metall):** (Industrial Union of Metalworkers)
*   **IG BCE (Industriegewerkschaft Bergbau, Chemie, Energie):** (Industrial Union for Mining, Chemistry, and Energy)
*   **GEW (Gewerkschaft Erziehung und Wissenschaft):** (Education and Science Workers' Union)
*   **GdP (Gewerkschaft der Polizei):** (Police Union)
*   **EVG (Eisenbahn- und Verkehrsgewerkschaft):** (Rail and Transport Workers' Union)
*   **NGG (Gewerkschaft Nahrung-Genuss-Gaststätten):** (Food, Beverages, and Catering Union)
*   **IG BAU (Industriegewerkschaft Bauen-Agrar-Umwelt):** (Construction, Agriculture, and Environment Union)

### Namen von Berufsverbänden

*   **Bundesärztekammer:** (German Medical Association)
*   **Deutscher Anwaltverein (DAV):** (German Bar Association)
*   **VDI (Verein Deutscher Ingenieure):** (Association of German Engineers)
*   **Steuerberaterkammer:** (Chamber of Tax Advisors) - Hinweis: Diese sind oft regional (z. B. Steuerberaterkammer München).
*   **Bundesrechtsanwaltskammer:** (Federal Chamber of Lawyers)

### Kontextbezogene Begriffe

*   **Tarifverhandlungen:** (Collective Bargaining Negotiations)
*   **Betriebsrat:** (Works Council)
*   **Mitgliedsbeitrag:** (Membership fee/dues)
*   **Gewerkschaftsbeitrag:** (Union dues)
*   **Streik:** (Strike)
   
### Allgemeine Begriffe der Genetik

*   **Genetische Daten**
*   **Genom**
*   **DNA (Desoxyribonukleinsäure)**
*   **RNA (Ribonukleinsäure)**
*   **Gen**
*   **Chromosom**
*   **Allel**
*   **Genotyp**
*   **Phänotyp**
*   **Mutation**
*   **Polymorphismus**
*   **Sequenzierung**
*   **Genexpression**
*   **Vererbung**
*   **Erblich**
*   **Genetischer Code**

### Begriffe im Zusammenhang mit Gentests

*   **Gentest**
*   **Genetische Untersuchung**
*   **Biobank**
*   **Genanalyse**
*   **DNA-Test**
*   **DNA-Analyse**
*   **Genetische Diagnostik**
*   **Pränataldiagnostik**
*   **Neugeborenenscreening**
*   **Trägerstatus**
*   **Abstammungsanalyse**
*   **Vaterschaftstest**
*   **Mutterschaftstest**
*   **Befund**
*   **Probe**
*   **Labor**
*   **Humangenetisches Labor**
*   **Facharzt für Humangenetik**
*   **Einwilligungserklärung**

### Begriffe im Zusammenhang mit genetischen Krankheiten und Störungen

*   **Genetische Krankheit**
*   **Erbkrankheit**
*   **Genetische Störung**
*   **Genetische Prädisposition**
*   **Monogenetische Erkrankung**
*   **Polygenetische Erkrankung**
*   **Chromosomenanomalie**
*   **Trisomie 21 / Down-Syndrom**
*   **Mukoviszidose**
*   **Chorea Huntington**
*   **Duchenne-Muskeldystrophie**
*   **Sichelzellenanämie**
*   **BRCA1/BRCA2 (Brustkrebsgen)**
*   **Familiäre Hypercholesterinämie**

### Begriffe im Zusammenhang mit genetischen Markern und Varianten

*   **Einzelnukleotid-Polymorphismus (SNP)**
*   **Variante**
*   **Pathogene Variante**
*   **Wahrscheinlich pathogene Variante**
*   **Variante unklarer Signifikanz (VUS)**
*   **Benigne Variante**
*   **Wahrscheinlich benigne Variante**

## Wichtige Hinweise

*   **"Rasse" ist ein Warnsignal:** Der Begriff "Rasse" sollte aufgrund seiner zutiefst problematischen Geschichte in Deutschland immer gekennzeichnet und wahrscheinlich herausgefiltert werden.
*   **Kontext ist entscheidend:** Die Sensibilität dieser Begriffe hängt stark vom Kontext ab. Beispielsweise ist "Türkisch" in der Beschreibung eines Sprachkurses notwendig, sollte aber aus einer Mitarbeiterbeurteilung herausgefiltert werden.
*   **Abwertende Begriffe:** Sie benötigen eine Liste von Beleidigungen und abwertenden Begriffen, die sich auf verschiedene Ethnien und Nationalitäten beziehen, um effektiv zu filtern. Diese Liste muss regelmäßig aktualisiert werden.
*   **Abkürzungen und Akronyme:** Achten Sie auf Abkürzungen und Akronyme, insbesondere bei politischen Parteien. Viele deutsche Organisationen werden üblicherweise mit ihren Akronymen bezeichnet (z.B. ver.di, IG Metall, DGB).
*   **Negation:** Achten Sie auf Verneinungen. "Nicht links" gibt immer noch Informationen über politische Ansichten preis.
*   **Indirekte Verweise:** Menschen könnten politische Meinungen äußern, ohne Parteien explizit zu nennen, z.B. "Ich unterstütze die Energiewende" könnte Unterstützung für die Grünen implizieren.
*   **Regionale Unterschiede:** Einige Berufsverbände könnten in verschiedenen Bundesländern unterschiedliche Namen haben..
