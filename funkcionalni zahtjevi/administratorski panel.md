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
| Alternative            | **5a.** U slučaju da događaj postoji u repertoaru sistem šalje upozorenje korisniku |

## 3.4 Ažuriranje događaja
| Naziv slučaja upotrebe | Ažuriranje događaja |
| ---------------------- | ------------------ |
| Glavni učesnik         | Administrator |
| Sporedni učesnik       | Sistem |
| Kratak opis            | Administrator može da ažurira postojeći događaj, to jest da promijeni određene detalje već postojećeg događaja |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Događaj je ažuriran |
| Koraci (osnovni tok)   | **1.** Sistem prikazuje odabrani događaj |
|                        | **2.** Administrator bira koje detalje će da modifikuje |
|                        | **3.** Administrator modifikuje izabrane detalje o događaju |
|                        | **4.** Sistem vrši provjeru unešenih podataka |
|                        | **5.** Sistem ažurira izmjenjene podatke |
|                        | **6.** Administrator dodaje ažurirani događaj u trenutni repertoar |
|                        | **7.** Sistem ažurira trenutni repertoar |
| Alternative            | -/- |


## 3.5 Ažuriranje repertoara
| Naziv slučaja upotrebe | Ažuriranje repertoara |
| ---------------------- | --------------------- |
| Glavni učesnik         | Administrator         |
| Sporedni učesnik       | Sistem |
| Kratak opis | Administrator može da ažurira repertoar i po potrebi izbriše, doda ili izmjeni neki od događaja |
| Preduslovi             | Administrator je prijavljen na Sistem |
| Postuslovi             | Repertoar je ažuriran |
| Koraci (osnovni tok)   | **1.** Administrator bira opciju za ažuriranje repertoara |
|                        | **2.** Sistem prikazuje događaje u repertoaru i moguće opcije |
|                        | **3.** Administrator ažurira repertoar |
|                        | **4.** Sistem ažurira repertoar |
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
| Alternative            | -/- |







|                        |  |
|  |  |
| Alternative            | -/- |

