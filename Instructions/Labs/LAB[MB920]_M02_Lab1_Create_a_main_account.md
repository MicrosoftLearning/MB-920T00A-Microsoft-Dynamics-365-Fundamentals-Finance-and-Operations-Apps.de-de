---
lab:
  title: 'Lab 1: Erstellen eines Hauptkontos'
  module: 'Module 2: Learn the Fundamentals of Microsoft Dynamics 365 Finance'
---

# Modul 2: Grundlagen von Microsoft Dynamics 365 Finance erlernen

## Lab 1: Erstellen eines Hauptkontos

## Lab-Einrichtung

   - **Geschätzte Dauer**: 5 Minuten

## Anweisungen


1.  Überprüfen Sie auf der **Finance and Operations**-Startseite oben rechts, ob Sie mit dem **USMF**-Unternehmen arbeiten.

2.  Wählen Sie bei Bedarf das Unternehmen und im Menü **USMF** aus.

3.  Wählen Sie im Navigationsbereich links **Module** > **Hauptbuch** > **Kontenplan** > **Konten** > **Hauptkonten** aus.

4.  Wählen Sie im Aktionsbereich **+ Neu** aus.

5.  Geben Sie auf der Seite **Hauptkonto** die folgenden Werte ein:

    - Hauptkonto: **601510**

    - Name: **International call expense** (Internationale Anrufkosten)

    - Hauptkostentyp: **Expense**

    - Hauptkontokategorie: **TANDEEXP**

    - DB/CR-Standard: **Debit**

    ![Screenshot: Hauptkonten – Diagramm mit Konten: Freigegebene Seite, auf der verschiedene Werte hinzugefügt werden müssen](./media/lab-create-a-main-account-01.png)

6.  Navigieren Sie zu **Module &gt; Finanzbuchhaltung &gt; Journaleinträge &gt; Allgemeine Erfassungen**.

7.  Wählen Sie im Aktionsbereich **+ Neu** aus.

8.  Geben Sie auf der Seite **Allgemeine Erfassungen** den folgenden Wert ein, und wählen Sie im Aktionsbereich **Zeilen** aus:

    - Name: GenJrn

9.  Geben Sie auf der Seite **Vorerfasste Belege** die folgenden Werte ein:

    - Kontotyp: **Ledger**

    - Hauptkonto: **601510**

    - Debit: **10.00** 

    - Offsetkontotyp: **Ledger**

    - Offsetkontonummer: **110180** 

10. Wählen Sie im Aktionsbereich die Schaltfläche **Speichern** aus.

11. Navigieren Sie zu **Überprüfen &gt; Buchung simulieren**. 

12. Wählen Sie im Aktionsbereich die Schaltfläche **Buchen** aus. Das Journal sollte veröffentlicht werden.
