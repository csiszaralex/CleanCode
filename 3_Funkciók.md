Minimalizáld aparaméterek számát
    Inkább objektum, mint sok adat

Lehetőleg ne legydnen visszatérési értéke
Minnél több, és kisebb függvény
Minden függvény csak 1 dolgot csináljon
    Azonos bemenet esetén mindig legyen ugyan az a kimeneti érték
    Ne legyen mellékhatása
        Kivéve ha szükséges: ekkor erre a neve is utaljon

Magas és alacsony szintű függvények
    Pl.:
        Alacsony szintű: email.includes('@')
            Mi kontrolálhatjuk, hogyan validáljuk az email címet
        Magas szintű: isEmail(email)
            Nem mi kontroláljuk, hogyan validáljuk
            Könnyebben értelmezhető
    A két típus lehetőleg ne keveredjen

Ne ismételdmagad, inkább használj fel egy függvényt többször

Írj teszteket