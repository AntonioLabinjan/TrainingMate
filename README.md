# TrainingMate
TrainingMate je web-servis namijenjen evidentiranju vježbi i obroka uz razne funkcionalnosti koje korisnicima omogućuju lakše praćanje informacija vezanih uz vježbe i obroke.

# Funkcionalnosti
# Osnovne funkcionalnosti
Create exercise
Read exercise
Update exercise
Delete exercise
Create meal
Read meal
Update meal
Delete meal
# Dodatne funkcionalnosti
Calculate exercise duration
Calculate exercise calories
Calculate meal calories
Sort meals by calories
Sort exercises by duration
Calculate caloric balance
Show graph with exercise calories
Show graph with meal calories
Show graph with exercises and their intensities
Show graph with meals and their categories
# Struktura
Web aplikacija sastoji se dva povezana servisa, od kojih jedan omogućuje evidentiranje vježbi, a drugi evidentiranje obroka. Omogućeno je dodavanje, pregledavanje, izmjenjivanje te brisanje vježbi i obroka, praćanje unosa, potrošnje kalorija, sortiranje vježbi i obroka te vizualiziranje pojedinih podataka pomoću grafova.

# Pokretanje
Preuzeti sve datoteke s Githuba i spremiti ih u mapu
Putem naredbenog retka pozicionirati se u mapu iz prethodnog koraka
Pomoću naredbe: docker build -t trainingmate . izraditi docker image
Pomoću naredbe: docker run -p 5000:8080 trainingmate pokrenuti konteiner pomoću stvorenog image-a
Otvoriti preglednik: localhost:5000

# Izrađeno u paru s Anastazijom Širol
