PAQUETE DE PRUEBA DE COMPILACION - DESBLOQUEAR MAPA v1.3

IMPORTANTE
Este paquete NO es una version 1.4 ni contiene una compilacion nueva ya verificada.
Incluye el CSI original v1.3, su fuente y un flujo de GitHub Actions para intentar
compilar la fuente en un servidor Windows de GitHub. La compilacion todavia debe
ejecutarse y sus registros revisarse. Que compile no demuestra que funcione dentro
del juego; eso requiere una prueba real en GTA San Andreas Android.

PASOS
1. En GitHub, crea un repositorio nuevo y vacio llamado desbloquear-mapa.
2. Extrae este ZIP en el telefono y sube TODO su contenido al repositorio,
   conservando la carpeta .github/workflows/compile.yml.
3. En el repositorio abre la pestaña Actions.
4. Selecciona "Compile CLEO script" y pulsa "Run workflow".
5. Si termina correctamente, abre la ejecucion y descarga el artefacto
   "Desbloquear-Mapa-compiled-test" en la seccion Artifacts.
6. Si falla, abre los registros del paso que falló y comparte el error.

No reemplaces el script de tu juego con un archivo generado hasta revisar el
resultado y conservar una copia de seguridad de tus archivos y partida.
