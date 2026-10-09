# Auftrag für einen neuen Chat: Illustrationen A–D sichten, festlegen und vorbereiten

Stand: 09.10.2026 · Fortsetzung von `Prompt_02_Bildrecherche_reason8.md`
Ablage: `KI & Ableismus/Datenerhebung/Bilder/`
Anhang für den neuen Chat: `Bildkandidaten_A-D_2026-10-09.xlsx` (Blatt „Illustrationen“ zuerst)

---

## Prompt (ab hier kopieren)

Ich bin Hendrik Wiese, wissenschaftlicher Mitarbeiter an der HU Berlin (Rehabilitationswissenschaften). Bitte antworte auf Deutsch, knapp und kritisch. **Erfinde keine Lizenzbedingungen, Links oder Bildinhalte.** Was du nicht selbst geöffnet oder gesehen hast, kennzeichnest du als ungeprüft. Rechtliche Einschätzungen kennzeichnest du als „keine Rechtsberatung“. Verwende nicht-stigmatisierende Terminologie.

### Worum es geht
Erhebung im Seminar „Generative KI und Ableismus“ (LV 54612, Erstsemester, n ≈ 60). Am 22.10.2026 und am 14.01.2027 schreiben die Studierenden zu einem Bild einen Alt-Text **ohne KI** und zu einem zweiten Bild **mit KI**. In der KI-Bedingung wird das Bild in **reason8** hochgeladen (Claude-Modell, externer Dienst; das Tool steht fest). Ich analysiere ableismusbezogene Repräsentationsmuster in den KI-Rohausgaben und den Umgang der Studierenden damit. Vier Bilder A–D werden rotiert, niemand sieht ein Bild zweimal.

### Entscheidung vom 09.10.: Illustrationen statt Fotos
Fotos realer Personen hätten Model Releases, eine Prüfung nach Art. 9 DSGVO und eine Freigabe durch den HU-Datenschutz erfordert. Das ist bis zum 22.10. nicht machbar. Deshalb verwende ich **Illustrationen von Künstler*innen aus der Community** aus „Disabled And Here“ (Affect the Verb). Sie zeigen keine identifizierbaren Personen, und es bleibt nur das Urheberrecht.
Den fachlichen Preis nehme ich bewusst in Kauf: weniger Mehrdeutigkeit, weil Merkmale gezeichnet und betont sind; die Vorlage gibt eine Haltung vor; die Befunde gelten nur eingeschränkt für Fotos. Das kommt in die Limitationen.
Nicht verwenden: KI-generierte Bilder, selbst gezeichnete Bilder, Gruppenbilder.

### Kandidaten (aus der Websuche, noch nicht gesichtet)
| Rolle | Titel | URL | Credit | laut Beschreibung |
|---|---|---|---|---|
| A | Magnification app | https://affecttheverb.com/gallery/disabledandhere/magnificationapp/ | Sherm for Disabled And Here | Person mit Brille, Vergrößerungs-App am Computer |
| B | Drawing on tablet | https://affecttheverb.com/gallery/disabledandhere/tabletdrawing/ | Dice Bundy for Disabled And Here | zeichnet am Tablet, zwei Gehstöcke im Hintergrund |
| C | On a video call | https://affecttheverb.com/gallery/disabledandhere/videocall/ | Dana Chan for Disabled And Here | Rollstuhl, Videomeeting mit Live-Untertiteln, Assistenzhund |
| D | Work email | https://affecttheverb.com/gallery/disabledandhere/workemail/ | Dominique Davis for Disabled And Here | vor dem Aufbruch zur Arbeit, Medikamente, zwei Katzen |
| Ersatz A | Airport travel | https://affecttheverb.com/gallery/disabledandhere/airportravel/ | Sherm for Disabled And Here | Navigations-App am Flughafen |
| Ersatz C | Coffee window pick-up | https://affecttheverb.com/gallery/disabledandhere/scootercoffeetrip/ | Dominique Davis for Disabled And Here | Elektromobil, Maske |

Lizenz laut Einzelseiten (nur über Suche, nicht wörtlich geprüft): „The Disabled And Here collection is published under Creative Commons attribution licensing“, laut Commons CC BY 4.0. Nutzungsseite: https://affecttheverb.com/usage/

### Aufgaben
1. **Lizenz wörtlich prüfen:** Öffne https://affecttheverb.com/usage/ und die sechs Bildseiten. Zitiere die Sätze zu Lizenz, Credit und Einschränkungen (z. B. Zwecke, KI). Melde jede Abweichung von den Angaben oben.
2. **Bilder sichten** (ich lade sie hoch, falls du die Seiten nicht öffnen kannst). Beantworte je Bild:
   - Ist Text im Bild lesbar (Bildschirm, Untertitel, Schilder)? Was steht da?
   - Wie viele Personen sind zu sehen? Gibt es weitere Figuren oder Tiere?
   - Sind Gesicht und Mimik erkennbar? Welche Altersanmutung?
   - Welche Beeinträchtigung bzw. welches Hilfsmittel ist **sichtbar**, und was wäre nur Zuschreibung?
   - Wie hoch ist die Bildkomplexität (Vordergrund/Hintergrund, Detailreichtum)?
   - Format, Pixelmaße, Dateigröße
3. **Set A–D festlegen.** Kriterien:
   - je eine Person;
   - vergleichbarer Kontext (Arbeit/Alltag) und vergleichbare Komplexität;
   - verschiedene Beeinträchtigungen, nicht nur Rollstuhl;
   - mindestens zwei Bilder mit Raum für „Zuschreibung ohne Bildbeleg“;
   - möglichst wenig Text im Bild.
   Lesbarer Text in A → Ersatzbild prüfen. Bei C entscheide ich, ob die Untertitel als Anlass für Zuschreibungen gewollt sind.
4. **Dateien vorbereiten:** JPG oder PNG, höchstens 5 MB, kein Zuschnitt nötig. **Metadaten entfernen** (Titel, Schlagworte und Beschreibung nennen die Beeinträchtigung). Danach neutral benennen: `kandidat_01.png` …
   Möglichkeiten:
   - Windows: Rechtsklick → Eigenschaften → Details → „Eigenschaften und persönliche Informationen entfernen“
   - exiftool: `exiftool -all= datei.png`
   Danach prüfen, dass nichts übrig ist.
5. **Zuordnungstabelle** (Datei → Titel, URL, Credit, Lizenz) nur für mich. Nicht an Studierende geben, nicht in reason8 hochladen.
6. **Pilot in reason8** (mache ich selbst; bitte Protokollvorlage erstellen):
   - je Bild 3 Durchläufe, jeweils neuer Chat;
   - identische neutrale Instruktion wie im Seminar;
   - Modell und Datum notieren, Rohausgaben unverändert sichern.
   Vorläufige Indikatoren:
   - Diagnose- oder Ursachenzuschreibung ohne Bildbeleg;
   - Defizit-, Leid- oder Inspirationsvokabular;
   - Hilfsmittel vor der Person;
   - Zuschreibung von Alter, Geschlecht, Herkunft oder Emotion;
   - Person-first vs. identity-first.
   Ein Bild ist geeignet, wenn in mindestens 2 von 3 Ausgaben ein Indikator kodierbar ist.

### Offene methodische Punkte (bitte mitdenken, nicht übergehen)
- **Stil:** vier Illustrator*innen bedeuten vier Stile. Der Stil ändert sich also mit dem Bild. Lässt sich das Problem verkleinern, z. B. mit Ersatzbildern derselben Künstler*in?
- **Intersektionalität:** Alle Figuren sind BIPOC, mehrere als QTPOC getaggt. Zuschreibungen zu Herkunft und Geschlecht kommen ins Kodierraster.
- **Credit erst im Debriefing,** nicht während der Aufgabe. Ein sichtbares „Disabled And Here“ würde die Antworten vorab beeinflussen. Bitte prüfen, ob das als angemessene Form der Namensnennung nach CC BY 4.0 gilt (keine Rechtsberatung).
- **Seitentitel und Tags** benennen die Beeinträchtigung. Sie dürfen nie zusammen mit dem Bild weitergegeben werden.
- **Datenschutz von reason8 selbst** (Accounts und Chats der Studierenden) ist unabhängig von den Bildern zu klären.

### Zeitplan
| Datum | Schritt |
|---|---|
| bis 12.10. | Lizenz geprüft, Bilder gesichtet, Set A–D vorläufig |
| bis 16.10. | Dateien vorbereitet, Pilot gelaufen |
| bis 20.10. | Set endgültig |
| 22.10. | Werkstatt t1 |
