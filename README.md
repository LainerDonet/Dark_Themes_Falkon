# 🌑 Falkon Dark Themes

Perfecto. El proyecto contiene un único tema llamado **Falkon Dark Themes**, con estructura típica de tema nativo para el navegador Falkon (incluye `main.css`, `theme.svg`, `metadata.desktop` e íconos SVG).

Aquí tienes un README profesional y técnicamente preciso adaptado exactamente a tu proyecto:

------

# Tek-Phase_Blue

Dark Theme for Falkon

## 📌 Descripción

**Falkon Dark Themes** es un tema oscuro personalizado para el navegador Falkon.
Está diseñado con una estética sobria  y coherencia visual en iconografía SVG.

El tema modifica la apariencia de:

- Barra de pestañas
- Barra de navegación
- Botones e iconos
- Elementos de estado
- Componentes interactivos

Está implementado mediante:

- `main.css` (definición de estilos)
- `theme.svg` (recursos gráficos base)
- Iconografía SVG personalizada
- `metadata.desktop` (registro del tema en Falkon)

------

## 📂 Estructura del Proyecto

```
Tek-Phase_Blue/
│
├── main.css
├── theme.svg
├── metadata.desktop
├── README.md
├── README.txt
└── images/
    ├── arrow-down.svg
    ├── backp1.svg
    ├── forwardp1.svg
    ├── refreshp1.svg
    ├── tab-close.svg
    ├── star.svg
    └── ...
```

------

## ⚙️ Requisitos

- Falkon ≥ 3.x
- Entorno Qt5 o Qt6
- GNU/Linux (recomendado KDE Plasma para mejor integración visual)

------

## 🚀 Instalación

### Método Manual (Recomendado)

1. Localiza el directorio de temas de Falkon:

```
~/.local/share/falkon/themes/
```

Si no existe:

```bash
mkdir -p ~/.local/share/falkon/themes/
```

1. Copia la carpeta `Tek-Phase_Blue` dentro del directorio:

```bash
cp -r Dark_Themes_Falkon ~/.local/share/falkon/themes/
```

1. Abre Falkon.
2. Ve a:

```
Preferencias → Apariencia → Tema
```

1. Selecciona **Tek-Phase_Blue**.

------

## 🎨 Personalización

El comportamiento visual del tema está controlado principalmente por:

```
main.css
```

Puedes modificar:

- Colores de fondo
- Colores hover
- Bordes
- Radios
- Estados activos/inactivos

Ejemplo de modificación de fondo principal:

```css
QMainWindow {
    background-color: #0f172a;
}
```

------

## 🧩 Componentes Técnicos

### main.css

Define estilos Qt para widgets como:

- `QTabBar`
- `QToolButton`
- `QLineEdit`
- `QMenu`
- `QToolBar`

### theme.svg

Contiene recursos vectoriales base utilizados por Falkon para renderizar elementos gráficos del tema.

### metadata.desktop

Registra el tema para que Falkon lo detecte automáticamente.

------

## 🎯 Filosofía de Diseño

Tek-Phase_Blue sigue estos principios:

- Minimalismo funcional
- Bajo brillo (dark-friendly)
- Contraste suficiente para legibilidad
- Iconografía coherente
- Estética técnica moderna

------

## 🛠 Desarrollo

Si deseas modificar o extender el tema:

1. Edita `main.css`.
2. Ajusta o reemplaza iconos en `images/`.
3. Mantén consistencia en la paleta azul-oscura.
4. Prueba cambios reiniciando Falkon.

------

## 🐛 Problemas Conocidos

- Cambios en versiones futuras de Falkon podrían afectar compatibilidad de estilos Qt.
- Algunas extensiones pueden sobrescribir estilos visuales.

------

## 📄 Licencia

Este proyecto puede distribuirse bajo la licencia que el autor determine.
(Si deseas, puedo ayudarte a definir MIT, GPLv3 u otra licencia apropiada).

------

## 👤 Autor

Proyecto desarrollado como tema visual personalizado para Falkon.

Por : Lainer Felipe Donet Vasconcellos

------

Si quieres, puedo ahora:

- Convertirlo en un README más técnico (orientado a desarrolladores Qt).
- Hacerlo más visual y orientado a usuarios finales.
- Añadir badges de GitHub.
- Añadir sección de screenshots.
- Limpiar el proyecto eliminando el directorio `.git/` interno (recomendado antes de subirlo a GitHub).