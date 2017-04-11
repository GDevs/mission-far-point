Nach über 2.5 Jahren der aktiven Prokrastination beginnt nun (hoffentlich) die Arbeit an einer 3D-Open-Source-Sandbox-Weltraum-Kampf-und-Handels-Simmulationen.

Die Entwicklung läuft unter dem Arbeitstitel:
# Mission: Farpoint
# Dev-Infos
## Erforderliche software
- CMake
- C++ Kompiler (vorzugsweise gcc oder unter Windows der mit Visual Studio 2017 ausgelieferte C++-Compiler)
- ?
## OGRE
Ogre 1.10 liegt im repo, die binärdateien sollten im verzeichiss ```./ogre_build``` liegen (wenn ```./``` das stammverzeichniss des repos ist)
### Kompilieren
1. CMake-**GUI** Starten
2. Das Quellverzeichniss (```PFAD_ZUM_REPO/ogre```) angeben
3. Das Buildverzeichniss (am besten ```PFAD_ZUM_REPO/ogre_build```)
4. Konfigurieren drücken
5. Generieren Drücken
6. Unter Linux kann Ogre nun im Buildverzeichniss mittels ```make``` kompiliert werden, unter Windows würde ich dort ein Visual-Studio-Projekt erwarten.
### ACHTUNG!
Das komplette verzeichniss ```ogre``` ist ein direkter Git-Klon von https://github.com/OGRECave/ogre.
Ich weiss nicht wie Git mit einem Repo in einem Repo umgeht, am besten die Git nur auf dem Stammverzeichniss des ***Mission Farpoint***-Repos nutzen!