# MuniSalud · portada pública

Esta es la portada estática de `https://munisalud.org`, servida por GitHub Pages desde la rama `main`. Su función es presentar el Aula Municipal de Salud Pública y dirigir a la plataforma formativa en `https://formacion.munisalud.org/home`.

## Línea visual

La página sigue la estética aplicada a MuniSalud a partir de la referencia de la Tarjeta Sanitaria Digital:

- fondo blanco y superficies azul muy claro;
- azul principal `#2B6EB2` y azul profundo `#124F8B` para jerarquía y cabecera;
- rojo institucional CAM `#FF0000` únicamente como acento y llamada a la acción;
- tarjetas blancas redondeadas, sombras suaves y tipografía de sistema;
- maquetación responsive comprobada en escritorio y móvil.

Los colores institucionales CAM conservados son `#FF0000`, `#D40000`, negro y blanco. La marca de la cabecera no se ha recoloreado.

## Recursos

- `cam-marca.png`, favicons y `og-image-1200x630.png`: recursos institucionales existentes de la Comunidad de Madrid.
- `biblioteca-munisalud.jpg`: recorte editorial de la biblioteca del Centro Regional de Documentación y Educación Sanitaria. Procede de la imagen oficial de Comunidad de Madrid utilizada también en la plataforma formativa. El fichero publicado no incluye metadatos EXIF.

## Publicación

GitHub Pages publica la raíz de la rama `main` del repositorio `Proportione/munisalud-landing`. El dominio canónico configurado es `munisalud.org`.

Para publicar una modificación:

```bash
git add index.html biblioteca-munisalud.jpg README.md
git commit -m "Descripción del cambio"
git push origin main
```

## Comprobaciones mínimas

1. Abrir `https://munisalud.org` en escritorio y móvil.
2. Confirmar que el botón lleva a `https://formacion.munisalud.org/home` en la misma pestaña.
3. Confirmar que carga `/biblioteca-munisalud.jpg` y que los metadatos `og:` siguen apuntando a la tarjeta institucional existente.
4. Verificar en GitHub Pages que el último build aparece como `built`.

La actualización visual de septiembre de 2026 se publicó con el commit `83cbf58`.
