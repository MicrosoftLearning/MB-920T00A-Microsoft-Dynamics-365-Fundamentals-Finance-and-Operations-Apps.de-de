---
lab:
  title: 'Lab 2: Excel-Integration'
  module: 'Module 1: Explore the core capabilities of Dynamics 365 finance and operations apps'
ms.openlocfilehash: e5929571477cfcdbb1b2e81c72ebc566a96c56a4
ms.sourcegitcommit: 8e5a278c6e08abdcc3fb719796f79842e868606b
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 07/14/2022
ms.locfileid: "147116296"
---
# <a name="module-1-explore-the-core-capabilities-of-dynamics-365-finance-and-operations-apps"></a>Modul 1: Erkunden der Kernfunktionen der Finanz- und Betriebs-Apps von Microsoft Dynamics 365

## <a name="lab-2---excel-integration"></a>Lab 2: Excel-Integration

Nachdem Sie sich mit den Finanz- und Betriebs-Apps vertraut gemacht haben, nehmen Sie sich etwas Zeit, um das Szenario zur Excel-Integration zu erkunden.

### <a name="task-1-create-template"></a>Aufgabe Nr. 1: Erstellen der Vorlage

1. Öffnen Sie die Homepage von Finance and Operations. 

2. Navigieren Sie zu **Module** > **Allgemein** > **Allgemein** > **Office-Integration** > **Excel-Arbeitsmappen-** **Designer**. Beachten Sie, dass die Navigation meistens über „Module“ erfolgt, sodass dies in der Regel nicht angegeben wird.

3. Suchen Sie im Filter nach **VendorGroup**.

4. Wählen Sie in der Liste der verfügbaren Felder die Felder **Kreditorengruppe**, **Beschreibung** und **Zahlungsbedingungen** aus, und verschieben Sie sie mit dem Pfeil nach rechts zu den ausgewählten Feldern.

5. Wählen Sie im Aktionsbereich die Schaltfläche **Arbeitsmappe erstellen** aus.

6. Wählen Sie rechts im Bereich **Speichern in** die Schaltfläche **Herunterladen** aus.

7. Laden Sie die Datei herunter, indem Sie **Speichern unter** auswählen und sie im Ordner **Downloads** speichern.

8. Navigieren Sie zu **Allgemein** > **Office-Integration** > ****Dokumentvorlagen****.

9. Wählen Sie **Neu** aus.

10. Wählen Sie im rechten Bereich im Abschnitt **Vorlage hochladen** die Schaltfläche **Durchsuchen** und dann die zuvor heruntergeladene Datei aus (wenn Sie den Standardnamen verwendet haben, heißt sie „DynamicsWorkbook“).

11. Geben Sie im Feld **Vorlagenname** die Zeichenfolge **CustomVendorGroup** ein.

12. Wählen Sie **OK** und anschließend **Speichern** aus.

### <a name="task-2-open-in-excel"></a>Aufgabe Nr. 2: In Excel öffnen

1. Navigieren Sie zu **Beschaffung** > **Einrichten** > **Kreditoren** > **Kreditorengruppen**.

2. Wählen Sie **In Microsoft Office öffnen** > **In Excel öffnen** aus, um die neue Vorlage „CustomVendorGroup“ zu suchen, die Sie hochgeladen haben.

3. Wählen Sie **CustomVendorGroup** aus, und laden Sie die Excel-Vorlage herunter.

4. Speichern Sie die heruntergeladene Excel-Vorlage, und öffnen Sie sie dann. Erlauben Sie bei Bedarf die Aktion „Schließen“, und wählen Sie **Bearbeitung aktivieren** aus. Stufen Sie dieses Add-In als vertrauenswürdig ein, und melden Sie sich dann an (mit denselben Anmeldeinformationen, sofern Sie gefragt werden).

Alle in der Tabelle „Kreditorengruppe“ enthaltenen Daten werden in der Excel-Tabelle angezeigt.

5. Geben Sie einen neuen Datensatz ein.

6. Geben Sie **100** im Feld **Kreditorengruppe**, **Insurance Vendor** (Versicherungsanbieter) im Feld **Beschreibung** und **Net10** im Feld **Zahlungsbedingungen** ein.

7. Wählen Sie die Schaltfläche **Veröffentlichen** in der Office-Add-In-App von Microsoft Dynamics aus.

8. Öffnen Sie das Formular **Kreditorengruppe**, um zu überprüfen, ob der neue Datensatz hinzugefügt wurde.

