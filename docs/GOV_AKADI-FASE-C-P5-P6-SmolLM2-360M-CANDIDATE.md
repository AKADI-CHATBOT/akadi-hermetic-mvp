# Fase C - P5 Registro REAL + P6 Comparacion - SmolLM2-360M - CANDIDATO_NO_ACTIVADO

- Motor candidato: HuggingFaceTB/SmolLM2-360M
- Prueba: P1-T1 Apertura y lectura de header sin red
- Estado: EJECUTADA FORMALMENTE - APROBADA - NO ACTIVADO
- Fecha ejecucion formal: Mon Nov 23 20:46:12 -05 2026
- Entorno: Termux, modo avion, sin WiFi, sin datos
- Custodio: AKADI / AKADI_HUMANO

## P5 Registro REAL - Salida completa P5_REAL_T1.txt
- REAL Tensores: 290
- REAL Primer: model.embed_tokens.weight
- REAL Tiempo: 0.0 segundos
- REAL MB: 724.0
- REAL Format: pt
- Curl: curl: (6) Could not resolve host: huggingface.co
- HASH REAL via sha256sum: 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f

## P6 Comparacion Esperado P2 vs Real P5
- Hash: Esperado 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f = Real 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f - COINCIDE
- Tamano: Esperado 723674912 / 724.0 MB = Real 724.0 MB - COINCIDE
- Tensores: Esperado 290 = Real 290 - COINCIDE
- Primer tensor: Esperado model.embed_tokens.weight = Real model.embed_tokens.weight - COINCIDE
- Formato: Esperado pt = Real pt - COINCIDE
- Tiempo: Esperado <1 seg = Real 0.0 seg - COINCIDE
- Curl sin red: Esperado fallo Could not resolve host = Real fallo Could not resolve host - COINCIDE
- Resultado P6: APROBADA 7 de 7

## Lo que NO es esta prueba
- NO es inferencia completa con transformers
- NO es generacion de texto
- NO es activacion
- NO es Fase D

## Siguiente
- P7: Decision del Custodio sobre P1-T1
- P8: Verificador independiente humano repite P1-T1 con mismo procedimiento
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, decision del custodio, 2026-11-23.
