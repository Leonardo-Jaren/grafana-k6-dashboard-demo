# Grafana k6 Dashboard Demo

Pulse es una propuesta interactiva para explorar un panel de rendimiento con modos de API y navegador.

> **Demo:** todas las métricas son simuladas. No ejecuta Grafana k6, no realiza solicitudes a la URL indicada y no mide la capacidad real de un sistema.

## Funciones

- Configuración de URL, método HTTP, usuarios virtuales, duración y perfiles de carga.
- Modos API y navegador con métricas, gráficos y umbrales simulados.
- Historial temporal y exportación de un reporte JSON.

## Ejecutar

Abre `index.html` en un navegador moderno. Chart.js y las fuentes se cargan desde servicios externos, por lo que los gráficos y la tipografía requieren conexión a Internet.

## Tecnologías

HTML, CSS, JavaScript y Chart.js.

## Alcance

La demo no contiene backend ni un ejecutor de k6. Evita introducir secretos; la URL se incluye en los reportes exportados.
