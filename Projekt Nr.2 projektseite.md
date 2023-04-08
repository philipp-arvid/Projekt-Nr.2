# Der temperaturgesteuerte Schuhkarton
## Links

 [Stundenprotokolle](https://github.com/philipp-arvid/Projekt-Nr.2/blob/main/README.md)
1. [Einleitung](#Einleitung)
2. [Entwicklung des Projekts](#Entwicklung)
3. [Fazit](#Fazit)

<h1>1. Einleitung</h1> <a name="Einleitung"></a>

<h3>1.1 Das Team</h3>

Aufgrund der sehr erfolgreichen und von Spaß geprägten Zusammenarbeit im ersten Halbjahr, haben wir uns entschieden auch im zweiten Halbjahr das Projekt gemeinsam anzugehen. Dadurch, dass wir am Ende der Zeit unseres letzten Projektes noch etwas Zeit hatten, haben wir uns auch schon ein Projekt überlegt, welches wir dieses Halbjahr umsetzten wollen und welches teilweise auf unser letztes Projekt aufbaut. Ebenfalls haben wir beide zusammen schon einige Erfahrungen mit Arduino gesammelt und können nun gut gemeinsam unser Vorwissen anwenden und in diesem Halbjahr ausweiten.

<h3>1.2 Der Arduino</h3>

Auch beim Projekt "Der temperaturgesteuerte Schuhkarton" handelt es sich wieder um ein Physical-Computing-Projekt. Diesmal wollen wir auf das Projekt im ersten Halbjahr aufbauen. Es ist weiterhin so, dass uns beim Arduino die Kombination aus Software und Hardware besonders interessiert. Der Arduino besteht aus Software und Hardware und ist somit eine open-source Physical Computing-Plattform. Dabei besteht die HArdware des Arduinos aus dem Micro-controller, welcher durch das passende Programm programmiert wird. Somit lassen sich Sketches schreiben, welches man mithilfe eines USB-Anschlusses auf den Arduino übertragen kann. Unser erstes Projekt hat uns beiden sehr gefallen und diesmal möchten wir aufjedenfall komplexere Schaltungen und Codes schreiben, da wir im Vergleich zu lezten Halbjahr etwas mehr Vorwissen haben. Wir verwenden weiter den Arduino und diesmal verwenden wir sowohl die Analogen, als auch die Digitalen Pins des Arduinos, um die unterschiedlichen Funktionen der Bestandteile unseres Projektes auszuführen. 


<h3>1.3 Genutzte Programme</h3>

Arduino-IDE:

Wie im ersten Halbjahr haben wir wieder das Arduinoprogramm genutzt. Mithilfe von Sketches, die wir schreiben, können wir die angeschlossenen Bestandteile steuern, was also der Software unseres Projektes enstpricht und erst die Grundlage für das Funktionieren unseres Projektes darstellt.

GitHub:

Auf GitHub haben wir wieder unseren Blog und die Projektseite verfasst. Das Programm eignet sich als Versionsverwaltung zur Softwareentwicklung sehr gut zum dokumnetieren und vorstellen solch einer Arbeit.

<h1>Entwicklung des Projekts</h1> <a name="Entwicklung"></a>

<h3>2.1 Vorgehen </h3>

Auch bei diesem Projekt haben wir wieder das Vorgehen Schritt für Schritt, von einfach zu komplizierter, die Dinge gelesen,gesteckt, und am Ende in den Sketch geschireben. Dieses Mal haben wir uns auch, im Verglich zum letzten Mal deutlich mehr Gedanken über die Reihenfolge unseres Vorgehens nachgedacht. Das liegt daran, dass die Glühbirne Steckdosenstrom brucht, und wir somit, bevor wir das hätten intergieren können, erstmal den Grundstein, wie den Wärmesensor und Relay legen mussten. 
Auch haben wir dieses Halbjahr weniger mit Youtube Videos gearbeitet, sondern mit Websites. Beim Arbeiten mit den verschidenen Internetseiten haben wir auch gelernt, dass nicht jede Internetseite immer vollständig richtig ist. So haben wir zum Beispiel, da wir davon Ausgegangen sind, dass der Inhalt einer Website komplett richtig ist, die Informationen manchmal nicht hinterfragt und versucht erstmal zu übernehemen. Dabei sind wir oft auf Probleme und Fehlermeldungen gestoßen, sodass wir die Informationen mit anderen Webistes zusammentragen mussten, um ein richitges Ergebnis zu erzielen oder Herr Buhl nach anhaltenden Fehlern, nach Hilfe gefragt haben. Dabei hat sich manchmal herausgestellt, dass die Fehler von sehr simpler Art, in einigen Fällen nur aus einem Tippfehler entstanden sind, welche wir einfach übersehen haben. Des Weitern haben wir gelernt, wie man Fehlerquellen untersucht: Man eliminiert alle möglichen Variablen, die einen Fehler hervorrufen können, und fügt diese Schritt für Schritt wieder zu, um dei Fehlerquelle zu finden. Somit konnten wir auch einige Probleme im Prozess unseres Projektes identifizieren und beheben. Trotz einiger Probleme, haben wir im Laufe der Zeit immer einen Weg gefunden, diese zu lösen, oder zum Umgehen. Auch wenn wir manchmal auch länger als eine Stunde an einem Problem festsaßen, ist dass Gefühl der Erleichterung und der Klarheit, beim lösen des Fehlers immer ein schönes Gefühl. Somit konnten wir auch am Ende- im strengen Zeitplan, ein fertiges Endprodukt erzielen. 


<h3> 2.2 Die Idee</h3>

Die Idee für das Projekt diesen Halbjahres, haben wir schon zum größten Teil im letztem Halbjahr, am ende unseres letzten Projekts entwickeln. Dieses Mal wollen wir mithilfe eines Wärmesensors, die Temperatur in einem Raum steuern. HIerbei soll der der Raum wieder der Schuhkarton sein, welchen wir auch schon bei unserem ersten Projekt verwendet haben. Zum steuern der Temperatur, brauchen wir eine Art Heizung in diesem Raum, welches dann eine klassische Glühbrine sein wird, die je nach der Intensität diser den Raum stärker oder schwächer leuchtet. Dann wollten wir noch einen Ventilator einbauen, der extern die Temperatur im Schuhkarton beeinflusst, sodass die die Glühbirne mehr anpassen muss. Dies war unsere Ursprüngliche Idee- denn im Laufe des Projekts hat sich diese geändert und aufgrund neuer Erkenntnisse weitereintwickelt. Durch das Steuern der Glühlampe mit dem Relay, konnten wir diese nur auf HIGH oder LOW schalten, wodurch wir keine Zwischenwerte und somit kein PID auf die Glühlampe anwenden konnten. Da wir jedoch dieses Halbjahr, unbedingt einmal mit PID arbeiten wollten, haben wir uns dann dafür entschieden den Ventilator mit PID zu steuern. Diese Idee, die sich erst später aus der ursprünglichen Entwickelt hat, haben wir dann in unserem Projekt umgesetzt.


<h3> 2.3 Hadwaretechnische Umsetzung </h3>

 <li> Das ganze Projekt drehte sich wieder um einen Schuhkarton. Dieser ist diesmal mit Aluminium ausgeklebt, damit Wärme schwerer aus dem Raum entweicht. Durch ein kleines Loch haben wir wieder die benötigten Kabel hinzugefügt. Außerdem haben wir diesmal noch ein größeres Loch gemacht. An dieses Loch, haben wir den Ventilator eingebaut, um den Raum, wenn gewollt, auch wieder abkühlen zu können. Der Ventilator wurde aus einem der Computer der Schule entfernt und wird nun von uns genutzt, für die Zwecke unseres Projektes. Auch befinden sich die Glühbirne und der Wärmesensor im Schuhkarton. Die Glühbrine dient hier als Heizung und diese haben wir selbst von zuhause mitgenommen. Diese benötigt Steckdosenstrom und kann den Schuhkarton doch relativ schnell erhitzen. Doch um die Temperatur zu steuern, müssen wir auch die Temperaut messen. Dafür haben wir einen Ntc Thermistor. Ein Ntc verändert seinen Widerstand abhängig von der Umgebungstempratur. In diesem Fall verringert der Ntc seine Temperatur bei steigenden Temperaturen, wodurch man je nach dem Widerstand, die Temperatur ermitteln kann. Also befinden sich die Glühbirne und der Ntc im Schuhkarton und der Ventilaor aussen, an einem Loch, der die Luft rauspustet.  </li>

 <li> Als erstes haben wir einen Stromkreis, in den wir einen NTC eingebaut haben und wodurch wie die Temperatur ermitteln können. In diesem Stromkreis haben wir einen Serienwiderstand mit 10 k Ohm geschaltet, da dies möglichst nah an dem durchschnittlichen Widerstaänden des Ntc ist, doasss es zu genaueren Messwerten kommt. Als Nächstes haben wir dort den Ntc gesteckt, der wie ein Spannungsteiler funktioniert. Am Pin A0, des Arduinos wird nun die Spannung als ein Bitwert gemessen und dann im Sketch in einen Temperaturwert umgerechnet.   </li>
	 

 <li> Dann steuern wir noch den Ventilator. Diesen steuern wir über einen Transistor, da der Ventilator 12 V benötigt und der Arduino nur 5 Volt ausgeben kann. AUch weil wir schon die 5 Volt Ausgänge des Arduino benutzen, benötigen wir also hier eine externe Stromquelle. Also verwenden wir hier ein externes Netzteil aus der Schule, welches bis zu 15 Volt ausgeben kann. Wir geben über einen analogen Pin des Arduinos einen Wert von 0 bis 255 an, der als Spannung ausgegeben wird. Dieser Analogpin ist mit der Basis des Transistors verbunden und steuert somit, wie viel Strom von Kollektor zu Emittor fließt. Der Output für den analogen Pin 5, wird durch PID berechnet. Der analoge Output funktioniert mit PWM. Das bedeutet, dass analoge Outputs mit einem Digitalen Signal geschaffen werden, indem diese durch impulse den Strom unterschiedliche lange pro Zeiteinheit weitergeben. So kommt ein Teilsignal zustande, je nachdem wie lange das HIGH Signal ist, kommt es zur Amplitude des Analogen Signals. So steuern wir den Ventilator mit dem Arduino über einen Transistor. Dadurch wird der Transistor dann gesteuert. </li>

 <li> Als Drittes haben wir dann noch die Glühbirne, welche gesteuert werden muss. Da diese Steckdosenstrom bekommen muss, arbeiten wir hier mit einem Relay. Wir arbeiten hier mit keinem Transistor, weil dieser bei dem starken Strom schnell durchbrennen kann. Hier gibt auch wieder zwei Stromkreise. Der Erste Stromkreis geht vom Arduino zum Relay. Ein Relay ist ein Schalter, der zwei Schaltstellungen besitzt, welche durch Strom betätigt werden können. Also können Relays durch einen Stromkreis kontrolliert werden und einen anderen steuern. In diesem Fall wird der Relay durch einen Stromkreis mit dem Arduino gesteuert und steuert selsbt den Stromkreis der Glühbrine mit der Steckdose. Den Relay haben wir dann auf „normally Open“ (am Produkt falsch beschriftet) angeschlossen. Das heißt, dass Der Stromkreis unterbrochen wird, wenn das Signal HIGH an den Relay weitergeleitet wird, also wenn über den weiteren Anschluss ein elektrisches Signal weitergeleitet wird. Wenn nur der normale Stromkreis läuft, ist der Relay offen, also bei LOW die Glühbirne an.    </li> 

Verwendete Materialen: 

 <li>Schuhkarton, Aluminiumfolie, Arduino UNO, Glühbirne, mehrere verschiedene Kabel, Netzteil (und Steckdose), Transistor, Ventilator, Ntc Thermistor, Steckbretter, Relay, Klebeband und Krokodilklemmen.   </li>



<h3> 2.4 Softwaretechnische Umsetzung </h3>
Bei diesem Projekt ist es die AUfgabe der Software, die Temperatur vom Ntc Thermistor ermitteln, den relay abhänig davon zu steuern und den Ventilator so zu aktivieren, dass er mithilfe von PID die Temperatur im Schuhkarton konstant zu halten. 


 <li> Zu Beginn müssen wir aus dem Ntc Thermistor die Temperatur ermitteln. Dazu muss ein wenig gerechnet werden, da der Thermistor nur seinen Widerstandswert in abhängigkeit zur Temperatur verändert, da dieser bei steigender Temperatur, kleinere Widerstände besitzt. Also müssen wir zunächst mit dem Analogpin A0 die Spannung messen, da der Ntc wie ein Spannungsteiler fungiert. Nun muss der Widerstandswert des Ntcs ermittelt werden, da wir diesen nicht direkt messen. Hierfür wird mithilfe einer Gleichung, die den Serienwiderstand und die Spannung beinhaltet, dann der Widerstandswert des Ntcs selbst, berechnet. Auch enspricht der Bitwert des A0 Eingangs für die Maximale Spannung 1023, weshalb diese Zahl in der Gleichung vorkommt.  </li>
 
 <details>
	<summary>Auschnitt des Codes</summary>
	
```c

	
int sensorPin = A0;
int bitwertNTC = 0;

long serienWiderstand = 9920; //des Widerstandes in Serie

  void loop() {
	 
 Serial.println("Sensormessung: ");
bitwertNTC = analogRead(sensorPin); 
	 
 widerstandNTC = serienWiderstand * (((double)bitwertNTC / 1023) / (1 - ((double)bitwertNTC / 1023))); 
}
```	
</details>
	
 <li> Als Nächstes müssen wir weiterhin die Temperatur aus dem Widerstandwert ermitteln. Dafür nutzen wir 3 unterschiedliche Gleichungen, um diese zu ermitteln. Aber grundsätzlich bedienen wir uns hier der Steinhart-Hart-Gleichung, mit der wir mit den Widerstandswerten des Ntcs und anderen Werten die Temperatur ermitteln können. In der Gleichung, die T_K_3 berechnet, verwenden wir die drei Parameter, die wir durch Messpunkte von den jeweiligen Widerstandswerten und der Temperaturen ermittelt haben und den ermittelten Widerstandswert, in der so eben beschriebenen Gleichung, um die Temperatur zu ermitteln. In der nächsten Gleichung, die T_K_B ermittelt, benutzen wir eine Gleichung, die mithilfe der von uns, durch ein Voltmeter gemessen, Werte für den Serienwiderstand rechnet und dem von uns berechneten spezifischen Materialwert, also B-Wert des Ntcs rechnet. In der dritten GLeichung, nutzen wir die gleiche Formel, wie die in der als letztes beschriebene Rechnung, nur mit anderen Werten. Denn hier rechnen wir mit den Werten für den Serienwiderstand und für den Ntcs vom Hersteller. Diese weisen tatsächloch von denen, von uns gemessenen Werten ab, weshalb wir auch mit diesen einmal die Temperatur berechnen. Nachdem wir mithilfe vom Ntc Widerstand die Temperatur mit unterschiedlichen Gleichungen berchnen, lassen wir uns nun all diese Werte mithilfe des seriellen Monitors anzeigen. Doch jetzt folgt noch ein letzter Schritt, da die Werte aus den eben beschrieben Gleichungen immer in Kelvin angegeben werden, müssen wir noch die Ergbebnisse immer so umrechen, dass wir diese in Grad Celsius erreichen.  </li>
 

 <details>
	<summary>Auschnitt des Codes</summary>
	
```c
long serienWiderstand = 9920; //des Widerstandes in Serie
long nennWiderstand = 10050.46; // des NTCs
long nennW_H = 10000; //laut Hersteller

int bWert = 3307.29; // B- Wert vom NTC
int b_H = 3435; //B-Wert laut Hersteller

double widerstandNTC = 0; 
double kelvinBias = 273.15;// 0°Celsius in Kelvin
double Tn = kelvinBias + 25; //Nenntemperatur in Kelvin
double T_K_3 = 0; //Die mit 3 Parametern errechnete IstTemperatur in Kelvin
double T_C_3 = 0; //Die errechnete IstTemperatur in Celsius

double T_K_B = 0; //Die mit 2 Parametern errechnete IstTemperatur in Kelvin
double T_C_B = 0; //Die errechnete IstTemperatur in Celsius

double T_K_H = 0; //Die mit Defaultparametern errechnete IstTemperatur in Kelvin
double T_C_H = 0; //Die mit Defaultparametern errechnete IstTemperatur in Celsius

double koA = 0.0008058251861;
double koB = 0.0002644552360;
double koC = 0.0000001421890507;

void loop() {

Serial.println("Sensormessung: ");
bitwertNTC = analogRead(sensorPin); // lese Analogwert an A0 aus

   //1023 entspricht maximaler Spannung
 widerstandNTC = serienWiderstand * (((double)bitwertNTC / 1023) / (1 - ((double)bitwertNTC / 1023))); // berechne den Widerstandswert vom NTC als Spannungsteiler

  T_K_3 = 1 / (koA + koB * log(widerstandNTC) + koC * log(widerstandNTC) * log(widerstandNTC) * log(widerstandNTC));

  T_K_B = 1 / ((1 / Tn) + ((double)1 / bWert) * log((double)widerstandNTC / nennWiderstand)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin
  T_K_H = 1 / ((1 / Tn) + ((double)1 / b_H) * log((double)widerstandNTC / nennW_H)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin

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
	 
```	
</details>	 
	 
 <li> Nun haben wir noch eine Glühbirne in unserem Schuhkarton, die wir abhängig von der Temperatur steuern wollen. Dadruch, dass der Relay keine anlogwerte annimmt und nur HIGH oder LOW, sein kann, steuern wir diesen über einen digitalpin Output. Dadurch, dass der Relay keine Analogoutput-Werte verwertet, können wir auch keine Algorithmen, wie PID, werwenden, um diesen zu steuern. Daher haben wir uns eine simple Lösung überlegt, und steuern diesen einfach nur über einen If() Befehl. Somit habe wir einen Schwellentemperaturwert, welcher entweder überschritten, oder unterschritten wird. Je nachdem, wo sich die Temperatur befindet, ist die Glühlampe an oder aus. Dabei ist auch wichitg zu beachten, dass der Relay Stromfluss ermöglicht, wenn der Output an den Relay LOW ist.  </li>
 
 <details>
	<summary>Auschnitt des Codes</summary>
	
```c

void setup() {

pinMode(RELAY_PIN, OUTPUT);
 
}
 void loop() {
	 
  ifpinMode(RELAY_PIN, OUTPUT);(T_C_H > 32)
  digitalWrite(RELAY_PIN, HIGH); 
  if(T_C_H < 32)
  digitalWrite(RELAY_PIN, LOW);
 }
		
		
```	
</details>
	 
<li> Nun haben wir ermittelte Temperaturwerte und eine, davon abhängige Glühlampe, die bis 32 Grad den Schuhkarton erhizt und ab 32 Grad, sich ausschaltet. Nun fehlt nur noch der Ventilator, den wir auch abhängig von der Tenperatur steuern wollen. Da dieser mit den Analogen Pins des Arduinos kompatibel ist, können wir hier PID verwenden, um diesen zu steuern. PID ist ein Algorithmus, der mithilfe von den Abweichungen des momentanen Wertes mit dem Zielwert, ein Output generiert, und diesen auch mit den gesamtfehler vergleicht, und so versucht optimal, den Zielwert zu erreichen. Hierbei haben wir eine Library benutzt, was ein Sketch mit extra Funktionalitäten, in diesem Fall die Gleichugnen des PID Algorithmus, versorgen kann. Jetzt muss man, mit der installierten Library, noch seinen Input definieren, welcher die Temperatur in Grad Celsius ist, sowie den Zielwert(Setpoint). Hierbei haben wir den Input gemapped. Das bedeutet, dass wir die möglichen Werte für die Temperatur, welche minimal 18 bis maximal 35 sind auf die PWM Werte übertragen haben. die PWM Werte entsprechenen die möglich, annehmbaren Werte für den Output, da der Analogoutput einen Wert von 0 bis 255 ausgeben kann. Daher haben wir den Setpoint auch in einem Wert von 0 bis 255, wie den Input übersetzt, sodass dieser mit den Werten des Inputs vergleicht werden kann. Dabei übernimmt der Zielwert 30 Grad in der Skala vom Input den Wert 180. Nun geben wir die angebenen Werte in das Rechensystem der Library ein, und erhalten ein Output. Den Output müssen wir vom maximalen Wert der PWM Werte abziehen, da der Ventilator erst eingreifen soll, wenn der Setpoint überschritten ist. Das bedeutet, dass wenn der Output hoch ist, da die Temperatur unter dem Setpoint liegt, so soll der Ventilator sich nicht bewegen. Doch wenn der Output niedrig ist, da der Setpoint überschritten wurde, so soll der Ventilator sich stark betätigen, um den Schuhkarton abzukühlen. Somit haben wir als letztes alle genannten, relevanten Werte: Input, Output und Setpoint, sowie den Wert für den Ventilator im seriellen Monitor uns anzeigen lassen, dass wir diese in Ruhe überprüfen können.  </li>
	
 <details>
	<summary>Auschnitt des Codes</summary>
	
```c
double Setpoint; 
double Input; 
double Output; 
double ventilator;

double Kp=0.1, Ki=5, Kd=0.05; //Parameter für PID
 
PID myPID(&Input, &Output, &Setpoint, Kp, Ki, Kd, DIRECT); //Variablen der PID Library hinzufügen


  void setup() {
	
Setpoint = 180;// Setpoint der Temperatur von 30 Grad in Werten von 0 bis 255 umgerechnet
  
myPID.SetMode(AUTOMATIC);// PID mit der library aktivieren

myPID.SetTunings(Kp, Ki, Kd);
  
pinMode(5,OUTPUT);
	 
}
	 
   void loop() {	
	 
 Input = map(T_C_H, 18, 35, 0, 255);  //mapped die ermittelte Temperatur auf PWM Werte

  myPID.Compute();// Berechnen

  ventilator = 255 - Output; // Output für den Ventilator, da dieser nicht erwärmen, sondern kühlen soll
  analogWrite(5, ventilator); 
	 
  Serial.print("    Input");
  Serial.print(Input);
  Serial.print("    Setpoint");
  Serial.print(Setpoint);
  Serial.print("    Output");
  Serial.print(Output);
  Serial.print("    Ventilator");
  Serial.print(ventilator);
  Serial.println("\n");
  delay(1000); // Warte kurz, dann mache alles nochmal	 
	
}	 
```	
</details>
	
<details>
	
<summary>fertiger Code</summary>
     
```c
		
#include <PID_v1.h> // Library im Code enthalten

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
double T_K_3 = 0; //Die mit 3 Parametern errechnete IstTemperatur in Kelvin
double T_C_3 = 0; //Die errechnete IstTemperatur in Celsius

double T_K_B = 0; //Die mit 2 Parametern errechnete IstTemperatur in Kelvin
double T_C_B = 0; //Die errechnete IstTemperatur in Celsius

double T_K_H = 0; //Die mit Defaultparametern errechnete IstTemperatur in Kelvin
double T_C_H = 0; //Die mit Defaultparametern errechnete IstTemperatur in Celsius

double koA = 0.0008058251861;
double koB = 0.0002644552360;
double koC = 0.0000001421890507;

const int RELAY_PIN = 8; // Pin des Relays

double Setpoint ; 
double Input; 
double Output ; 
double ventilator ;

double Kp=0.1, Ki=5, Kd=0.05; //Parameter für PID
 
 PID myPID(&Input, &Output, &Setpoint, Kp, Ki, Kd, DIRECT); //Variablen der PID Library hinzufügen


void setup() {

Serial.begin(9600);   

 Setpoint = 180;// Setpoint der Temperatur von 30 Grad in Werten von 0 bis 255 umgerechnet
  
myPID.SetMode(AUTOMATIC);// PID mit der library aktivieren

myPID.SetTunings(Kp, Ki, Kd);
  
pinMode(5,OUTPUT);
pinMode(RELAY_PIN, OUTPUT);
 
}

void loop() {

Serial.println("Sensormessung: ");
bitwertNTC = analogRead(sensorPin); // lese Analogwert an A0 aus

   //1023 entspricht maximaler Spannung
  widerstandNTC = serienWiderstand * (((double)bitwertNTC / 1023) / (1 - ((double)bitwertNTC / 1023))); // berechne den Widerstandswert vom NTC als Spannungsteiler

  T_K_3 = 1 / (koA + koB * log(widerstandNTC) + koC * log(widerstandNTC) * log(widerstandNTC) * log(widerstandNTC));

  T_K_B = 1 / ((1 / Tn) + ((double)1 / bWert) * log((double)widerstandNTC / nennWiderstand)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin
  T_K_H = 1 / ((1 / Tn) + ((double)1 / b_H) * log((double)widerstandNTC / nennW_H)); // Steinhart-Hart-Gleichung ermittle die Temperatur in Kelvin

  T_C_3 = T_K_3 - kelvinBias; // ermittle die Temperatur in °C
  T_C_B = T_K_B - kelvinBias; // ermittle die Temperatur in °C
  T_C_H = T_K_H - kelvinBias; // ermittle die Temperatur in °C

  Input = map(T_C_H, 18, 35, 0, 255);  //mapped die ermittelte Temperatur auf PWM Werte

  myPID.Compute();// Berechnen

  ventilator = 255 - Output; // Output für den Ventilator, da dieser nicht erwärmen, sondern kühlen soll
  analogWrite(5, ventilator); 

 
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
  Serial.print("    Input");
  Serial.print(Input);
  Serial.print("    Setpoint");
  Serial.print(Setpoint);
  Serial.print("    Output");
  Serial.print(Output);
  Serial.print("    Ventilator");
  Serial.print(ventilator);
  Serial.println("\n");
  delay(1000); // Warte kurz, dann mache alles nochmal

  if(T_C_H > 32)
  digitalWrite(RELAY_PIN, HIGH); 
  if(T_C_H < 32)
  digitalWrite(RELAY_PIN, LOW);
}
	 
     
```
     
 </details> 
	
<h3> 2.5 Das Endprodukt </h3>	
	 
   [youtube-link1](https://youtu.be/TtX-G6phrgQ)	  

   [youtube-link2](https://youtu.be/DlXQkOoCB9U)	  
 


<h1>3. Fazit</h1> <a name="Fazit"></a>
