---
lab:
  title: 'Lab 1: Erstellen eines neuen Produkts'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Supply Chain Management'
ms.openlocfilehash: e8fad0a9ddf0787c57ee7b98ddc6ef8363832ffc
ms.sourcegitcommit: f825cf821d4b03ce60261e296c85eabbc643cc17
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/27/2022
ms.locfileid: "147425862"
---
# <a name="module-3-learn-the-fundamentals-of-microsoft-dynamics-365-supply-chain-management"></a>Modul 3: Grundlagen von Microsoft Dynamics 365 Supply Chain Management erlernen

## <a name="lab-1---create-a-new-product"></a>Lab 1: Erstellen eines neuen Produkts

## <a name="objectives"></a>Ziele

Im Unternehmen Contoso Entertainment System USA (USMF) müssen Sie einen neuen Artikel für eine neue Gehäusekonfiguration erstellen, die Sie bei einem Kreditor erwerben können.

## <a name="lab-setup"></a>Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## <a name="instructions"></a>Anweisungen

1. Überprüfen Sie auf der Finance and Operations-Startseite oben rechts, ob Sie mit dem USMF-Unternehmen zusammenarbeiten.

1. Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus.

1. Wählen Sie oben links das Hamburger-Menü **Navigationsbereich erweitern** aus.

1. Wählen Sie im Navigationsbereich **Module** > **Produktinformationsmanagement** und dann **Freigegebene Produkte** in der Kategorie **Produkte** aus.

1. Wählen Sie auf der Seite „Details“ im oberen Menü **+ Neu** aus.

1. Stellen Sie im Bereich „Neues freigegebenes Produkt“ im Menü **Produkttyp** sicher, dass **Artikel** ausgewählt ist.

1. Stellen Sie im Menü **Produktuntertyp** sicher, dass **Produkt** ausgewählt ist.

1. Wählen Sie das Menü **Rückverfolgungsgruppe** und dann **Keine** aus.

1. Geben Sie unter **IDENTIFIZIERUNG** in den Feldern **Produktnummer** und **Artikelnummer** die Nummer **GTL007** ein.

1. Geben Sie im Feld **Produktname** die Bezeichnung **Gehäuse 2** ein.

1. Wählen Sie unter **REFERENZGRUPPEN** das Menü **Lagersteuerungsgruppe** und dann **FIFO (First-In-First-Out)** aus.

1. Wählen Sie das Menü **Artikelgruppe** und dann **TV&Video** aus.

1. Wählen Sie das Menü **Lagerdimensionsgruppe** und dann **SiteWH** aus.

1. Überprüfen Sie unter **MASSEINHEITEN**, dass die folgenden Werte eingestellt sind:

    | **Einstellung**| **Wert**|
    | :--- | :--- |
    | Bestandseinheit| in Stück|
    | Bestelleinheit| in Stück|
    | Verkaufseinheit| in Stück|
    | Stücklisteneinheit| in Stück|

1. Wählen Sie unter **MEHRWERTSTEUER** das Menü **Artikel-Mehrwertsteuergruppe** und dann **ALLE** aus.

1. Wählen Sie unter **BESTEUERUNG VON EINKÄUFEN** das Menü **Artikel-Mehrwertsteuergruppe** und dann **ALLE** aus.

1. Geben Sie unter PREISE im Feld „Einkaufspreis“ den Wert 30,00 ein.

1. Geben Sie im Feld „Verkaufspreis“ den Wert 30,00 ein.

1. Ihre neue Produktfreigabe sollte folgendermaßen aussehen:

    ![Bildschirmbild mit dem ausgefüllten Produktformular für neue Versionen](./media/lp1-m2-new-release-product.png)

1. Klicken Sie auf **OK**.

1. Wählen Sie auf der Menübandleiste unter **Verwalten** die Option **Überprüfen** aus, um sicherzustellen, dass das Produkt finalisiert wurde.

    ![Bildschirmbild mit der Menübandleiste mit hervorgehobener Überprüfung](./media/lp1-m2-validate-ribbon-bar.png)

1. Stellen Sie sicher, dass Ihnen das Informationsbanner angezeigt wird, das bestätigt, dass alle erforderlichen Feldwerte validiert wurden.

    ![Bildschirmbild der Benachrichtigung, dass alle erforderlichen Felder validiert wurden](./media/lp1-m2-confirmation-of-validation.png)

1. Schließen Sie alle Seiten, und kehren Sie zur Startseite zurück.
