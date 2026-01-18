# SV2Abgabe
upload GIFs for SV

# Task 1

## Part 1

Berechnung: Berechnen Sie zuerst die theoretische Resonanzfrequenz f₀ mit der Formel von Folie 5 und den gegebenen Werten

f₀ = 1 / (2π√(LC))
1/(2π√(0,01H • 1 • 10^-7F))
f₀ -> 5032,92121045Hz

## Part 2

Simulation: Bauen Sie die Schaltung auf. Finden Sie im Simulator die Frequenz, bei der der Strom I maximal ist. (Tipp: Verwenden Sie einen "Slider" für die Frequenz und beobachten Sie die Helligkeit/Geschwindigkeit der fließenden Punkte).

Task1 GIF
![Task1 GIF](https://github.com/Crazybaloonguy/SV2Abgabe/blob/main/Aufzeichnung%202026-01-07%20203217.gif)

## Part 3

Dokumentation: Notieren Sie die Frequenz, die Sie im Simulator gemessen haben.

Eine Frequenz im Bereich von etwa $5 \cdot 10^3$ Hz bis $5,075 \cdot 10^3$ Hz, was nahezu exakt dem berechneten Wert entspricht.

## Part 4

Vergleich: Vergleichen Sie Ihren Rechenwert (aus 1.), Ihren Messwert (aus 3.) und den Wert auf Folie 7. Was stellen Sie fest?

Die theoretische Resonanzfrequenz beträgt 5032,92 Hz. Bei einer Verdopplung des Widerstandes halbiert sich der maximale Strom. Zudem sinkt die Resonanzfrequenz, je größer die Induktivität der Spule gewählt wird.

# Task 2

## Part 1

Finden Sie eine Methode in der Simulationssoftware, um den Frequenzgang des Stroms sichtbar zu machen. (Tipp: Die Spannung am Widerstand R ist proportional zum Strom I).

## Part 2

Stellen Sie den Widerstand R so ein, dass Sie ihn interaktiv verändern können (z.B. mit einem Schieberegler).

## Part 3

Dokumentieren Sie durch ein GIF, wie sich die Form der Resonanzkurve (die "Peak-Form") ändert, wenn Sie R von einem sehr kleinen Wert (z.B. 5 Ω) zu einem großen Wert (z.B. 300 Ω) ändern.

Task2 GIF
![Task2 GIF](https://cdn.discordapp.com/attachments/1390449415600341055/1459139313827708968/Aufzeichnung_Schaltung_2_SV2.gif?ex=696cbce1&is=696b6b61&hm=a88278e15eb20b8ed9d88fc5fe3df5dd288f042b1b53c8e27fbc1a677a55366c&)

## Part 4

Erklären Sie den Zusammenhang, den Sie beobachten:

1. Was passiert mit der Höhe des Peaks?
2. Was passiert mit der Breite des Peaks?
3. Was bedeutet das für die Güte Q und die Bandbreite der Schaltung (vgl. Folie 9)?

A1. Die Höhe des Peaks sinkt, sobald der Widerstand vergrößert wird.
A2. Die Breite des Peaks nimmt bei steigendem Widerstand zu.
A3. Eine größere Bandbreite bedeutet, dass die Güte Q der Schaltung sinkt, da der Dämpfungsanteil durch den Widerstand zunimmt.

# Task 3

## Part 1

Bauen Sie beide Schaltungen im Simulator auf.

## Part 2

Berechnen Sie zuerst die erwartete Resonanzfrequenz f₀ (Thomsonsche Formel).
f₀ = 1 / (2π√(LC))
1/(2π√(1•10^-3H • 10•10^-9F))
f₀ -> 50329,2121045Hz

## Part 3

Simulieren Sie den Frequenzgang der Ausgangsspannung für beide Schaltungen (z.B. in einem Bereich von 15 kHz bis 30 kHz).

## Part 4

Dokumentieren Sie Ihre Ergebnisse durch GIFs, die den Frequenzgang beider Schaltungen zeigen.

Task3 GIFs
![Task3 GIF](https://cdn.discordapp.com/attachments/1287859367361642599/1462173050324914408/Aufzeichnung_2026-01-17_193036.gif?ex=696d3a45&is=696be8c5&hm=e2df3a218139fa3fdb77cbcccd9cd4c2a59e31b102459e25e02da0de31c117e4&)

## Part 5

Beantworten Sie die folgenden Fragen:

1. Bestätigt Ihre Simulation die berechnete Resonanzfrequenz?
2. Beschreiben Sie präzise das gegensätzliche Verhalten der beiden Schaltungen bei dieser Frequenz.
3. Erklären Sie Warum führt Aufbau 1 (Parallelschwingkreis als Ausgang) zu einem Spannungsmaximum, während Aufbau 2 (Reihenschwingkreis parallel zum Ausgang) zu einem Spannungsminimum führt?
(Tipp: Denken Sie an die Impedanz. Wie verhält sich ein Parallelschwingkreis bei f₀? Und wie ein Reihenschwingkreis?)

A1. Ja, die Simulationsergebnisse bestätigen die rechnerisch ermittelte Resonanzfrequenz.
A2. Der Bandpass liefert bei Resonanz ein Spannungsmaximum am Ausgang, während die Bandsperre dort ein Spannungsminimum aufweist. Somit lässt der Bandpass vorrangig die Resonanzfrequenz passieren, während die Bandsperre diese gezielt unterdrückt.
A3. Parallelschwingkreis: Bei Resonanz wird die Impedanz sehr hoch (Sperrverhalten), wodurch die Spannung fast vollständig am Ausgang abfällt.
Reihenschwingkreis: Bei Resonanz wird die Impedanz minimal (Durchlassverhalten), wodurch das Signal gegen Masse kurzgeschlossen wird und die Ausgangsspannung einbricht.

# Task 4

## Part 1

Bauen Sie das R-2R-Netzwerk im Simulator auf.

## Part 2

Stellen Sie nacheinander alle 8 Binärkombinationen (von 000 bis 111) mit den drei Schaltern ein.

## Part 3

Messen Sie für jede Kombination die resultierende analoge Ausgangsspannung Uaus (Tipp: der "DC Level" im Scope) und füllen Sie die folgende Tabelle aus.

| Bit 2 (MSB) | Bit 1 | Bit 0 (LSB) | Dezimalwert | Uaus (V) |
|-------------|-------|-------------|-------------|----------|
| 0           | 0     | 0           | 0           | 0.00 V   |
| 0           | 0     | 1           | 1           | 1.25 V   |
| 0           | 1     | 0           | 2           | 2.50 V   |
| 0           | 1     | 1           | 3           | 3.75 V   |
| 1           | 0     | 0           | 4           | 5.00 V   |
| 1           | 0     | 1           | 5           | 6.25 V   |
| 1           | 1     | 0           | 6           | 7.50 V   |
| 1           | 1     | 1           | 7           | 8.75 V   |

## Part 4

Dokumentieren Sie durch ein GIF, wie sich die Ausgangsspannung ändert, wenn Sie die Binärkombinationen durchschalten.

Task4 GIF
![Task4 GIF](https://cdn.discordapp.com/attachments/1390449415600341055/1459143543821176944/Aufzeichnung_Schaltung_4_SV2.gif?ex=696cc0d2&is=696b6f52&hm=e3485707e7c75aaab67a5d8d56d1109c993886cc644c042344db9c8f10845203&)

## Auswertung

1. Analysieren Sie Ihre Messwerte. Was stellen Sie fest?
2. Berechnen Sie die Spannungsdifferenz (die "Schrittgröße") zwischen den einzelnen Dezimalwerten (z.B. die Differenz zwischen Wert 1 und Wert 2). Ist diese Schrittgröße konstant?
3. Erklären Sie, warum die Schaltung das tut, was auf Folie 30 (Quantisierung/Treppenstufen) gezeigt wird.

A1. Die Analyse zeigt, dass jedes Bit eine gewichtete Spannung beisteuert: Bit 0 liefert 1,25 V, Bit 1 liefert 2,5 V und Bit 2 liefert 5 V. Durch die Kombination erhöht sich die Gesamtausgangsspannung beim Hochzählen linear.
A2. Die Schrittweite zwischen den Dezimalwerten ist mit 1,25 V absolut konstant, was einen linearen Spannungsverlauf ergibt.
A3. Die Schaltung fungiert als Digital-Analog-Wandler. Da jeder Schalter ein binäres Gewicht repräsentiert und die Widerstände die Spannung entsprechend stufenweise summieren, entsteht am Ausgang eine charakteristische Treppenform.

# Task 5

## Part 1

Berechnung: Berechnen Sie die theoretische Resonanzfrequenz f₀ für den LC-Bandpass (L = 1 mH, C = 10 nF). Notieren Sie Ihren Rechenweg und das Ergebnis.

f₀ = 1 / (2π√(LC))
1/(2π√(10^-3H • 10•10^-9F))
f₀ -> 50329,212Hz

## Part 2

Aufbau: Bauen Sie den Bandpass-Filter vom Typ auf Folie 12 (oberes Bild) im Simulator nach. Verwenden Sie Ri = 2,2 kΩ und die gegebenen L/C-Werte

(Siehe GIF)

## Part 3

Simulation:

1. Speisen Sie die Schaltung mit einer Rechteckspannung (Square Wave).
2. Stellen Sie die Grundfrequenz f₁ der Rechteckwelle genau auf die in Schritt 1 berechnete Resonanzfrequenz f₀ ein.

(Siehe GIF)

## Part 4

Messung & Dokumentation:

1. Öffnen Sie das Oszilloskop ("Scope") und zeigen Sie das Eingangssignal (an der Quelle) und das Ausgangssignal (über dem L/C-Parallelkreis) gleichzeitig an.
2. Dokumentieren Sie durch ein GIF, das beide Wellenformen zeigt.

Task5 GIF
![Task5 GIF](https://cdn.discordapp.com/attachments/1390449415600341055/1462150875324879221/Aufzeichnung_Schaltung_5.gif?ex=696d259e&is=696bd41e&hm=a48fe7ed51f259ff815fe9f9f35f90c3ee4ec5e109d7c568dc98f75d86ff5e7f&)

## Part 5

Erklärung:

1. Beschreiben Sie den Unterschied zwischen der Eingangs- und der Ausgangswellenform.
2. Erklären Sie mit Verweis auf die Fourier-Analyse (Folie 25), warum das Ausgangssignal diese Form hat. Welche Frequenzkomponenten der Rechteckwelle lässt der Filter passieren und welche blockiert er?

A1. Während das Eingangssignal eine scharfe Rechteckform mit vielen Oberschwingungen aufweist, ist das Ausgangssignal geglättet und besitzt eine nahezu sinusförmige Gestalt.
A2. Laut Fourier-Analyse besteht ein Rechtecksignal aus der Grundfrequenz und ungeradzahligen Oberwellen. Da der Bandpass nur die Grundschwingung passieren lässt und die höheren Frequenzen dämpft, bleibt am Ausgang fast ausschließlich der sinusförmige Grundton übrig.

# Task 6

## Part 1

1. Stellen Sie die Quelle auf "Sine" (Sinus), 5V Amplitude.
2. Führen Sie eine AC-Analyse ("Frequency"-Plot) am Ausgang (V) durch.
3. Finden Sie die Frequenz, bei der die Schaltung ihre stärkste Resonanz (größte Verstärkung) zeigt.

A1.
Task6 GIF AC
![Task6 GIF](https://cdn.discordapp.com/attachments/1462219784325435434/1462220305199009835/Aufzeichnung_Schaltung_6_Part_1_SV2.gif?ex=696d6647&is=696c14c7&hm=af2dffc065f0004e0c1666da80383110504d594d9412c92b8fd50ea408c0f6b6&)
A3. Die maximale Resonanzamplitude der Schaltung wurde bei einer Frequenz von 3,54 MHz ermittelt.

## Part 2

1. Ändern Sie die Quelle zu einer "Square Wave" (Rechteck), 5V Amplitude.
2. Stellen Sie die Grundfrequenz der Rechteckwelle auf 1,18 MHz ein. (Dies ist 1/3 der Resonanzfrequenz aus Schritt 1).
3. Betrachten Sie den Eingang und den Ausgang (V) im Zeitbereich (Scope).
4. Betrachten Sie den Eingang und den Ausgang (V) im Frequenzbereich (FFT / "Frequency").

Task6 GIF Part 2 1,18MHz
![Task6 GIF](https://cdn.discordapp.com/attachments/1462219784325435434/1462220305950048256/Aufzeichnung_Schaltung_6_Part_2_SV2.gif?ex=696d6647&is=696c14c7&hm=2a24b842e3a7360e703c5df29095c68993ac1340cb1a74a99afcb851169a8e8c&)

Task6 GIF Part 2 (Kombiniert)
![Task6 GIF](https://cdn.discordapp.com/attachments/1462219784325435434/1462220306738319511/Aufzeichnung_Schaltung_6_Part_4_SV2.gif?ex=696d6647&is=696c14c7&hm=ac9768a96d7fd9c3ad8b7f58f50287a463981ab76cb16d63bac32f817a5a2f77&)

## Part 3 Variation (Optional)

1. Ändern Sie die Grundfrequenz der Rechteckwelle auf 712 kHz. (Dies ist 1/5 der Resonanzfrequenz).
2. Beobachten Sie erneut das Spektrum am Ausgang.

 Task6 GIF 712kHz
 ![Task6 GIF](https://cdn.discordapp.com/attachments/1462219784325435434/1462220143940730950/Aufzeichnung_Schaltung_6_Part_3_SV2.gif?ex=696d6621&is=696c14a1&hm=75c448da116706d550e806bb309aca8a1e60f54cb24fa3528073efffe9be7a5e)

## Part 4 Auswertung

Beantworten Sie die folgenden Fragen basierend auf Ihren Beobachtungen aus Schritt 2:

1. Zeitbereich: Vergleichen Sie das Eingangs- und Ausgangssignal. Welche Form hat das Ausgangssignal? Welche Frequenz hat es (grob gemessen)?
2. Frequenzbereich (Eingang): Beschreiben Sie das Spektrum der Rechteckwelle, das Sie sehen. Welche Harmonischen sind vorhanden (1., 3., 5. ...)?
3. Frequenzbereich (Ausgang): Beschreiben Sie das Spektrum am Ausgang. Was ist mit der Grundschwingung (1,18 MHz) passiert? Was ist mit der 3. Harmonischen (3,56 MHz) passiert?
4. Erklärung: Fassen Sie zusammen, was der Filter mit dem Rechtecksignal gemacht hat und warum das Ausgangssignal so aussieht, wie es aussieht.

A1. Das Eingangssignal ist rechteckig, während das Ausgangssignal eine sinusförmige Kurvenform annimmt. Die gemessene Frequenz des Ausgangssignals beträgt etwa 3,54 MHz (entsprechend der 3. Harmonischen).
A2. Das Spektrum der Rechteckwelle setzt sich aus der Grundfrequenz und den ungeradzahligen Harmonischen zusammen:
- 1. Harmonische (Grundwelle): 1,18 MHz
- 3. Harmonische: 3,54 MHz
- 5. Harmonische: 5,90 MHz
Mit steigender Frequenz nimmt die Amplitude der Anteile kontinuierlich ab.
A3. Die Grundschwingung bei 1,18 MHz wird stark gedämpft, da sie außerhalb des Resonanzbereichs liegt. Die 3. Harmonische bei 3,54 MHz liegt jedoch genau auf der Resonanzfrequenz, wird dadurch selektiv verstärkt und dominiert somit das Ausgangsspektrum.
A4. Der Filter wirkt als Bandpass, der gezielt die 3. Harmonische aus dem Frequenzgemisch der Rechteckwelle herausfiltert. Da alle anderen Frequenzanteile unterdrückt werden, resultiert am Ausgang ein reines sinusförmiges Signal mit der dreifachen Grundfrequenz.
