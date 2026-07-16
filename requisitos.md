# Requisitos Módulo Viajes

## Requisitos No Funcionales

| # | Requisito | Descripción |
|---|-----------|-------------|
| 1 | **Seguridad** | Cifrado SSL/TLS para todas las comunicaciones. Autenticación con token JWT. |
| 2 | **Rendimiento** | Soporte para 1,000 solicitudes por segundo (req/s) sin degradación del servicio. |
| 3 | **Disponibilidad** | Tiempo de respuesta menor a 2 segundos. |
| 4 | **Concurrencia** | Manejo de 1,000 usuarios concurrentes sin bloqueos. |

---

## Historias de Usuario

### US-01: Ver viajes cercanos en tiempo real

**COMO:** Chofer de la plataforma  
**QUIERO:** Visualizar los viajes disponibles en un radio cercano a mi ubicación actual, actualizados en tiempo real  
**PARA:** Poder seleccionar el viaje más conveniente sin perder tiempo ni combustible

#### Criterios de Aceptación (Gherkin)