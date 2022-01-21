---
lab:
    title: 'Lab 3: Dynamics 365 Finance Capstone-Lab'
    module: 'Modul 2: Grundlagen von Microsoft Dynamics 365 Finance erlernen'
---

## Lab 3 – Dynamics 365 Finance Capstone-Lab

## Ziel

In diesem Lab erkunden Sie die zentralen Funktionen von Dynamics 365 Finance. Sie erkunden das Hauptbuch, indem Sie eine neue juristische Person erstellen, ein neues Konto und Dimensionswerte hinzufügen und eine Zwischenbilanz ausführen. Sie erkunden außerdem Kreditorenkonten, indem Sie einen neuen Kreditor, eine Bestellung und eine Rechnung erstellen und die Rechnung bezahlen. Abschließend erkunden Sie Debitorenkonten, indem Sie einen neuen Kunden, eine Rechnung und einen Fälligkeitsbericht erstellen und dann die Kundenzahlung anwenden.

## Lab-Einrichtung

   - **Geschätzte Dauer**: 45 Minuten

## Übung 1: Hauptbuch erkunden

### Neue juristische Person erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Organisationsverwaltung** > **Organisationen** > **Juristische Personen** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um eine neue juristische Person zu erstellen.

1. Erstellen Sie im Bereich **Neue juristische Person** anhand der folgenden Daten eine neue juristische Person, und klicken Sie auf **OK**:

    | **Einstellung** | **Wert** |
    | :--- | :--- |
    | Name | Contoso Training USA |
    | Unternehmen | USTR |
    | Land/Region | USA |

1. Wählen Sie auf der Seite „Juristische Personen“ das Inforegister **Adressen** und **Bearbeiten** aus.

1. Geben Sie im Faktenfeld die folgenden Aktualisierungen ein, und klicken Sie dann auf **OK**:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Postleitzahl| 98052|
    | Straße| 123 Main Street|
    | Primär für Land/Region | Stellen Sie sicher, dass **Ja** ausgewählt ist. |

1. Wählen Sie das Inforegister **Kontaktdaten** aus.

1. Wählen Sie **+Hinzufügen** aus, und geben Sie den folgenden Kontakt ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Beschreibung| Firmenhauptsitz|
    | Name/Adresse des Kontakts| 888-555-1234|
    | Primär| Kontrollkästchen aktivieren |

1. Wählen Sie das Inforegister **Steuerregistrierung** aus.

1. Geben Sie im Feld **Steuernummer** die Nummer **88-1234567** ein.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Navigationsbereich **Start** aus.

### Neues Konto in einem vorhandenen Kontenplan erstellen

1. Überprüfen Sie auf der Startseite oben rechts, dass das Unternehmen **USMF** ausgewählt ist.  
    Wenn nicht, wählen Sie das aktuell ausgewählte Unternehmen aus, und ändern Sie das Unternehmen dann in **USMF**.

1. Wählen Sie im Navigationsbereich **Module** > **Hauptbuch** > **Kontenplan** > **Konten** > **Hauptkonten** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um eine neues Konto für Umsatzerlöse zu erstellen.

1. Geben Sie auf der Seite „Hauptkonten“ die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Hauptkonto| 401500|
    | Name| Schulungsumsatz|
    | Hauptkontotyp| Umsatz |

1. Wählen Sie im Aktionsbereich **Speichern** aus.

### Neuen Dimensionswert hinzufügen

1. Wählen Sie im Navigationsbereich **Module** > **Hauptbuch** > **Kontenplan** > **Dimensionen** > **Finanzdimensionen** aus.

1. Wählen Sie in der Navigationsliste **ServiceLine** aus.  
    Sie können auch anhand des Felds **Filter** nach **ServiceLine** suchen.

1. Wählen Sie im Aktionsbereich **Dimensionswerte** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus.

1. Geben Sie in den Feldern **Dimensionswert** und **Beschreibung** den Text **Training Services** ein.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

### Konto und Dimensionswert in einer allgemeinen Erfassung verwenden

1. Wählen Sie im Navigationsbereich **Module** > **Hauptbuch** > **Journaleinträge** > **Allgemeine Erfassungen** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus.

1. Wählen Sie in der ersten Zeile der Liste in der Spalte **Name** das Menü dann **Allgemeine Erfassung** aus.

1. Wählen Sie im Aktionsbereich **Positionen** aus.

1. Wählen Sie in der Liste in der Spalte **Datum** das Kalendersymbol aus, und ändern Sie das Datum dann in den 1. des Monats.

1. Wählen Sie in der Spalte **Konto** das Menü aus, und geben Sie dann die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Hauptkonto| 601200|
    | Unternehmenseinheit| 004|
    | Abteilung| 025|
    | CostCenter| 009|
    | Artikelgruppe| Dienste|

1. Geben Sie im Feld **Beschreibung** den Text **Expense Reclass** ein.

1. Geben Sie im Feld **Soll** den Wert **1000,00** ein.

1. Scrollen Sie nach rechts, und wählen Sie in der Spalte **Gegenkonto** das Menü aus. Geben Sie dann die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Hauptkonto| 602200|
    | Unternehmenseinheit| 004|
    | Abteilung| 025|
    | CostCenter| 009|
    | Artikelgruppe| Dienste|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich **Prüfen** > **Überprüfen** aus.  
    Warten Sie, bis die Erfassungsüberprüfung abgeschlossen ist.

1. Sehen Sie sich das Warnbanner an.  
    Diese Warnung kann in diesem Lab ignoriert werden.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

### Zwischenbilanz mit einem Dimensionssatz ausführen

1. Wählen Sie im Navigationsbereich **Module** > **Hauptbuch** > **Abfragen und Berichte** > **Zwischenbilanz** aus.

1. Wählen Sie auf der Seite „Zwischenbilanz“ die Option **Salden berechnen** aus.

1. Die Schaltfläche **Salden berechnen** befindet sich unter den Einstellungen für **EINZUBEZIEHENDE DATEN**.

1. Überprüfen Sie die Ergebnisse in der Tabelle.

1. Erweitern Sie auf der Seite „Zwischenbilanz“ unter **Standardansicht** den Eintrag **Parameter**.

1. Wählen Sie unter **EINZUBEZIEHENDE DATEN** das Menü **Finanzdimensionssatz** und dann **MA-BU-DEPT-CC** aus.

1. Wählen Sie **Salden berechnen** aus, um die in der Erfassung verwendeten Dimensionen anzuzeigen.

1. Schließen Sie die Seite.

## Übung 2: Kreditorenkonten erkunden

### Kreditor erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Kreditorenkonten** > **Kreditoren** > **Alle Kreditoren** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um einen Kreditor zu erstellen.

1. Erstellen Sie auf der Seite „Neuer Datensatz“ einen neuen Kreditor mit den folgenden Daten:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Kreditorenkonto| V00001|
    | Name| ABC Training, Inc|
    | Gruppe| 20|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie das Inforegister **Adressen** und dann **+Hinzufügen** aus.

1. Geben Sie im Bereich „Neue Adresse“ die folgenden Aktualisierungen ein, und klicken Sie auf **OK**:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Name oder Beschreibung| Firmenhauptsitz|
    | Postleitzahl| 98052|
    | Straße| 123 Front Street|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie das Inforegister **Zahlung** aus.

1. Wählen Sie das Menü **Zahlungsmethode** und dann **SCHECK** aus.

1. Wählen Sie das Inforegister **Steuererklärung (US 1099)** aus, und geben Sie die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Steuererklärung (US 1099)| Ja|
    | Bundessteuernummer| 82-1234567|
    | Steuerkennungstyp| Arbeitgeberkennnummer|
    | Steuerformularfeld (US 1099)| MISC-03|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Schließen Sie das Formular.

### Bestellung für den neuen Kreditoren erstellen

1. Wählen Sie auf der Seite „V00001 : ABC Training, Inc“ im Aktionsbereich **Beschaffung** aus.

1. Wählen Sie im Aktionsbereich auf der Registerkarte **NEU** die Option **Bestellung** aus.

1. Geben Sie auf der Seite „Bestellung“ unter **Bestellpositionen** die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Artikelnummer| S0001|
    | Menge| 2|

    >[!Hinweis] Sie müssen nach rechts scrollen, um die Spalte **Menge** anzuzeigen.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich **Einkauf** und dann auf der Registerkarte **AKTIONEN** die Option **Bestätigen** aus.

### Kreditorenrechnung für Bestellung aufzeichnen

1. Wählen Sie im Aktionsbereich **Rechnung** aus.

1. Wählen Sie auf der Registerkarte **GENERIEREN** die Option **Rechnung** aus.

1. Wählen Sie im Aktionsbereich **Standard von:** aus. **Menge im Produktzugang** aus.

1. Wählen Sie im Menü **Standardmenge für Positionen** die Option **Bestellte Menge** und dann **OK** aus.

1. Geben Sie auf der Seite „Kreditorenrechnung“ die folgenden Aktualisierungen ein:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Nummer| INV001|
    | Rechnungsbeschreibung| Initial Installation Service|
    | Rechnungsdatum| *Geben Sie das heutige Datum ein.*|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich **Status des Abgleichs aktualisieren** aus.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

### Kreditorenrechnung begleichen

1. Wählen Sie im Navigationsbereich **Module** > **Kreditorenkonten** > **Zahlungen** > **Kreditorenzahlungserfassung** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus.

1. Wählen Sie auf der Seite „Kreditorenzahlungserfassung“ in der ersten Zeile die Spalte **Name**, das Menü und dann **VendPay** aus.

1. Wählen Sie im Aktionsbereich **Positionen** aus, um die Zahlung zu buchen.

1. Geben Sie auf der Seite „Kreditorenzahlungen“ im Feld **Konto** die Nummer **V00001** ein.

1. Wählen Sie auf der Symbolleiste **Buchungen ausgleichen** aus.

1. Aktivieren Sie auf der Seite „Buchungen für ABC Training ausgleichen“ in der Spalte **Markieren** das Kontrollkästchen.

1. Wählen Sie in der rechten unteren Ecke **OK** aus.

1. Wählen Sie im Aktionsbereich **Zahlungen generieren** aus.

1. Geben Sie im Bereich **Zahlungen generieren** die folgenden Aktualisierungen ein, und wählen Sie dann **OK** aus:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Zahlungsmethode| CHECK|
    | Bankkonto| USMF OPER|

1. Überprüfen Sie die Informationen im Bereich **Zahlung per Scheck**, und wählen Sie dann **OK** aus.

    >[!ALERT] Es wird ein Fehler angezeigt: **Drucker mit Pfad nicht gefunden**. Sie können diese Fehlermeldung ignorieren. Im Lab ist kein Drucker installiert.

1. Scrollen Sie in der Spalte **Zahlungsstatus** nach rechts, und stellen Sie sicher, dass **Gesendet** angezeigt wird.

1. Wählen Sie im Aktionsbereich **Prüfen** > **Überprüfen** aus.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

## Übung 3: Debitorenkonten erkunden

### Kunden erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Debitorenkonten** > **Kunden** > **Alle Kunden** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um einen neuen Kunden zu erstellen.

1. Erstellen Sie im Bereich **Kunde erstellen** anhand der folgenden Daten einen Kunden, und klicken Sie auf **Speichern**:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Kundenkonto| US-901|
    | Name| Fabrikam Consulting Services|
    | Kundengruppe| 30|
    | Postleitzahl| 98052|
    | Straße| 123 Middle Street|

1. Wählen Sie auf der Seite „US-901 Fabrikam Consulting Services“ das Inforegister **Standardwerte für Zahlungen** aus.

1. Wählen Sie das Menü **Zahlungsmethode** und dann **SCHECK** aus.

1. Wählen Sie das Inforegister **Finanzdimensionen** aus.

1. Geben Sie im Feld **Unternehmenseinheit** die Nummer **004** ein.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

### Freitextrechnung für den neuen Kunden erstellen

1. Wählen Sie im Aktionsbereich **Rechnung** und auf der Registerkarte **NEU** die Option **Freitextrechnung** aus.

1. Legen Sie auf der Seite „US-901 Fabrikam Consulting Services“ unter der **Überschrift** **Freitextrechnung** das Datum für **RECHNUNG** auf das aktuelle Datum fest.

1. Nehmen Sie unter **Rechnungspositionen** die folgenden Änderungen vor:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Beschreibung| Consultant Service Training|
    | Hauptkonto| 401200|
    | Mehrwertsteuergruppe| WA|
    | Betrag| 1500,00|

1. Wählen Sie im Aktionsbereich **Mehrwertsteuer** aus.

1. Überprüfen Sie auf der Seite „Mehrwertsteuerbuchungen“ den Datensatz, und wählen Sie dann **OK** aus.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

1. **Legen Sie im Bereich zum Senden einer kostenlosen Testrechnung** unter **DRUCKOPTIONEN** die Option **Rechnung drucken** auf **Ja** fest, und wählen Sie dann **OK** aus.

1. Klicken Sie im Bereich **Druckzieleinstellungen** auf **OK**, um die Rechnung auf dem Bildschirm zu drucken.

1. Prüfen Sie die Rechnung, und schließen Sie sie danach.

1. Schließen Sie das Formular.

### Debitoren-Fälligkeitsbericht zum Überprüfen ausführen

1. Wählen Sie im Navigationsbereich **Module** > **Kredit und Inkasso** > **Abfragen und Berichte** > **Debitoren** > **Kundenfälligkeitsbericht** aus.

1. Geben Sie im Bereich **Kundenfälligkeitsbericht** die folgenden Aktualisierungen ein, und wählen Sie dann **OK** aus:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Fälligkeit per| Heutiges Datum|
    | Zahlungsfristdefinition| 30_60_90_180|
    | Details| Yrs|

1. Wählen Sie im Kundenfälligkeitsbericht das Symbol **Nächste Seite** (Abwärtspfeil) aus, und scrollen Sie dann zur letzten Seite.
    Überprüfen Sie die Rechnung, die für den US-901-Kunden erstellt wurde.

1. Schließen Sie das Formular.

### Kundenzahlung für Freitextrechnung anwenden

1. Wählen Sie im Navigationsbereich **Module** > **Debitorenkonten** > **Zahlungen** > **Kundenzahlungserfassung** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus.

1. Wählen Sie auf der Seite „Kundenzahlungserfassung“ in der Spalte **Name** das Menü und dann **CustPay** aus.

1. Wählen Sie im Aktionsbereich **Kundenzahlungen eingeben** aus.

1. Geben Sie im Feld **Kunde** den Wert **US-901** ein.  
    Warten Sie, bis die Daten geladen wurden, und aktivieren Sie in der Spalte **Markieren** dann das Kontrollkästchen.

1. Geben Sie über dem Raster im Feld **Betrag** den Betrag **1597,50** ein. Der im Feld **Restbetrag** angezeigte Betrag sollte sich automatisch von **1.597,50** in **0** ändern.  
    Sie müssen möglicherweise in einen leeren Bereich klicken, damit der Wert berechnet wird.

1. Geben Sie im Feld **Zahlungsreferenz** den Wert **Check# 123** ein.

1. Wählen Sie im Aktionsbereich **In Erfassung speichern** aus.

1. Schließen Sie das Formular.

1. Wählen Sie im Aktionsbereich **Positionen** aus.

1. Wählen Sie im Aktionsbereich **Prüfen** > **Überprüfen** aus.

1. Wählen Sie im Aktionsbereich **Buchen** aus.
