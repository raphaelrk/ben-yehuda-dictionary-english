# Known issues and judgment calls

Collected from the translation workers' own reports; not exhaustive. `T3`, `T120` and so on
name the AI worker that translated the entries; they do not appear in the data file. General
rules the workers were given: expand an abbreviation only when confident, otherwise leave it
in Hebrew; keep references as printed even when they look wrong. Some early batches were made
before a rule was fixed, so practice varies. Corrections are welcome.

- T3: in one batch-2 entry, a bare "(ibid. b)" was completed as "(ibid. 129b)".
- T4, before the "keep references as printed" rule: some misprinted
  Bible references were silently corrected — Jeremiah 50:14 (printed נ ד), Job 20:29
  (printed ב כט), Exodus 34:27-28 (printed נד), Leviticus 6:19 (printed ז יט), Ezra 4:6
  (printed ד ז), Berakhot 6:1 (printed ל א). Also: כָּתַב's closing list of related words left in Hebrew.
- Unresolved abbreviations kept in Hebrew (all workers): e.g. סהמ"א, חל"א, רל', מה"ש (Barth),
  דל"ע (Böttcher), שבע"י, ת"ע/ת"ס, כ"ח, אה"ו, תנ"ך גזנ', פוע' מפוע', ש"ש, לקו"ק, ב"ז.
- Workers kept printed misprints in references (e.g. Ezra 3:64, Isaiah 68:14, Zephaniah 20:14).
- T5: replaced "ibid." (שם) with the book name where the intended source
  seemed clear; Ibn Janah's Judeo-Arabic quotations kept as printed; בוישנין rendered
  "bashful" (Jerusalem Talmud, end of Kiddushin) — uncertain.
- T10: ב"ז תב"ס 8:16 expanded as "Ben Ze'ev's translation of Ben Sira 8:16"
  (guess); in יָרַד II, Ibn Janah's quotation (Judeo-Arabic + Hebrew) given one English translation.
- T9: טָמֵא II resubmitted once (later line wins in the build). In יָעַד, every reference reads
  "(שמות כא ח-ט)" in Sefaria's text itself (a source-data error), so the English repeats
  "(Exodus 21:8-9)". In בָּשַׂר "להשתבח" (probably להשתכח) left in Hebrew; in אָחַר's note
  "זקנו של רש"י" translated literally ("Rashi's grandfather").
- T14: abbreviations expanded by judgement — ב"ע → Bar Ali; ר"י בן תנחו' ירוש' → Rabbi Joseph
  ben Tanhum Yerushalmi; ש"א (Aldabi) → Shevilei Emunah; מעי' יז. → Me'ilah 17a.
- T16: Jerusalem Talmud refs rendered "Sotah 8, 22d" (column number read as a letter);
  ק"ש, מו"א → Kalman Schulman, Mosdei Eretz (guess); in כַּלָּה I and כִּלָּה two Lisān al-ʿArab
  quotations were re-transcribed into Arabic script (should stay as printed); יָם paragraph 2
  (a word list) left in Hebrew.
- T17: less certain expansions — "Iggeret Hokhmah 1 3 4" (זָהָב); "Mozney Tzedek, al-Ghazali 37",
  "Ben Sira, translation of Ben Zev 36:20" (גָּמָל); ר"י א"ת → Rabbi Judah ibn Tibbon (דָּרַשׁ);
  יל"ג אדו"מ → Judah Leib Gordon, Ahavat David u-Mikhal (הוֹד, הֶדֶר).
- T19: glosses corrected — כָּפָר German "Derf" → "Dorf"; אָשַׁר III English "straigth" → "straight"
  (with a [Note] saying the source misprints it).
- T15: יְקָר English gloss "preicous" → "precious"; poetry lines in לַמֶד and חָקַק translated
  literally with low confidence.
- T20: זָמַר I — one line of a Purim poem translated tentatively; in הָדָר "(ibid. 27:2 [as printed])"
  has an added "[as printed]".
- T21: some medieval poetry rendered approximately (worst: ibn Ezra "פוך שערי" in יֶלֶד, Tarshish 5).
- T22: in חָנַן I the garbled Pu'al gloss "שחטו לו חֵן חמד" translated by likely meaning; in בָּעֵל
  an English rendering of the Arabic dictionary definition added beside the Arabic.
- T27: אֲדָמָה and אֶלָּא — the opening etymology note is translated but not marked "[Note: …]".
- T28: "תוספות דמאי" expanded as Tosefta Demai (reading); T31: in יסד I a run-in note left as plain text.
- T30: less certain expansions — דל' ומ' ארנ' → Delitzsch and Muss-Arnolt; ב"ז → Ben-Zeev;
  דה"ט → Dikdukei ha-Te'amim; מא"ג → Mordecai Aaron Günzburg; rough piyyut lines in יָקַר,
  חָלָה II, יֶקֶר II, חֹמֶר I.
- T37: grammarian abbreviations read as Ewald (אולד), Olshausen, König, Böttcher, Stade, Wellhausen;
  "שו"ת תמת ישר' שא לג" read as "question 33". T35: Kalir/Judah Halevi lines in גָּזַר and טָלַל I uncertain.
- Source-data error (confirmed in Sefaria's raw HTML): in some entries every reference is
  replaced by one repeated reference — יָעַד ("(שמות כא ח-ט)" ×51), חֹשֶׁךְ ("(שמות י כב-כג)" ×31).
  The translations follow the data; correct references need the printed dictionary (archive.org scans).
- Scan (2026-11-23) for entries where one reference makes up >60% of 8+ references (likely the same source-data error), 6 entries: דָּגָה I ("שמות ז יז-יח" ×14/17), זוֹל ("מע"ש ד א" ×12/12), חָלַץ II ("במד' לב כז" ×11/16), חֹשֶׁךְ ("שמות י כב-כג" ×31/34), יָעַד ("שמות כא ח-ט" ×51/62), כְּבֵדֻת ("שמות יד כה" ×10/13)
- T42: in הִגָּיוֹן, "דברי חפץ" (probably the title Divrei Chefetz) was translated as "words of
  delight"; added short glosses in the word lists of גָּבֹהַּ, כַּעַס, הִגָּיוֹן.
- T39: added short glosses to the body-part list in גּוּף I.
- T44: opening etymology notes of חֶבֶל, חוֹל I and חבל I not marked "[Note: …]".
- T43: three Arabic words printed in Hebrew letters were romanized (bakkā, abkā, bal) in batches 1–2; printed ellipses rendered as dashes.
- T59: opening Arabic etymology notes in כָּבָה and אָשָׁם not marked "[Note: …]"; fused quotation at the end of חֶדְוָה translated literally.
- T60: names expanded by judgement — ר"י א"ת → R. Y. ibn Tibbon, ר"י הלוי → R. Judah ha-Levi (least certain), רשב"ג with Shirei Shlomo → Solomon ibn Gabirol.
- T58: opening notes of יָסַר III, חפשׁ I, לקט, ארז, חלש I and אָוֶן not marked "[Note: …]".
- T65: book name אלמשתלחק romanized as "al-Mustalhaq"; best-effort piyyut lines in דָּגָה II, חֵפֶר II, חָצַב I, כָּלִיל III.
- T73: in הֲלִיכָה "נחול' א ב" rendered as Chullin 1:2 (possible correction).
- T75: ש"א → Shevilei Emunah under דָּמַע (reading); approximate piyyut lines in חָרַת I and וָו.
- T76: approximate renderings of liturgical poems in טָכַס and חָשַׁר.
- T78: uncertain renderings in חָשַׂף (Karaite wordplay) and וִתֵּק (with a bracketed rendering of the opening forms).
- T81: expansions to check — מא"ג → Mordecai Aaron Günzburg, ר"ש א"ת → Samuel ibn Tibbon, ר"ש (Mishnah) → Rabbi Samson, רדב"א → David ben Abraham; בֶּצַע sense b quotation boundary unclear.
- T86: opening note of כִּיּוֹר III not marked "[Note: …]".
- T83: literal, unconfident renderings of verse quotations in כְּסִיל (Moses ibn Ezra, Bonafed); Saadia's Judeo-Arabic note in כְּסִיל translated into English.
- T87: חל"א (in ארשׁ) expanded as "scholars of Akkadian".
- T85: approximate piyyut renderings (טוב ערה מנוצלת, טורפי בדי גורות, לזינה).
- T89: literal piyyut renderings (Kalir, Halevi) in טָרַח, גָּנַן, חָרַז, טֵאטֵא — expert review.
- T94: under גַּס III "א תכ"ב לחשבונם" rendered "the year 1422 by their reckoning" (check).
- Inconsistent: סהמ"א rendered "medieval literature" (T91, לוּז IV) and "later literature" (T91 batch 4; T4 "later literature (סהמ"א)"); needs one agreed reading.
- T96: transliterated names to check — "Fürst and Nager" (פירסט ונגר, אַזְכָּרָה), "R. Z. ben Saadia" (כֶּסֶת).
- T100: Aramaic/Arabic-only quotations (Onkelos, Targum Jonathan, Saadia under אֲפֻדָּה; Muhammad passage under חָנַךְ) kept as printed without English; uncertain Kalir lines (טָרָהּ) and Canon passage (כָּדָר).
- T97: best-reading poetry lines in וָעַד, חָפַף I, כָּסַף; "כלירמון גנו" rendered Clermont-Ganneau in א.
- T110: approximate poetic quotations in זָבַד, טוּחַ I, יָאַשׁ.
- T109: in אֵימָתַי two "ר"י" expanded as Rabbi Yose / Rabbi Judah from the Mishnah quoted; in אָמַד the stem הפ' labelled Hif'il (could be Huf'al).
- T119: bracketed clarifiers added in אֲשֶׁר ("[to the truth]", "[i.e.]", "[the place]") and in quotations in כֹּל I (not marked as notes).
- T115: expansions — ו"ה → Wolf Heidenheim, חו"ה → Chovot HaLevavot, ר"י גאון → Rabbi Yehudai Gaon (check).
- T121: מ"ש expanded as Minchat Shai (Masoretic notes in בּוֹא, אָכַל, הָלַךְ).
- T123: printed "=" between verse numbers written as ranges (Ezekiel 22:19-21, Sanhedrin 3:6-7) in יָצָא/כָּנַס.
- T124: garbled reference left as "(Jeremiah מ כ י)" in יָדַע I / יָרַד I.
- T126: typo abbreviations expanded (פבח' → Pesachim, תופסתא → Tosefta); parenthesized Hebrew forms added after some translated words, e.g. "(יִלְמַד)" (לָמַד, דִּין I, חַי).
- T127: "העבד" read as a typo for "העבר" (past tense) in כֹּחַ II; ר' זבדא kept as "R. Zabda" (probably ibn Zabara); רשב"ג kept as "Rashbag" in a poem citation; "נחבאת בחזיונה" left in Hebrew.
- T128: expansions — ר"ח → Rabbenu Hananel, רשב"ג → Solomon ibn Gabirol, ש"א → Shevilei Emunah, ג"ע → Gan Eden (R. Aaron the Karaite), נלד' → Nöldeke, אשרמון → Ascherson; "(Psalms צנד 17)" garbled (כָּרַת I).
- T130: expansions — שבי"ע → Shevilei Olam, רחז"ס → Ch. Z. Slonimski, דה"ט → Diqduqei ha-Te'amim; vowel points added to a few unpointed Hebrew phrases in חָזַק (e.g. חִזֵּק אוֹתוֹ).
- T129: expansions — רמב"ח → Moses ibn Habib, הלדסה' → Hildesheimer, א"ק → Adam Kadmon, ר"י א"ת → R. Judah ibn Tibbon; "ח' אורות" in כְּלִי translated "eight lights" (context suggests five); "ובמוכרת *יָלוּד" (יָלַד) left in Hebrew.
- T132: in כ the foreign glosses may have been reordered (check against the print); "י"ס כי הנוסחה משֻבשה" read as "some hold" (could be "some books"); in יהוה the divine name is kept in Hebrew in every quotation.
- T131: "פדר"א לא" read as Pirkei deRabbi Eliezer 31; "מעי' ט:" as Me'ilah 9b; Hebrew verb forms in parentheses after English words in יָסַף; gloss labels in כְּלוּם added afterwards.
- T133: in ה, a stray footnote marker "א" dropped from הֶהָלְכוּא (Joshua 10:24); "Bart" spelled Barth; שע"פ left unexpanded.
- 2026-11-24 fixes: חָזַר regrouped from 20 English paragraphs to the Hebrew's 5; added ellipses removed in יְצִיאָה and דִּבָּה.
- Further points from the last batches' reports (references below are kept as printed and look wrong):
  - T120: "ibid. 51:56" (for Genesis 31:36), Jeremiah 54:22, Jeremiah 36:45 (אִלְמָלֵא, כִּי I, יָשַׁב); ר"י, ר"א written "R. Y.", "R. A."; "תוקפות הויות" left in Hebrew.
  - T121: Genesis 15:11 (for 18:11); one long footnote in בּוֹא is printed and translated twice; Ewald/Böttcher/König quotations left in German.
  - T122: Psalms 10:23, Isaiah 20:23, 1 Samuel 2:50, Daniel 11:58, "Megillah רח.", Responsa Pe'er ha-Dor 153 (ב, לֵבָב, כָּבֵד II); German passages in ב left in German.
  - T123: Ruth 2:24, Proverbs 14:4, Psalms 19:30; sense letters in לֵב skip from b to d as printed.
  - T124: Exodus 51:13, Daniel 11:58; Aramaic Targum quotations translated; a note in יָרַד I is printed and translated twice.
  - T125: poem titles and unresolved abbreviations left in Hebrew (לְמַעַן, כָּבוֹד, כֵּן I).
  - T126: Jeremiah 12:6, 1 Samuel 1:27, Psalms 119:2, 2 Chronicles 17:7-10, Nedarim 38b, Berakhot 10a, Chagigah 6a.
  - T127: "ibid. 25:17" after Ezekiel (the quotation is 1 Samuel 25:17), Jeremiah 17:4, "ibid. 123"; the second paragraph of כֹּחַ II is a Hebrew word list.
  - T128: three Isaiah quotations in כָּרַת I read as "ibid." after 2 Kings; Jeremiah 40:4; "(Jeremiah 6)" with no verse; "Judges 7:5" twice in לָשׁוֹן; Avot 6:1.
  - T129: Jeremiah 17:3 and 16:13, Isaiah 39:4 (יָלַד); Isaiah 67:20, Genesis 26:3, Deuteronomy 1:48, Yoma 7:8 (כְּלִי); Psalms 93:3 (כּוּן).
  - T130: 2 Chronicles 21:4 (חָזַק); Zechariah 17:14, "ZDMG, 1817", Psalms 136:6-9, Isaiah 56:20, Psalms 74:11, Deuteronomy 4:29, Amos 8:8, Judges 11:6, Genesis 7:8 (ו); a Masoretic mnemonic left in Hebrew.
  - T131: Sanhedrin 150b, Leviticus Rabbah 52, "Midrash Rabbah מראש' 2" (כְּלוּם); Genesis 38:29 for Ruth 1:17 and for Genesis 38:26 (יָסַף).
  - T132: Avodah Zarah 7b, Mishnah Sukkah 1:2, Numbers 16:20; Greek χύρις, "E. Ewakd" (יהוה, כ); a duplicated sentence in the יהוה essay is translated twice.
  - T133: "ibid. 36:26" after Isaiah, "ibid. 17:55" after Judges, Ezekiel 20:50, 1 Samuel 16:26, Berakhot 34b (ה).
- T138: kept as printed — Jeremiah 57:21 (אוֹפֶה), misprinted glosses (flocok, Hinterhait, lumieux, ciclist); expansions to check — מוס ארנולד → Muss-Arnolt, לו → Lowe, לֶו → Löw, אוצ"ט → Otzar Tov, שי"ר → Shir (Rapoport), מדב"מ → "Mishnah of the people of the West", ר"א אירירו → R. A. Herrera; tentative lines in אָבַךְ, אֲבָךְ, אִיָר, אֲבִיּוֹנָה, אִזּוּן; words left in Hebrew in אֵימְתָן, אֵדִי, אָבַךְ, אִירָה, אִירָא; some Aramaic left untranslated in אַוְנָה, אִוְשָׁה; unlabeled gloss "menace" in אִיֵּם.
- T134: uncertain piyyut and Aramaic lines in אֵיתוֹן, אָהַהּ, אֲזָרָה, אַחַל II, אֲזֵן, אֲכָס; expansions to check — שבי"ע → Shevilei Olam, חקו"ד → Chikkur ha-Din, אדו"מ → Ahavat David u-Mikhal, כשתלי → Castell, זד"ת → Zoologie des Talmuds, מג"א → Magen Avot / Magen Avraham, רגב"ש → R. Gershon ben Solomon, ב"מ → "Heaven preserve us", בא read as "2 1" (אִישִׁי, אִישִׁיּוּת); references kept as printed that look wrong in אַדְּרַבָּה, אִחוּי, אִישׁוּת I, אֲזֵן, אַכְסַדְרָא, אָבָץ.
- T136: closing parenthesis supplied in אֲחַשְׁתְּרָנִים; 1 Kings 12:12 kept (probably 2 Kings) in אֲדַרְכָּל; expansions to check — אדו"מ → Ahavat David u-Mikhal, שבי"ע → Shevilei Olam, די"ע → Divrei Yemei Olam, צמ"ד → Tzemach David, מ"כ → Matnot Kehunah, סהמ"א → medieval literature; text that looks corrupt translated as printed in אֲבָבִית, אַדְמִימוּת, אָלוּחַ, אֶדֶק; misprinted glosses kept ("acron", "redish", "fievec"); loose poetry in אָדַק, אִחֵל, אָטוּר, אחת, אַדְמוֹן; Aramaic and its Hebrew rendering both translated in אֲחִיזָה, אִדָּן.
- T139: expansions to check — אדו"מ → Ahavat David u-Mikhal, רמא"ג → Mordecai Aaron Günzburg, או"ט → Otzar Tov, אד"מ → Adam ha-Kohen, או"נ → Otzar Nechmad; "ירוש' מעש' מח ד" read as Ma'aserot 48d (אַכְרוֹעַ); kept as printed — Kilayim "8, 31 נ" (אָוָז), two senses lettered d (אַוֵּיר), Jeremiah 21:27 (אֲטַב), "Mon. YVII" (אִכְפַּת), odd Arabic in אָטָד, misprinted German glosses, unlabeled glosses in אוֹכֵל and אַוֵּיר; uncertain lines in אֶגְרוֹף, אֲגָפָה, אָטָד, אֲדוּמָה, אַט; words left in Hebrew in אֵד, אַגְרַת, אֲוִיר קַדְמוֹן, אַכְרוֹעַ, אָטָד, אֻכָּף; some Aramaic left in אָטוּ.
- T135: expansions to check — כשתל(י) → Castelli (T134 read it Castell), מ"ש → Minchat Shai, אד"מ, שש"ק → Adam HaKohen, Shirei Sefat Kodesh, במו"ק פה → "in Mo'ed Katan here"; kept as printed though odd — "Peah 10" (אֱגוֹד), Deuteronomy 17:9 (אֹטֶם), "ביד" (אַלְמֹג), "זמי יעמוד" (אָלַם II), senses a then c (אַגָּן); uncertain lines in אַוְזָה, אוֹזֵן, אֵלֶם, אִטְלוּלָה, אָלַם I, אֶלְפָּה, אַגָּן, אֶטֶף; Judeo-Arabic left in אוֹגִירָה, אִידָן, אַלְמֹג.
- T137: expansions to check — תוה"ט → Toledot HaTeva, האוה"ד/או"ד → Emunot veDeot, ק"ש, די"ע → K. Schulman, Divrei Yemei Olam, מו"מ → Geonim of East and West; misprints read through — שס as "ibid." (אָבוּת), "ידיד ג" as "14 14c" (אוּמָן), "שם ע." as 70a (אַבַּט); glosses labelled by guess in אַבּוּב ("Röhre; pipe; tube") and אַלֶף (scrambled in print; a glyph is missing from the source); kept as printed though odd in אוּמָה, אַלֶף בֵּית, אַלָּמוּת, אִילָנִי; words left in Hebrew in אִילוֹנִית, אַלָּמוּת, אָבוּת, אַיְלוֹנִית, אִימָה; literal guesses in אַיֶּלֶת, אִבְחָה, אֵילַך.
- T140: expansions to check — מער' המער' → Ma'arikh ha-Ma'arakhot, תו"ה → Duties of the Heart, מ"א → Magen Avot; kept as printed though odd — Makhshirin 10:3 (אלתית), "there 19a" (אנוסה), Chullin printed as תול' (אנין I), Ben Sira 51:2 (אשוח), "Nedarim 49 י" (אשון), "Esther Rabbah 30" (אלתר), "EecEpS" (אלקום); words left in Hebrew in אלץ, אם, אנינות I; low-confidence piyyut and Karaite lines in אנוח, אנון, אפרתי, אשון, אשור, אנינות II, אמא.
- T141: expansions to check — או"ד → Emunot ve-De'ot (אַרְבָּה I), שינהק → Schönhak; "versifler, baater" labelled French/English by guess (אָפַז); kept as printed though odd — Genesis 1:1 and "there 63:15" (אָתֵי מֵרָחוֹק), Jeremiah 49:19 (אַרְגִּיעָה), "Kings book 3 section 4" (אֻרָוָה), Greek ἀσδενής (אִסְתְּנִיס), "Aescuplapius" (אַשְׁמַן), "Ahasuerus Mnemon" (אַפָּדַן); uncertain lines in אִשֵּׁשׁ, אַשְׁמַן, אֲתִייָה, אִפּוּף, אֲרִיחִי, אֻמְלָל, אִשְׁתְּקַד, אָמִיר; words left in Hebrew in אֵמוּם, אִשֵּׁשׁ, אִשְׁתְּקַד, אַפְטָט, אָע.
- T142: expansions to check — מא"ג → M. A. Günzburg, צ"ד → Tzemach David, א"ב → Elijah Bachur, פורגם/פורגס → Porges, "שמד מ." → "persecution 40", לאימתך → "toward Your nation" (אָמָּנוּת), "מנהג הוא" → "He is the leader" (אַרְצָה); "Mode" labelled German (אָפְנָה); kept as printed though odd — Psalms 21:2 (אֲרֶשֶׁת), "there 6:1-2" (בֶּדֶק I), "BEJ" (אֲפִיפִיוֹר), a garbled etymology note (בֶּדֶק I); words left in Hebrew in אָמָן, אַפִּיקוֹרוֹס, אָפַךְ, בָּדִיד, בֶּדֶק I; uncertain verse in אַרְקָה, אֲפִיפִיוֹר, בְּדֹלַח.
- T144: a misprinted ")" rendered "(" in אֶנֶף; uncertain verse in אָנַן, אֶנֶף, אָסוּם, אֶרְאֶל; "בעל גבר" → "one with a large member" (אשכן); "ליחס התנ"ך" translated literally (בּוֹ); words left in Hebrew in אֹשֶׁךְ, אֲנָצָה, בְּהִיקוּת, בַּהֲמִי, אֶשְׁכֹּל I, אַקְלִים, אֲסוּפָה, אָקוֹן, אֲרִאֵל; kept as printed though odd — Nedarim 7 40a (אָשִׁישׁ I), Tosefta Uktzin 11:2 (אֶשְׁכֹּל I), Gittin 13 43b (נבדק), "-lity, -dity" (אֹשֶׁךְ).
- T143: readings to check — "ר"י מפיסא" → R. Yechiel of Pisa, "תוכח' מוס' ה" → Musaf 5 (אִמֵּש), שת"ז/ש"ת → "adjectival noun" (בּוֹגֵר), חלא"ש → "scholars of Akkadian" (אפף), "הווחד" read as the child (אַשְׁפֹּת); kept as printed though odd — Isaiah 24:23 (אמרכל), Genesis 29 (אמש), "טו"ב פעמים" (אפפניאל), corrupt Hai Gaon words (אָפַץ); uncertain verse in אמש, אִמֵּש, אָפַן, בָּהַק, בּוּט, אַשְׁמוֹר, אֶשְׁנָב, אשמדי.
- T145: misprints read through (check) — "השתפכות הכלים" rendered "waves" (בִּגְאוֹן), "והדם הכללי" rendered "the general term" (אַסְכָּרָה); scrambled parentheses dropped around glosses in בַּגַר; kept as printed though odd — 2 Kings 3:16, 26 (בִּי II), Job 32:22 (אֶסְתָּן), "Sanhedrin 9 23" (בַּטְלָן), "Kiddushin 59b" (בַּגַר); tentative lines in אַרְכָּה, בֹּחַן, אָסַם, אֲרִיחָה, בְּאוּשָׁה, בַּחְרַאן.
- Repeated-reference scan of the non-siddur entries (2026-11-25; one parenthesised reference makes up >60% of 6 or more, probably the same source-data error): דּוּגִית ("ב"ב עג." ×11/11), הִתְנַכְּרוּת ("רד"ק, שרש זור" ×5/6), הִתְעַמְּלוּת ("ר"ש א"ת, מו"נ ג כה" ×14/15), וֶשֶׁט ("חול' ב ד" ×10/10), וַתְּרָן ("ירוש' סוט' ה כ ד" ×6/7), זַכּוּת ("כוזרי א קג" ×9/11), חִפּוּשׂ ("פסח' ז:" ×12/12), חִקּוּי ("מלות הגיון ח" ×8/9), כִּילוּ ("ירוש' ברכ' א ג." ×12/13), לָעַס ("שבת יט ב" ×9/10)
- T146: בְּלוֹא repeats Jeremiah 38:12 for every citation in the source; readings to check — "שיוחש בכבד" → heaviness (בְּתוּר), תינוקות של ב"ר → "schoolchildren" (ב"ר), בר מינן → "may it be far from us" (ב"מ), "אדומיית" → "reddish" (בֶּלְגַּמִי); ביקורת left untranslated in בִּקֹּרֶת II; kept as printed though odd — Job 6:5 (בְּלִיל), 1 Kings 19:25 (בָּרָה II), תתרסג (גַּאַוְתָן); literal verse in בּוּקָה, בָּלַם I, בַּלָּהָה, בַּת קוֹל, בָּתָה.
- T148: readings to check — תוה"א → Toledot ha-Aretz by Schönhack (בְּרוֹשִׁי), "הרעיפה" → nosebleed (גְּבוּלִי), "ואם היתומים" → the orphans' mother (גִּבּוּי); note boundaries in ג placed by sense; kept as printed though odd — Beitzah 15a (בֵּיצָה), "Hürdo" (בָּצְרָה), a repeated Ketubot 68a quotation (גִּבּוּי), "perplexed ones" and "arrows" (בְּרִיקָה); words left in Hebrew in בַּרְחָן, בָּקִיעַ, בִּרְיוֹן, ג; obscure Hoshana line in בַּרְיוֹן.
- T147: readings to check — אמו"ר → Emunah Ramah (בְּחִינָה), בחי"ע → Bechinat Olam (בָּזַר), אי"ש → Ish-Shalom (בָּחַל III), בטיית → "in Arabic" (בָּרֶקֶת); kept as printed though odd — Ezekiel 22:15 (בַּעַץ), Yoma 1:3 (בַּרְקַאי), "AWXVII" (בָּחַל I), feminine labels on masculine words (בַּעֲלָן, גְּדִיגוֹד), a garbled source (בַּעֲלַת הַלַּהַב); tentative verse in בַּחַל, בִּצּוּר, בַּצּוּר, גֶּדֶף, גְּדִידָה, בִּתּוּק; glosses left unlabelled in בָּרֶקֶת, בַּרְקַאי, גדמות, גְּדִיגוֹד and others.
- T150: readings to check — ר"י א"ת → R. J. ibn Tibbon, דפוס קוסט' → Constantinople, "מענית" → "she who torments" (גותן), "אם של זיתים" → "mass" (גוש), קנטר → "clamp" (בנאי), "ממחה" → "restrain" (בריה II); two-word glosses in גיבעול labelled German/French by guess; kept as printed though odd — years 4426 and 4531 (גברתן), "Chullin 50:1" (גז), "-negl" (בסיא), a repeated paragraph ending (גופיות); uncertain verse in בלק, בסיסה, בסיס, בריה II, גד II, גופני; words left in Hebrew in גברתן, גבעול, בורך, בריחה.
- T149: misprint read through — "ונבדק" rendered "joined" (גַּבְנִינוּת); "תקפוזה" split into word and note (בִּקֹּרֶת I); two-word glosses labelled German/French by position; cited Hebrew forms added in parentheses in places; kept as printed though odd — Jeremiah 1:21 (גִּזּוּם), "هَمَّز עלי" (גָּזַם II), glosses "-ny" and "deri" (גִּזְרָה); uncertain verse in בָּלַג I, גָּבַשׁ, גָּחוֹן, גָּזַף, בִּיתָן; words left in Hebrew in גִּזְרָה, גָּבְלִית, בָּרָה I, בַּיִר.
- T151: expansions to check — תוה"ט → Toledot HaTeva, מק"נ → Mekitzei Nirdamim, ש"א → Shevilei Emunah, עמה"מ → Emek HaMelekh, שהי"ח → Shir HaYichud, או"נ → Otzar Nechmad; misprinted glosses kept in גְּלוֹם I, גָּלִיל, בִּעְבַּע II, גָּהַר, גִּלְבּוֹן; words left in Hebrew in בֹּשֵׁש, בְּשָׂרִי, בַּת לַיְלָה, בַּת נֶפֶשׁ, בָּעַט I, גִּהוּק, גִּהוּר II, גָּהַר, גִּהֵץ, גִּלְדִּי, גְּלוֹם II, גָּלוּד, גִּלּוּעַ, גָּלִיל; least certain verse in גֹּדֶשׁ, גָּהַר, גָּהַץ I and II, גִּלּוּב, גִּלָּיוֹן.
- T152: expansions to check — תוה"א → Toledot HaAretz by Schönhak, בה"ע → Bikkurei HaIttim, או"נ → Otzar Nechmad, אוצה"ס → Otzar HaSifrut, יסו"ע → Yesod Olam, מכ' → Matnot Kehunah (גָּלַשׁ III), דה"ט → Dikdukei HaTe'amim, ה' דרנבורג → H. Derenburg, גנזכ' → Ginsburg; kept as printed though odd — Ezekiel 27:11 for a quotation about the Chinese (גַּמָּד), "פזח 112a" (גָּרוּשׁ), Ezekiel 23:2 (דַּד), Ecclesiastes 10:8 (גּוּמָץ), glosses "heigth", "boilling", "Sctzling"; words left in Hebrew in גּוּן, גָּוַן, גַּוָּן, גֹּמֶד, דָּדָה I and II, גַּרְזֶן, גִּמּוֹל; tentative verse in גַּהַר, גִּמּוֹן II, דָּדָה II, גָּרַז, גְּוִי.
- T153: expansions to check — שבי"ע → Shvilei Olam, ש"א → Shvilei Emunah, דו"מ → David and Michal (אדו"מ is Ahavat David u-Mikhal elsewhere), עי"ת → Ten Days of Repentance, תוה"א → Toledot HaAretz, תוה"ט → Toledot HaTeva, מק"נ → Mekitzei Nirdamim, R. Bahya "הדין" → the Dayyan, הר"י מינץ → R. Judah Minz; kept as printed though odd — Shabbat 24:5 and "Bava Batra Sukkah 20b" (גִּיגִית), Yerushalmi "7 8 4" (גִּיּוֹרֶת), misprinted English glosses; words left in Hebrew in גָּסָה, גִּיחַ I, גִיסָה, גְּנַי, דְּבֵלָה II, דַּבְלוּל, דּוּת, דּוֹפַן; Daniel Aramaic left in דַּחִוָן, דָּחַל; uncertain lines in גִּיהַּ I–II, גִּיחַ I, גִּעְגּוּעַ, דְּחִיפָה, דָּחַל, דִּיב, דָּחִיק, דָּיוֹן.
- T154: readings to check — חו"ה → Chovot ha-Levavot (דְּבָרִי), ר"ל → Resh Lakish (גַּלְמוּד), "from jasper" (גָּלַף I), "day 2"/"day 7" for יום ב/יום ז in selichot, the Seder ha-Chakhamim date (דֻּגְמָה); words left in Hebrew in דַּבֶּשֶׁת, דָּלַח, גֹּלֶף, גַּלְעִין, גָּפַס, גַּפָּה, דִּגְדּוּג, גָּרָב I, דְלוּעִי, גָּפַף, דֻּבְשָׁן, גֵּפְתָּן, גְּלִילָה; misprinted glosses kept in גַּלְמוּד, גֶּפֶת, דְּלוּס, דַּבֶּשֶׁת; Aramaic left in גָּרָב III, גֵּץ I; a long note printed and translated three times in גָּלַע; uncertain piyyut in גָּלַע, הִגְלִיעַ, גִּפּוּף I, דְּגִילָה, דִּלָּיוֹן.
- T156: expansions to check — או"נ → Otzar Nechmad (גָּרַס I), עמה"מ → Emek ha-Melekh (דִּמְדּוּם), "הרוני'" → Jerome (דּוּכִיפַת), "ש"א ו." → 1 Samuel 6 (גְּרָרָה II); "Luxuriance; -ancy" labelled French/English (דָּמָךְ); kept as printed though odd — 25:15 after Proverbs (גֶּרֶם); words left in Hebrew in גְּנֹגֶנֶת, גְּנוֹנָה, גְּרִישָׁה, גְּרָמָה, גָּרַס II, דּוּכִיפַת, דּוּמָה, דּוֹפֵק I, דִּמְדּוּם, דַּלְתוֹת, דִּמְיוֹנִי, דִּמּוּעַ; angelic letter strings left in דּוּמִיאֵל.
- T155: expansions to check — תוספת' שבת נט. → Tosafot Shabbat 59a (גָּמַע), א"ד → "some say" (גָּשִׁישׁ), רע"ג → Rav Amram Gaon (דְּאָבוֹן), ב"ז → Ben-Ze'ev (דַּאֲבָה), לקו"ק → Likkutei Kadmoniyot (דַּקְדְּקָן), שורץ → Schwarz (גִּמֵּז), גרמנץ → "Gramnitz fair" (דַּיָּנוּת); words left in Hebrew in גִּמּוֹן I, גָּמַם, גָּמַע, גָּמַץ, גַּשְׁמוּת, גִּשֵּׁשׁ, דַּיְתּוּת, דָּכְיָה, דָּפַן I, דַּפְקָנִי, דֹּק I, דַּקָּה II, גֹּמִיָּה, דַּף; some Aramaic left in דַּיִס, דִּיֵּת, גַּמְלוֹן, דָּפַן II; misprinted glosses kept; a note printed and translated three times in דְּפוּס.
- T157: expansions to check — חמה"י → Chemdat ha-Yamim, מא"ג/רמא"ג → M. A. Ginzburg (Günzburg elsewhere), רומני → Romaniote, רמב"ח → R. Moses b. Chaviv; numbered cross-references (ב. גרם) rendered a./b./c. (T140 rendered them as numbers); kept as printed though odd — Shabbat 22:6 and a missing negative (גרד I, II), year 5510 (דפס), a garbled Terumot reference (דהה); words left in Hebrew in גרד I, גרדום I, דוגית, דודא, דוך, דווי, דפס, דקדק III, דקדוק I, גרגרן, הדסי; uncertain verse in דודא, דהר, הדף, הדרניאל.
- T159: expansions to check — שבי"ע → Shevilei Olam, ת"ע → the Septuagint (הֲלֹם), ע"ח → Etz Chaim and ג"ע → Gan Eden of Aaron the Karaite, לאזינו → Lasinio (הטעאי), רמב"ע → Moses Ibn Ezra, ריב"ג → Ibn Tibbon or Ibn Janah by context, מאמ' השכל → Ma'amar HaSekhel; "imposition" labelled "French and English" (הטלה); kept as printed though odd — three-number Yerushalmi references (הטחה), "Sukkah 1 52b" and "Peah 8 21a" (דקדק), misspelled glosses; words left in Hebrew in דקות, הטעאה, דוקרן, הילול, הברה, הלוכה, דֶּקֶר; literal verse in הדקיר, החויה, היד, הילול, הילום, הטיה, הָלַם I.
- T158: expansions to check — שבי"ע → Shevilei Olam, אד"ם שש"ק → Adam HaCohen, Shirei Sefat Kodesh, מא"ג → M. A. Günzburg, תו"ט לאברמ' → Toldot HaTeva of Abramowitsch, ר"ש בר"ש → "R. S. son of R. S."; kept as printed though odd — Joshua 59:8 and "ibid. 64:4" (דָרַךְ), "ibid. Psalms 90" (הֵיכָן I), "ibid. 155b" (הַמְרָאָה II); words left in Hebrew in דָּמַךְ, דָּנָב, דְּרָשָׁה, הָמַן, הֵיכָן I, הִיג, הַמְרָאָה I, הַמְעָדָה, דָּעַץ; uncertain lines in הַמְרָצָה, דִּשְׁנִי, הֶמֶס I.
