# Biblioteca - Sistema de Gestión de Libros

Este proyecto implementa un sistema básico de gestión de libros para una biblioteca, desarrollado en Java. El sistema permite manejar información básica de libros, incluyendo funcionalidades de préstamo y devolución.

## Características

- Gestión de información básica de libros (título, autor, ISBN, número de páginas)
- Sistema de préstamos y devoluciones
- Verificación de disponibilidad de libros
- Generación de reportes detallados de libros
- Constructor de copia para duplicar registros de libros

## Estructura del Proyecto

El proyecto consta de dos clases principales:
- `Libro.java`: Clase principal que maneja la lógica de los libros
- `Main.java`: Clase con el programa principal y casos de prueba

## Funcionalidades Implementadas

### Clase Libro
- Gestión de atributos básicos (título, autor, ISBN, páginas)
- Métodos para préstamo y devolución
- Verificación de disponibilidad
- Generación de reportes mediante toString()

### Métodos Principales
- `prestarLibro()`: Gestiona el préstamo de libros
- `devolverLibro()`: Procesa la devolución de libros
- `verificarDisponibilidad()`: Consulta el estado actual del libro
- `toString()`: Genera reportes detallados

## Cómo Usar

1. Compile las clases Java:
```bash
javac Libro.java Main.java
```

2. Ejecute el programa principal:
```bash
java Main
```

## Ejemplos de Uso

```java
Libro libro = new Libro("Don Quijote", "Cervantes", "9788424922498", 863);
libro.prestarLibro();
System.out.println(libro.toString());
```

## Ejercicios Propuestos para Mejoras

1. Implementar validación de ISBN usando expresiones regulares
2. Agregar sistema de fecha de devolución
3. Implementar cálculo de multas por retraso
4. Integrar sistema de categorías/géneros literarios

## Contribuir

Las contribuciones son bienvenidas. Por favor, siéntase libre de:
- Reportar bugs
- Sugerir nuevas características
- Enviar pull requests

## Licencia

Este proyecto está bajo la Licencia MIT. Ver el archivo `LICENSE` para más detalles.
