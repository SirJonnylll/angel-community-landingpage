Für die Einsendeaufgabe habe ich mir als Projekt wieder die Angel-Community-App ausgesucht.
Mein Ziel war es eine Landingpage für meine Website zu erstellen. Diese ist sehr einfach aufgebaut, da dass eigentliche Ziel der Aufgabe sein sollte, sich mit GItHub vertraut zu machen und etwas über die Versionskontrolle zu lernen.

Zur unterstützung habe ich ChatGPT verwendet. Primär wurde ChatGPT verwendet, da ich Probleme hatte mein Git mit GitHub zu verbinden. 

1.Schritt: Ich habe lokal ein Projekt über GitBash vorbereitet
  Hierfür habe ich folgendes eingegeben:
  
    mkdir angel-community-landingpage --> Verzeichnis erstellen
    cd angel-community-landingpage --> Hier wird das Arbeitsverzeichnis in Bash geändert, siehe Screenshot
    git init --> wird initialisiert

![image](https://github.com/user-attachments/assets/0e31591a-a475-43c0-ac47-3e37087bcc44)

2. Schritt: Erstellen einer .html im Verzeichnis

    "echo "<h1>Willkommen zur Angel Community</h1>" > index.html"

3. Schritt: Genannte Git-Befehle anwenden:

//Leider ist mir Bash zwei mal abgestürzt. Daher folgen jetzt teilweise Screenshots aus der Historie von Bash

status:
![image](https://github.com/user-attachments/assets/f01939cb-cdfe-459c-be7d-ce69c1984427)

commit: erstellen, umbennen und löschen
![image](https://github.com/user-attachments/assets/93c0c0d3-de05-4d76-b197-ff000b2ee764)

log anzeigen:
![image](https://github.com/user-attachments/assets/d8500c1e-10bb-4549-903a-2746616516a9)

Zeitreise mithilfe von git log und git checkout 

![image](https://github.com/user-attachments/assets/9c7ddd09-7284-45e8-93bd-0f3b3910cc23)


4. Schritt: Mit GitHub verbinden und lokales Verzeichnis pushen

git remote add origin git@github.com:SirJonnylll/angel-community-landingpage.git
git branch -M main
git push -u origin main


Alle weiteren Änderungen sollte man im Github sehen

Für den Pullrequest - https://github.com/edlich/education/pull/551

