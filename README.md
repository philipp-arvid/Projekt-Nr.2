# Projekt-Nr.2

Blog Nr.2

10.01.2023 Zuerst gab es heute die Noten für unser letztes Projekt. Dazu gab es noch einige Rückmeldungen und uns wurde etwas zum neuen Projekt und den Möglichkeiten erzählt. Wir haben uns aufgrund des Erfolgreichen Projekts des letzten Halbjahres entschlossen weiterhin zusammenzuarbeiten. Die Grundidee des neue Projekts haben wir uns schon im letzten Halbjahr überlegt. Heute haben wir dann die Projektseite und den Blog für unser Projekt erstellt. Wir haben uns noch genauer überlegt wie wir das Projekt umsetzten wollen.

11.01.2023 Heute haben wir uns überlegt, welche Teile wir für unser projekt benötigen und fragen welche von denen schon in der schule vorzufinden sind, und welche wir uns selber beschaffen werden. Anschließend haben wir den Schuhkarton mit Aluminiumfolie ausgekleidet und uns danach schonmal einige videos und Websiten angeguckt, um schnmal einige Informationen zu sammlen wie genau wir unser projekt relisieren können. Außerdem haben wir uns über den Wärmesensor besonders informiert und überlgen uns nun , wie wir den Ntc Therministor kalibirieren können. Dafür haben wir auch schon einen generellen Aufbau, wie man den Ntc Therministor steuert. Diesen wollen wir dann nächste Woche kalibrieren.

17.01.2023

Heute haben wir die ersten Materialien zusammen getragen. Nun haben wir eine 25 Watt Glühbirne und müssen uns jetzt überlegen, wie oder welchen Transistor wir brauchen um Strom aus der Steckdose steuern zu können. Als nächstes müssen wir uns auch übelergen, wie wir unseren Wärmesensor kalibrieren. Doch dies ist nicht ganz einfach, da der Npc Wärmesensor nicht linear funktioniert.

18.01.2023

Heute haben wir einen ersten Schritt geschafft. Wir haben es geschafft, auch nach Problemen den Wiedertstand des NTCs auszulesen. Als nächstes müssen wir den NTC Wiederstan in eine Temperatur umrechnen. https://forum.arduino.cc/t/ol-temperatur-messen-welcher-oltemperaturgeber-kfz/152055/12#msg1170722 https://www.mymakerstuff.de/2018/05/18/arduino-tutorial-der-temperatursensor/

24.01.2023 heute haben wir weiter recherchiert, wie man einen Ntc Wiedersandswert in Temperarur umrechnet. Da haben wir eine wuelle schon gefunden, doch leider hat das noch nicht geklappt- hier ist der code damit wir nicht immer ein halbe stunde wieder auf dem Stand von der stunde davor kommen müssen .

25.01.2023

Heute haben wir mit einem code, den wir auf der Website(/www.mymakerstuff.de/2018/05/18/arduino-tutorial-der-temperatursensor/) gefunden haben, versucht den Ntc Wiederdtand in eine Temperatur umzuzrechnen. Dabei wird sich auf die Steinhart-hart-Gleichung bezogen. Doch dieser Code hat nicht geklappt, weshlab wir uns anschließend gefrgat haben, owran das leigen könnte. Wir haben gedacht es könnte daran liegen, dass wir anders als bei unserer Quelle im  Internet einen anderen Wiedersntand in Reihe geschaltet haben und oder einen anderen Thermisnistor haben. Dass wir einen anderen Therministor haben könnte eine Rolle spielen, da jeder Thermistor einen spezifischem B-wert hat. Da wir nicht wussten, was für ein B-Wert unser Thermistor hat, müssen wir durch eine Formel, welche Tempertaurmesswerte in KOmbinationen mit den jeweils zugehörigen Wiederstandsmesswerten nutzt, um den Materialspezifischen B-wert bestimmen. Dies werden wir in den nächsten Stunden verfolgen.

heute wasserkocher, weiter probiert, mehrere websites, herr buhl hat nicht geklappt, B wert ist abhänging von der dfunktion , neuer Thermistor mit board für nächste woche, auch selbser probiert mit float

31.01.2023
Tatsächloch hat sich herausgestellt, dass wir nicht nur einen anderen Thermistor und Wiederstand verwenden, es ist auch der Code grundsätzlich fehlerhaft, den wir von unserer Quelle entnommen hatten. Heute haben wir daher den überarbeiteten code von herr Buh( sehr freundlich) angteguckt und verstanden. Dabei planen wir in der nächsten Doppelstunde mit einem präzisen Thermometer 3 Punkte für die Steinhart Hart Formel zu bestimmen, um dann genauerer Messwerte vom Ntc zu bekommen. Unser Fehler lag darin, dass wir  unsere Quelle mit dem tutorial nicht hinterfragt hjaben und somit hat das Bestimmen der Temperatur duch den Ntc nicht geklappt. Ein Fehler war, dass der maximale Bitwert nicht 1024 war, sonder 1023 bei 5V und bei der Korrektur dieses fehlers hat anschließend das Messen grundsätzlich funktioniert. Auch hatten wir zum Beispiel eineni falschen Wiederstand in Reihe geschaltet. Der Serienwiederstand in unserem Schaltkreis hatte nur 1k Ohm, doch damit es zu einer besseren Messung kommt, sollten der Nennwiederstand des Ntcs und der Wiederstand des Serienwiederstandes möglichst gleich sein. Denn dann können die Unterschiede in den Wiederständen deutlich feiner unterschieden werden und so kommt es zu genaueren Messwerten. Also habenw ir heute gelernt unsere Quellen zu hinterfrgaen und sobald wir Informationen aufnehmen auch mit anderen zu verghleichen und gegebenfalls selbst nachzudenken. Gerade kommt es bei einer tatsächlichen Tempertatur von 19 bis 20 Gtrad zu einem Messwetr von 27 Grad. Wir hoffen , dass wir durch die neue Kalibrierung genauere Messwerte bekommen können. 

01.02.2023
Eis, kochendes wasser, Parameter rechner ausrechnen, Steinhart hart formel, haben es geshcafft, neuee Werte eingesetzt 

02.02.2023

Thermistor funktioniert, Transistor recherchieren, Thermistor testen, Glühbirne anschliessen ( nächster Schritt) 

08.02.2023

Huete aufbau von her bzhl thermistor angeguckt, plam für freitag, Kabel sichern, trnasistor mit 230 V, Kabelschuhe holt Herr buhl, Aufbau dann am Fteiitag

10.02.2023

erstmal haben wir die Kabel verbunden, indem wir gelötet haben. ein aufbau hergestellt, dass die Lampe über den Transostor gesteiert wird. Getestet, ob der stromkreis funktionmiert, ohn eden Transistor enzuschakten, und anschließend haben wir mit dem transistor einen Fehlstrom erzeugt. dasdurch hat sich herausgestellt, dass etwas m aufbau nicht korrekt war und in der nächstenm Stunde werden wir den aufbau überarbeiten müssen. 

15.02.2023 

Heute haben wir recherchiert, um mit einem relay die nächste Stunde einen richtigen aufbau erzielen zu können. Dieser wird uns nächste Stunde zu verfügung stehen und dann können wir hoffentlich mit seperaten Stromkreisen den Transistor richtig steuern. Wir haben us Videos angesehen und mehrere Internetseiten durchgelesen. Dadurch haben wir uns den genauen Aufbau aus mehreren Internetseiten zusammmengeplant. Nächste Woche können wir dies dann aufbauen und haben damit dann den Aufbau unseres Projekts so gut wie fertig

22.02.23
Heute aufbau, test mit irgentwa; FREITAG cODE SCHREIBEN für relay test mit LED dnach mit glühlampe

24.02.23

relay weiter ausprobiert, lange nicht geklappt, Beschriftung vertauscht, relay 4er Module probiert mit voltMeter- auch nicht geklappt. Danach probiert an der Schaltstelle (Input am Relay)  mit einer externen Netztstelle einen Impuls zu senden. Das hat gekllappt, abver erkenntnis man braucht LOW für Schalter nicht HIgh bei relay. Dadurch hat sich alles gfeklärt und wir haben die Gölühbirne angeschlossen und mit einem einasch if code den Schwellenwert für das Schalten bei 25 grad gesetzt. Dies hat geklappt und als nächstes müssen wir den Aufbau in den Schuhkarton bringen und danach mit PID steuern. Als letztes noch Ventilator.- 

01.03.2023

Heute aufbau im Schuhkarton, erster Test mit ferttigem Aufbau, Test erflogreich und nun nächstes Ziel: PID programmieren und damit di Glhülmape steuern, PID Recherche, Planung Arvid nächste Woche nicht da
