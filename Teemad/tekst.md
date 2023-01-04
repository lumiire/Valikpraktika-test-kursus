# Tekst

Teksti on meie ümber üha rohkem. Me toodame ise teksti tekstitöötluses ja muudes rakenduses. Internet on teksti täis, klassikud ja tüvitekstid on laialt ja tasuta kättesaadavad. Võimalusi tekstide hankimiseks on peaaegu lõputu.

Teksti saab mitut moodi defineerida. Teksti töötlusemiseks arvutiga võime aga lihtsustamiseks alustada sellest, et tekst on tähemärkide jada. Tekstitöötlusprogrammide failid sisaldavad lisaks tekstisisule ka vorminguks vajalikke koode, ent alati saab seda ka eksportida “puhta tekstina”.

Teeme selle illustreerimiseks katse. Teeme uue faili tekstitöötlusprogrammis (nagu Microsoft Word või LibreOffice.org).  Kirjutame sinna järmise rea:

Me hoiame nõnda ühte.

Salvestame selle kõigepealt näiteks docx vormingus. Faili täpne suurus sõltub programmist ja versionist, minul tuli näiteks 4425 baiti. Selline fail sisaldab palju lisaks tekstisisule ka palju muud infot mis kuulub failivormingu juurde. 

Meie tahame aga puhta tekstiga tegeleda. Selleks tuleb failivorminguks valida txt. Kui programm võimaldab ka valida kooditabelite vahel, siis valime UTF8. 

Eeldame, et meil on nüüd fail nimega nagu yhte.txt järgmise sisuga

Me hoiame nõnda ühte.

Selle faili suurus on palju väiksem – väikeste tehniliste variatsioonidega on faili suurus nüüd tähemärkide arv. Võime ette kujutada, et faili sisu on selline numbrite jada: 

77 101 32 104 111 105 97 109 101 32 110 245 110 100 97 32 252 104 116 101 46 https://sisu.ut.ee/unixtekst/mis-arvutis-tekst

Siin on ASCII (ja UTF8) jaoks täht M tähistatud numbriga 77, täht e numbriga 101 ja nii edasi. Muidugi ei ole nad tegelikult päris sellisel kujul salvestatud, sest arvuti kood on binaarne – kas null või üks. Üks bait on kaheksa binaarset numbrikohta. Arvuti jaoks on sama tekst umbes järgmisel kujul: 

01001101 01100101 00100000 01101000 01101111 01101001 01100001 01101101 01100101 00100000 01101110 11110101 01101110 01100100 01100001 00100000 11111100 01101000 01110100 01100101 00101110

Kui edaspidi räägime tekstifailidest, käib jutt niisiis puhtast tekstist. Siis saame aru, et tekstifail on olemuselt lihtne: algusest lõpuni numbrite jada, kus iga bait üldjuhul tähistab ühte tähemärki. Tähemärkideks on lisaks tähtedele, numbritele ja kirjavahemärkidele näiteks tühikud ja tabulaatorid. Kui teame kuidas puhta tekstina salvestada, saame seda töödelda paljude erinevate programmidega, sellest sõltumata, millises programmis tekst on loodud.
