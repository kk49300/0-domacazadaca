# JMBAG
0036493004
#Pitanje 1
Bin/Debug folder nakon dodavanja class library kao reference ima ClassLibrary1.dll i ClassLibrary1.pdb.
Nakon micanja .dll class library projekta iz Bin/Debug foldera i pokretanja, pojavljuje se pogreška da je program prestao raditi, zato jer je .dll bitna datoteka za prepoznavanje class library koji se koristi u console application.
Da bih poslala aplikaciju poslala bih console apllication tj. .exe (aplikacija) i .dll class library (proširenje aplikacije).

#Pitanje 2
Nakon izmjene stringa koji ispisuje MyConsole.PrintHelloWorld() metoda i pokretanja konzolne aplikacije bez prevođenja class library projekta ispisuje se novi string. Zato jer su class library i consol application automatski povezani.

#Pitanje 3
Nakon pokretanja aplikacije ispisalo se: "Pero: Hello world."

#Pitanje 4
U sadržaju Bin/Debug foldera konzolne aplikacije nakon što sam dodala pero class library kao referencu ima PeroClassLibrary.dell.

#Pitanje 5
Ako obrišem originalni .dll na disku aplikacija i dalje normalno radi, zato jer se ta datoteka kopirala u folder Bin/Debug i korisi se od tamo. 
U references listi se sada PeroClassLibrary traži u folderu Bin/Debug.

#Pitanje 6
Buildanje aplikacije nakon brisanja NodaTime direktorij unutar packages direktorija u solutionu je izvedeno uspiješno. 
U packages direktoriju se ponovno pojavio NodaTime.
