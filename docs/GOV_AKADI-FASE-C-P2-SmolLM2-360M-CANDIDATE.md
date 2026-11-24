# Fase C - P2 Valores esperados - SmolLM2-360M - CANDIDATO_NO_ACTIVADO

- Motor candidato: HuggingFaceTB/SmolLM2-360M
- Prueba: P1-T1 Apertura y lectura de header sin red
- Estado: VALORES ESPERADOS CONGELADOS ANTES DE EJECUCION FORMAL - NO EJECUTADA - NO ACTIVADO
- Fecha P2: 2026-11-23
- Custodio: AKADI / AKADI_HUMANO
- Herramienta independiente: sha256sum + stat + ls + Python con read(200000) y mmap parcial, distinto del metodo P1/G4

## Valores esperados P2 - NO SE AJUSTAN DESPUES
- Hash SHA-256 esperado via sha256sum: 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f
- Tamano esperado via stat: 723674912 bytes
- Tamano esperado via ls: 691M, 724.0 MB
- Tensores esperados: 290
- Primer tensor esperado ordenado: model.embed_tokens.weight
- Primer tensor esperado en header: model.embed_tokens.weight
- Formato esperado metadata: pt
- Curl en modo avion: debe fallar Could not resolve host huggingface.co

## Regla P2
- Si la ejecucion formal P3-P4 da un valor distinto, la prueba es FALLIDA.
- No se cambia P2 para que coincida con el resultado.
- No se cambia P1 para que coincida con el resultado.

## Siguiente
- P3-P4: Ejecucion controlada en modo avion, con registro REAL P5
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, decision del custodio, 2026-11-23.
