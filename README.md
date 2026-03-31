RobertsRobotBar Prototype

Dette projekt er en tidlig prototype af et system til at styre en Universal Robots robotarm til at mixe drinks.

Formålet med prototypen var at etablere en simpel løsning til kommunikation med robotten og afvikling af drink-scripts. 
Projektet blev anvendt i praksis i forbindelse med Tønder Festival.

Funktionalitet:
Kommunikation med robotten via TCP
Afvikling af scripts til drink-mixing
Simpel brugerflade til valg af drinks
REST API som bindeled mellem frontend og robot

Teknologi:
Python
Flask (REST API)
HTML frontend
SQLite database
TCP kommunikation til robot
Arkitektur

Frontend er implementeret i HTML og kommunikerer med backend via HTTP requests.

Backend er opbygget som en REST API i Flask, som:

Modtager requests fra frontend
Sender kommandoer til robotten via TCP
Håndterer simpel logik for afvikling af scripts sekventielt

SQLite blev anvendt til at gemme data som opskrifter og konfiguration.
