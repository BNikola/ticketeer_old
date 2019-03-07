# Administratorski panel

## 3.1 Kreiranje sale

| Naziv slučaja upotrebe | Kreiranje sale |
| ---------------------- | -------------- |
| Glavni učesnik         | Administrator  |
| Sporedni učesnici      | Sistem         |
| Kratak opis            | Administrator kreira salu sa određenim rasporedom i brojem mjesta |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Administrator je kreirao salu |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju kreiranje sale |
|                        | **2.** Administartor bira opciju "IZGLED SALE" |
|                        | **3.** Sistem prikazuje ponuđene opcije |
|                        | **4.** Administartor odabira izgled sale |
|                        | **5.** Administartor vrši kreiranje odjeljaka [SU_Kreiranje_odjeljaka] |
|                        | **6.** Sistem prikazuje kreiranu salu |
|                        | **7.** Administartor vrši kreiranje cjenovnih razreda |
|                        | **8.** Sistem ažurira izgled i opis sale |
| Alternative            | -/- |

## 3.2 Kreiranje odjeljaka

| Naziv slučaja upotrebe | Kreiranje sale |
| ---------------------- | -------------- |
| Glavni učesnik         | Administrator  |
| Sporedni učesnici      | Sistem         |
| Kratak opis            | Administrator kreira odjeljke sa određenim rasporedom i brojem mjesta |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Odjeljci u sali su kreirani |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za kreiranje odjeljaka |
|                        | **2.** Administrator bira broj odjeljaka za kreiranje |
|                        | **2.** Administrator bira koji odjeljak želi da modifikuje |
|                        | **3.** Sistem selektuje željeni odjeljak i prikazuje opcije |
|                        | **4.** Administrator dodaje mjesta u odjeljak |
|                        | **5.** Sistem provjerava unešene vrijednost |
|                        | **6.** Sistem ažurira kreirani odjeljak |
|                        | **7.** Administrator ponavlja prethodne korake za svaki odjeljak |
|                        | **8.** Nakon podešavanja svih odjeljaka sistem prikazuje šemu sale |
|                        | **9.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |


## 3.3 Kreiranje događaja
| Naziv slučaja upotrebe | Kreiranje događaja |
| ---------------------- | ------------------ |
| Glavni učesnik         | Administrator |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator kreira događaje i ažurira trenutni repertoar. Događaji imaju vrijeme održavanja, lokaciju i detalje  |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Događaj je kreiran |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za kreiranje događaja |
|                        | ?? |
|                        | **2.** Administrator modifikuje ime događaja |
|                        | **2.** Administrator dodaje detalje događaja |
|                        | **3.** Sistem provjerava unešene podatke |
|                        | **4.** Sistem prikazuje događaj |
|                        | **5.** Administrator dodaje događaj u trenutni repertoar |
|                        | **6.** Sistem ažurira trenutni repertoar |
|                        | **7.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | **5a.** U slučaju da događaj postoji u repertoaru sistem šalje upozorenje korisniku |

## 3.4 Ažuriranje događaja
| Naziv slučaja upotrebe | Ažuriranje događaja |
| ---------------------- | ------------------ |
| Glavni učesnik         | Administrator |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da ažurira postojeći događaj, to jest da promijeni određene detalje već postojećeg događaja |
| Preduslovi             | Administrator je prijavljen na Sistem |
|                        | Administrator izabrao događaj za ažuriranje |
| Postuslovi             | Događaj je ažuriran |
| Koraci (osnovni tok)   | **1.** Sistem prikazuje odabrani događaj |
|                        | **2.** Administrator bira koje detalje će da modifikuje |
|                        | **3.** Administrator modifikuje izabrane detalje o događaju |
|                        | **4.** Sistem vrši provjeru unešenih podataka |
|                        | **5.** Sistem ažurira izmjenjene podatke |
|                        | **6.** Administrator dodaje ažurirani događaj u trenutni repertoar |
|                        | **7.** Sistem ažurira trenutni repertoar |
|                        | **8.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |


## 3.5 Ažuriranje repertoara
| Naziv slučaja upotrebe | Ažuriranje repertoara |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da ažurira repertoar i po potrebi izbriše, doda ili izmjeni neki od događaja |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Repertoar je ažuriran |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za ažuriranje repertoara |
|                        | **2.** Sistem prikazuje događaje u repertoaru i moguće opcije |
|                        | **3.** Administrator vrši izmjene repertoara |
|                        | **4.** Sistem ažurira repertoar |
|                        | **5.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |


## 3.5 Određivanje vrijednosti kredita
| Naziv slučaja upotrebe | Određivanje vrijednosti kredita |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da, u skladu sa pravilima poslovanja, odredi ekvivalentnu vrijednost kredita upotrebnoj valuti |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Vrijednost kredita je ažurirana |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za određivanje vrijednosti kredita |
|                        | **2.** Sistem prikazuje moguće opcije |
|                        | **3.** Administrator unosi odgovarajuću vrijednost kredita |
|                        | **4.** Sistem vrši provjeru unešenih podataka |
|                        | **5.** Sistem ažurira vrijednost kredita |
|                        | **6.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |


## 3.6 Ažuriranje korisničkog naloga
| Naziv slučaja upotrebe | Ažuriranje korisničkih naloga |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da ažurira korisničke naloge i omogući određene funkcionalnosti za korisnike |
| Preduslovi             | Administrator je prijavljen na Sistem |
|                        | Korisnički nalog je već kreiran |
| Postuslovi             | Funkcionalnosti korisnika su ažurirane |
| Koraci (osnovni tok)   | **1.** Administrator šalje zahtjev za pregled korisnika |
|                        | **2.** Sistem prikazuje listu registrovanih korisnika |
|                        | **3.** Administrator bira korisnički nalog za modifikovanje |
|                        | **4.** Administrator modifikuje korisnički nalog |
|                        | **5.** Sistem provjerava validnost unešenih podataka |
|                        | **6.** Sistem ažurira korisničke podatke |
|                        | **7.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |


## 3.7 Brisanje korisničkog naloga
| Naziv slučaja upotrebe | Brisanje korisničkog naloga |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da obriše korisnički nalog |
| Preduslovi             | Administrator je prijavljen na Sistem |
|                        | Korisnički nalog je već kreiran |
| Postuslovi             | Korisnički nalog je obrisan |
| Koraci (osnovni tok)   | **1.** Administrator šalje zahtjev za pregled korisnika |
|                        | **2.** Sistem prikazuje korisničke naloge |
|                        | **3.** Administrator bira korisnički nalog koji želi da obriše |
|                        | **4.** Administrator šalje zahtjev za brisanje |
|                        | **5.** Sistem provjerava da li je nalog aktivan |
|                        | **6.** Administrator potvrđuje brisanje korisničkog naloga |
|                        | **7.** Sistem briše korisnički nalog |
|                        | **8.** Sistem briše nalog iz liste korisničkih naloga |
|                        | **9.** Sistem obavještava administratora o uspješnom brisanju |
| Alternative            | -/- |


## 3.8 Kreiranje korisničkih rankova
| Naziv slučaja upotrebe | Kreiranje korisničkih rankova |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da kreira rankove korisnika. U zavisnosti od ranka, korisnici će imati određene funkcionalnosti |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Korisnički rankovi su kreirani |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za kreiranje korisničkih rankova |
|                        | **2.** Administrator bira broj rankova i dodjeljuje im nazive |
|                        | **3.** Sistem provjerava validnost unešenih vrijednosti |
|                        | **4.** Sistem se ažurira |
|                        | **5.** Sistem obavještava administratora o uspješnom ažuriranju |
| Alternative            | -/- |








|                        |  |
|  |  |
| Alternative            | -/- |

