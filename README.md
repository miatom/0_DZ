#JMBAG
0036471019

# Pitanje 1
Nakon dodavanja class library reference i buildanja projekta u Bin/Debug folderu pojavile 
su se dvije nove datoteke. Jedna od njih je novi asemblij ClassLibrary1.dll.
Ukoliko izbrišemo novi asemblij naša aplikacija više neće raditi, jer više nema pristupa 
klasi MyConsole. Kako bi se aplikacija uspješno pokrenula potrebno je u direktoriju imati oba asemblija
(datoteke sa .exe i .dll nastavkom).

# Pitanje 2
Ukoliko bez prevođenja pokrenemo datoteku KonzolnaAplikacija.exe string koji ona ispisuje će ostati nepromjenjen.
Odnosno, svaki puta kada mijenjamo datoteke Program.cs ili Class1.cs moramo datoteke ponovo prevesti (build)
kako bi promjene bile vidljive. U suprotnom pokrećemo stare inačice asemblija. 

# Pitanje 3
Pokretanjem aplikacije unutar konzole smo dobili ispis: "Pero: Hello World".

# Pitanje 4
Unutar bin/Debug direktorija pojavio se novi asemblij PeroClassLibrary.dll.

# Pitanje 5
Ukoliko obrišemo originalni .dll na disku naša aplikacija će i dalje raditi, upravo zato što je
Visual Studio prilikom pokretanja aplikacije u bin/Debug direktoriju stvorio istovjetan asemblij.

# Pitanje 6
Nakon brisanja NodaTime paketa iz packages direktorija te ponovog pokretanja build se uspješno izvršio
dok se NodaTime paket ponovo stvorio u direktoriju packages unutar solutiona.


 
