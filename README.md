# Simulación de Gestión de Recursos

## Descripción del Proyecto
Este proyecto es una simulación de gestión de recursos diseñada para ayudar a los estudiantes a explorar sistemas y arquitecturas de programación. La simulación se centra en la interacción del usuario, la transición entre escenas y la extensión del sistema para aumentar la complejidad de la simulación.

## Objetivos del Proyecto
Los estudiantes deberán:
- Implementar la funcionalidad de gestión de escenas.
- Configurar la persistencia de datos.
- Aplicar conceptos de herencia y polimorfismo.
- Utilizar abstracción y encapsulación para mejorar la reusabilidad y proteger los datos.
- Optimizar el código.

## Escenas del Proyecto
El proyecto contiene dos escenas principales:
1. **Menu**: Un menú de inicio donde los usuarios pueden lanzar la simulación y cerrar la aplicación.
2. **Main**: Una escena de simulación ambientada en un almacén.

Además, hay una escena adicional llamada **Optimization**, utilizada para estudiar y optimizar el código.

## Interacciones del Usuario
El usuario debe poder:
- Lanzar la escena de simulación desde el menú de inicio.
- Volver al menú de inicio desde la escena de simulación.
- Salir de la aplicación.
- Seleccionar un color para aplicarlo a las Unidades de Transporte (montacargas) en la simulación. El último color elegido debe ser preseleccionado la próxima vez que se inicie la aplicación.

## Funcionalidades Básicas de la Simulación
La simulación incluye:
- Dos tipos de Pilas de Recursos que producen elementos a una velocidad de 0.5 por segundo.
- Dos tipos de Unidades:
  - Una Unidad (trabajador) que puede moverse.
  - Una Unidad de Transporte (montacargas) que puede transportar recursos a una base predefinida.

El usuario puede:
- Mover la cámara por el espacio del almacén usando las teclas de flecha o WASD.
- Seleccionar objetos definidos haciendo clic izquierdo y abrir una superposición de UI con sus detalles.
- Mover las Unidades haciendo clic derecho en cualquier ubicación o en una Pila de Recursos.

## Requisitos Adicionales de la Simulación
- Crear una nueva Unidad de Productividad que aumente la producción de recursos en una base.
- Refinar y optimizar el código aplicando principios de programación orientada a objetos.

## Estilo del Proyecto
El proyecto está ambientado en un almacén con un estilo de baja poligonización. Los estudiantes pueden personalizar el tema del proyecto importando sus propios activos.

## Scripts Proporcionados
El proyecto incluye varios scripts parcialmente o completamente escritos:

- **Base.cs**: Subclase de Building, almacena una referencia singleton.
- **Building.cs**: Clase base abstracta para ResourcePile y Base.
- **ColorHandler.cs**: Crea botones de color para la selección de color de las Unidades de Transporte.
- **ResourcePile.cs**: Subclase de Building, produce recursos a una velocidad específica.
- **TransporterUnit.cs**: Subclase de Unit, transporta recursos de una Pila de Recursos a la Base.
- **Unit.cs**: Clase base abstracta para todas las Unidades, controla el movimiento, color y comportamiento.
- **UserControl.cs**: Maneja la entrada del usuario, mueve la cámara y controla la funcionalidad de clics.

## Checklist de Tareas
1. Gestión de escenas:
   - Crear transiciones entre dos escenas.
   - Configurar botones para controlar las transiciones.
   - Configurar un botón para salir de la aplicación.

2. Persistencia de datos:
   - Configurar botones para aplicar un color a los objetos en una segunda escena.
   - Guardar el último color elegido y preseleccionarlo en el próximo inicio de la aplicación.

3. Herencia y Polimorfismo:
   - Crear un nuevo tipo de objeto en la simulación con una variación en el comportamiento derivada de una clase base.

4. Abstracción:
   - Refactorizar para reducir el código duplicado y mejorar la reutilización.

5. Encapsulación:
   - Utilizar getters y setters para proteger los datos.

6. Optimización del código:
   - Perfilar el código para identificar problemas básicos de optimización.

¡Buena suerte con tu proyecto!
