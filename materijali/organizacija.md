## Korisnici
- Privilegovan može da bira mjesto i kupuje putem kredita
- obični moze da rezerviše - radnik na blagajni bira mjesto i salje se potvrda o rezervaciji
- neregistrovani može da gleda repertoar i ništa više
- validacija rezervacije na blagajni

## Radnik na blagajni
- validacija rezervacije na blagajni
- odabir mjesta korisnika bez privilegija
- identifikacija gosta na blagajni a ne pred salom (blagajnik provjerava kod i izdaje ulaznice korisniku)
    - unos sifre
    - pretrazivanje evidencije (trazenje odgovarajuce rezervacije)
    - pronadjeno/nije
    - izdavanje karte / obavjestenje -> ponuda za novu rez.
- ispraviti dijagram i tabelu
- rezervacija na licu mjesta -> pregled korisnika
- dodati sistem

## Registrovani korisnik
 - Biranje mjesta u sali -> staviti u preduslov generisanje forme
    - izbaciti 1. 2. iz koraka


### Nefunkcionalni zahtjevi
- koliko ranije može da se otkaže registracija
- identifikacija korisnika
    - slanje koda na mail sa potvrdom o rezervaciji
    - korisnik treba da pokaze kod iz mail-a pri preuzimanju ulaznica
    - korisnik sa privilegijama samo preuzima karte nakon validacije, bez placanja (ako je kupio preko kredita)
    - sortiranje rezervacija po rangovima
- ponovno slanje validirane rezervacije ako nije stiglo na mail
- jedinstvenost korisnika
- sta je automatsko
    - registracija
    - zahtjev za rezervaciju (koliko kosta) - blagajnik potvrdi
    - obavjestenje o eventualnoj promjeni mjesta - obavijest telefonom
    - ponovno slanje obavijesti o rezervaciji
    - nema dovoljno kredita - poruka
    - ako nema dovoljno kredita - vraca se na validaciju rezervacije
    - smanjenje broja kredita

## Terminologija
- Datastores
    - Evidencija korisnickih naloga
    - Evidencija događaja
    - Repertoar
    - Evidencija zauzetosti sjedišta
    - Evidencija zahtjeva za rezervaciju
    - Evidencija rezervacija

- Objekti
    - Zahtjev (novi) na početku toka i Poruke (nova) na kraju toka
    - Slanje obavještenja - obavještenje kao objekat - prijem obavještenja