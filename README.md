# Pequeños Programadores 🧩

Aplicación educativa para aprender programación mediante bloques visuales, pensada para niños y adaptable a móviles y ordenadores.

## Ejecutar
Abre [index.html](./index.html) en un navegador moderno. La aplicación funciona sin conexión y no necesita instalar dependencias.

## Funciones implementadas
- Paleta de bloques de movimiento, aspecto, control y variables.
- Programa visual con bloques anidados, bloques **Repetir** y **Si / Si no**.
- Reordenación mediante botones y arrastrar/soltar.
- Ejecución continua, paso a paso, pausa y detención.
- Bloques de variables con nombre personalizable: asignar, incrementar y calcular.
- Operaciones aritméticas: suma, resta, multiplicación, división y resto.
- Condiciones con comparación de variables: mayor, menor, igual, mayor/igual, menor/igual y distinto.
- Mundo editable en cuadrícula con hasta 12 personajes independientes, obstáculos y monedas.
- Selector de personaje activo, creación/eliminación de personajes y colisiones entre ellos.
- Cada personaje conserva su posición, orientación, visibilidad y sprite personalizado.
- Taller de pixel-art táctil con lienzo de 16 × 16, selector de color y paleta rápida.
- Herramientas de dibujo: lápiz, borrador, cubo de pintura por zonas contiguas, líneas y rectángulos.
- Historial de deshacer y rehacer (hasta 40 cambios) y limpieza/relleno del lienzo.
- Exportación de sprites a PNG ampliado a 256 × 256 píxeles, conservando la transparencia.
- Los sprites dibujados aparecen en el mundo y se guardan dentro del proyecto exportado/importado.
- Tres escenarios de ejemplo, recogida de monedas y variables.
- Guardado automático local, guardado manual e importación/exportación de proyectos JSON.
- Interfaz adaptable a pantallas pequeñas y grandes.

## Estado y limitaciones
Esta es una implementación inicial funcional. El motor de mundo usa una cuadrícula 2D sencilla con varios personajes y colisiones por casilla: todavía no es un motor de plataformas con gravedad, físicas continuas, animaciones avanzadas ni colisiones complejas. El editor permite bloques anidados y dibujar sprites de 16 × 16 píxeles; todavía no incluye animaciones por fotogramas, redimensionado del lienzo ni capas. La ejecución paso a paso avanza por instrucciones, incluidas las que están dentro de contenedores.

No se ha completado una batería de pruebas automatizadas ni una validación en todos los navegadores y dispositivos. Las funciones deben probarse en el navegador de destino antes de usarse en un entorno educativo.

## Privacidad
Los proyectos se guardan localmente en el navegador. La aplicación no envía los programas a un servidor.

## Licencia
MIT (consulta [LICENSE](./LICENSE)).
