# Monopoly Online - Software Engineering Projekt

Willkommen in unserem Repository für das Software Engineering Modul. Dieses Projekt umfasst die Konzeption und Modellierung einer Online-Version des bekannten Brettspiels **Monopoly**.

## 👥 Projektteam
* Luis Zipse
* Marios Zoumpolakis
* Celine Hager
* Tina Ranft

## 🔄 Vorgehensweise und Kommunikation

Unser Entwicklungsprozess folgte einem hybriden Ansatz. Zur Aufgabenverwaltung und Verfolgung des Projektfortschritts haben wir **Jira** eingesetzt.

**Hinweis zur Dokumentation:** Da wir als Team eng zusammengearbeitet haben, fand ein Großteil der Abstimmung, Ideenfindung und Problemlösung **mündlich** (in Präsenz oder Calls) statt. Daher bilden die Tickets in Jira und die Commit-Historie auf GitHub primär die Ergebnisse unserer Arbeit ab und nicht den gesamten Kommunikationsprozess.

## 📂 Projektphasen und Artefakte

Wir haben das Projekt in logische Phasen unterteilt, die sich in den hochgeladenen Dokumenten widerspiegeln:

### 1. Regelwerk und Systemgrenzen
Zunächst haben wir die offiziellen Spielregeln analysiert und für die Online-Umsetzung angepasst.
* **Datei:** `Monopoly_Regelwerk.pdf`
* **Wichtige Design-Entscheidung:** Im Gegensatz zum Brettspiel wird die **Bank** in unserer Version nicht von einem Spieler verkörpert. Sie ist stattdessen als **Teil des Systems** modelliert, der Regelprüfungen und Transaktionen automatisiert abwickelt.

### 2. Anforderungsanalyse (Use Cases)
Basierend auf dem Regelwerk haben wir die funktionalen Anforderungen definiert.
* **Datei:** `Monopoly_ Use-Case-Beschreibungen .docx`
* **Hinweis zum Umfang:** Gemäß der Aufgabenstellung haben wir uns auf die Modellierung von **10 exemplarischen Use Cases** beschränkt.
  * Da das Spiel komplexer ist, enthalten die Beschreibungen an einigen Stellen Referenzen zu weiteren (notwendigen, aber hier nicht modellierten) Use Cases, um die logische Konsistenz zu wahren.

### 3. Statische Modellierung
Zur Abbildung der Datenstruktur und der Systemarchitektur wurden ein Data Dictionary und ein Klassendiagramm erstellt.
* **Data Dictionary:** `Data Dictionary.docx`
* **Klassendiagramm:** `Monopoly_Klassendiagramm.drawio`

### 4. Dynamische Modellierung (Sequenzdiagramme)
Abschließend haben wir die Interaktionen innerhalb des Systems visualisiert. Der Fokus lag hierbei auf der Abbildung eines vollständigen **Spielzugs**, inklusive aller Verzweigungen und der Interaktion mit der als Systemkomponente modellierten Bank.
* **Datei:** `Sequenzdiagramme SE Monopoly.drawio`

---

## 🛠 Tools
* **Modellierung:** Draw.io
* **Projektmanagement:** Jira
* **Versionskontrolle:** GitHub
