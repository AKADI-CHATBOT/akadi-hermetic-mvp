# Fase C - P1 Especificacion de prueba - SmolLM2-360M - CANDIDATO_NO_ACTIVADO

- Motor candidato: HuggingFaceTB/SmolLM2-360M
- Prueba: P1-T1 Apertura y lectura de header sin red
- Estado: ESPECIFICACION ANTES DE EJECUCION - NO EJECUTADA - NO ACTIVADO
- Fecha especificacion: 2026-11-23
- Custodio: AKADI / AKADI_HUMANO

## P1-T1 Objetivo
- Verificar que model.safetensors se puede abrir sin red, sin libreria safetensors, con Python puro, y que el header es legible y deterministico.

## Entrada
- Archivo: candidato_SmolLM2/model.safetensors
- Hash SHA-256 esperado: [STRIPPED 65 bytes] Tamano esperado: 723674912 bytes, 724.0 MB
- Entorno: Termux en Android, modo avion, sin WiFi, sin datos

## Procedimiento exacto
- 1. Poner modo avion
- 2. Ejecutar lectura de header con Python puro: struct + json, sin safetensors, sin transformers, sin torch
- 3. Leer 8 bytes header length, luego header JSON, contar claves sin __metadata__
- 4. Registrar Tensores, Primer tensor, Tiempo, MB, Metadata format
- 5. Intentar curl a huggingface.co, debe fallar Could not resolve host

## Salida que debe producir
- Tensores: 290
- Primer tensor: model.embed_tokens.weight
- Metadata format: pt
- MB: 724.0
- Curl: fallo sin red

## Criterio de exito P1-T1
- Abre sin red OK
- Tensores = 290 exacto
- Primer tensor = model.embed_tokens.weight exacto
- Formato = pt
- Curl falla sin red
- Si un valor difiere, la prueba es FALLIDA, no se ajusta el esperado.

## Lo que NO es esta prueba
- NO es inferencia completa con transformers
- NO es generacion de texto
- NO es activacion
- NO es Fase D

## Siguiente
- P2: Valores esperados calculados con herramienta independiente, antes de ejecutar P1-T1 como prueba formal de Fase C
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, decision del custodio, 2026-11-23.
