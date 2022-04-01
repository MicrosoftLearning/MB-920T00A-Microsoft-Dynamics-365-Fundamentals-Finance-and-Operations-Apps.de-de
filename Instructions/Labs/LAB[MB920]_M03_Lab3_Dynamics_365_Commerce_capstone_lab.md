---
lab:
  title: 'Lab 3: Dynamics 365 Commerce – Capstone-Lab'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: c498966dc4b2bba78b4e0d27077c4b346666323f
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909416"
---
## <a name="lab-3---dynamics-365-commerce-capstone-lab"></a>Lab 3 – Dynamics 365 Commerce – Capstone-Lab

## <a name="objective"></a>Ziel

In diesem Lab erkunden Sie die Grundlagen der Einrichtung eines Commerce-Headquarters. Zu den Kernfunktionen zählen die Einrichtung eines Retail Channels, die Sortimentserstellung und die Konfiguration von Einzelhandelsrabatten.

## <a name="lab-setup"></a>Lab-Einrichtung

   - **Geschätzte Dauer**: 30 Minuten 

## <a name="instructions"></a>Anweisungen

## <a name="exercise-1-explore-commerce-headquarters"></a>Übung 1: Commerce-Headquarter erkunden

### <a name="create-a-new-store"></a>Neuen Shop erstellen

1. Überprüfen Sie auf der Landing Page oben rechts, dass das Unternehmen **USRT** ausgewählt ist.

1. Wenn nicht, wählen Sie das aktuell ausgewählte Unternehmen aus, und ändern Sie das Unternehmen dann in **USRT**.

1. Wählen Sie im Navigationsbereich **Module** > **Einzelhandel und Handel** > **Kanäle** > **Shops** > **Alle Shops** aus.

1. Wählen Sie im Aktionsbereich  **+Neu** aus, um einen neuen Shop zu erstellen.

1. Verwenden Sie im Fenster „Neuer Datensatz“ die Einstellungen in der folgenden Tabelle, um die Werte zu aktualisieren:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Name| Seattle Flagship Store|
    | Shopnummer| 000098|
    | Warehouse| Seattle|
    | Versandlagerort| Seattle|
    | Zeitzone des Shops| (GMT-08:00) Pacific Time|
    | Funktionsprofil| FN001|
    | Bestandsuche| Ja|
    | Kanalprofil| Standard|
    | Offlineprofil| Standard|
    | Mehrwertsteuergruppe| WA|
    | Zielbasierte Steuer verwenden| Ja|
    | Kundenadressbuch| RetailCust|
    | Mitarbeiteradressbuch| Seattle|
    | Standardkunde| 3002|

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie das Inforegister **Auszug/Abschluss** aus, und geben Sie die folgenden Informationen ein:

    | Einstellung| Wert|
    | :--- | :--- |
    | Auszugsbetragsberechnung| Letzter|
    | Maximale Differenz > Buchung| 100,00|

1. Wählen Sie **Finanzdimensionen** aus, und geben Sie die folgenden Informationen ein:

    | Einstellung| Wert|
    | :--- | :--- |
    | BusinessUnit| 004|
    | Einzelhandelskanal| 000210|

1. Wählen Sie das Inforegister **Bildschirmlayout** aus.

1. Geben Sie im Feld **Bildschirmlayoutkennung** den Wert   **A2CP16:9C** ein.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich  **Einrichtung** und dann auf der Registerkarte **KOPIEREN** die Option **Alle kopieren** aus.

1. Wählen Sie im Bereich **Alle kopieren** das Menü **Von Shop** und dann **ANNAPOL** aus.

1. Wählen Sie bei Bedarf das Menü **Bis Shop** und dann den Wert **00098** aus.

1. Wählen Sie **OK** aus.

1. Stellen Sie sicher, dass eine Erfolgsmeldung angezeigt wird, und schließen Sie dann die Seite.

### <a name="add-a-group-of-products-to-an-assortment-and-publish"></a>Gruppe von Produkten zu einem Sortiment hinzufügen und veröffentlichen

1. Wählen Sie im Navigationsbereich   **Module** > **Organisationsverwaltung** > **Organisationen** > **Organisationshierarchien** aus.

1. Wählen Sie in der Navigationsliste die Option für **Einzelhandelsgeschäfte nach Region** aus.

1. Wählen Sie im Aktionsbereich  **Anzeigen** aus.

1. Wählen Sie auf der Seite „Hierarchie-Designer“ im Aktionsbereich die Option   **Bearbeiten** aus.

1. Wählen Sie auf der Kachel **West** das Symbol mit den Auslassungszeichen ( **...** ) aus.

1. Wählen Sie auf der Seite „Hierarchie-Designer“ die Option   **Einfügen** > **Einzelhandelskanal** aus.

1. Wählen Sie im Fenster **Einzelhandelskanal** die Option **Seattle Flagship Store** und dann **OK** aus.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann **Schließen** aus.

1. Wählen Sie im Aktionsbereich  **Veröffentlichen** aus.

1. Wählen Sie im Bereich **Änderungen veröffentlichen** im Feld **Gültigkeitsdatum** den ersten Tag des aktuellen Monats aus.

1. Geben Sie im Feld **Änderungen beschreiben** den Text   **Seattle Flagship Store hinzugefügt**  ein, und wählen Sie  **Veröffentlichen** aus.

1. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann **Schließen** aus.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann **Schließen** aus.

1. Schließen Sie die Seite.

1. Wählen Sie im Navigationsbereich  **Module** > **Einzelhandel und Handel** > **Kataloge und Sortimente** > **Sortimente** aus.

1. Wählen Sie auf der Seite „Sortimente“   **AW-Outlet** aus.

1. Wählen Sie im Aktionsbereich  **Bearbeiten** aus.

1. Wählen Sie im Dialogfeld die Option  **Ja**  aus, um die Auswahl zu bestätigen.

1. Wählen Sie auf der Seite „AW-Outlet“ das Inforegister **Commerce Channel**.

1. Wählen Sie auf der Symbolleiste  **+Position hinzufügen** aus.

1. Wählen Sie im Bereich **Organisationsknoten auswählen** das Menü **Organisationshierarchie** und dann die Option für  **Einzelhandelsgeschäfte nach Region** aus.

1. Wählen Sie unter **VERFÜGBARE ORGANISATIONSKNOTEN** die Option  **Seattle Flagship Store**  und dann das Nach-rechts-Pfeilsymbol **Hinzufügen** aus, um den Store zu **AUSGEWÄHLTE ORGANISATIONSKNOTEN** hinzuzufügen.

1. Wählen Sie **OK** aus.

1. Wählen Sie im Aktionsbereich  **Veröffentlichen** aus.

1. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann  **Ja** aus.

1. Wählen Sie im Aktionsbereich  **Bearbeiten** aus.

1. Wählen Sie im **Bestätigungsdialogfeld** die Option  **Ja** aus.

1. Wählen Sie auf der Seite „AW-Outlet“ die Registerkarte **Produkte** aus.

1. Wählen Sie auf der Seite „AW-Outlet“ die Option **+Position hinzufügen** aus.

1. Wählen Sie im Menü **Kategorie** die Option  **Team Sports** (Mannschaftssport) und dann  **OK** aus.

1. Wählen Sie im Aktionsbereich  **Veröffentlichen** aus.  

### <a name="run-the-retail-scheduler-job-for-products"></a>Einzelhandels-Scheduler-Auftrag für Produkte ausführen

1. Wählen Sie im Navigationsbereich  **Module** > **Einzelhandel und Handel** > **Einzelhandel und Handel IT** > **Vertriebsplan** aus.

1. Wählen Sie in der Navigationsliste  **1040 (Produkte)** aus.

1. Wählen Sie im Aktionsbereich  **Jetzt ausführen** aus.

1. Überprüfen Sie im Bereich **Inkrementelle Synchronisierung mit Zeitplan "1040"** die Informationen, und wählen Sie dann  **OK** aus.

### <a name="create-a-new-product-discount"></a>Neuen Produktrabatt erstellen

1. Wählen Sie im Navigationsbereich  **Module** > **Einzelhandel und Handel** > **Preise und Rabatte** > **Alle Rabatte** aus.

1. Wählen Sie im Aktionsbereich  **Neu** > **Rabatt** aus.

1. Geben Sie auf der Seite „Rabatte“ im Feld **Name** den Namen  **Geschäftseröffnung** ein.

1. Geben Sie im Inforegister **Details** im Feld **Beschreibung** den Text  **Geschäftseröffnung 20 % Rabatt** ein.

1. Geben Sie im Inforegister **Preis/Rabatt** im Feld **Rabattprozentsatz** den Wert  **20,00** ein.

1. Geben Sie im Inforegister **Prüfungszeitraum** im Feld **Gültigkeitsdatum** ein Datum aus dem vorherigen Monat ein.

1. Geben Sie im Feld **Ablaufdatum** ein Datum ein, das eine Woche nach dem aktuellen Datum liegt.

1. Wählen Sie im Inforegister **Positionen** auf der Symbolleiste die Option **+ Hinzufügen**.

1. Wählen Sie in der Spalte **Kategorie** das Menü und dann **Team Sports** (Mannschaftssport) aus, und wählen Sie dann **OK** aus.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Aktionsbereich  **Preisgruppen** aus.

1. Wählen Sie auf der Seite „Preisgruppen“ das Menü **Preisgruppen** und dann  **West** aus.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Wählen Sie im Navigationsbereich  **Module** > **Einzelhandel und Handel** > **Preise und Rabatte** > **Alle Rabatte** aus.

1. Wählen Sie in der Navigationsliste  **ST100101** aus.

1. Wählen Sie im Inforegister **Allgemein** das Menü **Status** und dann  **Aktiviert** aus.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Schließen Sie das Formular.

1. Wählen Sie im Navigationsbereich  **Module** > **Einzelhandel und Handel** > **Einzelhandel und Handel IT** > **Vertriebsplan** aus.

1. Wählen Sie in der Navigationsliste  **1020 (Produkte)** aus.

1. Wählen Sie im Aktionsbereich  **Jetzt ausführen** aus.

1. Überprüfen Sie im Bereich **Inkrementelle Synchronisierung mit Zeitplan "1020"** die Informationen, und wählen Sie dann  **OK** aus.
