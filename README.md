# Proyecto de Eliminación de Fondo de Imágenes

Este proyecto utiliza Node.js y TypeScript para eliminar el fondo de imágenes utilizando la librería `@imgly/background-removal-node`.

## Requisitos Previos

Antes de ejecutar el proyecto, asegúrate de tener instalado:

- Node.js v23.9.0 o superior
- Git
- TypeScript

## Instalación y Configuración

1. Clona el repositorio desde GitHub:
   ```sh
   git clone https://github.com/NicolasMorgani/eliminar-background-typescript.git
   ```

2. Accede al directorio del proyecto:
   ```sh
   cd eliminar-background-typescript
   ```

3. Instala las dependencias:
   ```sh
   npm install
   ```

4. Compila el código TypeScript a JavaScript:
   ```sh
   npx tsc
   ```

## Uso

1. Coloca la imagen de entrada en la raíz del proyecto con el nombre `FotoPerfil1.jpeg`.
2. Ejecuta el script para procesar la imagen:
   ```sh
   node dist/index.js
   ```
3. La imagen con el fondo removido se guardará en `output-image.png`.

## Estructura del Proyecto

```
📂 tu-repositorio/
│── 📂 src/
│   └── index.ts
│── 📂 dist/ (generado después de compilar)
│── FotoPerfil1.jpeg (imagen de entrada)
│── output-image.png (imagen de salida)
│── package.json
│── tsconfig.json
│── README.txt
```

## Contacto
Si tienes preguntas o sugerencias, no dudes en abrir un issue en el repositorio de GitHub.

