---
lab:
  title: "Lab\_3: Erstellen einer Inventurerfassung"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modul 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management erlernen

## <a name="lab-3---create-a-counting-journal"></a>Lab 3: Erstellen einer Inventurerfassung

1. Überprüfen Sie auf der Homepage von Finance and Operations rechts oben, ob Sie mit dem Unternehmen **USMF** arbeiten. Wählen Sie bei Bedarf das Unternehmen und dann im Dropdownmenü **USMF** aus.

2. Wählen Sie im Navigationsbereich links **Module** > **Bestandsverwaltung** > **Journaleinträge** > **Artikelinventur** > **Inventur** aus.

3. Wählen Sie im Aktionsbereich die Schaltfläche **+ Neu** aus. Das Dialogfeld **Bestandserfassung erstellen** wird mit der Schaltfläche **OK** (unten) angezeigt. Klicken Sie auf die Schaltfläche **OK**.

4. Das Formular für die Inventurerfassung wird mit Kopfzeile und Detailinformationen angezeigt

    ![Screenshot des Formulars für die Inventurerfassung mit Kopfzeile und ausgefüllten Detailinformationen](./media/lp-scm-m-002-warehouse-inventory-mgmt-06.png)

5. Wählen Sie im Aktionsbereich **Zeilen erstellen &gt; On-hand** (vorrätig) aus.

6. Legen Sie im Dialogfeld **Inventurerfassung erstellen** die Felder **Lager**, **Bestandsstatus**, **Standort** und **Ladungsträger** auf **Ja** fest. 

    ![Screenshot des Dialogfelds „Inventurerfassung erstellen“ mit den Feldern, die wie beschrieben festgelegt sind](./media/lp-scm-m-002-warehouse-inventory-mgmt-07.png)

7. Erweitern Sie den Abschnitt **Einzuschließende Datensätze**, und wählen Sie den Link **Filter** aus. Geben Sie für das Feld **Elementnummer** den Eintrag **A0001** in die Kriterien ein, und wählen Sie dann **OK** aus.

8. Wählen Sie im unteren Bereich des Dialogfelds **Inventurerfassung erstellen** die Option **OK** aus.

Die Bestandsmenge des Artikels A0001 wird im Abschnitt **Erfassungspositionen** mit der Aufschlüsselung für Standort, Lager, Lagerort und Ladungsträger angezeigt.

9. Geben Sie im Abschnitt **Erfassungsposition** in der Spalte **Gezählt** die Zahlen ein, die für jede Kombination aus Standort/Lager/Lagerort/Ladungsträger gezählt wurden. Beachten Sie Folgendes:

    - Wenn die **Bestandsmenge** mit der **gezählten** Menge übereinstimmt, ist das Feld **Menge** leer.

    - Wenn der Wert des Felds **Gezählt** größer als der des Felds **Bestandsmenge** ist, enthält das Feld **Menge** einen positiven Wert.

    - Wenn der Wert des Felds **Gezählt** kleiner als der des Felds **Bestandsmenge** ist, enthält das Feld **Menge** einen negativen Wert.

10. Wählen Sie im Aktionsbereich die Schaltfläche **Überprüfen** und dann die Schaltfläche **Veröffentlichen** aus.

11. Schließen Sie die Seite, und navigieren Sie zur Startseite zurück.
