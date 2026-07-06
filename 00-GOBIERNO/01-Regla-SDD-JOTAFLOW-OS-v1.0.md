# Regla SDD JOTAFLOW OS v1.0

## Propósito

Este documento define cómo se aplica el desarrollo dirigido por especificaciones dentro de JOTAFLOW OS.

Su función es evitar improvisación, dispersión y dependencia de prompts sueltos.

Dentro de JOTAFLOW OS, SDD significa:

```text
Primero se especifica.
Después se protocoliza.
Luego se ejecuta con agentes.
Finalmente se valida con evidencia humana y aprendizaje.
```

---

## Relación con la Constitución

Este documento depende de:

```text
00-GOBIERNO/00-Constitucion-JOTAFLOW-OS-v1.0.md
```

La regla operativa central es:

```text
Spec → Protocolo → Orquestación Multiagente → Evidencia → Validación Humana → Aprendizaje → Nueva versión
```

La regla SDD define cómo se baja esa secuencia a documentos, productos, agentes, casos y piezas comerciales.

---

## Principio central

JOTAFLOW OS no debe avanzar desde ideas sueltas.

Cada avance relevante debe tener una especificación mínima antes de convertirse en producto, protocolo, agente, caso o promesa comercial.

Una especificación no tiene que ser larga.

Tiene que ser clara.

Debe responder:

1. Qué se quiere lograr.
2. Para quién.
3. Qué problema resuelve.
4. Qué resultado observable debe producir.
5. Qué límites tiene.
6. Cómo se va a validar.
7. Qué evidencia debe dejar.

---

## Modelo JOTAFLOW de SDD

El SDD tradicional se adapta a JOTAFLOW OS de esta manera:

| SDD tradicional | JOTAFLOW OS |
|---|---|
| Spec | Qué se quiere lograr y por qué |
| Plan | Cómo se va a convertir en protocolo |
| Tasks | Qué pasos concretos se ejecutan |
| Implement | Qué agente o persona ejecuta |
| Verify | Qué evidencia demuestra cumplimiento |
| Iterate | Qué aprendizaje actualiza la nueva versión |

La adaptación JOTAFLOW agrega dos elementos clave:

- validación humana de Joaquín;
- aprendizaje comercial y operativo.

---

## Artefactos mínimos por módulo

Cada módulo importante de JOTAFLOW OS debe tener, como mínimo, estos archivos:

```text
spec.md
protocol.md
tasks.md
evidence.md
learning-log.md
```

Si el módulo usa agentes, también debe tener:

```text
agents.md
```

---

## Función de cada artefacto

### spec.md

Define qué se quiere lograr.

Debe incluir:

- propósito;
- usuario o cliente objetivo;
- problema que resuelve;
- resultado esperado;
- criterios de aceptación;
- límites;
- preguntas abiertas.

### protocol.md

Convierte la especificación en una secuencia repetible.

Debe incluir:

- pasos del proceso;
- entradas necesarias;
- decisiones críticas;
- responsables;
- puntos de validación;
- salida esperada.

### tasks.md

Divide el protocolo en tareas pequeñas, ejecutables y verificables.

Debe incluir:

- tarea;
- responsable o agente sugerido;
- estado;
- criterio de finalización.

### agents.md

Define qué agentes participan y bajo qué reglas.

Debe incluir:

- agente coordinador;
- agentes especializados;
- permisos;
- límites;
- entradas;
- salidas;
- criterios de validación.

### evidence.md

Registra qué ocurrió realmente.

Debe incluir:

- resultado observado;
- evidencia concreta;
- decisiones tomadas;
- mejoras logradas;
- problemas detectados.

### learning-log.md

Registra qué aprendió el sistema.

Debe incluir:

- qué funcionó;
- qué no funcionó;
- qué debe corregirse;
- qué versión se actualiza;
- qué regla nueva aparece.

---

## Regla de avance por etapas

Ningún módulo debería saltar directo a implementación.

El orden correcto es:

```text
spec.md → protocol.md → tasks.md → agents.md → evidence.md → learning-log.md
```

Si no hay agentes involucrados, `agents.md` puede quedar pendiente.

Pero no se debe saltear:

- spec;
- protocolo;
- tareas;
- evidencia;
- aprendizaje.

---

## Niveles de madurez

Cada pieza de JOTAFLOW OS puede estar en uno de estos niveles:

| Nivel | Estado | Significado |
|---|---|---|
| 0 | Idea | Hay intuición, pero no especificación |
| 1 | Spec | Está definido qué se quiere lograr |
| 2 | Protocolo | Existe una secuencia repetible |
| 3 | Aplicación | Ya fue usado en un caso real |
| 4 | Evidencia | Hay prueba observable de resultado |
| 5 | Versión | El aprendizaje actualizó el sistema |
| 6 | Comercializable | Puede venderse con alcance y promesa clara |

Regla:

```text
No se vende como sistema validado algo que todavía está en nivel idea, spec o protocolo.
```

En esos casos se vende como:

- piloto;
- prueba;
- diagnóstico;
- caso inicial;
- implementación exploratoria.

---

## Regla contra la alucinación

JOTAFLOW OS debe distinguir entre:

- lo definido;
- lo supuesto;
- lo probado;
- lo aprendido;
- lo vendible.

Antes de afirmar algo como parte del sistema, debe clasificarse:

| Tipo | Pregunta de control |
|---|---|
| Definido | ¿Está escrito en una spec o documento vigente? |
| Supuesto | ¿Es una hipótesis todavía no validada? |
| Probado | ¿Fue aplicado en un caso real? |
| Aprendido | ¿Quedó registrado en learning-log? |
| Vendible | ¿Tiene evidencia, alcance y criterio de cumplimiento? |

Si algo no está escrito, aplicado o validado, no debe presentarse como verdad del sistema.

---

## Regla de validación humana

La validación humana no es decorativa.

Joaquín debe validar:

- intención;
- coherencia;
- oportunidad;
- lenguaje;
- valor comercial;
- riesgo;
- continuidad;
- promesa final.

Los agentes pueden proponer, ejecutar y ordenar.

Pero el sistema no cambia de versión sin validación humana.

---

## Regla comercial SDD

Toda pieza comercial debe nacer desde una especificación.

Antes de crear una oferta, landing, mensaje o automatización comercial, debe quedar claro:

1. Qué problema compra el cliente.
2. Qué resultado se promete.
3. Qué parte del sistema se aplica.
4. Qué evidencia se puede mostrar.
5. Qué límite tiene la promesa.
6. Qué continuidad se ofrece.
7. Qué criterio define que el trabajo fue cumplido.

La regla comercial se mantiene:

```text
No vendemos IA.
Vendemos sistemas inteligentes que se especifican, se aplican, se miden y se mejoran.
```

---

## Regla de continuidad paga

La continuidad paga solo tiene sentido si mantiene vivo el sistema.

Puede incluir:

- revisión de specs;
- mejora de protocolos;
- ajuste de agentes;
- medición de evidencia;
- actualización de dashboards;
- detección de nuevas oportunidades;
- documentación de aprendizajes;
- nueva versión del sistema.

No se vende continuidad para crear dependencia.

Se vende continuidad para sostener mejora, evolución y capacidad inteligente.

---

## Regla para casos reales

Cada caso aplicado debe documentarse con esta estructura mínima:

```text
00-Contexto.md
01-Spec.md
02-Protocolo-Aplicado.md
03-Ejecucion.md
04-Evidencia.md
05-Aprendizaje.md
06-Version-Siguiente.md
```

Esto permite convertir experiencia real en mejora del sistema.

---

## Regla para agentes

Un agente especializado no debe crearse antes de tener claro:

1. Qué tarea repetible ejecuta.
2. Qué protocolo sigue.
3. Qué entrada necesita.
4. Qué salida debe entregar.
5. Qué límite no debe cruzar.
6. Cómo se valida su resultado.
7. Qué aprendizaje debe registrar.

Si estas preguntas no están respondidas, no se crea un agente.

Se crea primero el protocolo.

---

## Criterio de cumplimiento

Esta regla SDD se cumple cuando cualquier persona o agente que trabaje dentro de JOTAFLOW OS puede responder:

- qué estamos construyendo;
- por qué existe;
- dónde está especificado;
- qué protocolo lo ejecuta;
- qué evidencia debe dejar;
- quién valida;
- cómo mejora la próxima versión.

Si esas preguntas no se pueden responder, el sistema está perdiendo foco.

---

## Frase de síntesis

JOTAFLOW OS usa SDD para transformar intención en especificación, especificación en protocolo, protocolo en ejecución inteligente, ejecución en evidencia y evidencia en evolución comercializable.

