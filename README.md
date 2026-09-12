# entrega-final-automatizacion
# Sistema de Información Automatizada de Carreras

Ecosistema de Automatización IA — Trabajo final.

**Orquestador:** n8n · **Base de datos:** Airtable · **IA:** Google Gemini (gemini-3.6-flash) · **Canal de salida:** Gmail

## Enlaces obligatorios

- 🔗 Base de datos (Airtable, modo lectura):https://airtable.com/invite/l?inviteId=inv69D8Sk8WZW8Jdd&inviteToken=29fd03c97e23f47fb8f57750e19e415ec572aeada1fe84a40d34bdd0fd74a3b0&utm_medium=email&utm_source=product_team&utm_content=transactional-alerts]
- 📊 Dashboard de control (Airtable Shared View): https://airtable.com/invite/l?inviteId=inv69D8Sk8WZW8Jdd&inviteToken=29fd03c97e23f47fb8f57750e19e415ec572aeada1fe84a40d34bdd0fd74a3b0&utm_medium=email&utm_source=product_team&utm_content=transactional-alerts)

## Contenido del repositorio

- `Documentacion_Sistema_Info_Carreras.pdf` — Diagrama de arquitectura + esquema de datos + matriz de costos + seguridad y resiliencia.
- `flujo-n8n.json` — Lógica del flujo exportada desde n8n.
- `screenshots/` — Capturas de evidencia (ejecución exitosa, ramas de error, registros en Airtable, correo recibido).

## Caso de uso

Un estudiante completa un Google Form solicitando información sobre una carrera. El sistema busca los datos reales en Airtable, genera una respuesta personalizada con IA, permite revisión humana (HITL) cuando el estudiante dejó una consulta libre, y entrega el correo final sin intervención manual en el caso estándar.
