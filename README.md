# Einführung
Im Rahmen unseres Projekts haben wir anhand des Datensatzes "IMDB Video Games" verschiedene Aspekte von Videospielen untersucht um ein besseres Verständnis für die Trends und Popularität von Videospielen zu gewinnen. Untersucht wurde unter anderem die Genrehäufigkeit, der Einfluss der Altersfreigabe auf die Popularität, der Einfluss des Erscheinungsjahres auf die Popularität, ob es einen Zusammenhang zwischen dem Erscheinungsjahr eines Spiel in dem beliebtesten Genre in diesem Jahr gibt und ob es einen Zusammenhang zwischen dem Verhältnis von Genre und Alterfreigabe gibt. 

Um diese Forschungsfragen zu beantworten wurden folgende Methoden verwendet: Statistische Auswertungen, Zeitreihenanalyse, Kreuztabellen und Grafiken. 

# Forschungsfrage 1 - Häufigkeiten der Genres
Welche Muster gibt es in der Verteilung der Genrehäufigkeiten in Videospielen, und was könnten diese über die Entwicklungstrends in der Videospielindustrie aussagen?

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/18d2ff0d-f135-46aa-8cf7-e7b9f7f719d1)

Die Grafik zeigt, dass das Genre 'Action' das mit Abstand beliebteste Genre ist, dicht gefolgt von 'Adventure'.
Beide Genres sind bekannt für ihre dynamischen und interaktiven Gameplay-Elemente, was sie bei einem breiten Spektrum von Spielern beliebt macht.
Das 'Fantasy'-Genre, das oft mit epischen Geschichten und komplexen Welten assoziiert ist, folgt an dritter Stelle, was darauf hinweist, dass auch immersive Spielerfahrungen sehr gefragt sind.

Es gibt einen deutlichen Abfall in der Häufigkeit nach dem 'Fantasy'-Genre. Die Genres 'Family' und 'Sci-Fi' weisen weniger als die Hälfte der Häufigkeit von 'Fantasy' auf.

Die geringere Häufigkeit der Genres 'Comedy', 'Crime', 'Mystery' und 'Thriller' könnte darauf hinweisen, dass diese Genres spezifischere Zielgruppen ansprechen oder dass sie oft als sekundäre Genres in Spielen erscheinen, die hauptsächlich als Action oder Adventure kategorisiert werden.

Diese Verteilung könnte auch spiegeln, welche Arten von Spielen Entwickler bevorzugen oder als finanziell sicherer betrachten. 

Zusammenfassend lässt sich sagen, dass die Videospielindustrie eine klare Neigung zu Action- und Adventure-Spielen zeigt. 


![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/c41e381d-fabf-44cd-acce-1e179e6ee132)

Das Genre 'Action' stellt mit 31,8% den größten Anteil der Spiele im Datensatz dar.
'Adventure'-Spiele machen 27,6% aus, was zeigt, dass auch dieses Genre sehr beliebt ist. 

'Fantasy'- und 'Sci-Fi'-Spiele zeigen ebenfalls einen signifikanten Anteil mit 11,6% bzw. 9,6%. Diese Genres sind oft für die Möglichkeit, den Spieler in eine ganz andere Umgebung zu versetzen, was ihre Beliebtheit erklären könnte.

'Family'-Spiele stehen bei 7,7%, was auf eine solide Präsenz von Spielen hinweist, die für alle Altersgruppen geeignet sind und die man oft zusammen mit der Familie genießen kann.

'Comedy', 'Crime', 'Mystery' und 'Thriller' haben die niedrigsten Anteile mit 4,8%, 3,4%, 3,2% und 3,2%. Diese Genres könnten spezialisierte Nischen darstellen, die auf bestimmte Spielergruppen ausgerichtet sind oder oft in Kombination mit anderen Genres wie Action und Adventure auftreten.

# Forschungsfrage 2 
Altersfreigabe und Popularität: Hat die Altersfreigabe (certificate) eines Spiels einen Einfluss auf seine Popularität (Bewertungen und Stimmen)? Sind Spiele mit einer bestimmten Altersfreigabe im Durchschnitt beliebter?

Die folgende Grafik zeigt die durchschnittliche Bewertung (rating) und die durchschnittliche Anzahl von Stimmen (votes) für Spiele, gruppiert nach ihrer Altersfreigabe (certificate).

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/1f624661-0233-4b36-93ca-811f379bbdb3)

Spiele mit der Altersfreigabe 'M' (Mature) haben die höchste durchschnittliche Bewertung mit 7.52. Dies könnte darauf hinweisen, dass Spiele, die für ein erwachsenes Publikum bestimmt sind, höher bewertet werden, möglicherweise weil sie komplexere Themen besitzen. 

Spiele mit der Altersfreigabe 'M' haben auch die höchste durchschnittliche Anzahl an Stimmen. Dies deutet auf die größte Popularität oder auf eine aktivere Spielergemeinschaft. 

Die Altersfreigaben '12', 'T' (Teen) und 'E10+' (Everyone 10 and older) folgen mit durchschnittlichen Bewertungen von 7.35, 7.30 bzw. 7.18. Dies deutet darauf hin, dass auch Spiele, die sich an Teenager und etwas jüngere Spieler richten, gut bewertet werden

Altersfreigaben mit weniger geläufigen Bezeichnungen, wie 'MA-13', 'TV-MA', 'TV-14' und 'Approved', haben entweder eine sehr geringe Anzahl von Stimmen oder sehr spezifische Durchschnittsbewertungen, was darauf hinweisen könnte, dass diese Kategorien seltener verwendet werden oder nur eine kleine Anzahl von Spielen repräsentieren.

Not Rated' und 'Unrated' Spiele haben eine breite Streuung in Bewertungen und Stimmen, was auf eine diverse Gruppe von Spielen hindeutet, die entweder nicht offiziell bewertet wurden oder aus anderen Gründen keine Bewertung erhalten haben.

Es scheint eine Tendenz zu geben, dass Spiele, die sich an ein älteres Publikum richten (wie 'M' und 'T'), im Durchschnitt besser bewertet werden und mehr Bewertungen erhalten als Spiele für jüngere Zielgruppen. Dies könnte auf eine größere Spielerbasis in diesen Altersgruppen oder auf eine höhere Qualität und Tiefgründigkeit der Spiele hinweisen, die diese Altersgruppen ansprechen. 

Insgesamt zeigen die Daten, dass Altersfreigaben in Zusammenhang mit der Bewertung und der Anzahl der abgegebenen Stimmen stehen, was auf einen Einfluss der Altersfreigabe auf die wahrgenommene Qualität und Beliebtheit eines Spiels hindeutet.

# Forschungsfrage 3 - Einfluss des Erscheinungsjahres

Wie beeinflusst das Erscheinungsjahr die Bewertung und Popularität eines Spiels? Gibt es Trends, die auf das Alter eines Spiels hinweisen?

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/b5131cca-442a-4f84-9be0-ef823263a53e)

Die durchschnittliche Bewertung der Spiele scheint im Laufe der Zeit relativ stabil zu sein, mit Werten, die größtenteils im Bereich von etwa 5,5 bis 7,5 liegen. Es gibt einige Ausreißer, vor allem in den frühen Jahren, wo die Bewertungen nicht sehr konsistenz scheinen, was auf eine geringere Anzahl von Spielen und somit auf eine größere Sensibilität gegenüber einzelnen Spielebewertungen hinweisen könnte.

Ab den späten 1980er bis Anfang der 1990er Jahre stabilisiert sich die durchschnittliche Bewertung und zeigt einen allmählichen Anstieg.

Die durchschnittliche Anzahl der Stimmen pro Spiel zeigt eine interessante Tendenz: Ab den späten 1990er Jahren gibt es einen allgemeinen Aufwärtstrend, der seinen Höhepunkt in den 2000er Jahren erreicht, gefolgt von einem scharfen Rückgang nach 2010.

Dies könnte auf die zunehmende Verfügbarkeit und Popularität von Online-Bewertungsplattformen zurückzuführen sein. 

Es scheint, dass das Erscheinungsjahr eines Spiels einen gewissen Einfluss auf die Popularität hat, gemessen an der Anzahl der Stimmen, die es erhält. Neuere Spiele haben möglicherweise noch nicht die Zeit gehabt, eine vergleichbare Anzahl von Stimmen zu sammeln wie ältere Spiele, was den Rückgang in den letzten Jahren erklären könnte.

In Bezug auf die Bewertung scheint das Erscheinungsjahr keinen klaren, langfristigen Trend hinsichtlich der Qualität der Spiele anzuzeigen. Die Qualität, gemessen an der durchschnittlichen Bewertung, bleibt über die Jahre hinweg relativ konstant, abgesehen von natürlichen Schwankungen, die auf die Veröffentlichung von Spielen mit unterschiedlichem Erfolg in verschiedenen Jahren zurückzuführen sein können.

Insgesamt deutet die Grafik darauf hin, dass das Alter eines Spiels hinsichtlich der Anzahl der Stimmen eine Rolle spielt, während die durchschnittliche Bewertung eines Spiels relativ altersunabhängig zu sein scheint

# Forschungsfrage 4 - Genre und Erscheinungsjahr-Korrelation:

Gibt es eine Korrelation zwischen dem Erscheinungsjahr eines Spiels und den Genres, die in diesem Jahr populär waren? Wie haben sich die Genrepräferenzen im Laufe der Zeit verändert, und was könnte das über die Entwicklung der Spieleindustrie aussagen?

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/dc3c3732-9f5a-4502-bc03-334f42fc1c22)

In der Grafik wurde für jedes Jahr der Anteil der Spiele pro Genre im Verhältnis zur Gesamtanzahl der Spiele berechnet. Die Daten wurden dann als Zeitreihe dargestellt, wobei jede Linie ein Genre repräsentiert. Die y-Achse zeigt den Anteil der Spiele des jeweiligen Genres, während die x-Achse das Erscheinungsjahr darstellt. Die verschiedenen Farben repräsentieren die unterschiedlichen Genres. 

Die Grafik zeigt deutlich, dass bestimmte Genres im Laufe der Zeit an Popularität gewonnen oder verloren haben.  Das Genre 'Action' zum Beispiel scheint über den gesamten Zeitraum hinweg eine wesentliche Rolle einzunehmen, mit einem deutlichen Anstieg in den letzten Jahren (Farbe hellblau). 

Genres wie 'Adventure' und 'Fantasy' zeigen ebenfalls einen Aufwärtstrend, was auf eine steigende Beliebtheit dieser Genres in neueren Spielen deutet.

Einige Genres haben konstante, aber niedrigere Anteile , wie zb 'Crime' und 'Thriller', was darauf hindeutet, dass diese Genres eine konstante, aber kleinere Fangemeinde von Spieler:Innen haben.

Man sieht in der Grafik deutlich, dass bestimmte Genres in bestimmten Zeiträumen an Popularität gewinnen, was zb auf neue technologische Entwicklungen deuten könnte oder auch auf gewisse Neuerscheinungen von bestimmten Videospielen.  

Die Grafik legt nahe, dass es eine Veränderung in den Genrepräferenzen über die Zeit gibt, was auf eine Evolution der Spieleindustrie hindeutet. 

Die Videospiel-Industrie scheint responsive auf solche Trends zu sein, was durch die Anpassung des Angebots an die Nachfrage nach bestimmten Genres gezeigt wird.

# Forschungsfrage 5 - Verhältnis von Genre zu Altersfreigabe
Welche Genres neigen dazu, welche Altersfreigaben zu erhalten? Gibt es bestimmte Genres, die häufiger eine bestimmte Altersfreigabe wie 'E' für jedermann oder 'M' für ein reifes Publikum bekommen? Könnte dies auf Genre-spezifische Inhalte zurückzuführen sein, die für bestimmte Altersgruppen geeigneter sind? Wie sieht der Code dafür aus? 

Um die Forschungsfrage zu beantworten, welche Genres dazu neigen, bestimmte Altersfreigaben zu erhalten, wurde die Methode der Kreuztabelle (Contingency Table) verwendet.

Diese Methode eignet sich besonders gut, da sie es ermöglicht, die Häufigkeiten der Kombinationen dieser kategorialen Variablen zu zählen und in einer Matrixform darzustellen. Dadurch kann man leicht erkennen, ob es bestimmte Muster gibt, wie etwa ob bestimmte Genres eine Tendenz zu bestimmten Altersfreigaben aufweisen.

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/4ec4d93a-2dfd-4bc2-94e5-fdb3e447baa7)

![image](https://github.com/Alisa99j/DQDA_Projekt/assets/155681145/78222462-065f-4bef-8f37-2b8df0e53e42)

Die Altersfreigabe 'T' (Teen) ist am häufigsten mit Action- und Adventure-Spielen verbunden, was darauf hindeutet, dass diese Genres für ein jugendliches Publikum beliebt und angemessen sind.

Spiele mit der Freigabe 'M' (Mature) folgen dicht dahinter bei Action- und Adventure-Genres, aber es ist auch bemerkenswert, dass dieses Rating in Verbindung mit dem Crime-Genre häufiger vorkommt als bei anderen Genres. Dies könnte darauf hinweisen, dass Crime-Spiele tendenziell Inhalte aufweisen, die für ein erwachsenes Publikum als geeignet angesehen werden.

Spiele mit der Einstufung 'E' (Everyone) sind bei Family-Spielen sehr häufig, was zu erwarten ist, da diese Spiele für alle Altersgruppen geeignet sind. Das Genre 'Fantasy' scheint ebenfalls eine signifikante Anzahl von 'E' Bewertungen zu haben, was auf familienfreundliche Inhalte hindeutet.
Die Einstufung 'E10+' (Everyone 10 and older) wird auch hauptsächlich bei Family- und Adventure-Genres vergeben, was darauf schließen lässt, dass diese Spiele Inhalte enthalten, die für etwas ältere Kinder gedacht sind.

Die Daten zeigen klare Muster in der Zuweisung von Altersfreigaben zu bestimmten Genres. Action- und Adventure-Spiele neigen dazu, Bewertungen zu erhalten, die sie für Jugendliche und Erwachsene geeignet machen ('T' und 'M'), während Family- und Fantasy-Genres häufiger als für alle Altersgruppen geeignet eingestuft werden ('E').

# Ergebnisse der Forschung 
 # Genrehäufigkeiten in Videospielen:
•	Action und Adventure sind die beliebtesten Genres.

•	Fantasy folgt an dritter Stelle. 

•	Genres wie Family und Sci-Fi sind weniger häufig.

•	Niedrigere Häufigkeiten bei Comedy, Crime, Mystery und Thriller könnten auf spezifischere Zielgruppen hinweisen.
 # Altersfreigabe und Popularität:
•	Spiele mit der Freigabe 'M' (Mature) haben die höchsten durchschnittlichen Bewertungen und die meisten Stimmen, was auf eine Beliebtheit bei einem erwachsenen Publikum hinweist.

•	Andere Altersfreigaben wie '12', 'T' (Teen) und 'E10+' (Everyone 10 and older) sind ebenfalls gut bewertet.

•	Es scheint eine Tendenz zu geben, dass Spiele für ältere Zielgruppen im Durchschnitt besser bewertet werden und mehr Bewertungen erhalten. 
# Einfluss des Erscheinungsjahres auf Bewertung und Popularität:
•	Die durchschnittliche Bewertung der Spiele bleibt über die Zeit relativ stabil.

•	Die durchschnittliche Anzahl der Stimmen pro Spiel zeigt einen Aufwärtstrend bis in die 2000er Jahre, gefolgt von einem Rückgang.

•	Das Erscheinungsjahr scheint einen Einfluss auf die Anzahl der Stimmen zu haben, aber nicht auf die durchschnittliche Bewertung.
# Genre und Erscheinungsjahr-Korrelation:
•	Bestimmte Genres wie Action, Adventure und Fantasy zeigen im Laufe der Zeit einen Aufwärtstrend.

•	Genres wie Crime und Thriller bleiben konstant, aber mit niedrigeren Anteilen.

•	Die Veränderungen in den Genrepräferenzen könnten zb auf technologische Entwicklungen  hinweisen.

•	Die Videospiel-Industrie scheint auf diese Trends zu reagieren, indem sie das Spielangebot entsprechend anpasst. 
# Verhältnis von Genre zu Altersfreigabe:

•	 Die Altersfreigabe 'T' (Teen) ist häufig mit Action- und Adventure-Spielen verbunden.

•	'M' (Mature) wird oft bei Action-, Adventure- und Crime-Genres vergeben.

•	'E' (Everyone) ist typisch für Family-Spiele und das Genre 'Fantasy'.

•	Diese Muster zeigen, dass bestimmte Genres dazu tendieren, spezifische Altersfreigaben zu erhalten. 

# Ausblick 

Mögliche Forschungsfragen für zukünftige Untersuchungen: 

Ökonomische Aspekte der Spieleentwicklung:
Wie wirken sich wirtschaftliche Faktoren auf die Produktion und den Erfolg von Spielen in verschiedenen Genres aus?

Kulturelle Untersuchungen:
Gibt es signifikante Unterschiede in den Genrepräferenzen zwischen verschiedenen Kulturen oder geografischen Regionen?

Gesundheitsaspekte und Videospielkonsum:
Welchen Einfluss haben verschiedene Genres auf die psychische und physische Gesundheit der Spieler?









