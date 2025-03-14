# Formatieren, Sortieren, Filtern und Hervorheben von Daten mit Microsoft 365 Copilot in Excel

Mit Microsoft Copilot 365 können Sie in Excel-Tabellen leicht etwas hervorheben, Daten sortieren und filtern, um schnell auf das Wesentliche aufmerksam zu machen. Verwenden Sie Copilot mühelos in einer einzelnen Tabelle:

- Sortieren und Filtern von Daten.

- Einfache bedingte Formatierung anwenden.

Um zu beginnen, formatieren Sie Ihre Daten in einem [unterstützten Format](https://support.microsoft.com/topic/format-data-for-copilot-in-excel-1604c8eb-57f1-4db1-8363-d53336228c65) und wählen Sie die Schaltfläche **Copilot** in der Multifunktionsleiste aus. Teilen Sie Copilot dann mit, wie die Tabelle bearbeitet werden soll, damit bestimmte Daten besser angezeigt werden.

Im folgenden Beispiel beginnen wir mit einem einfachen Prompt und fügen nach und nach Elemente hinzu. Folgen Sie dem Beispiel mit Ihren eigenen Daten.

## Lassen Sie uns loslegen

Laden Sie zunächst **_[Fabrikam Q1 marketing campaigns.xlsx](https://go.microsoft.com/fwlink/?linkid=2269124)_** herunter und speichern Sie die Datei in Ihrem **OneDrive-Ordner**, falls Sie dies noch nicht getan haben.

Öffnen Sie die Tabelle in Excel und öffnen Sie dann den Bereich **Copilot**, indem Sie das Copilot-Symbol in der Registerkarte **Startseite** der Menüleiste auswählen. Geben Sie die folgenden Prompts ein und folgen Sie den Anweisungen.

> [!NOTE]
> Prompt wird gestartet:
>
> _Sortiere diese Tabelle._

In diesem einfachen Prompt beginnen Sie mit dem grundlegenden **Ziel**, _eine Excel-Tabelle zu sortieren und zu filtern_. Es gibt jedoch keine Angaben dazu, wie die Daten sortiert werden sollen und welches Feld Sie filtern möchten.

| Element | Beispiel |
| :------ | :------- |
| **Grundlegender Prompt:** Beginnen Sie mit einem **Ziel** | **_Sortiere diese Tabelle..._** |
| **Guter Prompt:** Hinzufügen von **Kontext** | Durch das Hinzufügen von **Kontext** kann Copilot besser verstehen, wozu die Folien dienen und auf welches Thema er sich konzentrieren soll. _„... um nach dem wirkungsvollsten Vertriebsmitarbeitenden zu suchen.“_ |
| **Besserer Prompt:** Angabe von **Quelle(n)** | Die **Quelle** für diesen Prompt wird als die Tabelle angenommen, mit der wir in Excel arbeiten. _„... diese Tabelle [Tabelle 1]...“_ |
| **Bester Prompt:** Festlegen von **Erwartungen** | Schließlich kann das Hinzufügen von **Erwartungen** Copilot dabei helfen, zu verstehen, wie Sie die Tabelle sortiert, gefiltert und dargestellt haben möchten. _„und hebe die besten und schlechtesten Kampagneninhabenden basierend auf dem Nettoumsatz hervor.“_ |

> [!NOTE]
> **Gestaltete Eingabeaufforderung:**
>
> _Sortiere diese Tabelle [Tabelle1], um die Verkaufsperson mit der größten Wirkung zu finden, und hebe die besten und schlechtesten Kampagneninhabenden basierend auf dem Nettoumsatz hervor._

Diese Eingabeaufforderung wird in mehreren Schritten mit der Eingabeaufforderungstechnik einer **Verkettung** ausgeführt. Sie fordern Copilot auf, sequenzielle Back-to-Back-Befehle auszuführen, um ein einzelnes Ziel zu erreichen.

**Erster Prompt**:

```text
Sort this table [Table1] to look for the most impactful salesperson.
```

**Zweiter Prompt**:

```text
highlight the top and bottom campaign owners based off of net revenue
```

Copilot hat alle Informationen, die er benötigt, um Ihnen eine solide Antwort zu geben, dank des **Ziels**, **Kontexts**, **Ursprungs** und **Erwartungen** in diesem Prompt.

## Mehr entdecken

Probieren Sie diese einfachen Eingabeaufforderungen aus, um Ihre Daten hervorzuheben, zu sortieren und zu filtern, und fügen Sie weitere Elemente hinzu, um Ihre Ergebnisse zu verbessern:

- Stellen Sie die obersten 10 Werte in der Spalte "Vertrieb" fett dar.

- Heben Sie die höchsten Werte der verkauften Einheiten hervor.

- Sortieren Sie die Kundenbindungsquote von der kleinstem zur größten Quote.  

- Filtern Sie nach Elementen, die in der nächsten Woche fällig sind.

> [!IMPORTANT]
> Copilot funktioniert nur bei Dateien, die auf OneDrive oder SharePoint gespeichert sind. Wenn Sie die Schaltfläche „Copilot“ in der Menüleiste nicht auswählen können, versuchen Sie zunächst, die Datei in der Cloud zu speichern. Weitere Informationen finden Sie unter [Hervorheben, Sortieren und Filtern von Daten mit Copilot in Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936).
