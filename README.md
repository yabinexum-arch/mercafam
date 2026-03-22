# 🛒 MercaFam Pro

**Tu asistente de compras familiar para toda Latinoamérica**

[![Demo en vivo](https://img.shields.io/badge/Demo-En%20vivo-brightgreen)](https://yabinexum-arch.github.io/mercafam)
[![Sin dependencias](https://img.shields.io/badge/Dependencias-Ninguna-blue)]()
[![Mobile First](https://img.shields.io/badge/Diseño-Mobile%20First-orange)]()
[![PWA](https://img.shields.io/badge/PWA-Instalable-purple)]()

---

## ¿Qué es MercaFam Pro?

MercaFam Pro es una aplicación web progresiva (PWA) diseñada para que cualquier familia organice, controle y analice sus compras del mercado. Funciona **100% offline**, sin necesidad de servidor ni base de datos — todo se guarda directamente en el dispositivo del usuario.

Pensada para amas de casa y familias latinoamericanas, ofrece una experiencia intuitiva tanto en celular como en computador.

> 🔗 **Demo en vivo:** [yabinexum-arch.github.io/mercafam](https://yabinexum-arch.github.io/mercafam)

---

## ✨ Funcionalidades

### 🛒 Hacer Mercado
- Lista de compras activa con checklist en tiempo real
- Registro de precio y cantidad por artículo
- Organización por **quincenas**: Q1 (1-15), Q2 (16-31), Tienda y Extras
- Presupuesto configurable con alerta visual al superar el límite
- Botón de duplicar artículos con un toque
- Autocompletado al agregar artículos del catálogo

### 📦 Artículos
- Catálogo personal de artículos con precios de referencia
- Búsqueda y filtro por categoría
- 11 categorías: Carnes, Aseo, Alimentos, Hogar, Bebidas, Higiene, Verduras, Frutas, Lácteos, Papelería, Otros

### 📅 Historial
- Registro completo de todos los mercados realizados
- Vista expandible por mes con detalle por quincena
- Acceso rápido a cualquier mercado anterior

### 📈 Estadísticas
- Análisis inteligente del gasto mensual
- **Inflación personal**: compara precios actuales vs primeros registros por artículo
- Gráfica de gasto por mes
- Distribución por categoría (gráfico donut)
- Artículos más comprados
- Evolución de categorías en el tiempo

### 📊 Comparativa
- Comparación visual de gasto entre meses
- Gráfica por categoría con leyenda interactiva
- Detalle desglosado por categoría

### 🧮 Calculadora
- Calculadora integrada con historial de operaciones
- Calculadora flotante disponible también dentro del módulo de mercado

### ⚙️ Extras
- **Recibo de compra** al finalizar el mercado (formato ticket)
- **Actualización masiva de precios** de referencia desde el recibo
- **Compartir por WhatsApp** la lista de compras
- **Backup y restauración** de datos en formato JSON
- **Tutorial de onboarding** para nuevos usuarios
- **Pantalla de bienvenida** personalizada con nombre y avatar
- Instalable como app en Android y iOS (PWA)

---

## 🎨 Diseño

- Tema **oscuro / claro** con un toque
- Diseño **Mobile First** optimizado para Android
- Navegación inferior con íconos SVG animados
- Fuentes: Inter + JetBrains Mono (Google Fonts)
- Paleta de colores consistente con variables CSS

---

## 🛠 Tecnologías

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura |
| CSS3 + Variables CSS | Estilos y temas |
| JavaScript (Vanilla ES6) | Lógica completa |
| localStorage | Almacenamiento de datos |
| Canvas API | Gráficas (donut chart) |
| PWA / Web App Manifest | Instalación como app |
| Google Fonts | Tipografía |

> **Sin frameworks. Sin dependencias externas de JS.** Todo el código es nativo del navegador.

---

## 🚀 Instalación y uso

### Opción 1 — Usar en el navegador (sin instalación)
Abre directamente: [yabinexum-arch.github.io/mercafam](https://yabinexum-arch.github.io/mercafam)

### Opción 2 — Instalar como app en el celular
1. Abre el link en Chrome (Android) o Safari (iOS)
2. Toca el menú del navegador
3. Selecciona **"Agregar a pantalla de inicio"** o **"Instalar app"**
4. La app funciona desde ese momento sin conexión a internet

### Opción 3 — Descargar el archivo
1. Descarga `index.html`
2. Ábrelo en cualquier navegador moderno
3. No requiere servidor ni instalación adicional

---

## 📁 Estructura del proyecto

```
mercafam/
└── index.html          # App completa en un solo archivo
    ├── <style>         # ~1,400 líneas de CSS (tema oscuro/claro, responsive)
    └── <script>        # ~2,300 líneas de JS (lógica, módulos, datos)
```

---

## 🔒 Privacidad

Todos los datos se guardan **exclusivamente en el dispositivo del usuario** mediante `localStorage`. No se envía ningún dato a servidores externos. La app funciona completamente sin conexión después de la primera carga.

---

## 📄 Licencia

© 2025 MercaFam Pro. Todos los derechos reservados.

---

*Hecho con ❤️ para las familias latinoamericanas*
