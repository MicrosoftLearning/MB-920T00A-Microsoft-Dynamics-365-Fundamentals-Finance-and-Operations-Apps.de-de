---
lab:
  title: "Lab\_2: Bestellung erstellen"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# Modul 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management erlernen

## Lab 2: Bestellung erstellen

## Lab-Einrichtung

   - **Geschätzte Dauer**: 15 Minuten

## Ziel

In dieser Übung machen Sie sich mit der Benutzeroberfläche und den verschiedenen Feldern vertraut, die im Bestellformular verfügbar sind. Außerdem erfahren Sie, wie Sie eine neue Bestellung erstellen können.


## Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## Anweisungen

1. Überprüfen Sie auf der Finance and Operations-Startseite oben rechts, ob Sie mit dem **USMF**-Unternehmen arbeiten. Wählen Sie bei Bedarf das Unternehmen und dann im Dropdownmenü **USMF** aus.

2. Wählen Sie oben links das Hamburger-Menü **Navigationsbereich erweitern** aus.

3. Wählen Sie **Module** > **Beschaffung** > **Bestellungen** > **Alle Bestellungen** aus.

4. Wählen Sie auf der Seite **Alle Bestellungen** im oberen Menü die Option **+ Neu** aus.

5. Wählen Sie im Bereich **Bestellung anlegen** das Dropdownmenü **Kreditorenkonto** und dann **US-101** aus.

> [!NOTE]
> Hinweis: Wenn Sie einen Kreditor auswählen, werden Details aus dem Kreditorendatensatz wie Adresse, Rechnungskonto, Lieferbedingungen und Lieferart als Standardwerte in den Auftragskopf kopiert. Sie können diese Werte jederzeit ändern.

6. Erweitern Sie wenn nötig den Abschnitt **Allgemein**.

7. Wählen Sie unter **LAGERDIMENSIONEN** das Dropdownmenü **Standort** aus, und überprüfen Sie die Liste der Standorte.

Das Feld **Standort** gibt zusammen mit dem Feld **Lager** an, wohin die beschafften Waren oder Dienstleistungen geliefert werden müssen. Die Standardlieferadresse ist der Standort. Beide Felder können mit Werten gefüllt werden, die für den ausgewählten Kreditor eingerichtet wurden, oder Sie können sie manuell angeben.

8. Unter **TERMINE** wird das Feld **Lieferdatum** verwendet, um festzulegen wann beschaffte Waren und Dienstleistungen geliefert werden müssen.

    Sie können einen einzelnen Liefertermin für den Auftrag angeben, oder den einzelnen Auftragspositionen können eindeutige Liefertermine zugewiesen werden. Wenn das hier angegebene Lieferdatum für bestimmte Produkte oder Dienstleistungen nicht eingehalten werden kann, weil sie längere Vorlaufzeiten haben, werden diese Zeilen mit einem späteren Lieferdatum erstellt.

9. Erweitern Sie den Abschnitt **Verwaltung**. Im Feld **Besteller** können Sie angeben, wer den Auftrag erteilt.

    Dies kann zweckmäßig sein, um es dem Kreditor mitzuteilen, falls er diese Person kontaktieren muss. Der Wert kann automatisch zugewiesen werden, wenn das aktuelle Benutzerkonto einem Namen auf der Seite **Benutzer** zugeordnet ist.

10. Klicken Sie auf **OK**.

Der Auftragskopf wurde nun erstellt. Wenn Sie mit Bestellpositionen arbeiten, wird nur eine Zusammenfassung der Kopfzeileninformationen angezeigt. Wenn Sie den Rest der Informationen anzeigen möchten, wählen Sie **Kopfzeile** aus.

![Screenshot: Bestellkopfzeile, in der die Zusammenfassung der Bestellinformationen angezeigt wird. Das Wort „Kopfzeile“ ist hervorgehoben.](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-17.png)

11. Wählen Sie unter **Bestellpositionen** im Menü die Option **Bestellposition** aus.

![Screenshot mit Einkaufsbestellpositionen](./media/03-learn-the-fundamentals-of-dynamics-365-supply-chain-management-18.png)

12. Wählen Sie unter **DISPLAY** **Dimensionen** aus.

    Produkte können in Varianten vorliegen, die sich nach Dimensionen wie Farbe, Größe oder Stil unterscheiden. Produkte können auch so eingerichtet werden, dass sie Lagerdimensionen wie Standort und Lager verwenden. Es gibt auch optionale Rückverfolgungsangaben wie Chargen‑ und Seriennummern. Um die Effizienz der Auftragserfassung zu verbessern, können Sie die üblicherweise verwendeten Dimensionsfelder direkt zum Auftragsraster hinzufügen.

13. Aktivieren Sie im Anzeigebereich **Dimensionen** unter **PRODUKTDIMENSIONEN** das Kontrollkästchen **Farbe**.

Optional: Wenn Sie den Umschalter **Einstellungen speichern** aktivieren, werden die von Ihnen ausgewählten Dimensionen beim nächsten Öffnen der Bestellseite auch im Raster der Bestellposition angezeigt.

14. Klicken Sie auf **OK**.

15. Wählen Sie das Zellendropdownmenü **Artikelnummer** und dann **T0004** aus.

Denken Sie daran, dass Sie auch das Filterfeld eingeben können, anstatt durch die Liste zu scrollen.

Bestellpositionen werden für Produkte und Dienstleistungen durch Angabe einer Artikelnummer oder als Aufwand durch Angabe einer Beschaffungskategorie angelegt.

Die Beschaffungskategorie wird zum Hinzufügen von Zeilen verwendet, in denen beschaffte Artikel direkt als Aufwand erfasst werden, anstatt in den Lagerbestand aufgenommen zu werden. Wenn Sie einen Einkauf verrechnen müssen, können Sie eine Bestellposition erstellen, in der eine Beschaffungskategorie angegeben ist, anstatt eine Zeile mit einer Artikelnummer zu erstellen. Artikel können auch einer Beschaffungskategorie zugeordnet werden. In diesem Fall wird die Beschaffungskategorie nur zu Informationszwecken angezeigt.

16. Öffnen Sie das Dropdownmenü **Farbe**, überprüfen Sie im Menü die verfügbaren Optionen, und wählen Sie dann eine der Farben oder Farbkombinationen aus.

17. **Standort** und **Lager** werden normalerweise mit Werten aus dem Auftragskopf gefüllt. Es ist jedoch möglich, die Felder zu überschreiben, wenn einige Positionen an verschiedene Standorte geliefert werden müssen.

18. Geben Sie im Feld **Menge** **10** ein.

    Die **Menge** wird automatisch mit der Mindestbestellmenge für das Produkt aufgefüllt, wenn diese eingerichtet ist, oder mit dem Wert **1**.

19. Einige zusätzliche Informationen:

- **Einheit:** Zeigt die Maßeinheit für die bestellte Menge an. Normalerweise wird die Einheit automatisch von der Einkaufseinheit in den Produktmasterdaten bereitgestellt.

- **Preis je Einheit**: Enthält einen Wert aus einem Kaufvertrag oder einem Handelsvertrag. Es ist möglich, den Stückpreis in einzelnen Bestellpositionen zu ändern – beispielsweise wenn mit dem Kreditor ein eindeutiger Preis ausgehandelt wird.

- **Rabatt**: Stellt einen Rabattbetrag pro Einheit dar. Dieser Rabatt reduziert daher den Stückpreis um den Rabatt. Dieser Rabatt wird normalerweise automatisch aus Kaufverträgen oder Handelsvereinbarungen geliefert. Es ist jedoch möglich, einzelne Zeilen zu überschreiben, wenn mit dem Kreditor eindeutige Rabatte ausgehandelt wurden.

- **Rabattprozentsatz**: Bei Eingabe wird der Nettobetrag für die Zeile entsprechend reduziert. Der Rabattprozentsatz wird normalerweise automatisch aus Kaufverträgen oder Handelsvereinbarungen geliefert. Es ist jedoch möglich, einzelne Zeilen zu überschreiben, wenn mit dem Kreditor ein eindeutiger Rabattprozentsatz ausgehandelt wurde.

- **Nettobetrag**: Berechnet aus anderen Feldern in der Zeile, einschließlich Menge, Stückpreis, Rabatt und Rabattprozentsatz. Es ist möglich, den Nettobetrag zu ändern, dann sind jedoch die Felder „Stückpreis“, „Rabatt“ und „Rabattprozentsatz“ leer. Wenn Sie dann zur Position buchen, ist der gebuchte Betrag proportional zum Nettobetrag. Das Feld „Nettobetrag“ wird nur zur Anzeige des Nettobetrags der Zeile verwendet.

20. Wählen Sie unter den Bestellpositionen unten auf der Seite die Option **Positionsdetails** aus.

21. Wählen Sie die Registerkarte **Lieferung** aus.

    Jeder Bestellposition kann eine eindeutige Auftragsposition zugewiesen werden. Das Datum wird vom Feld im Bestellkopf übernommen, Sie können dieses jedoch ändern.

22. Schließen Sie die Seite **Bestellposition**.

23. Verwenden Sie auf der Seite **Alle Bestellungen** das Filterfeature, und suchen Sie Ihre neue Bestellung.

24. Wenn Sie fertig sind, schließen Sie die Seite **Alle Bestellungen**, und kehren Sie zur Startseite zurück.

