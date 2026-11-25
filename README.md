# Repositorio LEMD para Kodi

Skin **LEMD** (versión 1.9.14) para Fire TV, ligera y con tema Barajas, con
actualizaciones automáticas. Solo TV en directo (IPTV Simple), Umbrella y Meteorología.

## Instalar (una sola vez)

1. Kodi: *Ajustes › Sistema › Add-ons* → activa **Orígenes desconocidos**.
2. *Ajustes › Explorador de archivos › Añadir fuente* → `https://infrap3home.github.io/LEMD/` → nombre `LEMD`.
3. *Ajustes › Add-ons › Instalar desde un archivo zip* → `LEMD` → `repository.lemd-1.0.1.zip`.
4. *Instalar desde repositorio › Repositorio LEMD › Aspecto › Skin › LEMD* → Instalar.
5. Opcional: *Sonidos de la interfaz › LEMD · sonidos de cabina*.

Kodi revisa el repositorio al arrancar y cada pocas horas e instala las versiones
nuevas solo (*Ajustes › Sistema › Add-ons › Actualizaciones* → «Instalar automáticamente»).

¿No llega la última versión? Kodi solo mira el repositorio una vez al día (LEMD 1.4.4 o
superior le pide mirar al encender). Para ponerla ya: *Instalar desde un archivo zip › LEMD* →
`skin.lemd-1.9.14.zip` (Kodi 21+) o `skin.lemd-1.9.14-kodi20.zip` (Kodi 20).

## Contenido

| Carpeta | Para |
|---|---|
| `omega/` | Kodi 21 y posteriores |
| `nexus/` | Kodi 20 |
| `repository.lemd-1.0.1.zip` | El add-on del repositorio (se instala una vez) |

Este repositorio se genera con `herramientas/publicar_repo.py`; no edites los archivos a mano.
