InfcMod (Fabric, Minecraft 1.21.11)
Taste V (aenderbar unter Optionen > Steuerung > InfcMod) fuehrt /invsee <naechster Spieler> aus.

BAUEN
1. Java 21 installieren.
2. Dieses Projekt in den Ordner von https://github.com/FabricMC/fabric-example-mod kopieren
   (src/, build.gradle, gradle.properties, settings.gradle ersetzen; gradlew/gradle/ behalten)
   ODER Gradle 8.14+ installiert haben und "gradle build" ausfuehren.
3. Versionen in gradle.properties mit https://fabricmc.net/develop abgleichen.
4. ./gradlew build  ->  build/libs/infcmod-1.0.0.jar

MODPACK
Die fertige infcmod-1.0.0.jar zusammen mit der Fabric API (und optional Mod Menu)
in modpack/mods/ legen, dann den Ordner modpack/ als Instanz-Ordner (z.B. Prism Launcher) nutzen.

EINFACHSTER WEG (GitHub baut die .jar fuer dich)
1. Neues Repository auf github.com anlegen.
2. ALLE Dateien dieses Ordners hochladen (auch den versteckten Ordner .github).
3. Oben auf "Actions" klicken, Build abwarten, unter "Artifacts" infcmod-jar herunterladen.
