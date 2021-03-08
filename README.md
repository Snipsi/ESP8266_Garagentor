# ESP8266 Garagentor
## Übersicht
"Wunschlos glücklich"-Paket für Garagentore:
- Ein Relais löst den Garagentorantrieb aus (Tastimpuls). 
- Magnetkontakte werden abgefragt um den Öffnungszustand des Tores zu erkennen.
- Eine LED-Leiste (WS2814) blinkt während der Torbewegung rot, in Endlage des Tores leuchtet sie einige Sekunden grün.
- Steuerung über einen integrierten Webserver und Alexa-Integration.
- Für die Entwicklung könnenn Informationen über ein OLED Display (SSD1306) ausgegeben werden. 
- Eine Blink Mini-Indoor Kamera wird von vom Netzteil der Box mit Spannung versorgt.

## Hardware
- ESP8266 Bord mit OLED und Batteriehalter (Warum dieses? Nun - ich hatte noch 3 Stück davon rumliegen und wollte nichts Neues kaufen. Andere ESP8266 mit mind. 3 freie GPIOs, z.B. NodeMCU, funktionieren bestimmt genauso. Der Batteriehalter wird in diesem Projekt nicht gebraucht, deshalb habe ich ihn aus Platzgründen abgelötet.)
- WS2814 LED Strip, eingeklebt in ein Stück Rest-Alu-Profil mit diffuser Abdeckung.
- 1-Kanal Relay, 5V/230V
- 5V / 3W Netzteil
- Kabelabzweigkasten (hier: OBO T160) als witterungsgeschütztes Gehäuse
