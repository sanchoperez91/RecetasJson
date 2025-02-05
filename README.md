# Gestor de Recetas con Búsqueda Dinámica

Este proyecto es una aplicación web que permite buscar y visualizar recetas de cocina en función de diferentes criterios como nombre, horario, ingredientes y categoría. Se utiliza **HTML, CSS, JavaScript y JSON** para manejar y mostrar la información de forma dinámica.

## Características
- 📌 Carga y visualización de recetas desde un archivo JSON.
- 🔍 Búsqueda dinámica filtrando por nombre, horario, ingredientes o categoría.
- 📱 Interfaz responsiva y diseño estilizado con CSS.
- ⚡ Uso de JavaScript para generar y manipular elementos del DOM de manera dinámica.

## Tecnologías utilizadas
- **HTML**: Estructura de la página.
- **CSS**: Estilizado de la interfaz.
- **JavaScript**: Manipulación del DOM y llamadas AJAX.
- **JSON**: Fuente de datos de recetas.

## Instalación y uso
1. Clona este repositorio:
   ```sh
   git clone https://github.com/tuusuario/gestor-recetas.git
   ```
2. Abre el archivo `index.html` en un navegador.
3. Escribe un término de búsqueda en el campo correspondiente y presiona el botón para ver los resultados.

## Estructura del proyecto
```
/
├── index.html        # Estructura principal de la página
├── styles.css        # Estilos CSS
├── script.js         # Lógica en JavaScript
├── json/
│   ├── bd1.json     # Base de datos de recetas en formato JSON
└── README.md        # Documentación del proyecto
```

## 📌 Ejemplo de JSON de recetas
```json
{
  "recetas": [
    {
      "nombre": "Ensalada Mediterránea",
      "horario": "Almuerzo",
      "ingredientes": "Lechuga, tomate, aceitunas, queso feta",
      "categoria": "Saludable",
      "calorias": 200,
      "duracion": 15,
      "img": "img/ensalada.jpg"
    }
  ]
}
```

## Contribución
Si deseas mejorar este proyecto, haz un fork, crea una rama y envía un pull request con tus mejoras.

## Autor
Desarrollado por sanchoperez91.



