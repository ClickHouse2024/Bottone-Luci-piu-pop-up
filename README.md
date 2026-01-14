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
- Mushroom card (scaricabile tramite HACS) https://github.com/piitaya/lovelace-mushroom
- Bubble-card (scaricabile tramite HACS) https://github.com/Clooos/Bubble-Card

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


## Hardware Utilizzato

- Relè zigbee Sonoff ZBMini Extreme (no neutro)
  👉 https://amzn.to/4pIKrLP
- Lampada Govee da terra con base luminosa
  👉 https://amzn.to/4qiRsnL
- Lampada Govee da terra
  👉 https://amzn.to/4aZ16HB
- Govee COB Striscia LED Pro 3m
  👉 https://amzn.to/3NLMUry
- Aqara Striscia LED T1 con Matter
  👉 https://amzn.to/4qRkN8C

## Affiliazione
I link Amazon presenti sono link affiliati.
Acquistando tramite questi link supporti il canale senza costi aggiuntivi.
