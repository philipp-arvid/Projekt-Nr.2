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

Das Vorgehen hat sich diesmal deutlich vom anderen Mal entschieden. Erstmal mussten wir planen, wie wir beginnen und wann wir was machen, weil wir z.B. nicht sofort mit Steckdosenstrom arbeiten konnten. Dazu haben wir dieses Mal weniger mit Videos gearbeitet, da Videos nur bei sehr ähnlichen Projekten nützlich sind. Diesmal haben wir viel mit Websites gearbeitet, wo Prinzipien und Vorgänge erklärt sind. Diese haben wir dann auf unser Projekt übertragen. Ein weiterer Unterschied war, dass wir dieses Mal deutlich öfter Probleme und Fehler hatten, welche nicht nur tippfehler waren und in 1-2 Minuten behoben werden konnten. Da es öfter Fehler waren, welche auf der Website nicht auftraten, aber bei uns waren, sodass wir die Ausführung nicht starten konnten mussten wir oft noch andere Websites mit hinzunhemen und dann die verschiedenen Websites vergleichen. Auch Herr Buhl hat uns diesmal netterweise öfter geholfen, da auch mit Websites die Fehlersuche schwierig war. Des Weiteren haben wir diesmal nicht die Sachen einzeln getestet, da wir generell schon ein gutes Grundwissen haben. Wir haben die Sachen sofort in den Einbau mit eingebunden, da es sonst sehr kompliziert wäre, die Einzelnen Teile in den Gesamtaufbau einzubauen . Den Code haben wir aber oft erst einzeln geschrieben und dann in den Gesamtcode eingefügt. Insgesamt gab es mehr Probleme. Diese konnten wir aber am Ende immer lösen, was fast noch ein größeres Erfolgserlebnis ist. Trotz der Probleme war es wieder ein erfolgreiches Projekt, welches viel Spaß gemacht hat und mit viel Stress aber pünktlich fertig geworden ist.

<h3> 2.2 Die Idee</h3>

Diesmal wollen wir die Wärme in einem Raum steuern. Der Raum wird wieder durch ein einen Schuhkarton dargestellt. Dieser wird mit Aluminium ausgekleidet. Im Karton drin befindet sich eine Glühlampe. Diese gibt Wärme ab. es soll dann mithilfe der Glühlampe, welche durch PID gesteuert wird, eine gezielte Wärme erreicht werden. Im Karton befindet sich außerdem noch ein Ventilator, welcher die Luft im Raum abkühlt. Dieser Ventilator kann angemacht werden, damit die Glühlampe von einem weiter entfernten Wert die neu eingestellte vorgegebene Temperatur, im Raum, erreicht.

<h3> 2.3 Hadwaretechnische Umsetzung </h3>

Das ganze Projekt ist wieder in einem Schuhkarton. Dieser ist diesmal mit Aluminium ausgeklebt, damit die Wärme nicht aus dem Raum entweicht. Durch ein kleines Loch haben wir wieder die Kabel hinzugefügt. Außerdem haben wir diesmal noch ein größeres Loch gemacht. In dies haben wir den Ventilator eingebaut, um den Raum, wenn gewollt auch wieder abkühlen zu können. Der NTC und die Glühlampe befinden sich natürlich im Raum.

Als erstes haben wir einen Stromkreis, in den wir einen NTC eingebaut haben. Durch den Widerstand, welcher sich aus der Temperatur ergibt, kann man die Temperatur errechnen. Dies läuft über den Pin A0. 

Dann steuern wir noch den Ventilator. Diesen steuern wir über einen Transistor, da der Ventilator 12 V benötigt. Wir geben über einen Kreislauf des des Arduino eine bestimmt Anweisung, wie viel Strom der Ventilator empfangen soll. Dies wird von 0 bis 255 angegeben. Dadurch wird der Transistor sozusagen gesteuert. Dieser bekommt nur einen Teil an Strom. Durch diese Anweisung steuert der Transistor dann Stromkreis des Ventilators. Der Transistor hat drei Anschlüsse. Über 2Anschlüsse läuft der Stromkreis. Über den dritten wird eine Anweisung durch Strom gesendet. Durch diese wird der separate Stromkreis dann gesteuert. Es soll aber oft nur ein Teil des Stroms an den Ventilator weitergegeben werden. Da dies nicht möglich ist, lässt der Transistor immer mit kleinen Zeitabständen Strom und keinen Strom zum Ventilator. Also wenn der Ventilator  127,5 erhalten soll, gibt der Transistor immer 

Als drittes haben wir dann noch die Glühbirne, welche gesteuert werden muss. Da diese Steckdosenstrom bekommen muss, arbeiten wir hier mit einem Relay. Wir arbeiten hier mit keinem Transistor, weil dieser bei dem starken Strom schnell durchbrennen kann. Hier gibt es also auch wieder zwei Stromkreise. Der erste Stromkreis geht vom Arduino zum Relay. Den Relay haben wir dann auf „normally Open“ (am Produkt falsch beschriftet) angeschlossen. Das heißt, dass Der Stromkreis unterbrochen wird, wenn Strom durch den Arduino an den dazu gegeben wird. Wenn nur der normale Stromkreis läuft, ist der Relay offen. Wenn Strom über einen dritten Anschluss dazugegeben wird, ist der Relay geschlossen. Dieser steuert dann also die Glühlampe. Wenn der Relay geschlossen ist, ist die Glühlampe aus, weil der Strom nicht weitergeleitet wird. Wenn der Relay offen ist, ist die Glühlampe an. 

Welche Teile benötigen wir dafür?

Karton Aluminiumfolie Arduino Glühlampe Kabel Netzteil(e) Transistor ventilator Wärmesensoren Steckbrett



<h3> 2.4 Softwaretechnische Umsetzung </h3>


<h3> 2.5 Das Endprodukt </h3>



       <summary>Video 1</summary>

   [youtube-link](https://youtu.be/TtX-G6phrgQ)	  

	

       <summary>Video 1</summary>

   [youtube-link](https://youtu.be/DlXQkOoCB9U)	  
 


<h1>3. Fazit</h1> <a name="Fazit"></a>
