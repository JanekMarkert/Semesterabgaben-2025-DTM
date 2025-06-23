# 🗺️ Semesterabgaben 2025 – Thematische Kartographie  
_@Janek Markert | BHT Berlin – Digitale Techniken und Medien_

In diesem Repository dokumentiere ich meine Abgaben zum Kurs **"Thematische Kartographie"** im Sommersemester 2025 an der BHT Berlin.  
Jede Aufgabe wurde in **QGIS** bearbeitet und behandelt unterschiedliche Methoden der thematischen Kartendarstellung. Zu jeder Abgabe gibt es eine kurze Beschreibung, Erläuterung der Umsetzung sowie Hinweise zu eventuellen Problemen und deren Lösung.

---

## 📂 Übersicht der Abgaben

- [Aufgabe 1 – Dasymetrische Choroplethenkarte](#aufgabe-1--dasymetrische-choroplethenkarte)
- [Aufgabe 2 – Gitterchoroplethenkarte](#aufgabe-2--gitterchoroplethenkarte)
- [Aufgabe 3 – Punktrasterkarten](#aufgabe-3--punktrasterkarten)
- [Aufgabe 4 – Value-by-alpha Mapping](#aufgabe-4--value-by-alpha-mapping)
- [Aufgabe 5 – Tilemaps](#aufgabe-5--tilemaps)
- [Aufgabe 6 – Flowmaps](#aufgabe-6--flowmaps)
- [Aufgabe 7 – mess'-Daten](#aufgabe-7--mess-daten)

---

## 🧭 Aufgabe 1 – Dasymetrische Choroplethenkarte  
**Thema:** Kleines Einmaleins der thematischen Kartographie

**Was ich gemacht habe:**  
Erstellung einer dasymetrischen Karte auf Basis vorhandener Flächendaten, mit zusätzlicher Differenzierung nach Landnutzung.

**Problem & Lösung:**  
Datenüberlagerungen erzeugten uneinheitliche Klassen – durch manuelles Nachbearbeiten und korrekte Klassifizierung konnte die Darstellung verbessert werden.

---

## 🧭 Aufgabe 2 – Gitterchoroplethenkarte

**Was ich gemacht habe:**  
Erzeugung eines gleichmäßigen Gitters über die Karte mit standardisierter Flächendarstellung. Anwendung farblicher Codierung nach Kategorien.

**Problem & Lösung:**  
Ein Rasterversatz wurde durch korrekte Bezugspunktwahl und Gitterausrichtung behoben.

---

## 🧭 Aufgabe 3 – Punktrasterkarten

**Was ich gemacht habe:**  
Visualisierung aggregierter Werte durch gleichmäßig verteilte Punkte. Jeder Punkt entspricht einem bestimmten Datenwert.

**Problem & Lösung:**  
Die Skalierung wirkte uneinheitlich – durch Normierung der Punktanzahl pro Flächeneinheit wurde eine bessere Lesbarkeit erreicht.

---

## 🧭 Aufgabe 4 – Value-by-alpha Mapping

**Was ich gemacht habe:**  
Verwendung von Transparenz zur Darstellung zusätzlicher Variablen in einer Choroplethenkarte (z. B. Einwohnerzahl + Dichte).

**Problem & Lösung:**  
Geringe Kontraste machten die Karte schwer lesbar – durch Anpassung der Farbpalette und der Alpha-Werte wurde dies korrigiert.

---

## 🧭 Aufgabe 5 – Tilemaps

**Was ich gemacht habe:**  
Darstellung der Fläche durch gleich große Kacheln (Tiles), um verzerrungsfreie Vergleiche zwischen Regionen zu ermöglichen.

**Problem & Lösung:**  
Regionen mit ungewöhnlicher Form mussten sinnvoll in das Tile-Raster übertragen werden – dies gelang durch manuelles Zuweisen.

---

## 🧭 Aufgabe 6 – Flowmaps

**Was ich gemacht habe:**  
Darstellung von Bewegungsflüssen (z. B. Pendlerströme) mithilfe von Pfeilen und gewichteter Linienbreite.

**Problem & Lösung:**  
Die Lesbarkeit bei Überlagerungen war eingeschränkt – durch gezieltes Kurvenrouting und Priorisierung der Hauptflüsse wurde das verbessert.

---

## 🧭 Aufgabe 7 – Mesh-Daten

**Was ich gemacht habe:**  
Verarbeitung und Visualisierung von echten Messdaten (z. B. Umwelt- oder Verkehrsaufkommen). Kartografische Generalisierung zur besseren Darstellung.

**Probl**
