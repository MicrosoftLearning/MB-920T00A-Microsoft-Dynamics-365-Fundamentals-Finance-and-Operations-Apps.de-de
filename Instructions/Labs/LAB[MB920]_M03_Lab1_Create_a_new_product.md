---
lab:
  title: "Lab\_3.1: Erstellen eines neuen Produkts"
  module: 'Learning Path 3: Learn the fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Lernpfad 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management
# Modul 2: Beschreiben der Vertriebs- und Beschaffungsprozesse

## Lab 3.1: Erstellen eines neuen Produkts

Sie planen in Ihrer Organisation die Herstellung eines neuen Artikels, eines Hemdes. Das Hemd wird unterschiedliche Farben und Größen haben. In diesem Lab erfahren Sie, wie Sie einen neuen Artikel mit mehreren Varianten erstellen und ihn in der juristischen Person USMF freigeben.

## Übungsschritte

1. Wählen Sie im Navigationsbereich von Dynamics 365 Supply Chain Management **Module** und wählen Sie dann **Produktinformationsmanagement** > **Setup** > **Dimensions- und Variantengruppen**. Öffnen Sie die Seite **Farbgruppen** und erstellen Sie einen neuen Datensatz.

    - Farbgruppe: **ShirtColor**

    - Beschreibung: **Hemdfarbe**

2. Geben Sie im Inforegister **Farbgruppenlinien** die folgenden drei Datensätze ein:

    | **Farbe** | **Farbname** |
    |-----------|----------------|
    | Blau      | Blau           |
    | White     | Weiß          |
    | Schwarz     | Schwarz          |


3. Speichern Sie die Datensätze.

4. Wählen Sie **Produktinformationsmanagement** > **Einrichten** > **Dimensions- und Variantengruppen**. Öffnen Sie die Seite **Größengruppen** und erstellen Sie einen neuen Datensatz.

    - Größengruppe: **ShirtSize**

    - Beschreibung: **Hemdgröße**

5. Geben Sie im Inforegister **Größengruppenlinien** die folgenden drei Datensätze ein

    | **Größe** | **Name der Größe** |
    |----------|---------------|
    | S        | Klein         |
    | M        | Medium        |
    | L        | Large         |


6. Speichern Sie die Datensätze.

7. Wählen Sie im Navigationsbereich von Dynamics 365 Supply Chain Management **Module** und dann **Produktinformationsmanagement**. Wählen Sie dann im Menü **Produkte** den Eintrag **Produktmaster**.

8. Auf der Seite **Produktmaster**, wählen Sie im oberen Menü **+ Neu**.

9. Stellen Sie auf der Seite **Neues Produkt** im Feld **Produkttyp** sicher, dass **Artikel** ausgewählt ist.

10. Überprüfen Sie im Feld **Produktuntertyp**, dass **Produktmaster****** ausgewählt ist.

11. Geben Sie auf der Registerkarte **Identifikation** in das Feld **Produktnummer** **SH001** ein.

12. In das Feld **Produktname** geben Sie **Hemd** ein.

13. Geben Sie in das Feld **Produktabmessungsgruppe** **Farbgröße** ein.

14. Klicken Sie auf die Schaltfläche **OK**.

15. Wählen Sie im Aktionsbereich im Menü **Produkt** unter der Gruppe **Einrichten** den Eintrag **Dimensionsgruppen**.

16. Wählen Sie in der Dropdown-Liste **Lagerdimensionsgruppe** die Option **SiteWH**.

17. Wählen Sie in der Dropdown-Liste **Rückverfolgungsgruppe** die Option **Keine**.

18. Wählen Sie die Schaltfläche **OK** aus.

19. Wählen Sie **ShirtColor** in der Liste **Farbgruppe**.

20. Wählen Sie **Hemdengröße** in der Liste **Größengruppe**.

21. Wählen Sie die Schaltfläche **Produktvarianten** im Aktionsbereich.

22. Wählen Sie auf der Seite **Produktvarianten** im Aktionsbereich die Schaltfläche **Variantenvorschläge**.

23. Wählen Sie die Schaltfläche **Alle vorschlagen** auf der Seite **Variantenvorschläge**.

24. Wählen Sie die vorgeschlagenen Varianten aus, indem Sie die Schaltfläche **Alle auswählen** und anschließend die Schaltfläche **Erstellen** wählen.

Varianten werden auf der Seite „Produktvarianten“ erstellt.

25. Wählen Sie die Schaltfläche **Produkte freigeben** im Aktionsbereich, um das Produkt in einer juristischen Person freizugeben.

26. Eine Seite wird geöffnet, auf der der erste Schritt als **Zu veröffentlichende Produkte auswählen** angezeigt wird.

27. Wählen Sie unten auf dieser Seite die Schaltfläche **Weiter** aus.

28. Markieren Sie die Varianten, die Sie in der juristischen Person freigeben möchten, und wählen Sie die Schaltfläche **Weiter**.

29. Auf der Seite **Unternehmen zur Freigabe auswählen** wählen Sie die juristische Person **USMF** aus, für die das Produkt freigegeben werden soll.

30. Wählen Sie unten auf dieser Seite die Schaltfläche **Weiter** aus.

31. Auf der Seite **Auswahl bestätigen** legen Sie den Wert von **Infolog bei Fehler anzeigen** auf **Ja** und **Als Batch ausführen** auf **Nein** fest.

32. Wählen Sie unten auf dieser Seite die Schaltfläche **Fertigstellen** aus.

33. Wechseln Sie oben rechts als juristische Person zu **USMF**.

34. Wählen Sie im Navigationsbereich **Module** und dann **Produktinformationsverwaltung** aus. Wählen Sie dann im Menü **Produkte** die Option **Freigegebene Produkte** aus.

33. Auf der Seite **Produkte freigeben** suchen Sie den neuen Artikel **SH001** im Raster.

34. Wählen Sie den Produktlink aus und navigieren Sie zur Seite **Freigegebene Produktdetails**.

35. Im Inforegister **Allgemein** geben Sie Folgendes ein:

    - Artikel Modellgruppe: **FIFO**

36. Auf der Registerkarte **Kauf** FastTab geben Sie Folgendes ein:

    - Einheit: **ea**

    - Artikel-Mehrwertsteuergruppe: **ALLE**

    - Preis: **30**

37. Im Inforegister **Verkauf** geben Sie Folgendes ein:

    - Einheit: **ea**

    - Artikel-Mehrwertsteuergruppe: **ALLE**

    - Preis: **35**

38. Geben Sie im Inforegister **Bestandsverwaltung** die folgenden Informationen ein:

    - Einheit: **ea**

39. Geben Sie im Inforegister **Techniker** die folgenden Informationen ein:

    - Stücklisteneinheit: **ea**

40. Geben Sie im Inforegister **Kosten verwalten** die folgenden Informationen ein:

    - Artikelgruppe: **Audio**

41. Wählen Sie im Aktionsbereich **Produkt** aus, um die Konfiguration abzuschließen. Wählen Sie die Schaltfläche **Überprüfen** unter der Gruppe **Verwalten** aus.

42. Schließen Sie alle Seiten, und kehren Sie zur **Startseite** zurück.

 
