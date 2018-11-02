# Esercizi terza lezione
Inserisco qui i testi degli esercizi presenti in questa cartella:


Esercizio 1.xml) Crea un file xml e inserisci un prologo con la dichiarazione XML e un commento con le vostre informazioni

---------------

Esercizio 2.xml) Scrivi un xml non opportunamente annidato e poi fai il check

---------------

Esercizio 3.xml) Correggi il file 2.xml, aggiungi un figlio a un elemento e aggiungi un fratello a un elemento

---------------

Esercizio 4.xml) Inserire all'interno di un tag un frammento di codice HTML. Osservare che, anche se la chiusura dei tag è errata, il parser non da errore perchè non entra nel CDATA

---------------

Esercizio 5.dtd) Definire in una DTD: l'elemento root TEI e i seguenti figli: header (obbligatoria un'occorrenza), facsimile (opzionale un'occorrenza), text (obbligatoria almeno un'occorrenza)- I figli hanno tutti un content model testuale

---------------

Esercizio 6.dtd) Definire in una DTD una root TEI che ha come figli:
- header (obbligatorio una volta sola)
- facsimile (opzionale una volta sola)
- testo (obbligatorio una o più volte)
l'elemento testo è mixed content con possibile elemento "seg"

Gli attributi sono:
- header: type (fixed, CDATA, intestazione); lang (opzionale, NMTOKEN)
- facsmile: source (obbligatorio); ref (opzionale, IDREFS)
- testo: id (obbligatorio ID); type (opzionale, contenuto testuale)