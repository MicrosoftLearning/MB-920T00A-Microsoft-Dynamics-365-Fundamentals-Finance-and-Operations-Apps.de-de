---
lab:
  title: "Lab\_2.1: Erstellen eines Hauptkontos"
  module: 'Learning Path 2: Learn the fundamentals of Microsoft Dynamics 365 Finance'
---

# Lernpfad 2: Grundlagen von Microsoft Dynamics 365 Finance
# Modul 2: Beschreiben der Finanzbuchhaltung

## Lab 2.1: Erstellen eines Hauptkontos

## Lab-Einrichtung

   - **Geschätzte Dauer**: 5 Minuten

## Ziel

In diesem Lab führen Sie die folgenden Aktivitäten aus:

1. Erstellen einer juristischen Person

2. Erstellen eines Geschäftskalenders

3. Erstellen eines Kontenplans

4. Erstellen Sie Hauptkonten im Kontenplan.

5. Erstellen Sie eine Organisationseinheit vom Typ „Abteilung“ und „Kostenstelle“.

6. Erstellen Sie eine Buchhaltungsstruktur mithilfe der Hauptkonten und Kostenstellen.

7. Konfigurieren des Sachkontos

# Übungsschritte

## Juristische Person erstellen

1. Wählen Sie im linken Navigationsbereich von Dynamics 365 Finance **Module****&gt;****Verwaltung von Organisationen****&gt; Organisationen &gt;Rechtspersonen** aus.

2. Wählen Sie auf der Seite **Juristische Personen** im Aktionsbereich die Schaltfläche **Neu**, um eine neue juristische Person anzulegen, und geben Sie die folgenden Informationen ein:

    - Name: **Contoso Demo Systems**

    - Unternehmen: **CDS**

    - Land/Region: **USA**

3. Wählen Sie **OK** am unteren Rand.

## Erstellen eines Geschäftskalenders

1. Wählen Sie im linken Navigationsbereich von Dynamics 365 Finance **Module****&gt;****Hauptbuch****&gt;Kalender &gt;Geschäftskalender**. 

2. Wählen Sie auf der Seite **Geschäftskalender** im Aktionsbereich die Schaltfläche **Neuer Kalender**, um einen neuen Geschäftskalender zu erstellen, und geben Sie die folgenden Informationen ein:

    - Kalender: **CDS**

    - Beschreibung: **Demosysteme Kalender**

    - Beginn des Geschäftsjahres: **30.9.2024**

    - Ende des Geschäftsjahres: **1.10.2024**

    - Name des Geschäftsjahres: **2024–25**

    - Länge der Periode: **1**

    - Einheiten: **Monate**

3. Wählen Sie die Schaltfläche **Erstellen**.

Das System generiert 14 Zeiträume, einschließlich eines Eröffnungszeitraums und eines Abschlusszeitraums und 12 Zeiträume für 12 Monate.

## Kontenplan erstellen

1. Wählen Sie im linken Navigationsbereich von Dynamics 365 Finance **Module** > **Finanzbuchhaltung****&gt;****Kontenplan****&gt; Konten &gt;Kontenplan**.

2. Wählen Sie auf der Seite **Kontenplan** im Aktionsbereich die Schaltfläche **Neu**, um einen neuen Kontenplan zu erstellen, und geben Sie die folgenden Informationen ein:

    - **Kontenpläne**: Demosysteme

    - **Beschreibung**: Contoso-Demosysteme

3. Wählen Sie die Schaltfläche **Neu** im Inforegister **Hauptkonten**, um Hauptkonten mit den folgenden Werten zu erstellen:

    - Hauptkonto: **1000**

    - Name: **Bargeld**

    - Hauptausgabentyp: **Bilanz**

    - Hauptkontokategorie: **BARGELD**

    - DB/CR-Standard: **Debit**

4. Erstellen Sie ein weiteres Hauptkonto:

    - Hauptkonto: **3000**

    - Name: **Umsatzerlös**

    - Hauptkostentyp: **Umsatzerlös**

    - Hauptkontokategorie: **REV**

    - DB/CR-Standard: **Debit**

5. Erstellen Sie ein weiteres Hauptkonto:

    - Hauptkonto: **6000**

    - Name: **Reisekosten**

    - Hauptkostentyp: **Expense**

    - Hauptkontokategorie: **EXP**

    - DB/CR-Standard: **Debit**

##  Eine Organisationseinheit erstellen

1. Navigieren Sie zu **Module****&gt;****Organisationsverwaltung****&gt; Organisationen &gt;Organisationseinheiten**.

2. Wählen Sie im Aktionsbereich die Schaltfläche **Neu**, gefolgt vom Typ **Betriebseinheit** und geben Sie den folgenden Wert ein:

    - Name: **CDS_Training**

3. Wählen Sie im Aktionsbereich die Schaltfläche „Neu“ gefolgt vom Typ „Kostenstelle“ aus, und geben Sie folgenden Wert ein:

    - Name: **CDS_Purchase**

4. Fügen Sie zwei weitere Kostenstellen hinzu: **CDS_IT** und **CDS_Admin**.

## Erstellen einer Buchhaltungsstruktur

1. Vergewissern Sie sich auf der Startseite **Finanzen und Betriebsabläufe** oben rechts, dass Sie mit dem Unternehmen **CDS** arbeiten.

2. Wählen Sie ggf. das Unternehmen aus und wählen Sie im Menü **CDS**.

3. Wählen Sie im linken Navigationsbereich von Dynamics 365 Finance **Module** > **Finanzbuchhaltung****&gt;****Kontenplan &gt;Strukturen &gt;Kontenstrukturen konfigurieren**.

4. Wählen Sie im Aktionsbereich die Schaltfläche **Neu**, um eine neue Kontenstruktur mit den folgenden Werten zu erstellen:

    - Kontostruktur: **CDS_BS**

    - Beschreibung: **CDS-Bilanz**

    - Hauptkonto hinzufügen: **JA**

5. Wählen Sie die Schaltfläche **Erstellen**.

6. Wählen Sie im Inforegister **Segmente und zulässige Werte** die Schaltfläche **Hinzufügen**, um den **Hauptkontobereich 1000..2999** hinzuzufügen.

7. Wählen Sie die Schaltfläche **Aktivieren** im Aktionsbereich und anschließend die Schaltfläche **Aktivieren** im Batchverarbeitungsdialog.

8. Wählen Sie im Aktionsbereich der Seite **Kontenstrukturen** die Schaltfläche **Neu**, um eine weitere Kontenstruktur mit den folgenden Werten anzulegen:

    - Kontostruktur: **CDS_Revenue**

    - Beschreibung: **CDS-Umsatz**

    - Hauptkonto hinzufügen: **JA**

9. Wählen Sie die Schaltfläche **Erstellen**.

10. Wählen Sie im Inforegister **Segmente und zulässige Werte** die Schaltfläche **Hinzufügen**, um den **Hauptkontobereich 3000..5999** hinzuzufügen.

11. Wählen Sie die Schaltfläche **Aktivieren** im Aktionsbereich und anschließend die Schaltfläche **Aktivieren** im Batchverarbeitungsdialog.

12. Wählen Sie im Aktionsbereich der Seite **Kontenstrukturen** die Schaltfläche **Neu**, um eine weitere Kontenstruktur mit den folgenden Werten zu erstellen:

    - Kontostruktur: **CDS_Expense**

    - Beschreibung: **CDS-Ausgaben**

    - Hauptkonto hinzufügen: **JA**

13. Wählen Sie die Schaltfläche **Erstellen**.

14. Wählen Sie im Inforegister **Segmente und zulässige Werte** die Schaltfläche **Hinzufügen**, um den **Hauptkontobereich 6000..9999** hinzuzufügen.

15. Wählen Sie die Schaltfläche **Segment** im Inforegister **Segmente und zulässige Werte**.

16. m Dialog **Segment hinzufügen** wählen Sie **Kostenstelle** und anschließend die Schaltfläche **Segment hinzufügen**.

17. Geben Sie in das Feld **Kostenstelle** **253..255** ein. 

18. Wählen Sie die Schaltfläche **Aktivieren** im Aktionsbereich und anschließend die Schaltfläche **Aktivieren** im Batchverarbeitungsdialog.

## Konfigurieren des Ledgers

1. Vergewissern Sie sich auf der Startseite **Finanzen und Betriebsabläufe** oben rechts, dass Sie mit dem Unternehmen **CDS** arbeiten.

2. Wählen Sie ggf. das Unternehmen aus und wählen Sie im Menü **CDS**.

3. Wählen Sie im linken Navigationsbereich von Dynamics 365 Finance **Module** > **Finanzbuchhaltung &gt;Einrichten &gt;Sachkonto-Seite** und konfigurieren Sie Folgendes:

    - Kontenplan: **Demosysteme**

    - Geschäftskalender: **CDS**

    - Buchhaltungswährung: **USD**

    - Berichtswährung: **USD**

    - Wechselkurstyp der Buchhaltungswährung: **Standard**

    - Budget-Wechselkurstyp: **Budget**

4. Wählen Sie im Inforegister **Kontenstruktur** die Schaltfläche **Hinzufügen**, um die Kontenstruktur **CDS_BS** hinzuzufügen.

5. Fügen Sie zwei weitere Kontostrukturen hinzu: **CDS_Revenue** und **CDS_Expense**.

Dies schließt die Grundkonfiguration des Finanzbuchhaltungsmoduls ab. Sie können ihre Journalkonfiguration jetzt planen, um Journale zu buchen. 

 
