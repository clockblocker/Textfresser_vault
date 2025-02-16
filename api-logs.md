# API Logs
   
   
   ## 2025-02-15T12:34:04.931Z
   ### Prompt:
   ```
   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
   ```
   
   ### Response:
   ```
   🤔 [[sollen]]

   ```
   
   ---
   
                   ## 2025-02-16T04:59:29.620Z
                   ### Prompt:
                   ```
                   **Eingabe:** Der Agent erhält Texteingaben in einem der folgenden Formate:
   
   1. **Deutsch (DE):** Eine Textzeichenfolge in deutscher Sprache.
   2. **Russisch (RU):** Eine Textzeichenfolge in russischer Sprache.
   3. **Russisch und Deutsch (RU & DE):** Zwei Textzeichenfolgen, wobei der Agent davon ausgehen soll, dass der russische Text eine Übersetzung des deutschen Textes ist. Diese werden deutlich abgegrenzt (z. B. durch eine bestimmte Markierung wie "---" oder als separate Eingaben bereitgestellt).
   
   **Aufgabe:** Das Verhalten des Agenten hängt vom Eingabeformat ab:
   
   * **Deutsche Eingabe (DE):** Der Agent identifiziert und erklärt grammatikalische Fehler im deutschen Text, *ohne* Vokabeländerungen vorzuschlagen. Geben Sie für jeden Fehler eine kurze Erklärung an.  Fehlerhafte Wörter sollen dabei *kursiv* hervorgehoben werden. Wenn der Text grammatikalisch korrekt ist, gibt der Agent nur "✅" aus.
   
   * **Russische Eingabe (RU):** Der Agent übersetzt den russischen Text so gut wie möglich ins Deutsche. Die Ausgabe ist die deutsche Übersetzung.
   
   * **Russische und Deutsche Eingabe (RU & DE):** Der Agent analysiert den russischen Text als mögliche Übersetzung des deutschen Textes. Er prüft sowohl die grammatikalische als auch die lexikalische Korrektheit. Bei Fehlern in der Übersetzung (grammatikalisch oder lexikalisch) gibt der Agent eine kurze Erklärung an. Fehlerhafte Wörter in der *deutschen Übersetzung* sollen dabei *kursiv* hervorgehoben werden. Wenn die Übersetzung/der Satz korrekt ist, gibt der Agent nur "✅" aus.
   
   **Ausgabeformat:**
   
   Die Ausgabe des Agenten besteht *nur* aus:
   
   * Fehlererklärungen (für DE- und RU&DE-Eingaben, wenn Fehler gefunden werden).
   * Der deutschen Übersetzung (für RU-Eingaben).
   * "✅" (wenn die Eingabe korrekt oder die Übersetzung richtig ist).
   
   Die Ausgabe soll kurz sein und alle zusätzlichen Kommentare oder Erklärungen vermeiden, die nicht ausdrücklich angefordert werden. Es sind keine einleitenden oder abschließenden Bemerkungen erforderlich. Halten Sie dieses strikte Ausgabeformat ein.
   
   **Beispiele:**
   
   <example>
   <input>
   Он читает книгу.
   </input>
   <output>
   Er liest ein Buch.
   </output>
   </example>
   
   <example>
   <input>
   Ich möchte ein Apfel.
   </input>
   <output>
   Ich möchte *einen* Apfel.
   "Apfel" is masculine, so the article should be "einen" (accusative) in this context.
   </output>
   </example>
   
   <example>
   <input>
   Sie hat gesagt, dass sie müde ist.
   Она сказала, что она устала.
   </input>
   <output>
   ✅
   </output>
   </example>
   
   <example>
   <input>
   Мы пойдем гулять завтра.
   </input>
   <output>
   Wir werden morgen spazieren gehen.
   </output>
   </example>
   
   <example>
   <input>
   Ich habe kein Zeit.
   </input>
   <output>
   Ich habe *keine* Zeit.
   Das Wort "kein" sollte "keine" sein, da "Zeit" feminin ist (Nominativ oder Akkusativ).
   </output>
   </example>
                   ```
   
                   ### Response:
                   ```
                   Alles, was wir hier haben, sind Ordner, Dateien und Text.

                   ```
                   
                   ---
                   
                   ## 2025-02-16T04:59:38.857Z
                   ### Prompt:
                   ```
                   Translate the given German text to English. The translation should be staying true to the original meaning. When possible, mimic german sentance structure. Only provide the translation, no explanations or additional content.
   
   <example>
   input:
   Der fleißige Student fängt an, das schwierige Buch zu lesen.
   output:
   The diligent student begins the difficult book to read.
   </example>
   
   <example>
   input:
   Keine Angst. Mit Wasser kriegt man das wieder ab.
   output:
   No worry. With water can one wash it off.
   </example>
                   ```
   
                   ### Response:
                   ```
                   All, with which we here have, are folders, files and text.

                   ```
                   
                   ---
                   
                   ## 2025-02-16T05:20:03.647Z
                   ### Prompt:
                   ```
                   Translate the given German text to English. The translation should be staying true to the original meaning. When possible, mimic german sentance structure. Only provide the translation, no explanations or additional content.
   
   <example>
   input:
   Der fleißige Student fängt an, das schwierige Buch zu lesen.
   output:
   The diligent student begins the difficult book to read.
   </example>
   
   <example>
   input:
   Keine Angst. Mit Wasser kriegt man das wieder ab.
   output:
   No worry. With water can one wash it off.
   </example>
                   ```
   
                   ### Response:
                   ```
                   **continuation**

                   ```
                   
                   ---
                   
                   ## 2025-02-16T05:20:11.196Z
                   ### Prompt:
                   ```
                   Translate the given German text to English. The translation should be staying true to the original meaning. When possible, mimic german sentance structure. Only provide the translation, no explanations or additional content.
   
   <example>
   input:
   Der fleißige Student fängt an, das schwierige Buch zu lesen.
   output:
   The diligent student begins the difficult book to read.
   </example>
   
   <example>
   input:
   Keine Angst. Mit Wasser kriegt man das wieder ab.
   output:
   No worry. With water can one wash it off.
   </example>
                   ```
   
                   ### Response:
                   ```
                   Continuation

                   ```
                   
                   ---
                   
                   ## 2025-02-16T05:21:19.784Z
                   ### Prompt:
                   ```
                   Translate the given German text to English. The translation should be staying true to the original meaning. When possible, mimic german sentance structure. Only provide the translation, no explanations or additional content.
   
   <example>
   input:
   Der fleißige Student fängt an, das schwierige Buch zu lesen.
   output:
   The diligent student begins the difficult book to read.
   </example>
   
   <example>
   input:
   Keine Angst. Mit Wasser kriegt man das wieder ab.
   output:
   No worry. With water can one wash it off.
   </example>
                   ```
   
                   ### Response:
                   ```
                   **to precede**

                   ```
                   
                   ---
                   
                   ## 2025-02-16T05:41:14.596Z
                   ### Prompt:
                   ```
                   You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
       
       <german_word>
       {{german_word}}
       </german_word>
       
       Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:
       
       1. Identify the part of speech of the word.
       2. If it's a verb:
          - Determine if it's trennbar (separable) or untrennbar (inseparable).
          - Identify its tense forms (present, past, perfect).
          - Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
       3. For nouns:
          - Identify the gender (masculine, feminine, or neuter).
          - Determine the declension pattern.
       4. For adjectives:
          - Note the comparative and superlative forms.
       5. Identify and list examples of each morpheme in the word.
       6. Plan which template you'll use based on the part of speech.
       7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).
       
       It's OK for this section to be quite long.
       
       Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:
       
       1. For trennbar verbs:
          - Start with an appropriate emoji
          - Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table
       
       2. For untrennbar verbs and verbs without prefixes:
          - Follow a similar format to trennbar verbs, adjusting the conjugation details as needed
       
       3. For adjectives:
          - Start with an appropriate emoji
          - Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms
       
       4. For nouns:
          - Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
          - Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms
       
       5. For other parts of speech:
          - Create a similar template, adapting the information as appropriate for the specific part of speech
       
       Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
   <examples>
   <example>
   <german_word>
   verfeinden
   </german_word>
   <ideal_output>
   😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]
   
   ---
   
   
   ---
   = [[zerstreiten]], [[entzweien]]
   ≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
   ≠ [[versöhnen]], [[vertragen]], [[anfreunden]]
   
   ---
   to make enemies, to set at odds
   поссорить, сделать врагами
   
   ---
   [[ver]]|[[fein]]|[den]]
   
   ---
   ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
   er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
   ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 
   
   PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]
   
   ---
   [[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds
   
   ---
   [[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]
   
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   tanztest
   </german_word>
   <ideal_output>
   💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]
   
   ---
   
   ---
   = [[sich bewegen]], [[schwofen]], [[abhotten]]
   ≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
   ≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]
   
   ---
   to dance
   танцевать
   
   ---
   [[tanz]]|[[en]]
   
   ---
   ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
   du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
   er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
   wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
   ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]
   
   PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]
   
   ---
   
   ---
   [[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Hoffnung
   </german_word>
   <ideal_output>
   🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
   die [[Hoffnungen]]
   
   ---
   
   
   ---
   = [[Zuversicht]], [[Optimismus]]
   ≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
   ≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]
   
   ---
   hope
   надежда
   
   ---
   [[Hoff]]|[[nung]]
   
   ---
   N: die [[Hoffnung]], die [[Hoffnungen]]  
   A: die [[Hoffnung]], die [[Hoffnungen]]  
   G: der [[Hoffnung]], der [[Hoffnungen]]  
   D: der [[Hoffnung]], den [[Hoffnungen]]  
   
   ---
   [[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Busch
   </german_word>
   <ideal_output>
   🔵 🌳 der [[Busch]]
   die [[B\xFCsche]]
   
   ---
   
   
   ---
   = [[Strauch]], [[Gesträuch]]
   ≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
   ≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]
   
   ---
   bush, shrub
   куст
   
   ---
   [[Busch]]
   
   ---
   N: der [[Busch]], die [[Büsche]]  
   A: den [[Busch]], die [[Büsche]]  
   G: des [[Busches]], der [[Büsche]]  
   D: dem [[Busch]], den [[Büschen]] 
   
   ---
   buschig, buschieren
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   klein
   </german_word>
   <ideal_output>
   🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]
   
   ---
   
   
   ---
   = [[kompakt]], [[winzig]], [[gering]]
   ≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
   ≠ [[groß]], [[riesig]], [[weit]], [[breit]]
   
   ---
   small, little
   маленький
   
   ---
   [[klein]]
   
   ---
   N: [[klein]], [[kleiner]], [[kleinster]]  
   A: [[kleinen]], [[kleineren]], [[kleinsten]]  
   G: [[kleiner]], [[kleinerer]], [[kleinster]]  
   D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
   F: [[kleine]], [[kleinere]], [[kleinste]]  
   N: [[kleines]], [[kleineres]], [[kleinstes]]  
   P: [[kleinen]], [[kleineren]], [[kleinsten]]  
   
   ---
   [[Kleinheit]], [[kleinlich]], [[kleinmachen]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   anzurufen
   </german_word>
   <ideal_output>
   📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]
   
   ---
   
   
   ---
   = [[telefonieren]], [[kontaktieren]], [[anklingeln]]
   ≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
   ≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]
   
   ---
   to call, to phone
   звонить 
   
   ---
   [[an]]|[[ru]]|[[fen]]
   
   ---
   ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
   er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
   ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]
   
   PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]
   
   ---
   [[anrufen]] - [[an]] = [[rufen]] / to call, to phone
   
   ---
   [[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   ständigen
   </german_word>
   <ideal_output>
   🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]
   
   ---
   
   
   ---
   = [[fortwährend]], [[dauerhaft]], [[andauernd]]
   ≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
   ≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]
   
   ---
   constantly, continuously, persistently, perpetually
   постоянный, непрерывный, беспрестанный
   
   ---
   [[stän]]|[[dig]]
   
   ---
   N: [[ständig]], [[ständiger]], [[ständigster]]  
   A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
   F: [[ständige]], [[ständigere]], [[ständigste]]  
   N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
   P: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   
   ---
   [[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   traurig
   </german_word>
   <ideal_output>
   😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
   nicht [[fröhlich]]
   
   ---
   
   
   ---
   = [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
   ≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
   ≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]
   
   ---
   sad, sorrowful
   грустный, печальный
   
   ---
   [[trau]]|[[rig]]
   
   ---
   N: [[traurig]], [[trauriger]], [[traurigster]]  
   A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   G: [[trauriger]], [[traurigerer]], [[traurigster]]  
   D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
   F: [[traurige]], [[traurigere]], [[traurigste]]  
   N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
   P: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   
   ---
   [[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   obwohl
   </german_word>
   <ideal_output>
   🔗 [[obwohl]], [ɔpˈvoːl]
   
   ---
   
   
   ---
   = [[obgleich]], [[wenngleich]], [[obschon]]
   ≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
   ≠ [[weil]], [[denn]], [[deshalb]], [[daher]]
   
   ---
   although, even though, despite
   хотя, не смотря на 
   
   ---
   [[ob]]|[[wohl]]
   
   ---
   [[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   Rechercheergebnisse
   </german_word>
   <ideal_output>
   🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
   die [[Rechercheergbnisse]]
   
   ---
   
   
   ---
   = [[Untersuchungsergebnis]], [[Forschungsergebnis]]
   ≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
   ≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]
   
   ---
   research result, findings
   результаты исследования
   
   ---
   [[Recher­che]]+[[ergeb­nis]]
   [[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]
   
   ---
   N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
   D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  
   
   ---
   [[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
   </ideal_output>
   </example>
   </examples>
   
                   ```
   
                   ### Response:
                   ```
                   🔢 [[zehn]], [tseːn]
   
   ---
   
   
   ---
   = [[Zehner]], [[Dekade]]
   ≈ [[Anzahl]], [[Menge]], [[Zahl]], [[Betrag]]
   ≠ [[eins]], [[null]], [[wenig]]
   
   ---
   ten, ten
   десять
   
   ---
   [[zehn]]
   
   ---
   
   
   ---
   [[zehnmal]], [[zehnte]], [[zehnfach]], [[zehnjährig]], [[zehnprozentig]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:01:47.457Z
                   ### Prompt:
                   ```
                   You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
       
       <german_word>
       {{german_word}}
       </german_word>
       
       Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:
       
       1. Identify the part of speech of the word.
       2. If it's a verb:
          - Determine if it's trennbar (separable) or untrennbar (inseparable).
          - Identify its tense forms (present, past, perfect).
          - Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
       3. For nouns:
          - Identify the gender (masculine, feminine, or neuter).
          - Determine the declension pattern.
       4. For adjectives:
          - Note the comparative and superlative forms.
       5. Identify and list examples of each morpheme in the word.
       6. Plan which template you'll use based on the part of speech.
       7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).
       
       It's OK for this section to be quite long.
       
       Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:
       
       1. For trennbar verbs:
          - Start with an appropriate emoji
          - Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table
       
       2. For untrennbar verbs and verbs without prefixes:
          - Follow a similar format to trennbar verbs, adjusting the conjugation details as needed
       
       3. For adjectives:
          - Start with an appropriate emoji
          - Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms
       
       4. For nouns:
          - Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
          - Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms
       
       5. For other parts of speech:
          - Create a similar template, adapting the information as appropriate for the specific part of speech
       
       Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
   <examples>
   <example>
   <german_word>
   verfeinden
   </german_word>
   <ideal_output>
   😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]
   
   ---
   
   
   ---
   = [[zerstreiten]], [[entzweien]]
   ≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
   ≠ [[versöhnen]], [[vertragen]], [[anfreunden]]
   
   ---
   to make enemies, to set at odds
   поссорить, сделать врагами
   
   ---
   [[ver]]|[[fein]]|[den]]
   
   ---
   ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
   er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
   ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 
   
   PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]
   
   ---
   [[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds
   
   ---
   [[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]
   
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   tanztest
   </german_word>
   <ideal_output>
   💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]
   
   ---
   
   ---
   = [[sich bewegen]], [[schwofen]], [[abhotten]]
   ≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
   ≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]
   
   ---
   to dance
   танцевать
   
   ---
   [[tanz]]|[[en]]
   
   ---
   ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
   du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
   er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
   wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
   ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]
   
   PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]
   
   ---
   
   ---
   [[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Hoffnung
   </german_word>
   <ideal_output>
   🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
   die [[Hoffnungen]]
   
   ---
   
   
   ---
   = [[Zuversicht]], [[Optimismus]]
   ≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
   ≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]
   
   ---
   hope
   надежда
   
   ---
   [[Hoff]]|[[nung]]
   
   ---
   N: die [[Hoffnung]], die [[Hoffnungen]]  
   A: die [[Hoffnung]], die [[Hoffnungen]]  
   G: der [[Hoffnung]], der [[Hoffnungen]]  
   D: der [[Hoffnung]], den [[Hoffnungen]]  
   
   ---
   [[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Busch
   </german_word>
   <ideal_output>
   🔵 🌳 der [[Busch]]
   die [[B\xFCsche]]
   
   ---
   
   
   ---
   = [[Strauch]], [[Gesträuch]]
   ≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
   ≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]
   
   ---
   bush, shrub
   куст
   
   ---
   [[Busch]]
   
   ---
   N: der [[Busch]], die [[Büsche]]  
   A: den [[Busch]], die [[Büsche]]  
   G: des [[Busches]], der [[Büsche]]  
   D: dem [[Busch]], den [[Büschen]] 
   
   ---
   buschig, buschieren
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   klein
   </german_word>
   <ideal_output>
   🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]
   
   ---
   
   
   ---
   = [[kompakt]], [[winzig]], [[gering]]
   ≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
   ≠ [[groß]], [[riesig]], [[weit]], [[breit]]
   
   ---
   small, little
   маленький
   
   ---
   [[klein]]
   
   ---
   N: [[klein]], [[kleiner]], [[kleinster]]  
   A: [[kleinen]], [[kleineren]], [[kleinsten]]  
   G: [[kleiner]], [[kleinerer]], [[kleinster]]  
   D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
   F: [[kleine]], [[kleinere]], [[kleinste]]  
   N: [[kleines]], [[kleineres]], [[kleinstes]]  
   P: [[kleinen]], [[kleineren]], [[kleinsten]]  
   
   ---
   [[Kleinheit]], [[kleinlich]], [[kleinmachen]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   anzurufen
   </german_word>
   <ideal_output>
   📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]
   
   ---
   
   
   ---
   = [[telefonieren]], [[kontaktieren]], [[anklingeln]]
   ≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
   ≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]
   
   ---
   to call, to phone
   звонить 
   
   ---
   [[an]]|[[ru]]|[[fen]]
   
   ---
   ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
   er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
   ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]
   
   PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]
   
   ---
   [[anrufen]] - [[an]] = [[rufen]] / to call, to phone
   
   ---
   [[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   ständigen
   </german_word>
   <ideal_output>
   🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]
   
   ---
   
   
   ---
   = [[fortwährend]], [[dauerhaft]], [[andauernd]]
   ≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
   ≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]
   
   ---
   constantly, continuously, persistently, perpetually
   постоянный, непрерывный, беспрестанный
   
   ---
   [[stän]]|[[dig]]
   
   ---
   N: [[ständig]], [[ständiger]], [[ständigster]]  
   A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
   F: [[ständige]], [[ständigere]], [[ständigste]]  
   N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
   P: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   
   ---
   [[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   zweiteres
   </german_word>
   <ideal_output>
   2️⃣ [[zwei]], [t͡svaɪ̯]  
   
   ---
   
   ---
   = [[doppelt]], [[beide]], [[paar]]  
   ≈ [[ein paar]], [[mehrere]], [[einige]]  
   ≠ [[eins]], [[drei]], [[keiner]]  
   
   ---
   two  
   два  
   
   ---
   [[zwei]]  
   
   ---
   N: [[zwei]]  
   A: [[zwei]]  
   G: [[zweier]]  
   D: [[zweien]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]  
   A: [[zweiten]], [[zweiteren]], [[zweiten]]  
   G: [[zweiten]], [[zweiterer]], [[zweiten]]  
   D: [[zweitem]], [[zweiterem]], [[zweiten]]  
   F: [[zweite]], [[zweitere]], [[zweiteste]]  
   N: [[zweites]], [[zweiteres]], [[zweitestes]]  
   P: [[zweiten]], [[zweiteren]], [[zweitesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen** *(if applicable)*  
   (none for zwei)  
   
   ---
   [[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]
   </ideal_output>
   </example>
   
   
   <example>
   <german_word>
   einzigsten
   </german_word>
   <ideal_output>
   1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]  
   
   ---
   = [[einziger]], [[einer]], [[einmal]]  
   ≈ [[gewisser]], [[irgendein]], [[ein paar]]  
   ≠ [[null]], [[zwei]], [[kein]]  
   
   ---
   one, a/an, single  
   один, некий, какой-то  
   
   ---
   [[ein]]  
   
   ---
   N: [[ein]], [[eins]]  
   A: [[ein]]  
   G: [[eines]]  
   D: [[einem]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[erste]], [[erster]], [[erstes]], [[ersten]]  
   A: [[ersten]], [[ersteren]], [[ersten]]  
   G: [[ersten]], [[ersterer]], [[ersten]]  
   D: [[erstem]], [[ersterem]], [[ersten]]  
   F: [[erste]], [[erstere]], [[ersteste]]  
   N: [[erstes]], [[ersteres]], [[erstestes]]  
   P: [[ersten]], [[ersteren]], [[erstesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen**  
   N: [[einige]], [[einer]], [[einziges]], [[einigen]]  
   A: [[einigen]], [[einiger]], [[einzigsten]]  
   G: [[einiger]], [[einigerer]], [[einzigster]]  
   D: [[einigem]], [[einigerem]], [[einzigstem]]  
   F: [[einige]], [[einige]], [[einzigste]]  
   N: [[einiges]], [[einigeres]], [[einzigstes]]  
   P: [[einigen]], [[einigeren]], [[einzigsten]]  
   
   ---
   [[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   traurig
   </german_word>
   <ideal_output>
   😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
   nicht [[fröhlich]]
   
   ---
   
   
   ---
   = [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
   ≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
   ≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]
   
   ---
   sad, sorrowful
   грустный, печальный
   
   ---
   [[trau]]|[[rig]]
   
   ---
   N: [[traurig]], [[trauriger]], [[traurigster]]  
   A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   G: [[trauriger]], [[traurigerer]], [[traurigster]]  
   D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
   F: [[traurige]], [[traurigere]], [[traurigste]]  
   N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
   P: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   
   ---
   [[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   obwohl
   </german_word>
   <ideal_output>
   🔗 [[obwohl]], [ɔpˈvoːl]
   
   ---
   
   
   ---
   = [[obgleich]], [[wenngleich]], [[obschon]]
   ≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
   ≠ [[weil]], [[denn]], [[deshalb]], [[daher]]
   
   ---
   although, even though, despite
   хотя, не смотря на 
   
   ---
   [[ob]]|[[wohl]]
   
   ---
   [[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   Rechercheergebnisse
   </german_word>
   <ideal_output>
   🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
   die [[Rechercheergbnisse]]
   
   ---
   
   
   ---
   = [[Untersuchungsergebnis]], [[Forschungsergebnis]]
   ≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
   ≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]
   
   ---
   research result, findings
   результаты исследования
   
   ---
   [[Recher­che]]+[[ergeb­nis]]
   [[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]
   
   ---
   N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
   D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  
   
   ---
   [[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
   </ideal_output>
   </example>
   </examples>
   
                   ```
   
                   ### Response:
                   ```
                   1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]

---


---
= [[einziger]], [[einer]], [[einmal]]
≈ [[gewisser]], [[irgendein]], [[ein paar]]
≠ [[null]], [[zwei]], [[kein]]

---
one, a/an, single
один, некий, какой-то

---
[[ein]]

---
N: [[ein]], [[eins]]
A: [[ein]]
G: [[eines]]
D: [[einem]]

---
📏 **Konjugierte Ordinalzahlen**
N: [[erste]], [[erster]], [[erstes]], [[ersten]]
A: [[ersten]], [[ersteren]], [[ersten]]
G: [[ersten]], [[ersterer]], [[ersten]]
D: [[erstem]], [[ersterem]], [[ersten]]
F: [[erste]], [[erstere]], [[ersteste]]
N: [[erstes]], [[ersteres]], [[erstestes]]
P: [[ersten]], [[ersteren]], [[erstesten]]

---
📊 **Konjugierte Indefinitzahlen**
N: [[einige]], [[einer]], [[einziges]], [[einigen]]
A: [[einigen]], [[einiger]], [[einzigsten]]
G: [[einiger]], [[einigerer]], [[einzigster]]
D: [[einigem]], [[einigerem]], [[einzigstem]]
F: [[einige]], [[einige]], [[einzigste]]
N: [[einiges]], [[einigeres]], [[einzigstes]]
P: [[einigen]], [[einigeren]], [[einzigsten]]

---
[[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:04:18.482Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:08.365Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:13.001Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:14.919Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:27.321Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:31.018Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:05:34.732Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:07:48.139Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:07:52.076Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:07:57.827Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:08:06.988Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:08:13.260Z
                   ### Prompt:
                   ```
                   You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
       
       <german_word>
       {{german_word}}
       </german_word>
       
       Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:
       
       1. Identify the part of speech of the word.
       2. If it's a verb:
          - Determine if it's trennbar (separable) or untrennbar (inseparable).
          - Identify its tense forms (present, past, perfect).
          - Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
       3. For nouns:
          - Identify the gender (masculine, feminine, or neuter).
          - Determine the declension pattern.
       4. For adjectives:
          - Note the comparative and superlative forms.
       5. Identify and list examples of each morpheme in the word.
       6. Plan which template you'll use based on the part of speech.
       7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).
       
       It's OK for this section to be quite long.
       
       Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:
       
       1. For trennbar verbs:
          - Start with an appropriate emoji
          - Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table
       
       2. For untrennbar verbs and verbs without prefixes:
          - Follow a similar format to trennbar verbs, adjusting the conjugation details as needed
       
       3. For adjectives:
          - Start with an appropriate emoji
          - Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms
       
       4. For nouns:
          - Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
          - Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms
       
       5. For other parts of speech:
          - Create a similar template, adapting the information as appropriate for the specific part of speech
       
       Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
   <examples>
   <example>
   <german_word>
   verfeinden
   </german_word>
   <ideal_output>
   😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]
   
   ---
   
   
   ---
   = [[zerstreiten]], [[entzweien]]
   ≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
   ≠ [[versöhnen]], [[vertragen]], [[anfreunden]]
   
   ---
   to make enemies, to set at odds
   поссорить, сделать врагами
   
   ---
   [[ver]]|[[fein]]|[den]]
   
   ---
   ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
   er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
   ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 
   
   PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]
   
   ---
   [[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds
   
   ---
   [[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]
   
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   tanztest
   </german_word>
   <ideal_output>
   💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]
   
   ---
   
   ---
   = [[sich bewegen]], [[schwofen]], [[abhotten]]
   ≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
   ≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]
   
   ---
   to dance
   танцевать
   
   ---
   [[tanz]]|[[en]]
   
   ---
   ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
   du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
   er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
   wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
   ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]
   
   PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]
   
   ---
   
   ---
   [[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Hoffnung
   </german_word>
   <ideal_output>
   🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
   die [[Hoffnungen]]
   
   ---
   
   
   ---
   = [[Zuversicht]], [[Optimismus]]
   ≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
   ≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]
   
   ---
   hope
   надежда
   
   ---
   [[Hoff]]|[[nung]]
   
   ---
   N: die [[Hoffnung]], die [[Hoffnungen]]  
   A: die [[Hoffnung]], die [[Hoffnungen]]  
   G: der [[Hoffnung]], der [[Hoffnungen]]  
   D: der [[Hoffnung]], den [[Hoffnungen]]  
   
   ---
   [[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Busch
   </german_word>
   <ideal_output>
   🔵 🌳 der [[Busch]]
   die [[B\xFCsche]]
   
   ---
   
   
   ---
   = [[Strauch]], [[Gesträuch]]
   ≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
   ≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]
   
   ---
   bush, shrub
   куст
   
   ---
   [[Busch]]
   
   ---
   N: der [[Busch]], die [[Büsche]]  
   A: den [[Busch]], die [[Büsche]]  
   G: des [[Busches]], der [[Büsche]]  
   D: dem [[Busch]], den [[Büschen]] 
   
   ---
   buschig, buschieren
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   klein
   </german_word>
   <ideal_output>
   🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]
   
   ---
   
   
   ---
   = [[kompakt]], [[winzig]], [[gering]]
   ≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
   ≠ [[groß]], [[riesig]], [[weit]], [[breit]]
   
   ---
   small, little
   маленький
   
   ---
   [[klein]]
   
   ---
   N: [[klein]], [[kleiner]], [[kleinster]]  
   A: [[kleinen]], [[kleineren]], [[kleinsten]]  
   G: [[kleiner]], [[kleinerer]], [[kleinster]]  
   D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
   F: [[kleine]], [[kleinere]], [[kleinste]]  
   N: [[kleines]], [[kleineres]], [[kleinstes]]  
   P: [[kleinen]], [[kleineren]], [[kleinsten]]  
   
   ---
   [[Kleinheit]], [[kleinlich]], [[kleinmachen]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   anzurufen
   </german_word>
   <ideal_output>
   📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]
   
   ---
   
   
   ---
   = [[telefonieren]], [[kontaktieren]], [[anklingeln]]
   ≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
   ≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]
   
   ---
   to call, to phone
   звонить 
   
   ---
   [[an]]|[[ru]]|[[fen]]
   
   ---
   ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
   er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
   ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]
   
   PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]
   
   ---
   [[anrufen]] - [[an]] = [[rufen]] / to call, to phone
   
   ---
   [[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   ständigen
   </german_word>
   <ideal_output>
   🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]
   
   ---
   
   
   ---
   = [[fortwährend]], [[dauerhaft]], [[andauernd]]
   ≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
   ≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]
   
   ---
   constantly, continuously, persistently, perpetually
   постоянный, непрерывный, беспрестанный
   
   ---
   [[stän]]|[[dig]]
   
   ---
   N: [[ständig]], [[ständiger]], [[ständigster]]  
   A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
   F: [[ständige]], [[ständigere]], [[ständigste]]  
   N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
   P: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   
   ---
   [[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   zweiteres
   </german_word>
   <ideal_output>
   2️⃣ [[zwei]], [t͡svaɪ̯]  
   
   ---
   
   ---
   = [[doppelt]], [[beide]], [[paar]]  
   ≈ [[ein paar]], [[mehrere]], [[einige]]  
   ≠ [[eins]], [[drei]], [[keiner]]  
   
   ---
   two  
   два  
   
   ---
   [[zwei]]  
   
   ---
   N: [[zwei]]  
   A: [[zwei]]  
   G: [[zweier]]  
   D: [[zweien]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]  
   A: [[zweiten]], [[zweiteren]], [[zweiten]]  
   G: [[zweiten]], [[zweiterer]], [[zweiten]]  
   D: [[zweitem]], [[zweiterem]], [[zweiten]]  
   F: [[zweite]], [[zweitere]], [[zweiteste]]  
   N: [[zweites]], [[zweiteres]], [[zweitestes]]  
   P: [[zweiten]], [[zweiteren]], [[zweitesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen** *(if applicable)*  
   (none for zwei)  
   
   ---
   [[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]
   </ideal_output>
   </example>
   
   
   <example>
   <german_word>
   einzigsten
   </german_word>
   <ideal_output>
   1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]  
   
   ---
   = [[einziger]], [[einer]], [[einmal]]  
   ≈ [[gewisser]], [[irgendein]], [[ein paar]]  
   ≠ [[null]], [[zwei]], [[kein]]  
   
   ---
   one, a/an, single  
   один, некий, какой-то  
   
   ---
   [[ein]]  
   
   ---
   N: [[ein]], [[eins]]  
   A: [[ein]]  
   G: [[eines]]  
   D: [[einem]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[erste]], [[erster]], [[erstes]], [[ersten]]  
   A: [[ersten]], [[ersteren]], [[ersten]]  
   G: [[ersten]], [[ersterer]], [[ersten]]  
   D: [[erstem]], [[ersterem]], [[ersten]]  
   F: [[erste]], [[erstere]], [[ersteste]]  
   N: [[erstes]], [[ersteres]], [[erstestes]]  
   P: [[ersten]], [[ersteren]], [[erstesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen**  
   N: [[einige]], [[einer]], [[einziges]], [[einigen]]  
   A: [[einigen]], [[einiger]], [[einzigsten]]  
   G: [[einiger]], [[einigerer]], [[einzigster]]  
   D: [[einigem]], [[einigerem]], [[einzigstem]]  
   F: [[einige]], [[einige]], [[einzigste]]  
   N: [[einiges]], [[einigeres]], [[einzigstes]]  
   P: [[einigen]], [[einigeren]], [[einzigsten]]  
   
   ---
   [[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   traurig
   </german_word>
   <ideal_output>
   😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
   nicht [[fröhlich]]
   
   ---
   
   
   ---
   = [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
   ≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
   ≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]
   
   ---
   sad, sorrowful
   грустный, печальный
   
   ---
   [[trau]]|[[rig]]
   
   ---
   N: [[traurig]], [[trauriger]], [[traurigster]]  
   A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   G: [[trauriger]], [[traurigerer]], [[traurigster]]  
   D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
   F: [[traurige]], [[traurigere]], [[traurigste]]  
   N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
   P: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   
   ---
   [[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   obwohl
   </german_word>
   <ideal_output>
   🔗 [[obwohl]], [ɔpˈvoːl]
   
   ---
   
   
   ---
   = [[obgleich]], [[wenngleich]], [[obschon]]
   ≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
   ≠ [[weil]], [[denn]], [[deshalb]], [[daher]]
   
   ---
   although, even though, despite
   хотя, не смотря на 
   
   ---
   [[ob]]|[[wohl]]
   
   ---
   [[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   Rechercheergebnisse
   </german_word>
   <ideal_output>
   🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
   die [[Rechercheergbnisse]]
   
   ---
   
   
   ---
   = [[Untersuchungsergebnis]], [[Forschungsergebnis]]
   ≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
   ≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]
   
   ---
   research result, findings
   результаты исследования
   
   ---
   [[Recher­che]]+[[ergeb­nis]]
   [[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]
   
   ---
   N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
   D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  
   
   ---
   [[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
   </ideal_output>
   </example>
   </examples>
   
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]], [ˈzɔlən] | [[sollte]], haben [[gesollt]]
   
   ---
   
   
   ---
   = [[müssen]], [[dürfen]], [[brauchen]]
   ≈ [[beabsichtigen]], [[vorhaben]], [[planen]]
   ≠ [[wollen]], [[dürfen]], [[können]]
   
   ---
   should, ought to
   следует, должен
   
   ---
   [[soll]]|[[en]]
   
   ---
   ich: [[soll]], [[sollte]], –, [[solle]], [[sollte]]
   du: [[sollst]], [[solltest]], [[solle]] | [[soll]], [[solltest]], [[solltest]]
   er/sie/es: [[soll]], [[sollte]], –, [[solle]], [[sollte]]
   wir: [[sollen]], [[sollten]], [[sollen wir|sollen]], [[sollen]], [[sollten]]
   ihr: [[sollt]], [[solltet]], [[sollt]], [[sollet]], [[solltet]]
   
   PI: [[sollend]], PII: [[gesollt]], Zu+inf: [[zu sollen]]
   
   ---
   [[sollen]] - [[soll]] = [[en]] / should, ought to
   
   ---
   [[Soll]], [[Sollbruchstelle]], [[Sollwert]], [[Soll-Ist-Vergleich]], [[sollte]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:09:19.355Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:13:08.745Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:13:10.858Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:13:18.788Z
                   ### Prompt:
                   ```
                   You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
       
       <german_word>
       {{german_word}}
       </german_word>
       
       Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:
       
       1. Identify the part of speech of the word.
       2. If it's a verb:
          - Determine if it's trennbar (separable) or untrennbar (inseparable).
          - Identify its tense forms (present, past, perfect).
          - Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
       3. For nouns:
          - Identify the gender (masculine, feminine, or neuter).
          - Determine the declension pattern.
       4. For adjectives:
          - Note the comparative and superlative forms.
       5. Identify and list examples of each morpheme in the word.
       6. Plan which template you'll use based on the part of speech.
       7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).
       
       It's OK for this section to be quite long.
       
       Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:
       
       1. For trennbar verbs:
          - Start with an appropriate emoji
          - Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table
       
       2. For untrennbar verbs and verbs without prefixes:
          - Follow a similar format to trennbar verbs, adjusting the conjugation details as needed
       
       3. For adjectives:
          - Start with an appropriate emoji
          - Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms
       
       4. For nouns:
          - Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
          - Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms
       
       5. For other parts of speech:
          - Create a similar template, adapting the information as appropriate for the specific part of speech
       
       Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
   <examples>
   <example>
   <german_word>
   verfeinden
   </german_word>
   <ideal_output>
   😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]
   
   ---
   
   
   ---
   = [[zerstreiten]], [[entzweien]]
   ≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
   ≠ [[versöhnen]], [[vertragen]], [[anfreunden]]
   
   ---
   to make enemies, to set at odds
   поссорить, сделать врагами
   
   ---
   [[ver]]|[[fein]]|[den]]
   
   ---
   ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
   er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
   wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
   ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 
   
   PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]
   
   ---
   [[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds
   
   ---
   [[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]
   
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   tanztest
   </german_word>
   <ideal_output>
   💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]
   
   ---
   
   ---
   = [[sich bewegen]], [[schwofen]], [[abhotten]]
   ≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
   ≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]
   
   ---
   to dance
   танцевать
   
   ---
   [[tanz]]|[[en]]
   
   ---
   ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
   du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
   er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
   wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
   ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]
   
   PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]
   
   ---
   
   ---
   [[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Hoffnung
   </german_word>
   <ideal_output>
   🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
   die [[Hoffnungen]]
   
   ---
   
   
   ---
   = [[Zuversicht]], [[Optimismus]]
   ≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
   ≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]
   
   ---
   hope
   надежда
   
   ---
   [[Hoff]]|[[nung]]
   
   ---
   N: die [[Hoffnung]], die [[Hoffnungen]]  
   A: die [[Hoffnung]], die [[Hoffnungen]]  
   G: der [[Hoffnung]], der [[Hoffnungen]]  
   D: der [[Hoffnung]], den [[Hoffnungen]]  
   
   ---
   [[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   Busch
   </german_word>
   <ideal_output>
   🔵 🌳 der [[Busch]]
   die [[B\xFCsche]]
   
   ---
   
   
   ---
   = [[Strauch]], [[Gesträuch]]
   ≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
   ≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]
   
   ---
   bush, shrub
   куст
   
   ---
   [[Busch]]
   
   ---
   N: der [[Busch]], die [[Büsche]]  
   A: den [[Busch]], die [[Büsche]]  
   G: des [[Busches]], der [[Büsche]]  
   D: dem [[Busch]], den [[Büschen]] 
   
   ---
   buschig, buschieren
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   klein
   </german_word>
   <ideal_output>
   🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]
   
   ---
   
   
   ---
   = [[kompakt]], [[winzig]], [[gering]]
   ≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
   ≠ [[groß]], [[riesig]], [[weit]], [[breit]]
   
   ---
   small, little
   маленький
   
   ---
   [[klein]]
   
   ---
   N: [[klein]], [[kleiner]], [[kleinster]]  
   A: [[kleinen]], [[kleineren]], [[kleinsten]]  
   G: [[kleiner]], [[kleinerer]], [[kleinster]]  
   D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
   F: [[kleine]], [[kleinere]], [[kleinste]]  
   N: [[kleines]], [[kleineres]], [[kleinstes]]  
   P: [[kleinen]], [[kleineren]], [[kleinsten]]  
   
   ---
   [[Kleinheit]], [[kleinlich]], [[kleinmachen]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   anzurufen
   </german_word>
   <ideal_output>
   📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]
   
   ---
   
   
   ---
   = [[telefonieren]], [[kontaktieren]], [[anklingeln]]
   ≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
   ≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]
   
   ---
   to call, to phone
   звонить 
   
   ---
   [[an]]|[[ru]]|[[fen]]
   
   ---
   ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
   er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
   wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
   ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]
   
   PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]
   
   ---
   [[anrufen]] - [[an]] = [[rufen]] / to call, to phone
   
   ---
   [[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   ständigen
   </german_word>
   <ideal_output>
   🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]
   
   ---
   
   
   ---
   = [[fortwährend]], [[dauerhaft]], [[andauernd]]
   ≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
   ≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]
   
   ---
   constantly, continuously, persistently, perpetually
   постоянный, непрерывный, беспрестанный
   
   ---
   [[stän]]|[[dig]]
   
   ---
   N: [[ständig]], [[ständiger]], [[ständigster]]  
   A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
   F: [[ständige]], [[ständigere]], [[ständigste]]  
   N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
   P: [[ständigen]], [[ständigeren]], [[ständigsten]]  
   
   ---
   [[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   zweiteres
   </german_word>
   <ideal_output>
   2️⃣ [[zwei]], [t͡svaɪ̯]  
   
   ---
   
   ---
   = [[doppelt]], [[beide]], [[paar]]  
   ≈ [[ein paar]], [[mehrere]], [[einige]]  
   ≠ [[eins]], [[drei]], [[keiner]]  
   
   ---
   two  
   два  
   
   ---
   [[zwei]]  
   
   ---
   N: [[zwei]]  
   A: [[zwei]]  
   G: [[zweier]]  
   D: [[zweien]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]  
   A: [[zweiten]], [[zweiteren]], [[zweiten]]  
   G: [[zweiten]], [[zweiterer]], [[zweiten]]  
   D: [[zweitem]], [[zweiterem]], [[zweiten]]  
   F: [[zweite]], [[zweitere]], [[zweiteste]]  
   N: [[zweites]], [[zweiteres]], [[zweitestes]]  
   P: [[zweiten]], [[zweiteren]], [[zweitesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen** *(if applicable)*  
   (none for zwei)  
   
   ---
   [[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]
   </ideal_output>
   </example>
   
   
   <example>
   <german_word>
   einzigsten
   </german_word>
   <ideal_output>
   1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]  
   
   ---
   = [[einziger]], [[einer]], [[einmal]]  
   ≈ [[gewisser]], [[irgendein]], [[ein paar]]  
   ≠ [[null]], [[zwei]], [[kein]]  
   
   ---
   one, a/an, single  
   один, некий, какой-то  
   
   ---
   [[ein]]  
   
   ---
   N: [[ein]], [[eins]]  
   A: [[ein]]  
   G: [[eines]]  
   D: [[einem]]  
   
   ---
   📏 **Konjugierte Ordinalzahlen**  
   N: [[erste]], [[erster]], [[erstes]], [[ersten]]  
   A: [[ersten]], [[ersteren]], [[ersten]]  
   G: [[ersten]], [[ersterer]], [[ersten]]  
   D: [[erstem]], [[ersterem]], [[ersten]]  
   F: [[erste]], [[erstere]], [[ersteste]]  
   N: [[erstes]], [[ersteres]], [[erstestes]]  
   P: [[ersten]], [[ersteren]], [[erstesten]]  
   
   ---
   📊 **Konjugierte Indefinitzahlen**  
   N: [[einige]], [[einer]], [[einziges]], [[einigen]]  
   A: [[einigen]], [[einiger]], [[einzigsten]]  
   G: [[einiger]], [[einigerer]], [[einzigster]]  
   D: [[einigem]], [[einigerem]], [[einzigstem]]  
   F: [[einige]], [[einige]], [[einzigste]]  
   N: [[einiges]], [[einigeres]], [[einzigstes]]  
   P: [[einigen]], [[einigeren]], [[einzigsten]]  
   
   ---
   [[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]
   </ideal_output>
   </example>
   
   <example>
   <german_word>
   traurig
   </german_word>
   <ideal_output>
   😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
   nicht [[fröhlich]]
   
   ---
   
   
   ---
   = [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
   ≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
   ≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]
   
   ---
   sad, sorrowful
   грустный, печальный
   
   ---
   [[trau]]|[[rig]]
   
   ---
   N: [[traurig]], [[trauriger]], [[traurigster]]  
   A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   G: [[trauriger]], [[traurigerer]], [[traurigster]]  
   D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
   F: [[traurige]], [[traurigere]], [[traurigste]]  
   N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
   P: [[traurigen]], [[traurigeren]], [[traurigsten]]  
   
   ---
   [[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   obwohl
   </german_word>
   <ideal_output>
   🔗 [[obwohl]], [ɔpˈvoːl]
   
   ---
   
   
   ---
   = [[obgleich]], [[wenngleich]], [[obschon]]
   ≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
   ≠ [[weil]], [[denn]], [[deshalb]], [[daher]]
   
   ---
   although, even though, despite
   хотя, не смотря на 
   
   ---
   [[ob]]|[[wohl]]
   
   ---
   [[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
   </ideal_output>
   </example>
   <example>
   <german_word>
   Rechercheergebnisse
   </german_word>
   <ideal_output>
   🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
   die [[Rechercheergbnisse]]
   
   ---
   
   
   ---
   = [[Untersuchungsergebnis]], [[Forschungsergebnis]]
   ≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
   ≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]
   
   ---
   research result, findings
   результаты исследования
   
   ---
   [[Recher­che]]+[[ergeb­nis]]
   [[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]
   
   ---
   N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
   G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
   D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  
   
   ---
   [[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
   </ideal_output>
   </example>
   </examples>
   
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]], [ˈzɔlən] | [[sollte]], haben [[gesollt]]
   
   ---
   
   
   ---
   = [[müssen]], [[dürfen]], [[brauchen]]
   ≈ [[beabsichtigen]], [[vorhaben]], [[planen]]
   ≠ [[wollen]], [[mögen]], [[dürfen]]
   
   ---
   should, ought to
   следует, должен
   
   ---
   [[soll]]|[[en]]
   
   ---
   ich: [[soll]], [[sollte]], –, [[solle]], [[sollte]]
   du: [[sollst]], [[solltest]], [[solle]] | [[soll]], [[solltest]], [[solltest]]
   er/sie/es: [[soll]], [[sollte]], –, [[solle]], [[sollte]]
   wir: [[sollen]], [[sollten]], [[sollen wir|sollen]], [[sollen]], [[sollten]]
   ihr: [[sollt]], [[solltet]], [[sollt]], [[sollet]], [[solltet]]
   
   PI: –, PII: [[gesollt]], Zu+inf: [[sollen]]
   
   ---
   
   ---
   [[Soll]], [[sollte]], [[sollen]], [[Sollbruchstelle]], [[Sollwert]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:15:20.701Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt"   "🍳[[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🤞 🔴 die [[Hoffnung]]. Given "eisigen", reply with "🥶 [[eisig]]. I a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️, [[vergangen]] | 🕰️, [[vergehen]]. Given "Nieser", reply with "🤧 [[niesen]] | 🔵 🤧 der [[Nieser]]. Gigen "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 😌 🟢 das [[Klare]]"
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:16:57.700Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:06.840Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:12.096Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:13.191Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:22.866Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:29.445Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:35.108Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:41.401Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:18:50.552Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:19:08.518Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:20:35.482Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                   ## 2025-02-16T06:20:43.024Z
                   ### Prompt:
                   ```
                   Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                   ```
   
                   ### Response:
                   ```
                   🤔 [[sollen]]

                   ```
                   
                   ---
                   
                  ## 2025-02-16T06:21:58.327Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:27:27.476Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:27:30.487Z
                  ### Prompt:
                  ```
                  You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
<german_word>
{{german_word}}
</german_word>

Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:

1. Identify the part of speech of the word.
2. If it's a verb:
- Determine if it's trennbar (separable) or untrennbar (inseparable).
- Identify its tense forms (present, past, perfect).
- Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
3. For nouns:
- Identify the gender (masculine, feminine, or neuter).
- Determine the declension pattern.
4. For adjectives:
- Note the comparative and superlative forms.
5. Identify and list examples of each morpheme in the word.
6. Plan which template you'll use based on the part of speech.
7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).

It's OK for this section to be quite long.

Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:

1. For trennbar verbs:
- Start with an appropriate emoji
- Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table

2. For untrennbar verbs and verbs without prefixes:
- Follow a similar format to trennbar verbs, adjusting the conjugation details as needed

3. For adjectives:
- Start with an appropriate emoji
- Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms

4. For nouns:
- Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
- Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms

5. For other parts of speech:
- Create a similar template, adapting the information as appropriate for the specific part of speech

Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
<examples>
<example>
<german_word>
verfeinden
</german_word>
<ideal_output>
😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]

---


---
= [[zerstreiten]], [[entzweien]]
≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
≠ [[versöhnen]], [[vertragen]], [[anfreunden]]

---
to make enemies, to set at odds
поссорить, сделать врагами

---
[[ver]]|[[fein]]|[den]]

---
ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 

PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]

---
[[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds

---
[[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]

</ideal_output>
</example>

<example>
<german_word>
tanztest
</german_word>
<ideal_output>
💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]

---

---
= [[sich bewegen]], [[schwofen]], [[abhotten]]
≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]

---
to dance
танцевать

---
[[tanz]]|[[en]]

---
ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]

PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]

---

---
[[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
</ideal_output>
</example>

<example>
<german_word>
Hoffnung
</german_word>
<ideal_output>
🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
die [[Hoffnungen]]

---


---
= [[Zuversicht]], [[Optimismus]]
≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]

---
hope
надежда

---
[[Hoff]]|[[nung]]

---
N: die [[Hoffnung]], die [[Hoffnungen]]  
A: die [[Hoffnung]], die [[Hoffnungen]]  
G: der [[Hoffnung]], der [[Hoffnungen]]  
D: der [[Hoffnung]], den [[Hoffnungen]]  

---
[[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
</ideal_output>
</example>

<example>
<german_word>
Busch
</german_word>
<ideal_output>
🔵 🌳 der [[Busch]]
die [[B\xFCsche]]

---


---
= [[Strauch]], [[Gesträuch]]
≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]

---
bush, shrub
куст

---
[[Busch]]

---
N: der [[Busch]], die [[Büsche]]  
A: den [[Busch]], die [[Büsche]]  
G: des [[Busches]], der [[Büsche]]  
D: dem [[Busch]], den [[Büschen]] 

---
buschig, buschieren
</ideal_output>
</example>

<example>
<german_word>
klein
</german_word>
<ideal_output>
🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]

---


---
= [[kompakt]], [[winzig]], [[gering]]
≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
≠ [[groß]], [[riesig]], [[weit]], [[breit]]

---
small, little
маленький

---
[[klein]]

---
N: [[klein]], [[kleiner]], [[kleinster]]  
A: [[kleinen]], [[kleineren]], [[kleinsten]]  
G: [[kleiner]], [[kleinerer]], [[kleinster]]  
D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
F: [[kleine]], [[kleinere]], [[kleinste]]  
N: [[kleines]], [[kleineres]], [[kleinstes]]  
P: [[kleinen]], [[kleineren]], [[kleinsten]]  

---
[[Kleinheit]], [[kleinlich]], [[kleinmachen]]
</ideal_output>
</example>
<example>
<german_word>
anzurufen
</german_word>
<ideal_output>
📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]

---


---
= [[telefonieren]], [[kontaktieren]], [[anklingeln]]
≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]

---
to call, to phone
звонить 

---
[[an]]|[[ru]]|[[fen]]

---
ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]

PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]

---
[[anrufen]] - [[an]] = [[rufen]] / to call, to phone

---
[[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
</ideal_output>
</example>
<example>
<german_word>
ständigen
</german_word>
<ideal_output>
🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]

---


---
= [[fortwährend]], [[dauerhaft]], [[andauernd]]
≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]

---
constantly, continuously, persistently, perpetually
постоянный, непрерывный, беспрестанный

---
[[stän]]|[[dig]]

---
N: [[ständig]], [[ständiger]], [[ständigster]]  
A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
F: [[ständige]], [[ständigere]], [[ständigste]]  
N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
P: [[ständigen]], [[ständigeren]], [[ständigsten]]  

---
[[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
</ideal_output>
</example>

<example>
<german_word>
zweiteres
</german_word>
<ideal_output>
2️⃣ [[zwei]], [t͡svaɪ̯]  

---

---
= [[doppelt]], [[beide]], [[paar]]  
≈ [[ein paar]], [[mehrere]], [[einige]]  
≠ [[eins]], [[drei]], [[keiner]]  

---
two  
два  

---
[[zwei]]  

---
N: [[zwei]]  
A: [[zwei]]  
G: [[zweier]]  
D: [[zweien]]  

---
📏 **Konjugierte Ordinalzahlen**  
N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]  
A: [[zweiten]], [[zweiteren]], [[zweiten]]  
G: [[zweiten]], [[zweiterer]], [[zweiten]]  
D: [[zweitem]], [[zweiterem]], [[zweiten]]  
F: [[zweite]], [[zweitere]], [[zweiteste]]  
N: [[zweites]], [[zweiteres]], [[zweitestes]]  
P: [[zweiten]], [[zweiteren]], [[zweitesten]]  

---
📊 **Konjugierte Indefinitzahlen** *(if applicable)*  
(none for zwei)  

---
[[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]
</ideal_output>
</example>


<example>
<german_word>
einzigsten
</german_word>
<ideal_output>
1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]  

---
= [[einziger]], [[einer]], [[einmal]]  
≈ [[gewisser]], [[irgendein]], [[ein paar]]  
≠ [[null]], [[zwei]], [[kein]]  

---
one, a/an, single  
один, некий, какой-то  

---
[[ein]]  

---
N: [[ein]], [[eins]]  
A: [[ein]]  
G: [[eines]]  
D: [[einem]]  

---
📏 **Konjugierte Ordinalzahlen**  
N: [[erste]], [[erster]], [[erstes]], [[ersten]]  
A: [[ersten]], [[ersteren]], [[ersten]]  
G: [[ersten]], [[ersterer]], [[ersten]]  
D: [[erstem]], [[ersterem]], [[ersten]]  
F: [[erste]], [[erstere]], [[ersteste]]  
N: [[erstes]], [[ersteres]], [[erstestes]]  
P: [[ersten]], [[ersteren]], [[erstesten]]  

---
📊 **Konjugierte Indefinitzahlen**  
N: [[einige]], [[einer]], [[einziges]], [[einigen]]  
A: [[einigen]], [[einiger]], [[einzigsten]]  
G: [[einiger]], [[einigerer]], [[einzigster]]  
D: [[einigem]], [[einigerem]], [[einzigstem]]  
F: [[einige]], [[einige]], [[einzigste]]  
N: [[einiges]], [[einigeres]], [[einzigstes]]  
P: [[einigen]], [[einigeren]], [[einzigsten]]  

---
[[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]
</ideal_output>
</example>

<example>
<german_word>
traurig
</german_word>
<ideal_output>
😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
nicht [[fröhlich]]

---


---
= [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]

---
sad, sorrowful
грустный, печальный

---
[[trau]]|[[rig]]

---
N: [[traurig]], [[trauriger]], [[traurigster]]  
A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
G: [[trauriger]], [[traurigerer]], [[traurigster]]  
D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
F: [[traurige]], [[traurigere]], [[traurigste]]  
N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
P: [[traurigen]], [[traurigeren]], [[traurigsten]]  

---
[[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
</ideal_output>
</example>
<example>
<german_word>
obwohl
</german_word>
<ideal_output>
🔗 [[obwohl]], [ɔpˈvoːl]

---


---
= [[obgleich]], [[wenngleich]], [[obschon]]
≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
≠ [[weil]], [[denn]], [[deshalb]], [[daher]]

---
although, even though, despite
хотя, не смотря на 

---
[[ob]]|[[wohl]]

---
[[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
</ideal_output>
</example>
<example>
<german_word>
Rechercheergebnisse
</german_word>
<ideal_output>
🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
die [[Rechercheergbnisse]]

---


---
= [[Untersuchungsergebnis]], [[Forschungsergebnis]]
≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]

---
research result, findings
результаты исследования

---
[[Recher­che]]+[[ergeb­nis]]
[[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]

---
N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  

---
[[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
</ideal_output>
</example>
</examples>

                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]], [ˈzɔlən] | [[sollte]], haben [[gesollt]]

---

---
= [[müssen]], [[dürfen]], [[brauchen]]
≈ [[beabsichtigen]], [[vorhaben]], [[planen]], [[beabsichtigen]]
≠ [[wollen]], [[dürfen]], [[können]]

---
should, ought to
следует, должен

---
[[soll]]|[[en]]

---
ich: [[soll]], [[sollte]], –, [[soll]], [[sollte]]
du: [[sollst]], [[solltest]], [[soll]] | [[soll]], [[solltest]], [[solltest]]
er/sie/es: [[soll]], [[sollte]], –, [[soll]], [[sollte]]
wir: [[sollen]], [[sollten]], [[sollen wir|sollen]], [[sollen]], [[sollten]]
ihr: [[sollt]], [[solltet]], [[sollt]], [[sollt]], [[solltet]]

PI: –, PII: [[gesollt]], Zu+inf: [[sollen]]

---
[[sollen]] - [[soll]] = [[en]] / should, ought to

---
[[Soll]], [[Sollbruchstelle]], [[Sollwert]], [[Sollzeit]], [[Soll-Ist-Vergleich]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:27:44.960Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:27:52.094Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:27:55.311Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🤔 [[sollen]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:35:06.359Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  🔢 [[zweite]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:36:31.396Z
                  ### Prompt:
                  ```
                  You are an expert linguist specializing in the German language. Your task is to create a detailed dictionary entry for a given German word. Here's the word you need to analyze:
<german_word>
{{german_word}}
</german_word>

Before creating the entry, analyze the word and plan your approach. Break down the word inside <word_breakdown> tags:

1. Identify the part of speech of the word.
2. If it's a verb:
- Determine if it's trennbar (separable) or untrennbar (inseparable).
- Identify its tense forms (present, past, perfect).
- Note any irregular conjugations. -Fill the list of cojugations (Präsens, Präteritum, Imperativ, Konjunktiv I, Konjunktiv II) 
3. For nouns:
- Identify the gender (masculine, feminine, or neuter).
- Determine the declension pattern.
4. For adjectives:
- Note the comparative and superlative forms.
5. Identify and list examples of each morpheme in the word.
6. Plan which template you'll use based on the part of speech.
7. List the key information you'll need to include in the entry (e.g., pronunciation, conjugations, synonyms, antonyms, translations, morphemes).

It's OK for this section to be quite long.

Now, create the dictionary entry using the appropriate template based on your analysis. Strictly adhere to the format provided in the examples, ensuring no additional text is included that isn't present in the templates. Use the following guidelines:

1. For trennbar verbs:
- Start with an appropriate emoji
- Include pronunciation, conjugations, synonyms, antonyms, English and Russian translations, morpheme breakdown, and a conjugation table

2. For untrennbar verbs and verbs without prefixes:
- Follow a similar format to trennbar verbs, adjusting the conjugation details as needed

3. For adjectives:
- Start with an appropriate emoji
- Include pronunciation, antonyms, synonyms, English and Russian translations, and unique possible forms

4. For nouns:
- Use 🔴 for feminine, 🟢 for neuter, and 🔵 for masculine nouns
- Include plural form, synonyms, English and Russian translations, morpheme breakdown, and unique possible forms

5. For other parts of speech:
- Create a similar template, adapting the information as appropriate for the specific part of speech

Present only your final entry. Do not present the user with word_breakdown. Do not write to the user your thought process.
<examples>
<example>
<german_word>
verfeinden
</german_word>
<ideal_output>
😤 [[verfeinden]], [fɛɐ̯ˈfaɪ̯ndn̩] | [[verfeindete]], haben [[verfeindet]]

---


---
= [[zerstreiten]], [[entzweien]]
≈ Feindschaft  [[schließen]], [[verkrachen]], in Konflikt [[geraten]]
≠ [[versöhnen]], [[vertragen]], [[anfreunden]]

---
to make enemies, to set at odds
поссорить, сделать врагами

---
[[ver]]|[[fein]]|[den]]

---
ich: [[verfeinde]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
du: [[verfeindest]], [[verfeindetest]], [[verfeinde]] | [[verfeind]] | [[verfeinde]], [[verfeindest]], [[verfeindetest]]
er/sie/es: [[verfeindet]], [[verfeindete]], –, [[verfeinde]], [[verfeindete]]
wir: [[verfeinden]], [[verfeindeten]], [[verfeinden wir|verfeinden]], [[verfeinden]], [[verfeindeten]]
ihr: [[verfeindet]], [[verfeindetet]], [[verfeindet]], [[verfeindet]], [[verfeindetet]] 

PI: [[verfeindend]], PII: [[verfeindet]], Zu+inf: [[zuverfeinden]]

---
[[verfeinden]] - [[ver]] = [[feinden]] / to make enemies, to set at odds

---
[[Verfehndung]], [[Verfeindung]], [[Feind]], [[feindlich]], [[Feindschaft]]

</ideal_output>
</example>

<example>
<german_word>
tanztest
</german_word>
<ideal_output>
💃 [[tanzen]], [ˈtanʦn̩] | [[tanzte]], haben [[getanzt]]

---

---
= [[sich bewegen]], [[schwofen]], [[abhotten]]
≈ [[wiegen]], [[sich drehen]], [[hüpfen]], [[ballettieren]]
≠ [[sitzen]], [[stehen]], [[verharren]], [[ruhen]]

---
to dance
танцевать

---
[[tanz]]|[[en]]

---
ich: [[tanze]], [[tanzte]], –, [[tanze]], [[tanzte]]
du: [[tanzt]], [[tanzt]], [[tanze]] | [[tanz]], [[tanzt]], [[tanztest]]
er/sie/es: [[tanzt]], [[tanzte]], –, [[tanze]], [[tanzte]]
wir: [[tanzen]], [[tanzten]], [[tanzen wir|tanzen]], [[tanzen]], [[tanzten]]
ihr: [[tanzt]], [[tanztet]], [[tanzt]], [[tanzt]], [[tanztet]]

PI: [[tanzend]], PII: [[getanzt]], Zu+inf: [[zu tanzen]]

---

---
[[Tanz]], [[Tänzer]], [[Tänzerin]], [[Tanzfläche]], [[tanzerisch]], [[Tanzkurs]]
</ideal_output>
</example>

<example>
<german_word>
Hoffnung
</german_word>
<ideal_output>
🔴 🕊️ die [[Hoffnung]], [ˈhɔfnʊŋ]
die [[Hoffnungen]]

---


---
= [[Zuversicht]], [[Optimismus]]
≈ [[Erwartung]], [[Vertrauen]], [[Glaube]], [[Wunsch]]
≠ [[Verzweiflung]], [[Pessimismus]], [[Hoffnungslosigkeit]], [[Resignation]]

---
hope
надежда

---
[[Hoff]]|[[nung]]

---
N: die [[Hoffnung]], die [[Hoffnungen]]  
A: die [[Hoffnung]], die [[Hoffnungen]]  
G: der [[Hoffnung]], der [[Hoffnungen]]  
D: der [[Hoffnung]], den [[Hoffnungen]]  

---
[[hoffen]], [[hoffentlich]], [[hoffnungsvoll]], [[hoffnungslos]]
</ideal_output>
</example>

<example>
<german_word>
Busch
</german_word>
<ideal_output>
🔵 🌳 der [[Busch]]
die [[B\xFCsche]]

---


---
= [[Strauch]], [[Gesträuch]]
≈ [[Gebüsch]], [[Hecke]], [[Gehölz]]
≠ [[Baum]], [[Wiese]], [[Ackerland]], [[Ödland]]

---
bush, shrub
куст

---
[[Busch]]

---
N: der [[Busch]], die [[Büsche]]  
A: den [[Busch]], die [[Büsche]]  
G: des [[Busches]], der [[Büsche]]  
D: dem [[Busch]], den [[Büschen]] 

---
buschig, buschieren
</ideal_output>
</example>

<example>
<german_word>
klein
</german_word>
<ideal_output>
🐭 [[klein]], [\u02C8kla\u026A\u032Fn] ≠ [[gro\xDF]]

---


---
= [[kompakt]], [[winzig]], [[gering]]
≈ [[niedrig]], [[schmal]], [[zierlich]], [[zart]], [[begrenzt]]
≠ [[groß]], [[riesig]], [[weit]], [[breit]]

---
small, little
маленький

---
[[klein]]

---
N: [[klein]], [[kleiner]], [[kleinster]]  
A: [[kleinen]], [[kleineren]], [[kleinsten]]  
G: [[kleiner]], [[kleinerer]], [[kleinster]]  
D: [[kleinem]], [[kleinerem]], [[kleinstem]]  
F: [[kleine]], [[kleinere]], [[kleinste]]  
N: [[kleines]], [[kleineres]], [[kleinstes]]  
P: [[kleinen]], [[kleineren]], [[kleinsten]]  

---
[[Kleinheit]], [[kleinlich]], [[kleinmachen]]
</ideal_output>
</example>
<example>
<german_word>
anzurufen
</german_word>
<ideal_output>
📞 [[anrufen]], [ˈanʦuˌʁuːfən] | [[rief an]], haben [[angerufen]]

---


---
= [[telefonieren]], [[kontaktieren]], [[anklingeln]]
≈ [[sich melden]], [[Kontakt aufnehmen]], [[durchklingeln]]
≠ [[ignorieren]], [[ablehnen]], [[auflegen]], [[beenden]]

---
to call, to phone
звонить 

---
[[an]]|[[ru]]|[[fen]]

---
ich: [[rufe an]], [[rief an]], –, [[rufe an]], [[riefe an]]
du: [[rufst an]], [[riefst an]], [[rufe an]] | [[ruf an]], [[rufest an]], [[riefest an]]
er/sie/es: [[ruft an]], [[rief an]], –, [[rufe an]], [[riefe an]]
wir: [[rufen an]], [[riefen an]], [[rufen wir an|rufen an]], [[rufen an]], [[riefen an]]
ihr: [[ruft an]], [[rieft an]], [[ruft an]], [[rufet an]], [[riefet an]]

PI: [[anrufend]], PII: [[angerufen]], Zu+inf: [[anzurufen]]

---
[[anrufen]] - [[an]] = [[rufen]] / to call, to phone

---
[[Anruf]], [[Anrufer]], [[Anruferin]], [[anrufbar]], [[Anrufbeantworter]]
</ideal_output>
</example>
<example>
<german_word>
ständigen
</german_word>
<ideal_output>
🕰️ [[ständig]], [ˈʃtɛndɪç] ≠ [[selten]]

---


---
= [[fortwährend]], [[dauerhaft]], [[andauernd]]
≈ [[permanent]], [[kontinuierlich]], [[beständig]], [[ununterbrochen]], [[pausenlos]]
≠ [[selten]], [[gelegentlich]], [[unregelmäßig]], [[sporadisch]]

---
constantly, continuously, persistently, perpetually
постоянный, непрерывный, беспрестанный

---
[[stän]]|[[dig]]

---
N: [[ständig]], [[ständiger]], [[ständigster]]  
A: [[ständigen]], [[ständigeren]], [[ständigsten]]  
G: [[ständigen]], [[ständigeren]], [[ständigsten]]  
D: [[ständigem]], [[ständigeren]], [[ständigstem]]  
F: [[ständige]], [[ständigere]], [[ständigste]]  
N: [[ständiges]], [[ständigeres]], [[ständigstes]]  
P: [[ständigen]], [[ständigeren]], [[ständigsten]]  

---
[[stehen]], [[Ständigkeit]], [[zuständig]], [[anständig]], [[beständig]], [[aufständig]]
</ideal_output>
</example>

<example>
<german_word>
zweiteres
</german_word>
<ideal_output>
2️⃣ [[zwei]], [t͡svaɪ̯]  

---

---
= [[doppelt]], [[beide]], [[paar]]  
≈ [[ein paar]], [[mehrere]], [[einige]]  
≠ [[eins]], [[drei]], [[keiner]]  

---
two  
два  

---
[[zwei]]  

---
N: [[zwei]]  
A: [[zwei]]  
G: [[zweier]]  
D: [[zweien]]  

---
📏 **Konjugierte Ordinalzahlen**  
N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]  
A: [[zweiten]], [[zweiteren]], [[zweiten]]  
G: [[zweiten]], [[zweiterer]], [[zweiten]]  
D: [[zweitem]], [[zweiterem]], [[zweiten]]  
F: [[zweite]], [[zweitere]], [[zweiteste]]  
N: [[zweites]], [[zweiteres]], [[zweitestes]]  
P: [[zweiten]], [[zweiteren]], [[zweitesten]]  

---
📊 **Konjugierte Indefinitzahlen** *(if applicable)*  
(none for zwei)  

---
[[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]
</ideal_output>
</example>


<example>
<german_word>
einzigsten
</german_word>
<ideal_output>
1️⃣ [[eins]], [aɪ̯ns] | [[ein]], [aɪ̯n]  

---
= [[einziger]], [[einer]], [[einmal]]  
≈ [[gewisser]], [[irgendein]], [[ein paar]]  
≠ [[null]], [[zwei]], [[kein]]  

---
one, a/an, single  
один, некий, какой-то  

---
[[ein]]  

---
N: [[ein]], [[eins]]  
A: [[ein]]  
G: [[eines]]  
D: [[einem]]  

---
📏 **Konjugierte Ordinalzahlen**  
N: [[erste]], [[erster]], [[erstes]], [[ersten]]  
A: [[ersten]], [[ersteren]], [[ersten]]  
G: [[ersten]], [[ersterer]], [[ersten]]  
D: [[erstem]], [[ersterem]], [[ersten]]  
F: [[erste]], [[erstere]], [[ersteste]]  
N: [[erstes]], [[ersteres]], [[erstestes]]  
P: [[ersten]], [[ersteren]], [[erstesten]]  

---
📊 **Konjugierte Indefinitzahlen**  
N: [[einige]], [[einer]], [[einziges]], [[einigen]]  
A: [[einigen]], [[einiger]], [[einzigsten]]  
G: [[einiger]], [[einigerer]], [[einzigster]]  
D: [[einigem]], [[einigerem]], [[einzigstem]]  
F: [[einige]], [[einige]], [[einzigste]]  
N: [[einiges]], [[einigeres]], [[einzigstes]]  
P: [[einigen]], [[einigeren]], [[einzigsten]]  

---
[[einmal]], [[einzig]], [[einer]], [[einige]], [[erstens]], [[einheit]], [[einzel]], [[einzigartig]], [[einmalig]]
</ideal_output>
</example>

<example>
<german_word>
traurig
</german_word>
<ideal_output>
😢 [[traurig]], [ˈtʁaʊ̯ʁɪç]
nicht [[fröhlich]]

---


---
= [[betrübt]], [[bekümmert]], [[niedergeschlagen]]
≈ [[melancholisch]], [[wehmütig]], [[bedrückt]]
≠ [[fröhlich]], [[glücklich]], [[heiter]], [[vergnügt]]

---
sad, sorrowful
грустный, печальный

---
[[trau]]|[[rig]]

---
N: [[traurig]], [[trauriger]], [[traurigster]]  
A: [[traurigen]], [[traurigeren]], [[traurigsten]]  
G: [[trauriger]], [[traurigerer]], [[traurigster]]  
D: [[traurigem]], [[traurigerem]], [[traurigstem]]  
F: [[traurige]], [[traurigere]], [[traurigste]]  
N: [[trauriges]], [[traurigeres]], [[traurigstes]]  
P: [[traurigen]], [[traurigeren]], [[traurigsten]]  

---
[[Trauer]], [[trauern]], [[Traurigkeit]], [[betrauern]], [[trauernd]]
</ideal_output>
</example>
<example>
<german_word>
obwohl
</german_word>
<ideal_output>
🔗 [[obwohl]], [ɔpˈvoːl]

---


---
= [[obgleich]], [[wenngleich]], [[obschon]]
≈ [[dennoch]], [[gleichwohl]], [[trotzdem]], [[nichtsdestotrotz]]
≠ [[weil]], [[denn]], [[deshalb]], [[daher]]

---
although, even though, despite
хотя, не смотря на 

---
[[ob]]|[[wohl]]

---
[[trotz]], [[obschon]], [[obzwar]], [[wiewohl]], [[obgleich]]
</ideal_output>
</example>
<example>
<german_word>
Rechercheergebnisse
</german_word>
<ideal_output>
🟢 📄 das [[Rechercheergbenis]], [reˈʃɛrʃəʔɛɐ̯ɡeːpnɪs]
die [[Rechercheergbnisse]]

---


---
= [[Untersuchungsergebnis]], [[Forschungsergebnis]]
≈ [[Ergebnis]], [[Resultate]], [[Erkenntnisse]], [[Befund]]
≠ [[Hypothese]], [[Vermutung]], [[Spekulation]]

---
research result, findings
результаты исследования

---
[[Recher­che]]+[[ergeb­nis]]
[[Re]]|[[cher]]|[[che]]|[[er]]|[[geb]]|[[nis]]

---
N: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
A: das [[Rechercheergbenis]], die [[Rechercheergbnisse]]  
G: des [[Rechercheergbnis­ses]], der [[Rechercheergbnisse]]  
D: dem [[Rechercheergbnis]], den [[Rechercheergbnissen]]  

---
[[recherchieren]], [[Recherche]], [[ergebnisorientiert]], [[Forschung]]
</ideal_output>
</example>
</examples>

                  ```

                  ### Response:
                  ```
                  2️⃣ [[zwei]], [t͡svaɪ̯]

---

---
= [[doppelt]], [[beide]], [[paar]]
≈ [[ein paar]], [[mehrere]], [[einige]]
≠ [[eins]], [[drei]], [[keiner]]

---
two
два

---
[[zwei]]

---
N: [[zwei]]
A: [[zwei]]
G: [[zweier]]
D: [[zweien]]

---
📏 **Konjugierte Ordinalzahlen**
N: [[zweite]], [[zweiter]], [[zweites]], [[zweiten]]
A: [[zweiten]], [[zweiteren]], [[zweiten]]
G: [[zweiten]], [[zweiterer]], [[zweiten]]
D: [[zweitem]], [[zweiterem]], [[zweiten]]
F: [[zweite]], [[zweitere]], [[zweiteste]]
N: [[zweites]], [[zweiteres]], [[zweitestes]]
P: [[zweiten]], [[zweiteren]], [[zweitesten]]

---
📊 **Konjugierte Indefinitzahlen** *(if applicable)*
(none for zwei)

---
[[zweitens]], [[zweifach]], [[zwilling]], [[zweierlei]], [[zweiundzwanzig]], [[der Zweite]], [[zweitweise]], [[zweimalig]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:37:34.314Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌. Given "zweiteste", reply with "2️⃣ [[zwei]]". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  2️⃣ [[zwei]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:37:37.595Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌. Given "zweiteste", reply with "2️⃣ [[zwei]]". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  2️⃣ [[zwei]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:38:01.925Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌. Given "zweiteste", reply with "2️⃣ [[zwei]]". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  2️⃣ [[zwei]]

                  ```
                  
                  ---
                  
                  ## 2025-02-16T06:38:05.341Z
                  ### Prompt:
                  ```
                  Given a german word, determine its infinitive form and pick an appropriate emoji to represent it. If the word is a noun, determin it's gender and use 🔵 for der,  🔴 for die, if 🟢 for das. Do not write anything else, just the infinitive and an emoji. given "brutzelt" reply with "🍳 [[brutzeln]]". Given "gesorgt" reply with "🤔 [[sorgen]]". Given "Hoffnungen" reply with "🔴 die [[Hoffnung]] 🕊️". Given "eisigen", reply with "🥶 [[eisig]]". If a word can be a form of multiple parts of speach, list all options, separated with |. For expample, given "vergangene", reply with "🕰️ [[vergangen]] | 🕰️ [[vergehen]]". Given "Nieser", reply with "🤧 [[niesen]] | 🔵 der [[Nieser]] 🤧". Given "klares", reply with "😌 [[klären]] | 😌 [[klar]] | 🟢 das [[Klare]] 😌. Given "zweiteste", reply with "2️⃣ [[zwei]]". The output should be compact, without extra spaces or newlines.
                  ```

                  ### Response:
                  ```
                  2️⃣ [[zwei]]

                  ```
                  
                  ---
                  