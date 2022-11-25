# PROGETTO-BD-OO
Progetto bd oo , libreria musicale


DA CORREGGERE 
la funzione decrypt e encrypt funzionano perfettamente ma se si aggiornano i dati relativi alla tabella utente 
non puo risalire alla password utente tramite la funzione decrittografia, perchè la funzione crypt di pgcrypto , crittografa 
la password in base alle colonne presenti nella tabella utente 

SOLUZIONE 
elimnare le funzioni decrittografia e crittografia nel db e sostituirle con delle funzioni nell'applicativo di java, cosi che 
all'inserimento di un nuovo utente nell'aplicativo, la password viene crittografata e inserita nel db insieme ai dati dell'utente

