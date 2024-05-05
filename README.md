# Progetto finale classe 4ELEB: gestione del ciclo di lavorazione in ST con macchine a stati finiti evolute
Progetto per TwinCAT3 da completare da parte degli studenti della classe 4ELEB A.S. 2023/2024

## Istruzioni per l'uso di questo repository
1. iniziare una sessione su GitHub con le proprie credenziali
2. dalla riga dell'indirizzo del browser, visitare il repository: https://github.com/damoreluc/4ELEB_CicloLavorazione_ST
3. Passare alla pagina `<>Code` del nuovo repository
4. Clic sul pulsante verde `<>Code` e copiare l'indirizzo del nuovo repository da clonare localmente: https://github.com/damoreluc/4ELEB_CicloLavorazione_ST.git
5. nel ***proprio PC***, aprire la cartella principale dei progetti TwinCAT, di solito è `Documenti\TcXaeShell`
6. da qui avviare un __terminale di Windows__ col comando `clic destro -> Apri nel terminale`
7. clonare il repository digitando nel terminale il comando 
   > `git clone https://github.com/damoreluc/4ELEB_CicloLavorazione_ST.git`
   
   il repository remoto verrà clonato localmente in una nuova cartella con lo stesso nome del repository remoto, dentro il percorso principale dei progetti TwinCAT `Documenti\TcXaeShell`

9. *opzionale* verificare la correttezza dell'ultima operazione col comando `git status`, dovrebbe fornire un messaggio simile:

        On branch master
        Your branch is up to date with 'origin/master'.

        nothing to commit, working tree clean

8. chiudere il terminale di Windows
9. avviare **TwinCAT3**
10. dal menu `File -> Apri... -> Progetto/Soluzione`, selezionare il progetto appena clonato ed aprirlo. 
Nel riquadro in basso a destra della finestra di TwinCAT3 XAE verrà indicato il nome del repository locale del progetto e il nome del branch attivo.
11. Il compito lasciato agli studenti consiste nell'analizzare i diagrammi SFC degli stati delle machine a stati finiti di zona e del coordinatore, scegliere una delle sette MSF e di svilupparne il codice delle strutture `case of` negli FB:
    - FB_FSM _( coordinatore )_
    - FB_Z1_FSM _( Zona Z1 )_
    - FB_Z2_FSM _( Zona Z2 )_
    - FB_Z3_FSM _( Zona Z3 )_
    - FB_Z4_FSM _( Zona Z4 )_
    - FB_Z5_FSM _( Zona Z5 )_
    - FB_Z6_FSM _( Zona Z6 )_
13. procedere con le modifiche del codice come richiesto dal nuovo progetto ed utilizzare i comandi della sezione **Team Explorer** di TwinCAT3 XAE per il commit e la sincronizzazione col repository remoto in GitHub.
