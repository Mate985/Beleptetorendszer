# Mikroelektromechanika
Széchenyi István Egyetem - Mikroelektromechanikai rendszerek Vizsgafeladat

Készítette: Kránitz Ferenc Máté

Neptun kód: BMXQYQ

Dátum: 9200 Mosonmagyaróvár, 2022.12.17

Tantárgy: Mikroelektromechanikai rendszerek (GKLB_INTM020)

Feladat: Vizsgafeladat

Tisztelt Olvasó! 

Ebben a leírásban szeretném ismertetni a projektemet. Egy beléptető rendszert készítettem, melynek működési elve abban rejlik, hogy amikor a megfelelő kártyát érintem az olvasó elé, akkor a szervó 30 fokos szögben elfordul, ezzel demonstrálva egy ajtó nyitását.
Egy Arduino UNO, egy MFRC522 RFID modul, egy MS/SG-90 Mikro szervó valamint egy Próbapanel és néhány szalagkábel volt a segítségemre.
Az MFRC522-es modult megforrasztottam, így stabilan bele lehetett tűzni a lábainál a próbapanelba. Ezután bekötöttem a szervót és az RFID modult az Arduino UNO-ba és ezt rákötöttem a számítógépre.
Először a DumpInfo segítségével a Kulcs és Kártya UID-kat kiolvasva a programomba ezeket hexadecimálisan beleírva lefordíttattam, majd feltöltöttem az Arduino-ra. 
A megírt program tökéletesen működik és a valós életben is megtudná állni a helyét.

Köszönöm megtisztelő figyelmét!

Tisztelettel:

Kránitz Ferenc Máté
