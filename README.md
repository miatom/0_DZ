#JMBAG
0036471019

# Pitanje 1
Nakon dodavanja class library reference i buildanja projekta u Bin/Debg folderu pojavile 
su se dvije nove datoteke. Jedna od njih je novi asemblij ClassLibrary1.dll.
Ukoliko izbri�emo novi asemblij na�a aplikacija vi�e ne�e raditi, jer vi�e nema pristupa 
klasi MyConsole. Kako bi se aplikacija uspje�no pokrenula potrebno je u direktoriju imati oba asemblija
(datoteke sa .exe i .dll nastavkom).

# Pitanje 2
Ukoliko bez prevo�enja pokrenemo datoteku KonzolnaAplikacija.exe string koji ona ispisuje �e ostati nepromjenjen.
Odnosno, svaki puta kada mijenjamo datoteke Program.cs ili Class1.cs moramo datoteke ponovo prevesti (build)
kako bi promjene bile vidljive. U suprotnom pokre�emo stare ina�ice asemblija. 

# Pitanje 3
Pokretanjem aplikacije unutar konzole smo dobili ispis: "Pero: Hello World".

# Pitanje 4
Unutar bin/Debug direktorija pojavio se novi asemblij PeroClassLibrary.dll

# Pitanje 5
Ukoliko obri�emo originalni .dll na disku na�a aplikacija �e i dalje raditi, upravo zato �to je
Visual Studio prilikom pokretanja aplikacije u bin/Debug direktoriju stvorio istovjetan asemblij.

# Pitanje 6
Nakon brisanja NodaTime paketa iz packages direktorija te ponovog pokretanja build se uspje�no izv�io
dok se NodaTime paket ponovo stvorio u direktoriju packages unutar solutiona.


 