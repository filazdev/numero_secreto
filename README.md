# Juego del Número Secreto

Este es un juego interactivo donde el jugador debe adivinar un número secreto generado aleatoriamente entre 1 y 10. El juego proporciona pistas sobre si el número ingresado es mayor o menor que el secreto, y permite reiniciar el juego después de acertar.

## Tecnologías Utilizadas

- **HTML**: Estructura básica de la página y la interfaz del usuario.
- **CSS**: Estilos para darle formato y diseño a la interfaz.
- **JavaScript**: Lógica del juego, generación de números aleatorios y manejo de eventos.

## Funcionalidades Principales

1. **Generación de un número secreto**: El juego genera un número aleatorio entre 1 y 10, asegurándose de que no se repita durante el juego.
2. **Interacción con el usuario**: El jugador ingresa su intento y recibe pistas sobre si el número es mayor o menor que el número secreto.
3. **Reinicio del juego**: Cuando el jugador adivina el número, puede reiniciar el juego para jugar nuevamente.

## Estructura del Código

- **HTML**: Define la estructura del juego, incluyendo la entrada de usuario y los botones de interacción.
- **CSS**: Estilos básicos para darle una apariencia atractiva al juego.
- **JavaScript**: Contiene la lógica del juego, manejando la generación de números, las validaciones y las interacciones con el usuario.

### Lógica del Juego en JavaScript

1. **`asignarTextoElemento(elemento, texto)`**: Modifica el contenido de un elemento HTML con el texto proporcionado.
2. **`verificarIntento()`**: Compara el número ingresado por el jugador con el número secreto y muestra una pista.
3. **`limpiarCaja()`**: Limpia el campo de entrada después de cada intento.
4. **`generarNumeroSecreto()`**: Genera un número secreto aleatorio que no se repita durante el juego.
5. **`condicionesIniciales()`**: Inicializa el juego, generando un nuevo número secreto y estableciendo los intentos a 1.
6. **`reiniciarJuego()`**: Resetea el juego, limpiando los campos y generando un nuevo número secreto.

## Instrucciones de Uso

1. Abre el archivo `index.html` en tu navegador.
2. Ingresa un número entre 1 y 10 en el campo de texto y haz clic en "Intentar".
3. El juego te dará una pista si el número ingresado es mayor o menor que el secreto.
4. Una vez adivinado el número, puedes hacer clic en "Nuevo juego" para reiniciar.

## Aprendizaje Adquirido

- **Manipulación del DOM**: Aprendí a modificar dinámicamente el contenido de la página y manejar la interacción con el usuario.
- **Generación de Números Aleatorios**: Implementé una función que genera números aleatorios sin repeticiones.
- **Eventos en JavaScript**: Utilicé eventos como `onclick` para ejecutar funciones específicas en respuesta a las acciones del usuario.
- **Estilos CSS**: Aprendí a usar CSS para diseñar una interfaz interactiva y atractiva para el usuario.

Este proyecto es una excelente manera de practicar la interacción entre HTML, CSS y JavaScript, creando un juego sencillo pero funcional que se puede extender con más características en el futuro.

