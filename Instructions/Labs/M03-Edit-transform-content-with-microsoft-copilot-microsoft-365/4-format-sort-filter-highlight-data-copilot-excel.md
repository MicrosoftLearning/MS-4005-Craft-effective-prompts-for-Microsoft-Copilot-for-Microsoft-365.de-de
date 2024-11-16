
Mit Microsoft Copilot 365 können Sie in Excel-Tabellen leicht etwas hervorheben, Daten sortieren und filtern, um schnell auf das Wesentliche aufmerksam zu machen. Verwenden Sie Copilot mühelos in einer einzelnen Tabelle: 

- Sortieren und Filtern von Daten.

- Einfache bedingte Formatierung anwenden.

Um zu beginnen, formatieren Sie die Daten als Tabelle und wählen im Menüband das Symbol **Copilot** aus. Teilen Sie Copilot dann mit, wie die Tabelle bearbeitet werden soll, damit bestimmte Daten besser angezeigt werden. 

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
| Einfacher Prompt: <br>Beginnen Sie mit einem **Ziel** | **_Sortiere diese Tabelle..._** |
| Guter Prompt: <br>**Kontext** hinzufügen | Durch das Hinzufügen von **Kontext** kann Copilot besser verstehen, wozu die Folien dienen und auf welches Thema er sich konzentrieren soll.<br><br>„_... um nach dem wirkungsvollsten Vertriebsmitarbeitenden zu suchen._“ |
| Besserer Prompt: <br>**Quelle(n)** angeben | Die **Quelle** für diesen Prompt wird als die Tabelle angenommen, mit der wir in Excel arbeiten.<br><br>„_... diese Tabelle [Tabelle 1]..._“ |
| Besserer Prompt: <br>Klare **Erwartungen** festlegen | Schließlich kann das Hinzufügen von **Erwartungen** Copilot dabei helfen, zu verstehen, wie Sie die Tabelle sortiert, gefiltert und dargestellt haben möchten.<br><br>„_Füge eine dritte Spalte hinzu, die den Nettoumsatz pro involvierter Person unter Berücksichtigung der Budgetkosten berechnet. Sortiere diese Tabelle in absteigender Reihenfolge nach dem Nettoumsatz pro involvierter Person und hebe die obersten und untersten Besitzer hervor._“ |

> [!NOTE]
> **Gestaltete Eingabeaufforderung:**
>
> _Sortiere diese Tabelle [Table1], um das effektivste Verkaufspersonal zu ermitteln. Füge eine dritte Spalte hinzu, die den Nettoumsatz pro involvierter Person unter Berücksichtigung der Budgetkosten berechnet. Sortiere diese Tabelle in absteigender Reihenfolge nach dem Nettoumsatz pro involvierter Person und hebe die besten und schlechtesten Besitzer hervor._

Diese Eingabeaufforderung wird in mehreren Schritten mit der Eingabeaufforderungstechnik einer **Verkettung** ausgeführt. Sie fordern Copilot auf, sequenzielle Back-to-Back-Befehle auszuführen, um ein einzelnes Ziel zu erreichen. 

In der entworfenen Eingabeaufforderung sagen Sie Copilot, dass es zuerst eine Formel für die neue Spalte erstellen muss, um den Nettoumsatz pro Benutzer*in zu berechnen und in die Tabelle einzufügen.

![Screenshot von Copilot in Excel, in dem eine Formel generiert wird, die in die Tabelle eingefügt werden soll.](../media/copilot-add-formula-excel.png)

Nachdem die neue Spalte in die Tabelle eingefügt wurde, können Sie Copilot bitten, die Tabelle nach dem höchsten Nettoumsatz pro Benutzer*in zu sortieren und den obersten und den untersten Verkäufer hervorzuheben.

[![Screenshot der erstellten Prompt-Ergebnisse anhand der Beispieltabelle mit Copilot in Excel.](../media/copilot-sort-highlight-table-excel.png)](../media/copilot-sort-highlight-table-excel.png#lightbox)

Copilot hat alle Informationen, die er benötigt, um Ihnen eine solide Antwort zu geben, dank des **Ziels**, **Kontexts**, **Ursprungs** und **Erwartungen** in diesem Prompt.

## Mehr entdecken

Probieren Sie diese einfachen Eingabeaufforderungen aus, um Ihre Daten hervorzuheben, zu sortieren und zu filtern, und fügen Sie weitere Elemente hinzu, um Ihre Ergebnisse zu verbessern:

- Stellen Sie die obersten 10 Werte in der Spalte "Vertrieb" fett dar.

- Heben Sie die höchsten Werte der verkauften Einheiten hervor.

- Sortieren Sie die Kundenbindungsquote von der kleinstem zur größten Quote.  

- Filtern Sie nach Elementen, die in der nächsten Woche fällig sind.

> [!IMPORTANT]
> Copilot funktioniert nur bei Dateien, die auf OneDrive oder SharePoint gespeichert sind. Wenn Sie die Schaltfläche „Copilot“ in der Menüleiste nicht auswählen können, versuchen Sie zunächst, die Datei in der Cloud zu speichern. Weitere Informationen finden Sie unter **[Hervorheben, Sortieren und Filtern von Daten mit Copilot in Excel](https://support.microsoft.com/office/highlight-sort-and-filter-your-data-with-copilot-in-excel-05302e3f-de42-4475-b235-be9cb3d4e936)**.