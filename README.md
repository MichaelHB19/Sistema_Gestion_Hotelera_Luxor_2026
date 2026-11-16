# Sistema de Gestión Hotelera - Hotel Luxor (PMS)

## Integrantes del Equipo
* Jordy Rolando Tejada Lazo (Analista Líder / Desarrollador)
* Michael Steve Hurtado Bejarano (Evaluador de Calidad / Arquitecto Web)
* Kevin Pedro Yare Chulunquia (Responsable de Configuración / Desarrollador)
* José Manuel Jaita Chura (Analista de Riesgos y Costos / Desarrollador)

---

## Objetivo del Proyecto
Desarrollar un producto de software web funcional (Property Management System) para la administración integral del Hotel Luxor, optimizando los procesos operativos de reservas, control de habitaciones, registro de huéspedes, estancias, pagos y generación de reportes financieros y estadísticos.

---

## Requisitos Funcionales (RF)
1. **RF-01 (Registro de Reserva):** Registrar una reserva con huésped, habitación, fechas, tarifa, importe y estado, verificando disponibilidad.
2. **RF-02 (Consulta de Reservas):** Consultar reservas por criterio, estado y rango de fechas, mostrando listado y detalle sin modificar datos.
3. **RF-03 (Edición de Reservas):** Editar los datos de una reserva y recalcular importe y disponibilidad, excluyendo la propia reserva de la comparación.
4. **RF-04 (Cancelación de Reservas):** Cancelar una reserva Pendiente o Confirmada, conservando su registro y liberando la disponibilidad correspondiente.
5. **RF-05 (Registro de Huéspedes):** Registrar huéspedes con identificación y datos personales, controlando formatos y duplicidad por tipo y número de documento.
6. **RF-06 (Consulta de Huéspedes):** Consultar huéspedes mediante criterio o filtros, con orden ascendente por apellidos y detalle de consulta.
7. **RF-07 (Edición de Huéspedes):** Editar datos del huésped preservando como no editables el tipo y número de documento.
8. **RF-08 (Registro de Pagos):** Registrar pagos en efectivo o transferencia, asociados al huésped y la reserva, con fecha y responsable.
9. **RF-09 (Consulta de Pagos):** Consultar pagos por huésped, fecha o modalidad, mostrando el detalle en modo de solo lectura.
10. **RF-10 (Eliminación de Pagos):** Eliminar un pago únicamente si la reserva asociada está Pendiente o Cancelada, con confirmación y recálculo del saldo.

---

## Requisitos No Funcionales (RNF)
1. **RNF-01 (Disponibilidad):** Atención del módulo de recepción las 24 horas del día (servicio 24 h/día).
2. **RNF-02 (Seguridad):** Autenticación y permisos por rol para proteger información personal y restringir el acceso.
3. **RNF-03 (Rendimiento):** Tiempo máximo de 2 segundos en la búsqueda del historial de huéspedes (umbral menor o igual a 2 s).
4. **RNF-04 (Respaldo):** Respaldo automático de la base de datos cada 24 horas, programado a las 00:00.
5. **RNF-05 (Concurrencia):** Soporte de registros simultáneos en temporada alta.

---

## Cronograma del Proyecto
Puedes consultar el cronograma detallado de actividades, fases e hitos del proyecto en el siguiente enlace:
[Ver Cronograma Completo en Google Sheets](https://docs.google.com/spreadsheets/d/1SKPj9q5H6jslAHcK-98jFi0Ce2P9pwwAuuccE_cCHi8/edit?usp=sharing)
