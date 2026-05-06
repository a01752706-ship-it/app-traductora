# Traductor AI — QWen2-0.5B

Aplicación web de traducción impulsada por inteligencia artificial que corre completamente en el navegador, sin servidores ni APIs externas.

<img width="1893" height="928" alt="image" src="https://github.com/user-attachments/assets/35da6dae-1e3e-461a-aa87-f6f6220b3d20" />

## Demo

[Ver aplicación en vivo](https://a01752706-ship-it.github.io/app-traductora/)

## Descripción

Esta app utiliza el modelo **QWen2-0.5B** ejecutado localmente en el navegador mediante [Transformers.js](https://huggingface.co/docs/transformers.js). El modelo se descarga una sola vez y queda en caché para usos posteriores.

## Características

- Traducción en el navegador sin conexión a servidores externos
- Sin costo por uso de API
- Interfaz oscura moderna y responsiva
- Barra de progreso durante la carga del modelo

## Uso

1. Abre la [demo en vivo](https://a01752706-ship-it.github.io/app-traductora/) o el archivo `index.html` directamente en tu navegador
2. Haz clic en **Cargar modelo** y espera a que se descargue (solo la primera vez)
3. Escribe el texto a traducir y obtén el resultado

## Tecnologías

- HTML / CSS / JavaScript (vanilla)
- [Transformers.js](https://huggingface.co/docs/transformers.js)
- Modelo: QWen2-0.5B
