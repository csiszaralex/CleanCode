3 fajtára bontható:
    Változók és tulajdonságok (properties)
    Funkciók és metódusok
    Osztályok

A neveknek jelentőségteljeseknek kell lennie

Miért számítenak a nevek?
Példa (asd vagy isLoggeIn)

Név típúsok:
    snake_case: Pl Python (is_valid)
    camelCase: Pl JavaScript (isValid)
    PascalCase: Pl Python és JS osztályok (UserRepository)
    kebab-case: Pl HTML (side-drawer)

Változó:
    Általában Főnév vagy melléknév
    Példa: Egy felhasználó
        Rossz: u
        Elfogadható: person
        Jó: user

Funkciók:
    Általában ige vagy melléknév
    Példa: Felhasználó adatainak mentése
        Rossz: process()
        Elfogadható: save()
        Jó: saveUser()

Osztályok:
    Álltalában főnév
    Példa: Felhasználó:
        Rossz: ObjA
        Elfogadható: AppUser
        Jó: User

Ne tárolj felesleges információkat
    Pl: userWithNameAndAge

További kerülendő:
    szleng:
        Rossz: products.diePlese()
        Jó: products.remove()
    Nem egyértelmű rövidítés:
        Rossz: ymdt = '20210129CET'
        Jó:dateWithTimeZone = '20210129CET'
    Félrevezető:
        Rossz: allAccounts = accounts.filter()
        Jó: FilteredAccounts = accounts.filter()

Használjmegkülönböztethető neveket
    Pl: Ugyan az a függvény a napi adat lekéréséhez és a mai adathoz
        Rossz: analitycs.getDailyData(day) --> Napi adat
               analitycs.getDailyData() --> Mai adat
        Jó: analitycs.getDailyData(day) --> Napi adat
            analitycs.getDataForToday() --> Mai adat
