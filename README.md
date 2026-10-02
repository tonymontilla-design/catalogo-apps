# Catálogo de Aplicaciones — Landing de alta conversión

Landing estática (un solo `index.html`, sin build) con las 8 aplicaciones de `PROYECTOS`:
VLYO ERP, VendeRD AI, Lavandería 123, foodOS, MOVIA, MovilidadRD, PRESTAMO360 y POS Express.

## Ver local

Abre `index.html` en el navegador (doble clic). No requiere servidor.

## Configurar (obligatorio)

Arriba del `<script>` final hay una constante:

```js
const WHATSAPP = "18090000000";
```

Cámbiala por tu número real (código país + número, sin `+` ni espacios).
Todos los botones "Solicitar demo" y el flotante usan ese número con mensaje pre-llenado por app.

## Desplegar gratis (Vercel)

1. Sube esta carpeta a GitHub (`catalogo-apps`).
2. Vercel → Add New → Project → Import → Deploy (sin Root Directory, es estático).
3. Opcional: conecta tu dominio.

## Secciones

Hero + stats → Catálogo (8 cards) → Por giro de negocio → Beneficios →
Proceso 4 pasos → FAQ (8 objeciones) → CTA final → Footer + WhatsApp flotante.
