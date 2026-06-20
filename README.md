# Maršrutētāji
Preču piegādes maršrutēšana lietotne - https://marsrutetaji2.onrender.com/. Uzspiežot uz linka ir nedaudz jauzgaida līdz mājaslapa uzstartējas.

**Admin panelis testēšanai:**  
Lietotājvārds: admin  
Parole: admin

**Kurjera panelis testēšanai:**  
Lietotājvārds: kurjers1  
Parole: kurjers1

**Lietotāja panelis testēšanai:**  
Lietotājvārds: user  
Parole: user


# Dalībnieku ieguldījums
- Mārtiņš Paulauskis - Express.js, Lietotāja panelis, administratora panelis, kurjera panelis, HTML, CSS, Maršruts, Maršruta vizualizācija, Maršruta aprēķins, Pagaidu servera uzstādīšana, 14.01.2024 bug fixes
- Renārs Kristaps Jansons - Express.js, SQL Lite, Maršruts, Maršruta vizualizācija
- Ričards Zviedris - Express.js, Lietotāja pierakstīšanās panelis, pieslēgšanās panelis, pasūtījumu izvadīšana paneļos, datubāzes izveide, token sistēma, HTML, CSS, Plakāta izveide, 14.01.2024 bug fixes
- Ritvars Zābaks - Risinājuma uzstādīšana uz servera, stenda plakāts, konceptu modelis, tehnoloģiju steks, projektēšanas pārskats

# Problēmas nostādne
Preču piegādes maršrutēšanas optimizācija ir kļuvusi par ļoti populāru problēmu pēdējo pāris gadu laikā. Pateicoties tehnoloģiju attīstībai, tagad praktiski visu ir iespējams iegādāties internetā, maksājot ar karti - pārtiku, higiēnas preces, dāvanas tuvajiem Ziemassvētkos un daudz ko citu.

Nesenā globālā pandēmija COVID-19 vēl vairāk mainīja cilvēku iepirkšanās paradumus, jo bija nepieciešams sociāli distancēties. Līdz ar to, liela daļa cilvēku vairs neapmeklē veikalus klātienē. Tā kā attālināti iegādātām precēm jānonāk pie pircējiem, ir nepieciešams izmantot piegādes pakalpojumus, taču ar lielo piegādes pakalpojumu sniedzēju skaitu ielās parādās ar vien vairāk transportlīdzekļu.

Lai minimizētu piegādes pakalpojumu sniedzēju izmaksas uz transportu, kā arī dabas piesārņojumu, ir nepieciešams pēc iespējas optimālāk plānot piegādes maršrutus.
# Darba un novērtēšanas mērķis
**Piegādes Maršrutu Optimizācija**: Izmantot algoritmus maršrutu optimizācijai, kas ļaus efektīvi plānot piegādes maršrutus, samazinot laiku un resursu izmantošanu.

**Sistēmas stabila darbība**: Izstrādāt uz izvietot lietotni tīmekļa pārlūkprogrammā, kas darbosies stabili un lietotājiem sniegs nepārtrauktus pakalpojumus.

**Lietotāju apmierinātība**: Sniegt lietotājiem nepieciešamās sistēmas funkcijas, lai palielinātu efektivitāti piegādes ķēdē starp klientu un piegādātāju.
# Līdzīgo risinājumu pārskats
**Produktu piegādes maršrutēšanas risinājumi:**
</br>
</br>

<h2> GSM TASKS </h2>

</br>

*GSM Tasks piedāvā:*

- **Automatizēta maršrutēšana:** Piedāvā iespēju ievadīt visas piegādes adreses un noteikt visefektīvāko maršrutu uz visiem galamērķiem.

- **Tiešsaistes izsekošana un analītika:** GSM Tasks nodrošina reālā laika izsekošanu, lai zinātu, kur atrodas vadītāji un kā norit katra piegāde tiešsaistē. Tāpat piedāvā analītikas datus, lai uzraudzītu svarīgos rādītājus un veiktu optimizāciju maršrutēšanā.

- **Dokumentu un parakstu digitālizācija:** Risinājums piedāvā iespēju digitāli augšupielādēt dokumentus un fotogrāfijas, kā arī ļauj digitāli parakstīt dokumentus, kas ir noderīgi piegādes prasību pildīšanai.

- **Integrācijas ar citiem rīkiem:** GSM Tasks ļauj integrēties ar citiem uzņēmuma rīkiem, tai skaitā ar GPS sistēmām un citiem piegādes platformu sniedzējiem, piemēram 'Waze' vai 'Google Maps'.

- **Lietotājam draudzīga lietotne:** Piedāvā intuitīvu lietotāja saskarni un viegli saprotamu datu vizualizāciju, padarot lietošanu par vienkāršu un efektīvu.

*Par GSM tasks API:*

- **Datu apmaiņa:** Visi dati, kas tiek apmainīti starp klientiem un API, notiek JSON formātā caur HTTPS. Visi API pieprasījumi ir jāveic caur HTTPS protokolu. Pieprasījumi, kas tiek veikti caur parastu HTTP, tiks noraidīti.

- **Autentifikācija:** Lai veiktu jebkādus pieprasījumus, ir nepieciešama autentifikācija. Tas nozīmē, ka katram pieprasījumam ir jābūt autorizētam, lai tas tiktu izpildīts.

- **Bāzes URL:** GSMtasks API bāzes adrese ir [https://api.gsmtasks.com](https://api.gsmtasks.com).

- **Tehniskā dokumentācija:** Tehnikā API dokumentācija ir pieejama vietnē [https://api.gsmtasks.com/docs](https://api.gsmtasks.com/docs). Šajā dokumentācijā var atrast informāciju par pieejamajiem resursiem, pieprasījumu formātu, atbildēm un citiem tehniskiem aspektiem.

*GSM tasks cenrādis:*

- **Essential per user:** Šis plāns ietver plānošanu atkārtojošiem uzdevumiem un piegādēm, kā arī atbalstu caur tiešsaistes čatu. Cena: 14€ par lietotāju/mēnesī.

- **Professional:** Šis plāns piedāvā papildu funkcijas, piemēram, maršruta optimizāciju. Cena: 19€ par lietotāju/mēnesī.

- **Enterprise:** Šis plāns ir pielāgots individuāli, uzņēmuma vajadzībām, ņemot vērā darbinieku skaitu un uzņēmuma specifikas. Cena: individuāli noteikta katram uzņēmumam.

*Maršrutēšanas Optimizācijas Algoritmi:*

- **Vehicle Routing Problem with Pickup and Delivery (VRPPD):** Šis algoritms tiek izmantots, lai atrastu īsāko iespējamo maršrutu, lai nogādātu preces no vietas, kur tās tiek paņemtas līdz piegādes vietai.

- **Vehicle Routing Problem with Time Windows (VRPTW):** Šī algoritma galvenais mērķis ir laika ierobežojumi piegādei. Algoritms tiek pielāgots tā, lai nodrošinātu preču piegādi noteiktajā laika periodā.

- **Vehicle Routing Problem with LIFO:** Šajā gadījumā 'VRPPD' algoritms tiek papildināts ar "Last In, First Out" struktūru. Tas ļauj samazināt laiku, ko pavada preču izkraušana.

- **Capacitated Vehicle Routing Problem (CVRP):** Algoritms tiek izmantots, lai optimizētu, kā transportlīdzekļi tiek iekrauti ar noteiktu preču daudzumu, lai nodrošinātu maksimālu efektivitāti.

- **Vehicle Routing Problem with Multiple Trips (VRPMT):** Šis algoritms risina to, kā viens transportlīdzeklis var veikt vairākas braucienus, samazinot izmaksas, ceļojuma attālumu un uzlabojot vadītāju produktivitāti.

- **Open Vehicle Routing Problem (OVRP):** Šis algoritms nodrošina to, ka transportlīdzeklis nav jāatgriež sākuma punktā. Optimizācijas uzdevums noslēpjas, kad transportlīdzeklis sasniedz galamērķi. Šī problēma var būt sarežģīta, jo katrs brauciens var tikt uzskatīts par atsevišķu maršrutu, kur piegādes un atgriešanās var tikt apstrādātas atsevišķi.

**Novērojumu apkopojums:**

| **Funkcijas un Pakalpojumi**              | **Apraksts**                                                                                                                                                                                                                                                                                           |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Automatizēta Maršrutēšana**          | Ļauj ievadīt visas piegādes adreses un noteikt visefektīvāko maršrutu uz visiem galamērķiem.                                                                                                                                                                                                                           |
| **Tiešsaistes Izsekošana un Analītika** | Nodrošina reālā laika izsekošanu un analītiku, ļaujot uzraudzīt vadītāju atrašanās vietu un katra piegāde notiek tiešsaistē.                                                                                                                                                                                  |
| **Dokumentu un Parakstu Digitālizācija** | Piedāvā iespēju digitāli augšupielādēt dokumentus un fotogrāfijas, kā arī ļauj digitāli parakstīt dokumentus, kas ir noderīgi piegādes prasību pildīšanai.                                                                                                                                                            |
| **Integrācijas ar Citiem Rīkiem**      | Ļauj integrēties ar citiem uzņēmuma rīkiem, tai skaitā ar GPS sistēmām un citiem piegādes platformu sniedzējiem, piemēram, 'Waze' vai 'Google Maps'.                                                                                                                                                                |
| **Lietotājam Draudzīga Lietotne**      | Piedāvā intuitīvu lietotāja saskarni un viegli saprotamu datu vizualizāciju, padarot lietošanu par vienkāršu un efektīvu.                                                                                                                                                                                       |
| **GSM Tasks API**                     | - **Datu Apmaiņa:** Visi dati, kas tiek apmainīti starp klientiem un API, notiek JSON formātā caur HTTPS. <br/>- **Autentifikācija:** Visi API pieprasījumi prasa autentifikāciju, un tie ir jāveic caur HTTPS protokolu. <br/>- **Bāzes URL:** [https://api.gsmtasks.com](https://api.gsmtasks.com). <br/>- **Tehniskā Dokumentācija:** [https://api.gsmtasks.com/docs](https://api.gsmtasks.com/docs). |
| **Cenrādis**                         | - **Essential per user:** Plāns ietver plānošanu atkārtojošiem uzdevumiem un piegādēm, kā arī atbalstu caur tiešsaistes čatu. Cena: 14€ par lietotāju/mēnesī. <br/>- **Professional:** Plāns piedāvā papildu funkcijas, piemēram, maršruta optimizāciju. Cena: 19€ par lietotāju/mēnesī. <br/>- **Enterprise:** Individuāli pielāgots plāns uzņēmumam. |
| **Maršrutēšanas Optimizācijas Algoritmi** | - **Vehicle Routing Problem with Pickup and Delivery (VRPPD):** Īsākais maršruts no preces paņemšanas vietas līdz piegādes vietai. <br/>- **Vehicle Routing Problem with Time Windows (VRPTW):** Maršruts ar laika ierobežojumu piegādei. <br/>- **Vehicle Routing Problem with LIFO:** "Last In, First Out" principa izmantošana preču izkraušanā. <br/>- **Capacitated Vehicle Routing Problem (CVRP):** Transportlīdzekļa iekraušanas optimizācija. <br/>- **Vehicle Routing Problem with Multiple Trips (VRPMT):** Vairāku braucienu veikšana ar vienu transportlīdzekli. <br/>- **Open Vehicle Routing Problem (OVRP):** Algoritms, kas neprasa transportlīdzekļa atgriešanos sākuma punktā. |

</br>
</br>
</br>
</br>
</br>
</br>




<h2> Onfleet </h2>

</br>

*Onfleet piedāvā:*

- **Automātiski statusa atjauninājumi:** Klientiem tiek nosūtīts SMS brīdī, kad piegāde ir sākusies, cikos gaidīt kurjeru, un arī brīdī, kad kurjers ir klāt.

- **Kurjera atrašanās vieta reallaikā:** Klientam ir redzamas precīzas kurjeru atrašanās vietas, kā arī iespējamais ierašanās laiks.

- **Integrēta klientu komunikācija:** Klientam ir iespējams sazināties ar kurjeru nospiežot vienu pogu.

*Par Onfleet API:*

- **Tehniskā dokumentācija:** Tehniskā API dokumentācija ir pieejama vietnē [https://onfleet.com/devhub](https://onfleet.com/devhub).

*Onfleet cenrādis:*

- **Launch:** Ietver 2000 piegādes, neierobežotu lietotāju skaitu, maršuta optimizāciju. Cena: 550$ par lietotāju/mēnesī.

- **Scale:** Iekļauj Launch pakotni, taču 5000 piegādes, advancētas pieejas ierašanās laika prognozēšanai. Cena: 1265$ par lietotāju/mēnesī.

- **Enterprise:** Šis plāns ir pielāgots individuāli, uzņēmuma vajadzībām, ņemot vērā darbinieku skaitu un uzņēmuma specifikas, un iekļauj visu, kas pieejams Launch un Scale pakotnēs.. Cena: individuāli noteikta katram uzņēmumam.

*Maršrutēšanas Optimizācijas Algoritmi:*

- Nav pieejama konkrēta informācija par Onfleet izmantotajiem algoritmiem, taču ir zināms, ka viņu piedāvatais API var tikt izmantots Python, PHP, Java, JavaScript, Ruby un Golang programmēšanas valodās.

**Novērojumu apkopojums:**

| **Funkcijas un Pakalpojumi**              | **Apraksts**                                                                                                                                                                                                                                                                                           |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Automatizēta Maršrutēšana**          | Ļauj ievadīt visas piegādes adreses un noteikt visefektīvāko maršrutu uz visiem galamērķiem.                                                                                                                                                                                                                           |
| **Tiešsaistes Izsekošana un Analītika** | Nodrošina reālā laika izsekošanu un analītiku, ļaujot uzraudzīt vadītāju atrašanās vietu un katra piegāde notiek tiešsaistē.                                                                                                                                                                                  |
| **Dokumentu un Parakstu Digitālizācija** | Piedāvā iespēju digitāli augšupielādēt dokumentus un fotogrāfijas, kā arī ļauj digitāli parakstīt dokumentus, kas ir noderīgi piegādes prasību pildīšanai.                                                                                                                                                            |
| **Integrācijas ar Citiem Rīkiem**      | Ļauj integrēties ar citiem uzņēmuma rīkiem, tai skaitā ar GPS sistēmām un citiem piegādes platformu sniedzējiem, piemēram, 'Waze' vai 'Google Maps'.                                                                                                                                                                |
| **Lietotājam Draudzīga Lietotne**      | Piedāvā intuitīvu lietotāja saskarni un viegli saprotamu datu vizualizāciju, padarot lietošanu par vienkāršu un efektīvu.                                                                                                                                                                                       |
| **Onfleet API**                     | - **Datu Apmaiņa:** Visi dati, kas tiek apmainīti starp klientiem un API, notiek JSON formātā caur HTTPS. <br/>- **Autentifikācija:** Visi API pieprasījumi prasa autentifikāciju, un tie ir jāveic caur HTTPS protokolu. <br/>- **Bāzes URL:** [https://onfleet.com/api/v2](https://onfleet.com/api/v2). <br/>- **Tehniskā Dokumentācija:** [https://onfleet.com/devhub](https://onfleet.com/devhub). |
| **Cenrādis**                         | - **Lauch:** PIetver 2000 piegādes, neierobežotu lietotāju skaitu, maršuta optimizāciju. Cena: 550$ par lietotāju/mēnesī. <br/>- **Scale:**  Iekļauj Launch pakotni, taču 5000 piegādes, advancētas pieejas ierašanās laika prognozēšanai. Cena: 1265$ par lietotāju/mēnesī. <br/>- **Enterprise:** Individuāli pielāgots plāns uzņēmumam. |

</br>
</br>
</br>
</br>
</br>
</br>



<h2> Route4me </h2>

</br>

*Route4me piedāvā:*

- **Dinamiska Maršrutēšana:** Route4Me ļauj lietotājiem ievadīt piegādes adreses un automātiski izveido visefektīvāko maršrutu, ņemot vērā dažādus faktorus, piemēram, satiksmi, laika logus un transportlīdzekļu ietilpību.

- **Reāllaika Izsekošana un Analīze:** Šis risinājums nodrošina reāllaika izsekošanu transportlīdzekļiem un piegādēm, kā arī sniedz detalizētus analītikas datus par maršrutu efektivitāti un vadītāju veiktspēju.

- **Dokumentu Digitalizācija un Parakstu Vākšana:** Route4Me ļauj digitalizēt piegādes dokumentus un ļauj klientiem elektroniski parakstīt piegādes apstiprinājumus, uzlabojot procesu efektivitāti.
  
- **Plašas Integrācijas Iespējas:** Route4Me piedāvā integrācijas ar dažādiem biznesa sistēmām un platformām, tostarp ar GPS izsekošanas iekārtām un citām piegādes pārvaldības platformām.

- **Lietotājam Draudzīga Mobilā Lietotne:** Route4Me piedāvā ērti lietojamu mobilās lietotnes interfeisu, kas ir intuitīvs un nodrošina vienkāršu datu vizualizāciju un pārvaldību.

  
*Par rout4me API:*

- **Autentifikācija:** Lai izmantotu API, nepieciešama autentifikācija, nodrošinot drošu datu apmaiņu un piekļuvi.

- **Bāzes URL:** Route4Me API bāzes adrese ir https://route4me.io/ .

- **Tehniskā Dokumentācija:** API dokumentācija ir pieejama vietnē https://route4me.io/docs/ , kurā ir detalizēta informācija par API izmantošanu, pieprasījumu formātiem un atbildēm.


*Route4me cenrādis:*

- **Route Management:** maksā $199 mēnesī, ietver vairākas būtiskas funkcijas biznesa operāciju pārvaldībai. Tas ļauj efektīvi pārvaldīt visus biznesa procesus, veicināt sadarbību starp dažādām uzņēmuma nodaļām un komandām. Šis plāns arī nodrošina iespēju integrēt sistēmu ar jebkuru citu lietotni, kas var būt nepieciešama uzņēmuma darbībai, tādējādi nodrošinot plašākas darba iespējas un efektivitāti. Turklāt tas piedāvā iespēju iegūt reāllaika biznesa ieskatus, kas ir svarīgi lēmumu pieņemšanai un stratēģijas plānošanai. Kā arī plāns ļauj sekot darbiniekiem un transportlīdzekļiem reāllaikā uz kartes.

- **Route Optimization:** maksā $249 mēnesī, papildus visām "Route Management" funkcijām piedāvā arī vairāku personu maršrutu automātisko optimizāciju. Šis plāns ļauj integrēt un pielāgot biznesa noteikumus maršrutu optimizācijas procesā, nodrošinot augstāku efektivitāti un pielāgojamību atbilstoši specifiskām uzņēmuma vajadzībām.

- **Route Optimization Plus:** maksā $349 mēnesī, ietver visas "Route Optimization" plāna funkcijas un piedāvā papildu iespējas. Tas ne tikai automātiski optimizē vairāku personu maršrutus, bet arī ļauj integrēt un pielāgot detalizētus biznesa noteikumus maršrutu optimizācijā, nodrošinot vēl precīzāku un efektīvāku maršrutu plānošanu atbilstoši konkrētām uzņēmuma vajadzībām un operacionālajām prasībām.

- **Bezmaksas 7 Dienu Neierobežots Izmēģinājums Jūsu Uzņēmumam:** Route4Me piedāvā bezmaksas 7 dienu neierobežotu izmēģinājumu jūsu uzņēmumam, kas ir pilnīgi bez maksas un neprasa kredītkartes informāciju. Šajā izmēģinājuma periodā jūs varat tūlītēji izveidot optimizētus maršrutus, piekļūt mobilajai lietotnei un saņemt nepārtrauktu atbalstu 24/7.

*Maršrutēšanas Optimizācijas Algoritmi:*

- Route4Me izmanto savu patentēto un īpaši izstrādāto Dynamic Route Optimization™ algoritmu un dzinēju. 

- Papildus klasiskajai Ceļojošā Pārdevēja Problēmai (Traveling Salesman Problem - TSP) un Transportlīdzekļu Maršrutēšanas Problēmai (Vehicle Routing Problem - VRP), Route4Me atbalsta dažādus maršrutēšanas optimizācijas ierobežojumus, lai atrisinātu maršrutēšanas problēmas ar papildu sarežģītības slāņiem.

**Novērojumu apkopojums:**

| **Funkcijas un Pakalpojumi**              | **Apraksts**                                                                                                                                                                                                                                                                                           |
|--------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Dinamiska Maršrutēšana**          | Automātiska visefektīvākā maršruta izveide, ņemot vērā satiksmi, laika logus, transportlīdzekļu ietilpību.                                                                                                                                                                                                                          |
| **Reāllaika Izsekošana un Analīze** | Transportlīdzekļu un piegāžu izsekošana reāllaikā, detalizēta maršrutu un vadītāju veiktspējas analīze.                                                                                                                                                                                  |
| **Dokumentu Digitalizācija un Parakstu Vākšana** | Piegādes dokumentu digitalizācija, elektroniskā parakstu vākšana.                                                                                                                                                            |
| **Plašas Integrācijas Iespējas**      | Integrācija ar dažādām biznesa sistēmām un platformām, ieskaitot GPS izsekošanu.                                                                                                                                                                |
| **Route4Me API**      | Autentifikācija drošai datu apmaiņai, bāzes URL: https://route4me.io/, detalizēta tehniskā dokumentācija.                                                                                                                                                                                       |
| **Cenrādis**                     | <strong>Route Management ($199/mēn.):</strong> Biznesa operāciju pārvaldība, sadarbība, lietotņu savienojums, reāllaika ieskati, dzīvā kartē sekot cilvēkiem. <strong>Route Optimization ($249/mēn.):</strong> Ietver "Route Management" funkcijas, automātiska vairāku personu maršrutu optimizācija. <strong>Route Optimization Plus ($349/mēn.):</strong> Ietver "Route Optimization" funkcijas, papildu biznesa noteikumu izmantošana maršrutu optimizācijā. <strong>Bezmaksas 7 Dienu Izmēģinājums:</strong> Bez maksas, bez kredītkartes, tūlītēja maršrutu izveide, mobilā lietotne, 24/7 atbalsts. |
| **Maršrutēšanas Optimizācijas Algoritmi**                         | Patentēts Dynamic Route Optimization™, risina TSP un VRP problēmas, atbalsta dažādus optimizācijas ierobežojumus. |

# Lietotāju stāsti
| Nr. | Lietotāju stāsts (lietotājs) vēlas (sasniegt mērķi), jo (ieguvums)  | Prioritāte |
|-----|----------------------------------------------------------------------|------------|
| 1.  | Noliktavas pārvaldnieks vēlas automatizētu sistēmu maršrutu optimizācijai, jo vēlas samazināt piegādes laiku un izmaksas. | Must have  |
| 2.  | Piegādes vadītājs vēlas mobilu lietotni piegāžu statusa atjauninājumiem, jo tas uzlabotu komunikāciju ar klientiem. | Should have |
| 3.  | Kurjers vēlas GPS navigāciju ar maršrutēšanu, jo tā efektīvi pielāgotos satiksmes apstākļiem un samazinātu piegādes aizkavēšanos. | Must have  |
| 4.  | Uzņēmuma vadītājs vēlas detalizētus pārskatus par piegādes efektivitāti, jo tad varētu labāk izvērtēt operatīvo efektivitāti un veikt stratēģiskus uzlabojumus | Could have |
| 5.  | Piegādes vadītājs vēlas integrāciju ar dronu piegādes sistēmām, jo tas sniegtu iespēju eksperimentēt ar nākotnes piegādes tehnoloģijām. | Won't have |
| 6.  | Klients vēlas izsekot savu sūtījumu, jo grib plānot saņemšanas laiku. | Should have |
| 7.  | Administrators vēlas pievienot lietotājam lomu kurjers, jo kurjeram nepieciešama atsevišķa loma, lai saņemtu pasūtījumus un maršrutus. | Must have |
| 8.  | Kurjers vēlas redzēt visus savus pasūtījumus. | Should have |
| 9.  | Administrators vēlas funkciju, lai pievienotu maršrutu individuālam kurjeram, jo ārkārtas situācijās var būt nepieciešams manuāli pievienot maršrutu. | Could have |
| 10.  | Klients  vēlas redzēt visos aktīvos viņa pasūtījumus, jo vajag sekot līdzi pasūtījumiem, kurus vēl gaida. | Must have |

# Algoritms
Šajā kodā tiek izmantots vienkāršs algoritms, lai sadalītu maršrutus starp kurjeriem, balstoties uz brauciena laiku. 
Lai paskaidrotu šo algoritmu sīkāk un detalizētāk, šeit ir redzama algoritma blokshēma un pseidokods.

## Blokshēma
![Screenshot 2024-01-13 145006](https://github.com/Rencc01/Marsrutetaji/assets/150249400/088a7ea8-45bd-409b-8db4-2ccee8bfbec1)

## Pseidokods

```
Funkcija executeMain(deliveryFile, username):
    Izvadīt "Attālumu aprekins aktivizēts, apstrādā failu:", deliveryFile
    Izvadīt "Lietotājs tikko pieprasīja maršruta optimizāciju:", username

    Ielasīt datubāzi un iegūt adreses
    Pārbaudīt un iegūt citus kurjerus no faila
    Attālumu un laika iegūšana no Google Distance Matrix API
    Sadalīt maršrutus starp vairākiem kurjeriem
    Saglabāt maršrutus datubāzē
    Izvadīt "Attalumu aprekinasana tika izpildīta"

Funkcija getDistanceMatrix(origins, destinations):
    Mēģināt:
        Veikt asinhronu pieprasījumu uz Google Distance Matrix API
        Atgriezt atbildes rindu elementus
    Noķert kļūdu:
        Izvadīt "Kļūda: Nav iespējams iegūt brauciena laiku"
        Izsvītrot izņēmuma notikumu

Funkcija distributeRoutes():
    Iegūt attālumus un laikus no getDistanceMatrix(START_ADDRESS, addresses)
    Aprēķināt kopējo brauciena laiku

    Sagatavot kurjeru sarakstu, sākot ar galveno lietotājvārdu un pievienojot atšķirīgos lietotājvārdus
    Inicializēt kurjeru maršrutu un brauciena laiku masīvus

    Sadalīt adreses starp kurjeriem
        Izvēlēties kurjeru ar minimālo brauciena laiku
        Pievienot adresi šim kurjeram un palielināt kopējo laiku

    Atgriezt kurjeru maršrutus un visus kurjerus

Funkcija saveRoutesToCSV(courierRoutes, allCouriers, deliveryFile):
    Sagatavot ierakstu sarakstu no maršrutiem un kurjeriem
    Rakstīt ierakstus datubāzē
    Izvadīt "Maršruti saglabāti failā:", outputPath
    Noķert kļūdu:
        Izvadīt "Kļūda saglabājot maršrutus"

Izsaukt distributeRoutes():
    Iegūt kurjeru maršrutus un visus kurjerus
    Izvadīt katru kurjeru ar viņa maršrutu
    Izsaukt saveRoutesToCSV ar iegūtajiem datiemi, deliveryFile

Izsaukt executeMain ar konkrētiem parametriem

```

# Konceptu modelis

![Screenshot 2024-01-13 152851](https://github.com/Rencc01/Marsrutetaji/assets/150249400/e8e4fd07-0bce-4d11-aec1-3325c1b352ab)

Sistēmu raksturo 8 koncepti - Lietotne, Administrācija, Lietotājs, Kurjers, Pasūtījums, Lokācija, Karte un Maršruts.

Starp konceptiem ir definēti to starpā attiecības.
Ir viena Lietotne, kas ir preču piegādes maršrutēšana lietotne, kurai klāt piekļūst vairāki Lietotāji, Administratori un Kurjeri.
Lietotājs ir spējīgs izveidot Pasūtījumu, kurā būs jānorāda piegādes Lokācija.
Pamatojoties uz vairākām Lokācijām, tiek izveidots Maršruts, kas tiek attēlots Kartē.
Karti redz tikai Administratori un Kurjeri.

# Tehnoloģiju steks

Servera pusē:


- **Operētājsistēma Windows**: Servera darbība notiek uz Windows operētājsistēmas, kas ir izvēlēta kā pamata platforma.
- **Serveris Windows Server 2022**: Windows Server 2022 kalpo kā servera operētājsistēma, nodrošinot vajadzīgo servera funkcionalitāti un drošību.
- **Windows ISS tīmekļa serveris**: IIS (Internet Information Services) ir Windows operētājsistēmas integrēta tīmekļa servera loma, kas nodrošina HTTP un HTTPS protokolu apkalpošanu un sniedz servera spējas izpildīt tīmekļa lietojumprogrammas.
- **SQLite datu bāze**: Sistēma izmanto SQLite, vieglu iegultu datu bāzi, kas saglabā datus vietēji un nodrošina vienkāršu datu pārvaldību.
- **Programmēšanas valodas**:
  - **JS (JavaScript)**: Tieši šī valoda tiek izmantota servera un klienta puses programmēšanai.
  - **HTML**: Lietojumprogrammu lietotāja saskarnes (UI) izstrādei tiek izmantots HTML, kas definē lapas struktūru.
  - **CSS**: Stila lapas izveidei un pielāgošanai tiek izmantots CSS.
  - **Express.js satvars**: Express.js ir servera puses JavaScript rīks, kas vienkāršo tīmekļa lietojumprogrammu izstrādi un ļauj efektīvi pārvaldīt HTTP pieprasījumus un maršrutēšanu.





Klienta pusē:

- **Tīmekļa pārlūkprogramma**: Lietotājiem tiek sniegta piekļuve sistēmai, izmantojot standarta tīmekļa pārlūkprogrammas, piemēram, Chrome, Firefox vai Safari.
- **JS, CSS, HTML**: Klienta puses lietotāja saskarnes (UI) izstrāde notiek, izmantojot iepriekš minētās tehnoloģijas - JavaScript, HTML un CSS.
- **Node.js vide**: Node.js nodrošina izpildes vidi klienta puses JavaScript valodai, kas ļauj darbināt JavaScript ārpus pārlūkprogrammas, piemēram, servera vidē.

# Novērtējums

RTU "Projektēšanas laboratorija" kursa ietvaros mūsu grupai ir izdevies izveidot preču piegādes maršrutēšanas lietotni.

Sistēma sastāv no trim paneļiem:
1. Lietotāja paneļa
2. Administratora paneļa
3. Kurjera paneļa

Ikvienam lietotājam ir iespēja reģistrēties sistēmā kā "User" lietotājam. Ir nepieciešams ievadīt vārdu, uzvārdu, lietotājvārdu un paroli. Pēc tam pieslēdzoties savam kontam panelī ir redzama informācija par lietotāju, aktīvie pasūtījumi un jauna pasūtījuma izveides veidne, kurā klientam jānorāda piegādes adresi, piegādes vēlamo datumu un laika intervālu, kurā viņš varēs saņemt sūtījumu no kurjera.

Pie administrācijas paneļa spēj piekļūt tie lietotāji, kam ir piešķirta admina loma. Admins savā panēlī tāpat kā lietotāji, redz informāciju par sevi. Administratora funkcija sistēma ir piešķirt kurjeram maršrutu norādītajā dienā. "Assign Delivery" veidnē Admins izvēlās piegādes dienu un kurjeru, kuram to piešķirt. Vēl viena svarīga funkcija adminam ir lomu piešķiršana, viņš ir spējīgs katram no lietotājiem uzstādīt "User" vai "Kurjera" lomu, kā arī dzēst lietotāju no sistēmas.

Kurjers savā panelī redz administratora piešķirtos piegādes maršrutus attēlotus tos kartē, kā arī kopējo maršruta distanci (km) un kopējo laiku, kas jāpavada maršrutā.

# Secinājumi
Piegādes maršrutēšanas sistēma "Maršrutētāji" ir veiksmīgi izstrādāta un piedāvā savā ziņā grupas sākotnējās plānotās funkcijas, izskatīgu dizainu un tiek nodrošināts nepārtraukts sistēmas darbības laiks, kā arī visi grupas dalībnieki ir iesaistījušies.
