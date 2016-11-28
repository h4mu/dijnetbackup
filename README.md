# dijnetbackup
Mentsd le a Díjnet számláidat amíg még ingyen megteheted!

Használat:

 1. Szükséged lesz a [Firefox böngészőre](https://www.mozilla.org/firefox/new/?scene=2)
 2. Telepítsd a [Selenium IDE bővítést](http://docs.seleniumhq.org/download/#selenium_ide) a Firefox böngésződben
 3. Telepítsd a [sideflow plugint](https://github.com/73rhodes/sideflow) a Selenium-hoz
 4. Töltsd le a [dijnetbackup szkriptet](https://github.com/h4mu/dijnetbackup/raw/master/dijnet_selenium.html)
 5. Nyisd meg a Seleniumban
![Open](https://github.com/h4mu/dijnetbackup/raw/master/pic/a_open.png)
![Select File](https://github.com/h4mu/dijnetbackup/raw/master/pic/b_open.png)
 6. A böngészőben nyisd meg a [Díjnet oldalát](https://www.dijnet.hu)
 7. Jelentkezz be
 8. Nyiss meg egy számlát amihez a "Letöltés" fülnél van "Hiteles számla"
![e-Szignó](https://github.com/h4mu/dijnetbackup/raw/master/pic/c_hiteles.png)
 9. Telepítsd az onnan letölthető e-Szignó programot
 10. Nyisd meg a böngésző beállításaiban  az Alkalmazások fület (pl. írd be a címsorba, hogy about:preferences#applications), és állítsd át a pdf, es3 és xml formátumok kezelését letöltésre, így a szkript nem fog minden fájl megnyitásakor rákerdezni, hogy mit csináljon vele
![Mentés](https://github.com/h4mu/dijnetbackup/raw/master/pic/d_mentes.png)
 11. Menj vissza a Díjnet oldalára, nyisd meg az egyik baloldali fület, hogy lásd, hogy be vagy-e még jelentkezve, ha nem, jelentkezz be
 12. Indítsd el a szkriptet Seleniumban
![Play](https://github.com/h4mu/dijnetbackup/raw/master/pic/e_play.png)
 13. Várj...
 14. Profit

> Written with [StackEdit](https://stackedit.io/).