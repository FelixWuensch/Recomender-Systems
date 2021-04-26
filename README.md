# Recomender-Systems
Prüfungsaufgabe 1- Vierter Teil

Um dieses Projekt zu starten, folgen Sie dem Binder Badge:      



# Ausführung der Übungsaufgabe

!!! Alle Befehle werden ausgeführt in dem die Zeile ausgewählt wird und anschließend mit Shift (Großschreibtaste) und Enter gestartet wird !!!

1. Im ersten Schritt müssen alle benötigten Libraries installiert und importiert werden, so dass im Folgenden alle Befehle erfolgreich ausgeführt werden können.

2. Danach werden unsere Daten im CSV Format eingelesen und die Spalten Überschriften werden eingefügt.

3. Daraufhin werden die Daten wieder begutachtet mit der üblichen Funktion: head().

4. Dann lesen wir die zweite Datei ein, welche wir Movie_Titles nennen. Davon lassen wir uns wieder den head() ausgeben.

5. Im fünften Schritt werden dann die zwei Daten zusammengefügt über die gleiche Spalte „Item_id“. 

6. Nun werden die Importe getätigt um die Daten zu veranschaulichen.

7. Damit beginnen wir auch direkt und erstellen ein DataFrame, welches die Filme nach ihrem Ranking sortiert. Ebenso ein weiteres welches die Daten nach der Anzahl an Bewertungen sortiert. Daraus basteln wir uns ein DataFrame, welches uns die Anzahl an Bewertungen mit dem Rating ausgibt. 

8. Das neu erzeugt DataFrame wird gleich in einem Histogramm veranschaulicht, dabei wir die Anzahl der Ratings angezeigt. Und im nächsten Histogramm werden die Filme nach ihrem Rating verteilt angezeigt. Zu guter Letzt betrachten wir die Daten noch in einem Jointplot.

9. Nach dem wir uns nun die Daten veranschaulicht haben, gehen wir nun dazu über ähnliche Filme zu empfehlen. Dazu erstellen wir eine Matrix aus der „User_ID“, dem „Title“ und dem „Rating“ und lassen uns diese Matrix anzeigen.

10. Wir lassen uns noch einmal die ersten 10 Besten Ratingfilme ausgeben und entscheiden uns dann für die Filme „Star Wars“ und „Liar Liar“. Dann lassen wir uns das Rating der Benutzer ausgeben. Danach können wir mit der Funktion .corrwith() uns Korrelierende Filme auf Basis der User Ratings berechnen lassen. Um das ganze abzurunden entfernen wir dann alle „NaN“ Werte, ebenso transferieren wir die Werte aus der Series in ein DataFrame und lassen uns den head() anzeigen.

11. Im elften Schritt lassen wir uns dann die Titel der Filme nach Ihrer Korrelation sortiert ausgeben. Dann entfernen wir noch alle Filme, welche weniger als 100 Bewertungen erhalten haben, da diese nicht aussagekräftig genug sind. Am Ende lassen wir uns für die Filme „Star Wars“ und „Liar Liar“ das jeweilige DataFrame anzeigen und sehen damit, welches die Top 5 korrelierenden Filme sind, welche dann auch vorgeschlagen werden sollten. 

Damit ist das Kapitel der Recommender-Systems abgeschlossen. Wir haben uns dafür die Daten genauer angeschaut mit der explorativen Datenanalyse. Dann haben wir uns zwei Filme ausgewählt und für diese die Daten strukturiert, so dass wir passende Korrelationen finden konnten. Zum Schluss haben wir und dann die Liste der Top 5 korrelierenden Filme ausgeben lassen. Dies sind dann auch die Top 5 Filme, welche dann von dem Recommender-System vorgeschlagen werden. Somit gehen wir weiter zum Thema Natural Language Processing.
