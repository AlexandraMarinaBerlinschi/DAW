# DAW
## Dezvoltarea Aplicatiilor Web utilizand ASP.NET Core MVC

Platforma “Collective Knowledge” cu urmatoarele functionalitati:
* Sa existe 3 tipuri de utilizatori: vizitator neinregistrat, utilizator inregistrat si administrator 
* Utilizatorii neinregistrati pot sa vada pagina de prezentare a platformei si formularele de autentificare si inregistrare 
* Pe prima pagina (pagina de prezentare) vor aparea mai multe categorii de discutie. In fiecare categorie vor exista mai multe subiecte de discutie 
* Orice utilizator (neinregistrat si inregistrat) poate vizualiza subiectele de discutii din diferite categorii si raspunsurile la discutiile respective 
* Subiectele dintr-o categorie pot fi vizualizate intr-o pagina noua. In cazul in care o categorie are mai multe subiecte de discutie, acestea vor fi afisate paginat 
* Discutiile si raspunsurile vor fi afisate sortat in urma unor criterii stabilite de utilizator (se aleg doua criterii) 
* Platforma va avea un motor de cautare propriu cu ajutorul caruia utilizatorii pot cauta diferite subiecte de discutie si raspunsuri. Cautarea se va face dupa cuvinte cheie aflate in subiectele de discutie si in raspunsuri
* Utilizatorii inregistrati isi pot crea un profil pe care il pot si edita 
* Utilizatorii inregistrati pot initia subiecte de discutie noi si pot trimite raspunsuri la alte discutii
* Utilizatorii neinregistrati pot doar sa vizualizeze. Subiectele de discutie si mesajele deja trimise vor putea fi modificate si sterse ulterior de autor 
* Administratorul se ocupa de stergerea discutiilor si mesajelor care au continut neadecvat si de plasarea subiectelor de discutie in categoria corespunzatoare lor. 
* Administratorul adauga categorii noi de subiecte si poate face CRUD pe categorii (poate vizualiza, crea, modifica si sterge).
* Tot administratorul este cel care asociaza sau revoca drepturile membrilor
