# Esercizi Develhope vacanze di Natale 2021

## Esercizio 1

Obiettivo: Leggere il contenuto di un file con l'uso di **fs e Promise**.
La libreria **fs** fornisce una serie di metodi per l'interazione con il file system e i file che vi sono dentro.
Per leggere il contenuto di un file è necessario, anzitutto importare la libreria con il seguente codice:
```
const fs = require('fs');
```
E successivamente usare il seguente metodo:
```
fs.readFile('nome o percorso del file', 'utf8', (err, data) => {
  Operazioni varie
});
```
Attenzione! La lettura di un file non è immediata e comporta un delay più o meno grande in base alla grandezza del suo contenuto.
Si richiedere l'utilizzo di una Promise che permetta di gestire liberamente la lettura di un file.
Il parametro **utf8** indica la codifica del file (maggiori info: https://it.wikipedia.org/wiki/Codifica_di_caratteri)

## Esercizio 2

Gli Elfi che si occupano della contabilità al Polo Nord hanno commesso qualche errore sulle note spese di quest'anno.
Babbo Natale è infuriato e ha chiesto a te di sviluppare una serie algoritmi per risolvere i problemi che sono stati creati!

### Problema 1
Sviluppa un algoritmo che legga i numeri nel file **input.txt e li memorizzi in un array**.
Una volta fatto ciò trova al suo interno due numeri che, sommati fra loro, diano come risultato 2020. Una volta trovati fanne una moltiplicazione e stampa il risultato di quest'ultima.
Se tutto è andato a buon fine il risultato dovrebbe corrispondere al numero **927684**.

### Problema 2
Gli Elfi della contabilità ti ringraziano per aver trovato l'errore, ma ti propongono una sfida in più, questa volta non dovrai più cercare solo due numeri che sommati fra loro diano come risultato 2020, ma ne dovrai cercare ben tre! Come prima, una volta trovati, moltiplicali e stampa il risultato.
Se tutto è andato a buon fine il risultato dovrebbe corrispondere al numero **292093004**.
