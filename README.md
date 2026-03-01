# 🌑 Falkon Dark Themes

Repositorio de **temas oscuros personalizados para el navegador Falkon**.
Este proyecto tiene como objetivo proporcionar esquemas visuales oscuros, minimalistas y ergonómicos, optimizados para entornos GNU/Linux y escritorios basados en Qt/KDE.

------

## 📌 Descripción

**Falkon Dark Themes** es una colección de configuraciones visuales diseñadas para:

- Reducir la fatiga visual.
- Integrarse con escritorios oscuros como KDE Plasma.
- Mantener consistencia con paletas modernas (Nord, Dracula, Solarized Dark, etc.).
- Ofrecer personalización avanzada mediante hojas de estilo (CSS).

------

## 🎯 Objetivos

- Proveer temas oscuros consistentes y bien estructurados.
- Permitir personalización modular.
- Mantener compatibilidad con versiones recientes de Falkon.
- Facilitar instalación manual y automatizada.

------

## 🖼️ Temas Incluidos

| Tema                    | Descripción                     | Estilo         |
| ----------------------- | ------------------------------- | -------------- |
| `Dracula-Falkon`        | Basado en la paleta Dracula     | Alto contraste |
| `Nord-Falkon`           | Tonos fríos y suaves            | Minimalista    |
| `Solarized-Dark-Falkon` | Balance cromático optimizado    | Profesional    |
| `Midnight-Blue`         | Azul profundo con grises suaves | Elegante       |

------

## 📦 Requisitos

- GNU/Linux
- Falkon ≥ 3.x
- Entorno Qt5 o Qt6
- (Opcional) KDE Plasma para mejor integración

------

## ⚙️ Instalación

### Método Manual

1. Clonar el repositorio:

```bash
git clone https://github.com/usuario/falkon-dark-themes.git
```

1. Copiar el tema deseado al directorio de configuración de Falkon:

```bash
mkdir -p ~/.config/falkon/themes
cp -r Dracula-Falkon ~/.config/falkon/themes/
```

1. Abrir Falkon → Preferencias → Apariencia → Seleccionar tema.

------

### Método con Script

```bash
chmod +x install.sh
./install.sh
```

------

## 🎨 Personalización

Puedes modificar:

- `userChrome.css`
- `userContent.css`

Ubicación típica:

```bash
~/.config/falkon/profiles/default/
```

Ejemplo para modificar color de fondo:

```css
QMainWindow {
    background-color: #1e1e2e;
}
```

------

## 📂 Estructura del Proyecto

```
falkon-dark-themes/
│
├── Dracula-Falkon/
├── Nord-Falkon/
├── Solarized-Dark-Falkon/
├── Midnight-Blue/
│
├── install.sh
└── README.md
```

------

## 🛠️ Compatibilidad

- Probado en:
  - KDE Plasma 5 y 6
  - Qt5 / Qt6
  - Distribuciones basadas en RHEL
  - Ubuntu / Debian

------

## 🚀 Futuras Mejoras

- Instalador con selector interactivo.
- Versión empaquetada (.tar.gz).
- Soporte para iconos SVG personalizados.
- Integración con scripts de automatización.

------

## 🤝 Contribuciones

1. Fork del proyecto.

2. Crear rama:

   ```bash
   git checkout -b feature/nuevo-tema
   ```

3. Commit y push.

4. Crear Pull Request.

------

## 📄 Licencia

MIT License

------

## 🧠 Motivación

Muchos usuarios de **Falkon** buscan una experiencia visual moderna sin depender de extensiones externas. Este repositorio centraliza configuraciones limpias, mantenibles y alineadas con estándares actuales de UI/UX en entornos Linux.