<p align="right"><img src="maestri-logo.png" alt="MAESTRI" width="360"></p>

# Milestone Export Analyzer

**Controlla gli esportati Milestone e prepara i documenti da consegnare al cliente.**

Seleziona un disco USB o una cartella: il programma raccoglie le informazioni sugli esportati, mostra le telecamere e gli intervalli disponibili e prepara i report.

## Scarica la demo

**[Scarica la demo per Windows](https://github.com/maestrir/Milestone-Export-Analyzer/releases/tag/v0.5.1-demo)**

Nella sezione **Assets**, scegli `MilestoneExportAnalyzer_Demo_v0.5.1.exe`. Non occorre scaricare gli archivi “Source code”.

La demo è utilizzabile fino al **25 dicembre 2026 compreso**, secondo l'orario italiano. I report già creati restano consultabili anche dopo la scadenza.

## Cosa puoi controllare

- Esportati trovati, telecamere, intervalli di registrazione e spazio occupato.
- Nome, modello, seriale hardware e capacità del supporto: per esempio un disco da 2 TB, con il dettaglio dello spazio occupato dagli esportati.
- Versione Milestone del progetto esportato e versione del Player, quando disponibili.
- Primo e ultimo fotogramma per ogni telecamera, quando il video può essere decodificato.
- Eventuali avvisi utili al controllo tecnico.

## Due report con un solo tasto

Premendo **Esporta report**, il programma crea la cartella `REPORT_nome-supporto`. Anche i nomi dei documenti riportano il nome del supporto.

**Report tecnico completo**  
Contiene i dati dell'analisi, i percorsi, gli avvisi e i fotogrammi disponibili.

**RAPPORTO TECNICO PER CONSEGNA**  
È il documento essenziale da stampare e accompagnare al disco. Riporta i dati del supporto, le dimensioni, gli esportati, le telecamere, gli intervalli e le versioni rilevate. Non contiene immagini, avvisi, percorsi completi delle cartelle o data di esportazione.

Sono inclusi anche i riepiloghi CSV. I report HTML si aprono nel browser e possono essere stampati o salvati in PDF.

## Come si usa

1. Scarica e avvia l'EXE.
2. Seleziona il disco o la cartella che contiene gli esportati.
3. Avvia l'analisi e attendi il completamento.
4. Controlla i risultati e le anteprime.
5. Premi **Esporta report**.

## Requisiti

- Windows a 64 bit.
- .NET Framework **4.8 o 4.8.1**.
- Spazio libero per i componenti estratti al primo avvio e per i report.

I componenti di lettura sono inclusi nell'EXE: non è necessario installare separatamente lo Smart Client Player.

## Compatibilità e prove

Sono stati analizzati campioni di esportazione Milestone **2020 R3, 2023 R3 e 2025 R3**. La compatibilità con tutte le versioni e tutte le varianti di esportazione non è ancora verificata.

La lettura video prevede H.264 e H.265; il risultato dipende dal formato dell'esportato e dal decoder. Le anteprime 4K/H.265 e il ridimensionamento su Windows richiedono ulteriori prove sui diversi sistemi: questa versione è pubblicata come **demo in prova**.

Il programma cerca progetti di esportazione Milestone con file SCP. Gli archivi ZIP vanno prima estratti. La lettura dei soli file AVI/MKV e l'inserimento di password per esportati protetti non sono previsti in questa versione.

Il seriale hardware è quello comunicato a Windows dal dispositivo o dal box USB e può non essere disponibile. Gli intervalli rilevati non attestano la continuità o l'autenticità delle registrazioni.

## Segnalazioni

Per segnalare un problema, apri una **Issue** indicando versione del programma, Windows, versione Milestone dell'esportato e messaggio di errore. Non caricare filmati o dati riservati dei clienti.

---

Progetto **MAESTRI — Roberto Maestri**. Software indipendente, non ufficiale Milestone. Questo repository contiene documentazione e demo; il codice sorgente dell'applicazione non è pubblicato.
