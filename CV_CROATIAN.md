# Životopis
 - **Mario Fatiga**
 - Jurketinec, 42243 Maruševec, Hrvatska
 - rođen 30.01.1988.


# Linkovi
[GitHub](https://github.com/mfatiga/)

[LinkedIn](https://www.linkedin.com/in/mario-fatiga-9198b435/)

[exercism](https://exercism.org/profiles/mfatiga)

[500px](https://500px.com/p/mfatiga)


# Uvod
 - arhitekt softverskih sustava, programer koji ne ovisi o programskom jeziku, voditelj tima
 - volim tražiti rješenja za sve vrste problema u bilo čemu što je povezano s tehnologijom
 - počeo s programiranjem 1996. s QBasicom na PC-u i Basicom na ZX Spectrumu
 - vrlo dobro poznavanje širokog spektra programskih jezika
 - veliki interes za sve što je povezano sa softverom i hardverom
 - veliki interes za sve aspekte tehnologije i znanosti
 - vrlo dobro poznavanje i razumijevanje elektronike i protokola ugradbenih sustava
 - Korisnik Linuxa - koristim NeoVIM za većinu razvoja ili Android Studio s VIM kraticama za Android
  - hobiji uključuju: sintisajzere, vožnja simulatora utrkivanja, letenje FPV dronom, Smart Home sustave, fotografiju itd.

# Radno iskustvo

## [03.2016. do sada] Softverski inženjer/arhitekt - SIL d.o.o, Varaždin, Hrvatska
 - dizajner rješenja IOT sustava baziranog na Linuxu, uglavnom razvijenom u Pythonu
 - programer i dizajner rješenja na brojnim softverskim bibliotekama i aplikacijama
 - arhitekt sustava na više projekata uključujući backend, firmware i arhitekturu mobilnih aplikacija

### Sustav za upravljanje i kontrolu entiteta iz resursa, bazirano na ZeroMQ:
 - dizajner softversog rješenja, glavni programer (Python, ZeroMQ, ...)
 - Python Linux sistemski servisi
 - generičko rješenje za kontrolu i upravljanje bilo koje vrste softverskog ili hardverskog resursa pomoću jednostavnog i moćnog API-ja
 - integrirano generičko RPC rješenje za pozive na unarne funkcije i tokove s mogućnošću lakog dodavanja novih implementacija resursa
 - lako proširiva podrška za više protokola (ZeroMQ, Websockets, ...)
 - kontrola i upravljanje distribuiranim resursima
 - automatski generirani API i dokumentacija

### Linux sustav za pametne sandućiće:
 - dizajner softverskog rješenja, glavni programer (Python, Redis, ...)
 - Python Linux sistemski servisi koje kontroliraju različite vrste vanjskog/internog hardvera/softvera
 - uglavnom se koristi za upravljanje vanjskim povezanim elektroničkim regulatorima brave
 - usluge komunikacije i zajedničke pohrane implementirane pomoću Redis-a
 - za lokalno pokrenut web server pruža API koji se temelji na REST-u i websocket-ima
 - sastoji se od preko 20 interno razvijenih programskih biblioteka, uključujući:
   - Python OpenAPI generator klijenta - generira python klijentski modul na temelju OpenAPI.json opisa REST servisa
   - PyRedisMQ - generički redovi poruka bazirani na redis-listi s podrškom za RPC (unarni i generatorski tokovi)
   - PyRedisLock - centralno zaključavanje dijelnjenih resursa pomoću automatskog isteka Redis ključa

### Android kiosk aplikacija za pametne sandućiće:
 - dizajner softverskog rješenja, glavni programer (Kotlin)
 - kontrola lokalnih i udaljenih (BLE) elektroničkih brava i poslovna logika vezana uz njih

### "Multiple parcel locker" / "Single parcel locker" / "SeeUS" - softverska rješenja za ugradbene sustave:
 - dizajner softverskih rješenja, arhitekt high-level hardverskog rješenja, glavni programer firmwarea (C++)
 - korištenje Mbed OS-a kao RTOS i HAL sloj iznad hardvera
 - korištenje STM (kontrola) i Nordic (BLE) mikrokontrolera
 - više revizija hardvera, do 4 istovremeno pokrenuta mikrokontrolera s različitim odgovornostima
 - hardver s ultra-niskom potrošnjom energije i optimizirani firmware s ultra-niskom potrošnjom
 - UART komunikacija optimizirana za nisku potrošnju energije pomoću inicijalizacije UART-a temeljene na zahtjevu-po-potrebi
 - rješenje za pohranu dinamičkih grupa malih objekata za male permanentne memorije - EEPROM (4-16 kilobajta)
 - algoritam za rezerviranje većih blokova memorije u jako fragmentiranom RAM-u
 - algoritam za usporedbu, spajanje, i pisanje (SPI) slika na ePaper
 - ideja i djelomično rješenje za DMA audio reprodukciju iz flash memorije s MP3 stream dekodiranjem

### "Smart Letterbox" Android aplikacija:
 - dizajner softverskog rješenja, glavni programer (Kotlin)
 - BLE (bluetooth low energy) skeniranje i komunikacija sa BLE uređajima

### "Civitavecchia" Android aplikacija:
 - [link](https://play.google.com/store/apps/details?id=hr.sil.civitavecchia)
 - arhitekt i programer (Kotlin)
 - turistička vodič-aplikacija za traženje i lov na točke interesa
 - detekcija BLE uređaja i odgovarajuće akcije u aplikaciji

### "Paketbox" Android aplikacija:
 - [link](https://play.google.com/store/apps/details?id=hr.sil.android.paketbox.user)
 - glavni programer (Kotlin)
 - aplikacija za kontrolu pametnih sandućića i dijeljenje ključa
 - BLE

### "Beacon Configurator" i "SilwareBullet" Android aplikacije:
 - dizajner softverskog rješenja, glavni programer (Kotlin)
 - interne aplikacije koje se koriste za konfiguriranje, analizu i otklanjanje pogrešaka ugradbenih sustava temeljenih na BLE-u
 - puno različitih funkcionalnosti uključujući generičko testiranje BLE komunikacije, GPS praćenje, crtanje parametara uživo, dinamičku izgradnju korisničkog sučelja na temelju informacija o podatkovnom protokolu BLE uređaja, itd.

### ESP8266 Arduino baziran WiFi na UART proxy
 - dizajner rješenja i programer (C++)
 - IOT WiFi na UART proxy
 - Arduino okruženje, protokol iznad TCP-a


## [03.2014. do 03.2016.] Softverski inženjer/arhitekt - Končar INEM d.d., Zagreb, Hrvatska

### MARS2:
 - programer, dizajner softverskog rješenja za korisničku web aplikaciju
 - zbrajanje i izvještavanje mjerenja o potrošnji i proizvodnji energije
 - tehnologije: WebApi2 rest servisi, React.js web front end s velikim brojem komponenti, druge Javascript uslužne biblioteke, ModBus i MBus Windows C# drajveri za izravno očitavanje mjernih vrijednosti s brojila električne energije

### MARS:
 - programer
 - instalacija sustava i edukacija korisnika u "HEP Proizvodnja d.o.o." u Varaždinu
 - tehnologije: poslužitelj: Windows servis za agregaciju i organizaciju podataka o potrošnji energije (neke pub-sub komponente i različiti drajveri agregatora izvora energije...); klijent: web aplikacija u Silverlight-u

### EIS (Energetski informacijski sustav grada Zagreba):
 - programer
 - agregiranje izmjerene potrošnje energije, naplate, algoritama za predviđanje potrošnje, energetskih razreda, puno algoritama i podataka pohranjenih u vremenskoj bazi podataka
 - tehnologije: ASP.NET MVC 5 (web aplikacija, Razor ekrani uz korištenje Kendo komponenti...), jQuery, D3js koji se koristi za vizualizaciju podataka; manji dijelovi izrađeni pomoću WebApi 2 i AngularJS frontenda pomoću NVD3 grafikona u Angular direktivama (D3 grafovi)

### Radni Nalozi:
 - dizajner rješenja i programer
 - jednostavna web aplikacija za praćenje i kreiranje radnih naloga razvijena pomoću WebApi 2 web servisa s fluxom (Reflux.js) + React.js frontendom


## [09.2013. do 03.2014.] Softverski inženjer - Multicom d.o.o., Zagreb, Hrvatska

### OSF (One Service Frontend)
 - programer
 - projekt za Hrvatski Telekom - Java EE 6 aplikacija koja se spaja na razne web servise te skuplja, organizira, i prikazuje skupljene informacije
 - razvoj JSF komponenti (npr. stablo) s rendererima i komponentama
 - JSF - PrimeFaces, JSTL, jQuery, Oracle DBMS

### TRT (Tariff Simulator Tool)
 - programer
 - projekt za Hrvatski Telekom - web aplikacija za simuliranje raznih promjena tarifa i opcija za mobilnu pretplatu - Ember.JS, jQuery, Java rest web servisi - JSON za razmjenu podataka
 - razvoj različitih vrsta PL/SQL skripti za Oracle baze podataka


## [09.2011. do 07.2013.] Softverski inženjer - WORX d.o.o., Varaždin, Hrvatska
 - razvoj i održavanje PLM aplikacije napisane na Javi (swing, ejb, hibernate, JBoss...), uključujući implementaciju i konfiguraciju ove aplikacije na udaljenim mrežama (mješavina Linux i Windows računala)
 - dizajn rješenja i razvoj mnoštva novih funkcionalnosti u tom PLM sustavu (na primjer, algoritam za obradu tijeka rada koji radi pomoću ručno nacrtanih dijagrama tijeka procesa, puno rada sa strukturama stabla uključujući usporedbu stabala...)
 - 1 mjesec radnog iskustva u Kanadi (ATS - Automation Tooling Systems, Cambridge, Ontario) - rad s njima na PLMWorxu kako bi dizajnirali i pravilno implementirali neke od njihovih poslovnih zahtjeva
 - dizajn rješenja i razvoj PDM proširenja, dodataka i vanjskih aplikacija za SolidWorks (C# klijent s Java web servisima, Hibernate, ejb, JBoss), AutoCAD (C#, MSSQL), Inventor (C# klijent s Java web servisima, hibernate, ejb, JBoss) i također nešto rada na proširenjima za Catia-u (VBA skripte)
 - djelomični dizajn rješenja i razvoj poslužiteljskog sustava grid procesiranja (koristeći Condor HTC kao sustav za upravljanje resursima) uključujući aplikacije za podršku i Windows servise koje koristi taj sustav
 - razvoj web PLM aplikacije (SmartClient 6.5 - 8.2, ejb, hibernate, JBoss...).
 - rad s različitim vrstama sustava za upravljanje bazama podataka, migracija podataka i procedura MS-SQL baze podataka na MySQL
 - rad u timu koji dizajnira i razvija aplikacije te također s ljudima iz različitih dijelova svijeta (Hrvatska, Kanada, Njemačka)


## [2008. do 2010.] Studentski poslovi
### [02.2011. do 07.2011.] Računalni programer - Financijska agencija (FINA), Zagreb, Hrvatska
Razvoj desktop i poslužiteljskih (windows servis) aplikacija u C#; korištenje i kreiranje baza podataka u MS SQL Server 2005.

### [Ljetni posao od 2008. do 2010.] Održavanje semafora - Selekta Prima d.o.o., Zagreb, Hrvatska
Održavanje semafora (provjera grešaka i popravak) na području Varaždina, Koprivnice, Križevaca, Čakovca, Ludbrega, Zlatar Bistrice, Ivanca. Posao je uključivao komunikaciju s policijom i tvrtkama koje osiguravaju uredno funkcioniranje prometa. Imao sam pristup službenom autu i mobitelu, a posao sam obavljao sam, zvao sam iskusnije samo kad nisam mogao sam otkloniti kvar. Posao se sastojao od dnevne provjere grešaka u radu semafora i odlaska na intervencije po zaprimljenom pozivu.


# Školovanje
## [09.2006. do 07.2011.] Magistar inženjer računarstva
Fakultet elektrotehnike i računarstva (FER), Zagreb, Hrvatska

## [09.2002. - 06.2006.] Tehničar za računalstvo
Elektrostrojarska škola, Varaždin, Hrvatska

## [2005] Cisco CCNA Course
Varaždin, Hrvatska


# Jezici
 - Engleski - vješt korisnik
 - Hrvatski - materinji jezik
