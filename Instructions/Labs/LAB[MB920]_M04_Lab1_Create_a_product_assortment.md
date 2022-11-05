---
lab:
  title: 'Lab 1: Produktsortiment erstellen'
  module: 'Module 4: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
---

## <a name="lab-1---create-a-product-assortment"></a>Lab 1: Erstellen eines Produktsortiments

## <a name="objectives"></a>Ziele

Sie müssen eine Auswahl zugehöriger Produkte erstellen, die einem bestimmten Commerce-Kanal zugeordnet sind und zu einem späteren Zeitpunkt verfügbar sein werden.

## <a name="lab-setup"></a>Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## <a name="instructions"></a>Anweisungen

1. Wählen Sie oben links auf der Finance and Operations-Seite das Hamburger-Menü **Navigationsbereich erweitern** aus.

1. Wählen Sie im Navigationsbereich **Einzelhandel und Handel** > **Kataloge und Sortimente** > **Sortimente** aus.

1. Wählen Sie auf der Seite „Sortimente“ die Option **+ Neu** aus.

1. Erweitern Sie im Bereich „Neuer Datensatz“ gegebenenfalls **Allgemeines**.

1. Wählen Sie das Feld **Datum des Inkrafttretens** und dann ein Datum in der Zukunft aus.

1. Geben Sie im Feld **Sortimentsnamen** einen Namen für das neue Sortiment ein. Beispielsweise **Neue Frühlingssaison**.

1. Das Ablaufdatum kann verwendet werden, um ein veröffentlichtes Sortiment automatisch zu deaktivieren.

1. Erweitern Sie **Commerce-Kanäle**.

1. Wählen Sie im Menü „Commerce-Kanäle“ die Option **+ Zeile hinzufügen** aus.

1. Wählen Sie unter „Organisationsknoten auswählen“ das Menü **Organisationshierarchie** und dann **Einzelhandelsgeschäfte nach Typ (Fabrikam)** aus.

1. Wählen Sie unter VERFÜGBARE ORGANISATIONSKNOTEN die Option „Online“ und dann das Nach-rechts-Pfeilsymbol ![Hinzufügen](./media/d365-fo-add-org-node-icon.png) aus, um es zu **AUSGEWÄHLTE ORGANISATIONSKNOTEN** hinzuzufügen.  
  Dadurch werden der übergeordnete Knoten und alle untergeordneten Knoten hinzugefügt.

1. Ergänzen Sie den übergeordneten Knoten **Einkaufszentrum**, und wählen Sie dann **OK** aus.

1. Stellen Sie sicher, dass die beiden Knoten zu den Commerce-Kanälen hinzugefügt wurden.

1. Erweitern Sie **Produkte**.

1. Wählen Sie im Menü Produkte die Option **+ Zeile hinzufügen** aus.

1. Wählen Sie das Menü **Kategorie**, **Mannschaftssport (Mannschaftssport)** und dann **OK** aus.

1. Dadurch werden alle untergeordneten Elemente der übergeordneten Kategorie hinzugefügt.

1. Überprüfen Sie die letzte Spalte **Zeilenart**. Standardmäßig werden alle Elemente eingeschlossen.

1. Wählen Sie **+ Zeile hinzufügen** und das Menü **Kategorie** aus, erweitern Sie **Mannschaftssport (Mannschaftssport)** , und klicken Sie dann auf **Baseball** und **OK**.

1. Um einen Artikel aus einer bereits enthaltenen größeren Kategorie auszuschließen, in diesem Fall Mannschaftsport, ändern Sie in der Spalte „Zeilenart“ den Wert in **Ausschließen**.

1. Wählen Sie in der Zeile Baseballkategorie das Menü **Produkte** aus.

1. Wenn Produkte innerhalb einer Kategorie definiert sind, können Sie ein bestimmtes Produkt zum Einschließen oder Ausschließen auswählen. Wählen Sie **AdultBaseballInfield** aus.

1. Um ein hinzugefügtes Produkt zu entfernen, löschen Sie den Inhalt des Produktfelds, und drücken Sie dann die Tabulatortaste auf Ihrer Tastatur oder wählen Sie einen anderen Bereich der Seite aus.

1. Wählen Sie oben im Menü **Speichern** aus.

1. Wählen Sie oben im Menü **Veröffentlichen** aus.

1. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann **Ja** aus.

1. Das neue erstellte Produktsortiment steht ab den festgelegten Gültigkeitsdatum zur Verfügung.
