# Budhót'n

Umělý jazyk na bázi slovanských jazyků s velmi komplexním repertoárem fonémů. 6. verze.

+ **Budhót'n.xslx** - původní Excel 2007+ tabulka s abecedou, gramatikou, slovníkem atd.
+ **budhotn.csv** - strojově čitelný slovník, přímo zde vyhledávatelný (~7000 řádků)

Vytváří [classroomtoilet](https://classroomtoilet.cz/), udržuje [637man](https://getmania.blogspot.com/).


## Kterak psáti znaky nabodlé

Budhót'n byl vymyšlen pro českou klávesnici. Ta má ve Window$ na AltGr (pravý Alt) a číselné řadě různé mrtvé klávesy, o nichž řada uživatelů pravděpodobně neví. V Linuxu je nutné použít Shift+AltGr, neboť AltGr na číselné řadě přeřazuje na symboly z americké klávesnice. Macintosh ani Amigu nikdo z autorů nemá, takže nemůže ověřit.

    Příklad: ~ ã â â ă å ą à ȧ á ő ä ç
    AltGr:   ~ ~ ˇ ^ ˘ ° ˛ ` ˙ ' ˝ " ¸
    Shift:   ° 1 2 3 4 5 6 7 8 9 0 % ˇ
    Běžně:   ; + ě š č ř ž ý á í é = ´
    
          Základ                        Shift                     Linux AltGr              Linux Shift+AltGr
    q w e r t z u i o p ú )     Q W E R T Z U I O P / (     \ | € ¶ ŧ ← ↓ → ø þ [ ]     Ω Ł E ® Ŧ ¥ ↑ ı Ø Þ ÷ ×
    a s d f g h j k l ů § "     A S D F G H J K L " ! '     ~ đ Đ [ ] ` ' ł Ł $ ' \     Æ § Ð ª Ŋ Ħ ̛  & Ł ˝ ß |
     y x c v b n m , . -         Y X C V B N M ? : _         ° # & @ { } ^ < > *         < > © ‘ ’ N º × ÷ ˙

Mrtvá tečka nahoře se chová zvláštně v případě I: ı a İ. Dále jsou na české klávesnici méně obskurní mrtvá tlačítka na kroužek (Shift+;), čárku (vedle Backspace), háček (Shift+´) a přehlásku. Přehláska je na té klávese, která je pokaždé někde jinde poblíž Entru/Return/<-', a pod Shiftem se na ní ukrývá apostrof. Ohledně zbylých nabodlých znaků je ještě důležité připomenout, že:
* na AltGr+K se nachází ł,
* na AltGr+L se nachází Ł,
* na AltGr+S se nachází đ,
* na AltGr+D se nachází Đ,
* na AltGr+P se nachází þ,
* na Shift+AltGr+P se nachází Þ,
* na AltGr+O se nachází ø,
* na Shift+AltGr+O se nachází Ø,
* na AltGr+T se nachází ŧ, a
* na Shift+AltGr+T se nachází Ŧ.

Na linuxové americké mezinárodní klávesnici lze napsat àãőçâơąăåạáäȧǎả þßðœøæµ ŁŦ¥ıØÞÆÐŊĦº.
