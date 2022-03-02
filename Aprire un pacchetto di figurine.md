Aprire un pacchetto di figurine

Che emozione, ogni volta che apro un pacchetto nuovo... chissà se troverò quella figurina così rara!
Dopo averle sfilate dal pacchetto, me le passo tra le mani controllando nell’album:
attacco subito quelle nuove, mentre le doppie le metto in un mazzetto a parte. 
Ormai ne sto accumulando diverse, spero di riuscire a combinare diversi scambi sabato con i miei amici! 

ELEMENTI IMPORTANTI PER L'ESECUZIONE DELL'ESERCIZIO

#Npacchetto
#Pila di carte
#Figurina(si suddivide in){
    #fnuova (Figurina nuova)
    #fdoppione (Figurina Doppione)
}
#album
#piladoppioni

-Apertura pacchetto (start)
-creazione pila carte per effettuare i vari controlli 
-confrontiamo ogni singola carta della pila carte per verificare quali sono fnuova e fdoppione
-controlloare figurina
if(figurina==fnuova){ 
    aggiungere all' album
}
else{
    aggiungere Fdoppiona al album piladoppioni
    Fdoppiona scambio per f nuova con amici il sabato sera
    if (Scambio avviene){
        aggiungere all'album
    }
}
verificare che pila carte non contenga nessun elemento, se questo è vero, allora procedere con lo scambio delle carte il sabato sera, se questo è falso ricominciare il ciclo da capo