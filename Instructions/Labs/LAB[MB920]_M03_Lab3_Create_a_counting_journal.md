---
lab:
  title: "Lab\_3: Erstellen einer Inventurerfassung"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modul 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management erlernen

## <a name="lab-3---create-a-counting-journal"></a>Lab 3: Erstellen einer Inventurerfassung

1. On the Finance and Operations home page, in the top right, verify you are working with the <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept> company. If necessary, select the company, and from the drop down, select <bpt id="p1">**</bpt>USMF<ept id="p1">**</ept>.

2. Wählen Sie im Navigationsbereich links **Module** > **Bestandsverwaltung** > **Journaleinträge** > **Artikelinventur** > **Inventur** aus.

3. Select the <bpt id="p1">**</bpt>+New<ept id="p1">**</ept> button in the action pane. The <bpt id="p1">**</bpt>Create inventory journal<ept id="p1">**</ept> dialog form will appear with the <bpt id="p2">**</bpt>OK<ept id="p2">**</ept> button in the bottom. Select the <bpt id="p1">**</bpt>OK<ept id="p1">**</ept> button.

4. Das Formular für die Inventurerfassung wird mit Kopfzeile und Detailinformationen angezeigt

![Screenshot des Formulars für die Inventurerfassung mit Kopfzeile und ausgefüllten Detailinformationen](../media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Wählen Sie im Aktionsbereich **Zeilen erstellen &gt; Online** aus.

6. Legen Sie im Dialogfeld **Inventurerfassung erstellen** die Felder **Lager**, **Bestandsstatus**, „Standort“ und **Ladungsträger** auf **Ja** fest. 

![Screenshot des Dialogfelds „Inventurerfassung erstellen“ mit den Feldern, die wie beschrieben festgelegt sind](../media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Expand the <bpt id="p1">**</bpt>Record to include<ept id="p1">**</ept> section and select the <bpt id="p2">**</bpt>Filter<ept id="p2">**</ept> link. In the <bpt id="p1">**</bpt>Item number<ept id="p1">**</ept> field, select <bpt id="p2">**</bpt>A0001<ept id="p2">**</ept>, and then select <bpt id="p3">**</bpt>OK<ept id="p3">**</ept>.

8. Wählen Sie im unteren Bereich des Dialogfelds **Inventurerfassung erstellen** die Option **OK** aus.

Die Bestandsmenge des Artikels A0001 wird im Abschnitt **Erfassungspositionen** mit der Aufschlüsselung für Standort, Lager, Lagerort und Ladungsträger angezeigt.

9. In the <bpt id="p1">**</bpt>Counted<ept id="p1">**</ept> column of the <bpt id="p2">**</bpt>Journal line<ept id="p2">**</ept> section, enter the numbers counted in each Site/Warehouse/Location/License plate. Note the following:

    - Wenn die **Bestandsmenge** mit der **gezählten** Menge übereinstimmt, ist das Feld **Menge** leer.

    - Wenn der Wert des Felds **Gezählt** größer als der des Felds **Bestandsmenge** ist, enthält das Feld **Menge** einen positiven Wert.

    - Wenn der Wert des Felds **Gezählt** kleiner als der des Felds **Bestandsmenge** ist, enthält das Feld **Menge** einen negativen Wert.

10. Wählen Sie im Aktionsbereich die Schaltfläche **Überprüfen** und dann die Schaltfläche **Veröffentlichen** aus.

11. Schließen Sie die Seite, und navigieren Sie zur Startseite zurück.
