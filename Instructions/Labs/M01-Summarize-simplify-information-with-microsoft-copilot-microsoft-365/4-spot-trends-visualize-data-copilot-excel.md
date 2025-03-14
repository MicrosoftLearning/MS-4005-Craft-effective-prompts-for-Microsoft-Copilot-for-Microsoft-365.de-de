# Erkennen von Trends und Visualisieren von Daten mit Copilot in Excel

Microsoft 365 Copilot in Excel unterstützt Sie bei der Arbeit mit Daten in Excel-Tabellen. Sie können mit Microsoft Copilot Formelspaltenvorschläge erstellen, Erkenntnisse in Diagramme und PivotTables anzeigen und interessante Datenabschnitte hervorheben.

Wählen Sie in Excel **Copilot**  im Menüband aus, um den Chatbereich zu öffnen.

![Screenshot des Copilot-Symbols im Excel-Menüband.](../media/summarize_copilot-ribbon-excel.png)

Um Copilot in Excel zu verwenden, müssen Ihre Daten auf eine der folgenden Arten formatiert werden:

- Als Excel-Tabelle
- Als Unterstützungsbereich

Sie können eine Tabelle erstellen oder einen Zellbereich in eine Tabelle umwandeln, wenn Sie über einen Datenbereich verfügen. Gehen Sie dazu wie folgt vor:

1. Markieren Sie die Zelle oder den Bereich in den Daten.

1. Wählen Sie  **Startseite > Als Tabelle formatieren**.

1. Aktivieren Sie im Dialogfeld  **Als Tabelle formatieren**  das Kontrollkästchen neben  **Meine Tabelle hat Header** , wenn die erste Zeile des Bereichs der Header sein soll.

1. Wählen Sie **OK** aus.

Wenn Sie Ihre Daten lieber in einem Bereich aufbewahren und nicht in eine Tabelle konvertieren möchten, muss sie alle folgenden Anforderungen erfüllen:

- Nur eine Kopfzeile
- Die Kopfzeilen sollten sich nur in Spalten befinden, nicht in Zeilen
- Kopfzeilen sollten eindeutig sein, keine doppelten Kopfzeilen
- Keine leeren Kopfzeilen
- Daten sollten auf konsistente Weise formatiert werden
- Keine Teilergebnisse
- Keine leeren Zeilen oder Spalten
- Keine verbundenen Zellen

Im folgenden Beispiel beginnen wir mit einer grundlegenden Anfrage zur Analyse einer Tabelle und fügen nach und nach Elemente hinzu, um den Prompt robuster zu machen.

![Screenshot des Copilot-Bereichs in Excel beim ersten Öffnen.](../media/summarize_copilot-pane-excel.png)

## Lassen Sie uns loslegen

Laden Sie zunächst **_[Contoso Chai Tea market trends 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)_** herunter und speichern Sie die Datei in Ihrem **OneDrive Ordner**, falls Sie dies noch nicht getan haben.

Öffnen Sie die Tabelle in Excel und öffnen Sie dann den Bereich **Copilot**, indem Sie das Copilot-Symbol in der Registerkarte **Startseite** der Menüleiste auswählen. Geben Sie die folgenden Prompts ein und folgen Sie den Anweisungen.

> [!NOTE]
> Prompt wird gestartet:
>
> _Analysiere diese Tabelle in Excel._

In dieser einfachen Eingabeaufforderung beginnen Sie mit dem grundlegenden **Ziel**: _eine Excel-Tabelle analysieren zu lassen._ Es gibt jedoch keine Informationen darüber, warum die Tabelle zusammengefasst werden muss oder wofür die Zusammenfassung erforderlich ist.

| Element | Beispiel |
| :------ | :------- |
| **Grundlegender Prompt:** Beginnen Sie mit einem **Ziel** | **Analysiere diese Tabelle in Excel.** |
| **Guter Prompt:** Hinzufügen von **Kontext** | Das Hinzufügen von **Kontext** kann Copilot dabei helfen, den Zweck der Analyse zu verstehen und die Antwort entsprechend anzupassen. _„Wir suchen die meistverkauften Produkte von Mai bis August für den Verkauf von traditionell hergestelltem oder vorgefertigtem Chai.“_ |
| **Besserer Prompt:** Angabe von **Quelle(n)** | Das Hinzufügen von **Quellen** kann Copilot helfen, den Bereich einzugrenzen, indem Sie bestimmte Informationen oder Bereiche verwenden. _„… von Mai bis August für den Verkauf von traditionell hergestelltem oder vorgefertigtem Chai.“_ |
| **Bester Prompt:** Festlegen von **Erwartungen** | Schließlich kann das Hinzufügen von **Erwartungen** Copilot dabei helfen, zu verstehen, wie die Zusammenfassung gestaltet werden soll und wie detailliert sie sein muss. _„Bitte fasse das Top-Verkaufsprodukt für jeden Store und jeden Monat zusammen.“_ |

> [!NOTE]
> **Gestaltete Eingabeaufforderung:**
>
> _Analysiere diese Tabelle in Excel. Wir suchen die meistverkauften Produkte von Mai bis August für den Verkauf von handwerklich hergestelltem Chai oder vorgefertigtem Chai. Bitte fasse das meistverkaufte Produkt für jeden Monat zusammen._

Dieser Prompt gibt Copilot alles, was benötigt wird, um eine gute Antwort zu finden, einschließlich **Ziel**, **Kontext**, **Quelle** und **Erwartungen**.

## Mehr entdecken

Probieren Sie den finalen Prompt und andere mit Ihrer eigenen Excel-Tabelle aus. Hier sind einige Vorschläge für Prompts, die Sie ausprobieren können. Kopieren Sie sie und fügen Sie **Kontext**, **Quellen** und **Erwartungen** hinzu.  

- Verkaufszahlen nach Kategorie im Zeitverlauf.

- Zeige den Gesamtumsatz für jedes Produkt an.

- Zeige die Gesamtsumme der Werbeverkäufe für jede Region im letzten Jahr an.

> [!IMPORTANT]
> Diese Funktion steht Kundschaft mit einer Microsoft 365 Copilot-Lizenz oder Copilot Pro-Lizenz zur Verfügung. Weitere Informationen zu Excel-Tabellen und deren Erstellung finden Sie unter [Erstellen einer Tabelle in Excel](https://support.microsoft.com/office/bf0ce08b-d012-42ec-8ecf-a2259c9faf3f).
