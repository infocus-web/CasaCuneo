# Casa Cuneo

Prototipo de la web y la plataforma de gestión del restaurante Casa Cuneo.

- **Sitio público**: carta, historia de la casa y reservas en 4 pasos con seña online (pago simulado).
- **Gestión** (`/#gestion`): reservas del día, plano del salón, cuentas por mesa con la seña descontada y ajustes de seña y cancelación.

Es un solo archivo estático (`index.html`), sin dependencias. Los datos de la demo se guardan en el navegador.

## Próximos pasos para la versión real
- Supabase: tablas de reservas, mesas, cuentas y consumos.
- Mercado Pago: cobro de la seña con webhook que confirma la reserva.
- Resend: comprobante de reserva por email.
