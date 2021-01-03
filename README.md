# Fragenkatalog SSS

## Python

Sie haben in Python eine 5 x 5 - Matrix a angelegt. Wie greifen Sie auf das zweite Element der dritten Zeile zu?
> 		a[3][2]

Wie legt man in Python eine 2 x 2 Matrix an, die in der ersten Zeile nur Einsen und in der zweiten Zeile nur Zweien hat
> 		np.array([[1, 1], [2, 2]])

## Messungen

### Messinstrumente

Welche elektrische Größe misst ein Drehspul-Messwerk?
>     Stromstärke (I)

Wie funktioniert ein Drehspulinstrument?
> 		Ein Strom fließt durch eine Spule des Drehspulinstrumentes und erzeugt ein elektromagnetisches Feld. Die Spule ist zwischen dem S- und N-Pol so aufgehangen, dass sie sich drehen kann. An der Spule ist eine Nadel aufgehangen, die auf eine Skala zeigt. Damit der Zeiger nicht direkt auf den Anschlag geht, sorgt eine Spiralfeder für eine Gegenkraft. Je stärker der Strom, der durch die Spule fließt, desto eher richtet sich die Nadel zum N-Pol des Magneten aus.

Ein Messintrument hat einen Anzeigefehler von 1% und einen Skalenendwert von 5 A. Im Moment zeigt das Instrument einen Strom von 2 A an. In welchem Bereich liegt der wahre Wert des Stroms?
> 		5*0.01 = 0.05
> 		2 +- 0.05 A

Warum kann ein Drehspulinstrument nicht beliebig schnell veränderliche Ströme oder Spannungen anzeigen?
> 		Ausgleichsphase

Was ist der Parallaxenfehler?
> 		Die Nadel beim Drehspulmessinstrument zeigt je nach Blickwinkel auf eine andere Zahl.


Auf der Anzeige Ihres analogen Messinstrumentes steht "KL 1.5". Was bedeutet das?
> 		Das bedeutet, dass der Anzeigefehler des Instrumentes bei 1.5% liegt

Zu was benützt man ein Oszilloskop?
> 		Man benutzt es, um Spannungsverläufe periodischer und einmaliger Signale über der Zeit visuell darzustellen.

Wie funktioniert ein analoges Oszilloskop?
> 		Ein Glühdraht am hinteren Teil des Oszilloskops erhitzt eine Kathode, von der sich Elektronen lösen, negativ laden und Richtung Anode wandern. Durch einen negativ geladenen Wehneltzylinder werden die Elektronen durch eine Öffnung gedrückt. Nach einem optischen Element, das den Strahl bündelt, werden die Elektronen über 4 Platten, jeweils 2 X- und Y-Platten, abgelenkt beziehungsweise angezogen. Die Y-Ablenkung beziehungsweise Anziehung wird durch das verstärkte Signal bestimmt. Dabei wird eine Spannung an die Platte angelegt, die je nach Intensität des Signals variiert. Die X-Platte sorgt dafür, dass der Strahl von der linken zur rechten Seite des Schirms gelenkt wird. Das wird durch eine Sägezahnspannung sichergestellt.

Was ist der Unterschied zwischen einem Sensor und einem Messgerät?
> 			Ein Sensor ist Teil eines Messgerätes beziehungsweise einer Messkette des Messgerätes. Er spricht auf bestimmte physikalische / chemische Größen an.

Was für ein Sensortyp ist der im Praktikum eingesetzte Abstandssensor?
> 		Analog

Wie funktioniert die Triggerung beim Oszilloskop?
> 		Bei jedem Durchlauf wird bis zu einer bestimmten erreichten Spannung die Ablenkung angehalten, damit sichergestellt wird, dass die Perioden des Signals übereinander gezeichnet werden können

Warum muss man jede Messung mit dem größten Messbereich beginnen?
> 		Da bei zu hoher Last Messinstrumente im kleinen Messbereich kaputt gehen können

Welches Messprinzip liegt dem im Praktikum eingesetzten Abstandssensor zugrunde?
> 	  Leitfähigkeit

### Messgrößen

Eine indirekte Messgröße A berechnet sich als Differenz zweier direkt gemessener Eingangsgrößen B und C mit absolutem Messfehler ΔB bzw. ΔC, d.h. A = B - C. Wie groß schätzen Sie den absoluten Messfehler ΔA?
> 		Er ist die Summe der Messfehler von B und C also ΔA=ΔB+ΔC

Sie haben eine indirekt gemessene Größe A, die von mehreren Eingangsgrößen B, C, D, ...  abhängt, die alle den gleichen Messfehler haben. Welche der Eingangsgrößen hat den größten  Einfluss auf den Messfehler von A?
> 		Die mit der größten Gewichtung

### Messfehler

Sie haben 20 Einzelmessungen mit einer Standardabweichung des Mittelwertes von s. Wie groß ist das Vertrauensintervall, in das der wahre Wert der Messgröße mit einer Wahrscheinlichkeit von 95,5 % fällt?
> 		2 Mal die Empirische Standardabweichung x Arithmetisches Mittel

Wie schätzt man den wahren Wert einer Messgröße, wenn mehrere fehlerbehaftete Messungen vorliegen?
> 		Mittelwert


## Lineare Regression

Was leistet die lineare Regression?
> 		Bestimmung der Übertragunsfunktion

Kann man die lineare Regression auch bei Kennlinien anwenden, die einem Gesetz der Form
y = x ^ a folgen?
> 		Nein, da die lineare Regression von einer linearen Übertragungsfunktion ausgeht

## Signale

Was ist ein gerades Signal?
> 		Ein gerade Signal ist ein Signal mit Symmetrie zur Y-Achse

Welches der unten aufgeführten Signale enthält keine unendlich hohen Frequenzen?
> 		

Was ist ein fastperiodisches Signal?
> 		Signal das in einem Beriech peridoisch ist


## Fourrier, Spektrum, Phase, ...

Welche Signale lassen sich als Fourierreihe darstellen?
> 		Alle physikalish erzeugbare Signale

### Fouriertransformation

Wie funktioniert die Kurzzeit-Fouriertransformation?
> 		1. überlappende Fenster erstellen
> 		2. Fensterfunktion anwenden
> 		3. Fenster fourier analysieren 11.10

Was muss man bei der Wahl des Fensters bei der Kurzzeit-Fouriertransformation 
beachten?
> 		fenster groß -> hohe frequenzauflösung, niedrige Zeitauflösung (sonogramm schmal, aber überlappend)
> 		fenster klein -> hohe zeitauflösung, niedrige Frequenzauflösung (sonogramm breit, aber abgegrenzt) 11.10

Die Fouriertransformierte von f_1(t) sei F_1(ω), die Fouriertransformierte von f_2(t)
sei F_2(ω). Wie sieht die Fouriertransformierte von f(t) = 3 f_1(t) - 0.7 f_2(t) aus, und
welche Eigenschaft macht man sich dabei zunutze?
> 		aus der Linearitätseigenschaft folgt F(t) = 3 * F_1(ω) - 0.7 * F_2(ω)

Was ist das Gibbs-Phänomen?
> 		über/unterschwinger der Fouriertransformierten bei Sprüngen Im Ausgangssignal

### Symmetrien

Welche Symmetrien hat die zweiseitige Fourierreihe?
> 		Y-Achsensymmetrie

### komplexe Fourierreihe, komplexe Zahlen

Was ist der Unterschied zwischen dem Skalarprodukt in einem zweidimensionalen Vektorraum und der Multiplikation zweier komplexer Zahlen?
> 		Beim Skalarprodukt von zweidimensionalen Vektoren kommt ein Zahl hervor. Bei der Multiplikation zweier komplexer Zahlen kommt wieder eine komplexe Zahl raus. 

Was ist der Unterschied zwischen der Menge der zweidimensionalen Vektoren und den komplexen Zahlen?
> 		Es gibt keinen Unterschied.

Aus welchen Grundsignalen besteht die komplexe Fourierreihe?
> 		Realteil beziehungsweise Cos-Anteil und Imaginärteil beziehungsweise Sin-Anteil

Was haben komplexe Zahlen mit Sinusschwingungen zu tun?
> 		Mithilfe der komplexen Fouriertransformation lassen sich Sinusschwingungen in der kartesischen Darstellung der komplexen Zahlen darstellen


### harmonische Fourierreihe

Aus welchen Summentermen besteht die harmonische Form der Fourierreihe?
> 		A * sin(wt)+B * cos(wt)

Welchen Vorteil hat die trigonometrische Form der Fourierreihe gegenüber der harmonischen Form?
> 		Das Wegfallen der Phase und die unbekannten Fourierkoeffizienten können berechnet werden

Wie sehen die Fourierkoeffizienten der zweiseitigen trigonometrischen Fourierreihe für
x(t) \= a cos(2 omega t) aus?
> 		

Wie viele Terme hat die zweiseitige trigonometrische Fourierreihe von 1 + sin t + 3 cos 2t?
> 		3

### Frequenz

Wie berechnet sich die Frequenz einer Sinusschwingung, das aus der Summe einer Sinus- und einer Cosinusfunktion gleicher Frequenz entsteht?
> 		Frequenz ändert sich nicht?


### Spektrum, Frequenzspektrum

Wie unterscheidet sich das Spektrum periodischer Rechteckimpulse von einer Gauß-Impulsfolge und warum?
> 		Rechteckimpulse besitzen unendlich hohe Frequenzen

Sie beobachten ein Spektrum aus mehreren Linien bei 100 Hz, 200 Hz, 270 Hz, 400 Hz und
800 Hz. Um was für einen Signaltyp handelt es sich?
> 		quasiperiodisches Signal

Wie sieht das Spektrum eines einzelnen Rechteckimpulses aus?
> 		stetige Funktion

Sie zerlegen ein relativ glattes, periodisches Signal in mehrere Abschnitte und bestimmen in jedem Abschnitt die lokale Fouriertransformation. Wie unterscheiden sich die lokalen Spektra vom Gesamtspektrum und warum?
> 		mehr hohe frequenzen, wegen den Sprüngen an den Fensterrändern

Bei dem Spektrum eines Signals ist der Realteil gerade und der Imaginärteil ungerade.
Um was für einen Signaltyp handelt es sich?
> 		reelles Signal, ohne Symmetrie

Wie unterscheiden sich die Spektren von schnell und langsam veränderlichen Signalen?
> 		Die Spektren schnell veränderlicher Signale haben „unendlich“ hohe Frequenzen

Wie verändert sich das Spektrums einer Rechteckschwingung mit fester Impulsdauer, bei
der die Periode immer weiter erhöht wird?
> 		Das Experiment zeigt: wird die Periodendauer T (bei gleichbleibender Impulsdauer) größer, so wird der Abstand der Linien 1/T notwendigerweise immer enger.

Was ist der Unterschied zwischen der Fourierreihe und dem Spektrum eines periodischen
Signals?
> 		Das Spektrum der kontinuierlichen Fouriertransformation lässt sich als Grenzfall des Linienspektrums der Fourierreihe für den Grenzübergang T -> unendl. einer unendlich großen Signal-Periodendauer darstellen.

Wie wirkt ein lineares System auf das Spektrum eines Signals?
> 		Wird auf den Eingang (oder die Eingänge) eines Systems ein sinusförmiges Signal beliebiger Frequenz gegeben und erscheint am Ausgang lediglich ein sinusförmiges Signal genau dieser Frequenz, so ist der Prozess linear. 12.6 -> spektrum hat gleiche 1. harmonische? 12.6 ff

Was passiert mit dem Spektrum eines Signals, wenn man es in zeitlicher Richtung verschiebt?
> 		f (t − a) °--* e^(−iωa) · F(ω)
> 		-> Betrag bleibt, Phase ändert sich

Wie sieht das Spektrum eines Signals aus, das um den Faktor 2 im Zeitbereich gestreckt wird?
> 		Das Spektrum wird schmaler, da aufgrund der Zeit-Frequenz-Unschärferelation eine höhere Auflösung in der Frequenz gegeben ist

Was passiert mit dem Spektrum eines Signals, wenn man es mit einem konstanten Phasenfaktor mit dem Phasenwinkel a multipliziert?
>     nichts

Wie muss man den Frequenzgang eines Filters im Spektralraum verändern, damit sich die
Impulsantwort in der Zeitdomäne verschiebt?
> 		durch eine Multiplikation des Frequenzgangs mit einem Phasenfaktor e^(−iωa) erreicht man eine Verschiebung der Impulsantwort. 14.19

Wie wirkt die Differentiation auf das Spektrum eines Signals?
> 		Die Ableitung im Frequenzbereich ist besonders einfach: simple Multiplikation um den Faktor iω. 12.17

Was ist ein Bode-Diagramm?
> 		Darstellung des Frequenzgangs anhand H(omega) in abhängigkeit der Frequenz (logarithmitert)


### Phase, Phasengang, Phasenspektrum

Was ist die Phase einer Sinusschwingung?
> 		Die zeitliche Verschiebung der Schwingung

Wie verändert der Phasengang eines linearen Systems die Phase des Eingangssignals?
> 		Phasengang: gibt für jede Frequenz an, wie stark die Phase der Sinusschwingungen verschoben wird. Der Phasengang ist meistens negativ, d.h. der Ausgang folgt verzögert dem Eingang. 12.24

### Amplitude, Amplitudengang, Amplitudenspektrum

Was ist die Regellage?
> 		Die positive Seite des zweiseitigen Amplitudenspektrums ist die Regellage.

Wie sieht der Amplitudengang eines Differenzierers aus?
> 		Jede Sinussignal wird proportional zu seiner Frequenz verstärkt, d.h. der Amplitudengang ist eine Gerade mit Steigung 1. 12.26


### Dirac

Was ist eine δ-Impulsfolge?
> 		Bei einem Dirac-Impuls geht das Tastverhältnis gegen 0. Man bekommt einen Nadelimpuls als Ausgang, dessen Fläche 1 beträgt.

Was ist die Ausblendeigenschaft des Dirac-Impulses?
> 		integral: δ(t) · f (t) dt = f (0).

Wie sieht die Fouriertransformierte des mit 2 skalierten Einheitsimpulses aus?
> 		konstant mit allen frequenzen (da zeitauslösung maximal)

### Frequenz-Zeit-Unschärferelation

Wie berechnet man die Frequenzunschärfe eines Signals?
> 		∆t · ∆f ≥ 0.88 bzw. σt · σω ≥ 1

Was besagt die Frequenz-Zeit-Unschärferelation?
> 		Man kann niemals gleichzeitig Zeitdauer und Frequenz genauer als σt · σω = 1 angeben. Dies ist eine fundamentale Grenze der Fourieranalysis und damit auch der Physik

Was bedeutet die Komplementarität von Frequenz und Zeit?
>     Eine zeitliche Eingrenzung der Signaldauer ∆t bedeutet eine Ausweitung des Frequenzbandes ∆f. 
>     Umgekehrt gilt: Je eingeschränkter das Frequenzband eines Signals ist, desto größer muss zwangsläufig die Zeitdauer des Signals sein.

Bei welchem Signal ist das Produkt aus Zeit- und Frequenzunschärfe genau gleich 1?
> 		Gabor-Wavelet

## Filter

Was ist Filterung?
> 		Veränderung der relativen Amplituden einzelner Frequenzkomponenten in einem Signal 14.12


Welche Eigenschaften haben ideale frequenzselektive Filter im Zeitbereich?
> 		Ideale Filter sind extrem scharf im Frequenzbereich lokalisiert.
> 		Nach der Unschärferelation führt dies zu einer weiträumigen ”Verschmierung” im Zeitbereich. 14.17
> 		- Nichtkausal
> 		- Unendlich große Impulsantwort (Sinc-Funktion)
> 		- Überschwingen
> 		- Oszillierendes Einschwingen 14.18

### Faltung

Wie funktioniert die Faltung, um das Ausgangssignal eines Systems zur Zeit t zu berechnen?
> 		kennt man die Antwort des Systems auf jeden zeitverschobenen Dirac-Impuls, so weiß man die Systemantwort auf jedes beliebige Signal. 13.29 impulsantwort (oder sprungantwort mit anschließendem differenzierer) * f(t) 14.4

Warum verwendet man meist nichtideale Filter mit welligen Durchlass- und Sperrbereichen und einem Übergangsbereich statt idealen frequenzselektiven Filtern?
>     

Was ist das Faltungsintegral?
> 		Systemantwort ermittelt duch integral über f(zeitverschoben t) * impulsantwort h(t - zeitverschoben t)

## Bildsignale

Wofür braucht man ein Dunkelbild?
> 		Um den Dunkelstrom zu korrigieren

Was bedeutet Vignettierung?
> 		Die Helligkeitswerte ändern sich an den Bildrändern

Wie findet man die "dead pixels" einer Kamera?
> 		Dead pixels tauchen im Weißbild als dunkle Pixel auf.


## Akustische Signale

Wie kann man einen Vokal in einem Sprachsignal erkennen?
> 		Vokale sind fastperiodische Signalabschnie in Sprachsignalen. 11.7

Was ist ein Phonem?
> 		die Menge aller Phone, die in einer gesprochenen Sprache die gleiche bedeutungsunterscheidende Funktion haben (z.B. gerolltes “r” und Rachen-“r”). 11.9

Was sind Formanten?
> 		Diejenigen Frequenzbereiche, bei denen die relative Verstärkung (im Hohlraumresonator) am höchsten ist, bezeichnet man als Formanten. 11.18

## Systeme

Ein System liefert für eine Sinusschwingung als Eingangssignal eine doppelt so große
Sinusschwingung gleicher Frequenz als Ausgangssignal, das um 10 ms verzögert ist. Um
welche Art von System handelt es sich?







Wie kann man am Besten die wechselnde Tonhöhe in der Aufnahme eines Solo-Musikstückes
bestimmen?
> 		Grundfrequenz(en)

Wievielen Dezibel entspricht ein Verstärkungsfaktor von 100?
> 		40 db 12.28

Wie funktioniert ein Nächste-Nachbar-Klassifikator?
> 		Für jedes zu erkennende Wort wird ein Referenzspektrum (Prototyp) gespeichert. Der momentane Sprachinput wird mit den Referenzspektren verglichen. Das ähnlichste Referenzspektrum wird als die wahrscheinlichste Wortbedeutung interpretiert. 11.24

Wie unterscheiden sich Korrelation und Kovarianz als Ähnlichkeitsmaß?
> 		Kovarianz ist unabhängig vom Mittelwert 11.26 (Bei der Korrelation ist die "Ähnlichkeit" bei lauten signalen immer größer)


Wie wird die momentane Frequenz eines akustischen Eingangssignals in der Basilarmembran des Innenohrs codiert?
> 		Position der Membran bestimmt Tonhöhe, da die basilarmembran konisch verläuft.
> 		Dünne stellen werden von hohen frequenzen angeregt, Breite stellen von hohen. 11.21

Was ist eine Schwebung?
> 		Interferenz zweier ähnlicher frequenzen -> Amplitude scheint sich periodisch zu ändern
