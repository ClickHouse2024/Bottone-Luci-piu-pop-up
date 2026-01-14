# Bottone Luci
Bottone conteggio luci accese con pop up interattivo per gestione luci

## Bottone
![Anteprima](bottone.png)
## PopUp
![Anteprima](popup.png)

## Descrizione
Breve spiegazione di cosa fa questa configurazione.
Esempio:
Questa configurazione permette di monitorare la quantita di luci accese
e cliccandolo la possibilita di accendere/spegnere le luci oppure cambiare intensita
luminosa o colore
## Dipendenze
Per utilizzare questo codice sono necessari:
- Home Assistant aggiornato
- Luce compatibile
- Mushroom card (scaricabile tramite HACS)
- Bubble-card (scaricabile tramite HACS)

## Importante

la parte di codice del bottone
tap_action:
  action: navigate
  navigation_path: "#Light-total"

e la parte di codice del popup
card_type: pop-up
    hash: "#Light-total"

devo vere in navigation_path e in hash lo stesso nome esempio: "#generale-luci"


## Note
Configurazione mostrata nel video TikTok.
Adattare entity_id e nomi in base al proprio sistema.
