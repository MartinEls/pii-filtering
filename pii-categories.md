# Personally Identifiable Information (PII) - Core Terms

*   **Direct Identifiers:**
    *   **Names:** Full names, first names, last names, middle names, aliases, maiden names, nicknames
    *   **Addresses:** Home addresses, billing addresses, shipping addresses, previous addresses, email addresses
    *   **Contact Details:** Phone numbers (mobile, home, work), fax numbers
    *   **Identification Numbers:** Social Security numbers (SSN), National Insurance numbers (NIN), passport numbers, driver's license numbers, tax identification numbers (TIN), employee IDs, student IDs, patient IDs, bank account numbers, credit card numbers
    *   **Online Identifiers:** IP addresses, MAC addresses, Usernames, User IDs, unique device identifiers (UDIDs), social media handles
*   **Indirect Identifiers (Potentially identifying when combined with other data):**
    *   **Date of Birth:** Full date of birth, or even just year of birth in certain contexts
    *   **Place of Birth:** City, state, or country of birth
    *   **Gender:** Male, Female, Non-binary, other gender identities
    *   **Job Title/Position:**  Specific job titles, particularly if unique within an organization
    *   **Employer/Company:** Name of the company a person works for
    *   **Salary/Income:** Details about a person's earnings
    *   **Marital Status:** Single, married, divorced, widowed, etc.
    *   **Education:** Degrees, schools attended, qualifications
    *   **Vehicle Identification Number (VIN)**

**II. Sensitive Personal Data (Special Categories under GDPR)**

*   **Racial or Ethnic Origin:** Information about a person's race, ethnicity, or nationality.
*   **Political Opinions:**  Affiliation with political parties, political beliefs, voting records.
*   **Religious or Philosophical Beliefs:** Information about a person's religion, faith, or philosophical beliefs.
*   **Trade Union Membership:** Membership in a labor union or professional association.
*   **Genetic Data:** Information derived from genetic testing.
*   **Biometric Data (used for identification):** Fingerprints, facial recognition data, iris scans, voice recordings used for identification.
*   **Health Data:** Medical history, diagnoses, treatments, medications, disabilities, mental health information.
*   **Sex Life or Sexual Orientation:** Information about a person's sexual preferences or activities.

**III. Other Potentially Sensitive Information**

*   **Criminal Convictions and Offences:** Information about a person's criminal record.
*   **Financial Information:** (beyond account numbers) Details about a person's financial status, credit history, debts.
*   **Location Data:** GPS coordinates, location tracking data, travel history.
*   **Communication Data:** Content of emails, messages, phone calls (not just the metadata).
*   **Photographs and Videos:**  Images or videos that can identify individuals.
*   **Behavioral Data:** Information about a person's online behavior, browsing history, preferences, interests derived from online activity.

**IV. Context-Specific Sensitive Information**

*   **Employee Performance Reviews:** Information about an employee's performance, evaluations, disciplinary actions.
*   **Customer Service Notes:** Notes that might contain personal opinions about a customer or their behavior.
*   **Survey Responses:** Depending on the nature of the survey, responses might reveal sensitive information.

**Important Considerations:**

*   **Pseudonymization vs. Anonymization:** Understand the difference. Pseudonymization replaces identifying information with pseudonyms but still allows for re-identification. Anonymization irreversibly removes identifiers, making re-identification impossible.
*   **Data Minimization:** Collect and store only the minimum amount of personal data necessary for the specific purpose.
*   **Context is Key:** The sensitivity of data often depends on the context. For example, a job title might not be sensitive in a public directory but could be sensitive within internal company documents.
*   **Legal Basis for Processing:** Ensure you have a lawful basis for processing any personal data you retain after filtering.

This list is comprehensive but might not be exhaustive. It's crucial to always consider the specific context of the data and consult with legal professionals specializing in data privacy to ensure full GDPR compliance. Using this list as a starting point for filtering documents before storage can significantly reduce the risk of GDPR violations.

## Direct Terms - Race, Ethnicity, Nationality

*   **Rasse (Race):** While used in some older contexts, "Rasse" is a highly problematic term in German due to its association with Nazi ideology. **It should generally be avoided and always filtered out.** There isn't a perfect, universally accepted replacement, which makes this area complex.
*   **Ethnische Herkunft (Ethnic Origin):** This is the currently preferred and more neutral term used in official contexts.
*   **Volkszugehörigkeit (Ethnic/National Affiliation):** Another term that can refer to ethnicity or nationality, though it can also carry historical baggage depending on context.
*   **Nationalität (Nationality):** This refers to citizenship and is often a required field in forms. While less sensitive than "Rasse," it can still contribute to identifying someone's origin and should be filtered out when not legally required.
*   **Staatsangehörigkeit (Citizenship):** Similar to "Nationalität," it refers to the country of citizenship.
*   **Herkunft (Origin):** A more general term that can refer to geographic origin, ancestry, or ethnic background.
*   **Abstammung (Descent/Ancestry):**  Refers to lineage or ancestry.

## Specific Ethnic Groups and Origins

This is where it gets very specific, and you'll need a comprehensive list for thorough filtering. Here are some examples, but be aware that sensitivities and preferred terminology can change:

*   **General Regions/Continents:**
    *   Afrikanisch (African)
    *   Asiatisch (Asian)
    *   Europäisch (European)
    *   Nordamerikanisch (North American)
    *   Südamerikanisch (South American)
    *   Lateinamerikanisch (Latin American)
    *   Australisch (Australian)
*   **Countries/Nationalities (Examples - This list needs to be extensive in practice):**
    *   Deutsch (German)
    *   Türkisch (Turkish)
    *   Italienisch (Italian)
    *   Griechisch (Greek)
    *   Polnisch (Polish)
    *   Russisch (Russian)
    *   Arabisch (Arabic) - Can also refer to language.
    *   Chinesisch (Chinese)
    *   Japanisch (Japanese)
    *   Koreanisch (Korean)
    *   Indisch (Indian)
    *   Brasilianisch (Brazilian)
    *   Mexikanisch (Mexican)
*   **Specific Ethnic Groups (Examples - Sensitive and requires careful consideration):**
    *   Sinti und Roma (Sinti and Roma) - **Important:** Always use the full term "Sinti und Roma," as "Roma" alone is often considered an umbrella term and could include groups that don't identify as such. Never use outdated, derogatory terms like "Zigeuner".
    *   Kurdisch (Kurdish)
    *   Jüdisch (Jewish) - Also refers to religion.
    *   Slawisch (Slavic)
    *   Baskisch (Basque)
*   **Terms for "Foreigner" and related words (Highly sensitive and often discriminatory):**
    *   Ausländer (Foreigner) - While a common term, it can be perceived as exclusionary.
    *   Ausländisch (Foreign)
    *   Migrationshintergrund (Migration Background) - A more neutral term used to describe people who have immigrated to Germany or whose parents have.
    *   Nicht-deutsch (Non-German)

## Adjectives and Descriptive Terms

Be mindful of adjectives that might indirectly reveal origin:

*   **Schwarz (Black):** Can refer to skin color.
*   **Weiß (White):** Can refer to skin color.
*   **Braun (Brown):** Can refer to skin color.
*   **Südländisch (Southern/Mediterranean):** Often used in a stereotypical way to describe people from Southern Europe.
*   **Exotisch (Exotic):**  Problematic due to its colonial connotations and should be avoided.

**Important Considerations**

*   **"Rasse" is a Red Flag:**  The term "Rasse" should always be flagged and likely filtered due to its deeply problematic history in Germany.
*   **Context is Crucial:**  The sensitivity of these terms depends heavily on context. For example, "Turkish" is necessary in a language course description but should be filtered out of an employee performance review.
*   **Indirect Identifiers:** Be aware that seemingly innocuous information, when combined, can reveal someone's origin (e.g., last name + city of birth).
*   **Derogatory Terms:** You'll need a list of slurs and derogatory terms related to different ethnicities and nationalities for effective filtering. This list needs regular updating.
*   **Legal Advice:**  Consult with a legal professional specializing in German data privacy law to ensure your filtering process is compliant with the GDPR and other relevant regulations, such as the *Allgemeines Gleichbehandlungsgesetz* (AGG - General Equal Treatment Act).

**In summary, filtering for racial or ethnic origin in German requires a nuanced approach due to the sensitive history and complex language surrounding these topics. Use this list as a starting point, but be prepared to expand it significantly and refine your filtering process based on legal advice and evolving best practices.**

## Political Parties (Politische Parteien)

*   **Major Parties (and their abbreviations):**
    *   **CDU:** Christlich Demokratische Union Deutschlands (Christian Democratic Union of Germany)
    *   **CSU:** Christlich-Soziale Union in Bayern (Christian Social Union in Bavaria) - Operates only in Bavaria, while CDU is in the rest of Germany
    *   **SPD:** Sozialdemokratische Partei Deutschlands (Social Democratic Party of Germany)
    *   **Bündnis 90/Die Grünen:** (Alliance 90/The Greens) - Often shortened to "Die Grünen" or just "Grüne"
    *   **FDP:** Freie Demokratische Partei (Free Democratic Party)
    *   **Die Linke:** (The Left) - Often just "Linke"
    *   **AfD:** Alternative für Deutschland (Alternative for Germany)
*   **Other/Smaller Parties (Examples):**
    *   **NPD:** Nationaldemokratische Partei Deutschlands (National Democratic Party of Germany) - Far-right, now called "Die Heimat"
    *   **Die PARTEI:** (The PARTY) - Satirical party
    *   **Piratenpartei Deutschland:** (Pirate Party Germany)
    *   **Freie Wähler:** (Free Voters) - More of an association than a party, varies regionally
    *   **ÖDP:** Ökologisch-Demokratische Partei (Ecological Democratic Party)
    *   **Tierschutzpartei:** (Animal Protection Party)
    *   **Volt Deutschland:** (Volt Germany) - Pan-European party
    *   **Die Basis** Basisdemokratische Partei Deutschland

## Political Beliefs and Ideologies (Politische Überzeugungen und Ideologien)

*   **General Terms:**
    *   **links:** (left-wing)
    *   **rechts:** (right-wing)
    *   **liberal:** (liberal)
    *   **konservativ:** (conservative)
    *   **sozialistisch:** (socialist)
    *   **kommunistisch:** (communist)
    *   **sozialdemokratisch:** (social democratic)
    *   **grün:** (green - ecological)
    *   **nationalistisch:** (nationalist)
    *   **rechtsextrem:** (far-right/right-wing extremist)
    *   **linksextrem:** (far-left/left-wing extremist)
    *   **faschistisch:** (fascist)
    *   **anarchistisch:** (anarchist)
    *   **feministisch:** (feminist)
    *   **christdemokratisch:** (Christian democratic)
    *   **christsozial:** (Christian social)
    *   **neoliberal:** (neoliberal)
    *   **libertär:** (libertarian)
    *   **rechtspopulistisch:** (right-wing populist)
    *   **linkspopulistisch:** (left-wing populist)

## Terms Related to Voting (Abstimmung/Wahl)

*   **General Terms:**
    *   **Wahl:** (election/vote)
    *   **Abstimmung:** (vote/ballot)
    *   **wählen:** (to vote)
    *   **Wähler:** (voter)
    *   **Wählerin:** (female voter)
    *   **Stimme:** (vote/voice)
    *   **Stimmzettel:** (ballot paper)
    *   **Briefwahl:** (postal voting/vote by mail)
    *   **Urnenwahl:** (ballot box voting)
    *   **Wahllokal:** (polling station)
    *   **Wahlbeteiligung:** (voter turnout)
    *   **Wahlkreis:** (constituency/electoral district)
    *   **Erststimme:** (first vote - for a direct candidate)
    *   **Zweitstimme:** (second vote - for a party list)
*   **Terms that may indicate political preference:**
    *   **hat gewählt:** (voted for - could be followed by a party name)
    *   **stimmte für:** (voted for - could be followed by a party name)
    *   **unterstützt:** (supports - could be followed by a party name)
    *   **Mitglied:** (member - could be followed by a party name)
    *   **Anhänger:** (supporter - could be followed by a party name)
    *   **Sympathisant:** (sympathizer - could be followed by a party name)

## Important Considerations

*   **Context is crucial:**  The word "Stimme" (voice) can be harmless or sensitive depending on the context.  "Stimme" in a musical context is different from "Stimme" in a political context.
*   **Abbreviations:** Be aware of abbreviations and acronyms, especially for political parties.
*   **Negation:** Watch out for negations. "Nicht links" (not left-wing) still reveals information about political views.
*   **Indirect References:** People might express political opinions without explicitly naming parties, e.g., "Ich unterstütze die Energiewende" (I support the energy transition) could imply support for the Green party. You must train your filter to recognize those instances.

This list provides a solid starting point for filtering German terms related to political opinions. Remember to combine this with other data filtering strategies and to regularly update your list as new parties and political terms emerge. As always, consult with legal experts to ensure compliance with GDPR and other relevant data privacy regulations.

## Major Religions & Denominations

*   **Christentum** (Christianity)
    *   **Katholizismus** (Catholicism)
        *   **Römisch-katholisch** (Roman Catholic)
    *   **Protestantismus** (Protestantism)
        *   **Evangelisch** (Protestant - often refers to Lutheran/Reformed churches in Germany)
        *   **Lutherisch** (Lutheran)
        *   **Reformiert** (Reformed/Calvinist)
        *   **Evangelisch-lutherisch** (Evangelical Lutheran)
        *   **Evangelisch-reformiert** (Evangelical Reformed)
        *   **Freikirche** (Free Church - can include various Protestant denominations)
        *   **Baptisten** (Baptists)
        *   **Methodisten** (Methodists)
        *   **Pfingstbewegung** (Pentecostalism)
        *   **Adventisten** (Adventists)
    *   **Orthodox** (Orthodox)
        *   **Griechisch-Orthodox** (Greek Orthodox)
        *   **Russisch-Orthodox** (Russian Orthodox)
        *   **Serbisch-Orthodox** (Serbian Orthodox)
*   **Islam** (Islam)
    *   **Sunnitisch** (Sunni)
    *   **Schiitisch** (Shia)
    *   **Aleviten** (Alevis - considered by some a separate faith, by others a branch of Shia Islam)
    *   **Sufismus** (Sufism - more of a mystical dimension within Islam than a separate denomination)
*   **Judentum** (Judaism)
    *   **Orthodoxes Judentum** (Orthodox Judaism)
    *   **Konservatives Judentum** (Conservative Judaism)
    *   **Liberales Judentum** (Reform/Liberal Judaism)
*   **Buddhismus** (Buddhism)
    *   **Theravada-Buddhismus** (Theravada Buddhism)
    *   **Mahayana-Buddhismus** (Mahayana Buddhism)
    *   **Vajrayana-Buddhismus** (Vajrayana Buddhism)
        *   **Tibetischer Buddhismus** (Tibetan Buddhism)
    *   **Zen-Buddhismus** (Zen Buddhism)
*   **Hinduismus** (Hinduism)
*   **Bahaitum** (Baha'i Faith)
*   **Jesidentum** (Yazidism)

**II. Religious Titles & Roles:**

*   **Pfarrer/Pfarrerin** (Pastor/Priest - generally Protestant)
*   **Priester** (Priest - generally Catholic)
*   **Diakon/Diakonin** (Deacon)
*   **Bischof/Bischöfin** (Bishop)
*   **Papst** (Pope)
*   **Imam** (Imam)
*   **Rabbiner/Rabbinerin** (Rabbi)
*   **Mönch/Nonne** (Monk/Nun)

**III. Philosophical Beliefs & Worldviews:**

*   **Atheismus** (Atheism)
*   **Agnostizismus** (Agnosticism)
*   **Humanismus** (Humanism)
    *   **Säkularer Humanismus** (Secular Humanism)
*   **Existenzialismus** (Existentialism)
*   **Nihilismus** (Nihilism)
*   **Spiritualität** (Spirituality) - This is a broad term and might need context to determine sensitivity.
*   **Esoterik** (Esotericism) - Also broad, covering various beliefs and practices.
*   **Anthroposophie** (Anthroposophy)
*   **Konfuzianismus** (Confucianism) - More prominent as an ethical philosophy

**IV. Other Related Terms:**

*   **Kirche** (Church)
*   **Moschee** (Mosque)
*   **Synagoge** (Synagogue)
*   **Tempel** (Temple)
*   **Kloster** (Monastery/Convent)
*   **Gemeinde** (Congregation/Community)
*   **Glaubensgemeinschaft** (Religious Community)
*   **Weltanschauung** (Worldview)
*   **Sekte** (Sect/Cult) - This term can be controversial and should be handled with care.
*   **Glaube** (Faith/Belief)
*   **Religion** (Religion)
*   **Philosophie** (Philosophy)
*   **Ethik** (Ethics)
*   **Moral** (Morals)
*   **Konfessionslos** (Without religious affiliation)
*   **Religionszugehörigkeit** (Religious Affiliation)
*   **Heide** (Heathen/Pagan, historically used, sometimes considered derogatory)
*   **Neopaganismus** (Neopaganism)
*   **Zeugen Jehovas** (Jehovah's Witnesses)
*   **Neuapostolische Kirche** (New Apostolic Church)
**V.  Important Considerations:**

*   **Context:** As always, context is vital. Some of these terms might be harmless in certain contexts but sensitive in others.
*   **Adjectives:** Be mindful of adjectives that might indicate religious affiliation, e.g., "jüdisch" (Jewish), "muslimisch" (Muslim), "christlich" (Christian), etc.
*   **Derogatory Terms:** This list focuses on neutral or commonly accepted terms. Be aware that derogatory terms for religious groups exist and should also be filtered out.

This list provides a strong starting point for filtering German terms related to religious or philosophical beliefs.  Remember to continuously update your filtering system as new terms and expressions emerge. Consulting with legal professionals specializing in data privacy and GDPR is crucial to ensure full compliance and sensitivity to the nuances of language.

Okay, here are some specific German terms related to Trade Union Membership (Membership in a labor union or professional association) that should be filtered out for GDPR compliance:

## General Terms for Trade Unions

*   **Gewerkschaft:** (Trade Union/Labor Union) - This is the most common and general term.
*   **Gewerkschaften:** (Trade Unions/Labor Unions) - Plural form.
*   **Arbeitnehmerverband:** (Employee Association) - A more general term that can encompass trade unions.
*   **Arbeitnehmerverbände:** (Employee Associations) - Plural form.
*   **Berufsverband:** (Professional Association) - This term is broader and refers to associations representing specific professions.
*   **Berufsverbände:** (Professional Associations) - Plural form.
*   **Mitgliedschaft:** (Membership) - While not specific to unions, the context will usually make it clear.
*   **Mitglied:** (Member)
*   **Gewerkschaftsmitglied:** (Trade Union Member) - Specifically identifies someone as a member of a trade union.
*   **Gewerkschaftsmitgliedschaft:** (Trade Union Membership) -  Specifically identifies the membership.

## Names of Major German Trade Unions (These should definitely be filtered)

*   **DGB (Deutscher Gewerkschaftsbund):** (German Trade Union Confederation) - The largest umbrella organization for trade unions in Germany.
*   **ver.di (Vereinte Dienstleistungsgewerkschaft):** (United Services Trade Union) - One of the largest individual unions, representing workers in various service sectors.
*   **IG Metall (Industriegewerkschaft Metall):** (Industrial Union of Metalworkers) - A very influential union representing workers in the metal and electrical industries.
*   **IG BCE (Industriegewerkschaft Bergbau, Chemie, Energie):** (Industrial Union for Mining, Chemistry, and Energy)
*   **GEW (Gewerkschaft Erziehung und Wissenschaft):** (Education and Science Workers' Union) - Represents teachers and other education professionals.
*   **GdP (Gewerkschaft der Polizei):** (Police Union)
*   **EVG (Eisenbahn- und Verkehrsgewerkschaft):** (Rail and Transport Workers' Union)
*   **NGG (Gewerkschaft Nahrung-Genuss-Gaststätten):** (Food, Beverages, and Catering Union)
*   **IG BAU (Industriegewerkschaft Bauen-Agrar-Umwelt):** (Construction, Agriculture, and Environment Union)

## Names of Professional Associations (Berufsverbände - Filter as needed)

*   **Bundesärztekammer:** (German Medical Association)
*   **Deutscher Anwaltverein (DAV):** (German Bar Association)
*   **VDI (Verein Deutscher Ingenieure):** (Association of German Engineers)
*   **Steuerberaterkammer:** (Chamber of Tax Advisors) - Note that these are often regional (e.g., Steuerberaterkammer München).
*   **Bundesrechtsanwaltskammer:** (Federal Chamber of Lawyers)

## Contextual Terms and Phrases

*   **Tarifverhandlungen:** (Collective Bargaining Negotiations) - Often mentioned in the context of trade unions.
*   **Betriebsrat:** (Works Council) - While not a union, works councils are closely related and often involve union members.
*   **Mitgliedsbeitrag:** (Membership fee/dues)
*   **Gewerkschaftsbeitrag:** (Union dues)
*   **Streik:** (Strike) - Another term closely associated with trade union activity.

**Important Notes:**

*   **Regional Variations:** Some professional associations might have different names in different German states (Bundesländer).
*   **Acronyms:** Be aware of acronyms. Many German organizations are commonly referred to by their acronyms (e.g., ver.di, IG Metall, DGB). Your filtering system should recognize both the full name and the acronym.
*   **Specificity:** While general terms like "Gewerkschaft" are important to filter, be especially vigilant about filtering the specific names of unions and professional associations.
*   **Context is Key:**  A term like "Mitglied" (member) might not be sensitive on its own. However, if it appears in close proximity to a union's name or other related terms, it should be flagged.

By filtering these German terms related to trade union membership and professional associations, you will be taking a significant step toward ensuring GDPR compliance for your documents. Remember to combine this list with other categories of sensitive data and consult with legal professionals specializing in data privacy for the most comprehensive and up-to-date approach.

Okay, here are some specific German terms related to "Genetic Data: Information derived from genetic testing" that you should consider filtering out for GDPR compliance. These terms are categorized for clarity:

**I. General Terms Related to Genetics:**

*   **Genetische Daten:** Genetic data (This is the most important term to filter)
*   **Genom:** Genome
*   **DNA (Desoxyribonukleinsäure):** DNA (Deoxyribonucleic acid)
*   **RNA (Ribonukleinsäure):** RNA (Ribonucleic acid)
*   **Gen:** Gene
*   **Chromosom:** Chromosome
*   **Allel:** Allele
*   **Genotyp:** Genotype
*   **Phänotyp:** Phenotype
*   **Mutation:** Mutation
*   **Polymorphismus:** Polymorphism
*   **Sequenzierung:** Sequencing
*   **Genexpression:** Gene expression
*   **Vererbung:** Inheritance
*   **Erblich:** Hereditary
*   **Genetischer Code:** Genetic code

**II. Terms Related to Genetic Testing:**

*   **Gentest:** Genetic test
*   **Genetische Untersuchung:** Genetic examination
*   **Genanalyse:** Genetic analysis
*   **DNA-Test:** DNA test
*   **DNA-Analyse:** DNA analysis
*   **Genetische Diagnostik:** Genetic diagnostics
*   **Pränataldiagnostik:** Prenatal diagnostics
*   **Neugeborenenscreening:** Newborn screening
*   **Trägerstatus:** Carrier status
*   **Abstammungsanalyse:** Paternity/Maternity testing, Ancestry analysis
*   **Vaterschaftstest:** Paternity test
*   **Mutterschaftstest:** Maternity test
*   **Befund:** Test result, finding
*   **Probe:** Sample (biological sample)
*   **Labor:** Laboratory
*   **Humangenetisches Labor** Human genetics laboratory
*   **Labor für Humangenetik** Laboratory for human genetics
*   **Facharzt für Humangenetik:** Specialist in human genetics (this phrase indicating that a document might contain sensitive info)
*   **Einwilligungserklärung:** Informed consent

**III. Terms Related to Genetic Diseases and Conditions:**

*   **Genetische Krankheit:** Genetic disease
*   **Erbkrankheit:** Hereditary disease
*   **Genetische Störung:** Genetic disorder
*   **Genetische Prädisposition:** Genetic predisposition
*   **Monogenetische Erkrankung:** Monogenic disorder
*   **Polygenetische Erkrankung:** Polygenic disorder
*   **Chromosomenanomalie:** Chromosomal abnormality
*   **Trisomie 21 / Down-Syndrom:** Trisomy 21 / Down Syndrome
*   **Mukoviszidose:** Cystic fibrosis
*   **Chorea Huntington:** Huntington's disease
*   **Duchenne-Muskeldystrophie:** Duchenne muscular dystrophy
*   **Sichelzellenanämie:** Sickle cell anemia
*   **BRCA1/BRCA2 (Brustkrebsgen):** BRCA1/BRCA2 (breast cancer genes)
*   **Familiäre Hypercholesterinämie:** Familial hypercholesterolemia

**IV. Terms Related to Genetic Markers and Variants**

*   **Einzelnukleotid-Polymorphismus (SNP):** Single nucleotide polymorphism (SNP)
*   **Variante:** Variant
*   **Pathogene Variante:** Pathogenic variant
*   **Wahrscheinlich pathogene Variante** Likely pathogenic variant
*   **Variante unklarer Signifikanz (VUS):** Variant of uncertain significance (VUS)
*   **Benigne Variante:** Benign variant
*   **Wahrscheinlich benigne Variante:** Likely benign variant

**V. Other related terms**

*   **Biobank:** Biobank
*   **Forschung:** Research
*   **Genetische Beratung:** Genetic counselling
*   **Datenschutz:** Data protection
*   **Informationelle Selbstbestimmung:** Informational self-determination

**Important Notes:**

*   **Context:** Always consider the context. Some terms might be harmless in one context but sensitive in another.
*   **Combinations:** Be aware of combinations of terms that might indicate genetic data (e.g., "Labor" + "DNA-Analyse").
*   **Abbreviations:** Be aware of common abbreviations like "DNA" for "Desoxyribonukleinsäure."
*   **Proper Nouns:** The names of specific genetic tests, companies, or research projects may also need to be filtered.
*   **Regular Updates:** This list is not exhaustive and needs regular updates as new genetic tests and terminology emerge.

This detailed list of German terms provides a strong foundation for filtering genetic data. However, always consult with legal professionals and experts in data privacy to ensure compliance with GDPR and other applicable regulations in Germany. They can provide the most accurate and up-to-date guidance for your specific needs.
