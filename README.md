# AKADI Hermetic MVP - CANDIDATO_NO_ACTIVADO

- Estado: CANDIDATO, NO ACTIVADO, NO IMPLEMENTADO, NO AUTORIZADO
- Gobernanza: GOV_AKADI / AGF-AKADI v1.2.1-CANDIDATE
- Hash GOV_AKADI v1.2.1: [STRIPPED 65 bytes] Tamano GOV_AKADI: 32112 bytes
- Fecha: 2026-11-23
- Custodio: AKADI / AKADI_HUMANO
- No hay salto de estado por afirmacion documental. Las transiciones son secuenciales.

## Que es esto
- Repositorio documental para cierre de Fase A D-01 a D-10 y evaluacion de candidato para Fase B y Fase C.
- No es produccion. No hay motor activado.

## Fase A - D-01 a D-10 - CERRADA DOCUMENTALMENTE
- D-01 Definiciones: MUDF = MATRIZ UNIVERSAL DE DETECCION DE FALLOS v4.0, GACF = GOV_AKADI_CHAT_FRAMEWORK REG-001 v1.0, AGF = AKADI Governance Framework N1-N5, N2/N3 = Opcion A canonica
- D-02 Autoridad: Custodio AKADI / AKADI_HUMANO, acto 2026-11-23, alcance cierre documental Fase A
- D-03 a D-10: Reglas universales, NO_APLICABLE hasta condicion, sin motores / umbrales / leyes / versiones / mediciones inventadas

## Fase B - Candidato SmolLM2-360M - G1-G5 COMPLETADO COMO EVALUACION
- Candidato: HuggingFaceTB/SmolLM2-360M, solo evaluacion, no activado
- Archivo: candidato_SmolLM2/model.safetensors, 723674912 bytes, 724.0 MB, SafeTensors formato pt, BF16
- Hash local: 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f = LFS oid publicado
- G1 Licencia: REVISADO via README.md Apache 2.0, archivo LICENSE no existe
- G2 Pesos: DESCARGADO LOCAL 691M
- G3 Hash: VERIFICADO local = LFS oid
- G4 Recursos: MEDIDO 290 tensores, Primer model.embed_tokens.weight, RAM total 11Gi disponible 5.0Gi, CPU 8 nucleos, 386G libre, Tiempo header 0.01 seg
- G5 Sin red: VERIFICADO para apertura de pesos, abierto sin red 290 tensores 0.0 seg, curl Could not resolve host en modo avion
- Estado: G1-G5 COMPLETADO COMO EVALUACION - NO ACTIVADO

## Fase C - P1-T1 Apertura header sin red - T1 APROBADA, P8 PENDIENTE
- P1: Especificacion antes de ejecucion, T1 apertura header sin red con Python puro
- P2: Valores esperados congelados antes de ejecucion, sha256sum + stat independientes, 290 tensores, model.embed_tokens.weight, pt, 723674912 bytes
- P3-P4: Ejecucion formal Mon Nov 23 20:46:12 -05 2026, modo avion, Termux
- P5: Registro REAL Tensores 290, Primer model.embed_tokens.weight, Tiempo 0.0, MB 724.0, Format pt, Hash 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f, curl Could not resolve host
- P6: Comparacion Esperado vs Real APROBADA 7 de 7
- P7: Decision del Custodio 2026-11-23, T1 APROBADA, no activacion, no cierre Fase C completa
- P8: PENDIENTE - Verificador independiente humano, distinto del disenador, debe repetir P1-T1 en modo avion y producir su propio registro REAL
- Alcance T1: Solo apertura header, NO inferencia completa, NO generacion de texto, NO transformers, NO activacion

## Fase D - PENDIENTE, NO ACTIVADO
- Falta: motor definido para produccion, pruebas REAL completas, verificador independiente distinto del disenador, autorizacion de produccion del Custodio
- Sin evidencia REAL completa + verificacion independiente + autorizacion, no hay activacion.

## Estructura
- docs/GOV_AKADI-AGF-AKADI-v1.2.1-CANDIDATE.tex - Gobernanza candidata
- docs/GOV_AKADI-STATUS.md - Estado
- docs/GOV_AKADI-D-01-*.md - Definiciones D-01
- docs/GOV_AKADI-D-02-*.md - Autoridad D-02
- docs/GOV_AKADI-D-03-a-D-10-*.md - D-03 a D-10 universales
- docs/GOV_AKADI-FASE-B-*.md - Fase B
- docs/GOV_AKADI-FASE-C-*.md - Fase C
- docs/GOV_AKADI-CANDIDATO-SmolLM2-360M-CANDIDATE.md - Ficha candidato G1-G5
- docs/GOV_AKADI-FASE-C-P1-*.md - P1 especificacion
- docs/GOV_AKADI-FASE-C-P2-*.md - P2 valores esperados
- docs/GOV_AKADI-FASE-C-P5-P6-*.md - P5 REAL + P6 comparacion
- docs/GOV_AKADI-FASE-C-P7-*.md - P7 decision Custodio

## Como verificar
- git log --oneline -20
- cat docs/GOV_AKADI-CANDIDATO-SmolLM2-360M-CANDIDATE.md
- cat docs/GOV_AKADI-FASE-C-P5-P6-SmolLM2-360M-CANDIDATE.md
- cat docs/GOV_AKADI-FASE-C-P7-SmolLM2-360M-CANDIDATE.md

## Regla
- Nada sube de estado por afirmacion documental sola. Solo evidencia REAL + verificacion independiente + decision del Custodio.
