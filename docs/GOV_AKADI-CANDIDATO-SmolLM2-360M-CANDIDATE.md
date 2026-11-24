# Candidato para evaluacion - SmolLM2-360M - CANDIDATO_NO_ACTIVADO

- Decision del Custodio: SmolLM2-360M exclusivamente como candidato para evaluacion.
- No se declara activacion ni cumplimiento total de G1-G5.
- Verificacion local realizada en Termux, 2026-11-23.

## Ficha documental del candidato
- Nombre exacto del checkpoint: HuggingFaceTB/SmolLM2-360M
- Repositorio oficial: https://huggingface.co/HuggingFaceTB/SmolLM2-360M
- Archivo de pesos: model.safetensors
- Formato: SafeTensors, formato pt en metadata
- Precision reportada: BF16
- Tamano: 723674912 bytes, 724.0 MB
- Hash local model.safetensors: [STRIPPED 65 bytes] Hash publicado LFS oid: 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f
- Hash local README.md: [STRIPPED 65 bytes] Hash local config.json: 34f7801487078de7e434e19162c497e5cc6ff397080e40e8586627cb68a5168a

## Estado G1-G5
- G1 Licencia: REVISADO DOCUMENTALMENTE VIA README.md - Apache 2.0, enlace a https://www.apache.org/licenses/LICENSE-2.0. Archivo LICENSE no existe.
- G2 Pesos accesibles: DESCARGADO LOCAL, ruta candidato_SmolLM2/model.safetensors, 691M
- G3 Hash comprobable: VERIFICADO - Hash local = Hash publicado LFS oid, tamano 723674912 coincide
- G4 Recursos medidos: MEDIDO EN DISPOSITIVO - RAM total 11Gi, disponible 5.0Gi, libre 313Mi, Swap 11Gi, CPU 8 nucleos, Almacenamiento 478G total 386G libre, Tensores 290, Primer tensor model.embed_tokens.weight, Tiempo abrir header 0.01 segundos, Tamano 724.0 MB, Formato pt
- G5 Sin salida de red: NO EVALUADO

## Estado consolidado
- CANDIDATO_IDENTIFICADO - G1 REVISADO - G2 DESCARGADO - G3 VERIFICADO - G4 MEDIDO - G5 PENDIENTE - NO ACTIVADO

## Siguiente paso
- Probar G5 aislamiento sin red en modo avion
- No se autoriza ejecucion ni activacion en este paso.
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, decision del custodio, 2026-11-23.
