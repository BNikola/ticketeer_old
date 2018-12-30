# Administratorski panel

## 3.1 Kreiranje sale

| **Naziv slučaja upotrebe** | Kreiranje sale |
| -------------------------- | -------------- |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
| **Kratak opis**            | Administrator kreira salu sa određenim rasporedom i brojem mjesta. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na sistem.</li><li>Administrator izabrao opciju kreiranje sale.</li></ol> |
| **Postuslovi**             | Administrator je kreirao salu |
| **Koraci (osnovni tok)**   | <ol><li>Administrator bira opciju "IZGLED SALE.</li><li>Sistem prikazuje ponuđene opcije.</li><li>Sistem prikazuje ponuđene opcije.</li><li>Administartor odabira izgled sale.</li><li>Administartor vrši kreiranje odjeljka [SU_Kreiranje_odjeljaka].</li><li>Sistem prikazuje kreiranu salu.</li><li>Administartor vrši kreiranje cjenovnih razreda.</li></ol> |
| **Alternative**            | -/- |


## 3.2 Kreiranje odjeljka
| **Naziv slučaja upotrebe** | Kreiranje odjeljka |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator kreira odjeljke sa određenim rasporedom i brojem mjesta. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator izabrao opciju za kreiranje odjeljka.</li></ol> |
| **Postuslovi**             | Odjeljci u sali su kreirani. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator dodaje mjesta u odjeljak.</li><li>Sistem provjerava unešene vrijednosti.</li><li>Administrator potvrđuje izmjene.</li><li>Sistem obavještava administratora u uspješnim izmjenama i ažurira salu.</li></ol> |
| **Alternative**            | 2.a Sistem obavještava administratora o nekorektnim vrijednostima. |


## 3.3 Kreiranje događaja
| **Naziv slučaja upotrebe** | Kreiranje događaja |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator kreira događaje i ažurira trenutni repertoar. Događaji imaju vrijeme održavanja, lokaciju i druge detalje. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator bira opciju za kreiranje događaja.</li></ol> |
| **Postuslovi**             | Događaj je kreiran. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator dodaje detalje događaja.</li><li>Sistem provjerava unešene vrijednosti.</li><li>Sistem prikazuje događaj.</li><li>Administrator dodaje događaj u trenutni repertoar.</li><li>Sistem ažurira trenutni repertoar.</li><li>Sistem obavještava administratora o uspješnom ažuriranju</li></ol> |
| **Alternative**            | 2.a Sistem obavještava administratora o nekorektnim vrijednostima. |


## 3.4 Ažuriranje događaja
| **Naziv slučaja upotrebe** | Ažuriranje događaja |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator može da ažurira postojeći događaj, to jest da promijeni određene detalje već postojećeg događaja. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator izabrao događaj za ažuriranje.</li></ol> |
| **Postuslovi**             | Događaj je ažuriran. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator modifikuje detalje o događaju.</li><li>Sistem provjerava unešene vrijednosti.</li><li>Sistem ažurira izmjenjene podatke.</li><li>Administrator dodaje ažurirani događaj u trenutni repertoar.</li><li>Sistem ažurira trenutni repertoar.</li><li>Sistem obavještava administratora o uspješnom ažuriranju</li></ol> |
| **Alternative**            | 2.a Sistem obavještava administratora o nekorektnim vrijednostima. |




## 3.5 Ažuriranje repertoara
| **Naziv slučaja upotrebe** | Ažuriranje repertoara |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator može da ažurira repertoar i po potrebi izbriše, doda ili izmjeni neki od događaja. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator bira opciju za ažuriranje repertoara.</li></ol> |
| **Postuslovi**             | Repertoar je ažuriran. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator vrši izmjene repertoara.</li><li>Sistem ažurira repertoar.</li><li>Sistem obavještava administratora o uspješnom ažuriranju.</li></ol> |
| **Alternative**            | -/- |



## 3.6 Određivanje vrijednosti kredita
| **Naziv slučaja upotrebe** | Određivanje vrijednosti kredita |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator može da, u skladu sa pravilima poslovanja, odredi ekvivalentnu vrijednost kredita upotrebnoj valuti. |
| **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator bira opciju za određivanje vrijednosti kredita.</li></ol> |
| **Postuslovi**             | Vrijednost kredita je ažurirana. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator unosi odgovarajuću vrijednost kredita.</li><li>Sistem vrši provjeru unešenih podataka.</li><li>Sistem ažurira vrijednost kredita.</li></ol> |
| **Alternative**            | 2.a Sistem obavještava administratora o nekorektnim vrijednostima. |


## 3.7 Ažuriranje korisničkog naloga
| **Naziv slučaja upotrebe** | Ažuriranje korisničkog naloga |
| -------------------------- | ------------------ |
| **Glavni učesnik**         | Administrator  |
| **Sporedni učesnici**      | Sistem         |
|**Kratak opis**             | Administrator može da ažurira korisničke naloge i omogući određene funkcionalnosti za korisnike. |
<!-- | **Preduslovi**             | <ol><li>Administrator je prijavljen na Sistem.</li><li>Administrator izabrao nalog za ažuriranje.</li></ol> |
| **Postuslovi**             | Korisnički nalog je ažuriran. |
| **Koraci (osnovni tok)**   | <ol><li>Administrator modifikuje detalje o događaju.</li><li>Sistem provjerava unešene vrijednosti.</li><li>Sistem ažurira izmjenjene podatke.</li><li>Administrator dodaje ažurirani događaj u trenutni repertoar.</li><li>Sistem ažurira trenutni repertoar.</li><li>Sistem obavještava administratora o uspješnom ažuriranju</li></ol> |
| **Alternative**            | 2.a Sistem obavještava administratora o nekorektnim vrijednostima. | -->
































