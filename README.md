Aplicația de gestiune a creditelor bancare este necesară pentru a simplifica și eficientiza procesul de gestionare a creditelor oferite de o instituție bancară.

	    Centralizarea și organizarea informațiilor: 

- Permite centralizarea și organizarea informațiilor despre creditele acordate clienților într-un singur loc. \
Aceasta elimină necesitatea de a utiliza documente fizice sau fișiere separate pentru fiecare credit. Utilizatorii pot accesa rapid și ușor toate informațiile necesare despre credite într-o interfață intuitivă.

	    Eficiență în gestionarea creditelor:

- Aplicația oferă funcționalități pentru adăugarea, actualizarea și ștergerea informațiilor despre credite. Utilizatorii pot introduce detaliile relevante despre credite, cum ar fi suma împrumutată, dobânda, durata și alți termeni specifici. Aceasta permite o gestionare eficientă a creditelor, monitorizarea stării lor și generarea rapoartelor relevante.

	    Informații legale și reglementare:

- Aplicația poate furniza informații detaliate despre legislația și reglementările referitoare la diversele tipuri de credite oferite. Utilizatorii pot accesa informații despre dobânzi, durată maximă, sume minime și maxime și alte informații legale relevante. Aceasta asigură respectarea reglementărilor în vigoare și furnizează o sursă de referință utilă pentru informarea clienților.

	

- În plus, aplicația de Gestiune a Creditelor Bancare oferă și funcționalități pentru gestionarea clienților care aleg să ia credite. Aceasta înseamnă că utilizatorii pot introduce și gestiona informațiile despre clienți în aplicație, inclusiv detalii personale, istoricul creditelor și alte informații relevante.

- Am implementat trei clase cheie în aplicația noastră de Gestiune a Creditelor Bancare: "Clienti", "TipuriCredite" și "Contracte". Aceste clase joacă un rol important în gestionarea și organizarea informațiilor referitoare la clienți, tipurile de credite și contractele de credit.

1.	    Clasa "Clienti":

•	Această clasă stochează informațiile despre clienți, inclusiv nume, prenume, sex, soldul contului bancar.

•	Oferă metode pentru adăugarea, actualizarea și ștergerea informațiilor despre clienți.

•	Poate fi utilizată pentru căutarea și vizualizarea detaliilor unui anumit client.

2.	    Clasa "TipuriCredite":


•	        Această clasă definește diferite tipuri de credite disponibile în aplicație, cum ar fi creditele de nevoi personale, creditele ipotecare, creditele auto, etc.

•	        Stochează informații specifice despre fiecare tip de credit, cum ar fi dobânzile asociate, durata maximă, suma minimă și suma maximă.

•	        Furnizează metode pentru accesarea și gestionarea informațiilor despre tipurile de credite.

3.	    Clasa "Contracte":

•	Această clasă gestionează detaliile specifice ale fiecărui contract de credit încheiat între bancă și un client.

•	Stochează informații precum suma împrumutată, dobânda, durata contractului și alte condiții specifice.

•	Oferă funcționalități pentru crearea, actualizarea și stergerea contractelor de credit.

•	Poate fi utilizată pentru generarea de rapoarte și monitorizarea stării contractelor de credit.


	Functiile aplicatiei:

1)		    Gestiune clienti:
-	Utilizatorul poate adauga informatii despre un nou client, modifica si sterge date de asemenea
-	Se poate exporta si importa aceasta lista sub forma unui fisier de tip .txt
-	Se poate scoate la imprimanta un raport al tuturor clientilor aflati in evidenta.

2)		    Gestiune credite:
-	Se poate alege clientul al carui credit va fi finantat
-	Este implementata o functie tip “calculator de credit” care pe baza sumei imprumutate, a ratei dobanzii si a duratei creditului poate determina rata lunara, numarul total de plati, plata totala, dobanda aferante creditului etc.

3)		    Functia de informare legata de tipurile creditelor bancare:

-	Se pot consulta informatii referitoare la cursul valutar (obtinut prin accesarea fisierului de tip XML – sursa: BNR)
-	Datele despre tipurile de credite bancare sunt stocate intr-o baza de date locala Microsoft SQL, iar datele sunt vizualizate intr-un obiect de tipul DataGridView
-	Se pot modifica prin intermediul acestuia datele stocate

4)		    Informatii legale
-	Toate informatiile legale relevante despre tipurile de credite bancare
-	Incarcarea acestor date din memorie
-	Functie de serializare/deserializare
-	Functie de salvare/citire din fisier custom

Meniurile sunt facute astfel incat sa faciliteze experienta utilizatorului, fiind implementate toate butoanele necesare navigarii usoare intre toate functiile aplicatiei.
