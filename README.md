# Grupa3-Treneri
e-Teretana (Fitness centar)

Naručilac želi da automatizira, ubrza i poboljša rad teretane. Ciljevi su sljedeći:
-	Omogućavanje kartičnog i gotovinskog plaćanja članskih karti (uživo) te omogućavanje kartičnog plaćanja od kuće (prilikom online učlanjivanja)
-	Članska karta će uvijek biti spremna dan poslije učlanjivanja u 12:00pm te se šalje notifikacija korisniku koju on onda može podići bilo kad nakon toga
-	Dodavanje opcija za mjesečne, tromjesečne i godišnje članarine
-	Omogućavanje iznajmljivanja opreme na maksimalno 15 dana
-	Dodavanje mogućnosti da se vidi koje sprave su u kojem trenutku zauzete i na koji vremenski period na način da svako ko želi koristi nešto mora to zabilježiti preko sistema, kao i trenutni broj prisutnih u odnosu na maksimalan kapacitet ljudi 
-	Dodavanje mogućnosti pregleda i prijavljivanja na grupne ili pojedinačne vježbe preko sistema (u tačno određenim navedenim terminima u toku sedmice kod odabranog trenera)
-	Vođenje evidencije o dolascima korisnika, te ukoliko neko koristi teretanu 85% dana u mjesecu dobija jednu mjesečnu članarinu gratis

Kao što se može zaključiti iz navedenog razmatranja, postoje različite vrste korisnika koji mogu pristupiti sistemu i to: Recepcioneri (imaju prava administratora sistema), treneri (imaju malo ograničenija prava), učlanjeni korisnici te korisnici koji nemaju vlastite profile nego samo traže određene informacije. U nastavku ćemo detaljno objasniti uloge svih korisnika te njihove načine pristupanja.

Korisnici koji nisu učlanjeni imaju pristup samo homepage-u na kojem su prikazane informacije o radu teretane kao što su: radni dani, radno vrijeme, lokacija, treneri i slično. Ima opciju online učlanjivanja ali nije obavezno.

Učlanjeni korisnici, bez obzira na to da li su se učlanili uživo ili online, imaju opciju da sa homepage pređu u korisnički pogled. Nakon prijave na svoje profile imaju mogućnost da prate sljedeće: prikaz raspoložive opreme za iznajmljivanje te ukoliko je taj korisnik već iznajmio nešto, onda prikaz krajnjeg roka za vraćanje opreme (kada rok isteke korisnik dobija notifikaciju), opciju za rezervaciju individualnih ili grupnih treninga kod odabranog trenera u odabranom terminu, prikaz trenutne raspoloživosti teretane i trenutno raspoloživih sprava, dok se mogućnost da zauzme opremu javlja kao opcija tek onda kada recepcioner zabilježi prisustvo u teretani. Također, korisnik može pratiti evidenciju svoje aktivnosti u smislu da mu se prikazuje broj dolazaka u teretanu, kao i procenat dana u odnosu na broj dana u tom mjesecu za vrijeme kojih je korisnik dolazio u teretanu te ukoliko se dođe do 85%, korisnik dobija nagradu (besplatna mjesečna članarina). Ukoliko korisniku istekne članarina, obnavljanje se može obaviti na isti način kao učlanjenje, na licu mjesta ili online.

Treneri nakon prijavljivanja na svoje naloge mogu vidjeti za koje termine ima prijavljenih članova, te koji su to članovi.

Recepcioner je zaslužen za obavljanje učlanjivanja korisnika, a dobija i notifikacije kada se neki novi član online prijavi. Na kraju radnog vremena svakog dana šalje izvještaj o broju članskih kartica i imena ljudi za koje su, te mu se iste dostavljaju sutradan u 12. U svakom trenutku ima pristup broju učlanjenih, kao i njihovim podacima. Recepcija je također zadužena za evidentiranje iznajmljene opreme (ovu funkcionalnost nema korisnik direktno preko svog profila) na način da unose podatke o iznajmljenoj opremi, datumu iznajmljivanja (rok se automatski računa), te podatke o korisniku koji je iznajmio opremu. Pored dužnosti evidentiranja, u svakom trenutku može pristupiti izvještaju o trenutno iznajmljenim, kao i raspoloživim spravama. Što se tiče zauzetosti određene opreme u teretani, recepcioner je dužan samo zabilježiti koji je korisnik trenutno prisutan u teretani nakon čega se korisniku javlja opcija da bilježi koju spravu trenutno zauzima. Recepcioner pored toga može samo pristupiti izvještaju o tome koje sprave su zauzete, do kada i od strane koga. Recepcioner također bilježi odlazak korisnika, pri čemu se korisniku oduzimaju navedene privilegije. Može pristupiti podacima o grupnim/pojedinačnim treninzima za taj dan na način da vidi koji trener je odgovoran za koji trening, kao i spisak svih prijavljenih članova za određene termine.

Zahtjeve navedene na početku dokumenta ćemo sada tekstualno malo detaljnije opisati:
Učlanjivanje
Ukoliko se korisnik učlanjuje preko online servisa dužan je popuniti prijavu „Sign up“, gdje unosi svoje podatke kako što su: ime, prezime, e-mail adresa, username i password, nakon čega se prelazi na odabit vrste članarine, te se prikazuje interfejs za unos podataka za kartično plaćanje. Ukoliko se korisnik odluči na učlanjivanje uživo na recepciji, korisnik recepcioneru daje sljedeće informacije: ime, prezime i e-mail adresu, nakon čega je potrebno da korisnik izvrši plaćanje odgovarajuće vrste članarine, te se generišu username i password i šalju korisniku na mail. Svaki novi član se dodaje u izvještaj koji poslije služi za kreiranje odgovarajuće članske kartice.

Rezervacija treninga
U slučaju da se korisnik želi prijaviti za grupni ili individualni trening prikazuje mu se interfejs koji nudi da odabere jednu od te dvije opcije. Nakon odabrane opcije, prikazuje se spisak slobodnih termina iz te oblasti zajedno sa odgovarajućim trenerima za te termine. Korisniku se nudi opcija da otkaže prijavljeni termin, ali najkasnije 24 sata prije početka termina.

Iznajmljivanje opreme
U slučaju da korisnik želi iznajmiti neku opremu, može preko svog profila provjeriti šta je slobodno za iznajmljivanje ili može direktno pitati na recepciji. Recepcioner bilježi podatke korisnika koji iznajmljuje opremu, kao i oznaku (serijski broj) opreme, nakon čega se iznajmljena oprema automatski označava kao zauzeta. Po povratku opreme, recepcioner ju označava kao slobodnu. Kako je maksimalni rok iznajmljivanja 15 dana, korisniku se šalju upozorenja 3 dana i 1 dan pred istek roka, kao i na dan isteka roka da je vrijeme da vrati što je iznajmio.

Korištenje opreme
Svaki korisnik koji je trenutno u teretani, što je zabilježeno od strane recepcionera, mora ili putem nekog vlastitog uređaja ili putem uređaja u teretani zabilježiti koju spravu koristi putem njenog serijskog broja i također mora navesti vremenski interval tokom kojeg će tu spravu koristiti. Taj vremenski interval se od strane istog korisnika može korigovati po potrebi. Kada korisnik zauzme neku spravu za korištenje ona bude označena kao zauzeta te ostali korisnici mogu pristupiti toj informaciji.

