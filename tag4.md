# Tag 4 — Deployment & Hosting

**Was gelernt?**
Den Weg einer App vom lokalen Dev-Server (`localhost:3000`) über Build und Test bis zur öffentlich erreichbaren Live-Version, und was bei jedem dieser Schritte typischerweise schiefgehen kann.

**Welches Problem?**
"Lokal läuft es bei mir" ist ein Satz, den ich aus der Technikwelt kannte, ohne zu verstehen, warum das nicht automatisch auch woanders funktioniert.

**Wie gelöst?**
Den kompletten Weg einmal nachvollzogen: Fork, Deploy, Debugging bei Fehlern, eigene Anpassungen, finaler Pull Request. Wichtige Erkenntnis für mein eigentliches Projekt: Genau deshalb bleibt unsere Schaltzentrale bewusst intern gehostet — jede zusätzliche Deployment-Stufe ist ein weiterer Punkt, an dem etwas brechen kann, und das wollen wir für ein Betriebstool ohne IT-Abteilung vermeiden.
