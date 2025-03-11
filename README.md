# Generador de Memoramas

Este proyecto es un generador de memoramas que permite crear un juego de memoria personalizado. El usuario puede definir el tamaño del grid, establecer un tiempo límite y cargar imágenes desde un archivo `.zip`. El memorama generado se puede descargar como un archivo `.zip` que incluye todo lo necesario para ejecutarlo.

## Características

- **Tamaño del Grid Personalizable**: El usuario puede definir el tamaño del grid (por ejemplo, 4 para un grid de 4x4).
- **Tiempo Límite Ajustable**: Se puede establecer un tiempo límite para completar el memorama.
- **Carga de Imágenes**: Las imágenes se pueden cargar desde un archivo `.zip`.
- **Efecto de Volteo**: Las cartas tienen un efecto de volteo al hacer clic.
- **Reinicio del Juego**: Cuando se acaba el tiempo o se gana el juego, se puede reiniciar con las cartas en nuevas posiciones.
- **Descarga en `.zip`**: El memorama generado se puede descargar como un archivo `.zip` que incluye:
  - `index.html`: El memorama listo para jugar.
  - `styles.css`: Los estilos del memorama.
  - `script.js`: La lógica del juego.
  - `images/`: Las imágenes proporcionadas.

## Instrucciones de Uso

1. **Ingresa el Tamaño del Grid**: Define el tamaño del grid (por ejemplo, 4 para un grid de 4x4).
2. **Establece el Tiempo Límite**: Ingresa el tiempo límite en segundos.
3. **Carga las Imágenes**: Sube un archivo `.zip` con las imágenes que se usarán en el memorama.
4. **Descarga el Memorama**: Haz clic en "Descargar Memorama" para generar y descargar el archivo `.zip`.
5. **Juega**: Descomprime el archivo `.zip` y abre `index.html` en tu navegador para jugar.

## Requisitos

- Navegador web moderno (Chrome, Firefox, Edge, etc.).
- Archivo `.zip` con imágenes en formato `.jpg`, `.jpeg`, `.png` o `.gif`.

## Ejemplo de Uso

1. El usuario ingresa `4` como tamaño del grid.
2. Sube un archivo `.zip` con al menos `8` imágenes (ya que se necesitan `8` pares para un grid de `4x4`).
3. Se descarga un archivo `memorama.zip` que contiene:
   - `index.html`: El memorama listo para jugar.
   - `styles.css`: Los estilos del memorama.
   - `script.js`: La lógica del juego.
   - `images/`: Las imágenes proporcionadas.
4. Al abrir `index.html`, el memorama se mostrará correctamente redimensionado, con el efecto de volteo y el temporizador funcionando.

## Contribuciones

¡Las contribuciones son bienvenidas! Si deseas mejorar este proyecto, sigue estos pasos:

1. Haz un fork del repositorio.
2. Crea una nueva rama (`git checkout -b feature/nueva-funcionalidad`).
3. Realiza tus cambios y haz commit (`git commit -am 'Añade nueva funcionalidad'`).
4. Haz push a la rama (`git push origin feature/nueva-funcionalidad`).
5. Abre un Pull Request.
