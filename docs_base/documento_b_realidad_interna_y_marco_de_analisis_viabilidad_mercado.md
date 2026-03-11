# DOCUMENTO B — REALIDAD INTERNA Y MARCO DE ANÁLISIS

## Viabilidad estratégica y mercado — Complementario al Dossier Empresarial

**Rol del documento:** Análisis interno. Base para tomar decisiones reales sobre el proyecto.  
**Complementa a:** Dossier Empresarial — Proyecto_automatizaciones (Documento A)

---

## 1. Propósito del documento

Este documento existe para evaluar el proyecto con honestidad. No es un documento de presentación ni de ventas. Su función es registrar la realidad interna, identificar los riesgos reales, y establecer las condiciones que determinan si el modelo de negocio es viable.

Cuando hay una decisión estratégica que tomar (qué cliente aceptar, qué proceso atacar primero, cómo fijar precios), este documento es la referencia correcta. El Documento A comunica hacia afuera; este documento orienta hacia adentro.

---

## 2. Aclaración de identidad y contexto

> [!IMPORTANT]
> - **Proyecto_automatizaciones** es un proyecto empresarial en proceso de validación. No está formalmente constituido como empresa todavía. El objetivo del período actual es validar el modelo con casos reales antes de formalizarlo.
> - **Zaragoza Activa / CONVIERTE** es el programa de acompañamiento bajo el que se está desarrollando esta validación. No es la empresa, ni la marca, ni el nombre del servicio.

La denominación "ZAC" no identifica al proyecto ante el mercado. Esta separación es importante para que la imagen comercial del proyecto no quede ligada al programa de incubación.

---

## 3. Qué hacemos realmente (la realidad interna del servicio)

Aunque externamente describimos el trabajo como "instalar control operativo", lo que hacemos en la práctica es más específico:

- Entendemos el proceso manual actual del cliente: cómo fluye la información, dónde se rompe, qué reglas se aplican (formalmente o de hecho).
- Diseñamos la lógica del sistema: qué datos capturar, qué reglas aplicar, qué alertas generar, qué mostrar en el tablero.
- Construimos la solución técnica: bases de datos, integraciones con los sistemas y canales existentes del cliente, interfaces para el equipo operativo.
- Ponemos en marcha el sistema con datos reales y acompañamos la estabilización.
- Mantenemos el sistema a lo largo del tiempo: ajustes cuando cambian los procesos o los formatos del cliente.

Internamente usamos Python como lenguaje principal, con herramientas específicas según el caso (bases de datos, integraciones de correo, tableros interactivos). La Inteligencia Artificial se incorpora solo cuando aporta valor medible (por ejemplo, lectura automatizada de documentos escaneados); no es el eje del servicio.

---

## 4. Capacidades reales del equipo fundador

**Conocimiento del sector:**  
Los fundadores tienen más de 20 años de experiencia operativa en logística y comercio exterior (transporte terrestre, aduanas, coordinación de clientes y proveedores). Esto acelera el análisis de los procesos del cliente y reduce las interpretaciones erróneas habituales en proyectos de digitalización. No es necesario que el cliente explique qué es un CMR o cómo funciona la liquidación de un transitario.

**Capacidad técnica interna:**  
El equipo puede desarrollar las soluciones sin subcontratar: backend, integraciones con sistemas existentes, automatizaciones y diseño de interfaces para usuario final. Esto da control sobre los tiempos, los costos y la calidad del trabajo entregado.

**Diseño de interfaces:**  
Hay capacidad interna para diseñar las pantallas y flujos que usará el equipo del cliente, con criterio de simplicidad. Si la herramienta no se adopta, no sirve: esto es parte del criterio de éxito desde el inicio.

---

## 5. Hipótesis que el proyecto necesita validar

El modelo de negocio descansa en tres hipótesis que aún no están confirmadas con datos:

1. **Hay un dolor pagable.** Las pymes logísticas tienen problemas de trazabilidad y control documental que les cuestan dinero de forma recurrente (facturas bloqueadas, errores de facturación, penalizaciones no gestionadas). Están dispuestas a pagar por una solución si el impacto es medible y el riesgo de adopción es bajo.

2. **El cliente acepta el modelo de implementación.** El cliente está dispuesto a trabajar con un proveedor externo que le instala un sistema a medida, en lugar de buscar un software genérico o un freelancer puntual. Valora la combinación de conocimiento del sector y capacidad técnica.

3. **El núcleo técnico es reutilizable.** Es posible construir soluciones a medida para distintos clientes sin tener que partir de cero en cada proyecto. Si cada implementación requiere el mismo esfuerzo independientemente del cliente anterior, el modelo no escala.

---

## 6. Segmento inicial de enfoque

**Pymes logísticas en Zaragoza:** empresas de transporte, transitarios y operadores de comercio exterior con operación activa.

Zaragoza es el punto de partida por razones prácticas: los fundadores están aquí, el acceso a clientes es más directo, y el ecosistema logístico de la zona (corredor ibérico y plataformas logísticas) ofrece suficiente densidad de empresas del perfil objetivo.

El mercado local es acotado. La hipótesis de expansión es que, una vez validado el modelo en Zaragoza, la metodología se puede replicar en otros hubs logísticos (Valencia, Barcelona, Madrid, y eventualmente otras ciudades europeas con corredores de transporte activos). Esa expansión no está planificada todavía; es una hipótesis de crecimiento a confirmar.

---

## 7. Oportunidad de mercado

Las pymes logísticas se encuentran en una situación frecuente: sus sistemas contables o ERP no cubren bien los procesos operativos de borde (incidencias, validación documental, trazabilidad de entregas), y llenar ese hueco con soluciones genéricas o freelancers puntuales no suele funcionar a largo plazo.

La oportunidad que identifica el proyecto está en ese espacio: un proveedor con conocimiento real del sector que puede diseñar e instalar sistemas adaptados al flujo específico del cliente, sin obligarle a reemplazar su infraestructura actual.

La diferenciación sostenible no está en la tecnología (que puede replicarse), sino en la combinación de comprensión operativa del sector y capacidad de implementación técnica propia.

---

## 8. Debilidades y límites actuales

- **Equipo pequeño con múltiples roles.** Actualmente los fundadores concentran la captación de clientes, el desarrollo técnico y el acompañamiento. Eso funciona en una fase inicial, pero limita la capacidad de atender varios proyectos en paralelo.

- **Sin historial comercial propio.** El proyecto no tiene clientes anteriores ni casos documentados. En B2B, esto genera resistencia en la fase de prospección, especialmente con empresas medianas. El piloto inicial sirve precisamente para construir esa evidencia.

- **Modelo de precios aún por validar.** No se sabe con certeza cuánto está dispuesto a pagar el cliente objetivo por el setup ni por el mantenimiento mensual. Eso se clarificará durante los primeros proyectos.

---

## 9. Riesgos comerciales y estratégicos

**Riesgo: el cliente quiere asesoría, no implementación.**  
Es habitual que una pyme pida "que le revisen los procesos" sin llegar a contratar el desarrollo de un sistema. Si el proyecto cae en esa dinámica, trabaja sin cobrar por ello. La mitigación es ser claros desde el primer contacto: el trabajo entregable es un sistema funcionando, no un informe.

**Riesgo: cada proyecto es totalmente único.**  
Si no hay un núcleo técnico reutilizable, cada implementación consume el mismo esfuerzo que la anterior. El modelo no escala y los márgenes se deterioran. Es necesario invertir desde el inicio en construir componentes reutilizables (validaciones, conectores de datos, plantillas de tableros).

**Riesgo: ciclos de venta B2B largos.**  
En B2B, el tiempo entre el primer contacto y la firma de un proyecto puede extenderse semanas o meses. Si el proyecto no tiene flujo de caja mientras espera cierres, es un problema financiero real. El piloto corto y gratuito (o de muy bajo costo) es una herramienta para acortar ese ciclo: el cliente ve el resultado antes de comprometerse.

**Riesgo: dependencia de un solo sector.**  
Enfocarse en logística tiene ventajas claras ahora, pero si el mercado logístico local tiene pocas empresas que encajen con el perfil, el volumen de clientes potenciales es limitado. La hipótesis es que la metodología se puede trasladar a otros sectores con procesos similares (distribución, manufactura con logística interna, etc.).

---

## 10. Condiciones para que el modelo sea viable

1. **Demostrar valor en el primer piloto.** Sin un caso real con métricas, el proyecto no tiene argumento comercial. El piloto no es opcional: es el paso más importante del período actual.

2. **Construir un núcleo técnico reutilizable.** Invertir tiempo en crear componentes que se puedan adaptar a distintos clientes, en lugar de construir todo desde cero cada vez.

3. **Establecer precios con margen real.** El modelo de setup + retainer solo funciona si el retainer cubre los costos de mantenimiento con margen positivo. Hay que calcular esto con datos reales, no estimaciones.

4. **Desarrollar un proceso de captación repetible.** La proximidad inicial a Zaragoza ayuda, pero hace falta un método claro para identificar clientes candidatos, presentar la propuesta y cerrar proyectos sin depender de contactos personales únicamente.

---

## 11. Papel de la solución inicial (el caso de entrada)

El proyecto arranca con un caso de uso acotado como punto de entrada comercial: el control documental en el ciclo de entrega-facturación de empresas de transporte (Doc-to-Cash).

Este caso fue elegido porque:
- El problema es concreto y reconocible por cualquier empresa de transporte.
- El impacto es medible desde el primer mes (facturas bloqueadas, tiempos de resolución).
- El alcance del piloto es acotado y no requiere integración con todos los sistemas del cliente.
- Sirve como demostración del modelo completo del proyecto: arranque guiado → sistema implementado → resultados medibles.

Este caso de entrada no define la identidad del proyecto. Es la puerta de entrada. Una vez validado, el proyecto puede aplicar la misma metodología a otros procesos del mismo cliente o a procesos distintos en clientes de otros sectores.

---

## 12. Criterios para las decisiones del repositorio

A medida que se produzcan otros entregables del proyecto (DAFO, Canvas, estrategia competitiva, propuesta de valor), deben alinearse con estos principios:

- El proyecto está en validación, no es una empresa ya consolidada. Las afirmaciones sobre el mercado y el modelo son hipótesis, no hechos demostrados.
- El servicio es diseño e implementación de sistemas a medida, no venta de software, licencias ni consultoría de procesos.
- La tecnología (automatización, integraciones, IA cuando aplica) es el medio de ejecución, no la propuesta comercial.
- El foco sectorial inicial es logística, pero no es la única opción a largo plazo.
