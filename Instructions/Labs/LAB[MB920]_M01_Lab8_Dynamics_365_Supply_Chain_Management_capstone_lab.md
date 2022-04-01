---
lab:
  title: 'Lab 8: Dynamics 365 Supply Chain Management – Capstone-Lab'
  module: 'Module 1: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: 05fc7cf7a81164c2cabf3637e307dcae2ca5d3f7
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137910036"
---
## <a name="lab-8---dynamics-365-supply-chain-management-capstone-lab"></a>Lab 8 – Dynamics 365 Supply Chain Management – Capstone-Lab

## <a name="objective"></a>Ziel

In diesem Lab erkunden Sie das Erstellen eines Produkts und die Pflege der Preisgestaltung. Darüber hinaus erfahren Sie mehr über wichtige Geschäftsprozesse bei Lieferketten, wie zum Beispiel die Bestandsverwaltung, Beschaffung und Sourcing.

## <a name="lab-setup"></a>Lab-Einrichtung

- **Geschätzte Dauer**: 45 Minuten 

## <a name="exercise-1-explore-product-management"></a>Übung 1: Produktverwaltung erkunden

### <a name="create-a-product"></a>Erstellen eines Produkts

Im Unternehmen Contoso Entertainment System USA (USMF) müssen Sie einen neuen Artikel für eine neue Gehäusekonfiguration eines Lautsprechers erstellen, die Sie bei einem Kreditor erwerben können.

1. Überprüfen Sie auf der Startseite oben rechts, dass das Unternehmen **USMF** ausgewählt ist.

1. Wenn nicht, wählen Sie das aktuell ausgewählte Unternehmen aus, und ändern Sie das Unternehmen dann in **USMF**.

1. Wählen Sie im Navigationsbereich **Module** > **Produktinformationsverwaltung** > **Produkte** > **Freigegebene Produkte** aus.

1. Wählen Sie auf der Detailseite für freigegebene Produkte im Aktionsbereich die Option **+ Neu** aus.

1. Stellen Sie im Bereich **Neues freigegebenes Produkt** im Menü **Produkttyp** sicher, dass **Artikel** ausgewählt ist.

1. Stellen Sie im Menü **Produktuntertyp** sicher, dass **Produkt** ausgewählt ist.

1. Wählen Sie das Menü **Rückverfolgungsgruppe** und dann **Keine** aus.

1. Geben Sie unter **IDENTIFIZIERUNG** im Feld **Produktnummer** die Nummer **GTL201** ein.

1. Geben Sie im Feld **Produktname** die Bezeichnung **Lautsprechergehäuse** ein.

1. Wählen Sie unter **MEHRWERTSTEUER** das Menü **Artikel-Mehrwertsteuergruppe** und dann **ALLE** aus.

1. Wählen Sie unter **BESTEUERUNG VON EINKÄUFEN** das Menü **Artikel-Mehrwertsteuergruppe** und dann **ALLE** aus.

1. Geben Sie unter **PREISE** im Feld **Einkaufspreis** den Wert **30,00** ein.

1. Geben Sie im Feld **Verkaufspreis** den Wert **30,00** ein.

1. Wählen Sie unter **REFERENZGRUPPEN** das Menü **Lagersteuerungsgruppe** und dann **FIFO (First-In-First-Out)** aus.

1. Wählen Sie das Menü **Artikelgruppe** und dann **CarAudio** aus.

1. Wählen Sie das Menü **Lagerdimensionsgruppe** und dann **SiteWH** aus.

1. Überprüfen Sie unter **MASSEINHEITEN**, dass die folgenden Werte eingestellt sind:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Bestandseinheit| jeder|
    | Bestelleinheit| jeder|
    | Verkaufseinheit| jeder|
    | Stücklisteneinheit| jeder|

1. Klicken Sie auf **OK**.

1. Wählen Sie im Aktionsbereich **Produkt** und dann unter **Verwalten** die Option **Prüfen** aus, um sicherzustellen, dass das Produkt finalisiert wurde.

1. Stellen Sie sicher, dass Ihnen das Informationsbanner angezeigt wird, das bestätigt, dass alle erforderlichen Feldwerte validiert wurden.

1. Schließen Sie alle Seiten, und kehren Sie zur Startseite zurück.

## <a name="exercise-2-explore-warehouse-management"></a>Übung 2: Lagerverwaltung erkunden

### <a name="create-a-warehouse"></a>Lager erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Bestandsverwaltung** > **Einrichtung** > **Bestandsaufschlüsselung** > **Lager** aus.

1. Wählen Sie auf der Seite „Lager“ im Aktionsbereich die Option **New** aus.

1. Geben Sie im Feld **Lager** den Wert **150** ein.

1. Geben Sie im Feld **Name** die Bezeichnung **Lager Außenstelle** ein.

1. Wählen Sie das Menü **Site** und dann **1 Heimlautsprecherproduktion** aus.

1. Wählen Sie das Inforegister **Lagerplatznamen** aus.

1. Die Optionen in diesem Abschnitt definieren das Standardformat für Standortnamen.

1. Legen Sie die Optionen **Gang einbeziehen** und **Regal einbeziehen** auf **Ja** fest.

1. Legen Sie die Option **Regal einbeziehen** auf **Ja** fest.

1. Geben Sie im Feld **Format** für das Regal **-##** ein.

1. Wählen Sie im Aktionsbereich **Lager** aus.

1. Wählen Sie unter **Verwalten** die Option **Lagerplatz-Assistent** aus.

1. Überprüfen Sie auf der Begrüßungsseite die Informationen, und wählen Sie dann in der unteren rechten Ecke **Weiter** aus.

1. Deaktivieren Sie die Kontrollkästchen **Eingangsrampen** und **Sammellagerplätze**.

1. Wählen Sie **Weiter** aus, und prüfen Sie die Informationen.

1. Fahren Sie mit jeder Seite fort, und wählen Sie dann nach Abschluss **Fertig** aus.

1. Schließen Sie die Seite, und kehren Sie zur Startseite zurück.

### <a name="create-a-trade-agreement-for-sales-price"></a>Handelsvereinbarung für Verkaufspreis erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Produktinformationsverwaltung** > **Produkte** > **Freigegebene Produkte** aus.

1. Suchen Sie auf der Detailseite „Freigegebene Produkte“ nach der Produktnummer **GTL201**.

1. Aktivieren Sie links neben **GTL201** das Kontrollkästchen zum **Auswählen bzw. Aufheben der Auswahl einer Zeile**.

1. Wählen Sie im Aktionsbereich **Verkaufen** und dann unter **HANDELSVEREINBARUNGEN** die Option **Handelsvereinbarungen erstellen** aus.

1. Wählen Sie im Aktionsbereich  **+Neu** aus.

1. Wählen Sie in der Spalte **Name** das Menü und dann **S_Price** aus.

1. Wählen Sie im Aktionsbereich **Positionen** aus.

1. Wählen Sie in den Erfassungspositionen auf der Seite „Handelsvereinbarung“ in der Spalte **Artikelrelation** das Menü und dann **GTL201** aus.

1. Dies ist die Artikelnummer des von Ihnen erstellten Produkts.

1. Wählen Sie in der Spalte **Lager** das Menü und dann **150** aus.

1. Unter Umständen müssen Sie nach rechts scrollen, damit die Spalte angezeigt wird.

1. Geben Sie in der Spalte **Betrag in Währung** den Wert **100,00** in das Feld ein.

1. Geben Sie im Detailbereich in das Feld **Von Datum** das erste Datum des aktuellen Jahres ein.

1. Wählen Sie im Aktionsbereich **Überprüfen** > **Alle Positionen überprüfen** aus.

1. Wählen Sie im Bereich **Preis-/Rabatterfassungsbuchung** die Option **OK** aus.

1. Überprüfen Sie, dass keine Fehler vorliegen.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

1. Wählen Sie im Bereich **Preis-/Rabatterfassungsbuchung** die Option **OK** aus.

1. Überprüfen Sie, ob der Vorgang abgeschlossen wurde.

1. Schließen Sie die Seite.

1. Wählen Sie auf der Detailseite für das freigegebene Produkt im Aktionsfenster unter **Verkaufen** > **HANDELSVEREINBARUNGEN** die Option **Handelsvereinbarungen anzeigen** aus.

1. Die Handelsvereinbarung sollte aufgeführt werden. Überprüfen Sie die Preisinformationen für die Position.

1. Schließen Sie die Seiten, und kehren Sie zur Startseite zurück.

## <a name="exercise-3-explore-production-management"></a>Übung 3: Produktionsverwaltung erkunden

### <a name="create-a-production-order-for-a-product"></a>Produktionsauftrag für ein Produkt erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Produktionssteuerung** > **Produktionsaufträge** > **Alle Produktionsaufträge** aus.

1. Wählen Sie im Aktionsbereich **Neuer Produktionsauftrag** aus.

1. Geben Sie im Bereich **Produktionsauftrag erstellen** unter **IDENTIFIZIERUNG** im Feld **Artikelnummer** den Wert **D0004** ein, und wählen Sie dann den identifizierten Artikel aus.

1. Wählen Sie unter **PRODUKTION** im Feld **Lieferung** ein Datum einen Monat nach dem heutigen Datum aus.

1. Das Lieferdatum gibt an, wann der Fertigungsauftrag enden soll, um pünktlich zu liefern. Dieses Datum kann im Planungsprozess verwendet werden. Beispielsweise können Sie die Bestellung ab dem Lieferdatum rückwärts planen.

1. Geben Sie im Feld **Menge** den Wert **30** ein.

1. Klicken Sie auf **Erstellen**.

1. Schließen Sie alle Seiten, und kehren Sie zur Startseite zurück.

## <a name="exercise-4-explore-inventory-management"></a>Übung 4: Bestandsverwaltung erkunden

### <a name="create-a-count-journal-with-the-product-for-the-created-warehouse"></a>Anzahlerfassung mit dem Produkt für das erstellte Lager erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Bestandsverwaltung** > **Journaleinträge** > **Artikelinventur > Inventur** aus.

1. Wählen Sie im Aktionsbereich  **+Neu** aus.

1. Wählen Sie im Bereich **Bestandserfassung erstellen** unter **Inventur von** für den Umschalter **Lager** die Einstellung **Ja**.

1. Klicken Sie auf **OK**.

1. Wählen Sie auf der Seite „Bestandsinventurerfassung“ im Inforegister **Erfassungskopfdetails** auf der Symbolleiste unter **Erfassungspositionen** die Option **+Neu** aus.

1. Wählen Sie in der Spalte **Artikelnummer** das Menü und dann **GTL201** aus.

1. Wählen Sie in der Spalte **Lager** das Menü und dann **150** aus.

1. Geben Sie in das Feld **Gezählt** den Wert **100,00** ein.

1. Hiermit wird die Anzahl der im Lager befindlichen Artikel dieses Produkts angegeben.

1. Wählen Sie im Aktionsbereich **Überprüfen** aus.

1. Wählen Sie im Bereich **Erfassung prüfen** die Option **OK** aus.

1. Wählen Sie im Aktionsbereich **Buchen** aus.

1. Wählen Sie im Bereich **Erfassung buchen** die Option **OK** aus.

1. Schließen Sie alle Seiten, und kehren Sie zur Startseite zurück.

### <a name="check-on-hand-inventory-for-the-product"></a>Verfügbaren Bestand des Produkt prüfen

1. Wählen Sie im Navigationsbereich **Module** > **Bestandsverwaltung** > **Abfragen und Berichte** > **Bestandsliste** aus.

1. Wählen Sie im Aktionsbereich **Dimensionen** aus.

1. Aktivieren Sie im Bereich der **Dimensionsanzeige** unter **LAGERDIMENSIONEN** die Kontrollkästchen **Site** und **Lager**, und wählen Sie dann **OK** aus.

1. Klicken Sie im Bereich **Filter** auf **Anwenden**.

1. Suchen Sie den verfügbaren Bestand für **GTL201**.

1. Schließen Sie alle Seiten, und kehren Sie zur Startseite zurück.

## <a name="exercise-5-explore-procurement-and-sourcing"></a>Übung 5: Beschaffung erkunden

### <a name="create-a-purchase-order-with-a-product"></a>Bestellung mit einem Produkt erstellen

1. Wählen Sie im Navigationsbereich **Module** > **Beschaffung** > **Bestellungen** > **Alle Bestellungen** aus.

1. Wählen Sie auf der Seite „Alle Bestellungen“ im Aktionsbereich die Option **+ Neu** aus.

1. Wählen Sie im Bereich **Bestellung anlegen** das Menü **Kreditorenkonto** und dann **US-101** aus.

1. Wenn Sie einen Kreditor auswählen, werden Details aus dem Kreditorendatensatz wie Adresse, Rechnungskonto, Lieferbedingungen und Lieferart als Standardwerte in den Auftragskopf kopiert. Sie können diese Werte jederzeit ändern.

1. Wählen Sie im Bereich **Allgemein** unter **LAGERDIMENSIONEN** das Menü **Site** und dann **1 Heimlautsprecherproduktion** aus.

1. Wählen Sie unter **DATEN** ein **Lieferdatum** aus, das eine Woche nach dem aktuellen Datum liegt.

1. Wählen Sie **Verwaltung** aus.

1. Wählen Sie das Menü **Auftraggeber** und dann **Lars Giusti** aus, um anzugeben, wer die Bestellung aufgibt.

1. Wählen Sie im Bereich **Bestellung anlegen** die Option **OK** aus.

1. Wählen Sie auf der Symbolleiste **Bestellposition** aus.

1. Wählen Sie unter **DISPLAY** **Dimensionen** aus.

1. Wählen Sie im Anzeigebereich **Dimensionen** unter **PRODUKTDIMENSIONEN** das Kontrollkästchen **Farbe** aus.

1. Klicken Sie auf **OK**.

1. Wählen Sie in der Spalte **Artikelnummer** das Menü und dann **T0005** aus.

1. Wählen Sie in der Spalte **Variantennummer** das Menü und dann eine der Farben aus.

1. Geben Sie im Feld **Menge** den Wert **15** ein.

1. Wählen Sie unter den **Bestellpositionen** unten auf der Seite das Inforegister **Positionsdetails** aus.

1. Diese Registerkarte ist möglicherweise bereits erweitert.

1. Wählen Sie die Registerkarte **Lieferung** aus, und übernehmen Sie das im Feld ausgewählte **Lieferdatum**, oder geben Sie ein künftiges Datum an.  
    Jeder Bestellposition kann eine eindeutige Auftragsposition zugewiesen werden. Das Datum wird vom Feld im Bestellkopf übernommen, Sie können dies jedoch ändern.

1. Notieren Sie sich die Bestellnummer. Sie benötigen sie später.

1. Wählen Sie im Aktionsbereich **Speichern** aus.

1. Schließen Sie die Seite „Bestellposition“.

1. Verwenden Sie auf der Seite „Alle Bestellungen“ die **Filterfunktion**, und suchen Sie Ihre neue Bestellung.

1. Wenn Sie fertig sind, schließen Sie die Seite „Alle Bestellungen“ und kehren Sie zur Startseite zurück.
