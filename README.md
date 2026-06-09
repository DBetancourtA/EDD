# 🐍 Python con Listas — ITB

> Material interactivo de práctica para la asignatura de **Programación en Python** — Instituto Tecnológico de Negocios.

-----

## 📂 Contenido del repositorio

```
/
├── index.html          → Página de referencia: Parte 1 — Introducción a las Listas
├── taller-listas.html  → Taller con sistema de grupos y claves de acceso
└── README.md           → Este archivo
```

-----

## 🗂️ Clases disponibles

|# |Tema                                                                                                        |Archivo                                     |Estado        |
|--|------------------------------------------------------------------------------------------------------------|--------------------------------------------|--------------|
|01|**Introducción a las Listas** — Agregar, eliminar, buscar, ordenar                                          |[`index.html`](./index.html)                |✅ Disponible  |
|02|**Taller — Uso de Listas en Python** — Sistema de calificaciones, inventario, asistencia, encuesta y ranking|[`taller-listas.html`](./taller-listas.html)|✅ Disponible  |
|03|Diccionarios en Python                                                                                      |—                                           |🔜 Próximamente|
|04|Funciones y modularización                                                                                  |—                                           |🔜 Próximamente|
|05|Manejo de archivos `.txt` y `.csv`                                                                          |—                                           |🔜 Próximamente|
|06|Programación Orientada a Objetos (POO)                                                                      |—                                           |🔜 Próximamente|
|07|Introducción a Pandas y análisis de datos                                                                   |—                                           |🔜 Próximamente|

-----

## 🚀 Cómo usar este material

### Para estudiantes

1. Abre el enlace de GitHub Pages que te dio el docente.
1. Navega a la clase o taller que corresponde a la sesión.
1. Sigue el **paso a paso** de cada ejercicio.
1. Descarga el esqueleto `.py`, ábrelo en **VS Code** y completa las secciones marcadas con `# TODO`.
1. Ejecuta con **▶ Run Python File** o presiona `F5`.

### Para el taller en grupos

1. El docente asigna un número de grupo y entrega la **clave de acceso**.
1. Ingresa la clave en el ejercicio correspondiente para desbloquearlo.
1. Al finalizar, el docente dice la **clave de solución** para descargar el código resuelto.

-----

## 🛠️ Requisitos técnicos

- **Python 3.x** — [Descargar](https://www.python.org/downloads/)
- **Visual Studio Code** — [Descargar](https://code.visualstudio.com/)
- **Extensión Python para VS Code** — busca `ms-python.python` en el panel de extensiones
- Navegador moderno (Chrome, Firefox, Edge) — sin instalación adicional para ver las páginas

-----

## 👨‍🏫 Para el docente

Las contraseñas del taller se configuran directamente en el archivo `taller-listas.html`, en el bloque marcado al inicio del `<script>`:

```js
const ACCESS_PASSWORDS = {
  1: "grupo1",   // clave del Grupo 1
  2: "grupo2",   // clave del Grupo 2
  3: "grupo3",
  4: "grupo4",
  5: "grupo5"
};

const SOLUTION_PASSWORD = "profe2025"; // clave maestra para descargar soluciones
```

Cambia los valores antes de publicar. El sistema es completamente del lado del cliente — no requiere servidor ni base de datos.

-----

## 📡 Publicar en GitHub Pages

```bash
# 1. Crea un repositorio en GitHub (ej: itb-python-listas)
# 2. Sube los archivos
git init
git add .
git commit -m "primera clase: listas en Python"
git remote add origin https://github.com/TU_USUARIO/itb-python-listas.git
git push -u origin main

# 3. En GitHub: Settings → Pages → Branch: main → Save
# 4. Tu sitio estará en: https://TU_USUARIO.github.io/itb-python-listas
```

-----

## 🧱 Tecnologías

- HTML5 + CSS3 + JavaScript vanilla — sin dependencias externas
- Fuentes: [JetBrains Mono](https://fonts.google.com/specimen/JetBrains+Mono) · [Inter](https://fonts.google.com/specimen/Inter) vía Google Fonts
- Hospedaje: GitHub Pages (gratuito)

-----

<p align="center">
  Hecho para el <strong>Instituto Tecnológico de Negocios</strong> · ITB Ecuador
</p>