# OPA²L · Banco de Retos Adicionales v2

## Contenido
Este proyecto contiene 90 situaciones problema contextualizadas:
- 10 para Unidad 1: Seguidor de voltaje
- 10 para Unidad 2: Comparador
- 10 para Unidad 3: Amplificador inversor
- 10 para Unidad 4: Amplificador no inversor
- 10 para Unidad 5: Sumador inversor
- 10 para Unidad 6: Integrador
- 10 para Unidad 7: Derivador
- 10 para Unidad 8: Filtro pasa bajas
- 10 para Unidad 9: Filtro pasa altas

Las problemáticas están redactadas como situaciones de aplicación y contienen:
1. Contexto/problema realista.
2. Datos técnicos.
3. Actividades de diseño, cálculo, simulación e implementación.

## Regla pedagógica
Cada reto está centrado exclusivamente en el circuito de la unidad correspondiente. No se exige combinar configuraciones de otras unidades.

## Archivos
- index.html: página principal.
- seguidor.html
- comparador.html
- inversor.html
- noinversor.html
- sumador.html
- integrador.html
- derivador.html
- pasabajas.html
- pasaaltas.html
- style.css: estilos globales e identidad visual.
- index-extra.css: estilos de la portada.
- script.js: banco de datos y comportamiento interactivo.

## Comportamiento
- La navegación muestra “Unidad 1”, “Unidad 2”, etc.
- Cada unidad tiene 10 botones de selección.
- “Generar reto aleatorio” selecciona una situación al azar.
- Al volver a cargar una unidad se intenta mostrar una situación diferente a la anterior.
- “Ver banco completo” muestra las diez problemáticas de la unidad.
- La selección anterior se guarda únicamente en localStorage del navegador.

## Responsive
La interfaz se adapta a:
- Computadores de escritorio.
- Portátiles.
- Tabletas.
- Teléfonos móviles.

No requiere servidor, PHP, base de datos ni instalación adicional.
