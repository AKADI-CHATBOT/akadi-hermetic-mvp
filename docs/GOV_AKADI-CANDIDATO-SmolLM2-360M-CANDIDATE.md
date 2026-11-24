# Candidato para evaluacion - SmolLM2-360M - CANDIDATO_NO_ACTIVADO

- Decision del Custodio: SmolLM2-360M exclusivamente como candidato para evaluacion.
- No se declara activacion ni cumplimiento total de G1-G5.
- Verificacion local realizada en Termux, 2026-11-23.

## Ficha documental del candidato
- Nombre exacto del checkpoint: HuggingFaceTB/SmolLM2-360M
- Repositorio oficial: https://huggingface.co/HuggingFaceTB/SmolLM2-360M
- Archivo de pesos: model.safetensors
- Formato: SafeTensors
- Precision reportada: BF16
- Tamano descargado: 691M, 723674912 bytes segun API, 723.56 MB segun README Memory footprint
- Hash local model.safetensors: 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f
- Hash local README.md: [STRIPPED 65 bytes] Hash local config.json: 34f7801487078de7e434e19162c497e5cc6ff397080e40e8586627cb68a5168a
- Hash local LICENSE: f36668ddf22403a332f978057d527cf285b01468bc3431b04094a7bafa6aba59 - corresponde a texto Entry not found, archivo LICENSE no existe

## Estado G1-G5
- G1 Licencia: REVISADO DOCUMENTALMENTE VIA README.md - README dice license: apache-2.0 y enlace a https://www.apache.org/licenses/LICENSE-2.0. Archivo LICENSE no existe en repo. Permite ejecucion local segun Apache 2.0. Pendiente revision juridica formal si se requiere.
- G2 Pesos accesibles: DESCARGADO LOCAL, ruta candidato_SmolLM2/model.safetensors, 691M
- G3 Hash comprobable: HASH LOCAL CALCULADO 7aaff6661428bed033abba9522bec81938678642cca3181fe752b6ca9e1e540f, falta comparar con referencia publicada en pagina del archivo
- G4 Recursos medidos: NO EVALUADO
- G5 Sin salida de red: NO EVALUADO

## Estado consolidado
- CANDIDATO_IDENTIFICADO - DESCARGA COMPLETADA - G1 REVISADO VIA README - G3 HASH LOCAL CALCULADO - NO ACTIVADO

## Siguiente paso
- Comparar hash local con referencia publicada en pagina del archivo
- Medir G4 recursos en dispositivo
- Probar G5 aislamiento sin red
- No se autoriza ejecucion ni activacion en este paso.
- Fuente: GOV_AKADI v1.2.1-CANDIDATE, decision del custodio, 2026-11-23.
