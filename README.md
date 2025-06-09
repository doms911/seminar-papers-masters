# seminar-papers-masters

## Opis

Ovaj repozitorij sadrži kolekciju seminarskih radova i pripadajućih prezentacija s Fakulteta elektrotehnike i računarstva, Sveučilišta u Zagrebu. Trenutno uključuje rad Dominika Barukčića "Generativno modeliranje u računalnom vidu" u PDF formatu te njegovu prezentaciju u PPTX formatu.

## Struktura repozitorija

```
seminarski-radovi/
├── pdf/
│   └── Seminar_Barukcic_Dominik.pdf       # Seminarski rad Dominika Barukčića
├── pptx/
│   └── GenerativnoModeliranje.pptx       # PowerPoint prezentacija
├── README.md                             # Ova datoteka
└── .gitignore                            # Ignorirane datoteke
```

* **pdf/**: sadrži PDF verzije seminarskih radova.
* **pptx/**: sadrži prezentacije za istovremeno izlaganje.

## Preduvjeti

* Za čitanje PDF-ova: Adobe Acrobat Reader, Okular, Evince ili sličan PDF preglednik.
* Za pregled i uređivanje prezentacije: Microsoft PowerPoint, LibreOffice Impress ili Google Slides.

## Korištenje

1. Klonirajte repozitorij:

   ```bash
   git clone https://github.com/korisnik/seminarski-radovi.git
   ```
2. Pregledajte seminarski rad:

   ```bash
   cd seminarski-radovi/pdf
   xdg-open Seminar_Barukcic_Dominik.pdf
   ```
3. Pokrenite prezentaciju:

   ```bash
   cd ../pptx
   libreoffice --impress GenerativnoModeliranje.pptx
   ```

## Doprinos

Ako imate vlastite seminarske radove ili prezentacije, slobodno ih dodajte u odgovarajuće mape:

1. Stavite PDF u **pdf/** direktorij.
2. Stavite PPTX u **pptx/** direktorij.
3. Dodajte kratak opis u README ukoliko je potrebno.

Zatim pošaljite pull request.

## Licenca

Ovaj repozitorij je licenciran pod MIT licencom. Više detalja potražite u datoteci [LICENSE](LICENSE).

---

*Repozitorij održava [Tvoje Ime](mailto:ime.prezime@fer.hr).*
