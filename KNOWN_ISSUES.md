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
