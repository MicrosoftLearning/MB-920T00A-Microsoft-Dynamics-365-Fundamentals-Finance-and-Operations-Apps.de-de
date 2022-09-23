---
demo:
  title: "Demo\_3: Projektkosten erkunden"
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
---

## <a name="demo-3---explore-project-costs"></a>Demo 3 – Projektkosten erkunden

In this demo, we will walk through the creation of a time and expense entry that will be charged to the Contoso Consulting project. We'll explore the entries in formats optimized for web and mobile presentation, and we'll see how a workflow is used to manage the approval process.

1. Wählen Sie in **Dynamics 365 for Finance and Operations** im Navigationsbereich die Option **Module > Projektverwaltung und -verrechnung > Arbeitszeitnachweise > Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)** aus.  
    Obwohl ich mich jetzt noch nicht auf einem Mobilgerät befinde, werden Sie die Formulare als für Mobilgeräte geeignet erkennen, nachdem wir die Option **Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)** ausgewählt haben.

    ![Screenshot des Menüs „Projektverwaltung und -verrechnung“, in dem die Option „Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)“ hervorgehoben ist](./media/projops_costs_1_select_my_timesheets.png)  

    Diese Optimierung ist ein wichtiges Unterscheidungsmerkmal für Microsoft-Geschäftsanwendungen und trägt dazu bei, dass es eine minimale Lernkurve zwischen der Verwendung im Web und auf Mobilgeräten gibt.

1. In the top right company picker, verify the legal entity you are connecting to is <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>. If it's not, change the legal entity to <bpt id="p1">**</bpt>USSI<ept id="p1">**</ept>.

1. Wählen Sie auf der Seite **Meine Arbeitszeitnachweise** die Option **Neu** aus.  
    Jetzt erstellen wir einen neuen Arbeitszeitnachweis, der auf den konfigurierten Einstellungen basiert.

1. Zeigen Sie im Bereich **Neuer Arbeitszeitnachweis** auf das Feld **Datum**.  
    Das eingegebene Datum bestimmt den Zeitraum für den Arbeitszeitnachweis.

1. Zeigen Sie auf **Aus Favoriten erstellen**.  
    Wenn Sie Favoriten gespeichert haben, können Sie auswählen, diese für die Erstellung zu verwenden, um Zeit zu sparen.

1. Wählen Sie **OK** aus, wenn Sie fertig sind.

1. Wählen Sie auf der Seite **Meine Arbeitsnachweisdetails** das Symbol **Neu +** aus.

1. Zeigen Sie im Bereich **Neue Zeile im Arbeitszeitnachweis** auf das Feld **Juristische Person**.  
    The new timesheet line will be opened, with details such as the customer, the project, the category, the line properties, and tax parameters. You can also select a different legal entity if the time entry is on behalf of another company within your organization.

1. Wählen Sie das Menü **Projektkennung** aus.

1. Wählen Sie eines der verfügbaren Projekte aus, z. B. das Projekt **Contoso Consulting**.

1. Wählen Sie **OK** aus, wenn Sie fertig sind.  
    Der für Mobilgeräte optimierte Bildschirm für die Zeiterfassung wird geöffnet und Sie können beginnen, Ihre Stunden pro Tag für das Projekt und die Kategorie, in diesem Fall **Service**, zu buchen.

1. Geben Sie auf der Seite **Zeiterfassung** im Feld **Mon** die Zahl **8** ein.  
    Dies stellt die Eingabe der Stunden für einen einzelnen Tag dar.

    ![Screenshot der Seite „Zeiterfassung“.](./media/projops_costs_2_mon_box.png)

1. In dieser Demo gehen wir durch die Erstellung eines Aufwandseintrags, der dem Contoso Consulting-Projekt in Rechnung gestellt wird.  
    Sie können auch interne und externe Kommentare zum Projekt eingeben, um sicherzustellen, dass alle Beteiligten die Art der erfassten Stunden verstehen.

1. Wir werden die Einträge in Formaten erkunden, die für die Darstellung im Web und auf Mobilgeräten optimiert sind. Zudem werden wir erfahren, wie ein Workflow zum Verwalten des Genehmigungsprozess verwendet wird.

1. Wählen Sie in der Navigationsleiste die Option **Speichern** aus.

1. Wählen Sie im linken Navigationsmenü unter **Arbeitszeitnachweise** die Option **Meine Arbeitszeitnachweise** aus.

1. Wählen Sie auf der Seite **Meine Arbeitszeitnachweise** die Zeiterfassung aus, die Sie zuvor erstellt haben.

1. Zeigen Sie auf der Registerkarte **Arbeitszeitnachweis** auf die Spalte „Kategorie“.  
    Now assume we've returned to a computer and are reviewing our time from within the web timesheet form. We can still see the same information, such as the category and the hours.

1. Zeigen Sie unter **Positionsdetails** auf **Interner Kommentar** und **Externer Kommentar**.  
    We can also review the comments we entered earlier. The information is there, but the layout format is just a bit different. This format is often used for final review because it can be easier for people to review and validate their time, especially when someone is assigned to multiple projects or categories.

1. Wählen Sie in der Navigationsleiste die Registerkarte **Workflow** aus.  
    If we're satisfied with the timesheet, we can submit it. The approvals required will be determined by each organization during the implementation phase based on their own company policies.

1. Wählen Sie im Bereich **Workflow für Arbeitszeitnachweis prüfen** die Option **Übermitteln** aus.

1. Fügen Sie im Bereich **Workflow für Arbeitszeitnachweis prüfen – Übermitteln** mögliche weitere Kommentare hinzu.

1. Klicken Sie auf **Senden**.

1. Browse to the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> page. If the <bpt id="p1">**</bpt>Hour transactions<ept id="p1">**</ept> tab is grayed out, browse to the <bpt id="p2">**</bpt>My timesheets page<ept id="p2">**</ept>, and select the previously created timesheet.

1. Überprüfen Sie auf der Seite **Stundenbuchungen** die Seite.  
    Upon approval, the results will be posted and will be visible in the Hour transactions page. We can see all the relevant information, such as the legal entity, project, category, hours, and in this case, even a view of the cost price and the sales price.  

Als nächstes können wir Detailinformationen für die Belegbuchungen anzeigen.

1. Wählen Sie in der Navigationsleiste die Option **Beleg** aus.

1. Zeigen Sie auf der Seite **Belegbuchungen** auf die Abschnitte **Sachkonto** und **Kontoname**.  
    In diesen Abschnitten sehen wir die Auswirkungen auf das Hauptbuch sowie die zu verwendenden Konten.  

Lassen Sie uns jetzt einen Aufwandseintrag für dasselbe Contoso Consulting-Projekt erstellen.

1. Wählen Sie im Navigationsbereich **Module > Ausgabenverwaltung > Eigene Ausgaben > Spesenabrechnungen** aus.

1. Wählen Sie auf der Seite **Ausgabenverwaltung** auf der Registerkarte **Berichte** die Option **+ Neue Spesenabrechnung** aus.

1. Stellen Sie in der Unternehmensauswahl oben rechts sicher, dass die juristische Person, mit der Sie eine Verbindung herstellen, **USSI** ist.

1. Klicken Sie auf **OK**.

1. Wählen Sie auf der Seite **Ausgaben** die Option **+ Neue Ausgaben** aus.  
Es wird eine neue Ausgabenposition angezeigt.

1. Wählen Sie in der Spalte **Spesenkategorie** die Option **Kraftstoff** aus dem Dropdownmenü **Kategorie** aus.  
Hier können wir die neue Ausgabe mit entsprechenden Details eingeben.

1. Geben Sie in der Spalte **Buchungsbetrag** den Wert **25,00** ein.

1. Wählen Sie in der Spalte **Währung** die Option **USD** aus.

1. Wenn das nicht der Fall ist, ändern Sie die juristische Person in **USSI**.  
    Wenn Sie alle Details eingegeben haben, können Sie die Ausgabe speichern.

1. Wählen Sie **Speichern** aus.

1. Wählen Sie im linken Navigationsmenü unter **Arbeitsbereiche** die Option **Ausgabenverwaltung** aus.

1. Wählen Sie auf der Seite **Ausgabenverwaltung** die soeben erstellte Spesenabrechnung aus.

1. Wählen Sie auf der Seite **Spesenabrechnung** das Feld **Projektkennung** und dann **00000093 Contoso Consulting** aus.  

Als nächstes können wir angeben, dass der Kraftstoff dem Contoso Consulting-Projekt in Rechnung gestellt wird, sowie zusätzliche Informationen zu den Ausgaben bereitstellen.

1. Zeigen Sie auf das Feld **Weitere Informationen**.

1. Wählen Sie im unteren rechten Bereich des Bildschirms die Option **Speichern und fortsetzen** aus.

1. Wählen Sie auf der rechten Seite des Bildschirms **Übermitteln** aus.

1. Fügen Sie im Feld **Kommentar** mögliche weitere Kommentare hinzu.

1. Klicken Sie auf **Senden**.

1. Zeigen Sie auf der Seite **Ausgabenverwaltung** auf die Spalte **Genehmigungsstatus**.  
    At this time, travel policies and expense approval flow will be activated. The costs have been posted and applied to the Contoso Consulting project and will be available later for invoicing if chargeable.

In this demo, we have processed a time and expense entry that was charged to the Contoso Consulting project. We saw samples in web and mobile formats and were able to see how workflows are used to manage the approvals required by the USSI organization.
