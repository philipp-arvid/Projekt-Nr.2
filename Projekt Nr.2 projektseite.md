
Temperatur haltender Schuhkarton

Das Team

Aufgrund der sehr erfolgreichen und von Spaß geprägten Zusammenarbeit haben wir uns entschieden auch im zweiten Halbjahr das Projekt geminsam anzugehen. Dazu haben wir uns am Ende des ersten Halbjahr ein Projekt überlegt, welches auf unser jetziges aufbaut. Deshalb ist dies die weitere Zusammenarbeit das einzige sinnvolle. Abgesehen von den Voraussetzungen haben wir uns auch so schon überlegt weiterhin zusammenzuarbeiten

Der Arduino

Auch beim Projekt "Temperatur haltender Schuhkarton" handelt es sich wieder um ein Physical-Computing-Projekt. Diesmal wollen wir auf das Projekt im ersten Halbjahr aufbauen. Es ist weiterhin so, dass uns auch die Hardware sehr interessiert. Des Weiteren haben finden wir es sehr spannend einen tieferen Einblick in einen Bereich zu bekommen. Das erste Projekt hat uns sehr gut gefallen. Also wollen wir jetzt erst das NTC calibrieren und danach mit PID arbeiten. Dies sind schwierigere Bestandteile des Physical-Computings! welche uns aber sher interessieren und bei welchen wir denken, dass sie nach dem ersten Halbjahr noch eine Herausforderung sind, wir diese aber noch gut bewältigen können. Außerdem haben wir jetzt einen komplexeren Aufbau, da wir wieder etwas messen, allerdings diesmal die Temperatur, welche durch das calibrieren etwas schwieriger ist. Dazu haben wir diesmal noch zwei seperate Kreisläufe, welche wir jeweils über einen Kreislauf mithilfe von einem Relay oder einem Transistor steuern.

Genutzte Programme

Arduino:
Wie im ersten Halbjahr haben wir wieder das Arduinoprogramm genutzt. Dies ist wieder die Grundlage unseres Projekts. Mithilfe von Sketches, die wir schreiben, können wir die Angeschlossenen Bestandteile steuern. Durch das Programm errechnen wir die Temperatur und steuern die Lampe und den Ventilator mithilfe anderer Bauteile, welche die Anweisungen auf getrennte Stromkreise übertragen

GitHub:
Auf GitHub haben wir wieder unseren Blog und die Projektseite verfasst. Also haben wir unsere gesamte Arbeit gut dokumentiert.

Die Idee

Diesmal wollen wir die Wärme in einem Raum steuern. Der Raum wird wieder durch ein einen Schuhkarton dargestellt. Dieser wird mit Aluminium ausgekleidet. Im Karton drin befindet sich eine Glühlampe. Diese gibt Wärme ab. es soll dann mithilfe der Glühlampe, welche durch PID gesteuert wird, eine gezielte Wärme erreicht werden. Im Karton befindet sich außerdem noch ein Ventilator, welcher die Luft im Raum abkühlt. Dieser Ventilator kann angemacht werden, damit die Glühlampe von einem weiter entfernten Wert die neu eingestellte vorgegebene Temperatur, im Raum, erreicht.

Hardwaretechnische Umsetzung

Das ganze Projekt ist wieder in einem Schuhkarton. Dieser ist diesmal mit Aluminium ausgeklebt, damit die Wärme nicht aus dem Raum entweicht. Durch ein kleines Loch haben wir wieder die Kabel hinzugefügt. Außerdem haben wir diesmal noch ein größeres Loch gemacht. In dies haben wir den Ventilator eingebaut, um den Raum, wenn gewollt auch wieder abkühlen zu können. Der NTC und die Glühlampe befinden sich natürlich im Raum.

Als erstes haben wir einen Stromkreis, in den wir einen NTC eingebaut haben. Durch den Widerstand, welcher sich aus der Temperatur ergibt, kann man die Temperatur errechnen. Dies läuft über den Pin A0. 

Dann steuern wir noch den Ventilator. Diesen steuern wir über einen Transistor, da der Ventilator 12 V benötigt. Wir geben über einen Kreislauf des des Arduino eine bestimmt Anweisung, wie viel Strom der Ventilator empfangen soll. Dies wird von 0 bis 255 angegeben. Dadurch wird der Transistor sozusagen gesteuert. Dieser bekommt nur einen Teil an Strom. Durch diese Anweisung steuert der Transistor dann Stromkreis des Ventilators. Der Transistor hat drei Anschlüsse. Über 2Anschlüsse läuft der Stromkreis. Über den dritten wird eine Anweisung durch Strom gesendet. Durch diese wird der separate Stromkreis dann gesteuert. Es soll aber oft nur ein Teil des Stroms an den Ventilator weitergegeben werden. Da dies nicht möglich ist, lässt der Transistor immer mit kleinen Zeitabständen Strom und keinen Strom zum Ventilator. Also wenn der Ventilator  127,5 erhalten soll, gibt der Transistor immer 

Als drittes haben wir dann noch die Glühbirne, welche gesteuert werden muss. Da diese Steckdosenstrom bekommen muss, arbeiten wir hier mit einem Relay. Wir arbeiten hier mit keinem Transistor, weil dieser bei dem starken Strom schnell durchbrennen kann. Hier gibt es also auch wieder zwei Stromkreise. Der erste Stromkreis geht vom Arduino zum Relay. Den Relay haben wir dann auf „normally Open“ (am Produkt falsch beschriftet) angeschlossen. Das heißt, dass Der Stromkreis unterbrochen wird, wenn Strom durch den Arduino an den dazu gegeben wird. Wenn nur der normale Stromkreis läuft, ist der Relay offen. Wenn Strom über einen dritten Anschluss dazugegeben wird, ist der Relay geschlossen. Dieser steuert dann also die Glühlampe. Wenn der Relay geschlossen ist, ist die Glühlampe aus, weil der Strom nicht weitergeleitet wird. Wenn der Relay offen ist, ist die Glühlampe an. 

Welche Teile benötigen wir dafür?

Karton Aluminiumfolie Arduino Glühlampe Kabel Netzteil(e) Transistor ventilator Wärmesensoren Steckbrett
