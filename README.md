# Veterinaria | PetShop

Sitio web estático de una veterinaria, creado como proyecto de práctica para aprender Tailwind CSS y construir una interfaz responsive con una identidad visual propia.

## Comportamiento

- La navegación lleva a las secciones de inicio, servicios, horarios y contacto.
- Las tarjetas de servicios se organizan en una columna en móviles, dos en pantallas medianas y cuatro en pantallas grandes.
- El horario muestra la atención de lunes a sábado, de 9:00 a. m. a 9:00 p. m., y domingos y festivos, de 9:00 a. m. a 6:00 p. m.
- El formulario solicita nombre, correo electrónico y mensaje, y utiliza la validación de campos obligatorios del navegador.

## Secciones

- Barra de navegación con enlaces a las secciones de la página.
- Presentación de la veterinaria.
- Cuatro tarjetas de servicios: consulta veterinaria, vacunación, baño y peluquería, y venta de alimentos y accesorios.
- Tabla de horarios de atención.
- Formulario de contacto.
- Pie de página.

## Identidad visual

La paleta de colores está definida en el tema de Tailwind:

| Uso      | Color     |
| -------- | --------- |
| Primario | `#6f4e37` |
| Acento   | `#d9822b` |
| Texto    | `#2b2b2b` |
| Fondo    | `#f6efe6` |

## Herramientas

- HTML5.
- Tailwind CSS 4.
- npm para administrar las dependencias y ejecutar la CLI de Tailwind.
- GitHub Pages para publicar el sitio.

## Ejecutar localmente

1. Instala las dependencias:

   ```bash
   npm install
   ```

2. Inicia Tailwind en modo de desarrollo:

   ```bash
   npm run dev
   ```

3. Abre `index.html` en el navegador. El modo de desarrollo observa los archivos y actualiza `src/output.css`.

Para generar una compilación minificada:

```bash
npm run build
```

**Sitio publicado:** [https://juajsia.github.io/proyecto-tailwind/](https://juajsia.github.io/proyecto-tailwind/)

**Autor:** Juan José Estrada
