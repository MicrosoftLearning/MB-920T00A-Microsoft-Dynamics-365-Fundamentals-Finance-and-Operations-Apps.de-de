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

Typischer ist es, dass Bestellungen automatisch als Ergebnis von Produktprogrammplanung, Direktlieferung und anderen Prozessen erstellt werden. Bei der manuellen Erstellung einer Bestellung wird sie normalerweise von einem Einkaufsvertreter erstellt. Erstellen Sie eine Bestellung unter Verwendung des USMF-Unternehmens. 

## Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## Anweisungen

1.  Überprüfen Sie auf der **Finance and Operations**-Startseite oben rechts, ob Sie mit dem **USMF**-Unternehmen arbeiten. 

1.  Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus. 

1.  Wählen Sie oben links das Hamburger-Menü **Navigationsbereich erweitern** aus. 

1.  Wählen Sie im Modul **Beschaffung** die Option **Bestellungen** > **Alle Bestellungen** aus. 

1.  Wählen Sie auf der Seite **Alle Bestellungen** im Aktionsbereich die Option **+ Neu** aus. 

1.  Wählen Sie im Bereich **Bestellung anlegen** das Feld **Kreditorenkonto** und dann `US-101` aus, oder geben Sie den Wert ein.

1.  Wenn Sie einen Kreditor auswählen, werden Details aus dem Kreditorendatensatz wie Adresse, Rechnungskonto, Lieferbedingungen und Lieferart als Standardwerte in den Bestellungskopf kopiert. Sie können diese Werte bei Bedarf ändern. 

1.  Erweitern Sie den Abschnitt **Allgemein**. 

1.  Wählen Sie unter **LAGERDIMENSIONEN** das Menü **Standort** aus und überprüfen Sie die Liste der Standorte. 

    > **Hinweis:** Das Feld **Standort** gibt zusammen mit dem Feld **Lager** an, wohin die beschafften Waren oder Dienstleistungen geliefert werden müssen. Die Standardlieferadresse wird aus dem **Standort** abgeleitet. Beide Felder können mit Werten gefüllt werden, die für den ausgewählten Kreditor eingerichtet wurden, oder Sie können sie manuell angeben. 

1.  Geben Sie für **Lager** `13` ein, oder wählen Sie den Wert aus.

1.  Unter **TERMINE** wird das Feld **Lieferdatum** verwendet, um festzulegen wann beschaffte Waren und Dienstleistungen geliefert werden müssen.

    > **Hinweis:** Sie können einen einzelnen Liefertermin für den Auftrag angeben, oder den einzelnen Auftragspositionen können eindeutige Liefertermine zugewiesen werden. Wenn das hier angegebene Lieferdatum für bestimmte Produkte oder Dienstleistungen nicht eingehalten werden kann, weil sie längere Vorlaufzeiten haben, werden diese Zeilen mit einem späteren Lieferdatum erstellt, um dies zu berücksichtigen.

1.  Erweitern Sie den Abschnitt **Verwaltung**. Im Feld **Auftraggeber** können Sie angeben, wer den Auftrag erteilt. 

    > **Hinweis:** Es kann zweckmäßig sein, dem Kreditor diese Information mitzuteilen, falls er diese Person kontaktieren muss. Der Wert kann automatisch zugewiesen werden, wenn das aktuelle Benutzerkonto einem **Personendatensatz** auf der Seite **Benutzer** zugeordnet ist. 

1.  Klicken Sie auf **OK**. 

1.  Der Auftragskopf wurde nun erstellt. Wenn Sie mit Bestellpositionen arbeiten, wird nur eine Zusammenfassung der Kopfzeileninformationen angezeigt. Wenn Sie den Rest der Informationen anzeigen möchten, wählen Sie die Registerkarte **Kopfzeile** aus. 

    ![Bildschirmbild mit der Position des Kopfzeilenmenüs](./media/lp1-m3-purchase-order-header-option.png)

1.  Wählen Sie unter **Bestellzeilen** auf der Symbolleiste das Menü **Bestellzeile** aus. 

    ![Bildschirmbild mit der Position der Menüoption „Bestellposition“](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1.  Wählen Sie unter **DISPLAY** **Dimensionen** aus. 

    > **Hinweis:** Produkte können in Varianten vorliegen, die sich nach Dimensionen wie Farbe, Größe oder Stil unterscheiden. Produkte können auch so eingerichtet werden, dass sie Lagerdimensionen wie Standort und Lager verwenden. Es gibt auch optionale Rückverfolgungsangaben wie Chargen- und Seriennummern. Um die Effizienz der Auftragserfassung zu verbessern, können Sie die üblicherweise verwendeten Dimensionsfelder direkt zum Auftragsraster hinzufügen. 

1.  Wählen Sie im **Anzeigebereich Dimensionen** unter **PRODUKTDIMENSIONEN** **Farbe** aus. 

1.  *Optional:* Wenn Sie den Umschalter **Einstellungen speichern** aktivieren, werden die von Ihnen ausgewählten Dimensionen beim nächsten Öffnen der Bestellseite auch im Raster der Bestellposition angezeigt. 

1.  Klicken Sie auf **OK**. 

1.  Wählen Sie unter **Bestellzeilen** das Feld **Artikelnummer** und **T0004** aus. 

    > **Hinweis:** Denken Sie daran, dass Sie `T0004` auch in den **Filter** eingeben können, anstatt durch die Liste zu scrollen. 

    > **Hinweis:** Bestellpositionen werden für Produkte und Dienstleistungen durch Angabe einer **Artikelnummer** oder als Aufwand durch Angabe einer **Beschaffungskategorie** angelegt.
    > 
    > Die **Beschaffungskategorie** wird zum Hinzufügen von Zeilen verwendet, in denen beschaffte Artikel direkt als Aufwand erfasst werden, anstatt in den Bestand aufgenommen zu werden. Dies bedeutet, dass Sie, wenn Sie einen Einkauf verrechnen müssen, eine Bestellposition erstellen können, in der eine **Beschaffungskategorie** angegeben ist, anstatt eine Zeile mit einer **Artikelnummer** zu erstellen. Artikel können auch einer Beschaffungskategorie zugeordnet werden. In diesem Fall wird die Beschaffungskategorie nur zu Informationszwecken angezeigt. 

1.  Öffnen Sie das Menü **Farbe**, überprüfen Sie im Menü die verfügbaren Optionen und wählen Sie dann eine der Farben oder Farbkombinationen aus. 

    > **Hinweis:** **Standort** und **Lager** werden normalerweise mit Werten aus dem Bestellungskopf gefüllt. Es ist jedoch möglich, die Felder zu überschreiben, wenn einige Positionen an verschiedene Standorte geliefert werden müssen. 

1.  Geben Sie im Feld **Menge** den Wert `10` ein. 

    > **Hinweis:** Die **Menge** wird automatisch mit der **Mindestbestellmenge** für das **Produkt** aufgefüllt, wenn diese eingerichtet ist, oder mit dem Wert **1**. 

    > **Hinweis:** Weitere verfügbare Felder mit Zeilendetails: 
    >
    >    - **Einheit:** Zeigt die Maßeinheit für die bestellte Menge an. Normalerweise wird die Einheit automatisch von der Einkaufseinheit in den Produktstammdaten bereitgestellt. 
    >
    >    - **Preis je Einheit**: Enthält einen Wert aus einem Kaufvertrag oder einem Handelsvertrag. Es ist möglich, den Stückpreis in einzelnen Bestellpositionen zu ändern – beispielsweise wenn mit dem Kreditor ein eindeutiger Preis ausgehandelt wird. 
    >
    >    - **Rabatt**: Stellt einen Rabattbetrag pro Einheit dar. Dieser Rabatt reduziert daher den Stückpreis um den Rabatt. Dieser Rabatt wird normalerweise automatisch aus Kaufverträgen oder Handelsvereinbarungen geliefert. Es ist jedoch möglich, einzelne Zeilen zu überschreiben, wenn mit dem Kreditor eindeutige Rabatte ausgehandelt wurden. 
    >
    >    - **Rabattprozentsatz**: Bei Eingabe wird der Nettobetrag für die Zeile entsprechend reduziert. Der Rabattprozentsatz wird normalerweise automatisch aus Kaufverträgen oder Handelsvereinbarungen geliefert. Es ist jedoch möglich, einzelne Zeilen zu überschreiben, wenn mit dem Kreditor ein eindeutiger Rabattprozentsatz ausgehandelt wurde. 
    >
    >    - **Nettobetrag**: Berechnet aus anderen Feldern in der Zeile, einschließlich Menge, Stückpreis, Rabatt und Rabattprozentsatz. Es ist möglich, den Nettobetrag zu ändern, aber dann sind die Felder „Einstandspreis“, „Rabatt“ und „Rabattprozentsatz“ leer und wenn Sie zur Zeile buchen, ist der gebuchte Betrag proportional zum Nettobetrag. Im Allgemeinen wird das Feld „Nettobetrag“ nur zur Anzeige des Nettobetrags der Zeile verwendet. 

1.  Erweitern Sie im Inforegister bei Bedarf **Zeilendetails**, und wählen Sie die Registerkarte **Übermittlung** aus. 

    > **Hinweis:** Jeder Bestellposition kann ein eindeutiges **Lieferdatum** zugewiesen werden. Das Datum wird aus dem Feld **Lieferdatum** im Bestellkopf übernommen, Sie können es hier jedoch ändern. 

1.  Notieren Sie sich die **Bestellnummer**, und **schließen** Sie die Seite. 

1.  Verwenden Sie in der Listenansicht **Alle Bestellungen** den **Filter**, um Ihre neue Bestellung zu finden. 

1.  Wenn Sie fertig sind, **schließen** Sie die Seite **Alle Bestellungen**, und kehren Sie zur Startseite zurück. 

