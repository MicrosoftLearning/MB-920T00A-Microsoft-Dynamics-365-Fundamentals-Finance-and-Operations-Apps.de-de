---
demo:
  title: "Demo\_2: Rechnung erstellen"
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-2---create-an-invoice"></a>Demo 2 – Rechnung erstellen

1. Navigieren Sie zum Arbeitsbereich **Projektverwaltung**.  
    In this demo, we'll go over the process of invoicing a single project within project operations. Although it's possible to perform mass invoicing, for demonstration purposes we will focus on just a single time and material project. We'll also see the posting results and financial insights within the project statement. Let's start with project invoicing. 

1. In the top-right company picker, verify the legal entity you are connected to is<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to<bpt id="p1"> **</bpt>USSI<ept id="p1">**</ept>.  
    From the<bpt id="p1"> **</bpt>Project management<ept id="p1">**</ept> workspace, we can see all the active projects. We can search for projects using the filter, or in this example, we will select a known Project ID. 

1. Wählen Sie in der Tabelle **Aktive Projekte** in der Spalte **Projektkennung** das Projekt **00000093 Contoso Consulting** aus.  

1. Öffnen Sie als Nächstes die Seite **Projektrechnungsvorschläge**, um alle bisher bearbeiteten Rechnungen für Contoso Consulting anzuzeigen. 

1. Wählen Sie im Aktionsbereich auf der Registerkarte **FAKTURIEREN** die Option **Projektrechnungsvorschläge** aus. 

1. Wählen Sie auf der Seite **Projektrechnungsvorschläge** auf der Navigationsleiste die Option **Neu** und dann **Rechnungsvorschlag** aus.  
    Dies ist eine einfache Aufwandsrechnung, sodass wir die Option für Rechnungsvorschlag aus Abrechnungsregel nicht auswählen müssen. 

    ![Screenshot der Seite „Projektrechnungsvorschläge“ mit hervorgehobenem neuen Rechnungsvorschlag](./media/projops_invoice_1_new_invoice_proposal.png)

1. Zeigen Sie im Bereich **Rechnungsvorschlag** erstellen auf die Felder unter  **Buchungen auswählen**.  
    From here, we can select things such as the invoicing method, the invoice date, the funding source, and the project. We can also choose to include sub projects, as well as incorporate transaction types, the start and end dates for transactions, and any financial dimensions we need. 

    ![Screenshot des Bereichs „Rechnungsvorschlag erstellen“, in dem der Abschnitt „Buchungen auswählen“ hervorgehoben ist](./media/projops_invoice_2_select_transactions.png)

1. Wählen Sie im Dropdownmenü **Projekt** die Option  **00000093 Contoso Consulting** aus. 

1. Stellen Sie für dieses Beispiel sicher, dass **Rechnungsdatum** auf **01.02.21**, das **Startdatum** auf  **01.02.21** und das Enddatum auf das heutige Datum festgelegt ist.  
    Sobald die Auswahl getroffen ist, wählen Sie die Schaltfläche „Suchen“ aus, um die Buchungen zu finden, die diesen Parametern entsprechen.

1. Wählen Sie **Suchen** aus.  
    In dieser Demo werden wir den Prozess der Rechnungsstellung für ein einzelnes Projekt innerhalb von Project Operations durchgehen.

1. Wählen Sie unter der Registerkarte **Projektbuchungen** die Option **Alle auswählen** aus.

1. Wählen Sie **OK** aus. 

1. Zeigen Sie auf der Seite **Rechnungsvorschlag** auf die Spalte **Rechnungspositionsbetrag**.  
    Hier können wir den Rechnungsbetrag und die Zusammenfassung sowie die Stundenbuchungen und Ausgaben sehen.

    ![Screenshot der Seite „Rechnungsvorschlag“ mit hervorgehobener Spalte für den Rechnungspositionsbetrag](./media/projops_invoice_3_invoice_line_amount_column.png)

1. Zeigen Sie auf die Registerkarte **Stunde**. 

1. Zeigen Sie auf die Registerkarte **Ausgaben**.  
    Sie können auch wechseln und die Ausgabenbuchung betrachten.  
Als nächstes überprüfen wir die Schaltfläche „Summen“, um zu sehen, wie die Rechnung sowohl aus der Kosten- als auch aus der Umsatzerlösperspektive aussehen wird.

1. Wählen Sie auf der Navigationsleiste die Option **Summen** aus.

1. Zeigen Sie auf der Seite **Summen** auf die Spalte **HAUPTBUCH**, die Spalte **DEBITOR** und die Spalte **Positionsrabatt**.  
    Auf dem Bildschirm „Summen“ können wir sehen, wie sich die Rechnung auf das Hauptbuch auswirkt. Zudem werden alle Kundeninformationen wie Kreditlimits, Rabatte, Mehrwertsteuern und die Nettoauswirkungen der Rechnung angezeigt. 

1. Wählen Sie auf der rechten Seite des Bildschirms das **X** aus, um die Seite zu schließen.  
    Obwohl es möglich ist, eine Massenrechnungsstellung durchzuführen, werden wir uns zu Demonstrationszwecken auf ein einzelnes Aufwandsprojekt konzentrieren. 

1. Wählen Sie auf der Seite **Rechnungsvorschlag** auf der Navigationsleiste die Option **Seitenansicht** aus. 

1. Wählen Sie im Dialogfeld die Option **Seitenansicht** aus.  
    Hier sehen Sie ein Beispiel für die Seitenansicht einer Proforma-Rechnung. 

1. Wählen Sie das**X** aus, um die Seite zu schließen.  
    Sobald wir alle Informationen überprüft haben und mit der Seitenansicht der Rechnung zufrieden sind, können wir den Rechnungsvorschlag buchen.

1. Wählen Sie auf der Navigationsleiste die Option **Buchen** aus.

1. Wählen Sie die Registerkarte **Parameter** aus.

1. Legen Sie unter **PARAMETER** die Option **Buchung** auf **Ja** fest.

1. Legen Sie unter **DRUCKOPTIONEN** die Option **Rechnung drucken** auf **Ja** fest.

1. Wählen Sie **OK** aus.

1. Zeigen Sie auf der Seite **Rechnung** auf die **Rechnungsnummer**.  
    Jetzt verfügen wir über eine Rechnungsnummer, die generiert wurde.  
    Nachdem die Rechnung gebucht wurde, können wir die Informationen in der Rechnungserfassung überprüfen und die Detailinformationen der Sachkontobuchungen anzeigen.

1. Navigieren Sie zum Arbeitsbereich **Projektverwaltung**.

1. Wählen Sie in der Tabelle **Aktive Projekte** das Projekt  **00000093** **Contoso Consulting** aus.

1. Wählen Sie im Aktionsbereich auf der Registerkarte **FAKTURIEREN** die Option **Rechnungserfassungen** aus.

1. Wählen Sie auf der Seite **Rechnungserfassung** auf der Aktionsleiste die Option **Beleg** aus.

1. Zeigen Sie auf der Seite **Belegbuchungen** auf die Spalte **Sachkonto**.  
    Wir werden auch die Buchungsergebnisse und Finanzeinblicke innerhalb der Projektaufstellung sehen.

1. Navigieren Sie zum Arbeitsbereich **Projektverwaltung**. 

1. Wählen Sie in der Tabelle **Aktive Projekte** das Projekt  **00000093 Contoso Consulting** aus.

1. Wählen Sie auf der Seite **Contoso Consulting** auf der Navigationsleiste die Option **Steuerung** aus.  
    Von hier aus können wir alle Projektdetails sehen.  
    Als nächstes betrachten wir die Projektfinanzen einer Projektaufstellung.

1. Wählen Sie **Projektaufstellungen** aus.

1. Zeigen Sie auf der Seite **Projektaufstellungen** auf den Abschnitt **PROJEKTDATUM**.  
Sie können eine Aufstellung für einen beliebigen Datumsbereich erstellen.

1. Wählen Sie das Feld **Startdatum** aus, und geben Sie **01.02.2021** ein.
1. 
1. Wählen Sie das Feld **Enddatum** aus, und geben Sie das heutige Datum ein.

1. Wenn Sie fertig sind, wählen Sie **Berechnen** aus.

    ![Screenshot der Seite „Projektaufstellungen“ mit hervorgehobener Option „Berechnen“](./media/projops_invoice_4_calculate.png)

1. Zeigen Sie auf **Buchungen**.  
    Lassen Sie uns mit der Projektrechnung beginnen.
