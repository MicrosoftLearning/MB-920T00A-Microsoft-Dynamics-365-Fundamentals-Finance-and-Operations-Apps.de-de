---
lab:
  title: 'Lab 1: Rabattprodukt erstellen'
  module: 'Module 3: Learn the Fundamentals of Microsoft Dynamics 365 Commerce'
ms.openlocfilehash: 2d3a61398c6184a9b43e2fd0da9d28cb55f55ee5
ms.sourcegitcommit: 252458fca8e71b6e5e8b99ae4c2b47cd85461a30
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 01/27/2022
ms.locfileid: "137910012"
---
## <a name="lab-1---create-a-discount-product"></a>Lab 1 – Rabattprodukt erstellen

## <a name="objectives"></a>Ziele

Die Bostoner Filiale Ihres Unternehmens ist bereit, den Verkauf einiger Produkte zu fördern, die verkauft werden müssen, um Platz für die neue Position zu schaffen. Sie müssen einen neuen Produktrabatt erstellen und aktivieren.

## <a name="lab-setup"></a>Lab-Einrichtung

   - **Geschätzte Dauer**: 10 Minuten

## <a name="instructions"></a>Anweisungen

1. Wählen Sie oben links auf der Finance and Operations-Seite das Hamburger-Menü **Navigationsbereich erweitern** aus.

1. Wählen Sie im Navigationsbereich **Arbeitsbereiche** > **Preis- und Rabattmanagement** aus.

1. Überprüfen Sie auf der Seite „Preis- und Rabattverwaltung“ **Aktive Rabatte**, die aktuell angezeigt werden.

1. Wählen Sie im Menü die Option **Neu** aus, überprüfen Sie die verfügbaren Optionen, und klicken Sie dann auf **Rabatt**.

1. Geben Sie im Feld **Name** auf der Seite Rabatte einen Namen für Ihren Rabatt ein. Zum Beispiel „Neujahr 20 %“.

1. Überprüfen Sie auf der Registerkarte „Allgemein“, ob der Status auf **Deaktiviert** gesetzt ist.

1. Der Rabatt kann nur bearbeitet werden, wenn er deaktiviert ist.

1. Wählen Sie das Menü **Modus für Rabattparallelität** aus, überprüfen Sie die verfügbaren Optionen, und klicken Sie dann auf **Bester Preis**.

    >[!NOTE] Beachten Sie bei der Auswahl zwischen den Optionen für den Modus für Rabattparallelität Folgendes:
    >
    >  - Wenn mehrere zusammengesetzte Rabatte gelten, wird immer zuerst der höchste Rabatt berechnet.  Der nächsthöhere Rabatt wird dann auf den Restbetrag berechnet.  Diese Berechnungshierarchie wird fortgesetzt, bis alle anwendbaren zusammengesetzten Rabatte angewendet wurden.  
    >    **Richtig:** 40 % Rabatt + 20 % Rabatt = 52 % Rabatt  
    >      - (40 % Rabatt auf 100 $ = 40 $. Verbleibend = 60 $.  20 % Rabatt auf 60 $ = 12. Verbleibend = 48 $)  
    >
    >    **Nicht richtig**: 40 % Rabatt + 20 % Rabatt = 60 % Rabatt
    >
    >  - Exklusive Rabatte gelten immer für einen besten Preis oder einen zusammengesetzten Rabatt, selbst wenn dies der niedrigste Rabattprozentsatz ist.
    >    - Wenn mehr als ein exklusiver Rabatt gilt, wird der höchste Rabatt verwendet.
    >  - Wenn sowohl „Bester Preis“ als auch „Zusammengesetzt“ anwendbar sind oder wenn mehrere derselben gelten, wird der höchste Rabatt verwendet.

1. Wählen Sie das Menü **Skontokonto** aus, und überprüfen Sie die Liste.

1. Geben Sie im Feld „Skontokonto“ **Rabatt** ein.

1. Die Liste wird automatisch gefiltert.

1. Wählen Sie in den Ergebnissen die Skontokontonummer **403200** aus.

1. Überprüfen Sie die anderen Optionen, und erweitern Sie **Details**.

1. Geben Sie im Feld **Beschreibung** eine Beschreibung für den Rabatt ein. Zum Beispiel „Neujahrsrabatt von 20 %“

1. Erweitern Sie **Preis/Rabatt**.

1. Geben Sie im Feld „Rabattprozentsatz“ den Wert **20,00** ein.

1. Erweitern Sie **Prüfungszeitraum**.

1. Richten Sie das **Gültigkeitsdatum** und das **Ablaufdatum** für den Rabatt ein.

1. Stellen Sie sicher, dass Sie das Ablaufdatum in der Zukunft festlegen, da sonst der Rabatt nicht in der Liste der aktiven Rabatte angezeigt wird.

1. Erweitern Sie **Positionen**.

1. Wählen Sie im Menü **+ Hinzufügen** aus.

1. Wählen Sie das Menü **Kategorie** und dann **Mode (Mode)** aus.

1. Dadurch gilt der Rabatt für alle Produkte in der Kategorie Mode.

1. Erweitern Sie **Positionen**, und geben Sie dann im Feld **Beschreibung** eine Beschreibung für die Produktlinien ein. Beispielsweise sind alle Produkte in der Kategorie Mode im Rabatt enthalten.

1. Wählen Sie oben auf der Seite im Menü **Preisgruppen** aus.

1. Wählen Sie auf der Seite „Preisgruppen“ das Menü **Preisgruppe** aus.

1. Überprüfen Sie die verfügbaren Preisgruppen und wählen Sie **Boston Preisgruppe** und dann **Speichern** aus.

1. Wählen Sie oben rechts auf der Seite „Preisgruppen“ das Symbol **Schließen** aus.

1. Wählen Sie auf der Seite „Rabatte“ auf der Registerkarte „Details“ das Menü **Status** und dann **Aktiviert** aus.

1. Beachten Sie, dass Rabatteinstellungen nicht mehr bearbeitet werden können.

1. Speichern Sie Ihre Änderungen, und schließen Sie die Rabattseite.

1. Überprüfen Sie auf der Seite „Preis- und Rabattverwaltung“ die Registerkarte „Aktive Rabatte“, und stellen Sie sicher, dass Ihr neu hinzugefügter Rabatt am Ende der Liste angezeigt wird.

1. Wählen Sie bei Bedarf oben rechts das Symbol **Aktualisieren** zum Aktualisieren der Rabattliste aus.
