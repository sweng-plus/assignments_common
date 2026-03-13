[English version](oop_assignment_general_rules.md)

## \# Allgemeine Regeln

-   Beginnen Sie Ihre Arbeit damit, den **Aufgabentext sorgfältig zu
    lesen** sowie den **Starter-Code im Verzeichnis `src/main/java`**,
    einschließlich der darin enthaltenen Kommentare.
-   Von Ihnen wird erwartet, dass Sie:
    -   Code zu Klassen und Methoden im Starter-Code hinzufügen,
        insbesondere an allen Stellen, die mit `TODO` markiert sind,
        sowie an weiteren geeigneten Stellen.
    -   bestehende Methoden implementieren bzw. deren Implementierung
        anpassen. Insbesondere sollen **Platzhalter‑Rückgabewerte (dummy
        return values)** ersetzt werden.
    -   eigene Java-Dateien hinzufügen. Diese müssen jedoch **im selben
        Package wie die gegebenen Dateien** liegen (achten Sie auf die
        Package-Deklarationen).
-   Sie dürfen die Starter-Klassen erweitern, zum Beispiel durch:
    -   neue Attribute und Methoden,
    -   Vererbung (Super- oder Unterklassen),
    -   innere Klassen (falls wirklich notwendig).
-   Beim Starter-Code müssen Sie unbedingt darauf achten, **nicht**:
    -   das Root-Package umzubenennen (den Ordner unter
        `src/main/java`),
    -   Klassennamen oder deren Access-Modifier zu ändern,
    -   Methodensignaturen zu verändern,
    -   den Inhalt des `.github`-Ordners oder der Datei `pom.xml` zu
        verändern,
    -   vorhandene Testklassen im Ordner `src/test/java` (falls
        vorhanden) zu verändern.
-   **Wichtig:** Wenn mindestens eine dieser Regeln verletzt wird,
    können einzelne oder alle Tests fehlschlagen und es können Punkte
    verloren gehen.

## \# Zum Testen

-   Sie sollten immer eine **`main`-Methode** (gegebenenfalls auch eine
    eigene Klasse) mit **minimalen Tests Ihres Codes** erstellen.
-   Unmittelbar nach der Abgabefrist wird ein **Test-Workflow** auf
    Ihrer Software ausgeführt und auf Basis der Testergebnisse eine
    **Punktezahl berechnet**.
-   Sie können diesen Workflow auf GitHub **eine begrenzte Anzahl von
    Malen vor der Deadline** ausführen.
-   Wenn Sie mit **git und Maven** arbeiten, können Sie den
    Test-Workflow auch **lokal beliebig oft** ausführen.
-   Zu Beginn ist es normal, dass im Starter-Code **Compilerfehler
    auftreten oder Tests fehlschlagen**, da der Starter-Code die
    Anforderungen der Aufgabe zunächst noch nicht erfüllt.

## \## Tests auf GitHub ausführen

-   Öffnen Sie auf der GitHub-Seite des Repositories den Tab **Actions**
    (oben) und wählen Sie links **GitHub Classroom Workflow**. Dort
    sehen Sie eine Liste aller bisherigen Workflow-Runs.
-   Rechts oberhalb dieser Liste befindet sich der Button **Run
    workflow**.
-   Klicken Sie darauf und anschließend im Popup-Fenster erneut auf den
    **grünen Button mit demselben Namen**.
-   Warten Sie, bis die Seite aktualisiert wird (dies kann einige
    Minuten dauern).
-   Danach erhalten Sie eine **Übersichtsseite** mit Informationen
    darüber, wie viele Runs Ihnen noch zur Verfügung stehen sowie über
    die Ergebnisse der **Kompilation und Tests** und die daraus
    resultierende **Punktezahl**.

## \# Nach der Abgabefrist

-   Nach der Deadline wird automatisch **ein letzter Testlauf**
    ausgeführt.
-   Die **endgültige Punktezahl** wird anschließend als Badge im
    **README** angezeigt (sichtbar auf der Repository-Seite). Später
    werden die Punkte nach **Blackboard** übertragen.
-   Danach haben Sie **keinen Schreibzugriff mehr auf Ihr
    Assignment-Repository**, sodass Sie nach der Deadline keine
    Änderungen mehr pushen können.
-   Sie können das Repository jedoch weiterhin **bis zum Ende des
    Semesters lesen**.
-   Nach Ende des Semesters wird das Repository **gelöscht**.
