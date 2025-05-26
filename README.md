# LaTeX-Vorlage für die Technische Hochschule Brandenburg (THB)

---

Diese Repository enthält eine **LaTeX-Vorlage**, die speziell für Abschlussarbeiten, Projekte oder andere wissenschaftliche Dokumente an der Technischen Hochschule Brandenburg (THB) angepasst wurde. Mein Ziel war es, eine benutzerfreundliche Vorlage zu schaffen, die den gängigen Formatierungsanforderungen der THB entspricht und dir den Start deines Schreibprojekts erleichtert.

## Was ist enthalten?

* **`Vorlage_Latex_Git_allgemein.tex`**: Dies ist die Hauptdatei der LaTeX-Vorlage. Hier definierst du die Struktur deines Dokuments, fügst Inhalte hinzu und referenzierst deine Literatur.
* **`Vorlage_Bibtex_Git.bib`**: Eine BibTeX-Datei für die Verwaltung deiner Literaturverweise. Du kannst hier alle deine Quellen eintragen und sie dann einfach in deiner `Vorlage_Latex_Git_allgemein.tex`-Datei zitieren.

* **### Beispiel-PDF ansehen

Möchtest du sehen, wie ein kompiliertes Dokument mit dieser Vorlage aussieht?
* **[Klicke hier, um das Beispiel-PDF anzuzeigen](https://github.com/Narrenpfarrer/Th-Brandenburg_Latex_Vorlage/blob/main/Vorlage_Latex_Git_allgemein.pdf)**

## Funktionen der Vorlage

* **THB-spezifische Anpassungen**: Die Vorlage berücksichtigt gängige Formatierungsrichtlinien der THB, wie z.B. Seitenränder, Kopf- und Fußzeilen (falls relevant) und die Titelseite.
* **Einfache Struktur**: Eine klare und logische Gliederung hilft dir, den Überblick über dein Dokument zu behalten.
* **Automatische Literaturverwaltung**: Durch die Integration von `references.bib` kannst du deine Quellen effizient verwalten und automatisch formatierte Literaturverzeichnisse generieren lassen.
* **Anpassungsfähig**: Die Vorlage ist so gestaltet, dass du sie leicht an deine spezifischen Anforderungen anpassen kannst, sei es für eine Bachelorarbeit, Masterarbeit oder ein Projektbericht.

## Wie benutzt man diese Vorlage?

1.  **Repository klonen**: Klone dieses Repository auf deinen lokalen Rechner:
    ```bash
    git clone [https://github.com/DEIN-GITHUB-USERNAME/DEIN-REPOSITORY-NAME.git](https://github.com/DEIN-GITHUB-USERNAME/DEIN-REPOSITORY-NAME.git)
    ```
    (Ersetze `DEIN-GITHUB-USERNAME` und `DEIN-REPOSITORY-NAME` durch deine tatsächlichen Daten.)

2.  **Dateien bearbeiten**:
    * Öffne `Vorlage_Latex_Git_allgemein.tex` in deinem bevorzugten LaTeX-Editor (z.B. TeXstudio, VS Code mit LaTeX Workshop Extension oder Overleaf).
    * Füge deinen Text, Abbildungen und Tabellen in den entsprechenden Abschnitten hinzu.
    * Trage deine Literaturdaten in `Vorlage_Bibtex_Git.bib` ein.

3.  **Kompilieren**: Um dein Dokument zu kompilieren und ein PDF zu erstellen, benötigst du eine LaTeX-Distribution (z.B. TeX Live oder MiKTeX). Navigiere im Terminal oder in der Kommandozeile zum Verzeichnis des geklonten Repositories und führe die folgenden Befehle aus:
    ```bash
    pdflatex Vorlage_Latex_Git_allgemein.tex
    bibtex Vorlage_Latex_Git_allgemein  # Nur ausführen, wenn du Änderungen an Vorlage_Bibtex_Git.bib vorgenommen hast
    pdflatex Vorlage_Latex_Git_allgemein.tex
    pdflatex Vorlage_Latex_Git_allgemein.tex
    ```
    Es kann notwendig sein, `pdflatex` mehrmals auszuführen, damit alle Querverweise und das Literaturverzeichnis korrekt gesetzt werden.

4.  **Ergebnis prüfen**: Nach erfolgreicher Kompilierung findest du die PDF-Datei (`Vorlage_Latex_Git_allgemein.pdf`) im selben Verzeichnis.

## Beitrag leisten

Verbesserungsvorschläge oder Erweiterungen sind jederzeit willkommen! Fühl dich frei, ein Issue zu öffnen oder einen Pull Request einzureichen.

---

Viel Erfolg bei deiner Arbeit an der THB!
