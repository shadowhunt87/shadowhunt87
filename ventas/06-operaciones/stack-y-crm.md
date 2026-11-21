# Stack Tecnológico y CRM

## Herramientas recomendadas

| Necesidad | Opción recomendada | Alternativa económica |
|---|---|---|
| CRM | HubSpot Sales Hub (Starter) | Pipedrive / Zoho CRM |
| WhatsApp para equipos | WhatsApp Business API + bandeja compartida (integrada al CRM) | WhatsApp Business App + etiquetas |
| Email marketing y automatización | HubSpot Marketing / Brevo | Mailchimp |
| Agenda de reuniones | Calendly / agenda integrada del CRM | Google Calendar con página de citas |
| Videollamadas | Google Meet / Zoom | - |
| Grabación y análisis de llamadas | Fathom / tl;dv | Grabación nativa de Meet |
| Prospección B2B | LinkedIn Sales Navigator | LinkedIn gratuito + Apollo |
| Firma electrónica | DocuSign / PandaDoc | Firma con PDF |
| Diseño | Canva Pro / Figma | - |
| Dashboards | Reportes del CRM + Looker Studio | Google Sheets |
| Pagos | Pasarela local (Azul, CardNet) + transferencia | Enlace de pago |

> Selección final **`[VALIDAR]`** según presupuesto. Criterio número uno: que integre WhatsApp, porque es el canal principal del mercado.

## Configuración mínima del CRM

### Objetos y campos obligatorios
- **Contacto:** nombre, teléfono/WhatsApp, email, cargo, fuente (UTM), consentimiento de contacto.
- **Empresa:** nombre, industria, tamaño, ciudad, línea de producto de interés.
- **Negocio (deal):** producto, plan, valor (MRR o monto de proyecto), etapa, próximo paso, fecha de próximo paso, fecha estimada de cierre, motivo de pérdida.

### Pipelines separados
1. SaaS (Taller Pro RD + POS)
2. Servicios (Ciberseguridad + Desarrollo)
3. Academy B2B
4. Alianzas

### Automatizaciones esenciales
- Asignación round-robin de leads a los SDR.
- Alerta si un lead nuevo no se contacta en 5 minutos.
- Tarea automática al cambiar de etapa.
- Alerta de deal sin actividad por 7 días.
- Al marcar "Ganado": crear ticket de onboarding y notificar a CS.
- Encuesta NPS automática el día 30 y cada 90 días.

## Higiene de datos
- Revisión semanal de duplicados y campos vacíos (RevOps).
- **Regla:** lo que no está en el CRM no cuenta para comisión.
- Seguridad: accesos con 2FA, permisos por rol y baja de accesos el mismo día en que un colaborador sale.
