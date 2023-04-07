# Temperatur haltender Schuhkarton


Zurück zur [Projektseite](https://github.com/philipp-arvid/Projekt-Nr.2/blob/main/Projekt%20Nr.2%20projektseite.md)



</br>
</br>
</br>


## Stundenübersicht
<table align="center">
	
    
<tr>
	
<td><a href=#eins>1. Stunde am 10.01.2023</a></td>
<td><a href=#zwei>2. Stunde am 11.01.2023</a></td>
<td><a href=#drei>3. Stunde am 17.01.2023</a></td>
<td><a href=#vier>4.Stunde am 18.01.2023</a></td>
<td><a href=#fünf>5. Stunde am 24.01.2023</a></td>
<td><a href=#sechs>6. Stunde am 25.01.2023</a></td>
	
</tr>
<tr>
	
    <td><a href=#sieben>7. Stunde am 27.01.2023</a></td>
    <td><a href=#acht>8. Stunde am 01.02.2023</a></td>
    <td><a href=#neun>9. Stunde am 03.02.2023</a></td>
    <td><a href=#zehn>10. Stunde am 08.02.2023</a></td>
    <td><a href=#elf>11. Stunde am 10.02.2023</a></td>
    <td><a href=#zwölf>12. Stunde am 15.02.2023</a></td>
</tr>
<tr>
	
    <td><a href=#dreizehn>13. Stunde am 22.02.2023</a></td>
    <td><a href=#vierzehn>14. Stunde am 24.02.2023</a></td>
    <td><a href=#fünfzehn>15. Stunde am 01.03.2023</a></td>
    <td><a href=#sechzehn>16. Stunde am 03.03.2023</a></td>
    <td><a href=#siebzehn>17. Stunde am 08.03.2023</a></td>
    <td><a href=#achtzehn>18. Stunde am 10.03.2023</a></td>
 </tr>
 <tr>

    <td><a href=#neunzehn>19. Stunde am 15.03.2023</a></td>
    <td><a href=#zwanzig>20. Stunde am 17.03.2023</a></td>
    <td><a href=#einundzwanzig>21. Stunde am 23.03.2023</a></td>
    <td><a href=#zweiundzwanzig>22. Stunde am 29.03.2023</a></td> 
    <td><a href=#dreiundzwanzig>23. Stunde am 31.03.2023</a></td>  
    <td><a href=#vierundzwanzig>Finalisierung 06.04 und 07.04.2023</a></td>

      
</tr>	
	   </table>
	
	
	
	
	
 ### 1. Stunde vom 10.01.2023<a name="eins"></a>
 
Zuerst gab es heute die Noten für unser letztes Projekt. Dazu gab es noch einige Rückmeldungen und uns wurde etwas zum neuen Projekt und den Möglichkeiten erzählt. Wir haben uns aufgrund des Erfolgreichen Projekts des letzten Halbjahres entschlossen weiterhin zusammenzuarbeiten. Die Grundidee des neue Projekts haben wir uns schon im letzten Halbjahr überlegt. Heute haben wir dann die Projektseite und den Blog für unser Projekt erstellt. Wir haben uns noch genauer überlegt wie wir das Projekt umsetzten wollen.


 ### 2. Stunde vom 11.01.2023<a name="zwei"></a> 
 
Heute haben wir uns überlegt, welche Teile wir für unser projekt benötigen und fragen welche von denen schon in der schule vorzufinden sind, und welche wir uns selber beschaffen werden. Anschließend haben wir den Schuhkarton mit Aluminiumfolie ausgekleidet und uns danach schonmal einige videos und Websiten angeguckt, um schnmal einige Informationen zu sammlen wie genau wir unser projekt relisieren können. Außerdem haben wir uns über den Wärmesensor besonders informiert und überlgen uns nun , wie wir den Ntc Therministor kalibirieren können. Dafür haben wir auch schon einen generellen Aufbau, wie man den Ntc Therministor steuert. Diesen wollen wir dann nächste Woche kalibrieren.


 ### 3. Stunde vom 17.01.2023<a name="drei"></a>

Heute haben wir die ersten Materialien zusammen getragen. Nun haben wir eine 25 Watt Glühbirne und müssen uns jetzt überlegen, welchen Transistor wir brauchen um Strom aus der Steckdose steuern zu können. Als nächstes müssen wir uns auch übelergen, wie wir unseren Wärmesensor kalibrieren. Doch dies ist nicht ganz einfach, da der Npc Wärmesensor nicht linear funktioniert. Dadurch muss man dort eine Formel für den die Wärme, abhängig von dem Wiederstand, welches der Wärmesensor ist, aufstellen.

 ### 4. Stunde vom 18.01.2023<a name="vier"></a>
 
Heute haben wir einen ersten Schritt geschafft. Wir haben es geschafft, auch nach Problemen den Wiedertstand des NTCs auszulesen. Damit haben wir die Grundlage für die Temperaturberechnung gelegt. Dies wollen wir dann in den nächsten Stunden machen. Dafür haben wir schonmal einen Ansatz aus dem Arduino-Forum. https://forum.arduino.cc/t/ol-temperatur-messen-welcher-oltemperaturgeber-kfz/152055/12#msg1170722 https://www.mymakerstuff.de/2018/05/18/arduino-tutorial-der-temperatursensor/

 ### 5. Stunde vom 24.01.2023<a name="fünf"></a>

Heute haben wir weiter recherchiert, wie man einen Ntc Wiedersandswert in Temperarur umrechnet. Wir haben eine Quelle mit einem Code gefunden. Dieser funktioniert aber auch nach Kontrolle und der Bearbeitung einiger Fehler nicht. Also müssen wir in der nächsten Stunde weiter an der Rechnung der Temperatur arbeiten.


 ### 6. Stunde vom 25.01.2023<a name="sechs"></a>

Heute haben wir mit einem code, den wir auf der Website(/www.mymakerstuff.de/2018/05/18/arduino-tutorial-der-temperatursensor/) gefunden haben, versucht den Ntc Wiederdtand in eine Temperatur umzuzrechnen. Dabei wird sich auf die Steinhart-hart-Gleichung bezogen. Doch dieser Code hat nicht geklappt, weshlab wir uns anschließend gefrgat haben, woran das liegen könnte. Wir haben gedacht es könnte daran liegen, dass wir anders als bei unserer Quelle im  Internet einen anderen Wiederstand in Reihe geschaltet haben und oder einen anderen Thermistor haben. Dass wir einen anderen Thermistor haben könnte eine Rolle spielen, da jeder Thermistor einen spezifischem B-wert hat. Da wir nicht wussten, was für ein B-Wert unser Thermistor hat, müssen wir durch eine Formel, welche Tempertaurmesswerte in Kombinationen mit den jeweils zugehörigen Wiederstandsmesswerten nutzt, um den Materialspezifischen B-wert bestimmen. Dies werden wir in den nächsten Stunden verfolgen.


 (Heute haben wir nach vielen weiteren Messungen wieder keine passende Lösung ermittelt. Wir haben aber dafür herausgefunden, dass der B-Wert von der D-Funktion abhängig ist. Auch mit der Float-Funktion hat es nicht funktioniert. 
 
 heute wasserkocher, weiter probiert, mehrere websites, herr buhl hat nicht geklappt, B wert ist abhänging von der dfunktion , neuer Thermistor mit board für nächste woche, auch selbser probiert mit float)

 ### 7. Stunde vom 27.01.2023<a name="sieben"></a>

Tatsächlich hat sich herausgestellt, dass wir nicht nur einen anderen Thermistor und Wiederstand verwenden, es ist auch der Code grundsätzlich fehlerhaft, den wir von unserer Quelle entnommen hatten. Heute haben wir daher den überarbeiteten code von herr Buh( sehr freundlich) angteguckt und verstanden. Dabei planen wir in der nächsten Doppelstunde mit einem präzisen Thermometer 3 Punkte für die Steinhart Hart Formel zu bestimmen, um dann genauerer Messwerte vom Ntc zu bekommen. Unser Fehler lag darin, dass wir  unsere Quelle mit dem tutorial nicht hinterfragt hjaben und somit hat das Bestimmen der Temperatur duch den Ntc nicht geklappt. Ein Fehler war, dass der maximale Bitwert nicht 1024 war, sonder 1023 bei 5V und bei der Korrektur dieses fehlers hat anschließend das Messen grundsätzlich funktioniert. Auch hatten wir zum Beispiel eineni falschen Wiederstand in Reihe geschaltet. Der Serienwiederstand in unserem Schaltkreis hatte nur 1k Ohm, doch damit es zu einer besseren Messung kommt, sollten der Nennwiederstand des Ntcs und der Wiederstand des Serienwiederstandes möglichst gleich sein. Denn dann können die Unterschiede in den Wiederständen deutlich feiner unterschieden werden und so kommt es zu genaueren Messwerten. Also habenw ir heute gelernt unsere Quellen zu hinterfrgaen und sobald wir Informationen aufnehmen auch mit anderen zu verghleichen und gegebenfalls selbst nachzudenken. Gerade kommt es bei einer tatsächlichen Tempertatur von 19 bis 20 Gtrad zu einem Messwetr von 27 Grad. Wir hoffen , dass wir durch die neue Kalibrierung genauere Messwerte bekommen können. 


 ### 8. Stunde vom 01.02.2023<a name="acht"></a>
 
Heute haben wir uns darauf konzentriert genaue Parameter zu bestimmen, damit wir einen möglichst genauen B-Wert bestimmen können und so einen präziseren Thermistor haben, da unsere Werte momentan um ungefähr 7 Grad abwecihen. Dafür haben wir von Herr Buhl einen Wasserkocher und Eis zur Verfügung gestellt bekommen. Nun haben wir ein Thermometer und den Thermistor in eine Tasse mit Eiswasser getan, mit dem Ziel, dass dort 0 Grad herrschen(am ende haben wir 7 Grad als Messwert genommen) und dann in eine Tasse it kochendem Wasser also 100 Grad. Um dann einen dritten Parameter zu erhalten haben wir eine Tasse mit ungefähr 30 Grad genommen und wieder den iwderstand mit dem Thermistor bestimmt. NUn hattenw ir 3 genau Parameter bestimmt und mussten diese nur moch in die Formel eingeben(siehe Foto). Als wir diese in die Steinhart-HArt-Gleichung eingesetzt haben, haben einen entsprecheneden B-Wert bekommen, den wir dann in unseren COde für den Arduino iengestezt haben. Nun hat es mit dem Code tatsächlich geklappt präzise die Temperatur mit dem Thermisoor zu messen. 





 ### 9. Stunde vom 03.02.2023<a name="neun"></a>

Thermistor funktioniert, Transistor recherchieren, Thermistor testen, Glühbirne anschliessen ( nächster Schritt) 
Nun hat der der Thermistor endlich funktioniert und wir haben eine passende Themperatur ermittelt, welche auch bei hohen und niedrigen Temperaturen passend ist. Dies haben wir durch Tests mit kochendem Wasser und Eiswürfeln ausprobiert. Die Temperatur, die wir errechnet haben, weicht nur ganz minimal von der eines Thermometers ab. Daraufhin haben wir dann das Wissen zu einem Transistor aufgefrischt. Mit diesem wollen wir in der nächsten Stunde die Glühbirne an den Aufbau anbauen.

### 10. Stunde vom 08.02.2023<a name="zehn"></a>

Heute hat Herr Buhl den Aufbau den Aufbau geprüft, da wir mit Steckdosenstrom arbeiten und es einmal geprüft werden muss. Aktuell dürfen wir noch nicht arbeiten, weil der Steckdosenstrom noch nicht isoliert ist. Dann haben wir an den Transistor eine Kühlung geklebt, damit dieser den Strom von 230V aushält und nicht durchbrennt. Am Freitag wollen wir dann die Kabel zusammenlöten, weil die Kabelschuhe nicht zu unseren Kabeln passen.

### 11. Stunde vom 10.02.2023<a name="elf"></a>

Erstmal haben wir die Kabel verbunden, indem wir gelötet haben. Dann haben wir die Kabel durch Klebeband isoliert. Anschließend haben wir einen Aufbau hergestellt, sodass die Lampe über den Transostor gesteuert wird. Dazu haben wir noch getestet, ob der stromkreis funktioniert, ohne den Transistor anzuschalten. Anschließend haben wir mit dem Transistor einen Fehlstrom hergestellt, wodurch wir den ganzen Computerraum lahmgelegt haben. dadurch hat sich herausgestellt, dass etwas der Aufbau nicht korrekt war. In der nächstenm Stunde werden wir den Aufbau überarbeiten müssen. 

### 12. Stunde vom 15.02.2023<a name="zwölf"></a>

Heute haben wir recherchiert, um mit einem relay die nächste Stunde einen richtigen aufbau erzielen zu können. Dieser wird uns nächste Stunde zu verfügung stehen und dann können wir hoffentlich mit seperaten Stromkreisen den Transistor richtig steuern. Wir haben uns Videos angesehen und mehrere Internetseiten durchgelesen. Dadurch haben wir uns den genauen Aufbau aus mehreren Internetseiten zusammmengeplant. Nächste Woche können wir dies dann aufbauen und haben damit dann den Aufbau unseres Projekts so gut wie fertig

### 13. Stunde vom 22.02.2023<a name="dreizehn"></a>

Heute haben wir den gaplanten Aufbau dann umgesetzt. Daraufhin haben wir dann einen Test durchgeführt.
Heute aufbau, test mit irgentwa; FREITAG cODE SCHREIBEN für relay test mit LED dnach mit glühlampe

### 14. Stunde vom 24.02.2023<a name="vierzehn"></a>  

relay weiter ausprobiert, lange nicht geklappt, Beschriftung vertauscht, relay 4er Module probiert mit voltMeter- auch nicht geklappt. Danach probiert an der Schaltstelle (Input am Relay)  mit einer externen Netztstelle einen Impuls zu senden. Das hat gekllappt, abver erkenntnis man braucht LOW für Schalter nicht HIgh bei relay. Dadurch hat sich alles gfeklärt und wir haben die Gölühbirne angeschlossen und mit einem einasch if code den Schwellenwert für das Schalten bei 25 grad gesetzt. Dies hat geklappt und als nächstes müssen wir den Aufbau in den Schuhkarton bringen und danach mit PID steuern. Als letztes noch Ventilator.- 

### 15. Stunde vom 01.03.2023<a name="fünfzehn"></a>

Heute haben wir den Aufbau komplett fertig im Schuhkarton gehabt. Dies führte dazu, dass wir schon einen ersten Test durchführen konnten. Dieser war erfolgreich. Also können wir uns jetzt mit unserem nächsten Ziel beschäftigen. Dies ist nämlich, dass wir die Glühlampoe durch PID steuern. Außerdem haben wir uns überlegt, was wir in der Doppelstunde im Homeschooling machen können. Wir sind zu dem Entschluss gekommen uns weiter über zukünftige Themen zu informieren und unseren Blog auf vordermann zu bringen, da wir aufgrund von Zeitknappheit diesen nicht immer ganz schreiben konnten.

### 16. Stunde vom 03.03.2023<a name="sechzehn"></a>

In der heutgen Doppelstunde hatten wir Homeschooling. Also haben wir an unserem Blog gearbeitet. Da wir oft mit speziellen Sachen bis zum Ende der Stunde beschäftigt waren, konnten wir uns einige Male nur Stichpunkte machen. Diese haben wir nun zu Texten verfasst. Arvid hat dazu schon mit ersten recherchen für PID begonnen und Philipp hat sich über den Ventilat informiert.

### 17. Stunde vom 08.03.2023<a name="siebzehn"></a>

In der heutigen Stunde war Arvid nicht da. Philipp hat heute den Ventilator eines alten PCs geholt und diesen auseinandergebaut, sodass wir nur noch den Ventilator ohne Kühlung etc. haben. Die hat viele Probleme Bereitet, weil der Ventilator so gebaut ist, dass man ihn nicht auseinander bauen soll. Dann habe ich mich über den Ventilator informiert. Dieser hat mehrere Anschlüsse, welche wir jetzt passend zuordnen können. Nächste Stunde wollen wir dann den Ventilator steuern.

### 18. Stunde vom 10.03.2023<a name="achtzehn"></a>

Diese Stunde war Arvid wieder nicht da. Ich habe den Ventilator in in den Einbau angebunden und einen Code für diesen geschrieben. Zu Beginn habe ich den Ventilator mit Relay gesteuert. Am Ende der Stunde lief der Ventilator dann durch einen Knopf. Hierdurch wollen wir steurn, wann der Ventilator läuft. Durch die Lampe soll die Temperatur erreicht werden. Wenn wir dann eine neue Zieltemperatur haben kühlen wir den Karton manuell durch den Ventilator runter, damit die Lampe dann wieder mit PID die Zieltemperatur erreichen kann.


### 19. Stunde vom 15.03.2023<a name="neunzehn"></a>

Heute haben wir dann den Code des Ventilators mit dem Code der Glühlampe zusammengefügt. Dabei gab es allerdings einen Fehler. Uns wurde nämlich immer eine Temperatur von -273,15 Grad, also den Unterschied von Kelvin zu Celsius. Nach längerem untersuchen des Codes und des Aufbaus haben wir entdeckt, dass sich aufgrund des öfteren Transports der NTC ausgestckt hat und direkt bei einem anderen lag, wo wir es dann eingefügt haben.


### 20. Stunde vom 17.03.2023<a name="zwanzig"></a>

Heute haben wir dann den Ventilator in den Karton eingebaut, sodass dieser die Luft aus dem Karton herauspustet. Danach haben wir uns dann über PID informiert, welches unser Projekt vervollständigen soll. Dabei gibt es allerdings viele Möglichkeiten mit der Library. Wir wollen PID aber in der einfachen Form ohne Library durchführen.

### 21. Stunde vom 24.03.2023<a name="einundzwanzig"></a>

Heute haben wir weiter für PID recherchiert. Für PID ohne Library gab es nur wenige Quellen. Am Ende haben wir allerdings eine passende gefunden, mit der wir dann gearbeitet haben. Diese haben wir dann ähnlich verwendet und in unseren Code geschrieben. Beim Prüfen gab es dann allerdings 9 Fehler, wovon wir 4 noch beheben konnten.

Da haben wir diese Website gefunden: http://brettbeauregard.com/blog/2011/04/improving-the-beginners-pid-introduction/

Und mit diesem code bis jetzt gearbeitet, der noch einige Probleme aufweist:
 <details> 
	
  int sensorPin = A0;
  int bitwertNTC = 0;

 long serienWiderstand = 9920; //des Widerstandes in Serie 
  long nennWiderstand = 10050.46; // des NTCs
  long nennW_H = 10000; //laut Hersteller

  int bWert = 3307.29; // B- Wert vom NTC
  int b_H = 3435; //B-Wert laut Hersteller 

  double widerstandNTC = 0; 
  double kelvinBias = 273.15;// 0°Celsius in Kelvin 
  double Tn = kelvinBias + 25; //Nenntemperatur in Kelvin 
  double T_K_3 = 0;  //Die mit 3 Parametern errechnete IstTemperatur in Kelvin
  double T_C_3 = 0; //Die errechnete IstTemperatur in Celsius

  double T_K_B = 0;  //Die mit 2 Parametern errechnete IstTemperatur in Kelvin
  double T_C_B = 0; //Die errechnete IstTemperatur in Celsius

  double T_K_H = 0;  //Die mit Defaultparametern errechnete IstTemperatur in Kelvin
  double T_C_H = 0; //Die mit Defaultparametern errechnete IstTemperatur in Celsius

  double koA = 0.0008058251861;
  double koB = 0.0002644552360;
  double koC = 0.0000001421890507;


  unsigned long lastTime;
  double input = T_C_H;
  double output = 0;
  double setpoint = 32;


 double errSum, lastErr;

  void compute() 

{

unsigned long now = millis();
double timeChange = (double)(now - lastTime);

double error = setpoint - input; 
errSum += (error * timeChange);
double dErr = (error - lastErr) / timeChange; 

Output = kp * error + ki * errSum + kd * dErr; 

  lastErr = error; 
  lastTime = now; 

}

void setTunings(double kp, double ki, double kd)   

{
kp = 1.5;
ki = 0.05;
kd = 0.1;


}

  const int RELAY_PIN = 8; 

  void setup() {
    pinMode (7, OUTPUT);
    pinMode(RELAY_PIN, OUTPUT);

 	Serial.begin(9600); 

  }

  void loop() {
   digitalWrite (7,HIGH);
    delay (100);
    digitalWrite (7,LOW);
    delay (1000);

  	Serial.println("Sensormessung: ");
 	bitwertNTC = analogRead(sensorPin); // lese Analogwert an A0 aus 
	
     //1023 entspricht maximaler Spannung  	widerstandNTC = serienWiderstand*(((double)bitwertNTC/1023)/(1-((double)bitwertNTC/1023))); // berechne den Widerstandswert vom NTC als Spannungsteiler

  	T_K_3 = 1/(koA+koB*log(widerstandNTC)+koC*log(widerstandNTC)*log(widerstandNTC)*log(widerstandNTC));
  
    T_K_B = 1/((1/Tn)+((double)1/bWert)*log((double)widerstandNTC/nennWiderstand)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin     T_K_H = 1/((1/Tn)+((double)1/b_H)*log((double)widerstandNTC/nennW_H)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin 
	
  	T_C_3 = T_K_3 - kelvinBias; // ermittle die Temperatur in °C
  	T_C_B = T_K_B - kelvinBias; // ermittle die Temperatur in °C
  	T_C_H = T_K_H - kelvinBias; // ermittle die Temperatur in °C

  	Serial.print("Analog: "); // 
  	Serial.println(bitwertNTC); // 
  	Serial.print("NTC- Widerstand: "); //Gebe die ermittelten Werte aus
  	Serial.println(widerstandNTC); // 
  
  	Serial.print("Temp. 3 Param: "); //Gebe die ermittelten Werte aus
  	Serial.print(T_C_3); //
  	Serial.print("   Temp.B: "); //Gebe die ermittelten Werte aus
  	Serial.print(T_C_B); //
  	Serial.print("   Temp.Default: "); //Gebe die ermittelten Werte aus
  	Serial.print(T_C_H); //
    Serial.println("\n");
    delay(1000); // Warte kurz, dann mache alles nochmal
  // if(T_C_H<35)
  // digitalWrite(RELAY_PIN, LOW);
   //if(T_C_H>35)
  // digitalWrite(RELAY_PIN, HIGH);
  }
 </details> 

### 22. Stunde vom 29.03.2023<a name="zweiundzwanzig"></a>

	
entfallen

### 23. Stunde vom 31.03.2023<a name="dreiundzwanzig"></a>
	
Heute haben wir die verbleibenden 5 Fehler gefunden. Also haben wir auch PID fertig. Allerdings wird die Glühbirne nicht heller oder dunkler, sondern bleibt ständig gleich. Als wir dann an die Lampe nur einen Teil des Stroms gesendet haben, haben wir heraugefunden, dass die Glühbirne entweder ganz hell oder gar nicht leuchtet. Also ist PID für die Lampe nicht möglich. Das heißt, dass wir PID auf den Ventilator anwenden müssen und die Glühlampe wie zu beginn mit if steuern müssen. Dann haben wir probiert, ob dies der Ventilator überhaupt mit der halben Geschwindigkeit arbeiten kann. Dies funktioniert. Also müssen wir nun PID auf den Ventilator umstellen. Dieser Test hat uns allerdings wieder viel Zeit gekostet, weil wir dabei herausgefunden haben, das unser Pin 6 defekt ist, mit dem wir die ganze Zeit getestet haben, ob der Ventilator mit einer Teilgeschwindigkeit laufen würde. Ab jetzt arbeiten wir also ohne Pin 6.

### Finalisierung 06.04 und 07.04.2023<a name="vierundzwanzig"></a>	
