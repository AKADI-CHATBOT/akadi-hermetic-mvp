# GOV_AKADI / AGF-AKADI - Estado de integracion

Archivo: docs/GOV_AKADI-AGF-AKADI-v1.2.1-CANDIDATE.tex
Version: 1.2.1-CANDIDATE
Fecha del documento: 23 de noviembre de 2026
SHA-256: 905be608cb58b1944c64b874002ec7793b13f62534b371e71eb4872fad55461a

## Estado real - no cambiar sin evidencia

- Tipo: Borrador de diseno para revision humana.
- Estado: CANDIDATE. NO VIGENTE como norma de produccion.
- Implementacion: NO IMPLEMENTADO.
- Activacion: NO ACTIVADO.
- Autorizacion: NO AUTORIZADO.

Este documento describe diseno, alcance, requisitos, controles y plan de verificacion.
No acredita implementacion, validacion, autorizacion, activacion ni operacion real
de ninguna capacidad, segun su propia Seccion 1.

## Regla que se preserva al integrar

La existencia de este documento en el repositorio, su nivel de detalle o su
coherencia interna NO constituyen por si mismos aprobacion AGF, incorporacion
contractual, implementacion, pruebas ejecutadas, verificacion independiente,
autorizacion de produccion ni activacion. Ningun estado se eleva por afirmacion
documental.

## Relacion con akadi-hermetic-mvp

- akadi-hermetic-mvp es el MVP hermetico existente, con su propio estado
  declarado en README.md y docs/MATURITY.md.
- Este archivo GOV_AKADI / AGF-AKADI es una capa de gobernanza / diseno
  propuesta, en estado CANDIDATE. No sustituye ni reescribe el estado del MVP.
- No usar este archivo para afirmar que el MVP esta en produccion real bajo
  AGF-AKADI, ni que AGF-AKADI esta operando.

## Que falta para avanzar

- Fase A - cierre documental: resolver D-01 y D-02.
- Fase B - evaluacion de motores: G1 a G5 documentadas para al menos un motor
  y, si se usa comprobacion de integridad, GA-EVI-001 en estado VALIDADO.
- Fase C - pruebas controladas: criterios con umbrales (D-04).
- Fase D - decision de activacion: evidencia REAL verificada por verificador
  independiente + autorizacion emitida por autoridad competente.

Decisiones pendientes: D-01 a D-10 (ver Seccion Decisiones pendientes del .tex).

## Sanitizacion aplicada antes de integrar

- Se verifico que no contiene secretos, tokens, correos, rutas absolutas ni datos personales.
- Se verifico LF, sin BOM, sin espacios al final.
- Version purgada: v1.1.0-CANDIDATE NO se integra, solo v1.2.1-CANDIDATE.
- Hash verificado despues de sanitizar: 905be608cb58b1944c64b874002ec7793b13f62534b371e71eb4872fad55461a

## Licencia

Al integrarse en akadi-hermetic-mvp, el archivo queda bajo la licencia del
repositorio (AGPL-3.0-or-later) salvo que el custodio declare otra cosa por
escrito. El nombre AKADI sigue custodiado segun README.
