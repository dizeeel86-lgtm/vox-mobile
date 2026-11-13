VOX MOBILE 1.0 — PRVA PROTOTIP VERZIJA

SADRŽAJ
- index.html: korisnički interfejs
- manifest.webmanifest: PWA podešavanja
- sw.js: osnovni offline cache
- icon.svg: ikonica

VAŽNO
Ovo je UI prototip / demo. Još NIJE povezan sa OpenAI API-jem i ne izvršava stvarne pozive, poruke ili druge komande.
Ne stavljaj OpenAI API ključ u index.html ili bilo koji fajl koji se objavljuje javno.

KAKO DA GA PRIPREMIŠ NA WINDOWS-U
1. Raspakuj ZIP u folder, npr. C:\VOX.
2. Za instalaciju kao PWA potreban je HTTPS hosting (npr. privatni GitHub Pages ili drugi hosting).
3. Otvori HTTPS adresu u Safari na iPhone-u.
4. Pritisni Share > Add to Home Screen > Add.

NAPOMENA O GLASU
Ugrađeno prepoznavanje govora zavisi od podrške Safari/iOS verzije i može biti nedostupno. U tom slučaju koristi unos teksta dok ne povežemo poseban voice servis.

SLEDEĆI RAZVOJNI KORAK
Postaviti privatni backend (npr. FastAPI) koji čuva API ključ na serveru, autentifikuje tvoj uređaj i prosleđuje zahteve AI modelu. Tek nakon toga uključiti stvarne AI odgovore i bezbedno izvršavanje akcija.
