# SPORE-Saves
Creado por motivos de copia de seguridad, creaciones y más.

Repositorio local = donde tú tienes guardado este repositorio en tu ordenador, y es en el que se hacen cambios.

Repositorio remoto = dónde el git/github guardan este repositorio que es al que todos debemos adherirnos.

# SPORE MPT (Multijugador por Turnos) / SPORE MBT (Multiplayer by Turns)
## PREPARACIÓN ##
1. Tened el SPORE adecuado:
   - MÍNIMO: En nuestro caso necesitas tener el Spore 1.02 o superior + Aventuras Galácticas 1.0 o superior (Spore + Factoría de Criaturas + Aventuras Galácticas 1.0; o sea, los que te puede actualizar con los CD/DVD sin parches adicionales).
   - RECOMENDADO: El que usa el host de este repositorio (Spore 1.05.001 + Spore AG 1.10; o sea, tener el Spore 1.05.001 que otorga la asimetría con el botón A, tener la expansión de Factoría de Criaturas, y tener la expansión de Aventuras Galácticas 1.10; o sea, lo que te puede actualizar con los CD/DVD sin parches adicionales, y después ejecutas el isntalador del parche 1.05)
   - Sobre mods: solo se tolerarán los siguientes mods:
     - Alteraciones de los ficheros SPORE_EP1/Data/Config/ConfigManager.txt y SPORE_EP1/Data/Config/Properties.txt (ver secciones de abajo):
     - Ciertos ficheros .package que no añadan nuevas partes ni alteren en exceso la jugabilidad (salvo excepciones, ver abajo) de tal forma que tampoco afecten al guardado de las partidas.
     - En caso de duda, consultad con el host.
   - Sobre lenguajes: preferiblemente el español porque las carpetas de creaciones en Spore está ajustada a la carpeta y subcarpetas en Español, pero podéis hacerlo en cualquier otro idioma, solo tendréis que tener cuidado en el paso de enlaces simbólicos.

2. Clonad este repositorio a nivel local:
   - 1º. Instalad la herramienta "git" en vuestro ordenador en caso de que no la tuvieseis ya (se encarga del control de versiones) https://github.com/git-guides/install-git
   - 2º. Crearos una carpeta dónde os dé la gana, por ejemplo "Progreso Spore" en el Escritorio (en mi caso, ruta "C:/Users/User/Desktop/Progreso Spore"), y abrid esa carpeta
   - 3º. Abrid la terminal, símbolo de sistema o equivalente (por ejemplo en Windows, la Git Bash) y ejecutad el comando de descarga del repositorio (por ejemplo si usáis https puede ser algo como el ejemplo de abajo):
        ```
        git clone https://github.com/tardisfromtornspace/SPORE-Saves.git
        ```
   - 4º. Verificad que ahora se ha creado un repositorio SPORE-Saves dentro de la carpeta "Progreso Spore" (o el nombre que hubiérais decidido darle a esa carpeta) con los contenidos de este repositorio.

3. ENLACES SIMBÓLICOS/ACCESOS DIRECTOS:
   - En vuestro directorio de guardado de partidas de Spore
     - 1º Id a donde estaría vuestra carpeta de guardado de Spore, donde se localizan vuestros archivos de Pollination.package y todo eso (en mi caso C:/Users/User/AppData/Roaming/Spore)
     - 2º Renombrad dicha carpeta de guardado para evitar sobreescrituras (en caso de que algo fuera mal o quiesiérais dejar de jugar). Por ejemplo en mi caso renombraría la carpeta "Spore" de "C:/Users/User/AppData/Roaming/" a "SporeBACKUP".
     - 3º Donde antes estaba vuestro directorio de guardado de Spore, ahora creareis un acceso directo con ese mismo nombre que apunte a la carpeta de Spore del repositorio local que os habéis descargado (por ejemplo, si mi antiguo guardado estaba en "C:/Users/User/AppData/Roaming/Spore", y mi repositorio local está en "C:/Users/User/Desktop/Progreso Spore" entonces crearía un acceso directo en "C:/Users/User/AppData/Roaming/", lo llamaría "Spore" y apuntaría a "C:/Users/User/Desktop/Progreso Spore/SPORE-Saves/AppData/Roaming/Spore".
   - En vuestro directorio de "Mis Creaciones Spore" / "My Spore Creations".
     - 1º Id a donde se almacenan vuestras creaciones en Spore (en mi caso, "C:/Users/User/Mis Documentos/Mis Creaciones Spore")
     - 2º Ahora comprobaréis si dicha carpeta está en un lenguaje distinto al español; también deberéis verificar si es solo la carpeta superior la que tiene otro nombre (por ejemplo, "My Spore Creations") o si además las subcarpetas están en otro idioma (con las subcarpetas con cosas cosas como "UFOs", "Creatures", etc.). Renombráis esa carpeta en caso de que algo vaya mal.
     - 3º PLAN A. Si tanto esa carpeta como las subcarpetas están en español, o si tu carpeta de Mis Creaciones Spore está en inglés pero todas sus subcarpetas están es español, bastará con crear el acceso directo con el nombre de vuestro directorio de creaciones original que apunte al del repositorio (por ejemplo, en mi caso, crearía en "C:/Users/User/Mis Documentos/" un acceso directo llamado "Mis Creaciones Spore" que apuntaría a "C:/Users/User/Desktop/Progreso Spore/SPORE-Saves/Creaciones (de 'Mis documentos')/Mis Creaciones Spore")
     - 3º PLAN B. Si tanto la carpeta como las subcarpetas no están en español, lo que se debe hacer es crear una carpeta con el nombre original y dentro de ella crear accesos directos a sus carpetas equivalentes en español utilizadas por el repositorio (por ejemplo, si mi juego está en inglés y mis creaciones del Spore se guardaban en "C:/Users/User/Documents/Mis Spore Creations" y las naves espaciales se guardan en la carpeta "UFOs", deberé crear la carpeta "My Spore Creations" en "C:/Users/User/Documents/" y en su interior crear un acceso directo llamado "UFOs" que apunte a "C:/Users/User/Desktop/Progreso Spore/SPORE-Saves/Creaciones (de 'Mis documentos')/Mis Creaciones Spore/OVNIs")

4º Elegid el método para jugar (reomendado asignaros unos turnos cada uno).

### SOBRE MODS: SPORE_EP1/Data/Config/*.package ###

Aquí se indican los cambios que el host tiene (:ribbon: son los paquetes por defecto, :reminder_ribbon: son los mods adicionales):
- :reminder_ribbon: 1CellEvoadvantage_v1.1.package            <--- Excepción a "no alterar la jugabilidad"
- :reminder_ribbon: 2019DavoBloodBite.package
- :reminder_ribbon: 65034-placetribaltoolsanywhere.package    <--- Excepción a "no alterar la jugabilidad"
- :reminder_ribbon: AnimationMod.package
- :reminder_ribbon: DanceAnimations2.package
- :reminder_ribbon: DanceAnimations3.package
- :reminder_ribbon: DCityWalls.package                        <--- Excepción a "no alterar la jugabilidad"
- :reminder_ribbon: Editorbg.package
- :ribbon: EP1_PatchData.package
- :reminder_ribbon: MMDbg.package
- :reminder_ribbon: MrsWhitesYourInvasion.package             <--- Excepción a "no alterar la jugabilidad"
- :reminder_ribbon: Ramone_Kemono.s_2nd_MMD_Drag_Ball.package
- :reminder_ribbon: Ramone_Kemono.s_MMD_Drag_Ball_SFW.package
- :reminder_ribbon: SG.s_UserCellAdder.package                <--- Excepción a "no alterar la jugabilidad"
- :reminder_ribbon: Spore2005_BetaFaces.package
- :ribbon: Spore_EP1_Content_01.package
- :ribbon: Spore_EP1_Content_02.package
- :ribbon: Spore_EP1_Data.package
- :ribbon: Spore_EP1_Locale_01.package


### SOBRE MODS: SPORE_EP1/Data/Config/ConfigManager.txt ###

Aquí se indican los cambios que el host tiene, poniéndolos al final del documento:
-----------------------------------------------------
```
# Force saving, works nicely
boolProp disableValidation true

# FPS modification, 1000/(FPS you want) In this case, 1000/100=10
intProp frameLimitMS 10

# HD textures
intProp   skinpaintTextureSize        2048
floatProp skinpaintBumpHeight         50
floatProp skinpaintGlossMultiplier    2
floatProp skinpaintPhongMultiplier    3
floatProp skinpaintPartBumpScale      3
floatProp skinpaintAmbOccDiffuse      3
floatProp skinpaintAmbOccSpecular     2

# Recording settings
floatprop recordMovieLength 840

IntProp recordMovieWidth 1280
IntProp recordMovieHeight 720 

floatprop recordMovieFPS 30.0
floatprop recordMovieQuality 0.75
boolprop recordMovieAudio true
boolprop recordMovieNoUI false
boolprop recordMovieFrameUI false

# Multi-Creature Test Drive 
boolProp EditorEnablePlayModeDrop true
boolProp EditorAlwaysAllowDrop true
```
-----------------------------------------------------

### SOBRE MODS: SPORE_EP1/Data/Config/Properties.txt ###

Aquí se indican los cambios que el host tiene, poniéndolos al final del documento:
-----------------------------------------------------
```
# ColladaExport
property HasShownExportToolEULA 0x087c4363 bool

# Force saving, works nicely
property disableValidation 0x055d7ca1 bool true

# FPS modification
property frameLimitMS 44 int

# HD textures
property skinpaintTextureSize        (hash(skinpaintTextureSize))     int
property skinpaintBumpHeight         (hash(skinpaintBumpHeight))      float
property skinpaintGlossMultiplier    (hash(skinpaintGlossMultiplier)) float
property skinpaintPhongMultiplier    (hash(skinpaintPhongMultiplier)) float
property skinpaintPartBumpScale      (hash(skinpaintPartBumpScale))   float
property skinpaintAmbOccDiffuse      (hash(skinpaintAmbOccDiffuse))   float
property skinpaintAmbOccSpecular     (hash(skinpaintAmbOccSpecular))  float

# Recording settings
property recordMovieLength 0x0456f974 float 840 # time in seconds, by default it is 2 minutes, not 840 seconds

property recordMovieWidth 0x0456f975 int 1280 # Width 1280
property recordMovieHeight 0x0456f975 int 720 # Height 720

property recordMovieFPS 0x0456f977 float 30.0 # FPS limit, we change it to 60
property recordMovieQuality 0x0456f978 float 0.75 # Record quality, from 0.1 to 1
property recordMovieAudio 0x0456f979 bool true # Allow to capture sound
property recordMovieNoUI 0x0456f97a bool false # Disable to capture UI
property recordMovieFrameUI 0x0641021a bool false # Disable to capture Frame UI (border)

# Multi-Creature Test Drive
property EditorEnablePlayModeDrop  0xD7F24DCF bool true
property EditorAlwaysAllowDrop     0x0678f3f1 bool true
```
## Cómo jugar en multijugador por turnos ##
Una vez se han instalado todo, puesto los enlaces simbólicos adecuados y asignado los turnos, lo único que se debe hacer es:
1. Antes de jugar tu turno, asegurarse que tu repositorio local está actualizado (desde el terminal dentro de la carpeta del repositorio local):
```
git pull
```
2. Una vez todo está actualizado, ponerte a jugar, y cuando esa persona haya jugado y terminado su turno, deberá guardar su progreso en el repositorio remoto ("git status" es mostrar las diferencias/cambios entre lo que hay en tu repositorio y lo que hay en el remoto; "git add -A" es añadir todos los cambios a una lista de actualizaciones; 'git commit -m "Texto" ' significa que esos cambios se añaden a una tanda de modificaciones que se pueden subir al repositorio remoto, con el texto "Texto" como explicación; mientras que "git push" significa aplicar esos cambios al repositorio remoto):
```
git status
git add -A
git commit -m "Turno 1 de Pancracio"
git push
```

Por ejemplo, si tenemos tres jugadores, Sergio, Antonio y Patricia; y han decidido asignarse los turnos de tal forma que el primero sea de Sergio, el segundo de Antonio, el tercero de Patricia, y de nuevo Sergio. Asumamos que todos han puesto su carpeta en el Escritorio con el nombre "Progreso Spore".

1. Sergio está en Windows, así que se va a la carpeta "Progreso Spore", la abre, da click derecho, verá la opción de "Git Bash" y le da click a esa opción. Se le abrirá la consola de git y ahí escribirá "git pull". Espera a que los cambios que pudieran haber ocurrido en el respositorio remoto se actualicen, y comienza a jugar. Sergio ha empezado por el estadio célula en un planeta llamado "SergioWorld", se ha creado una especie llamada "Batracio Espora", y ha logrado llegar al estadio criatura. Termina su turno, así que cierra el Spore, vuelve a la ventana del Git Bash (que por comodidad, ha decidido dejar abierta antes por donde estaba) y ejecuta primero "git status" para verificar que todo ha ido bien, que se han actualizado los archivos apropiados y que ahora se ha creado un guardado de su mundo "SergioWorld" y de su célula y de su criatura "Batracio Espora". Entonces añade esos cambios con "git add -A", crea un commit "git commit -m 'TURNO 1, Sergio 25-10-2025'" y lo actualiza en el repositorio remoto con git push:

```
git pull

git status
git add -A
git commit -m "TURNO 1, Sergio 25-10-2025"
git push
```
2. Antonio está en Linux, así que se va a la carpeta "Progreso Spore", abre la terminal y ahí escribirá "git pull". Espera a que los cambios de Sergio se le actualicen a su repositorio local, y comienza a jugar. Antonio ha decidido empezar por el estadio tribal en un planeta llamado "Antonino", se ha creado una especie llamada "Pájaro de San Antonio", y ha logrado relacionarse con 4 tribus. Termina su turno, así que cierra el Spore, vuelve a la ventana de su terminal (que por comodidad, ha decidido dejar abierta antes por donde estaba) y ejecuta primero "git status" para verificar que todo ha ido bien, que se han actualizado los archivos apropiados y que ahora se ha creado un guardado de su mundo "Antonino" junto a una criatura "Pájaro de San Antonio" del estadio criatura y un "Pájaro de San Antonio (1)" del estadio tribal. Entonces añade esos cambios con "git add -A", crea un commit "git commit -m 'TURNO 2, Antonio 26-10-2025'" y lo actualiza en el repositorio remoto con git push:

```
git pull


git status
git add -A
git commit -m "TURNO 2, Antonio 26-10-2025"
git push
```
3. Patricia también está en Linux, así que se va a la carpeta "Progreso Spore", abre la terminal y ahí escribirá "git pull". Espera a que los cambios de Sergio y Antonio se le actualicen a su repositorio local, y comienza a jugar. Patricia ha decidido empezar por el estadio criatura en un planeta llamado "Baal", se ha creado una especie llamada "Custodio de Sangre", y ha logrado avanzar hasta el estadio civilización, creándose una ayuntamiento llamado "Adminstratum" y un vehículo religioso llamado "Tanque de Asedio". Termina su turno, así que cierra el Spore, vuelve a la ventana de su terminal (que por comodidad, ha decidido dejar abierta antes por donde estaba) y ejecuta primero "git status" para verificar que todo ha ido bien, que se han actualizado los archivos apropiados y que ahora se ha creado un guardado de su mundo "Baal" junto a una criatura "Custodio de Sangre" del estadio criatura, un "Custodio de Sangre (1)" del estadio tribal, un "Custodio de Sangre (2)" del estadio civilización, un edificio "Adminstratum" y un vehículo "Tanque de Asedio". Entonces añade esos cambios con "git add -A", crea un commit "git commit -m 'TURNO 3, Patricia 27-10-2025'" y lo actualiza en el repositorio remoto con git push:

```
git pull


git status
git add -A
git commit -m "TURNO 3, Patricia 27-10-2025"
git push
```
4. Le vuelve a tocar a Sergio en Windows, así que vuelve a abrir la "Git Bash" en la carpeta del repositorio local y ahí escribirá "git pull". Espera a que los cambios de Antonio y Patricia se le actualicen, y comienza a jugar; esta vez logrando lelgar al estadio tribal, tras hacer modificaciones a su criatura. Termina su turno, así que cierra el Spore, vuelve a la ventana del Git Bash (que por comodidad, ha decidido dejar abierta antes por donde estaba) y ejecuta primero "git status" para verificar que todo ha ido bien, que se han actualizado los archivos apropiados y que ahora se ha modificado su guardado de "SergioWorld", su "Batracio Espora" del estadio criatura, y se ha creado un "Batracio Espora (1)" del estadio tribal. Entonces añade esos cambios con "git add -A", crea un commit "git commit -m 'TURNO 4, Sergio 28-10-2025'" y lo actualiza en el repositorio remoto con git push:

```
git pull

git status
git add -A
git commit -m "TURNO 4, Sergio 28-10-2025"
git push
```

### NORMAS DURANTE EL JUEGO ###
1. No se permite borrar creaciones ni mundos de otros jugadores.
2. Por motivos de compatibilidad, solo se usarán los mods que se mencionaran durante la instalación y cualquier otro mod que se hubiera consensuado añadir.

### EN CASO DE ERROR ###
En caso de error durante la aplicación de cambios, se pueden revertir, pero no lo hagas sin antes consultar al host y avisarle del problema https://git-scm.com/book/en/v2/Git-Basics-Undoing-Things

