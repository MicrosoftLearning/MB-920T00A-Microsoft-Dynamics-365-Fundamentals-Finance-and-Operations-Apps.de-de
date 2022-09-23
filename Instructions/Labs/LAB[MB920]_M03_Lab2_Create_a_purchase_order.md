---
lab:
  title: "Lab\_2: Bestellung erstellen"
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
---

# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modul 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management erlernen

## <a name="lab-2---create-a-purchase-order"></a>Lab 2: Erstellen einer Bestellung

## <a name="objectives"></a>Ziele

It's more typical for purchase orders to be created automatically as result of master planning, direct delivery, and other processes. When created manually, a purchase order is usually created by a purchasing agent. Create a purchase order using the the USMF company.

## <a name="lab-setup"></a>Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## <a name="instructions"></a>Anweisungen

1. Überprüfen Sie auf der Finance and Operations-Startseite oben rechts, ob Sie mit dem USMF-Unternehmen zusammenarbeiten.

1. Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus.

1. Wählen Sie oben links das Hamburger-Menü **Navigationsbereich erweitern** aus.

1. Wählen Sie **Module** > **Beschaffung** > **Bestellungen** > **Alle Bestellungen** aus.

1. Wählen Sie auf der Seite „Alle Bestellungen“ im oberen Menü die Option **+ Neu** aus.

1. Wählen Sie im Bereich „Bestellung anlegen“ das Menü **Kreditorenkonto** und dann **US-101** aus.

1. When you select a vendor, details from the vendor record, such as address, invoice account, delivery terms, and delivery mode, will be copied as default values into the order header. You can change these values at any time.

1. Erweitern Sie den Abschnitt **Allgemein**.

1. Wählen Sie unter **LAGERDIMENSIONEN** das Menü **Standort** aus und überprüfen Sie die Liste der Standorte.

1. The Site field, together with the Warehouse field, specifies where the procured goods or services must be delivered. The default delivery address is the site. Both fields can be populated with values set up for the selected vendor, or you can specify them manually.

1. Unter **TERMINE** wird das Feld Lieferdatum verwendet, um festzulegen wann beschaffte Waren und Dienstleistungen geliefert werden müssen.

1. You can specify a single delivery date for the order, or the individual order lines can be given unique delivery dates. If the delivery date specified here cannot be met for specific products or services because they have longer lead times, then those lines will be created with a later delivery date to accommodate for this.

1. Expand the <bpt id="p1">**</bpt>Administration<ept id="p1">**</ept> section. The <bpt id="p1">**</bpt>Orderer<ept id="p1">**</ept> box can be used to specify who is placing the order.

1. Typischer ist es, dass Bestellungen automatisch als Ergebnis von Produktprogrammplanung, Direktlieferung und anderen Prozessen erstellt werden.

1. Klicken Sie auf **OK**.

1. Bei der manuellen Erstellung einer Bestellung wird sie normalerweise von einem Einkaufsvertreter erstellt.

    ![Bildschirmbild mit der Position des Kopfzeilenmenüs](./media/lp1-m3-purchase-order-header-option.png)

1. Wählen Sie unter **Bestellpositionen** im Menü die Option **Bestellposition** aus.

    ![Bildschirmbild mit der Position der Menüoption „Bestellposition“](./media/lp1-m3-purchase-order-purchase-order-line-menu.png)

1. Wählen Sie unter **DISPLAY** **Dimensionen** aus.

1. Erstellen Sie eine Bestellung unter Verwendung des USMF-Unternehmens.

1. Wählen Sie im Anzeigebereich Dimensionen unter **PRODUKTDIMENSIONEN** das Kontrollkästchen **Farbe** aus.

1. Optional: Wenn Sie den Umschalter „Einstellungen speichern“ auswählen, werden die von Ihnen ausgewählten Dimensionen beim nächsten Öffnen der Bestellseite auch im Raster der Bestellposition angezeigt.

1. Klicken Sie auf **OK**.

1. Wählen Sie das Zellenmenü **Artikelnummer** und dann **T0004** aus.

1. Denken Sie daran, dass Sie auch das Filterfeld eingeben können, anstatt durch die Liste zu scrollen.

1. Bestellpositionen werden für Produkte und Dienstleistungen durch Angabe einer Artikelnummer oder als Aufwand durch Angabe einer Beschaffungskategorie angelegt.

1. Procurement category is used for adding lines where procured items are expensed directly, rather than going into inventory. This means that if you need to expense a purchase, you can do this by creating a purchase order line that specifies a procurement category, rather than creating a line with an item number. Items can also be associated with a procurement category and in this case, the procurement category is shown as informational only.

1. Öffnen Sie das Menü **Farbe**, überprüfen Sie im Menü die verfügbaren Optionen und wählen Sie dann eine der Farben oder Farbkombinationen aus.

1. Standort und Lager werden normalerweise mit Werten aus dem Auftragskopf gefüllt. Es ist jedoch möglich, die Felder zu überschreiben, wenn einige Zeilen an verschiedene Standorte geliefert werden müssen.

1. Geben Sie im Feld **Menge** **10** ein.

1. Die Menge wird automatisch mit der Mindestbestellmenge für das Produkt gefüllt, wenn diese eingerichtet ist, oder mit dem Wert „1“.

1. Weitere Informationen:

    - <bpt id="p1">**</bpt>Unit<ept id="p1">**</ept>: Indicates the unit of measure for the ordered quantity. Normally, the unit is automatically provided from the purchasing unit on the product master data.

    - <bpt id="p1">**</bpt>Unit price<ept id="p1">**</ept>: Contains a value from either a purchase agreement or a trade agreement. It is possible to change the unit price on individual order lines—for example, if a unique price is negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount<ept id="p1">**</ept>: Represents a discount amount per unit. This discount therefore reduces the unit price by the discount. This discount is commonly supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if unique discounts have been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Discount percentage<ept id="p1">**</ept>: When entered, this reduces the net amount for the line accordingly. The discount percent is often supplied automatically from purchase agreements or trade agreements, but it is possible to override on individual lines if a unique discount percentage has been negotiated with the vendor.

    - <bpt id="p1">**</bpt>Net amount<ept id="p1">**</ept>: Calculated from other fields on the line, including quantity, unit price, discount, and discount percent. It is possible to change the Net amount, but then the Unit Price, Discount, and Discount percent fields will be blank, and when you post toward the line, the amount posted will be proportional to the net amount. Generally, the Net Amount field is only used for displaying the net amount of the line.

1. Wählen Sie unter den Bestellpositionen unten auf der Seite die Option **Positionsdetails** aus.

1. Wählen Sie die Registerkarte **Lieferung** aus.

1. A unique delivery date can be assigned to each order line. The date is inherited from the field on the purchase order header, but you can change this.

1. Schließen Sie die Seite „Bestellposition“.

1. Verwenden Sie auf der Seite „Alle Bestellungen“ die Filterfunktion und suchen Sie Ihre neue Bestellung.

1. Wenn Sie fertig sind, schließen Sie die Seite „Alle Bestellungen“ und kehren Sie zur Startseite zurück.
