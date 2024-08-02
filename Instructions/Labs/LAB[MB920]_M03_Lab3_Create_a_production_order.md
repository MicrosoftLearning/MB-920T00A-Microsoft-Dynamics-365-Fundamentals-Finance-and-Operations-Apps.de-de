---
lab:
  title: "Lab\_3.2: Erstellen eines Produktionsauftrags"
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Lernpfad 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management
# Modul 4: Beschreiben des Herstellungsprozesses

## Lab 3.2: Erstellen eines Produktionsauftrags

## Ziel

Fertigungsaufträge helfen, den Fertigungsprozess in Supply Chain Management einzuleiten. In dieser Übung machen Sie sich mit der Benutzeroberfläche und den Funktionen des Fertigungsauftragsformulars vertraut. Außerdem erfahren Sie am Ende der Übung, wie Sie einen Produktionsauftrag erstellen und bearbeiten können.

## Übungsschritte

1. Vergewissern Sie sich auf der Startseite von Dynamics 365 **Supply Chain Management** oben rechts, dass Sie mit dem Unternehmen **USMF** arbeiten.

2. Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus.

3. Wählen Sie im linken Navigationsbereich **Module** > **Produktionssteuerung** > **Produktionsaufträge** > **Alle Produktionsaufträge** aus.

4. Wählen Sie im oberen Menü **Neuer Produktionsauftrag** und geben Sie folgende Daten ein.

    - Artikel Nummer: **D0002**

    - Menge: **10**

    - Standort: **1**

    - Lagerort: **11**

    - Lieferung: [wählen Sie ein Datum einen Monat nach dem heutigen Datum]

    - Stücklistennummer: **D0002BOM**

    - Routennummer: **000004**

5. Wählen Sie die Schaltfläche **Erstellen**.

Es wird ein neuer Produktionsauftrag für 10 Stück des Artikels D0002 erstellt.

6. Wählen Sie **Produktionsauftrag (Menü des Aktionsfensters) &gt; Verarbeiten &gt; Schätzen.**

7. Wählen Sie im Dialogfeld **Schätzung** im Feld **Gewinneinstellung** die Option **Standard**, markieren Sie das Feld **Referenzen** und wählen Sie die Schaltfläche **OK**.

Der **Status** des Produktionsauftrags ändert sich in **Geschätzt**.

8. Wählen Sie **Planen (Menü des Aktionsbereichs) &gt; Produktionsauftrag &gt; Vorgänge planen.**

9. Wählen Sie im Dialogfenster **Vorgangsplanung** im Feld **Planungsrichtung** die Option **Ab heute** und wählen Sie die Schaltfläche **OK**.

10. Wählen Sie **Ansicht (Menü des Aktionsbereichs) &gt;Zugehörige Informationen &gt;Kapazitätsreservierung**.

11. Überprüfen Sie die neu erstellten Datensätze auf der Seite **Kapazitätsreservierung**.

12. Navigieren Sie zurück zur Seite **Alle Produktionsaufträge**. Beachten Sie, dass sich der **Status** des Produktionsauftrags in **Geplant** ändert.

13. Wählen Sie **Produktionsauftrag (Menü des Aktionsfensters) &gt; Bearbeiten &gt; Freigabe**.

14. Im Dialogfeld **Freigabe** markieren Sie das Feld **Referenzen** und wählen die Schaltfläche **OK**.

15. Der **Status** des Produktionsauftrags ändert sich in **Freigegeben**.

16. Wählen Sie **Produktionsauftrag (Menü des Aktionsbereichs) &gt; Prozess &gt; Starten**.

17. Wählen Sie im Dialogfeld **Starten** die Registerkarte **Allgemein**.

18. Auf der Registerkarte **Allgemein** geben Sie Folgendes ein.

    - Datum: **Heutiges Datum**

    - Menge: **10**

    - Produktion starten: **JA**

    - Arbeitsplanliste jetzt buchen: **NEIN**

    - Kommissionierliste jetzt buchen: **NEIN**

19. Wählen Sie die Schaltfläche **OK** aus.

Der **Status** des Produktionsauftrags ändert sich in **Gestartet**.

20. Wählen Sie **Ansicht (Menü des Aktionsbereichs) &gt;Journale &gt;Kommissionierliste**.

Es wird ein neues Kommissionierlistenjournal mit drei Zeilen erstellt.

21. Buchen Sie das Kommissionierlistenjournal.

22. Navigieren Sie zurück zur Seite **Alle Produktionsaufträge** und wählen Sie **Ansicht (Menü des Aktionsbereichs) &gt; Journale &gt; Arbeitsplanliste**.

Ein neues Arbeitsplanlistenjournal wird mit drei Zeilen erstellt.

23. Markieren Sie das Feld **Vorgang abgeschlossen** in allen drei Zeilen und buchen Sie das Arbeitsplanlistenjournal.

24. Navigieren Sie zurück zur Seite **Alle Produktionsaufträge** und wählen Sie **Produktionsaufträge (Menü des Aktionsbereichs) &gt; Verarbeiten &gt; Als abgeschlossen melden**.

25. Geben Sie im Dialogfeld **Als abgeschlossen melden** **10** in das Feld **Gutmenge** ein. Markieren Sie das Feld **Auftrag beenden** und wählen Sie **OK**.

Der **Status** des Produktionsauftrags ändert sich in **Beendet**. Der Bestand des Artikels **D0002** erhöht sich um 10 in Betrieb 1 und Lager 11.

26. Wählen Sie **Kosten verwalten (Menü des Aktionsbereichs) &gt;Berechnungen &gt;Berechnungsdetails anzeigen**.

Notieren Sie sich die Endkalkulation des hergestellten Artikels auf der Registerkarte **Übersicht der Kalkulation**.

 
