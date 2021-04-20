---
title: "Protocolli Romeo"
description: "Sistema Radar"
date: 2020-10-20T14:09:21+09:00
draft: false
---

### Protocollo Romeo (Radar)


***nome in codice: "Romeo"***

### Guida:

{{< img src="/prRomeo/preview_MapLegend.png" width="300px">}} 

    1. Range
    2. Tipo di Targets
    3. Background Mappa
    4. Superfice Mappa
    5. Anelli mappa (33.3%, 66.7%, e 100% del Range)
    6. Indicatore di Distanza
    7. Segnale dell'Entità

##### Esistono 3 tipi di Segnalini che possono comparire nel Radar:

- Triangolo (Navi o Stazioni)
- Quadrato (Giocatori)
- Cerchio (Asteroidi)

##### Questi Segnalini possono avere 5 colori diversi, i quali dipendono dalla ostilità che hanno nei vostri confronti:

- Blu  (proprie griglie)
- Verde (Alleati)
- Giallo (Neutrali)
- Rosso (Nemici)
- Bianco (senza proprietà)

###### Note:

- Per accedere al menù delle impostazioni della mappa: aprire la chat con "ENTER", premere il tasto "F2" e in seguito comparità un menù nel quale potete modificare alcune impostazioni (ClientSide).
- Un asteroide non può avere un propietario e di conseguenza il suo colore sarà sempre Bianco (Nella Mappa).
- Si può aggiungere il Radar anche sui pannelli LCD: accedere al terminale del LCD e nella sezione "Content", inserie la voce "Script" e successivamente selezionare "MiniMap by jTurp".
- Se vi avvicinate ad un LCD con il radar istallato, il vostro radar in alto a destra scomparirà in automatico.
- Esiste una Mappa più grande, simile ad una cartina nautica ma applicata nel ambito spaziale. Tramite una combinazioni di tasti (SHIFT + U) si può accedere alla mappa precedentemente citata. Questa mappa vi permette di visualizzare delle informazioni aggiuntive sulle navi attorno a voi.
- Il Range minimo è 0m e quello massimo è 5000m.

***

##### Key Bindings

| Tasti     				| Funzione 			 			|	Valori		|
|		:----:				|			:----:				|	:----:		|
|	SHIFT + Rotella			|	Zoom in/out					|	X10m		|		
|	CTRL + Rotella			|	Zoom in/out					|	X100m		|		
|	SHIFT + CTRL + Rotella	|	Zoom in/out					|	X1000m		|		
|	SHIFT + M				|	Toggle Map					|	On/Off		|	
|	SHIFT + V				|	Toggle Voxel				|	On/Off		|
|	SHIFT + T				|	Cycle Displayed Entities	|	-			|	
|	SHIFT + B				|	Toggle Bots					|	On/Off		|
|	SHIFT + U				|	Toggle Universe Map			|	On/Off		|

###### Note:

- Le combinazioni "SHIFT + M, V, T, B, U" sono solo dei esempi.
- Per fare il Key Bindings bisogna accedere al menù delle impostazioni e andare sotto la voce "Key Bindings".



##### Comandi Chat

| Comandi    				| Descrizione 			 					|	Valori						|
|		:----:				|			:----:							|	:----:						|	
|	/map range <valore>		|	Imposta un range preciso				|	Valore numerico in metri	|		
|	/map targets <valore>	|	Imposta un target						|	All - F - N - NE - E		|	
|	/map Show				|	Mostra o nasconde la mappa dal HUD		|				-				|
|	/map show cockpit		|	Mostra o nasconde la mappa dal cockpit	|				-				|

	All = tutti
	F = Alleati
	N = solo i Neutrali
	NE = Neutrali / Nemici
	E = solo i Nemici
	
***

### Protocolli Corto raggio

- Romeo - Alpha: Impostare il Range a 1000m. Per scontri ravvicinati o per individuare meglio le entità intorno alla nave.
- Romeo - Beta: Impostare il Range a 2000m. Per ingaggi a corto raggio in fase di combattimento.

### Protocolli Medio raggio

- Romeo - Gamma: Impostare il Range a 2500m - 3000m. Stato di allerta minimo. Per scansione a medio-lungo raggio, utile per quando si è in movimento.

### Protocolli Lungo raggio

- Romeo - Delta: Impostare il Range a > 3000m. Stato di allerta medio-minima. Per scansioni a lunga distanza, utile per segnalare navi in lontananza, per localizzare relitti oppure per viaggi con una velocità pari o superiore a 100 m/s.

***
