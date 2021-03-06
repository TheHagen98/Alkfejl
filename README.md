# Alkfejl
# Leírás:

Egy bevásárló listákat kezelő és házhozszállítási funkcióval rendelkező program, amiben a regisztrált felhasználó szabadon hozhat létre új listát, szerkesztheti, és elmentheti kedvenc üzleteit, árucikkeit. Amennyiben a felhasználó még nem véglegesítette rendelését, adhat hozzá új tételeket, vagy törölheti is akár magát a listát. Véglegesítés után azomban már nem szerkesztheti. Kiszállítás után lehetősége adódik jelezni hogy az árucikkek megfelelően megérkeztek-e vagy sem.

# Funkcionális követelmények:



* Regisztráció

* Belépes

* Bevásárlólista létrehozása

* Bevásárlólista szerkesztése

* Bevásárlólista törlése

* Bevásárlólista listázása (Boltban / Kiszállítás alatt / Kiszállítva)

* Bevásárlólista véglegesítése



* Termékek kedvencekbe tétele

* Boltok kedvencekbe tétele



* Áruk és boltok megtekintése (Regisztráció nélkül is)



* Felhasználók blokkolása (Adminként) [Ha sokszor nem veszi át a temréket]





 # Nem funkcionális követelmények:


 * Felhasználóbarát, letisztult felület

 * Jelszavas azonosítás
 
 * Jelszavak biztonságos tárolása

 * Keresési eredmények gyors megjelenítése



# Szerepkörök


## Vendég: 
* Nem regisztrált látogató

* Megtekintheti a boltok és termékek listáját

## Tag: 
* Regisztrált és bejelentkezett látogató

* Megtekintheti a boltok és termékek listáját

* Bevásárlólistát hozhat létre, módosíthat, törölhet, véglegesíthet

* Hozzáadhatja a boltokat és árukat a kedvencekhez

## Admin:
* Blokkolhat egy felhasználót

# Szakterületi fogalomjegyzék

* Áru: A bevásárlólista elemei, bolti áruk

* Bolt: Áruk találhatók benne, egy kiszállítócég tartozik hozzá

* Bevásárlólista: A felhasználó által létrehozott lista amelyen található áruk kiszálításra kerülnek

# Táblák
![Image of Yaktocat](https://github.com/TheHagen98/Alkfejl/blob/master/vJPEG.jpg)

# Flowchart
![Image of Yaktocat](https://github.com/TheHagen98/Alkfejl/blob/master/flowchat.png)

# Usecase
![Image of Yaktocat](https://github.com/TheHagen98/Alkfejl/blob/master/Use-Case.png)

# Fejlesztői környezet beállítása:
## Dependenciák:

* org.springframework.boot

* com.h2database

* org.projectlombok

* org.junit.vintage

## Használt technológiák:

* Java

* Spring

* Lombok

* Maven

* SQL

* Angular

* Bootstrap


