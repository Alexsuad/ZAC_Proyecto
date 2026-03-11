# File: output/bloque_1/tests/02_canvas_valor_prueba_controlada.md
# ──────────────────────────────────────────────────────────────────────
# Propósito: Versión de prueba controlada del Canvas de Propuesta de Valor.
# Rol: Verificar que la propuesta de valor queda alineada con los Documentos A y B corregidos.
# Nota: ARCHIVO DE PRUEBA — No reemplaza el oficial hasta validación explícita.
# ──────────────────────────────────────────────────────────────────────

**Proyecto:** Proyecto_automatizaciones  
**Subnicho de validación inicial:** Pyme transportista, 10–50 camiones (Zaragoza/Aragón)  
**Caso de entrada:** Viaje → Evidencia (POD/CMR/albarán) → Factura → Cobro (Doc-to-Cash)

---

## 1. Perfil del Cliente

**Segmento objetivo:** Pymes de transporte de cargas completas (FTL) con flotas de 10 a 50 vehículos. Operan a nivel nacional e ibérico, con gestión documental mayoritariamente manual o semi-digital. El cobro depende de la entrega correcta y verificable de los documentos de porte.

### 1.1 Tareas del cliente

- Asignar cargas a chóferes y evitar viajes en vacío.
- Recolectar los documentos de entrega firmados (CMR, albarán) para poder facturar el servicio al cargador.
- Cruzar costos de cada ruta (peaje, combustible, dietas) contra lo facturado para controlar el margen.
- Cumplir con la normativa del MITMA sobre control de tiempos de conducción y trazabilidad documental.

### 1.2 Dolores del cliente

- **[HIPÓTESIS] Cobros bloqueados por falta de documentación:** La factura no puede emitirse porque el CMR o el albarán firmado no llegó a tiempo, está incompleto o no queda vinculado al viaje correcto. Esto congela tesorería de forma recurrente. *Cómo se validará: midiendo el ciclo real "fin de viaje → factura emitida" en el cliente piloto (antes vs. después).*

- **[HECHO] Presión de márgenes operativos:** El combustible y el personal representan más del 60% de los costos directos, reduciendo la tolerancia a cualquier error de facturación o sobrecosto no reclamado. *(Fuente: Observatorio de Costes del Transporte de Mercancías por Carretera, MITMA, julio 2024.)*

- **[HIPÓTESIS] Carga administrativa manual:** El equipo de tráfico invierte horas diarias en reclamar documentos por WhatsApp, puntear albaranes contra la orden de carga y preparar la información para facturar. Este costo de horas no se mide, pero es real y repetitivo.

### 1.3 Ganancias esperadas

- Emitir la factura en menos de 24 horas desde la descarga, sin esperar a que el papel llegue físicamente a la oficina.
- Saber si un viaje ganó o perdió dinero tan pronto como se cierra la operación.
- Reducir el tiempo del equipo administrativo en tareas de seguimiento y reclamación de documentos.

---

## 2. Propuesta de Valor

**En una frase:**  
Diseñamos e implementamos un sistema de control operativo a medida que convierte el caos documental del ciclo de entrega en un flujo ordenado, trazable y listo para facturar, sin obligar a la empresa a cambiar su infraestructura actual.

### 2.1 Qué se diseña e implementa

El servicio se organiza a partir del proceso real del cliente, no de módulos predefinidos. Para el caso de entrada Doc-to-Cash, el trabajo típico incluye:

**Control de recepción documental**  
Se estructura la entrada de documentos por los canales que el cliente ya usa (correo, carpetas compartidas u otros). Se aplican reglas definidas con el cliente para determinar si cada documento es válido: ¿llegó? ¿es legible? ¿corresponde al viaje correcto? El resultado es un estado claro por cada viaje, visible para el equipo de tráfico y para la gerencia.

**Trazabilidad por operación**  
Cada viaje queda con su documentación vinculada, su estado de cobro y su historial de incidencias en un solo punto de consulta. Si hay un bloqueo, se sabe por qué y desde cuándo, sin bucear en correos ni en Excel.

**Alertas automáticas a responsables**  
Cuando un viaje lleva demasiado tiempo sin documentación completa, se genera una notificación al responsable correspondiente. El equipo deja de perseguir papeles manualmente; el sistema avisa.

**Panel de control para la dirección**  
Vista resumida que muestra cuántos viajes están listos para facturar, cuántos están bloqueados y por qué. Orientada a decisiones, no a reportes interminables.

### 2.2 Métricas de validación del piloto

| Indicador | Objetivo | Cómo se mide |
|---|---|---|
| Días entre fin de viaje y emisión de factura | Reducción medible frente a baseline | Antes vs. después sobre un mínimo de 20 operaciones |
| Horas semanales del equipo en seguimiento manual | Reducción de al menos 40% | Estimación de horas antes del piloto; medición durante y después |
| Viajes bloqueados por documentación incompleta | Reducción del número y del tiempo de resolución | Seguimiento semanal durante el piloto |

*Todos los indicadores son hipótesis a confirmar con datos reales del cliente piloto.*

---

## 3. Diferenciación y límites del servicio

### Por qué este servicio y no otras alternativas

- **Frente a suites TMS integrales (Dashdoc, SAP, Dynamics):** No exigen migrar ni reemplazar el sistema actual de la empresa. El servicio actúa en paralelo sobre el proceso documental, sin interrumpir la operación.
- **Frente a freelancers o scripts puntuales:** El servicio incluye implementación, puesta en marcha y mantenimiento continuo. No es una entrega única que el cliente tiene que sostener solo.
- **Frente a no hacer nada (Excel + WhatsApp):** El costo del desorden documental es real y recurrente. Este servicio lo hace visible y lo reduce con evidencia medible.

### Qué cubre y qué no cubre

**Cubre:**
- Diseño del sistema de control documental adaptado al flujo del cliente.
- Implementación técnica, integraciones con los canales y sistemas existentes.
- Puesta en marcha con datos reales y acompañamiento hasta la estabilización.
- Mantenimiento y ajuste cuando cambian las reglas o los formatos del cliente.

**No cubre:**
- Gestión contable, laboral o de nóminas.
- Sistemas de rastreo GPS o gestión de flotas en tiempo real.
- Reemplazo del ERP o TMS central de la empresa.
- Diagnósticos o informes sin entregable técnico posterior.

---

## 4. Hipótesis y cómo se validan

- **[HIPÓTESIS]** El bloqueo de facturas por falta de documentación de entrega es un problema frecuente y con impacto económico medible en pymes de transporte de 10–50 camiones.  
  *Validación: entrevistas con 3–5 gerentes del segmento. Si más del 60% lo identifica como problema recurrente, la hipótesis se refuerza.*

- **[HIPÓTESIS]** El cliente acepta delegar el control documental a un proveedor externo si el servicio se integra en sus canales actuales sin exigirle cambios de hábito al equipo operativo.  
  *Validación: en el piloto, medir si el equipo usa el sistema sin formación extensa a los 30 días. Objetivo: más del 80% de uso autónomo.*

- **[HIPÓTESIS]** El servicio es rentable para el cliente si el ahorro mensual en horas administrativas y en facturas desbloqueadas supera el costo del retainer mensual.  
  *Validación: en el piloto, calcular el ahorro real en horas × coste hora del administrativo. Si el ahorro mensual supera el precio del retainer, el ROI es positivo.*

---

*Nota de trazabilidad interna:*  
- notebook_id: a9776342-15b0-4d0d-9280-86fb060e7027  
- hito_note_id: ff2aa51a-0ab0-46c0-b313-bc64ee7d5589  
- auditoría semántica pendiente sobre esta versión de prueba
