---
lab:
  title: 'Lab 1: Produktsortiment erstellen'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

# Modul 4 Grundlagen von Microsoft Dynamics 365 Commerce erlernen

## Lab 1: Produktsortiment erstellen

## Ziel

Sie müssen eine Auswahl zugehöriger Produkte erstellen, die einem bestimmten Commerce-Kanal zugeordnet sind und zu einem späteren Zeitpunkt verfügbar sein werden. 

## Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## Anweisungen

1.  Überprüfen Sie auf der **Finance and Operations**-Startseite oben rechts, ob Sie mit dem **USMF**-Unternehmen arbeiten. 

1.  Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus. 

1.  Wählen Sie im linken Navigationsbereich im Modul **Einzelhandel und Handel** die Option **Kataloge und Sortimente** > **Sortimente** aus. 

1.  Wählen Sie auf der Seite **Sortimente** die Option **+ Neu** aus. 

1.  Erweitern Sie im Formular **Neuer Datensatz** bei Bedarf das Inforegister **Allgemein**. 

1.  Wählen Sie das Feld **Datum des Inkrafttretens** und dann ein Datum in der Zukunft aus.  

1.  Geben Sie im Feld **Sortimentsname** einen Namen für das neue Sortiment ein. Zum Beispiel, `New Spring Season`

    > **Hinweis:** Das **Ablaufdatum** kann verwendet werden, um ein veröffentlichtes Sortiment automatisch zu deaktivieren. 

1.  Erweitern Sie das Inforegister **Commerce Channels**. 

1.  Wählen Sie auf der Symbolleiste **Commerce Channels** die Option **+ Zeile hinzufügen** aus. 

1.  Wählen Sie unter **Organisationsknoten auswählen** für das Feld **Organisationshierarchie** **Einzelhandelsgeschäfte nach Typ (Fabrikam)** aus. 

1.  Wählen Sie unter VERFÜGBARE ORGANISATIONSKNOTEN die Option „Online“ und dann das Nach-rechts-Pfeilsymbol ![Hinzufügen](./media/d365-fo-add-org-node-icon.png) aus, um es zu **AUSGEWÄHLTE ORGANISATIONSKNOTEN** hinzuzufügen.

    Dadurch werden der übergeordnete Knoten und alle untergeordneten Knoten hinzugefügt. 

1.  Ergänzen Sie den übergeordneten Knoten **Einkaufszentrum**, und wählen Sie dann **OK** aus. 

1.  Vergewissern Sie sich, dass die beiden Knoten zum Inforegister **Commerce Channels** hinzugefügt wurden. 

1.  Erweitern Sie das Inforegister **Produkte**. 

1.  Wählen Sie auf der Symbolleiste **Produkte** die Option **+Zeile hinzufügen** aus. 

1.  Erweitern Sie für das Feld **Kategorie**, **Mannschaftssport (Mannschaftssport)** , und wählen Sie dann **OK** aus.

    Dadurch werden alle untergeordneten Elemente der übergeordneten Kategorie hinzugefügt.

1.  Überprüfen Sie die letzte Spalte **Zeilenart**. Standardmäßig werden alle Elemente eingeschlossen.

1.  Wählen Sie **+ Zeile hinzufügen** und das Menü **Kategorie** aus, erweitern Sie **Mannschaftssport (Mannschaftssport)** , und klicken Sie dann auf **Baseball** und **OK**. 

1.  Um einen Artikel aus einer bereits enthaltenen größeren Kategorie auszuschließen, in diesem Fall Mannschaftsport, ändern Sie in der Spalte **Zeilenart** den Wert in `Exclude`. 

1.  Wählen Sie in der Zeile Baseballkategorie das Menü **Produkte** aus. 

1.  Wenn Produkte innerhalb einer Kategorie definiert sind, können Sie ein bestimmtes Produkt zum Einschließen oder Ausschließen auswählen. Wählen Sie **AdultBaseballInfield** aus, oder geben Sie `0013` ein. 

    > **Hinweis:** Um ein hinzugefügtes Produkt zu entfernen, löschen Sie den Inhalt des Felds **Produkt**, und drücken Sie dann die TAB-TASTE auf Ihrer Tastatur, oder wählen Sie einen anderen Bereich der Seite aus. 

1.  Wählen Sie im Aktionsbereich **Speichern** und dann **Veröffentlichen** aus. 

1.  Wählen Sie im Bestätigungsdialogfeld die Option **Ja**. Das neue erstellte Produktsortiment steht ab den festgelegten **Wirksamkeitsdatum** zur Verfügung. 

