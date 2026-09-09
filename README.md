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

## 🎨 Principales Clases Disponibles

- `.apple-navbar`: Barra superior con desenfoque de fondo (*frosted glass*).
- `.apple-container`: Contenedor centrado y responsivo con márgenes Apple.
- `.apple-card`: Tarjeta blanca pura con bordes suaves y elevación atmosférica.
- `.apple-card-interactive`: Tarjeta con efectos al pasar el ratón y pulsar.
- `.apple-btn .apple-btn-primary`: Botón azul clásico de Apple.
- `.apple-btn .apple-btn-secondary`: Botón grisáceo suave.
- `.apple-input`: Campo de texto limpio con foco azul.
- `.apple-badge`: Etiquetas redondeadas de estado (`.apple-badge-blue`, `.apple-badge-green`).

---

## 🔄 Actualización Automática

Cualquier cambio realizado en las variables de `core.css` en este repositorio se propagará automáticamente a todas las aplicaciones que lo utilicen sin necesidad de cambiar su código individual.
