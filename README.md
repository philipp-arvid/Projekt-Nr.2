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

Heute haben wir uns darauf konzentriert genaue Parameter zu bestimmen, damit wir einen möglichst genauen B-Wert bestimmen können und so einen präziseren Thermistor haben, da unsere Werte momentan um ungefähr 7 Grad abwecihen. Dafür haben wir von Herr Buhl einen Wasserkocher und Eis zur Verfügung gestellt bekommen. Nun haben wir ein Thermometer und den Thermistor in eine Tasse mit Eiswasser getan, mit dem Ziel, dass dort 0 Grad herrschen(am ende haben wir 7 Grad als Messwert genommen) und dann in eine Tasse it kochendem Wasser also 100 Grad. Um dann einen dritten Parameter zu erhalten haben wir eine Tasse mit ungefähr 30 Grad genommen und wieder den iwderstand mit dem Thermistor bestimmt. NUn hattenw ir 3 genau Parameter bestimmt und mussten diese nur moch in die Formel eingeben(siehe Foto). Als wir diese in die Steinhart-HArt-Gleichung eingesetzt haben, haben einen entsprecheneden B-Wert bekommen, den wir dann in unseren COde für den Arduino iengestezt haben. Nun hat es mit dem Code tatsächlich geklappt präzise die Temperatur mit dem Thermisoor zu messen. 



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

Heute aufbau im Schuhkarton, erster Test mit ferttigem Aufbau, Test erflogreich und nun nächstes Ziel: PID programmieren und damit di Glhülmape steuern, PID Recherche
03.03.2023 

doppelstunde ist leider entfallen und daher haben wir am Blog vorherige Stunden umgeschrieben und Ergänzt, da wir dies in den Stunden manchmal im instenisven Arbeiten a, Projekt vernachlässigt haben. 

08.03 

In der heutigen Stunde war Arvid nicht da. Philipp hat heute den Ventilator eines alten PCs geholt und diesen auseinandergebaut, sodass wir nur noch den Ventilator ohne Kühlung etc. haben. Die hat viele Probleme Bereitet, weil der Ventilator so gebaut ist, dass man ihn nicht auseinander bauen soll. Dann habe ich mich über den Ventilator informiert. Dieser hat mehrere Anschlüsse, welche wir jetzt passend zuordnen können. Nächste Stunde wollen wir dann den Ventilator steuern.

10.03.2023

Diese Stunde war Arvid wieder nicht da. Ich habe den Ventilator in in den Einbau angebunden und einen Code für diesen geschrieben. Zu Beginn habe ich den Ventilator mit Relay gesteuert. Am Ende der Stunde lief der Ventilator dann durch einen Knopf. Hierdurch wollen wir steurn, wann der Ventilator läuft. Durch die Lampe soll die Temperatur erreicht werden. Wenn wir dann eine neue Zieltemperatur haben kühlen wir den Karton manuell durch den Ventilator runter, damit die Lampe dann wieder mit PID die Zieltemperatur erreichen kann.

15.3

Heute 
Alles zusammengefügt, anschliessen an gesamnten Code, Temperatur falsch- warum? 

17.4

Loch imk Karton für Ventilator und PID Recherche, Lösung xes Problems vom 15.3 

24.03.23

Heute haben wir weiter für PId recherchiert. Es hiess am anfang man müsste eine library verwenden, doch da dies für unser Projekt noch nicht nötig ist, haben wir nach PID gesucht, die ohne Library funktioniert. Da haben wir diese Website gefunden: http://brettbeauregard.com/blog/2011/04/improving-the-beginners-pid-introduction/



Und mti diesem code bis jetzt gearbeitet, der immernoch einige Probleme aufweist: 

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


29.3.2023
entfallen

31.03.2023
heute haben wir weiter mit pid versucht, gugvkt ob relay analog kann, getestet und ergebmnis, es klappt nicht, also: heute machen wir pid mit Ventilator und steuern Glühbirne nur mit if. 


