# App para revendedores (Vinted, Wallapop…) — Utilidades del MVP

Pregunta central: **¿Cuánto gano de verdad?**
Público: revendedor habitual (ropa vintage, zapatillas, rastro, electrónica). No el que vacía el armario una vez.
Regla de oro: añadir un producto en menos de 10 segundos; marcarlo vendido con un toque.

## MVP (versión 1)

### 1. Alta rápida de producto
Foto · nombre · categoría · precio de compra · dónde lo compraste · fecha · costes extra (limpieza, reparación).

### 2. Estados del producto
En stock → Publicado → Vendido (→ Devuelto). Plataforma: Vinted, Wallapop, otra.

### 3. Venta y beneficio real
Al marcar vendido: precio de venta · plataforma · envío que pagas tú · comisiones/destacados · embalaje.
Resultado: beneficio neto del producto y margen %.

### 4. Control de tiempo
Botones rápidos por producto (5 / 15 / 30 min) para buscar, limpiar, fotos, publicar y enviar.
Temporizador para sesiones (ir al rastro, tarde de publicar).
Resultado: **€ por hora real**.

### 5. Gastos generales
Lo que no es de un producto: gasolina, cajas y bolsas, destacados, suscripciones. Se resta del beneficio del mes.

### 6. Panel principal
Beneficio neto del mes · € por hora · nº de ventas · valor del stock · margen medio · días medios en vender · categorías más rentables.

### 7. Stock parado
Avisos a los 30 y 60 días sin vender, con sugerencia de rebaja.

### 8. Contador de Hacienda (DAC7)
Ventas y facturación del año por plataforma frente a los umbrales (30 ventas o 2.000 €). Aviso al acercarse.
Exportar resumen anual (CSV/Excel).

## Después del MVP (versión 2)
- IA: precio sugerido a partir de la foto.
- IA: título y descripción del anuncio listos para pegar en Vinted/Wallapop.
- Sincronización en la nube y varios dispositivos.
- Informe anual en PDF.
- Recordatorio de envíos pendientes.

## Fuera de alcance
Conexión directa con Vinted/Wallapop (no hay API oficial).

## Decisiones pendientes
- Formato: web app instalable (recomendado) o app nativa.
- Datos: guardados en el móvil + exportar (recomendado para el MVP) o con cuenta en la nube.
- Nombre de la app.
- Precio: gratis hasta X productos, Pro 3,99–4,99 €/mes.
