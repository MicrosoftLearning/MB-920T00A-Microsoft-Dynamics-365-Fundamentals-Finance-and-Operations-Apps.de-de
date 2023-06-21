---
lab:
  title: "Lab\_2: Excel-Integration"
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
---

# Modul 1: Erkunden der Kernfunktionen der Finanz- und Betriebs-Apps von Microsoft Dynamics 365

## Lab 2: Excel-Integration

## Ziel

In diesem Lab erfahren Sie, wie Sie Finanz- und Betriebsdaten mithilfe der Office-Add-In-App des Dynamics-Datenconnectors nach Excel kopieren. Außerdem erfahren Sie, wie Sie mit der gleichen App Daten in Dynamics 365 Finance and Operations einfügen. 

## Lab-Einrichtung

   - **Geschätzte Dauer**: 5 Minuten

## Anweisungen

Nachdem Sie sich mit den Finanz- und Betriebs-Apps vertraut gemacht haben, nehmen Sie sich etwas Zeit, um das Szenario zur Excel-Integration zu erkunden. 

1.  Überprüfen Sie auf der **Finance and Operations**-Startseite oben rechts, ob Sie mit dem **USMF**-Unternehmen arbeiten. 

2.  Navigieren Sie zu **Beschaffung** > **Einrichten** > **Kreditoren** > **Kreditorengruppen**.

3.  Wählen Sie im Aktionsbereich **In Microsoft Office öffnen** und unter **In Excel öffnen** die Option **Kreditorengruppen (usmf)** aus.

4.  Wählen Sie im Bereich **In Excel öffnen** die Option **Herunterladen** aus. 

5.  Die Excel-Vorlagendatei wird heruntergeladen und gespeichert. **Öffnen** Sie die heruntergeladene Excel-Vorlagendatei, überspringen Sie bei Bedarf andere Standardsicherheitsaufforderungen, oder lassen Sie sie zu, schließen Sie die Aktivierung, und wählen Sie **Bearbeitung aktivieren** aus. Wählen Sie **Diesem Add-In vertrauen** aus, und melden Sie sich dann an (mit denselben Anmeldeinformationen, sofern Sie gefragt werden). 

    Nach der Anmeldung aktualisiert die Datenconnector-App die vorhandenen Daten aus der **Kreditorengruppentabelle** und zeigt sie in der Excel-Kalkulationstabelle an. 

6.  Geben Sie zum Erstellen eines neuen Datensatzes `100` im Feld **Kreditorengruppe**, `Insurance vendor` im Feld **Beschreibung** und `Net10` im Feld **Zahlungsbedingungen** ein. 

7.  Wählen Sie im Aufgabenbereich Microsoft Dynamics-Datenconnector die Schaltfläche **Veröffentlichen** aus. 

8.  Aktualisieren Sie die Liste der **Kreditorengruppen** in Dynamics 365 Finance and Operations, um sicherzustellen, dass der neue Datensatz erfolgreich hinzugefügt wurde. 

