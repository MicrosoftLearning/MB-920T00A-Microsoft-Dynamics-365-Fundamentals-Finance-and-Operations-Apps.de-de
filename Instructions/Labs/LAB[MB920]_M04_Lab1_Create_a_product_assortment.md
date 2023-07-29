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

1.  Wählen Sie oben links auf der Finance and Operations-Startseite das Hamburger-Menü **Navigationsbereich erweitern** aus.

2.  Wählen Sie im Navigationsbereich **Einzelhandel und Handel** > **Kataloge und Sortimente** > **Sortimente** aus.

3.  Warten Sie, bis die Seite geladen sind.

4.  Wählen Sie auf der Seite **Sortimente** die Option **+ Neu** aus.

5.  Erweitern Sie **Allgemeines** im Bereich **Neuer Datensatz**.

6.  Wählen Sie das Feld **Datum des Inkrafttretens** und dann ein Datum in der Zukunft aus.

7.  Geben Sie im Feld **Sortimentsnamen** einen Namen für das neue Sortiment ein. Beispielsweise **Neue Frühlingssaison**.

8.  Stellen Sie die **Ablaufdatum** auf **Nie**.

    Das Ablaufdatum kann verwendet werden, um ein veröffentlichtes Sortiment automatisch zu deaktivieren.

9.  Erweitern Sie **Commerce-Kanäle**.

10. Wählen Sie im Menü **Commerce-Kanäle** die Option **+ Zeile hinzufügen** aus.

11. Wählen Sie unter **Organisationsknoten auswählen** das Menü **Organisationshierarchie** und dann **Einzelhandelsgeschäfte nach Typ (Fabrikam)** aus.

12. Wählen Sie unter **VERFÜGBARE ORGANISATIONSKNOTEN** die Option **Online** und dann **Hinzufügen** > ![Picture 15](./media/04-learn-the-fundamentals-of-dynamics-365-commerce-17.png) aus, um es zu **AUSGEWÄHLTE ORGANISATIONSKNOTEN** hinzuzufügen.

    Dadurch werden der übergeordnete Knoten und alle untergeordneten Knoten hinzugefügt.

13. Ergänzen Sie den übergeordneten Knoten **Einkaufszentrum**, und wählen Sie dann **OK** aus.

14. Stellen Sie sicher, dass die beiden Knoten zu den Commerce-Kanälen hinzugefügt wurden.

15. Erweitern Sie **Produkte**.

16. Wählen Sie im Menü **Produkte** die Option **+ Zeile hinzufügen** aus.

17. Wählen Sie das Menü **Kategorie**, **Mannschaftssport (Mannschaftssport)** und dann **OK** aus.

    Dadurch werden alle untergeordneten Elemente der übergeordneten Kategorie hinzugefügt.

18. Überprüfen Sie die letzte Spalte **Zeilenart**. Standardmäßig werden alle Elemente eingeschlossen.

19. Wählen Sie **+ Zeile hinzufügen** und das Menü **Kategorie** aus, erweitern Sie **Mannschaftssport (Mannschaftssport)** , und klicken Sie dann auf **Baseball** und **OK**.

20. Um einen Artikel aus einer bereits enthaltenen größeren Kategorie auszuschließen, in diesem Fall **Mannschaftsport**, ändern Sie in der Spalte **Zeilenart** den Wert in **Ausschließen**.

21. Wählen Sie in der Kategoriezeile **Baseball** das Menü **Produkte** aus.

22. Wenn Produkte innerhalb einer Kategorie definiert sind, können Sie ein bestimmtes Produkt zum Einschließen oder Ausschließen auswählen. Wählen Sie **AdultBaseballInfield** aus.

23. Um ein hinzugefügtes Produkt zu entfernen, löschen Sie den Inhalt des Produktfelds, und drücken Sie dann die **TAB-TASTE** auf Ihrer Tastatur, oder wählen Sie einen anderen Bereich der Seite aus.

24. Wählen Sie oben im Menü **Speichern** aus.

25. Wählen Sie oben im Menü **Veröffentlichen** aus.

26. Überprüfen Sie die Informationen im Dialogfeld, und wählen Sie dann **Ja** aus.

    Das neue erstellte Produktsortiment steht ab den festgelegten Gültigkeitsdatum zur Verfügung.

