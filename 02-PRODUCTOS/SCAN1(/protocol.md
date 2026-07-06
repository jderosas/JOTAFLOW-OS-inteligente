# Protocolo SCAN12 v1.0

## Objetivo del protocolo

Convertir respuestas del formulario SCAN12 en una devolucion ejecutiva clara, accionable y validada humanamente.

## Entradas necesarias

- Formulario SCAN12 respondido.
- Nombre, empresa, rol, rubro y tamano aproximado.
- Motivo principal por el que responde.
- Respuestas cerradas de las 12 capacidades.
- Respuestas abiertas de cierre.

## Salida esperada

Una devolucion ejecutiva que incluya:

- lectura general;
- lectura por dimension;
- capacidades mas fuertes y mas fragiles;
- UMO principal candidata;
- Quick Win sugerido para 30 dias;
- posible continuidad a 90 dias;
- limite claro de la recomendacion.

## Secuencia

### 1. Recibir respuestas

Reunir las respuestas del formulario y verificar que las 12 preguntas principales esten completas.

Criterio de avance: no interpretar si falta informacion critica.

### 2. Calcular puntajes

Asignar puntaje:

| Opcion | Puntaje |
|---|---:|
| A | 0 |
| B | 1 |
| C | 2 |
| D | 3 |

Calcular:

- puntaje total;
- puntaje de Direccion;
- puntaje de Operacion;
- puntaje de Crecimiento;
- puntaje por capacidad.

### 3. Leer dimensiones

Clasificar cada dimension:

| Puntaje | Estado |
|---:|---|
| 0 a 3 | Critica / reactiva |
| 4 a 6 | Fragil / informal |
| 7 a 9 | En desarrollo |
| 10 a 12 | Ordenada / aprovechable |

### 4. Detectar capacidades prioritarias

Ordenar las 12 capacidades de menor a mayor puntaje.

Marcar:

- 3 capacidades mas fragiles;
- 3 capacidades mas ordenadas;
- contradicciones relevantes entre puntajes y respuestas abiertas.

### 5. Proponer UMO candidata

La UMO no se define solo por el menor puntaje.

Debe combinar:

- bajo puntaje;
- dolor declarado por el cliente;
- impacto potencial;
- posibilidad real de mejora en 30 dias;
- evidencia disponible;
- criterio de Joaquin.

Pregunta de control:

```text
Que punto es suficientemente importante para generar valor y suficientemente acotado para mejorar en 30 dias?
```

### 6. Diseñar Quick Win 30 dias

El Quick Win debe tener:

- objetivo claro;
- alcance chico;
- responsable;
- evidencia esperada;
- indicador simple;
- entregable visible.

No debe prometer transformacion total.

### 7. Preparar devolucion

Usar `output-report-template.md`.

La devolucion debe sonar ejecutiva, simple y concreta.

Debe evitar:

- juicio moral;
- lenguaje inflado;
- promesas vagas;
- diagnosticos excesivamente largos;
- recomendaciones imposibles de ejecutar.

### 8. Validacion humana

Joaquin revisa:

- coherencia de la UMO;
- tono de la devolucion;
- oportunidad comercial;
- limite de la promesa;
- proximo paso recomendado.

La IA puede asistir, pero no cerrar la conclusion final sin validacion humana.

### 9. Registrar evidencia

Luego de presentar la devolucion, registrar en `evidence.md`:

- fecha;
- cliente;
- UMO propuesta;
- reaccion del cliente;
- decision tomada;
- proximo paso;
- aprendizaje inicial.

### 10. Registrar aprendizaje

Cuando haya resultado observado, registrar en `learning-log.md`:

- que funciono;
- que no funciono;
- que debe ajustarse;
- que nueva version se recomienda.

