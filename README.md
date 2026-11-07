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
- Mundo editable en cuadrícula con personaje, obstáculos y monedas.
- Tres escenarios de ejemplo, recogida de monedas y variables.
- Guardado automático local, guardado manual e importación/exportación de proyectos JSON.
- Interfaz adaptable a pantallas pequeñas y grandes.

## Estado y limitaciones
Esta es una implementación inicial funcional. El motor de mundo usa una cuadrícula 2D sencilla: todavía no es un motor de plataformas con gravedad, físicas continuas, animaciones avanzadas ni colisiones complejas. El editor permite bloques anidados, aunque su experiencia visual y accesibilidad todavía pueden mejorarse. La ejecución paso a paso avanza por instrucciones, incluidas las que están dentro de contenedores.

No se ha completado una batería de pruebas automatizadas ni una validación en todos los navegadores y dispositivos. Las funciones deben probarse en el navegador de destino antes de usarse en un entorno educativo.

## Privacidad
Los proyectos se guardan localmente en el navegador. La aplicación no envía los programas a un servidor.

## Licencia
MIT (consulta [LICENSE](./LICENSE)).
