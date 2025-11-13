# test-univ-tours

Projet test pour montrer l'utilisation



Ce que le projet va permettre :



* Récupérer des messages
* les stocker en BDD
* les afficher
* utiliser Node-Red





Ajouter une image :



![rafale](IMG\_3257.JPG)


```flowchart TD
       mosquitto[serveur<br>Mosquitto] -->|messages| RPi[Raspberry Pi<br>Node-RED<br>Documentation]
       RPi --> BDD
       RPi <--> GitHub
```


```mermaid
flowchart TD
   github --> |git clone URL|local
   local --> |git push origin main| github
   github --> |git pull origin main| local
   local --> |edition / creation<br> fichiers| local
   local --> |git add file1 file2| index
   index --> |git commit -m ...| local
```
