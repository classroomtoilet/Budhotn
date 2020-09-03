# Budhót'n

Umělý jazyk na bázi slovanských jazyků s velmi komplexním repertoárem fonémů. 6. verze.

+ **Budhót'n.xslx** - původní Excel 2007+ tabulka s abecedou, gramatikou, slovníkem atd.
+ **budhotn.csv** - strojově čitelný slovník, přímo zde vyhledávatelný (~7000 řádků)
+ **README.md** - tento informační soubor


## Kontakty

Budhót'n vytváří [classroomtoilet#2074](https://classroomtoilet.cz/), repozitář udržuje [637man#2338](https://getmania.blogspot.com/).

[Skupina na Facebooku (aktualizace Budhót'n.xlsx)](https://www.facebook.com/groups/261329611863060)

[Stránka blogu classroomtoilet.cz na Facebooku](https://www.facebook.com/classroomtolet) \[sic\]

[Tento GitHub repozitář](https://github.com/classroomtoilet/Budhotn/)

Skupina na Discordu (spojená s autorovým blogem): classroomtoilet.cz

E-mail: classroomtoilet (å) classroomtoilet ˙ cz


## Kterak psáti znaky nabodlé

Budhót'n byl vymyšlen pro českou klávesnici. Ta má ve Window$ na AltGr (pravý Alt) a číselné řadě různé mrtvé klávesy, o nichž řada uživatelů pravděpodobně neví. V Linuxu je nutné použít Shift+AltGr, neboť AltGr na číselné řadě přeřazuje na symboly z americké klávesnice. Macintosh ani Amigu nikdo z autorů nemá, takže nemůže ověřit.

  AltGr: | ~ | ~ | ˇ | ^ | ˘ | ° | ˛ | \` | ˙ | ' | ˝ | " | ¸
:--- | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---:
Příklad: | ~ | ã | ǎ | â | ă | å | ą | à | ȧ | á | ő | ä | ç
  Shift: | ° | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | % | ˇ
  Běžně: | ; | + | ě | š | č | ř | ž | ý | á | í | é | = | ´

Na Window$ jsou omezenější možnosti nabodávání než na Linuxu. Rovněž nefunguje prstolamné Ctrl+Shift+U. [DOSový zlozvyk levého Altu](https://en.wikipedia.org/wiki/Alt_code) umožňuje pouze DOS Latin a s úvodní 0 Window$ Latin (>255 funguje v závislosti na aplikaci), pokud není HKEY_CURRENT_USER\Control Panel\Input Method\EnableHexNumpad == "1", to pak umožňuje použití úvodního + a je hexadecimální. Nicméně naštěstí všechny nabodlé znaky Budhót'nu na Windows bez mapy znaků napsat jdou, neboť autor, jsouc omezen tímto obstarožním systémem, nepoznal mocnou sílu pravideně aktualizovaných [skladných sekvencí X11](https://cgit.freedesktop.org/xorg/lib/libX11/plain/nls/en_US.UTF-8/Compose.pre).

          Základ                        Shift                     Linux AltGr              Linux Shift+AltGr
    q w e r t z u i o p ú )     Q W E R T Z U I O P / (     \ | € ¶ ŧ ← ↓ → ø þ [ ]     Ω Ł E ® Ŧ ¥ ↑ ı Ø Þ ÷ ×
    a s d f g h j k l ů § "     A S D F G H J K L " ! '     ~ đ Đ [ ] ` ' ł Ł $ ' \     Æ § Ð ª Ŋ Ħ ̛  & Ł ˝ ß |
     y x c v b n m , . -         Y X C V B N M ? : _         ° # & @ { } ^ < > *         < > © ‘ ’ N º × ÷ ˙

Mrtvá tečka nahoře se chová zvláštně v případě I: ı a İ. Dále jsou na české klávesnici méně obskurní mrtvá tlačítka na kroužek (Shift+;), čárku (vedle Backspace), háček (Shift+´) a přehlásku. Přehláska je na té klávese, která je pokaždé někde jinde poblíž Entru/Return/<-', a pod Shiftem se na ní ukrývá apostrof. Na linuxové americké mezinárodní klávesnici s AltGr mrtvými tlačítky nelze napsat đ, Ł a ł, jen ð a £. Kompletní seznam všech nabodlých písmenek:

Písmeno | Klávesy | Unicode
--- | --- | ---
Á á | 8 / AltGr+9,A | U+00C1 U+00E1
À à | AltGr+7,A | U+00C0 U+00E0
Â â | AltGr+3,A | U+00C2 U+00E2
Ă ă | AltGr+4,A | U+0102 U+0103
Å å | AltGr+5,A | U+00C5 U+00E5
Ą ą | AltGr+6,A | U+0104 U+0105
Ć ć | ´,C | U+0106 U+0107
Č č | 4 / Shift+´,C / AltGr+2,C | U+010C U+010D
Ď ď | Shift+´,d / AlrGr+2,D | U+010E U+010F
Đ đ | AltGr+D (malé AltGr+S) | U+0110 U+0111
Ë ë | ¨,E / AltGr+=,E | U+00CB U+00EB
É é | 0 | U+00C9 U+00E9
È è | AltGr+7,E | U+00C8 U+00E8
Ê ê | AltGr+3,E | U+00CA U+00EA
Ğ ğ | AltGr+4,G | U+011E U+011F
Ï ï | ¨,I / AltGr+=,I | U+00CF U+00EF
Í í | 9 | U+00CD U+00ED
Ì ì | AltGr+7,I | U+00CC U+00EC
Î î | AltGr+3,I | U+00CE U+00EE
Ĺ ĺ | ´,L / AltGr+9,L | U+0139 U+013A
Ľ ľ | Shift+´,L | U+013D U+013E
Ł ł | AltGr+L (malé AltGr+K) | U+0141 U+0142
Ń ń | ´+N / AltGr+9,N | U+0143 U+0144
Ň ň | Shift+´,N / AltGr+2,N | U+0147 U+0148
Ö ö | ¨,O / AltGr+=,O | U+00D6 U+00F6
Ó ó | ´,O | U+00D3 U+00F3
Ô ô | AltGr+3,O | U+00D4 U+00F4
Ő ő | AltGr+0,O | U+0150 U+0151
Ŕ ŕ | ´,R / AltGr+9,R | U+0154 U+0155
Ř ř | 5 / AltGr+2,R | U+0158 U+0159
Ś ś | ´,S | U+015A U+015B
Š š | 3 / AltGr+2,S | U+0160 U+0161
Ť ť | Shift+´,T / AltGr+2,T | U+0164 U+0165
Ü ü | ¨,U / AltGr+=,U | U+00DC U+00FC
Ú ú | Ú / AltGr+9,U | U+00DA U+00FA
Ù ù | AltGr+7,U | U+00D9 U+00F9
Û û | AltGr+3,U | U+00DB U+00FB
Ů ů | Ů / AltGr+5,U | U+016E U+016F
Ų ų | AltGr+6,U | U+0172 U+0173
Ű ű | AltGr+0,U | U+0170 U+0171
Ÿ ÿ | ¨,Y / AltGr+=,Y | U+0178 U+00FF
Ý ý | 7 / AltGr+9,Y | U+00DD U+00FD
Ż ż | AltGr+8,Z | U+017B U+017C
Ź ź | ´,Z / AltGr+9,Z | U+0179 U+017A
Ž ž | 6 / AltGr+ě+Z | U+017D U+017E
