# Mahjong – Drachenwelt (Android-Projekt)

Ein natives Android-Studio-Projekt als spielbarer erster Prototyp mit fünf Leveln, Hochformat-Vollbild, Mahjong-Steinen, Vierer-Ablage, Münzbelohnung und Drachen-Meilensteinen. Die bereitgestellte Grafik liegt als `app/src/main/assets/designvorlage.png` im Projekt und dient als visuelle Referenz.

## APK erstellen
1. Installiere Android Studio (aktuelle stabile Version) auf einem PC.
2. Entpacke diesen ZIP-Ordner.
3. Android Studio → **Open** → Ordner `MahjongDrachenwelt` auswählen.
4. Gradle-Synchronisierung abwarten.
5. **Build → Build Bundle(s) / APK(s) → Build APK(s)** auswählen.
6. Die Debug-APK liegt normalerweise unter `app/build/outputs/apk/debug/app-debug.apk`.
7. APK auf das Android-Handy kopieren und öffnen. Bei Nachfrage die Installation aus dieser Quelle erlauben.

## Hinweis
Dies ist eine erste native Projektversion, keine bereits kompilierte APK. Das Bild aus der Anfrage ist als Designvorlage enthalten; die eigentliche Spielfläche wird nativ gezeichnet, damit Steine antippbar sind. Bitte vor einer Veröffentlichung ausgiebig testen und die Spielmechanik/Optik weiter verfeinern.
