# NewsBrief

> Proyecto 01 · Inmersión ONE: Agentes de IA para Negocios

**NewsBrief** es un panel de inteligencia de noticias que utiliza agentes de IA para transformar información de actualidad en un resumen ejecutivo y una página web estructurada, adaptada a un sector y una región específicos.

## ¿Cómo funciona?

El usuario define cuatro parámetros:

- **Sector:** industria o área de interés.
- **Región:** ámbito geográfico de cobertura.
- **Fecha mínima:** límite temporal para las publicaciones.
- **Número de noticias:** cantidad de resultados solicitados.

A partir de estos datos, el sistema recopila y estructura noticias, genera recursos visuales, elabora un análisis ejecutivo y construye una página HTML autónoma en español.

## Arquitectura

El flujo se implementa en Google Opal mediante cinco módulos especializados que coordinan la recopilación de información, su estructuración, la generación de contenido y la construcción de la interfaz.

La arquitectura separa el procesamiento de noticias del análisis ejecutivo, permitiendo desarrollar ambos en paralelo antes de integrarlos en el resultado final.

## Resultado

Cada ejecución genera un panel web que integra:

- Feed de noticias con fechas, resúmenes y palabras clave.
- Imagen principal adaptada al tema.
- Síntesis ejecutiva y conclusiones relevantes.
- Implicaciones prácticas para el negocio.
- Pregunta de seguimiento para orientar la vigilancia estratégica.

## Diseño y tecnología

La salida es un documento HTML autónomo, con estilos integrados y sin dependencias externas de frontend. La interfaz sigue un sistema visual minimalista, con jerarquía tipográfica clara, contenido en español y una presentación orientada a la lectura ejecutiva.

## Ejemplos

- `examples/NewsBrief-Actuarial.html` — Sector asegurador y previsional.
- `examples/NewsBrief-Actuarialv2.html` — Versión con análisis ejecutivo integrado.
- `examples/NewsBrief-DataScience.html` — Aplicación al sector de Data Science.

---

_Proyecto experimental de aplicación de agentes de IA a la inteligencia de negocios._