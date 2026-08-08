# Calculadora de Peso Fetal Estimado PRO

Herramienta web educativa de Herramientas360 para estimar el peso fetal mediante biometrías ecográficas y situar el resultado de forma orientativa según la edad gestacional.

URL oficial: https://tpz4hm662z-rgb.github.io/calculadora-de-peso-fetal-estimado/

## Funcionamiento

La calculadora utiliza la edad gestacional y las medidas BPD, HC, AC y FL introducidas por la persona usuaria. Aplica ecuaciones de Hadlock y presenta el peso fetal estimado, su intervalo orientativo y el percentil aproximado.

La información obtenida no constituye un diagnóstico ni sustituye la interpretación de un profesional sanitario.

## Archivos principales

- `index.html`: estructura, contenido, metadatos SEO y datos estructurados.
- `css/style.css`: estilos de la herramienta y presentación para impresión.
- `js/config.js`: identidad, límites y configuración general.
- `js/core.js`: utilidades compartidas de validación, accesibilidad y presentación.
- `js/script.js`: validación específica, cálculo y representación de resultados.
- `icons/`: favicon y apple-touch-icon.
- `robots.txt` y `sitemap.xml`: configuración de rastreo y publicación.

## Uso local

Es un sitio estático sin proceso de compilación. Puede abrirse `index.html` directamente o servirse mediante un servidor HTTP estático.

## Privacidad

Los datos introducidos y los cálculos permanecen en el navegador. Google Analytics utiliza exclusivamente la propiedad común `G-QH8MJ6LVHN`.

## Publicación

El repositorio está configurado para publicarse en la URL oficial indicada. `CONFIG.herramienta.url`, canonical, Open Graph, Twitter Cards, `robots.txt` y `sitemap.xml` utilizan esa misma dirección.

## Licencia

Consultar [LICENSE](LICENSE).
