# MUEBLES NUVA · Tienda web

Tienda en línea de **MUEBLES NUVA** (Barranquilla, Colombia): muebles fabricados a mano
con envío gratis a toda Colombia y pago anticipado por transferencia o Nequi.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La tienda completa: catálogo, carrito y proceso de compra |
| `politicas.html` | Políticas legales (privacidad, datos, términos, envíos, devoluciones) |

Ambos son HTML autónomos, sin compilación ni dependencias. Se abren directamente
o se publican en cualquier hosting estático.

## Cómo comprar (flujo del cliente)

1. **Comprar** — agrega muebles al carrito (varios en el mismo pedido)
2. **Tus datos** — formulario con validación: cédula, celular colombiano, dirección con número
3. **Pago** — datos de transferencia y Nequi, con botón para copiar
4. **Confirmación** — número de pedido `NUVA-XXXXXX`

## Diseño

- **Color de marca:** `#D35400` (terracota), tomado del sitio actual de la tienda
- **Acento:** `#B08D57` (latón, por las bases doradas de los muebles)
- **Tipografías:** Fraunces (títulos) + Inter (texto)
- **Efectos:** titulares en cascada palabra por palabra, parallax en portada y llamado,
  botones con relleno curvo y destello, revelado de imágenes con cortina, botones magnéticos
- Respeta `prefers-reduced-motion` y cumple contraste AA

## Pendientes antes de publicar

- [ ] **Datos bancarios reales** — hoy son de relleno (`000-000000-00`), están en la constante `PAGO` de `index.html`
- [ ] **A dónde llegan los pedidos** — hoy solo se guardan en el navegador del cliente
- [ ] **Correo de confirmación** — la pantalla final lo promete y todavía no se envía
- [ ] **Opiniones reales** — las actuales son de ejemplo, en la constante `OPINIONES`
- [ ] **Días de entrega** por ciudad
- [ ] **Contenido de las políticas** en `politicas.html`
- [ ] **Links de redes sociales** en el pie
- [ ] **Fotos propias** — hoy se cargan del CDN de la tienda en Tiendanube
