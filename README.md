# test\_iut new

Projet test pour montrer l'utilisation

Ce que le projet va permettre :

* récupérer les messages
* les stocker en BDD
* les afficher
* utiliser Node-RED



Commandes : 
- git clone [code du dossier GitHub (http://...)]
- cd [nom du projet (test_iut)]
- git add [nom du fichier (README.md)]
- git commit -m "Modification du README"
- git push origin main (pour envoyer du local ver GitHub)
- git pull origin main (pour envoyer de GitHub vers le local)

Ajouter une image :
![Robot](Robot.jpg)

```mermaid
flowchart TD
    mosquitto[serveur<br>Mosquitto] --> |message| RPi[Raspberry Pi<br>Node-RED<br>Documentation]
    RPi --> BDD
    RPi <--> GitHub
```



