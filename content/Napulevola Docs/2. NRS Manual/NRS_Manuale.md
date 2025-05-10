# NRS: Napulevola Report System  
## Manuale dell’utente  
**Autori**: Giovanni Mantellini – Raffaele Carusi  
**Data**: 13/05/2020  

---

## Sommario  
1. [Introduzione](#introduzione)  
2. [Come iniziare](#come-iniziare)  
3. [Configurazione iniziale di NRS](#configurazione-iniziale-di-nrs)  
4. [Caricamento di un volo di compagnia VA](#caricamento-di-un-volo-di-compagnia-va)  
5. [Richieste di assistenza e supporto](#richieste-di-assistenza-e-supporto)  

---

## Introduzione  
Napulevola Report System (NRS) è un sistema integrato per la gestione della carriera dei piloti Napulevola. Con una semplice interfaccia, il pilota esegue e registra i voli di compagnia, al termine dei quali verrà "valutato" con un punteggio per la sua carriera di pilota Napulevola.

Il registratore è compatibile con FSX, P3D e X-Plane v10-v11 ed è a disposizione di tutti i piloti Napulevola iscritti.

---

## Come iniziare  
Scaricare NRS dalla pagina [http://www.napulevola.it/NRS/](http://www.napulevola.it/NRS/).  
È necessario essere registrati alla VA Napulevola. Puoi iscriverti [qui](http://www.napulevola.it/comunita/iscrizione.aspx).  
![[Pasted image 20250510064904.png]]
Clicca sul bottone di download e salva il file `.zip` dove preferisci. Estrai l’archivio in una nuova cartella, ad esempio sul Desktop.

**Esempio immagine cartella estratta:**  
![[Pasted image 20250510065048.png]]

---

## Configurazione iniziale di NRS  
Cliccare sull’icona `NRS.exe` nella cartella estratta.

Si aprirà il box di login: 
![[Pasted image 20250510065147.png]]
- Inserire solo la parte numerica del proprio callsign e la password.  
- Selezionare "Ricordami" e cliccare "Pilot Login".  
- Collegamento al server NPV confermato.

![[Pasted image 20250510065431.png]]
Al primo avvio NRS caricherà dal server il databse degli aeroporti. Questa operazione viene effettuata solo al primo avvio ed avviene in background. Lo stato sarà visualizzato dalla barra di progresso come da immagine.

NRS può essere personalizzato tramite delle opzioni disponibili nel menu **Preferenze**
![[Pasted image 20250510065743.png]]
**Log Directory:**  
- Menu → Preferenze → Log Directory 
- Di default la directory per i file di log è /Documenti/NRS/LogData. E' importante conoscere la location della cartella nel caso i file di log servano allo Staff NPV per operazioni di debug

**Avvio automatico con Windows:**  
- Menu → Preferenze → Carica all’avvio di Windows  
- Per rimuoverlo: “Rimuovi dall’avvio di Windows”

**Minimizzazione all’avvio:**  
- Menu → Preferenze → Minimizza all’avvio  

**Notifiche:**  
- Per disattivarle: cliccare su "Disattiva Notifiche" 

Si può inoltre scegliere se inviare automaticamente il report di volo dal menu **Gestione Volo**

**Auto invio del report:**  
- Menu → Gestione volo → Auto Invia Report [ON]  
- Disabilitare cliccando nuovamente (diventa [OFF])

![[Pasted image 20250510065831.png]]

---
## Caricamento di un volo di compagnia VA  

- Avviare il simulatore e posizionarsi sull’aeroporto scelto.  
- Prenotare il proprio volo sulla piattaforma www.napulevola.it
- Lanciare NRS. Al primo avvio il volo verrà caricato automaticamente
![[Pasted image 20250510070344.png]]

**Dati mostrati:**  
- Zero Fuel Weight (ZFW)  
- Block Fuel  
- Aeromobile scelto  

**Caricamento manuale:**  
Se NRS era già aperto il volo non sarà caricato automaticamente ma dovrà essere caricato dal Menu NRS -> Carica Volo

**Simulatore connesso:**  

**Suggerimento:**  
Per ottenere il bonus online, collegarsi prima a IVAO/VATSIM e poi cliccare “Start REC”.

**Utenti FSX/P3D:**  
Configurare Ivap correttamente per permettere a NRS di rilevare il collegamento online.

**Verifica ZFW:**  
NRS tollera ±3% rispetto al valore indicato nel flightsheet.

### Stato iniziale richiesto:
- Flight Phase: Departure  
- Flight Status: Online/Offline  
- Autenticazione: Online  
- FDR Status: Connected  

In caso di errore: chiudere e riaprire NRS e ricaricare il volo.

**Durante il volo:**  
- Flight Phase cambia automaticamente.  
- Dopo il decollo → “In Flight”  
![In Flight](imgs/stato_inflight.png)  
- A destinazione → “OnBlock”  
![On Block](imgs/stato_onblock.png)

**Invio report:**  
- Alla richiesta, cliccare “Sì”  
![Conferma invio report](imgs/invio_report_confermato.png)  
- Conferma invio → punteggio visibile su [napulevola.it](http://napulevola.it) → MyNPV → I Miei voli

---

## Richieste di assistenza e supporto  
Per chiarimenti o supporto, unisciti al server Discord:  
[https://discord.gg/jFmMuBs](https://discord.gg/jFmMuBs)

---

Buon divertimento dallo staff Napulevola!
