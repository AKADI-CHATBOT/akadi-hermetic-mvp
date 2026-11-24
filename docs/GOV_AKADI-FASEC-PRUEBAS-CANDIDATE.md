# Fase C - Pruebas controladas - CERRADO CORREGIDO

- Entrada segun GOV_AKADI v1.2.1: fase B y criterios con umbrales (D-04).
- Decision: Fase C = NO_APLICABLE hasta definir motor + umbrales D-04 + especificacion de prueba.
- Regla universal: Aplica a todos los motores.
- Correccion: Version anterior no estaba en repo y faltaban P6 y P8 exactos. Se corrige aqui.

## Por que no se puede ejecutar Fase C ahora
- Fase B: NO_APLICABLE hasta definir motor. Sin motor, no hay motor que probar.
- D-04 Umbrales: NO definidos. D-04 = NO_APLICABLE hasta motor y evaluacion de riesgo.
- Especificacion de prueba fijada con hash (P1): NO existe para ningun motor.
- Pruebas reales: No acreditadas segun Estado vigente del documento.

## Procedimiento P1-P8 exacto segun documento
- P1: La especificacion se fija, con archivo y hash, antes de escribir el componente.
- P2: Los valores esperados se calculan con una herramienta independiente del componente probado, por ejemplo sha256sum.
- P3: El ejecutor lee los casos desde la especificacion y no contiene casos propios.
- P4: Cada registro incluye, antes de la ejecucion, los hashes de la especificacion, del componente y del ejecutor.
- P5: Un registro no se modifica despues de calcular su hash. Un cambio posterior genera un incidente y un nuevo registro.
- P6: Los bloques con comandos se guardan en un archivo o se ejecutan desde variables; no se pegan como texto en la terminal.
- P7: Un resultado distinto del esperado se registra como FALLIDA para ese caso. La especificacion no se modifica para que pase.
- P8: Una validacion requiere un validador distinto del disenador, en un entorno distinto, y la obtencion de los hashes de referencia.

## GA-COMP-001 y GA-EVI-001
- GA-COMP-001: IMPLEMENTADO como artefacto de prueba. No acredita capacidad alguna.
- GA-EVI-001: IMPLEMENTADO como artefacto de prueba. VALIDADO pendiente de dos validadores independientes.
- No son capacidades del sistema. No acreditan pruebas reales de ningun motor.

## Alcance
- Cierre documental Fase C. No es ejecucion de pruebas, no es evidencia REAL.
- Cuando se defina motor, umbrales D-04 y especificacion de prueba, Fase C se reabre para ejecutar pruebas controladas.
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, Seccion Hoja de ruta condicionada y Procedimiento de evidencia, decision del custodio, 2026-11-23.
