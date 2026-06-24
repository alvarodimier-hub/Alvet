# ALVET

ALVET es una app web de una sola página (sin dependencias ni proceso de build) para el registro de actividad veterinaria, pensada para cirujanos y anestesistas independientes.

## Funcionalidades

- **Casos**: registrar cirugías/anestesias realizadas (fecha, clínica, paciente, procedimiento, cirujano/anestesista, estudios complementarios, monto cobrado y notas).
- **Calendario**: vista mensual con los casos ya realizados y los turnos agendados a futuro, con detalle por día.
- **Insumos**: control de stock con aviso de faltantes y registro de gastos/compras.

## Cómo usarla

Es un único archivo HTML autocontenido (`ALVETE.html`). Basta con abrirlo en cualquier navegador moderno; no requiere servidor ni instalación.

Los datos se guardan únicamente en el `localStorage` del navegador donde se use, por lo que no se sincronizan entre dispositivos ni se envían a ningún servidor.
