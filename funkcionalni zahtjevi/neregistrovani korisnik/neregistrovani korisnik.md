# Funkcionalni zahtjevi neregistrovanog korisnika

## 0.1 Registracija

|Naziv slučaja upotrebe|Registracija|
|---|---|
|Glavni učesnik|Korisnik|
|Sporedni učesnik|Sistem|
|Kratki opis|Korisnik unosi svoje podatke i salje zahtjev za registraciju|
|Preduslovi|Korisnik nije vec registrovan; Korisnik nije prijavljen na Sistem|
|Postuslovi|Korisnik je registrovan na Sistem|
|Koraci (osnovni tok)|**1.** Korisnik unosi podatke potrebne za registraciju|
||**2.** Korisnik salje zahtjev za registraciju|
||**3.** Sistem prima zahtjev za registraciju|
||**4.** Sistem verifikuje korisničke podatke|
||**5.** Sistem registruje korisnika|
||**6.** Sistem salje informaciju o uspjesnoj registraciji|
||**7.** Korisnik prima informaciju o uspjesnoj registraciji|

## 0.2 Pregled događaja/repertoara

|Naziv slučaja upotrebe|Pregled događaja/repertoara|
|---|---|
|Glavni učesnik|Korisnik|
|Sporedni učesnik|Sistem|
|Kratki opis|Korisnik ima uvid u događaje/repertoar|
|Preduslovi|-|
|Postuslovi|-|
|Koraci (osnovni tok)|**1.** Korisnik salje zahtjev za prikaz repertoara|
||**2.** Sistem prima zahtjev|
||**3.** Sistem salje pregled događaja/repertoara|
||**4.** Korisnik prima pregled događaja/repertoara|

## 0.3 Odabir događaja i pregled informacija o događaju

|Naziv slučaja upotrebe|Odabir događaja i pregled informacija o događaju|
|---|---|
|Glavni učesnik|Korisnik|
|Sporedni učesnik|Sistem|
|Kratki opis|Korisnik bira događaj i pregleda dodatne informacije o odabranom događaju|
|Preduslovi|-|
|Postuslovi|-|
|Koraci (osnovni tok)|**1.** Korisnik bira događaj iz pregleda događaja/repertoara [0.2]|
||**2.** Sistem prikazuje korisniku informacije o događaju|

## 0.4 Pregled kontak informacija

|Naziv slučaja upotrebe|Pregled kontak informacija|
|---|---|
|Glavni učesnik|Korisnik|
|Sporedni učesnik|Sistem|
|Kratki opis|Korisnik pregleda kontakt informacije|
|Preduslovi|-|
|Postuslovi|-|
|Koraci (osnovni tok)|**1.** Korisnik bira opciju za prikaz kontakt informacija|
||**2.** Sistem šalje korisniku kontakt informacije|
