# Vom Anliegen zur bestätigten Übernahme

**Fiktives Lehrbeispiel.** Die folgenden Dokumente und Dialoge dienen der Veranschaulichung. Es wurden keine entsprechenden Dateien geöffnet oder Agenten gestartet.

## 1. HUMAN beschreibt sein Anliegen

> „Ich überlege, ein eigenes Notizwerkzeug zu bauen. Zuerst möchte ich wissen, ob meine vorhandene Arbeitsweise schon genügt.“

## 2. Die Quellen werden benannt

Für dieses Beispiel stellt HUMAN zwei Dokumente bereit:

**Quelle Q1: `NOTIZIDEE.md` · Fassung 1**

> Ich möchte kurze Gedanken lokal erfassen, nach Themen wiederfinden und später ergänzen können. Dafür erwäge ich eine eigene Anwendung. Eine Synchronisierung zwischen Geräten ist zunächst nicht erforderlich.

**Quelle Q2: `BISHERIGE_ARBEITSWEISE.md` · Fassung 1**

> Ich schreibe bereits einzelne Markdown-Dateien in einen lokalen Ordner. Die Dateinamen enthalten Datum und Thema. Ich kann die Dateien durchsuchen. Schwierigkeiten habe ich vor allem mit uneinheitlichen Themenbezeichnungen und doppelten Notizen.

Diese beiden Fassungen bilden die gemeinsame Grundlage. Spätere Änderungen müssten ausdrücklich in den Auftrag übernommen werden.

## 3. ADVISOR formuliert den Auftrag

> „Du möchtest prüfen lassen, ob deine bestehende Arbeit mit Markdown-Dateien die beschriebenen Anforderungen bereits abdeckt und welche Lücken tatsächlich einen Neubau rechtfertigen könnten.
>
> Ich empfehle ARCHITECT im Modus EXPLORER: zuerst untersuchen, noch nicht planen oder bauen.“

HUMAN bestätigt:

> „Ja. Genau diese Untersuchung auf Grundlage der beiden Dokumente. Noch nichts entwickeln oder verändern.“

## 4. HANDOVER: der bestätigte Auftrag wird übergeben

**Beispielkennung:** Ü01 · Fassung 1

**Empfänger:** ARCHITECT

**Funktion:** EXPLORER — Bestand und Bedarf untersuchen

**Auftrag**

Vergleiche die Anforderungen aus Q1 mit der beschriebenen Arbeitsweise aus Q2. Unterscheide dabei:

- bereits abgedeckte Anforderungen;
- belegte Lücken;
- offene Fragen, die anhand dieser Quellen nicht beantwortet werden können.

**Erwartetes Ergebnis**

Ein kurzer Bericht mit nachvollziehbaren Quellenbezügen. Er soll HUMAN eine Entscheidung darüber ermöglichen, ob ein weiterer Entwicklungsschritt sinnvoll ist. Eine Empfehlung muss erkennen lassen, auf welche Anforderung oder belegte Schwierigkeit sie sich stützt.

**Arbeitsgrundlage**

Ausschliesslich Q1 und Q2, jeweils Fassung 1.

**Grenzen**

- Keine Dateien anlegen, verändern oder löschen.
- Keinen Code schreiben und keinen Bauplan erstellen.
- Keine weiteren Ordner, Anwendungen oder Konten untersuchen.
- Keine Webrecherche durchführen.
- Keine zusätzlichen Anforderungen unterstellen.
- Aus der Untersuchung entsteht keine automatische Freigabe zum Bauen.

## 5. TAKEOVER: ARCHITECT weist die Übernahme aus

Eine nachvollziehbare Übernahme müsste drei Dinge sichtbar machen:

| Gegenstand | Erforderlicher Beleg |
|---|---|
| Auftrag | Der Empfänger nennt Ü01, Fassung 1, und die vereinbarte Funktion EXPLORER. |
| Quellen | Im tatsächlichen Lauf ist belegt, dass Q1 und Q2 in den bezeichneten Fassungen bereitgestellt und erfolgreich gelesen wurden. |
| Verständnis und Grenzen | Der Empfänger reformuliert die Untersuchung und nennt die wesentlichen Ausschlüsse. |

**Illustrative Übernahmeantwort des ARCHITECT:**

> „Ich übernehme Ü01, Fassung 1, als ARCHITECT im Modus EXPLORER.
>
> Meine Grundlage sind `NOTIZIDEE.md`, Fassung 1, und `BISHERIGE_ARBEITSWEISE.md`, Fassung 1. Aus Q1 entnehme ich: lokale Erfassung, thematisches Wiederfinden und späteres Ergänzen; Gerätesynchronisierung ist zunächst nicht erforderlich. Q2 beschreibt bereits durchsuchbare Markdown-Dateien und nennt uneinheitliche Themenbezeichnungen sowie doppelte Notizen als Schwierigkeiten.
>
> Mein Auftrag ist, Anforderungen und vorhandene Arbeitsweise gegenüberzustellen und belegte Lücken von offenen Fragen zu unterscheiden.
>
> Ich darf nichts verändern, keine weiteren Quellen untersuchen und weder einen Bauplan noch Code erstellen. Fehlende Angaben kennzeichne ich als offen.
>
> Übernommen ist die Untersuchung. Ein anschliessender Entwicklungsauftrag ist damit nicht erteilt.“

## 6. Wann ist die Übergabe abgeschlossen?

Die Übergabe ist abgeschlossen, wenn der tatsächlich benannte Empfänger denselben bestätigten Auftrag übernommen hat und die bezeichneten Quellen nachweislich verfügbar und gelesen sind.

Fehlt beispielsweise Q2 oder liegt eine andere Fassung vor, bleibt die Übergabe unvollständig. Der Empfänger benennt die Abweichung, statt die fehlende Arbeitsgrundlage zu erfinden.

**Ein Übernahmesatz allein genügt nicht.** Die Reformulierung macht Verständnis prüfbar; tatsächliche Lesebelege zeigen den Quellenzugriff. Beides garantiert noch keine fehlerfreie spätere Untersuchung.

**Hier endet die dokumentierte Einstiegsphase.** Die Untersuchung selbst und alle weiteren Fachschritte gehören nicht zu dieser Lesestrecke.
