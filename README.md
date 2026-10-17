# Binario y decimal para ESO

Página web interactiva para que el alumnado de **Computación y Robótica en la ESO** comprenda el paso de **binario a decimal** y de **decimal a binario**. Funciona en el navegador, sin instalar nada y sin recoger ningún dato de los alumnos.

🔗 **Pruébala aquí:** [ENLACE A LA PÁGINA]

## ¿Qué incluye?

1. **Interruptores:** cada interruptor es un bit (encendido = 1, apagado = 0) con el valor de su posición. Al pulsarlos se ve el número binario, la suma y el resultado en decimal.
2. **Binario → decimal:** explicación del método de sumar las posiciones que valen 1, con ejemplo y práctica.
3. **Decimal → binario**, con dos métodos explicados paso a paso:
   - **Método de la división:** se divide entre 2 hasta que el cociente es menor que 2, y se leen el último cociente y los restos de abajo hacia arriba.
   - **Método de la resta:** se recorren las potencias de 2 de mayor a menor, restando las que caben.
   
   Ambos incluyen una representación gráfica de cómo se haría **en el papel**.
4. **Practica:** retos aleatorios en los dos sentidos, con un modo **contrarreloj** de 60 segundos.
5. **Tabla de potencias de 2:** para consultar y memorizar.
6. **Ficha imprimible:** genera ejercicios nuevos al azar, con hoja de soluciones opcional.

La página permite elegir entre **4 bits (0–15)**, pensado para 1º de ESO, y **8 bits (0–255)**, para 3º de ESO.

## Uso en el aula

- Comparte el enlace de la página en Google Classroom u otra plataforma.
- Los alumnos pueden usarla desde ordenador, tablet o móvil.
- La ficha imprimible se genera desde la pestaña correspondiente y se imprime con el botón o con `Ctrl+P`.

## Uso en local

El proyecto es un único archivo, `index.html`, sin dependencias externas. Para usarlo sin conexión basta con descargarlo y abrirlo con cualquier navegador.

## Estructura

- `index.html`: la página completa (HTML, CSS y JavaScript en un solo archivo).
- `README.md`: este documento.

## Autoría y licencia

Creado por [TU NOMBRE] para uso educativo.
Licencia: [elige una, por ejemplo CC BY-SA 4.0 para materiales educativos, o MIT para el código].
