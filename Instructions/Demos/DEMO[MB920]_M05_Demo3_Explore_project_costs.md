---
demo:
  title: 'Demo 3: Projektkosten erkunden'
  module: 'Module 5: Learn the Fundamentals of Microsoft Dynamics 365 Project Operations'
ms.openlocfilehash: ca5f0816e2d018c01ab7e24b43219ff32c0e693e
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137909415"
---
## <a name="demo-3---explore-project-costs"></a>Demo 3 – Projektkosten erkunden

In dieser Demo gehen wir durch die Erstellung eines Aufwandseintrags, der dem Contoso Consulting-Projekt in Rechnung gestellt wird. Wir werden die Einträge in Formaten erkunden, die für die Darstellung im Web und auf Mobilgeräten optimiert sind. Zudem werden wir erfahren, wie ein Workflow zum Verwalten des Genehmigungsprozess verwendet wird.

1. Wählen Sie in **Dynamics 365 for Finance and Operations** im Navigationsbereich die Option **Module > Projektverwaltung und -verrechnung > Arbeitszeitnachweise > Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)** aus.  
    Obwohl ich mich jetzt noch nicht auf einem Mobilgerät befinde, werden Sie die Formulare als für Mobilgeräte geeignet erkennen, nachdem wir die Option **Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)** ausgewählt haben.

    ![Screenshot des Menüs „Projektverwaltung und -verrechnung“, in dem die Option „Meine Arbeitszeitnachweise (für Mobilgeräte optimiert)“ hervorgehoben ist](./media/projops_costs_1_select_my_timesheets.png)  

    Diese Optimierung ist ein wichtiges Unterscheidungsmerkmal für Microsoft-Geschäftsanwendungen und trägt dazu bei, dass es eine minimale Lernkurve zwischen der Verwendung im Web und auf Mobilgeräten gibt.

1. Stellen Sie in der Unternehmensauswahl oben rechts sicher, dass die juristische Person, mit der Sie eine Verbindung herstellen, **USSI** ist. Wenn das nicht der Fall ist, ändern Sie die juristische Person in **USSI**.

1. Wählen Sie auf der Seite **Meine Arbeitszeitnachweise** die Option **Neu** aus.  
    Jetzt erstellen wir einen neuen Arbeitszeitnachweis, der auf den konfigurierten Einstellungen basiert.

1. Zeigen Sie im Bereich **Neuer Arbeitszeitnachweis** auf das Feld **Datum**.  
    Das eingegebene Datum bestimmt den Zeitraum für den Arbeitszeitnachweis.

1. Zeigen Sie auf **Aus Favoriten erstellen**.  
    Wenn Sie Favoriten gespeichert haben, können Sie auswählen, diese für die Erstellung zu verwenden, um Zeit zu sparen.

1. Wählen Sie **OK** aus, wenn Sie fertig sind.

1. Wählen Sie auf der Seite **Meine Arbeitsnachweisdetails** das Symbol **Neu +** aus.

1. Zeigen Sie im Bereich **Neue Zeile im Arbeitszeitnachweis** auf das Feld **Juristische Person**.  
    Die neue Zeile im Arbeitszeitnachweis wird mit Details wie Kunde, Projekt, Kategorie, Zeileneigenschaften und Steuerparameter geöffnet. Sie können auch eine andere juristische Person auswählen, wenn die Zeiterfassung im Namen eines anderen Unternehmens innerhalb Ihrer Organisation erfolgt.

1. Wählen Sie das Menü **Projektkennung** aus.

1. Wählen Sie eines der verfügbaren Projekte aus, z. B. das Projekt **Contoso Consulting**.

1. Wählen Sie **OK** aus, wenn Sie fertig sind.  
    Der für Mobilgeräte optimierte Bildschirm für die Zeiterfassung wird geöffnet und Sie können beginnen, Ihre Stunden pro Tag für das Projekt und die Kategorie, in diesem Fall **Service**, zu buchen.

1. Geben Sie auf der Seite **Zeiterfassung** im Feld **Mon** die Zahl **8** ein.  
    Dies stellt die Eingabe der Stunden für einen einzelnen Tag dar.

    ![Screenshot der Seite „Zeiterfassung“.](./media/projops_costs_2_mon_box.png)

1. Fügen Sie im Feld **Interner Kommentar** einen Kommentar hinzu. Beispiele: **Vielleicht Gespräch über neue Fahrräder führen**.  
    Sie können auch interne und externe Kommentare zum Projekt eingeben, um sicherzustellen, dass alle Beteiligten die Art der erfassten Stunden verstehen.

1. Fügen Sie im Feld **Externer Kommentar** einen Kommentar hinzu. Beispiele: **Ketten wurden eingestellt und die Vorderräder des Fuhrparks ausgerichtet**.

1. Wählen Sie in der Navigationsleiste die Option **Speichern** aus.

1. Wählen Sie im linken Navigationsmenü unter **Arbeitszeitnachweise** die Option **Meine Arbeitszeitnachweise** aus.

1. Wählen Sie auf der Seite **Meine Arbeitszeitnachweise** die Zeiterfassung aus, die Sie zuvor erstellt haben.

1. Zeigen Sie auf der Registerkarte **Arbeitszeitnachweis** auf die Spalte „Kategorie“.  
    Nehmen wir jetzt an, dass wir zu einem Computer zurückgekehrt sind und unsere Zeit aus dem für das Web vorgesehene Arbeitszeitnachweisformular heraus überprüfen. Wir können immer noch dieselben Informationen sehen, z. B. die Kategorie und die Stunden.

1. Zeigen Sie unter **Positionsdetails** auf **Interner Kommentar** und **Externer Kommentar**.  
    Wir können auch die Kommentare überprüfen, die wir zuvor eingegeben haben. Die Informationen sind vorhanden, aber das Layoutformat ist ein wenig anders. Dieses Format wird häufig für die abschließende Überprüfung verwendet, da es für die Mitarbeiter einfacher sein kann, ihre Zeit zu prüfen und zu validieren, besonders wenn einige Beteiligte mehreren Projekten oder Kategorien zugewiesen sind.

1. Wählen Sie in der Navigationsleiste die Registerkarte **Workflow** aus.  
    Wenn wir mit dem Arbeitszeitnachweis zufrieden sind, können wir ihn übermitteln. Die erforderlichen Genehmigungen werden von jeder Organisation während der Implementierungsphase auf der Grundlage ihrer Unternehmensrichtlinien festgelegt.

1. Wählen Sie im Bereich **Workflow für Arbeitszeitnachweis prüfen** die Option **Übermitteln** aus.

1. Fügen Sie im Bereich **Workflow für Arbeitszeitnachweis prüfen – Übermitteln** mögliche weitere Kommentare hinzu.

1. Klicken Sie auf **Senden**.

1. Navigieren Sie zur Seite **Stundenbuchungen**. Wenn die Registerkarte **Stundenbuchungen** abgeblendet dargestellt ist, navigieren Sie zur Seite **Meine Arbeitszeitnachweise**, und wählen Sie den zuvor erstellten Arbeitszeitnachweis aus.

1. Überprüfen Sie auf der Seite **Stundenbuchungen** die Seite.  
    Nach der Genehmigung werden die Ergebnisse gebucht und auf der Seite „Stundenbuchungen“ angezeigt. Wir können alle relevanten Informationen sehen, z. B. die juristische Person, das Projekt, die Kategorie, die Stunden und in diesem Fall sogar eine Ansicht des Einstands- und des Verkaufspreises.  

Als nächstes können wir Detailinformationen für die Belegbuchungen anzeigen.

1. Wählen Sie in der Navigationsleiste die Option **Beleg** aus.

1. Zeigen Sie auf der Seite **Belegbuchungen** auf die Abschnitte **Sachkonto** und **Kontoname**.  
    In diesen Abschnitten sehen wir die Auswirkungen auf das Hauptbuch sowie die zu verwendenden Konten.  

Lassen Sie uns jetzt einen Aufwandseintrag für dasselbe Contoso Consulting-Projekt erstellen.

1. Wählen Sie im Navigationsbereich **Module > Ausgabenverwaltung > Eigene Ausgaben > Spesenabrechnungen** aus.

1. Wählen Sie auf der Seite **Ausgabenverwaltung** auf der Registerkarte **Berichte** die Option **+ Neue Spesenabrechnung** aus.

1. Geben Sie im Bereich **Neue Spesenabrechnung** im Feld **Zweck** einen Titel ein. Beispiel: **Contoso – Feb2021**.

1. Klicken Sie auf **OK**.

1. Wählen Sie auf der Seite **Ausgaben** die Option **+ Neue Ausgaben** aus.  
Es wird eine neue Ausgabenposition angezeigt.

1. Wählen Sie in der Spalte **Spesenkategorie** die Option **Kraftstoff** aus dem Dropdownmenü **Kategorie** aus.  
Hier können wir die neue Ausgabe mit entsprechenden Details eingeben.

1. Geben Sie in der Spalte **Buchungsbetrag** den Wert **25,00** ein.

1. Wählen Sie in der Spalte **Währung** die Option **USD** aus.

1. Wählen Sie in der Spalte **Buchungsdatum** ein Datum aus. Ein Beispiel hierfür ist **2/1/2021**.  
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
    Zu diesem Zeitpunkt werden Reiserichtlinien und der Spesengenehmigungsfluss aktiviert. Die Kosten wurden gebucht und auf das Contoso Consulting-Projekt angewendet und stehen später für die Rechnungsstellung zur Verfügung, falls sie fakturierbar sind.

In dieser Demo haben wir einen Aufwandseintrag verarbeitet, der dem Contoso Consulting-Projekt in Rechnung gestellt wurde. Wir haben Beispiele im Webformat und im Format für Mobilgeräte gesehen und konnten erkennen, wie Workflows verwendet werden, um die von der USSI-Organisation benötigten Genehmigungen zu verwalten.
