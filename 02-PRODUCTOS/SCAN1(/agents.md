# Agentes SCAN12 v1.0

## Principio

Los agentes asisten el proceso SCAN12, pero no reemplazan la validacion humana.

La regla se mantiene:

```text
La IA ejecuta.
Los agentes especializan.
JOTAFLOW coordina.
Joaquin valida.
La evidencia mejora el sistema.
```

## Agente coordinador

### JOTAFLOW Coordinador SCAN12

Funcion:

- recibir respuestas;
- activar scoring;
- pedir interpretacion;
- ordenar devolucion;
- marcar dudas;
- preparar version para validacion humana.

No puede:

- cerrar promesa comercial final;
- cambiar metodologia;
- inventar evidencia;
- presentar como validado algo que todavia es piloto.

## Agentes especializados posibles

| Agente | Tarea | Entrada | Salida | Validacion |
|---|---|---|---|---|
| Agente Scoring | Calcular puntajes y ranking. | Respuestas cerradas. | Tabla de puntajes. | Reglas de `scoring.md`. |
| Agente Interpretacion | Detectar patrones y UMOs candidatas. | Puntajes + respuestas abiertas. | Lectura preliminar. | Joaquin valida UMO. |
| Agente Devolucion | Redactar informe ejecutivo. | Interpretacion validada. | Borrador de devolucion. | Joaquin ajusta tono y promesa. |
| Agente Comercial | Sugerir siguiente paso comercial. | UMO + Quick Win. | Propuesta de proximo paso. | Joaquin decide oferta final. |
| Agente Evidencia | Registrar resultado del caso. | Devolucion + reaccion + resultado. | Entrada en `evidence.md`. | Joaquin confirma registro. |

## Criterio para automatizar

Automatizar solo cuando el paso sea repetible y tenga criterio claro.

Orden recomendado:

1. scoring;
2. ranking de capacidades;
3. borrador de devolucion;
4. registro de evidencia;
5. aprendizaje para version siguiente.

La seleccion final de UMO queda bajo validacion humana hasta tener evidencia suficiente.

