# ProcessMaker-Use-Case-Automated-Material-Request
Dopo aver scaricato progetto e sottoprogetto, importarli: da tab "Desgin" cliccare su "import"
![immagine](https://user-images.githubusercontent.com/88326107/204031930-7b2cbd54-46ce-4249-b37d-d542d56f0cb8.png)
Cliccare sul pulsante della cartella, per scegliere il file da importare
![immagine](https://user-images.githubusercontent.com/88326107/204571547-d9907fbd-34c0-4ad0-8570-45f107e42d83.png)

Cliccare su "upload" e ripetere per il sottoprogetto
![immagine](https://user-images.githubusercontent.com/88326107/204571935-5a544fef-a91b-4d39-bd3c-020cbc0745ea.png)

Ora potete vedere i progetti importati nell'elenco dei progetti
![immagine](https://user-images.githubusercontent.com/88326107/204572224-575479d3-0edb-4fb2-97e5-baf4018d76b5.png)

Ora è necessario creare i profili degli users, ed associarli ai task.
In questo progetto, i profili coinvolti sono: 

-un impiegato, che effettuerà la richiesta di materiale

-un magazziniere, che verificherà la presenza del materiale richiesto in magazzino e, se presente, lo consegnerà all'impiegato; se non è presente, effettuerà la richiesta di acquisto, e consegnerà il materiale all'impiegato quando arriva

-il responsabile dell'ufficio acquisti, che in caso di necessità, approverà la richiesta di acquisto ed effettuerà l'ordine

Per creare un user:
Dal tab "Admin" cliccare su "Users". Se non avete ancora creato users, il riquadro a destra sarà vuoto.
Cliccare su "New". 
![immagine](https://user-images.githubusercontent.com/88326107/204602387-81ae5f2c-582b-46ba-bece-6c341c17fae7.png)
Apparirà una form da compilare con i dati del nuovo utente. 
![immagine](https://user-images.githubusercontent.com/88326107/204602567-31beffb5-224c-496b-965f-206fa0efb3f3.png)
Compiliamo almeno i campi obbligatori; "Expiration Date" può essere lasciato come è preimpostato. Salviamo lo user creato, cliccando su "Save"
![immagine](https://user-images.githubusercontent.com/88326107/204605723-4c50441c-dfe6-439d-a283-71e321307b34.png)
Ripetiamo l'operazione per creare gli altri user.

ATTENZIONE: per la maggior parte degli user il role può essere impostato come "operator"; per il Responsabile dell'ufficio acquisti, che all'interno dell'azienda è un manager, impostiamo il role come "Manager"
![immagine](https://user-images.githubusercontent.com/88326107/204610336-4f755152-3ebf-429e-a74e-9c182cfeba26.png)

.XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXx
.



Per ogni task, cliccate col pulsante destro sul task e selezionate "Assignment Rules"
![immagine](https://user-images.githubusercontent.com/88326107/204337836-133c179e-946a-413d-af2b-94d7b9a9d420.png)
Dall'elenco sulla sinistra ("Available Users List") prendete un profilo e trascinatelo nel riquadro sulla destra ("Assigned Users List")
![immagine](https://user-images.githubusercontent.com/88326107/204338226-a531e8c8-d10b-4d65-b4b6-ef11a9dca958.png)

.
.

![immagine](https://user-images.githubusercontent.com/88326107/204323401-88b5d9e0-f875-4cfe-bb13-12c9d77832c0.png)
.
![immagine](https://user-images.githubusercontent.com/88326107/204323599-fda85598-21b3-4d20-85c3-fb01c538d2df.png)
.





![immagine](https://user-images.githubusercontent.com/88326107/204328032-4696c194-1c2c-42cc-b90a-4393d94e006b.png)
.
![immagine](https://user-images.githubusercontent.com/88326107/204328111-602099e9-d767-4c8f-9bc6-ae01dc541804.png)

