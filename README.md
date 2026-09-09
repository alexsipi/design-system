# 🍎 NIIU Labs Design System for Apps Ecosystem

Sistema de diseño centralizado con estética Apple (limpio, blanco y minimalista) para todo el ecosistema de aplicaciones (personales, herramientas internas y soluciones para clientes).

---

## 🚀 Cómo usar en cualquier aplicación

Para aplicar este estilo a cualquier app (`Diet`, `Finance`, `Gym`, etc.), simplemente incluye esta línea en el `<head>` de tu `index.html`:

```html
<!-- Cargar el Sistema de Diseño Centralizado -->
<link rel="stylesheet" href="https://alexsipi.github.io/design-system/core.css">
```

*(O si prefieres usar la CDN directa de GitHub con jsDelivr):*
```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/alexsipi/design-system@main/core.css">
```

---

## 🎨 Principales Clases Disponibles (.niiu-)

- `.niiu-navbar`: Barra superior con desenfoque de fondo (*frosted glass*).
- `.niiu-container`: Contenedor centrado y responsivo con márgenes Apple.
- `.niiu-card`: Tarjeta blanca pura con bordes suaves y elevación atmosférica.
- `.niiu-card-interactive`: Tarjeta con efectos al pasar el ratón y pulsar.
- `.niiu-btn .niiu-btn-primary`: Botón azul clásico de Apple.
- `.niiu-btn .niiu-btn-secondary`: Botón grisáceo suave.
- `.niiu-input`: Campo de texto limpio con foco azul.
- `.niiu-badge`: Etiquetas redondeadas de estado (`.niiu-badge-blue`, `.niiu-badge-green`).

*(Nota: las clases `.apple-*` se mantienen como alias para compatibilidad retroactiva).*

---

## 🔄 Actualización Automática

Cualquier cambio realizado en las variables de `core.css` en este repositorio se propagará automáticamente a todas las aplicaciones que lo utilicen sin necesidad de cambiar su código individual.
