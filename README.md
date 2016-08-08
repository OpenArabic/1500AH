# 1500AH [[ [Re]generated on 2016-08-08 (14:00:57) ]]

* `1405CaliShahrudi.Mustadrakat (TAGS: CENT1500,PPE,SHC,_HADITH,_SHICI,_TARAJIM)`
* `1408CumarKahhala.MucjamMuallifin (TAGS: BIB,BIO,CENT1500,COL,PPE,_FAHARIS,_KUTUB,_TABAQAT,_TARAJIM)`
* `1408CumarKahhala.MucjamQabail (TAGS: CENT1500,COL,GEN,PPE,_ANSAB,_MACAJIM)`
* `1411SayyidKhui.MucjamRijal (TAGS: CENT1500,PPE,_HADITH,_SHICI,_TARAJIM)`
* `1411SayyidMarcashi.SharhIhqaq (TAGS: CENT1500,_CAQAID,_SHICI,_TWELVERS)`
* `1414SalimIbadi.IscafAcyan (TAGS: CENT1500,_ANSAB)`
* `1418SalihAhmadArkani.TihfaMajalis (TAGS: BIB,CENT1500,PPE,_FAHARIS,_KUTUB)`
* `1419MahmudTanahi.MujizFiMarajic (TAGS: BIB,CENT1500,PPE,_ADILLA,_FAHARIS,_KUTUB)`
* `1421HamdJasir.MucjamQabailMCS (TAGS: CENT1500,_ANSAB)`
* `1422MuhammadSalimMuhaysin.MucjamHuffazQuran (TAGS: CENT1500,PPE,_TABAQAT,_TARAJIM)`
* `1429BakrIbnCabdAllah.TabaqatNassabin (TAGS: CENT1500,_TABAQAT,_TARAJIM)`
* `1450AkramFaluji.MucjamSaghir (TAGS: CENT1500,_TABAQAT,_TARAJIM)`
* `1450CabdRahmanAlShaykh.Mashahir (TAGS: CENT1500,PPE,_TABAQAT,_TARAJIM)`
* `1450MuhammadHadiAmini.MucjamMatbicatNajafiya (TAGS: BIB,CENT1500,PPE,_FAHARIS,_KUTUB)`
* `1450MuhammadKhayrRamadan.TakmilaMucjamMuallifin (TAGS: BIB,CENT1500,COL,PPE,_TABAQAT,_TARAJIM)`
* `1450MuhammadSancani.NaylWatar (TAGS: BIO,CENT1500,COL,ORPHAN,PPE)`


# General description of the workflow with mARkdown

0. Have GitHub installed and setup on your computer.
1. Clone repositories.
2. Work from earliest to latest.
3. Make sure that nobody else is editing the text that you chose; to avoid that keep me posted on text you are planning to work with. (**NB**: if there is a file with extension `.mARkdown`, it means that somebody is working on that text!)
4. In most cases there are multiple versions of the same text; you need to identify relevant editions and do a preliminary evaluation.
5. Ideally,  you should be able to find a text that corresponds to an edition,  which you can access (scans of most editions can be found online; links to some editions can be found in the PDF folder in text repositories; if there are links in `urls.txt`, they can be downloaded in batch using `wget`). 
6. It is likely that there will be more than one text based on the same edition. `Shamela` texts are often improved versions of `JK` texts (with more tags already in place);  it makes sense to compare the number of tags already in place and choose the text that will require less time to finish. Keep in mind that there is no solid rule about which text is likely to be better; you need to evaluate them all.
7. Only one text should be converted into `mARkdown`—the text that according to your evaluation is of better/best available quality. Make sure to record your observations on each text file into a `README.md` file in the folder with the text group you are working on (answer the questions that are in the `README.md` file).
 		* **NB**: If your research focuses on specific texts, you may want having multiple editions converted into `mARkdown`; this will allow to compare how editions are different from each other.
8. When you selected the text that you will be converting to `mARkdown`, work with the copy of that text file. The file name of that copy should retain the `URI` + `.mARkdown` (period + mARkdown,  where the second and third letters are capitalized!). For example, `0310Tabari.Tarikh.JK000157-ara1` > `0310Tabari.Tarikh.JK000157-ara1.mARkdown`
		* **NB** by default, Windows hides file extensions, so you will need to change some settings so that they are displayed. *How to do that*: 1) Open `File explorer` (Win+E); 2) press `F10` to see the menu; 3) in the menu: `Tools` > `Folder options`; then choose tab `View`; then uncheck `Hide extensions for known file types`; 4) Click `Apply to Folders`, then `Ok`.
9. Keep in mind that you need to tag only the structure of a book you are working with,  which includes tagging chapter headers (`### |`, `### ||`, `### |||`, etc.) and major information units, like biographies (`### $`, `### $$`, `### $$$`, etc.) or lexicon items (these we should discuss before you start). Please, do not tag anything else—at least without consulting first with me.
10. **NB!** Do not delete anything from the text! At this point we do not know what is valuable and what is not (things like numbers, random characters, punctuation, stray HTML tags, etc.). Your goal is **to provide the structure** to texts, **not to edit** them. If you think something should be deleted, please, consult me first. Time is the most valuable asset at the moment and we cannot afford to spend it on fixing messed-up texts; we want to invest it into tagging new texts.
10. Make commits to relevant github repositories after each working session. In addition to saving/backing up your work, this will also allow me to check periodically on your progress and make suggestions along the way.
11. In the same `README.md` file add the number of hours it took you to process the file. We are trying to get estimates on how much time it is going to take to process the entire corpus; we also know at the moment that the amount of time is not proportional to the length of a text, since what matters most is how much structural information is preserved in the initial file and that differs drastically from text to text.

These are the major steps.  Please, do not hesitate to contact the me if you have any questions, no matter how insignificant they may seem to you.

