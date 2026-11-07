# Mauspi FreeDink

Adaptación web de **GNU FreeDink** para [Mauspi](https://mauspi.com/), proyectada en español, con guardados y trofeos de la comunidad.

> **Estado:** preparación / no publicada. Este repositorio contiene por ahora documentación y carpetas de trabajo, **no** el código ni los datos originales del juego. No implica que el lanzamiento del 9 de noviembre de 2026 esté confirmado.

## Fuentes

- [GNU FreeDink (sitio oficial)](https://www.gnu.org/software/freedink/)
- [Archivos oficiales GNU](https://ftp.gnu.org/gnu/freedink/)
- [Traducción de la aventura principal](https://www.translationproject.org/domain/dink.html)
- [Plan de lanzamiento Mauspi](https://github.com/PaperLucas64/mauspiweb/blob/main/docs/gnu-freedink-informe-lanzamiento-2026-11-09.md)

## Objetivos

1. Compilar la versión WebAssembly a partir de una versión oficial identificada y reproducible.
2. Integrar español (`dink.mo` para aventura y `freedink.mo` para motor).
3. Verificar permisos de redistribución de todos los recursos y sonidos incluidos.
4. Probar reproducción y guardado antes de desplegar.
5. Incorporar trofeos, XP y cuentas Mauspi siguiendo el GDD del sitio.

## Publicación y licencias

El motor original está sujeto a la GPLv3 o posterior; los archivos de datos, traducción, música y dependencias tienen licencias y atribuciones diferentes. Antes de distribuir una compilación, incorporaremos avisos, licencias, fuentes y scripts de compilación correspondientes a esa versión concreta. **Nunca suponer que la licencia del motor cubre el audio.**

No existe todavía autorización de publicación en producción ni migración de Supabase.
