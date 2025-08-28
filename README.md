# Calculadora Interactiva

## Descripción
Este es un proyecto de una **calculadora interactiva** hecha con **HTML, CSS y JavaScript**. Permite hacer operaciones básicas como sumar, restar, multiplicar y dividir.  

Los scripts de JavaScript se cargan de forma **asíncrona o diferida** para mejorar el rendimiento:

- **`async`**: El script se descarga y ejecuta tan pronto como esté listo, sin esperar a que se cargue todo el HTML. Se usa para scripts que no dependen del DOM o de otros scripts.  
- **`defer`**: El script se descarga mientras se carga el HTML, pero **se ejecuta al final**, después de que todo el DOM esté listo. Ideal para scripts que necesitan interactuar con elementos de la página.  

En este proyecto:

- `loader.js` → `async` porque solo simula carga y no depende del DOM.  
- `calculator.js`, `ui.js`, `validator.js`, `app.js` → `defer` porque necesitan que la página y otros scripts estén listos antes de ejecutarse.  


## Cómo usar
1. Abrir `index.html` en el navegador.  
2. Escribir los dos números.  
3. Elegir la operación.  
4. Hacer clic en **Calcular** y ver el resultado.  

