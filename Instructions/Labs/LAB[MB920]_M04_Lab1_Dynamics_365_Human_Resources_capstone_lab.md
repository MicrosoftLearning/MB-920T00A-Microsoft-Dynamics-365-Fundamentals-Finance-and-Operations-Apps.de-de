---
lab:
    title: 'Lab 1: Dynamics 365 Human Resources – Capstone-Lab'
    module: 'Modul 4: Grundlagen von Microsoft Dynamics 365 Human Resources erlernen'
---

## Lab 1 – Dynamics 365 Human Resources – Capstone-Lab

## Ziel

In diesem Lab erkunden Sie das Onboardingverfahren für einen neuen Mitarbeiter, darunter das Erstellen eines Mitarbeiterdatensatzes. Sie lernen außerdem das Leistungsbeurteilungsverfahren kennen, das die Einrichtung von Zielen und die Leistungsbewertung umfasst. Zusätzlich verwenden Sie Self-Service-Funktionen zum Übermitteln einer Spesenabrechnung.

## Lab-Einrichtung

- **Geschätzte Dauer**: 20 Minuten 

## Übung 1: Personalwesen erkunden

### Datensatz für eine Neueinstellung erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Personalwesen** > **Positionen** > **Positionen** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um eine neue Position zu erstellen.

1. Wählen Sie im Dialogfeld **Neue Position erstellen** das Menü **Stelle** und dann **Shopleiter** aus.

1. Wählen Sie **Position erstellen** aus.

1. Wählen Sie im Navigationsbereich **Module** > **Arbeitskräfte** > **Mitarbeiter** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um einen neuen Mitarbeiter zu erstellen.

1. Geben Sie im Bereich **Neue Arbeitskraft einstellen** die folgenden Informationen ein, wählen Sie dann **Einstellen**, und geben Sie Details ein.

    | **Einstellung** | **Wert** |
    | :--- | :---- |
    | Vorname | Bill |
    | Nachname | Smith |
    | Datum des Beschäftigungsbeginns | Wählen Sie das aktuelle Datum aus.|

### Ziel für die Neueinstellung erstellen

1. Wählen Sie im Aktionsbereich **Arbeitskraft** aus.

1. Wählen Sie auf der Registerkarte **ENTWICKLUNG** die Option **Ziele** aus.

1. Sie müssen möglicherweise nach rechts scrollen, um die Registerkarte zu sehen.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um ein neues Ziel zu erstellen.

1. Geben Sie im Inforegister **Allgemein** die folgenden Informationen ein:

    | **Einstellung** | **Wert** |
    | :--- | :---- |
    | Name | Verkaufsziel für Quartal |
    | Übersicht | Das Team des Shops unterstützen, das Verkaufsziel für das Quartal zu erreichen. |
    | Zielkategorie | Vertrieb |
    | Startdatum | Wählen Sie ein Datum aus, das eine Woche nach dem aktuellen Datum liegt. |
    | Enddatum | Wählen Sie ein Datum aus, das zwei Wochen nach dem Startdatum liegt. |

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Schließen Sie die Seite mit dem Verkaufsziel für das Quartal.

1. Schließen Sie die Seite mit den Zielen | für Bill.

### Der Neueinstellung Schulung zuweisen

1. Wählen Sie auf Bills Mitarbeiterseite im Aktionsbereich die Option **Arbeitskraft** aus.

1. Wählen Sie auf der Registerkarte **KOMPETENZEN** die Option **Kurse**.

1. Sie müssen möglicherweise nach rechts scrollen, um die Registerkarte zu sehen.

1. Wählen Sie im Aktionsbereich **+Neu** aus, um einen neuen Kurs zu erstellen.

1. Wählen Sie in der Rasteransicht in der Spalte **Kurskennung** das Menü aus, und wählen Sie dann **00004** aus.

1. Wählen Sie im Dialogfeld **Kursdaten übertragen** die Option **Ja**.

1. Wählen Sie in der Spalte **Startdatum** das Kalendersymbol und dann das aktuelle Datum aus.

1. Wählen Sie in der Spalte **Enddatum** das Kalendersymbol aus, und wählen Sie dann ein Datum aus, das zwei Wochen nach dem aktuellen Datum liegt.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Schließen Sie die Seite mit den Kursen | für Bill.

### Spesenabrechnung erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Personalwesen** > **Arbeitsbereiche** > **Mitarbeiter-Self-Service**.

1. Wählen Sie im **Abschnitt mit Ihren Karriereinformationen** unter dem Titel **Ausgaben** die Option **Neuer Bericht** aus.

1. Wählen Sie im Bereich **Neue Spesenabrechnung** im Menü **Zweck** die Option **Schulung** aus, und wählen Sie dann **OK** aus.

1. Geben Sie im Raster **Ausgaben** in der neuen Ausgabenzeile die folgenden Informationen ein:

    | **Einstellung** | **Wert** |
    | :--- | :---- |
    | Transaktionsdatum | Wählen Sie das aktuelle Datum aus. |
    | Spesenkategorie | Autovermietung |
    | Einzelhändler | LitWare Travel |
    | Buchungsbetrag | 150,00 |

1. Open Sie auf dem virtuellen Computer des Labs den **Editor**.

1. Geben Sie im Editor den Text **Beleg für LitWare Travel** ein.

1. Speichern Sie die Datei als **Beleg.txt** auf dem Desktop, und schließen Sie dann den Editor.

1. Sie verwenden diese Datei später, um einen Belegt zu einer Spesenabrechnung hinzuzufügen.

1. Kehren Sie zur Registerkarte von Microsoft Dynamics 365 Finance & Operations zurück.

1. Wählen Sie im Aktionsbereich **An Kopfzeilen angehängte Belege** aus.

1. Wählen Sie im Bereich **An Kopfzeilen angehängte Belege** die Option **Neuen Beleg hochladen und anfügen** aus.

1. Wählen Sie **Durchsuchen** aus.

1. Wählen Sie die Datei **Receipt.txt** aus, die Sie zuvor erstellt haben, und wählen Sie **Öffnen** aus.

1. Geben Sie im Feld **Notizen** den Eintrag **Autovermietung** ein, und wählen Sie dann **Hochladen** aus.

1. Aktivieren Sie das Kontrollkästchen **Beleg**, und wählen Sie dann **Positionen auswählen** aus.

1. Aktivieren Sie im Bereich **Belege an Positionen anfügen** das Kontrollkästchen **150,00 LitWare Travel**, und wählen Sie dann **OK** aus.

1. Wählen Sie **Schließen** aus.

1. Wählen Sie im Aktionsbereich **Workflow** und dann **Absenden** aus.

1. Geben Sie im Bereich **Spesenabrechnung – USMF – Absenden** im Feld **Kommentare** den Text **Bitte meine Spesenabrechnung prüfen** ein.

1. Wählen Sie **Absenden** aus.

### Leistungserfassung aufzeichnen

1. Wählen Sie im Navigationsbereich **Module** > **Personalwesen** > **Leistung** > **Leistungserfassung** aus.

1. Wählen Sie im Aktionsbereich **+Neu** aus.

1. Geben Sie auf der Seite **Neue Erfassung** die folgenden Informationen ein:


    | **Einstellung** | **Wert** |
    | :--- | :---- |
    | Titel | Absolvierte Schulung |
    | Beschreibung | Geschäftsschulung für Shopleiter absolviert |
    | Person | Bill Smith |
    | Abschlussdatum | Heutiges Datum |

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich die Option zum **Hinzufügen zu einem Ziel** aus.

1. Wählen Sie **Verkaufsziel für Quartal** und dann **OK** aus.

1. Schließen Sie die Seite mit der Leistungserfassung.
